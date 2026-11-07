# ReaCut для macOS

Видеоредактор ReaCut с русским интерфейсом и ИИ-ассистентом. Здесь только готовые сборки.

## Установка (один раз)

1. Скачайте **[ReaCut-mac.dmg](https://github.com/kimurazver67/reacut-releases/releases/latest/download/ReaCut-mac.dmg)** (Mac на Apple M1–M4). Файлы `blob-*.gz` в релизе — для автообновления, их скачивать не нужно.
2. Откройте DMG и перетащите ReaCut в «Программы».
3. Программа не подписана Apple, поэтому macOS её заблокирует. Откройте Терминал и выполните:
   ```
   xattr -cr /Applications/ReaCut.app
   ```
4. Запустите ReaCut.

## Обновления

Настройки → «Проверить обновления» → «Обновить и перезапустить». Программа сама скачает новую версию, сверит контрольную сумму, заменит себя и перезапустится.

## Лицензии

ReaCut основан на [rea-capcut](https://github.com/Xiangyu-CAS/rea-capcut) (MIT). Встроенные FFmpeg и x264 распространяются по GPL-2.0-or-later, их исходники лежат в каждом релизе (`media-tool-sources.tar.gz`).
