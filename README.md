# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM

##admin.py##
from django.apps import AppConfig
class AppConfig(AppConfig):
default_auto_field = 'django.db.models.BigAutoField'
name = 'App'

##models.py##
from django.db import models
class Employee(models.Model):
empid=models.IntegerField()
empname=models.CharField(max_length=20)
dept=models.CharField(max_length=20)
salary=models.FloatField()
aadhaar=models.BigIntegerField(null=True)

## OUTPUT
![Screenshot 2024-04-04 084230](https://github.com/JAYASREE24032006/ORM/assets/144360800/42adb1f5-0e6d-4566-b575-12bc8cff2a91)
![Screenshot 2024-04-04 084243](https://github.com/JAYASREE24032006/ORM/assets/144360800/34a1294b-1246-4982-ac6b-3264158a532d)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
