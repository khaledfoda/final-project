# final-project
1)we attack owasp juice shop using tool burip suit and access the admin account
we use the main file from web site files to acess admin path
![image](https://github.com/user-attachments/assets/e7a17790-2118-4bde-b3b1-04f248ccb575)
then we use file default_pass_for_services_unhash.txt it will be in files
to test password from it to get the admin pass using burip suite
. We will be attempting to guess the password for this account. Then, for the password parameter
![image](https://github.com/user-attachments/assets/796cb971-c4e1-4736-bf7c-3bedfb7b9408)
and we get pass of admin :admin123
the we pop up an alert to user using java script injection 
"<iframe src ="javascript:alert('xss')">"
![image](https://github.com/user-attachments/assets/b30cdd2c-af2d-4a6f-8d8d-53bf2e3766d9)
we use a sql injection to acess bender@juice-sh.op
this sql injection skip us from enter password and make us login to bender account successful
![image](https://github.com/user-attachments/assets/22c78d97-23b0-4469-bee0-376b7dd66394)

