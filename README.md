 Создать внешний репозиторий c названием XML.

 22. Клонировать репозиторий XML на локальный компьютер.
git clone https://github.com/Freazybeat/XML.git
 23. Внутри локального XML создать файл “new.xml”.
touch new.xml
 24. Добавить файл под гит.
git add .
 25. Закоммитить файл.
 git commit -m "add xml on repository"
 26. Отправить файл на внешний GitHub репозиторий.
 git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
vim new.xml
 28. Отправить изменения на внешний репозиторий.
git status
git add new.xml
git commit -m "add info in file"
git push
 29. Создать файл preferences.xml
touch preference.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
vim preference.xml
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
touch skills.xml
 vim skills.xml
 32. Сделать коммит в одну строку.
git add preference.xml skills.xml
$ git commit -m "add file1 , add file2"
 33. Отправить сразу 2 файла на внешний репозиторий.
$ git push
 34. На веб интерфейсе создать файл bug_report.xml.

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.


 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 38. Синхронизировать внешний и локальный репозиторий XML
$ git fetch
$ git pull
