# final-project
1)we attack owasp juice shop using tool burip suit and access the admin account
we use the main file from web site files to acess admin path
this is the steps:
Open owasp juice shop:
Right-click anywhere on the webpage and select Inspect (or press F12).
Navigate to the Network tab in the Developer Tools.

Filter and Locate the Main JavaScript File:
Reload the page if necessary to populate the Network tab.
Look for the main JavaScript file (main.js or similar). You can filter by type "JS" to make it easier to find
.
View the JavaScript File:
Click on the main JavaScript file to open its content in the Developer Tools.
Switch to the Response or Source tab to view the code.

Search for the Admin Path:
Use Ctrl+F (Search for keywords like admin or path.
Locate the relevant admin path, as administration 

![image](https://github.com/user-attachments/assets/e7a17790-2118-4bde-b3b1-04f248ccb575)
![image](https://github.com/user-attachments/assets/33f62f52-b7e1-4b1a-aefd-aaa7a5b2c197)

then we use file default_pass_for_services_unhash.txt it will be in files to test password from it to get the admin pass using burip suite
this is the steps:
Access the Login Page:
Open the login page and enter the username.

Set Up Burp Suite:intercept
Launch Burp Suite and configure it to and analyze network traffic.

Initiate the Password Attack:
Use Burp Suite's Intruder feature to send a list of potential passwords (a dictionary or wordlist) to the server.
Monitor the responses from the server to identify the correct password based on a unique response or status code.

. We will be attempting to guess the password for this account. Then, for the password parameter
![image](https://github.com/user-attachments/assets/796cb971-c4e1-4736-bf7c-3bedfb7b9408)
and we get pass of admin :admin123

the we pop up an alert to user using java script injection 
"<iframe src ="javascript:alert('xss')">"
![image](https://github.com/user-attachments/assets/b30cdd2c-af2d-4a6f-8d8d-53bf2e3766d9)
we use a sql injection to acess bender@juice-sh.op
this sql injection skip us from enter password and make us login to bender account successful
![image](https://github.com/user-attachments/assets/22c78d97-23b0-4469-bee0-376b7dd66394)

final this is a vidio link explain all steps:https://drive.google.com/file/d/1vtnd3FUkNiD5PUywSfO3r4EGLIrAEfUe/view
