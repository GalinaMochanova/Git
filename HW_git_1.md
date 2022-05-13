# GIT Homework 1


**JSON**

 1. Создать внешний репозиторий c названием JSON.
 2. Клонировать репозиторий JSON на локальный компьютер 
 ``` 
 git clone https://github.com/GalinaMochanova/JSON.git
 ```
 3. Внутри локального JSON создать файл “new.json”
 ``` 
 cd json
 touch new.json
 ```
 4. Добавить файл под гит
   ```
 git add new.json
  ```
 5. Закоммитить файл
   ```
         git commit -m 'add new.json'
 ```
 6. Отправить файл на внешний GitHub репозиторий
  ``` 
         git push
   ```
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:
 ```
 vim new.json
 
 i
 
 {
        "first_name": "Galina",
        "last_name": "Molchanova",
        "age": 31,
        "number_of_pets": 1,
        "salary": 500
}
esc
:wq
```
 8. Отправить изменения на внешний репозиторий
 ```
 git commit -am "add json to new.json"
 git push
 ```
 9. Создать файл preferences.json
 ``` 
  touch preferences.json
  ```
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:
  ```
 vim preferences.json
 i
 {
        "favorite_movie": "What_dreams_may_come",
        "favorite_series": "Friends",
        "favorite_food": "meat",
        "favorite_season": "spring",
        "country": "Germany"
}
esc
:wq
 ```
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON:
  ```
 touch skills.json
 vim slills.json
 i
 
 {
        "skill_1": "basic_theory_of_testing",
        "skill_2": "client_server_architecture",
        "skill_3": "json_xml",
        "skill_4": "Api_testing",
        "skill_5": "Devtools"
}

esc
:wq
 ```
 12. Отправить сразу 2 файла на внешний репозиторий
  ```
 git commit -am "add 2  files perferences, skills.json"
 git push
  ```
 13. На веб интерфейсе создать файл bug_report.json
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:
  ```
 {
  "field_1": :"Bug_summary", 
  "field_2": "Severity",
  "field_3": "Steps_to_reproduce",
  "field_4": "Actual_result",
  "field_5": "Expected_result"
}
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсe
 17. Синхронизировать внешний и локальный репозиторий JSON
  ```
 git pull
 ```

**XML**


 18. Создать внешний репозиторий c названием XML
 19. Клонировать репозиторий XML на локальный компьютер
  ```
  git clone https://github.com/GalinaMochanova/XML.git
   ```
 20. Внутри локального XML создать файл “new.xml”
  ```
 touch new.xml
  ```
 21. Добавить файл под гит
  ```
 git add .
  ```
 22. Закоммитить файл
  ```
 git commit -m "add file new.xml"
  ```
 23. Отправить файл на внешний GitHub репозиторий
  ```
 git push
  ```
 24. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML:
  ```
 vim new.xml
 i
 <resume>
   <first_name>Galina</first_name>
   <last_name>Molchanova</last_name>
   <middle_name>Alexandrovna</middle_name>
   <age>31</age>
   <number_of_pets>1</number_of_pets>
   <salary>500</salary>
 </resume>

esc
:wq 
 ```
 25. Отправить изменения на внешний репозиторий
  ```
  git commit -am "Update file new.xml"
  git push
   ```
 26. Создать файл preferences.xml
  ```
 touch preferences.xml
  ```
 27. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:
 ```
vim preferences.xml
i

<preferences>
   <favorite_movie>What_dreams_may_come</favorite_movie>
   <favorite_series>Friends</favorite_series>
   <favorite_food>meat</favorite_food>
   <favorite_season>spring</favorite_season>
   <country>Germany</country>
</preferences>

esc
:wq
 ```

 28. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
  ```
 touch slills.xml
 vim skills.xml
 i
 
 <skills>
   <skill_1>basic_theory_of_testing</skill_>
   <skill_2>client_server_architecture</skill_2>
   <skill_3>json_xml</skill_3>
   <skill_4>Api_testing"</skill_4>
   <skill_5>Devtools</skill_5>
</skills>

esc
:wq
 ```
 29. Сделать коммит в одну строку:
  ```
 git commit -am "add preferences.xml, skills.xml"
  ```
 30. Отправить сразу 2 файла на внешний репозиторий
  ```
 git push
  ```
 31. На веб интерфейсе создать файл bug_report.xml
 32. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 33. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 34. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 35. Синхронизировать внешний и локальный репозиторий XML
  ```
 git pull
  ```



