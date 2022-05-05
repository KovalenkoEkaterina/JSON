# JSON
1. Создать внешний репозиторий c названием JSON ===
Create a new repository-Json

 2. Клонировать репозиторий JSON на локальный компьютер ===
git clone 

 3. Внутри локального JSON создать файл “new.json” ===
cat > new.json

 4. Добавить файл под гит ===
git add new.json

 5. Закоммитить файл ===
git commit -m "new.json"

 6. Отправить файл на внешний GitHub репозиторий ===
git push

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON ===
vim new.json
{
        "Full name" : "Kovalenko Ekaterina Sergeevna",
        "Age" : "25",
        "Pet name" : "Simba",
        "Salary" : "60000"
}

 8. Отправить изменения на внешний репозиторий ===
git add new.json
git commit -m "new"
git push

 9. Создать файл preferences.json ===
cat > preferences.json

 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON ===
vim preferences.json
{
        "My favorite movie" : "A Dog’s Purpose",
        "My favorite serial" : "Friends",
        "My favorite food" : "Sushi",
        "My favorite season" : "Summer",
        "What country would I like to visit?" : "America"
}



 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON ===
vim skills.json
{ 
       "Skills" : "HTTP Methods", "API", "Postman", "Charles", "Android Studio", "Jmeter"
}

12. Отправить сразу 2 файла на внешний репозиторий ===
git add .
git commit -m "add new files"
git push

 13. На веб интерфейсе создать файл bug_report.json ===
add file
creat new file

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе ===
commit changes

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON ===
 
{
   "Bug report" : "Title/Bug ID", "Environment", "Steps to reproduce a Bug", "Expected result", "Actual result", "Visual Proof", Severity/Priority
}

 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе

 17. Синхронизировать внешний и локальный репозиторий JSON ===
git pull
