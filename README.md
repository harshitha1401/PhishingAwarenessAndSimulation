<div align="center" style="border: 2px solid #ccc; padding: 20px; border-radius: 12px; width: 80%; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
    <img
        width="180"
        height="220"
        alt="Logo - SURE ProEd"
        src="https://github.com/user-attachments/assets/88fa5098-24b1-4ece-87df-95eb920ea721"
        style="border-radius: 10px;"
    />

  <h1 align="center" style="font-family: Arial; font-weight: 600; margin-top: 15px;">SURE ProEd (formerly SURE Trust) 
      </h1>
<h2 style="color: #2b6cb0; font-family: Arial;">Skill Upgradation for Rural youth Empowerment Trust</h2>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<div style="padding: 20px; border: 2px solid #ddd; border-radius: 12px; width: 90%; margin: auto; background: #fafafa; font-family: Arial;">

<h2 style = "color:#333;"> Student Details </h2>
<div align = "left" style ="margin: 20px; font-size: 16px;">
    <p><strong>Name:</strong> P.Harshitha </p>
    <p><strong>Email ID:</strong> harshithapeddamuregs15@gmail.com </p>
    <p><strong>College Name:</strong> Rajiv Gandhi Unversity of Knowledge and Technologies(RGUKT-Idupulapaya),Kadapa </p>
    <p><strong>Branch/Specialization :</strong>Computer Science Engineering</p>
    <p><strong>College ID:</strong> R210335@rguktrkv.ac.in</p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Course Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Course Opted:</strong> CyberSecurity </p>
    <p><strong>Instructor Name:</strong> Mr. Derick Mathew Johnson </p>
</div>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Duration:</strong> 6 months </p>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Trainer Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">

<p><strong>Trainer Name:</strong> Mr. Derick Mathew Johnson</p>
<p><strong>Trainer Email ID:</strong>jderickmathew@gmail.com</p>
<p><strong>Trainer Designation:</strong>Trainer, Sure ProEd</p>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Table of Contents**
- [Course Learning](#course-learning-to-be-edited-by-student)
- [Projects Completed](#projects-completed)
- [Project Introduction](#project-introduction)
- [Technologies Used](#technologies-used)
- [Roles and Responsibilities](#roles-and-responsibilities)
- [Project Report](#project-report)
- [Learnings from LST & SST](#learnings-from-lst--sst)
- [Community Services](#community-services)
- [Certificate](#certificate)
- [Acknowledgments](#acknowledgments)

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />


## **Course Learning**
##Overall Learning 

During the Cyber Security internship at SURE ProEd, I gained practical knowledge of phishing attacks, email security, cybersecurity awareness, and secure web application development. I developed a complete Phishing Awareness & Simulation Platform using Flask, HTML, CSS, JavaScript, SQLite, GoPhish, and SMTP integration.

This project enhanced my skills in backend development, frontend design, REST API integration, database management, report generation, and ethical cybersecurity practices. I also improved my problem-solving, debugging, documentation, GitHub usage, and project management skills while working on a real-world cybersecurity application.

## **Projects Completed**
<div align="left" style="margin: 20px; font-size: 16px;">

<p><strong><a href="#project1">Project 1:</a></strong>Phishing Awareness and Simulation (PhishGaurd)</p>
</div>

<h3 id="project1">Project 1: Phishing Awareness and Simulaiton</h3>
<p> A consent-based phishing awareness platform developed using <strong>Python (Flask) & GoPhish</strong>  to safely simulate phishing attacks, educate participants, measure behavior change, and generate awareness reports.This project is intended only for authorized phishing awareness exercises in a controlled environment. Participants must provide informed consent before receiving any simulation emails.
</p>


## **Project Introduction**
(phishGuard Lab)Phishing Awareness & Simulation Platform
A consent-based phishing awareness platform developed using **Python (Flask)** and **GoPhish** to safely simulate phishing attacks, educate participants, measure behavior change, and generate awareness reports.This project is intended only for authorized phishing awareness exercises in a controlled environment. Participants must provide informed consent before receiving any simulation emails.

# Project Scope

This project satisfies the following objectives:

- Create simulated phishing email templates in a permission-based environment.
- Track email opens, clicks, credential submissions, and reporting behavior.
- Build phishing awareness training modules.
- Conduct pre-training (Round 1) and post-training (Round 2) phishing simulations.
- Compare behavioral improvements after awareness training.
- Generate statistical reports and recommendations.
- Integrate GoPhish as the primary phishing engine.
- Use Flask for participant management, awareness training, quizzes, and reporting.

---

# Features

## Volunteer Module

- Volunteer Registration
- Login
- Digital Consent Form
- Volunteer Dashboard
- Awareness Training Modules
- Phishing Awareness Quiz
- Debrief Page
- Report Suspicious Email

---

## Administrator Module

- Admin Login
- Volunteer Management
- Email Template Management
- Campaign Creation
- Round 1 & Round 2 Campaigns
- Campaign Reports
- GoPhish Integration
- Dashboard Statistics

---

## GoPhish Integration

The application automatically creates:

- SMTP Sending Profile
- Email Template
- Landing Page
- Target Group
- Campaign

using the GoPhish REST API.

The administrator only needs to:

1. Select volunteers
2. Select phishing email template
3. Create campaign
4. Click **Launch**

GoPhish handles email delivery and tracking.

---

# Project Workflow

```
                    ADMIN

          Register Volunteers
                  │
                  ▼
        Volunteers Give Consent
                  │
                  ▼
           Admin Dashboard
                  │
                  ▼
      Create Campaign (Round 1)
                  │
                  ▼
      Select Email Template
                  │
                  ▼
        Select Volunteers
                  │
                  ▼
        Launch GoPhish Campaign
                  │
                  ▼
        GoPhish Automatically Creates

          • SMTP Profile
          • Email Template
          • Landing Page
          • Target Group
          • Campaign

                  │
                  ▼
          Simulation Emails Sent
                  │
                  ▼
          Volunteer Opens Email
                  │
                  ▼
          Volunteer Clicks Link
                  │
                  ▼
      Simulation Landing Page Opens
                  │
                  ▼
      Credential Submission Recorded
      (Passwords Never Stored)
                  │
                  ▼
          Debrief Page
                  │
                  ▼
       Awareness Training Modules
                  │
                  ▼
               Quiz
                  │
                  ▼
      Round 2 Campaign (Post Training)
                  │
                  ▼
      Compare Round 1 vs Round 2
                  │
                  ▼
      Final Awareness Report
```


---

# Project Structure

```
phishing-awareness-platform/
│
├── app.py
├── config.py
├── models.py
├── run.py
├── seed.py
├── gophish_integration.py
├── smtp_sender.py
├── requirements.txt
├── README.md
│
├── instance/
│   └── platform.db
│
├── email_templates/
│   ├── password_reset.html
│   ├── internship_offer.html
│   ├── bank_verification.html
│   ├── delivery_failed.html
│   └── hr_update.html
│
├── templates/
│   ├── admin_dashboard.html
│   ├── admin_campaigns.html
│   ├── admin_reports.html
│   ├── admin_templates.html
│   ├── admin_volunteers.html
│   ├── volunteer_dashboard.html
│   ├── training.html
│   ├── quiz.html
│   ├── consent.html
│   └── landing/
│       ├── simulation_login.html
│       └── debrief.html
│
├── static/
│   ├── css/
│   └── js/
│
└── instance/
```

---

## **Technologies Used**

Backend

- Python 3.9+
- Flask
- SQLAlchemy
- SQLite

Frontend

- HTML5
- CSS3
- JavaScript
- Chart.js

Simulation Engine

- GoPhish REST API

Optional Email Backup

- Flask SMTP Sender

Other Tools

- Google Forms (Feedback)
- Git
- GitHub

---

# Installation

## Clone Project

```bash
git clone <repository-url>

cd phishing-awareness-platform
```

---

## Create Virtual Environment

Linux / macOS

```bash
python -m venv venv

source venv/bin/activate
```

Windows

```bash
venv\Scripts\activate
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Configure Environment

```bash
cp .env.example .env
```

Example

```env
SECRET_KEY=change-me

PUBLIC_BASE_URL=http://127.0.0.1:5000

DEFAULT_ADMIN_USERNAME=admin
DEFAULT_ADMIN_PASSWORD=zaqmlp

GOPHISH_API_URL=https://127.0.0.1:3333
GOPHISH_API_KEY=YOUR_API_KEY
GOPHISH_VERIFY_TLS=False

SMTP_HOST=localhost
SMTP_PORT=587
SMTP_USERNAME=
SMTP_PASSWORD=
```

---

## Seed Database

```bash
python seed.py
```

---

## Run Flask

```bash
python run.py
```

Open

```
http://127.0.0.1:5000
```

If port 5000 is already in use:

```bash
lsof -i:5000

kill -9 <PID>
```

---

# GoPhish Setup

Download

```bash
wget https://github.com/gophish/gophish/releases/latest/download/gophish-v0.12.1-linux-64bit.zip
```

Extract

```bash
unzip gophish-v0.12.1-linux-64bit.zip
```

Start GoPhish

```bash
chmod +x gophish

./gophish
```

Open

```
https://127.0.0.1:3333
```

Ignore the browser certificate warning (self-signed certificate).

Generate an API Key:

```
Settings

↓

API Keys

↓

Generate API Key
```

Copy the API key into `.env`.

---
## **Roles and Responsibilities**
# Email Templates

The project includes five phishing scenarios:

- Password Reset
- Internship Offer
- Bank Verification
- Delivery Failed
- HR Policy Update

---

# Awareness Training

The platform provides training on:

- Email Phishing
- Spear Phishing
- Smishing
- Vishing
- Whaling
- Social Engineering

---

# Quiz

After completing the training, volunteers take a phishing awareness quiz.

The quiz score is stored and compared with phishing simulation behavior.

---

# Reports

The reporting dashboard compares:

Round 1

- Click Rate
- Credential Submission Rate
- Report Rate
- Average Time to Report

Round 2

- Click Rate
- Credential Submission Rate
- Report Rate
- Average Time to Report

Additional Metrics

- Quiz Scores
- Behavioral Improvement
- Awareness Recommendations

---

# Privacy & Ethics

- Consent is mandatory before participation.
- Passwords entered on phishing pages are **never stored**.
- Only click and submission events are recorded.
- The platform is intended exclusively for authorized awareness campaigns.

---

# Expected Outcome

The completed project provides:

- Consent-Based Phishing Simulation Platform
- Five Phishing Email Templates
- GoPhish Campaign Integration
- Web-Based Awareness Training
- Phishing Awareness Quiz
- Before vs After Behavioral Analysis
- Interactive Statistical Reports
- Security Awareness Recommendations

---
## **Project Report**
<p align="center">
<a href="https://drive.google.com/file/d/1htj3vPXsvopM4YfhXD9V1nfTZ1UfF59y/view?usp=drivesdk">
<strong>📄 View Full Project Report</strong>
</a>
</p>

## **Learnings from LST & SST**

During the internship, I participated in **Life Skills Training (LST)** sessions conducted once every two weeks on Sundays and a **three-week Soft Skills Training (SST)** program.

The **LST sessions** focused on developing essential life skills such as time management, self-discipline, goal setting, adaptability, emotional intelligence, teamwork, and maintaining a positive attitude. These sessions helped me improve my personal development and prepared me to handle challenges effectively in both academic and professional environments.

The **SST program** concentrated on enhancing my professional skills, including communication, presentation, resume building, interview preparation, group discussions, workplace etiquette, and professional behavior. Through these sessions, I gained confidence in expressing my ideas, collaborating with others, and preparing for placements and future career opportunities.

Overall, both the LST and SST sessions played an important role in improving my personal, interpersonal, and professional skills alongside the technical knowledge gained during the Cyber Security internship.

## **Community Services**

During my internship period, I participated in multiple community-oriented activities such as Tree platation and helping Elder Citizens in  gongivaripalli,chittoor.

### **Activities Involved**
  
 <!-- add the location where you have panted -->
- **Tree Plantation Drive** – Participated by planting trees and contributing to environmental improvement.

  <!-- add the location where you helped -->
- **Helping Elder Citizens** – Assisted several elderly individuals with simple daily tasks and provided support where needed. 

<!-- you can write impacts according to your experience in your words-->

### **Impact / Contribution**
- Actively participated in promoting a greener and cleaner surroundings.
- Offered personal assistance to elder citizens, strengthening community bonds.
- Improved skills in communication, coordination, and social responsibility.

### **Photos**

<!-- add your photos below -->
<!-- change url below with your image urls (inside  src='')-->

<div align="center">
  <img src="https://drive.google.com/file/d/1ZfUodfW60fgnwYs5aZTH69Uo_kmiZNgL/view?usp=drivesdk" alt="Community Service Photo 1" width="30%">
  <img src="https://drive.google.com/file/d/1WPXbrB6nNFn1aAbQcSHvL3dNyLm3_oR9/view?usp=drivesdk" alt="Community Service Photo 2" width="30%">
  <img src="https://drive.google.com/file/d/1NpdO5QFI9GFcWbEkP9q0qQoTdXAGImb7/view" alt="Community Service Photo 3" width="30%">
</div>

## **Certificate**

The internship certificate serves as an official acknowledgment of the successful completion of my training period. It will be issued by the organization upon fulfilling all required tasks and meeting the performance expectations of the program. The certificate validates the skills, experience, and contributions made during the internship.

<!-- add your certificate image url below (inside src='')-->

<p align="center">
<img src="https://github.com/Lord-Rahul/Practice-Programs/blob/main/react/1/public/Gemini_Generated_Image_a6w8rda6w8rda6w8.png?raw=true" alt="Internship Certificate" width="80%">
</p>

---

## **Acknowledgments**

I would like to express my sincere gratitude to **SURE ProEd (formerly SURE Trust)** for providing me with the opportunity to participate in the Cyber Security Internship and gain valuable practical experience.

I am deeply thankful to my mentor, **Mr. Derick Mathew Johnson**, for his continuous guidance, technical support, encouragement, and valuable feedback throughout the internship. His mentorship played a significant role in the successful completion of my project.

I would also like to express my heartfelt gratitude to **Prof. Radhakumari Challa**(https://www.linkedin.com/in/prof-radhakumari-challa-a3850219b), Executive Director and Founder of **SURE Trust**(https://www.suretrustforruralyouth.com/)
 for creating a platform that empowers students through quality technical education and skill development opportunities.

Finally, I am grateful to everyone who contributed directly or indirectly to the successful completion of my project, "PhishGuard Lab – Phishing Awareness & Simulation Platform."

