# VR-Hospital-management
Features

Patient Registration: Enables patients to register and create accounts.
Appointment Management: Patients can make appointments with available doctors.
Patient Records: Secure storage and retrieval of patient medical records.
Pharmacy Billing: Automated pharmacy billing system.
Pharmacy Stock Control: Manages and monitors stock levels for medicines.
Admin Dashboard: Comprehensive dashboard for administrators to manage the system.
Doctor Dashboard: Allows doctors to view patient information and manage appointments.
Patient Dashboard: Patients can access their records and request another doctor if the assigned doctor is unavailable.
Doctor Assignment: Admin can assign or re-assign doctors to patients.

Tech Stack & Language Distribution

Frontend: HTML (69.5%), CSS (1.7%)
Backend: Python (28.8%), Node.js, Express.js
Database: MySQL
Others: HTML5, CSS3, JavaScript


Home Page

![image_2024-09-11_00-34-48](https://github.com/user-attachments/assets/f1828d35-19cb-41d0-a06d-00c30d62756f)


![image](https://github.com/user-attachments/assets/60c11ea1-828d-4c54-8997-75e206eefb05)


ADMIN
![image](https://github.com/user-attachments/assets/297a38ba-f93a-4c3d-b70c-41e084373253)


![image](https://github.com/user-attachments/assets/786f5b1f-10c9-4272-b37a-f7826bff5768)

![image](https://github.com/user-attachments/assets/6a76118c-10ad-46c2-9557-71d0a506e440)

![image](https://github.com/user-attachments/assets/fec255f1-623f-4609-97ba-111486fa8adb)

![image](https://github.com/user-attachments/assets/3a274156-072f-4fd0-bc16-430e19c169a1)

![image](https://github.com/user-attachments/assets/aeddf38e-2d7d-413a-b716-07585b32b495)


Doctor

![image](https://github.com/user-attachments/assets/61047a68-ef2f-4b14-9b6a-65c51e3a3908)


![image](https://github.com/user-attachments/assets/5b8f3c2f-76b0-4a2d-b761-f0466b96e6c7)

![image](https://github.com/user-attachments/assets/5309acbf-ed21-408f-a5bc-31e5b2149d1c)

Patient

![image](https://github.com/user-attachments/assets/a4954597-4922-4b6f-991e-c4a6ce60e897)

![image](https://github.com/user-attachments/assets/861474e4-3b83-4af5-b274-141daa5731e1)

![image](https://github.com/user-attachments/assets/5727b291-141c-48c4-b5fb-fbe5c8e4ad7c)

![image](https://github.com/user-attachments/assets/1ec007f9-2446-444e-aa62-25c86020e720)

![image](https://github.com/user-attachments/assets/2e8ad3fd-2d03-4d3f-8256-6dbb97b7ec4e)





Admin

Signup their account. Then Login (No approval Required).
Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).
Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
Can view/book/approve Appointment (approve those appointments which is requested by patient).

Doctor

Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).
Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.
Can view their discharged(by admin) patient list.
Can view their Appointments, booked by admin.
Can delete their Appointment, when doctor attended their appointment.

Patient

Create account for admit in hospital. Then Login (Approval required by hospital admin, Then only patient can login).
Can view assigned doctor's details like ( specialization, mobile, address).
Can view their booked appointment status (pending/confirmed by admin).
Can book appointments.(approval required by admin)
Can view/download Invoice pdf (Only when that patient is discharged by admin).

HOW TO RUN THIS PROJECT

Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
Open Terminal and Execute Following Commands :
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf

Download This Project Zip Folder and Extract it
Move to project folder in Terminal. Then run following Commands :
py manage.py makemigrations
py manage.py migrate
py manage.py runserver

Now enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:8000/

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Contact

Project Manager: Mr.Varad Joshi & Mr. Ravi Chandra
Email: varadj40@gmail.com

