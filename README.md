🎓 Educational Organisation Using ServiceNow

A fully functional Educational Management System built on the ServiceNow Platform (Personal Developer Instance - PDI). This application successfully digitizes and automates student admissions, academic progress tracking, and core student record management by leveraging ServiceNow's powerful low-code capabilities.

👥 Team

Team Leader,Fathima Nihla M
Team Member,Girisha M
Team Member,Hafna S
Team Member,Haifa Mujeeb

🎬 Project Demonstration
📺 Watch Demo Video: See the application, workflows, and auto-calculations in action!

🔗 Click here to watch the demo video

✨ Key Features Implemented : 
The application provides significant automation across administrative and academic functions:🔢 Automated Identification: Unique Admission Number is generated automatically upon student record creation.📍 Address Automation: Auto-fill Address functionality using PIN Code input to ensure data accuracy.📊 Dynamic Progress Calculation: The Student Progress Form instantly calculates:Auto Total MarksAuto PercentageAuto Result (Passed/Failed) based on defined criteria.🔄 Status Flow Management: A visual Process Flow tracks the entire admission lifecycle: New $\rightarrow$ In Progress $\rightarrow$ Joined/Rejected $\rightarrow$ Closed.🧩 Modular Design: Dedicated, role-based modules for Admissions Staff and Academic Staff.

Tech Stack and Components :
The solution is built entirely using ServiceNow's native functionality, minimizing custom code development.

Layer,Technology/Module,Description
Platform,ServiceNow (PDI),Core cloud platform for development and deployment.
Logic/Automation,"Client Scripts, UI Policies",Used for the real-time mark calculations and form field automations.
Data Structure,Custom Tables,"Primary tables: Admission, Student Progress, and Salesforce (for initial registration)."
Process Control,Process Flow,Configured to visually manage and enforce the Admission Status workflow.
Deployment,Update Sets,Used to package and migrate the application components.

⚙ How to Run the Project
To deploy and run this application, follow these steps in your ServiceNow instance:

Obtain PDI: Ensure you have an active Personal Developer Instance (PDI) from developer.servicenow.com.

Import Update Set: Navigate to System Update Sets > Retrieved Update Sets.

Load Files: Import the Update Set file (found in the /UpdateSets/ folder of this repository).

Commit: Commit the Update Set to load all application files, tables, and scripts into your instance.

Explore: Navigate the modules in the Application Navigator:

[Your Application Name] > Admissions

[Your Application Name] > Student Progress

📜 Project Documentation
All project phases are documented and available in the /Documents/ folder of this repository:

Ideation Phase

Project Planning Phase

Project Design Phase

Requirement Analysis Phase

Performance Testing Phase

🚀 Future Scope
Potential enhancements for the next phase of development include:

🎓 Student & Parent Portal: Creating a custom portal for external users to check status and progress.

📩 Communication Automation: Implementing Email & SMS Notifications triggered by status changes.

📊 Advanced Analytics: Developing custom reporting dashboards for deeper grade analysis.


🔐 License
This project is made available for academic, learning, and non-commercial purposes.
🧠 Integration: Connecting with external APIs or databases for expanded institutional use.
