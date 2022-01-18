# GIT
* git clone url repo  - клонируем репозиторий на локальную машину
* git init - создаем локально репозиторий , для дальнейшей работы
* git status - проверяем статус репозитория, какие изменения есть, что не закомичено
* git add name file/folder or git add .  - добавляем в локальный репо документ/папку и все сразу 
* git commit -m "комментарий" - делаем коммит( комментарий) , чтобы отслеживать историю изменений и можно было делать откаты
* git remote add origin Url repo - связываем локальный репозиторий с удаленным 
* git push -u origin main - заливаем локальные измененения в удаленный репо
* git remote -v - проверяем с каким удаленным репо есть связь, куда можно будет залить
* git pull - с удаленного репо заливаем коммиты( изменения) в локальные репо
*git branch "название ветки" - создаем новую ветку
* git checkout - проверяем какие есть ветки и где мы сейчас
* git checkout "название ветки" - перходим на нужную ветку
* git merge "название ветки" - сливаем изменения на мастер ( должны находиться на  мастере) 
* git log - посмотреть коммиты

плюс есть много флагов, которые можно добавлять к командам 
* git help - показывает варианты команда с описанием 

