
 <head>
  <meta charset="utf-8">
 </head>
 <body>
  <table width="100%" cellspacing="0" cellpadding="4" border="1">
  <col style="width:30%">
	<col style="width:50%">
    <h1 align="center"><B> JSON </B></h1>
   <tr>
    <th>Задания</th>
    <th>Ответы</th>
   </tr>
   <tr><td>1. Создать внешний репозиторий c названием JSON:</td><td>Открыть <a href="URL">github.com</a> как авторизированный пользователь, в поле <B><I>"Recent repositories"</I></B>  нажать зеленую кнопку <B><I>"NEW"</B></I>.В новом окне заполнить обязательные поля <B><I>"Owner"</B></I>-anastasiya-pv,<B><I>"Repository name"</B></I>-JSON,указать тип репозитория "public" или "private"(в данном примере "public"), подтвердить опцию <B><I>"add a README file".</B></I></td></tr>
   <tr><td>2. Клонировать репозиторий JSON на локальный компьютер:</td><td>В открытом репозитории нажать кнопку <B><I>"Code"</B></I>,выбрать опцию <B><I>"HTTPS"</B></I> и скопировать отобразившуюся ссылку.Открыть <a href="URL">github.com</a>, указать путь к требуемой папке, ввести <B><I>git clone <a href="URL">https://github.com/anastasiya-pv/JSON.git</a></B></I></td></tr>
   <tr><td>3. Внутри локального JSON создать файл “new.json”:</td><td>Открыть склонированный репозиторий(<B><I>cd JSON</B></I>) → <B><I>touch new.json</B></I></td></tr>
   <tr><td>4. Добавить файл под гит:</td><td><B><I>git add new.json</B></I></td></tr>
   <tr><td>5. Закоммитить файл:</td><td><B><I>git commit -m "add new.json file"</B></I></td></tr>
   <tr><td>6. Отправить файл на внешний GitHub репозиторий</td><td><B><I>git push</B></I></td></tr>
   <tr><td>7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:</td><td> <B><I>cat >> new.json</B></I>
<B><br>{"Name and Surname":"Anastasiya Papliauko",<br>
"The number of pets": "1",<br>
"Expected salary":"600$"}</br></B>
Используем сочетание клавиш <B><I>"CTRL+C"</B></I> для того, чтобы прервать процесс ввода данных в документ.
</td></tr>
   <tr><td>8. Отправить изменения на внешний репозиторий:</td><td><B><I>git add new.json -> git commit -m "new.json file editing" -> git push</B></I> 
</td></tr>
   <tr><td>9. Создать файл preferences.json:</td><td><B><I>cat > preferences.json</B></I></td></tr>
   <tr><td>10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON:</td><td><B><I>cat >> preferences.json</B></I><B><br>
{"My favorite film": "The finest hours",<br>
"My favorite serial": "The master of sun",<br>
"My favorite food": "Sushi",<br>
"My favorite season": "Summer",<br>
"What country would I like to visit": "Korea"}</B><br>
Используем сочетание клавиш <B><I>"CTRL+C"</B></I> для того, чтобы прервать процесс ввода данных в документ.</td></tr>
   <tr><td>11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON:</td><td><B><I>touch skills.json → vim skills.json → i →<br></B></I>
<B>{"Hard skills":<br> ["The basic theory of Software Testing",<br>
"Linux command line (terminal)/Git bash. GitHub",<br>
"HTTP methods, requests, responses",<br>
"JSON & XML",<br>
"API testing via POSTMAN (GET, POST, PUT, DELETE, creating variables, writing simple autotests, checking response)",<br>
"Creating Test cases, checklists, bug reports",<br>
"Test Design Technics",<br>
"Browser developer tools",<br>
"Mobile testing basics",<br>
"Android studio and ADB (android device manager)",<br>
"Charles",<br>
"Fiddler",<br>
"SQL basics (create, delete, drop, insert into, select, from, where, join)",<br>
"PostgreSQL database",<br>
"Scrum",<br>
"The basics of Python"]<br>
}<br></B>
Нажимем клавишу <B><I>"ESC"→:wq→</B></I> нажимем клавишу <B><I>"Enter"</B></I></td></tr>
   <tr><td>12. Отправить сразу 2 файла на внешний репозиторий:</td><td><B><I>git add . → git commit -m "add skills.json and preferences.json files" → git push</B></I></td></tr>
   <tr><td>13. На веб интерфейсе создать файл bug_report.json:</td><td>На <a href="URL">github.com</a> открыть репозиторий <B><I>"JSON"</B></I> → Нажать на кнопку <B><I>"Add files"</B></I>,а затем выбрать <B><I>"Create new files"</B></I> в выпадающем списке → ввести bug_report.json в поле <B><I>"name your file"</B></I></td></tr>
   <tr><td>14. Сделать Commit changes (сохранить) изменения на веб интерфейсе:</td><td>Внести пояснения к комиту<B><I>(e.g. create bug_report.json)</B></I> и указать ветку коммита → нажать <B><I>"Commit new file"</B></I></td></tr>
   <tr><td> 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:</td><td>В репозитории <B><I>JSON</B></I> выбрать файл <B><I>bug_report.json</B></I> → в открывшемся окне нажать кнопку <B><I>"Edit this file"</B></I> →  в поле <B><I>"Edit file"</B></I> ввести:<br>
<B>{"Bug Name": "Application \"NAME\" crashes upon clicking the \"PAY NOW\" button on the last step of product purchase",<br>
"Bug ID": "It will be automatically generated after bug report saving",<br>
"Tested on": "Android 10.0",<br>
"Device" : "Samsung Galaxy S10",<br>
"Environment" : "PROD",<br>
"Severity": "Critical",<br>
"Priority": "High",<br>
"Assigned to": "Name",<br>
"Reported by" : "Anastasiya -P",<br> 
"Reported On": "18FEB22",<br>

<br>"Description": "Unable to finish the process of product purchase as apllication \"NAME\" crashes upon clicking the \"PAY NOW\" button: the screen turns white and the application does not respond to user actions",<br>
<br>"Steps to Reproduce": {"1": "Open the Application",<br>
"2": "Search for the required product",<br>
"3": "Add the product to the cart by clicking  \"ADD\" button",<br>
"4": "Fill out all required fields for product delivery",<br>
"5": "Press the \"Purchase now\" button and select the option \"Pay by credit card\"",<br>
"6": "Enter the credit card data",<br>
"7": "Press the button \"PAY NOW\""},<br>

<br>"Expected Result": "Upon clicking the \"PAY NOW\"button  the money should be charged from user's credit card while the application should display the information about successfully created order",<br>

<br>"Actual Result": "Upon clicking the \"PAY NOW\" button the screen turns white and the application does not respond to user actions"
}</B></td></tr>
   <tr><td>16. Сделать Commit changes (сохранить) изменения на веб интерфейсе:</td><td>Внести пояснения к комиту<B><I>(e.g. update bug_report.json)</B></I>, указать ветку коммита → нажать <B><I>"Commit new file"</B></I></td></tr>
   <tr><td>17. Синхронизировать внешний и локальный репозиторий JSON:</td><td><B>git pull</B></td></tr><rd>
    </table>
 </body>

 

  <head>
  <meta charset="utf-8">
 </head>
 <body>
  <table width="100%" cellspacing="0" cellpadding="4" border="1">
  <col style="width:30%">
	<col style="width:50%">
    <h1 align="center"><B> XML </B></h1>
   <tr>
    <th>Задания</th>
    <th>Ответы</th>
   </tr>
   <tr><td>18. Создать внешний репозиторий c названием XML:</td><td>Открыть <a href="URL">github.com</a> как авторизированный пользователь, в поле <B><I>"Recent repositories"</I></B>  нажать зеленую кнопку <B><I>"NEW"</B></I>.В новом окне заполнить обязательные поля <B><I>"Owner"</B></I>-anastasiya-pv,<B><I>"Repository name"</B></I>-XML,указать тип репозитория "public" или "private"(в данном примере "public"), подтвердить опцию <B><I>"add a README file".</B></I></td></tr>
   <tr><td>19. Клонировать репозиторий XML на локальный компьютер:</td><td>В открытом репозитории нажать кнопку <B><I>"Code"</B></I>,выбрать опцию <B><I>"HTTPS"</B></I> и скопировать отобразившуюся ссылку.Открыть <a href="URL">github.com</a>, указать путь к требуемой папке, ввести <B><I>git clone <a href="URL">https://github.com/anastasiya-pv/XML.git</a></B></I></td></tr>
   <tr><td>20. Внутри локального XML создать файл “new.xml”:</td><td>Открыть склонированный репозиторий<B><I>(cd XML)→ touch new.xml</B></I></td></tr>
   <tr><td>21. Добавить файл под гит:</td><td><B><I>git add new.xml</B></I></td></tr>
   <tr><td>22. Закоммитить файл:</td><td><B><I>git commit -m "add new.xml file"</B></I></td></tr>
   <tr><td>23. Отправить файл на внешний GitHub репозиторий:</td><td><B><I>git push</B></I></td></tr>
   <tr><td>24. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML:</td><td><B><I>cat >> new.xml</B></I><br>
<B>&lt?xml version="1.0" encoding="UTF-8"?&gt <br>
&ltDocument_XML&gt<br>
&ltName_and_Surname&gtAnastasiya Papliauko&lt/Name_and_Surname&gt<br>
&ltThe_number_of_pets&gt1&lt/The_number_of_pets&gt<br>
&ltExpected_salary&gt600$&lt/Expected_salary&gt<br>
&lt/Document_XML&gt<br></B>
Используем сочетание клавиш <B><I>"CTRL+C"</B></I> для того, чтобы прервать процесс ввода данных в документ.</td></tr>
   <tr><td>25. Отправить изменения на внешний репозиторий:</td><td><B><I>git add new.xml -> git commit -m "new.xml file editing" -> git push<B><I></td></tr>
   <tr><td>26. Создать файл preferences.xml:</td><td><B><I>touch preferences.xml</B></I></td></tr>
   <tr><td>27. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:</td><td><B><I>cat >> preferences.xml</B></I><br>
<B>&lt?xml version="1.0" encoding="UTF-8"?&gt<br>
&ltPreferences&gt<br>
&ltMy_favorite_film&gtThe finest hours&lt/My_favorite_film&gt<br>
&ltMy_favorite_serial&gtThe master of sun&lt/My_favorite_serial&gt<br>
&ltMy_favorite_food&gtSushi&lt/My_favorite_food&gt<br>
&ltMy_favorite_season&gtSummer&lt/My_favorite_season&gt<br>
&ltWhat_country_would_I_like_to_visit&gtKorea&lt/What_country_would_I_like_to_visit&gt<br>
&lt/Preferences&gt</B><br>
Используем сочетание клавиш <B><I>"CTRL+C"</B></I> для того, чтобы прервать процесс ввода данных в документ.</td></tr>
   <tr><td>28. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML:</td><td><B><I>touch skills.xml → vim skills.xml → i →</B></I><br>
<B>&lt?xml version="1.0" encoding="UTF-8"?&gt<br>
&ltHard_skills&gt<br>
&ltFirst_line&gtThe basic theory of Software Testing&lt/First_line&gt<br>
&ltSecond_line&gtLinux command line (terminal)/Git bash.Github&lt/Second_line&gt<br>
&ltThird_line&gtHTTP methods, requests,responses&lt/Third_line&gt<br>
&ltFouth_line&gtJSON and XML&lt/Fouth_line&gt<br>
&ltFifth_line&gtAPI testing via POSTMAN(GET,POST,PUT,DELETE,creating variables,writing simple autotests,checking response)&lt/Fifth_line&gt<br>
&ltSixth_line&gtCreating test cases,checklists,bug reports&lt/Sixth_line&gt<br>
&ltSeventh_line&gtTest Design Technics&lt/Seventh_line&gt<br>
&ltEighth_line&gtBrowser developer tools&lt/Eighth_line&gt<br>
&ltNinth_line&gtMobile testing basics&lt/Ninth_line&gt<br>
&ltTenth_line&gtAndroid studio and ADB(android device manager)&lt/Tenth_line&gt<br>
&ltEleventh_line&gtCharles&lt/Eleventh_line&gt<br>
&ltTwelfth_line&gtFiddler&lt/Twelfth_line&gt<br>
&ltThirteenth_line&gtSQL basics(create,delete,drop,insert into,select,from,where,join)&lt/Thirteenth_line&gt<br>
&ltFourteenth_line&gtPostgreSQL database&lt/Fourteenth_line&gt<br>
&ltFifteenth_line&gtScrum&lt/Fifteenth_line&gt<br>
&ltSixteenth_line&gtThe basics of Python&lt/Sixteenth_line&gt<br>
&lt/Hard_skills&gt</B><br>
Нажимем клавишу <B><I>"ESC"→:wq→</B></I> нажимем клавишу <B><I>"Enter"</B></I></td></tr>
   <tr><td>29. Сделать коммит в одну строку:</td><td><B><I>git add . && git commit -m "add skills.xml and preferences.xml files"</B></I></td></tr>
   <tr><td>30. Отправить сразу 2 файла на внешний репозиторий:</td><td><B><I>git push</B></I></td></tr>
   <tr><td>31. На веб интерфейсе создать файл bug_report.xml:</td><td>На <a href="URL">github.com</a> открыть репозиторий <B><I>"XML"</B></I> → Нажать на кнопку <B><I>"Add files"</B></I>,а затем выбрать <B><I>"Create new files"</B></I> в выпадающем списке → ввести bug_report.xml в поле <B><I>"name your file"</B></I></td></tr>
   <tr><td>32. Сделать Commit changes (сохранить) изменения на веб интерфейсе:</td><td>Внести пояснения к комиту<B><I>(e.g. create bug_report.xml)</B></I> и указать ветку коммита → нажать <B><I>"Commit new file"</B></I></td></tr>
   <tr><td>33. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML:</td><td>В репозитории <B><I>XML</B></I> выбрать файл <B><I>bug_report.xml</B></I>→ в открывшемся окне выбрать кнопку <B><I>"Edit this file"</B></I> →  в поле <B><I>"Edit file"</B></I> ввести: <br>
<B>&lt?xml version="1.0" encoding="UTF-8"?&gt<br>
&ltBug_report&gt<br>
&ltBug_Name&gtBug name: Application "NAME" crashes upon clicking the "PAY NOW" button on the last step of product purchase&lt/Bug_Name&gt<br>
&ltBug_ID&gt Bug ID: It will be automatically generated after bug report saving&lt/Bug_ID&gt<br>
&ltTested_on&gt Tested on: Android 10.0&lt/Tested_on&gt<br>
&ltDevice&gt Device: Samsung Galaxy S10&lt/Device&gt<br>
&ltEnvironment&gtEnvironment: PROD&lt/Environment&gt <br>
&ltSeverity&gtSeverity:Critical&lt/Severity&gt<br>
&ltPriority&gtPriority:High&lt/Priority&gt<br>
&ltAssigned_to&gtAssigned to: DeveloperX&lt/Assigned_to&gt<br>
&ltReported_by&gtReported by: Name&lt/Reported_by&gt <br>
&ltReported_On&gtReported on: 18FEB22&lt/Reported_On&gt<br>
<br>&ltDescription&gtDescription:Unable to finish the process of product purchase as apllication "NAME" crashes upon clicking the "PAY NOW" button: the sceen turns white and the apllication does not respond to user actions&lt/Description&gt<br>
<br>&ltSteps_to_Reproduce&gt<br>
&ltFirst_step&gtSteps to Reproduce: 1)Open the Application&lt/First_step&gt<br>
&ltSecond_step&gt2)Search for the required product&lt/Second_step&gt<br>
&ltThird_step&gt3)Add the product to the cart by clicking "ADD" button&lt/Third_step&gt<br>
&ltFourth_step&gt4)Fill out all reqired fields for product delivery&lt/Fourth_step&gt<br>
&ltFifth_step&gt5)Press the "Purchase now" button and select the option "Pay by credit card"&lt/Fifth_step&gt<br>
&ltSix_step&gt6)Enter the credit card data&lt/Six_step&gt<br>
&ltSeven_step&gt7)Press the button "PAY NOW"&lt/Seven_step&gt<br>
&lt/Steps_to_Reproduce&gt<br>
<br>&ltExpected_Result&gtUpon clicking the "PAY NOW" button  the money should be charged from user's credit card while the application displays the information about successfully created order&lt/Expected_Result&gt<br>
<br>&ltActual_Result&gtUpon clicking the "PAY NOW" button the screen turns white and the application does not respond to user actions&lt/Actual_Result&gt<br>
<br>&lt/Bug_report&gt</td></tr></B>
   <tr><td>34. Сделать Commit changes (сохранить) изменения на веб интерфейсе:</td><td>Внести пояснения к комиту<B><I>(e.g. update bug_report.xml),</B></I> указать ветку коммита → нажать <B><I>"Commit new file"</B></I></td></tr>
   <tr><td>35. Синхронизировать внешний и локальный репозиторий XML:</td><td><B><I>git pull</B></I></td></tr>
 </table>
 </body>

 

  <head>
  <meta charset="utf-8">
 </head>
 <body>
  <table width="100%" cellspacing="0" cellpadding="4" border="1">
  <col style="width:30%">
	<col style="width:50%">
  <table width="100%" cellspacing="0" cellpadding="4" border="1">
<h1 align="center"><B> TXT</B></h1>
  <tr>
    <th>Задания</th>
    <th>Ответы</th>
   </tr>
   <tr><td>36. Создать внешний репозиторий c названием TXT:</td><td>Открыть <a href="URL">github.com</a> как авторизированный пользователь, в поле <B><I>"Recent repositories"</I></B>  нажать зеленую кнопку <B><I>"NEW"</B></I>.В новом окне заполнить обязательные поля <B><I>"Owner"</B></I>-anastasiya-pv,<B><I>"Repository name"</B></I>-TXT,указать тип репозитория "public" или "private"(в данном примере "public"), подтвердить опцию <B><I>"add a README file".</B></I></td></tr>
   <tr><td>37. Клонировать репозиторий TXT на локальный компьютер:</</td><td>В открытом репозитории нажать кнопку <B><I>"Code"</B></I>,выбрать опцию <B><I>"HTTPS"</B></I> и скопировать отобразившуюся ссылку.Открыть <a href="URL">github.com</a>, указать путь к требуемой папке, ввести <B><I>git clone <a href="URL">https://github.com/anastasiya-pv/TXT.git</a></B></I></td></tr>
   <tr><td>38. Внутри локального TXT создать файл “new.txt”:</td><td>открыть склонированный репозиторий<B><I>(cd TXT) → touch new.txt</B></I></td></tr>
   <tr><td>39. Добавить файл под гит:</td><td><B><I>git add new.txt</B></I></td></tr>
   <tr><td>40. Закоммитить файл:</td><td><B><I>git commit -m "add new.txt file"</B></I></td></tr>
   <tr><td>41. Отправить файл на внешний GitHub репозиторий:</td><td><B><I>git push</B></I></td></tr>
   <tr><td>42. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT:</td><td><B><I>cat >> new.txt</B></I><br>
<B>My name is Anastasiya Papliauko.<br>
I have only one pet.<br>
I expect to earn about 600$ per month<br></B>
Используем сочетание клавиш <B><I>"CTRL+C"</B></I> для того, чтобы прервать процесс ввода данных в документ.</td></tr>
   <tr><td>43. Отправить изменения на внешний репозиторий:</td><td><B><I>git add new.txt → git commit -m "new.txt file editing" → git push</B></I></td></tr>
   <tr><td>44. Создать файл preferences.txt:</td><td><B><I>touch preferences.txt</B></I></td></tr>
   <tr><td>45. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT:</td><td><B><I>cat >> preferences.txt</B></I><br>
<B>My favorite film is "The finest hours" while my favorite serial is "The master of sun".<br>
My favourite food is sushi and I like summer more than other seasons. <br>
I would like to visit Korea once again or any  other Asian countries.</B><br>
Используем сочетание клавиш <B><I>"CTRL+C"</B></I> для того, чтобы прервать процесс ввода данных в документ.</td></tr>
   <tr><td>46. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT:1</td><td> <B><I>touch skills.txt → vim skills.txt → i →</B></I><br>
<B>Hard skills are as follows: <br>
1.The basic theory of Software Testing<br>
2.Linux command line (terminal)/Git bash.Github<br>
3.HTTP methods, requests,responses<br>
4.JSON & XML<br>
5.API testing via POSTMAN(GET,POST,PUT,DELETE,creating variables,writing simple autotests,checking response)<br>
6.Creating Test cases,checklists,bug reports<br>
7.Test Design Technics<br>
8.Browser developer tools<br>
9.Mobile testing basics<br>
10.Android studio and ADB(android device manager)<br>
11.Charles<br>
12.Fiddler<br>
13.SQL basics(create,delete,drop,insert into,select,from,where,join)<br>
14.PostgreSQL database<br>
15.Scrum<br>
16.The basics of Python</B><br>
Нажимем клавишу <B><I>"ESC"→:wq→</B></I> нажимем клавишу <B><I>"Enter"</B></I></td></tr>
   <tr><td>47. Сделать коммит в одну строку:</td><td><B><I>git add . &&  git commit -m "add skills.txt and preferences.txt files"</B></I></td></tr>
   <tr><td>48. Отправить сразу 2 файла на внешний репозиторий:</td><td><B><I>git push</B></I></td></tr>
   <tr><td>49. На веб интерфейсе создать файл bug_report.txt:</td><td>На <a href="URL">github.com</a> открыть репозиторий <B><I>"TXT"</B></I> → Нажать на кнопку <B><I>"Add files"</B></I>,а затем выбрать <B><I>"Create new files"</B></I> в выпадающем списке → ввести bug_report.txt в поле <B><I>"name your file"</B></I></td></tr>
   <tr><td>50. Сделать Commit changes (сохранить) изменения на веб интерфейсе:</td><td>Внести пояснения к комиту<B><I>(e.g. create bug_report.txt)</B></I> и указать ветку коммита → нажать <B><I>"Commit new file"</B></I></td></tr>
   <tr><td>51. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT:</td><td>В репозитории <B><I>TXT</B></I> выбрать файл <B><I>bug_report.txt</B></I>→ в открывшемся окне выбрать кнопку <B><I>"Edit this file"</B></I> →  в поле <B><I>"Edit file"</B></I> ввести: <br>
<B>Bug Name: Application "NAME" crashes upon clicking the "PAY NOW" button on the last step of product purchase<br>
Bug ID: It will be automatically generated after bug report saving<br>
Tested on: Android 10.0<br>
Device: Samsung Galaxy S10<br>
Environment: PROD<br>
Severity: Critical<br>
Priority: High<br>
Assigned to: "Name"<br>
Reported by: Anastasiya-P <br>
Reported On: 18FEB22<br>


<br>Description: Unable to finish the process of product purchase as apllication "NAME" crashes upon clicking the "PAY NOW" button: the screen turns white and the application does not respond to user actions"<br>
<br>Steps to Reproduce:<br> 
1)Open the Application,<br>
2)Search for the required product,<br>
3)Add the product to the cart by clicking  "ADD" button",<br>
4)Fill out all required fields for product delivery,<br>
5)Press the "Purchase now" button and select the option "Pay by credit card",<br>
6)Enter the credit card data,<br>
7)Press the button "PAY NOW".<br>

<br>Expected Result: Upon clicking the "PAY NOW" button  the money should be charged from user's credit card while the application should display the information about successfully created order.<br>

<br>Actual Result: Upon clicking the "PAY NOW" button the screen turns white and the application does not respond to user actions.</B></td></tr>
   <tr><td>52. Сделать Commit changes (сохранить) изменения на веб интерфейсе:</td><td>Внести пояснения к комиту<B><I>(e.g. update bug_report.txt)</B></I>, указать ветку коммита → нажать <B><I>"Commit new file"</B></I></td></tr>
   <tr><td>53. Синхронизировать внешний и локальный репозиторий TXT:</td><td><B><I>git pull<B><I></td></tr>
  </table>  

