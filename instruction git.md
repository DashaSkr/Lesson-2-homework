# _**Инструкция для работы с Git и удалёнными репозиториями**_

***
![Git](git.png)

## Что такое Git?
_**Git**_ - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
___ 
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду _**git init**_  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)
**** 
## Создание коммитов

> ### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

>### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

>### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
***
## **Перемещение между сохранениями**
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## **Журнал изменений**
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием
___
## _**Ветки в Git**_

>## Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

>## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

>## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"
___
**Также информацию можно получить, перейдя по ссылке**:
[инструкция Git](https://habr.com/ru/post/541258/ "перейти по ссылке")