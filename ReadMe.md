Employee Information & Feedback Form (Power Automate Flow)

This project contains a Power Automate flow that serves a custom HTML employee information & feedback form.
The flow is triggered via an HTTP request and responds with the full form UI, built with Bootstrap for styling.

📌 Features

Collects employee personal and professional details:

Full Name, Date of Birth, Gender, Email, Phone, Address

Department / Unit, Highest Qualification, Next of Kin, Next of Kin Contact

Marital Status, Work Experience, Preferred Location, Skills, etc.

Upload fields for CV and Profile Picture

Rating field (1–5)

Feedback / Comments

Uses Power Automate trigger:

When a HTTP request is received

Returns the HTML form directly in the HTTP response.

Form styled with Bootstrap 4.5 for responsiveness.

📂 Files in this Repository

flow.json → Exported definition of the Power Automate flow

README.md → Documentation for the project

⚡ How It Works

Send a POST request to the flow’s trigger URL.

The flow composes and serves the full HTML form.

Users can fill in and submit employee information & feedback.

The flow can be extended to:

Store responses in SharePoint List

Send data to Dataverse

Trigger notifications via Outlook or Teams

🛠️ Tools Used

Power Automate (Flow)

HTML5 & Bootstrap 4.5

HTTP Trigger in Power Automate

🚀 Future Enhancements

Add data persistence (SharePoint/Dataverse/SQL).

Automate CV/Profile Picture storage in SharePoint document library.

Integrate with HR systems for onboarding workflows.