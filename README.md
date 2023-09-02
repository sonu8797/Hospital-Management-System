# Hospital Database Management System Web Application
This repository contains a Hospital Database Management System web application developed using HTML, CSS, Django, Python, and SQLite. The system aims to efficiently manage patient records, treatment details, and provide secure user authentication and authorization mechanisms. The application incorporates an intuitive user interface and robust APIs for seamless communication between the front-end and back-end components.

## Features
The Hospital Database Management System offers the following features:

- **Entity Relationship (ER) Diagram**: The system is designed based on an ER diagram that includes entities such as receptionist, data entry operator, doctor, patient, and admin. This diagram serves as a blueprint for the system's structure and relationships between different entities.

- **Seamless Communication**: Robust APIs have been implemented to ensure smooth communication between the front-end and back-end components of the web application. This enables efficient data transfer and interaction between users and the system.

- **Storage, Retrieval, and Management of records**: The application provides efficient storage, retrieval, and management of patient records and treatment details. Users can easily search for and access relevant information, facilitating streamlined operations within the hospital.

- **User Authentication and Authorization**: Secure user authentication and authorization mechanisms have been implemented using Django's built-in features. This ensures that only authorized personnel can access sensitive information and perform specific actions within the system.

---

## Usage
Upon accessing the Hospital Database Management System web application, users can perform the following tasks:

- **Login**: Users can authenticate themselves using their credentials. Different user roles have different levels of access and functionality within the system.

- **Patient record Management**: Users can add, update, or delete patient records. They can also search for patients based on various criteria, view detailed information, and track treatment details.

- **User Management**: Admin users have the authority to manage user accounts, including creating, updating, or deleting user profiles. They can assign different roles and permissions to users as necessary.

- **Reports**: The system provides the ability to generate reports based on patient data, treatment history, or other relevant parameters. This feature enables users to extract valuable insights and statistics from the database.

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
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```
## This project was made by Kriti Bhardwaj, Vinod Meena, Nirbhay Kumar and Sonu Kumar Yadav

