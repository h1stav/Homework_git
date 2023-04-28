#      JSON 
# (JSON репозиторий)

1. _Создаем внешний репозиторий c названием JSON._

`Repositories -> New -> Repos Name:JSON -> Check "Add a README file" -> Press "Create repository"`

2. _Клонировать репозиторий JSON на локальный компьютер_ 

`git clone <repository HTTPS>`

3. _Внутри локального JSON создать файл "new.json"_

`touch new.json`

4. _Добавить файл под гит_ 

`git add .` или `git add new.json`

5. _Закоммитить файл_

`git commit -m "любой комментарий"`

6. _Отправить файл на внешний GitHub репозиторий_

`git push`

7. _Отредактировать содержание файла “new.json” написать информацию о себе в формате JSON (ФИО, возраст, количество домашних животных, будущая желаемая зарплата)._

`vim new.json -> input data -> esc -> enter ":wq"`

8. _Отправить изменения на внешний репозиторий_

`git add . && git commit -m "любой комментарий"`

`git push`

9. _Создать файл preferences.json_

`touch preferences.json`

10. _В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON_

`vim preferences.json -> insert data -> esc -> enter ":wq"`

11. _Создать файл skills.json. Добавить информацию о скиллах которые будут изучены на курсе в формате JSON_

`touch skills.json`

12. _Отправить сразу 2 файла на внешний репозиторий_

`git commit -a -m "любой комментарий" && git push`

13. _На веб интерфейсе создать файл bug_report.json_

`Add file -> Create new file -> Name: bug_report.json`

14. _Сделать Commit changes (сохранить) изменения на веб интерфейсе_

`Commit New File`

15. _На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON_

`Choose bug_report.json -> Edit this file`

16. _Сделать Commit changes (сохранить) изменения на веб интерфейсе_

`Commit changes`

17. _Синхронизировать внешний и локальный репозиторий JSON_

`git pull`
