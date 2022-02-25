### **GitHub HW_2**

1. На локальном репозитории сделать ветки для:Postman,Jmeter,CheckLists,Bug Reports,SQL,Charles,Mobile testing

В приложении ***git bash*** войти в ранее сохраненную ветку или склонировать нужную ветку на локальный комьютер командой ***git clone ссылка на ветку***,а затем войти в нее. Последовательно ввести команды:<br>
- ***git branch Postman***<br>
- ***git branch Jmeter***<br>
- ***git branch Checklists***<br>
- ***git branch Bug_Reports***<br>
- ***git branch SQL***<br>
- ***git branch Charles***<br>
- ***git branch Mobile_testing***

2. Запушить все ветки на внешний репозиторий:<br>
a) При добовлении веток поочередно:
***git push удаленный-репозиторий ветка*** - (***e.g git push https://github.com/anastasiya-pv/Testing.git Postman***) <br> или
***git push -u origin ветка - (e.g. git push -u origin Jmeter)***<br>
б) при добавлении всех веток: ***git push --all -u***

3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта:
Перейти в ветку ***Bug_Reports*** с помощью команды ***git checkout Bug_reports → touch The_structure_of_bug_report.txt → vim The_structure_of_bug_report.txt→ i***→ <br>
***A bug report template should contain the following fields:***<br>
***1.Title:***<br>
***2.Bug ID:***<br>
***3.Device:***<br>
***4.Version:***<br>
***5.Severity:***<br>
***6.Priority:***<br>
***7.Assigned to:***<br>
***8.Reported by:***<br>
***9.Description:***<br>
***10.Steps to Reproduce:***<br>
***11.Expected Result:***<br>
***12.Actual result:*** <br>
***13.Attachments(if it's required)*** <br>
Нажимем клавишу ***"ESC"→:wq→*** нажимем клавишу ***"Enter"***
4. Запушить структуру багрепорта на внешний репозиторий: ***git add The_structure_of_bug_report.txt && git commit -m "adding The_structure_of_bug_report.txt file" → git push***

5. Вмержить ветку Bug Reports в Main: ***git checkout main → git merge Bug_Reports***
6. Запушить main на внешний репозиторий: ***git push***
7. В ветке Checklists набросать структуру чек листа:<br> 
Перейти в ветку ***Checklists*** с помощью команды ***git checkout Checklists →   cat > checklists.txt →*** <br>

A Checklist is a catalog of items/tasks that are recorded for tracking. This list could be either ordered in a sequence or could be haphazard.Thus, there is no concrete structure of checklists for software testing, but usually they  contain a list of blocks, sections, pages, other elements that should be tested and marked with the one of following statuses -  ***"Passed/Ok"/"Failed"/"Blocked"/"skipped"/"Not run***"*** and so on.

Look at the example of  registration form checklist below:<br>
| Tested item | Result |  
|-----------|:-----------:|
|1. Verify that the Registration form contains Username, First Name, Last Name, Password, Confirm Password, Email Id, Phone number, Date of birth, Gender, Location, Terms of use, Submit, Login (If you already have an account) | Passed ☑  |   
|2. Verify that all the fields such as Username, First Name, Last Name, Password and other fields have a valid placeholder | Passed ☑ | 
|3. Verify that all the required/mandatory fields are marked with * against the field | Passed ☑ | 
|4. Verify that clicking on submit button after entering all the mandatory fields, submits the data to the server | Passed ☑ | 
|5. Verify that system generates a validation message when clicking on submit button without filling all the mandatory fields. | Passed ☑ | 
|6. Verify that entering blank spaces on mandatory fields lead to validation error | Passed ☑ | 
|7. Verify that case sensitivity of Username | Failed ❎ | 
|8. Verify that system generates a validation message when entering existing username | Passed ☑ |   
|9. Verify that the character limit in all the fields (mainly username and password) based on business requirement| Passed ☑| 
|10. Verify that the username validation as per business requirement (in some application, username should not allow numeric and special characters)| Passed ☑ | 
|11. Verify that the validation of all the fields are as per business requirement| Passed ☑  | 
|12. Verify that the “terms and conditions” checkbox is unselected by default (depends on business logic, it may be selected or unselected)| Passed ☑ | 
|13.  Verify that the password is in encrypted form when entered|Failed ❎ | 

Используем сочетание клавиш **"CTRL+C"** для того, чтобы прервать процесс ввода данных в документ.

8. Запушить структуру на внешний репозиторий: ***git add The_structure_of_checklist.txt && git commit -m "adding The_structure_of_checklist.txt file" → git push***
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main: открыть на [гитхабе](https://https://github.com/) нужный репозиторий, сверху экрана нажать зеленую клавишу ***"Compare& pull request"*** → установить порядок веток,где 1 -это ветка в которую произойдет мержд, а 2  - это  ветка, из которой добавить комментарий, нажать ***"create pull request"*** → нажать ***"merge pull request"*** → в новом окне нажать на кнопку ***"Сonfirm merge"***, при необходимости оставить комментарий.  
10. Синхронизировать внешнюю и локальную ветки Main:  ***git checkout main → git pull***
