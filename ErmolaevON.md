# Руководство пользователя Git
## Основные команды
* git init - инициализация репозитория;
* git status - сообщает статус репозитория.

## Работа с ветками
* git branch - отображение всех имеющихся веток;
* git branch branch_name - создание новой ветки с именем __branch name__.

## Работа с репозиториями

* git fetch - связывается с удалённым репозиторием и забирает из него все изменения, которых у вас пока нет и сохраняет их локально;

* git clone <ссылка на репозиторий> <название папки> - клонирует выбранный репозиторий и скопирует в указанную папку (опционально);

* git pull - работает как комбинация команд git fetch и git merge, т.е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

* git push - используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.

## Пример работы с репозиториями

### Создание локального репозитория
* $git clone git@github.com:drnextgis/openlayers.git

* $cd openlayers

* $git remote add upstream  git://github.com/openlayers/openlayers.git

### Обновление локального репозитория
* $git pull upstream master

### Создаем ветку
* git checkout -b feature #Создаёт новую ветвь, названную "feature" и делает её активной

### Коммиты
* $git commit -a -m "message"

### Обновление удаленного репозитория
* $git push origin feature #Загружает изменения в текущей ветви в origin в ветвь feature

#### Справочные комманды
* $git show  
* $git log   
* $git diff

#### Так же можно удалить ветку, в которой велась разработка:  
* git branch -d feature #В локальном репозитории   
* git push origin :feature #В удалённом репозитории
