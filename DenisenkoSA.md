# Git manual.
----
## Конфигурация:

Указать имя пользователя: ***git config --global user.name 'name'***

Указать адрес электронной почты: ***git config --global user.email 'mail'***

----

## Основные команды

Узнать версию git: ***git --version***.

Создать новый репозиторий: ***git init***

Узнать статус репозитория: ***git status***

Отслеживать файл: ***git add***

Отслеживать все файлы: ***git add .***

Зафиксировать изменения: ***git commit***

Отобразить список изменений (commit): ***git log***

Переключиться на выбранный список изменений: ***git checkout \<number commit\>***

Отобразить разницу между текущей версий документа и зафиксированной: ***git diff***

----

## Ветвление

Создать новую ветку: ***git branch***

Переключиться на другую ветку: ***git checkout***

Объеденить ветки: ***git merge \<branch name\>***

Принудительное удаление указанной ветки:  ***git branch -d \<branch name\>***

Посмотреть предпоследний коммит: ***git checkout \<branch\>^</branch>***

Список всех веток: ***git branch --all***

----

## Удаленный репозиторий

Клонировать репозиторий: ***git clone***

Добавить удаленный репозиторий: ***git remote***

Отправить файлы в удаленный репозиторий: ***git push***

Загрузить файлы из удаленного репозитория: ***git pull***