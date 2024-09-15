# BreakdownBuddy

This project outlines the development of a user-friendly automotive service 
management system. It enables customers to request vehicle services, track their status, and 
view invoices. Mechanics can apply for jobs, manage their work assignments, and track their 
earnings. Admins can manage users, approve mechanics, and oversee the entire service 
process. The system also offers a day-night theme switch and ensures data integrity. This 
project aims to streamline vehicle servicing operations, enhancing customer and mechanic 
experiences.                                                                                    
HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Add to Path while installing Python)
- Open Terminal and Execute Following Commands :

pip install django==3.0.5
pip install django-widget-tweaks
(must needed)

##To run the server:
- Move to project folder in Terminal. Then run following Commands :

py manage.py makemigrations
py manage.py migrate
py manage.py runserver

- Now enter following URL in Your Browser Installed On Your Pc

http://127.0.0.1:8000/

