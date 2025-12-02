Job Tracker – PHP Web Application

Job Tracker is a clean and functional PHP-based web application designed to help users manage job listings, apply for positions, upload resumes, and access profile-based features.
The system is built with modular PHP pages, a structured MySQL backend, and a simple UI that demonstrates full-stack development principles.

🚀 Features
👤 User Management

User registration & login

Profile editing (name, details, resume, etc.)

Secure logout

Resume/CV upload support

💼 Job Tracking & Applications

Browse job listings

View job details

Apply for jobs through the portal

Track user-specific actions

💬 Messaging & Contact

Contact form for queries or support

Message handling via send-message.php

🛠️ Backend Utilities

Admin panel (/admin) for management tasks

Database connection abstraction (db.php)

AJAX-based data fetching using fetch.php

🎨 UI Components

Reusable header.php and footer.php

Clean layout pages: Home, About, Contact, Job Details

🧰 Tech Stack
Layer	Technology
Backend	PHP
Database	MySQL
Frontend	HTML, CSS, JavaScript (AJAX)
File Storage	Local uploads (/uploads)
Server	Apache (XAMPP / WAMP / LAMP)
📁 Project Structure
Job Tracker/
│
├── admin/                 
├── uploads/               
│
├── about.php              
├── apply.php              
├── contact.php            
├── config.php             
├── db.php                 
├── edit-profile.php       
├── fetch.php              
├── footer.php             
├── header.php             
├── home.php               
├── job-details.php        
├── login-signup.php       
├── logout.php             
├── profile.php            
├── register.php           
├── send-message.php       
├── submit.php             
├── upload-resume.php      
└── view-details.php       

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Riss620/Ca2.git
cd Ca2

2️⃣ Set Up Environment

Use:

XAMPP (recommended)

WAMP / MAMP

LAMP

3️⃣ Configure Database

Create a database (e.g., job_tracker_db)

Import SQL schema (if provided)

Update credentials in config.php

4️⃣ Run the Application

Visit:

http://localhost/Ca2/home.php

🎯 How to Use

Register or log in

Edit profile

Upload resume

Browse and apply for jobs

View job details

Contact admin

Admin can manage system

📌 Future Enhancements

Password hashing

Better admin dashboard

Application status tracking

Email notifications

Search & filtering features
