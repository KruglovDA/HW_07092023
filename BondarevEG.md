## Привет!

Аксельрод красивый пёс

Абсолютно верно

1. Уже был аккаунт на гитхаб
2. Создал локальный репозиторий
3. "Подружил" мой локальный и удаленный репозиторий. Гидхаб при создании нового репозитория подскажет как это можно сделать.
4. Отправил push ваш локальный репозиторий в удаленный на гидхаб, при этом мне, возможно нужно будет авторизоваться на удаленном репозиторий
5. Провести изменения "с другого компа"
6. Выкачать pull актуальное состояние из удаленного репозитория.

# Как дернуть проект другого спеца гите? 
## Инструкция

1. делаем форк (fork) проекта который нам нужен
2. делаю git clone для нашей версии этого репозитория
3. создаю ветку с предлогаемыми изменениями 
4. производим все изменения только в этой ветке
5. отправляем эти изменения на свой аккаунт (push)
6. в окне на гитхаб появляется возможность отправить pull request


## Запишу дополнительные команды для дополнительного касания

1. git branch -f main HEAD~3 - перемещение веток, переместит ветку main на 3 родителя назад от HEAD
2. git reset - отмена изменений, (локальная версия)
3. git revert - для командной работы, это команда создает новый коммит "С2" содержит изменения полностью противоположные тем что сделаны в "С2"
4. git clone "link"  - клонирует репозиторий
5. git pull - скачивает все удаленного с удаленного репозитория
6. git push - отправляет с локального репозитория на удаленный
7. git rebase - копирует набор коммитов и переносит в другое место, преимущество - можно делать чистые и красивые линейные последовательности коммитов
8. git checkout -b "case" - создание ветки и переход в нее
8.1 git checkout branch "name" - имя ветку на которую хотим переключится
9. git merge "name" - сливание веток c текущей
10. git log --graph - выводит дерево коммитов
11. git init - инициализация репозитория
12. git diff - показать разницу всех коммитов, показывает разницу между текущим файлом и сохраненным
13. git commit -a -m "name" - название изменений *пункт 20 и 21 в одной команде*
14. git log - показать все коммиты (журнал изменений) 
15. git checkout "name" - переключение на другую ветку, для работы нужно указать название ветки
16. git branch - выводит список веток репозиториев
17. git branch "name" - создание новой ветки
18. git branch -d "name" - удаляем ветку с именем "name"
19. git status - получить информацию от git о текущем состоянии
20. git add "name" - добавить файл или файлы к следующему коммиту
21. git commit -m "message" - создание коммита


## Синтаксис

1. **жирный текст** или __вот тоже можно__
2. *курсивный текст* или _вот так_
3. ~~зачеркнутый текст~~
4. #заголовки#
5. Заголовок первого уровня  Заголовок второго уровня
   =======================   ****
1, 2, 3, -нумерованные списки, это было не обязательно :)


ps для быстрого сохранения исполльзуется сочетание клавишь ctrl+s