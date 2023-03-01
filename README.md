# Food-Ordering-System
Online Food Ordering System is the web based application intended for restaurant's Businesses.It provide various feature such as searching,viewing and selection of food items from restaurant for customers.This Application also provides restaurant management and menu management for restaurant manager or owner. 

## Software Requirements
Programming languages : Python

Operating System      : Windows/Linux

Web Technologies      : Django(2.0),Html,Css,Javascript

Database              : Sqlite

#Live Webiste - https://foodcourt-production-6878.up.railway.app/


### Screenshot

###### Home page
![res_list](https://user-images.githubusercontent.com/20842692/50056350-f1761480-0180-11e9-9f53-348cae2c620e.png)

###### Restaurant menu page
![r_menu](https://user-images.githubusercontent.com/20842692/50056372-4023ae80-0181-11e9-9fb8-ccff9e493dd8.png)

###### Menu management page
![menu_manage](https://user-images.githubusercontent.com/20842692/50056396-9e509180-0181-11e9-89f4-ea356c1a8862.png)

###### Order History page
![order_status](https://user-images.githubusercontent.com/20842692/50056409-d2c44d80-0181-11e9-8b3a-0266fc5f8436.png)


#### Setup To Run
```
pip install -r requirements.txt
```
```
python manage.py runserver
```
Basic Steps to ensure to deploy in railway
Steps to Run in Locally:

create virtual env :- python -m venv env

Step 1 Enable the existing virtual env path for Command :

env\scripts\activate

---   
STATIC_ROOT=os.path.join(BASE_DIR,'assests') in settings.py

python manage.py collectstatic 

#Whenever some issue populating for continuously push in master :

git fetch origin master:tmp

git rebase tmp

git push origin HEAD:master

git branch -D tmp

