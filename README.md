# Termobox

Терминал для macOS на Apple Silicon (до версии 0.9.5 назывался NovaTerm). В этом репозитории только выпуски: образы DMG,
подписанные Developer ID и нотаризованные Apple. Исходного кода здесь нет, он закрыт.

A terminal for Apple Silicon Macs (called NovaTerm up to version 0.9.5). This repository holds releases only: disk images signed
with Developer ID and notarized by Apple. The source code is closed and is not here.

## Скачать / Download

**[Termobox для Mac (последняя версия) / latest version](https://github.com/snemesh/Termobox-releases/releases/latest/download/Termobox-arm64.dmg)**

Все версии и их изменения: [Releases](https://github.com/snemesh/Termobox-releases/releases).

- Нужен Mac на Apple Silicon (M1 и новее) и macOS 13 или новее.
  Requires an Apple Silicon Mac (M1 or later) and macOS 13 or later.
- Откройте DMG и перетащите Termobox в «Программы».
  Open the DMG and drag Termobox to Applications.
- У каждого выпуска есть файл `.sha256`; проверить образ / verify the image:

  ```sh
  shasum -a 256 -c Termobox-X.Y.Z-arm64.dmg.sha256
  ```

## Сторонние компоненты / Third-party software

Termobox включает открытые компоненты: библиотеки Rust (лицензии MIT, Apache-2.0, Zlib,
BSD-2-Clause, ISC, Unicode-3.0) и шрифт JetBrains Mono (SIL Open Font License 1.1). Полные
тексты их лицензий и уведомлений лежат в файле `THIRD-PARTY-NOTICES.txt`: на образе рядом
с приложением, внутри приложения (`Termobox.app/Contents/Resources`) и в каждом выпуске.

Termobox includes open-source components: Rust libraries (MIT, Apache-2.0, Zlib,
BSD-2-Clause, ISC, Unicode-3.0 licences) and the JetBrains Mono font (SIL Open Font
License 1.1). Their full licence texts and notices are in `THIRD-PARTY-NOTICES.txt`: on the
disk image next to the app, inside the app (`Termobox.app/Contents/Resources`), and attached
to every release.

## Лицензия / Licence

© 2026 the author of Termobox. Все права защищены / All rights reserved.
Termobox — проприетарная программа; её исходный код не публикуется.
Termobox is proprietary software; its source code is not published.
