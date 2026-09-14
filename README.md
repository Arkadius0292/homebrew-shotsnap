# Homebrew tap для ShotSnap

[ShotSnap](https://github.com/Arkadius0292/ShotSnap) — нативный скриншотер для macOS с аннотациями, локальной AI-маской секретов и OCR.

```bash
brew install --cask arkadius0292/shotsnap/shotsnap
```

Обновление: `brew upgrade --cask shotsnap` · удаление: `brew uninstall --cask shotsnap` (с настройками: `brew uninstall --zap --cask shotsnap`).

Требования: macOS 11+, Apple Silicon.

> Сборка ShotSnap подписана ad-hoc и пока не нотаризована Apple. Cask после установки снимает атрибут `com.apple.quarantine` с `ShotSnap.app`, чтобы Gatekeeper не блокировал первый запуск. Контрольная сумма архива задана в cask-файле и проверяется Homebrew при загрузке.

Cask обновляется из основного репозитория скриптом `scripts/update_homebrew_cask.sh`.
