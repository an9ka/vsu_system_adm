# Лекции Систем. Админ.
7.09 Лекция 1.

Есть разные варианты интерфейса:
bourne shell (sh)
zsh
csh
ksh (korn’s shell)
bourne again shell (bash)
dash

Управление ОС за пределами утилит.
cli (bash / powershell)
WEB интерфейсы (cockpit/???)

Shell 
Это интерфейс между пользователем и ОС для доступа к сервисам операционной системы. Это может быть GUI или CLI (интерфейс командной строки).

SH
sh (или командный язык оболочки) - это язык программирования, описанный POSIX стандарт. Он имеет множество реализаций (ksh88, dash,...). bash также может быть рассматривается реализация sh.

BASH
bash начался как sh -совместимая реализация (хотя он предшествует стандарту POSIX на несколько лет), но со временем он приобрел много расширений. Многие из этих расширений могут изменять поведение действительных сценариев оболочки POSIX, поэтому сам по себе bash не является допустимой оболочкой POSIX. Скорее, это диалект языка оболочки POSIX.

bash поддерживает переключатель --posix, что делает его более совместимым с POSIX. Он также пытается имитировать POSIX при вызове sh.
