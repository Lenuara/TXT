# TXT
1. Создать внешний репозиторий c названием TXT. 
    * Войти в свой профиль на https://github.com/ 
    * Зайти в раздел Repositories
    * Нажать кнопку New 
    * Указать:
       * Repository name "TXT"
       * Radiobutton "Private"
       * Checkbox "Add a README file"
    * Репозиторий [TXT](https://github.com/Lenuara/TXT) создан, его имя появилось в списке репозиториев 
2. Клонировать репозиторий TXT на локальный компьютер.  
    `cd ~/LearningQA/LearnGIT/`  
    `git clone https://github.com/Lenuara/TXT.git`
3. Внутри локального TXT создать файл “new.txt”  
    `cd TXT`  
    `touch new.txt`
4. Добавить файл под гит.  
    `git add new.txt`
5. Закоммитить файл.  
    `git commit -m "Add new.txt"`
6. Отправить файл на внешний GitHub репозиторий.  
    `git push`
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
    `vim new.txt`
8. Отправить изменения на внешний репозиторий.  
    `git add new.txt`  
    `git commit -m "Edited new.txt"`  
    `git push`
9. Создать файл preferences.txt  
    `touch preferences.txt`
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.  
    `vim preferences.txt`
11. Создать файл sklls.txt, добавить информацию о скиллах которые будут изучены на курсе в формате TXT   
    `vim sklls.txt`
12. Сделать коммит в одну строку.  
    `git add . && git commit -m "Add preferences.txt and sklls.txt"`
13. Отправить сразу 2 файла на внешний репозиторий.  
    `git push`
14. На веб интерфейсе создать файл bug_report.txt.  
   На вкладке репозитория нажать Add file -> Create new file -> Name your file... -> bug_report.txt
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
   Нажатием на кнопку Commit new file сохранить изменения
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.  
   Зайти в файл bug_report.txt  
   Нажать пиктограмму Edit this file
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
    Нажать Commit changes
18. Синхронизировать внешний и локальный репозиторий TXT  
   `git pull`

