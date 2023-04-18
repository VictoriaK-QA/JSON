# JSON
### GIT   HW#1_JSON

 1. Создать внешний репозиторий c названием JSON  
 
 <b>GitHub</b> <code> <b>+ New repository</b> </code>
 - [X] Public
 - [X] Add a README file

 <code> <b>Create repository</b> </code>

 2. Клонировать репозиторий JSON на локальный компьютер 
 
  <code> <b>git clone git@github.com:VictoriaK-QA/JSON.git</b> </code>

 3. Внутри локального JSON создать файл “new.json” 
 
 <code> <b>cd JSON/</b> </code>  <code> <b>touch new.json</b> </code>

 4. Добавить файл под гит 
 
  <code> <b>git add .</b> </code>

 5. Закоммитить файл 
 
  <code> <b>git commit -m "new file"</b> </code>

 6. Отправить файл на внешний GitHub репозиторий 
 
  <code> <b>git push</b> </code>
  
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON 
 
  <code> <b>vim new.json</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```json
 {
	"name": "Виктория",
	"age": 28,
	"pet": 1,
	"salary": 300
  }
 ```
 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>

 8. Отправить изменения на внешний репозиторий 
 
 <code> <b>git commit -am "new file"</b> </code> <b>git push</b> </code>
  
 9. Создать файл preferences.json 
 
 <code> <b>touch preferences.json</b> </code>

 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON 
 
 <code> <b>vim preferences.json</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```json
 {
	"favorite_movie": "The Godfather",
	"favorite_sitcom": "Friends",
	"favorite_food": "pasta",
	"favorite_season": "autumn",
	"country_to_travel": "Italy"
 }
  ```
 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>
 
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
 
 <code> <b>touch skills.json</b> </code>

 <code> <b>vim skills.json</b> </code>

 <b>Нажать</b> <code> <b>i</b> </code>
 ```json
 {
	"skills":["Testing Theory", "Client server", "SQL", "Postman", "Charles Fiddler Sniffing", "Web Services", "Git Linux Terminal", "DevTools", "Mobile Testing", "Web Testing", "Load testing"]
 }
 ```

 <b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>
  
 12. Отправить сразу 2 файла на внешний репозиторий 
 
 <code> <b>git add .</b> </code>

 <code> <b>git commit -m "info about skills and preferences"</b> </code> 
 
 <code> <b>git push</b> </code>

 13. На веб интерфейсе создать файл bug_report.json 
 
 <b>Нажать</b> <code> <b>Add file</b> </code> + <code> <b>Create new file</b> </code> 

 <b>Имя файла bug_report.json</b>

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 
 <b>Нажать</b> <code> <b>Commit new file</b> </code>

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON 
 
 <b>Нажать</b> <code> <b>Edit this file</b> </code>

 ```json
 {
  "ID": "BR-14",
  "Title": "What?Where?When?",
  "Severity": "Minor",
  "Priority": "Medium", 
  "Precondition": "Preparation steps",
  "Environment": "Devices",
  "STR": "Steps to restore",
  "ER": "Expected result",
  "AR": "Actual Result",
  "Attachment": "link"
 }
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе 
 
 <b>Нажать</b> <code> <b>Commit changes</b> </code>

 17. Синхронизировать внешний и локальный репозиторий JSON 
 
 <code> <b>git pull</b> </code>
