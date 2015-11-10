# Sublime Text 3 для работы с фронтэндом

Качать на [официальном сайте](http://www.sublimetext.com/3) и сразу ставить [Package Control](https://packagecontrol.io/installation).


## Содержимое репозитория

### Шпаргалка по горячим кнопкам

[Шпаргалка](http://nicothin.github.io/sublime-text/sublime-text-3-hotkeys.html) по горячим кнопкам Sublime Text 3 для Windows/Linux и OS X. Автономный html-файл с поиском-фильтром.


### Настройки, оформление, макросы

Папка `Packages` повторяет папку с настройками установленного ST3, чтобы ее открыть: Preferences → Browse Packages.

```
Packages/
  User/
    Default (Windows).sublime-keymap    — пользовательские настройки горячих клавиш в Win/Linux
    Emmet.sublime-settings              — настройки Emmet-а
    macros_add_class.sublime-macro      — макрос добавления атрибута class
    macros_add_sk.sublime-macro         — макрос добавления фигурных скобок
    Preferences.sublime-settings        — комментированный файл настроек
  nicothin.tmTheme                      — тема оформления
  russian_english.aff                   — файл для проверки орфографии
  russian_english.dic                   — файл для проверки орфографии
```


## Дополнения для Sublime Text

Как установить: <kbd>Ctrl + Shift + P</kbd> (покажет список всех команд ST3), набрать `inst`, чтобы быстро найти команду `Package Control: Install Package`, <kbd>Enter</kbd>, в появившемся списке всех возможных к установке дополнений начать набирать часть имени дополнения, когда оно найдено — <kbd>Enter</kbd>.


### Необходимый минимум

- [Emmet](https://packagecontrol.io/packages/Emmet) — сильно ускоряет набор при помощи аббревиатур
- [AutoFileName](https://packagecontrol.io/packages/AutoFileName) — выдает подсказки при подключении файлов
- [Sidebar Enhancements](https://packagecontrol.io/packages/SideBarEnhancements) — расширяет возможности сайдбара
- [LESS](https://packagecontrol.io/packages/LESS), [SCSS](https://packagecontrol.io/packages/SCSS), [Stylus](https://packagecontrol.io/packages/Stylus) — дополнения для подсветки синтаксиса CSS-препроцессоров
- [Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter) — подсветка цвета, если курсор внутри указания цвета


### Необязательные

- [Bracket​Highlighter](https://packagecontrol.io/packages/BracketHighlighter) — подсвечивает строки с открывающей и закрывающей скобками
- [AlignTab](https://packagecontrol.io/packages/AlignTab) — добавляет в контекстное меню возможности выравнивания
- [Can I Use](https://packagecontrol.io/packages/Can%20I%20Use) — добавляет в контекстное меню справку с caniuse.com
- [PlainTasks](https://packagecontrol.io/packages/PlainTasks) — ведение списка задач в виде файла
