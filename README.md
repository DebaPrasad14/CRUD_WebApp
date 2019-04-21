# CRUD_WebApp
Demonstrating CRUD operation using Python, DJango and MySQL, Html, Bootstrap

The main Idea of this application is to do CRUD Operaion with Employee Data.

- Here I have used MySQL DB from XAMPP and accordingly I have changed the DATABASE setting in settings.py file,
  which was created during My project creation Process.
  
- Accordingly we have to create a new database in MySQL serrver in XAMPP (go to localhost/phpmyadmin) 
  which is to be mentioned in settings.py
- After this we have to do migrations like 'python manage.py makemigrations' followed by 'python manage.py migrate'

- After project completed, when we go on adding new details of employees/records then output will come as below.
  with the below mentioned actions we can perform CREATE/ ADD, RETRIEVE/SHOW , UPDATE AND DELETE Operations.

Employee ID	  Employee Name	  Employee Email	  Employee Contact	  Actions
100	          kumar p	      kumarp@gmail.com	    9090732435	      Edit Delete
105	          Taimur k	    taimur11@outlook.com	9091256355	      Edit Delete
107	          Virat kohli	  viratk@gmail.com	    986504156	        Edit Delete
103	          Ankur J	      j.ankur@gmail.com	    8765004227	      Edit Delete

                                                                                Add New Record
