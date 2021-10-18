# Система контроля версий

***Cистема контроля версий (VCS)*** — программное обеспечение для облегчения работы с изменяющейся информацией.
* Полная история изменений каждого файла за длительный период. Это касается всех изменений, внесенных огромным количеством людей за долгие годы. Изменением считается создание и удаление файлов, а также редактирование их содержимого. Различные инструменты VCS отличаются тем, насколько хорошо они обрабатывают операции переименования и перемещения файлов. В историю также должны входить сведения об авторе, дата и комментарий с описанием цели каждого изменения. Наличие полной истории позволяет возвращаться к предыдущим версиям, чтобы проводить анализ основных причин возникновения ошибок и устранять проблемы в старых версиях программного обеспечения.
* Ветвление и слияние. Создание «веток» позволяет иметь несколько независимых друг от друга направлений разработки, а также выполнять их слияние, чтобы разработчики могли проверить, что изменения, внесенные в каждую из веток, не конфликтуют друг с другом. Многие команды разработчиков программного обеспечения создают отдельные ветки для каждой функциональной возможности, для каждого релиза либо и для того, и для другого.
* Отслеживаемость. Возможность отслеживать каждое изменение, внесенное в программное обеспечение, и связывать его с ПО для управления проектами и отслеживания ошибок. История с комментариями во время чтения кода помогает понять, что этот код делает и почему действие реализовано именно таким образом. Благодаря этому разработчики могут вносить корректные и совместимые изменения в соответствии с долгосрочным планом разработки системы. dd
Подготовка к работе
Подготовка к работе
1.	Скачать и установить VS Code [отсюда](https://code.visualstudio.com/docs/?dv=win)
2.	Скачать и установить Git [по ссылке](https://git-scm.com/download/win)
3.	Проверить, работает ли git  с помощью команды 
git --version
4.	Добавить имя и email пользователя с помощью команд
  git config --global user.email "email@mail.com"
  git config --global user.name "User Name"

# Команды 

## *git init*
>Команда git init создает в директории пустой репозитарий в виде директория .git, где и будет в дальнейшем храниться вся информация об истории коммитов.

## *git add*
>Следующее, что нужно знать — команда git add. Она позволяет внести в индекс — временное хранилище — изменения, которые затем войдут в коммит.

## *git status*
>Команда git status, пожалуй, можно считать самой часто используемой наряду с командами коммита и индексации. Она выводит информацию обо всех изменениях, внесенных в дерево  директорий проекта по сравнению с последним коммитом рабочей ветки; отдельно выводятся внесенные в индекс и неиндексированные
файлы.

## *git log*
>Иногда требуется получить информацию об истории коммитов, коммитах, изменивших отдельный файл; коммитах за определенный отрезок времени и так далее. Для этих целей используется команда git log.

## *git commit*
>Коммиты — базовое понятие во всех системах контроля версий, >
## *git checkout*
>Команда git checkout позволяет переключаться между последними >коммитами (если упрощенно) веток

**added on github**