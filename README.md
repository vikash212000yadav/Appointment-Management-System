# Hospital Management System

Hospital Management System based on Django web framework.
Respective platforms for Doctor, Patients, and Admin/HR Manager.
With Appointments Management System.

## Steps to install and run in local system:-

- Create a virtual environment
    ```python3 -m venv <env_name>```
    
- Activate virtual environment
    ```source <env_name>/bin/activate```
    
- Install requirements in venv
    ```pip install -r requirements.txt```
    
- Make migrations
    ```python manage.py makemigrations```
    
- Apply migrations
    ```python manage.py migrate``` 
    
- Create a super user
    ```python manage.py createsuperuser``` 
    
- Run the server
    ```python manage.py runserver``` 
    
<small>You can delete db.sqlite3 and then make your own migrations further.</small>

## After successful setup:

- Register as a doctor
- Then, register as a patient
- After that, make an appointment
- Finally, you can manage all appointments, patient and doctor data as a Admin too.

### NOTE: 

- Please find the ```APM_architecture.png``` for minimal architecture diagram for doctor and patient authentication/access management.
- Please go through ```Cache_CDN_LoadBalancer.md``` file for excerpts about use of Cache/CDN/Load Balancers.

