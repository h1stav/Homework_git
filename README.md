#      JSON 
# (JSON репозиторий)

1. _Создаем внешний репозиторий c названием JSON._

`Repositories --> New --> Repos Name:JSON --> Check "Add a README file" --> Press "Create repository"`

2. _Клонировать репозиторий JSON на локальный компьютер_ 

`git clone <repository HTTPS>`

3. _Внутри локального JSON создать файл "new.json"_

`touch new.json`

4. _Добавить файл под гит_ 

`git add .` или `git add new.json`

5. _Закоммитить файл_

`git commit -m "любой коментарий"`

6. _Отправить файл на внешний GitHub репозиторий_

`git push`

7. _Отредактировать содержание файла “new.json” написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата)

`vim new.json ---> input data ---> esc ---> enter ":wq"`

8. _Отправить изменения на внешний репозиторий_

`git commit -m "любой коментарий" && git push

Создать файл preferences.json === touch preferences.json
В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) === vim preferences.json ---> insert data ---> esc ---> enter ":wq"
Создать файл skills.json === touch skills.json
Отправить сразу 2 файла на внешний репозиторий === git add . && git commit -m "comment" && git push
На веб интерфейсе создать файл bug_report.json === Add file --> Create new file --> Name: bug_report.json
Сделать Commit changes (сохранить) изменения на веб интерфейсе === Commit New File
На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON === Choose bug_report.json --> Edit this file
Сделать Commit changes (сохранить) изменения на веб интерфейсе === Commit changes
Синхронизировать внешний и локальный репозиторий JSON === git pull
