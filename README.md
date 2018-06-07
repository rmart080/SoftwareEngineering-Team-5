# Useful commands for windows:

navegate to the folder ecommerce:
 >**PS C:\Users\yourName>** _cd ecommerce_
 
then you need to activate the workspace
 >**PS C:\Users\yourName>** _./Scripts/activate_

then go to src
 >**PS C:\Users\yourName>** _cd src_
 
and run the server
 >**(ecommerce) PS C:\Users\yourName>** _python manage.py runserver_
 
NOTE:
if you change anything on the models.py of your apps you need to make the migrations for the change to be effective:
 >**(ecommerce) PS C:\Users\yourName>** _python manage.py makemigrations_
 >
 >**(ecommerce) PS C:\Users\yourName>** _python manage.py migrate_
 
if you add any static content, such as pictures or files (on ./static_local/img, not from http://127.0.0.1:8000/admin)
 you need to collect the static content
 >**(ecommerce) PS C:\Users\yourName>** _python manage.py collectstatic_





  
