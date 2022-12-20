# Инструкция по работе с Git

## Что такое git?
**Git** - это наиболее популярная реализаия распределенной системы контроля версий. Самая популярная реализация **Git** - [это GitHub] (https://github.com/)

## Подготовка репозитория
Для создания репозитория используется команда "git init". Для этого необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале с папкой написать команду "git init"

## Создание коммита
Для создания коммита используется команда "git commit". Для этого в терминале с папкой репозиторием необходимо написать *git commit -m <сообщение к коммиту>*. Cообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***.

### добавление файла к коммиту
для добавления к будущему коммиту используется команда "git add". Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Создание коммитов
Для этого необходимо выполнить две команды: Первая команда: git add - добавляет все измененные данные в файл. А вторая команда создает коммит: git commit -m "Commit message."

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в терминале с папкой-репозиторием необходимо написать *git log*.

## Перемещение между коммитами
Для перемещения на предыдущие коммиты используется команда *git checkout*. Для этого необходимо в журнале изменений, как показано в предыдущей части, найти необходимый коммит и его номер. После чего в терминале с папкой-репозиторием написать команду *git checkout <номер коммита>*. После применения этой команды вы попадете в состояние **Detached head**. в котором никакние изменения фиксироваться не будут. Для возврата в обычное состояние необходимо написать команду *git checkout master*.

## Ветки в Git
Ветки - как черновики в Git, создав ветку мы можем как второй вариант оставить, также показав коллеге или начальнику мы можем убедиться в том, что можно продолжать или удалить, при этом оригинал держать в чистом варианте. 
1) Для проверки количество веток нужно в терминале ввести: *git branch*. 
2) Для создания новой ветки: *git branch +название ветки*
3) Для перемещения между ветками: *git checkout +название ветки*

## Слияние веток и разрешение конфликтов
Для слияния веток, нужно находиться в ветке master (или в нужной вам ветке), затем в терминале вводим: *git merge +название ветки*

## Удаление веток
Для удаления ненужной ветки, нужно в терминале ввести: *git branc -d +название ветки*. **Главное не забудьте перед этим проверить, все ли перевели или точно нужно удалять?)**

## Git status
Для того чтобы посмотреть текущее состояние ветки, например, какие файлы добавлены или не добавлены для создания commit, можно выполнить команду: *git status*

## Git diff
Просмотреть изменения относительно двух веток можно командой: *git diff*


>PS: Updated HomeWork