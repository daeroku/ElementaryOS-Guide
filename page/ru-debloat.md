# ElementaryOS - Удаление всего ненужного в системе (Деблоат)
------
## Готовый скрипт для удаления всего ненужного*
```bash
bash <(curl -s )
```
###### *Данный скрипт удаляет приложения Код, Обратная связь, Веб-браузер Epiphany, Просмотрщик документов Evince, Камера, Музыка, Видео и приложение с окошком горячих клавиш. (Но не такие они горячие как я))
------
## Удаление вручную всего ненужного
#### Удаление приложение Код
```bash
sudo apt remove io.elementary.code
```
#### Удаление приложение Обратная связь
```bash
sudo apt remove io.elementary.feedback
```
#### Удаление приложение Горячие клавишы
```bash
sudo apt remove io.elementary.shortcut-overlay
```
#### Удаление всех остаточных ненужных пакетов
```bash
sudo apt autoremove
```
#### Удаление браузера Epiphany
```bash
flatpak remove epiphany
```
#### Удаление просмотрщика документов Evince
```bash
flatpak remove evince
```
#### Удаление камеры
```bash
flatpak remove io.elementary.camera
```
#### Удаление музыка
```bash
flatpak remove io.elementary.music
```
#### Удаление видео
```bash
flatpak remove io.elementary.videos
```
#### Запустите процесс обновления
```bash
sudo apt update && sudo apt upgrade && flatpak update
```
