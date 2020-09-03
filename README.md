# Schoolmanagement
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Sumit%20Kumar-red)
---


## Functions
### Teacher
first teacher will apply for job, when their account is approved by admin, then only teacher can access their dashboard.
After account approval by admin teacher can take attendance of any class attendance and view attendance.
Teacher can also publish/announce notice to student like submission of assignments.

## Student
First student will take admission/signup.
When their account is approved by admin then only student can access their dashboard.
After account approval by admin then student can view their details like attendance.
Student cant view attendance of other student.
Student cant announce anything only they can view.

### Admin
First admin will signup their account.
Admin no need for their account approval.
After login they can see how many student/teacher wants to get job/admission in their school
They can approve or delete.
They can update any student/teacher details.
Admin can announce any notice.


## Drawbacks
On update page of teacher/student you must have to update password.

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps
```
## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Facebook](https://fb.com/sumit.luv)
- [Subscribe my Channel LazyCoder On Youtube](https://youtube.com/lazycoders)
