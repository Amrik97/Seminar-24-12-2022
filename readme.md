# инструкция по работе с Git

## Что такое git?
**Git** - это наиболее популярная реализаия распределенной системы контроля версий. Самая популярная реализация **Git** - [это GitHub] (https://github.com/)

## Подготовка репозитория
Для создания репозитория используется команда "git init". Для этого необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале с папкой написать команду "git init"

## Создание коммита
Для создания коммита используется команда "git commit". Для этого в терминале с папкой репозиторием необходимо написать *git commit -m <сообщение к коммиту>*. Cообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***.

### добавление файла к коммиту
для добавления к будущему коммиту используется команда "git add". Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммитов

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*.

## Перемещение между коммитами
Для перемещения на предыдущие коммиты используется команда *git checkout*. Для этого необходимо в журнале изменений, как показано в предыдущей части, найти необходимый коммит и его номер. После чего в терминале с папкой-репозиторием написать команду *git checkout <номер коммита>*. После применения этой команды вы попадете в состояние **Detached head**. в котором никакние изменения фиксироваться не будут. Для возврата в обычное состояние необходимо написать команду *git checkout master*.


## Ветки в Git

## Слияние веток и разрешение конфликтов

## Удаление веток