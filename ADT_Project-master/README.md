# Blood Link : Blood Bank Management System

Application URL: http://bbms.pythonanywhere.com/   

Project Summary: 

We have developed a blood bank management system where users can register to donate or receive blood based on their needs. A user in need of a blood bag can utilize search criteria to determine the availability of blood bags in blood banks by utilizing a dataset from Kaggle that provides information about various blood banks in India. 

 

Project Objectives: 

A blood bank management system's goal is to efficiently manage blood collection, storage, and distribution from donors to recipients.  

Our objectives for carrying out the same are as follows:  

Design and develop a web-based application that allows people to sign up as donors and recipients. 

To provide a user-friendly interface that is accessible to all.  

To safeguard the safety and confidentiality of sensitive information of those donating and receiving blood.  

To successfully manage inventories, schedule appointments, and provide appropriate dashboards to display statistics.  

Providing accurate and timely information on blood availability.  

 

Project Usefulness: 

The web application serves as a centralized one-stop solution for all stakeholders.  

Donors can register and schedule appointments at their leisure, while recipients can search for and request blood. This reduces the hassle.  

Blood bank administration can properly control the inventory hence lowering the chance of any error and enhancing the response time. 

 

TECHNICAL DESCRIPTION: 

 

Data: 

We have used the "Blood Bank Directory - India" Kaggle dataset. This dataset contains information about India's multiple blood banks. The National Institute of Health and Family Welfare (NIHFW), New Delhi, the Department of Health and Family Welfare, and the Ministry of Health and Family Welfare have created this dataset. The National Health Portal of India has made this data public to educate Indian residents about healthcare. The dataset currently contains 27 columns such as Blood Bank Name, City, Contact No, Blood Component Available, and so on, and we have normalized and separated the data into tables such as the user table, donor table, recipient table, and blood bank table.  

 

MVC Architecture: 

The web app that we have created follows the MVC schema as follows:  

Model: In our application all the backend data logic is stored in MySQL database.  

View: For creating the front end of our application we have used HTML (Hyper Text Markup Language), CSS and   Bootstrap.  

Controller: In our application Flask acts as the brain that will control how the data is displayed.  

 

Deployment Platform: 

We have deployed our application on PythonAnywhere by Anaconda. It is a web-based platform that provides users with the ability to host their web applications, databases, and other services in the cloud, making it easy to deploy and scale their Python-based projects. 

 

Tools: 

Frontend – HTML, CSS, JavaScript, Bootstrap 

Backend – Python, Flask 

Database – MySQL 

 

User Functionalities: 

Our application supports the following functionalities: 

First time users can create their own account based on their user type and their record is created in the database. To guarantee data integrity, we use the uniqueness rule and perform simple validations when creating a new incident record. 

A user can login to their profile and change their details whenever and the details will be updated in the database as well. 

A user can also view their appointment history. 

A user can select a Blood bank of their choice and book an appointment. 

The admin can view the details of all the users and can also accept or reject the appointment of any user. 

The admin can edit the details of the users by adding the details of the blood sample. 

The admin can also delete any user. 
