DHI Academic Portal Security Risk Assessment
Project Overview

This project is a Governance, Risk, and Compliance (GRC) based security risk assessment conducted for the DHI Academic Portal. The portal is used by teachers, students, and administrative staff for managing attendance, internal marks, and academic records.

The purpose of this project is to identify security risks related to the current authentication and access control system of the portal and recommend suitable security controls to reduce those risks.

Problem Statement

The DHI portal is accessed using shared computers by both teachers and students. In several cases, teachers save their passwords in web browsers for convenience. Since the same systems are later used by students, there is a risk of unauthorized access to teacher accounts.

The portal currently does not implement Multi-Factor Authentication (MFA), making it possible for anyone with the teacher’s password to access the account and modify sensitive academic data such as attendance and marks.

Objectives
Identify security risks in the DHI portal
Analyze the impact and likelihood of identified risks
Create a professional risk register
Recommend security controls to improve access security
Visualize risks using a dashboard
Risks Identified
Risk ID	Risk	Severity
R1	Unauthorized access to teacher portal	Critical
R2	Attendance record modification	Critical
R3	Marks tampering	High
Root Causes Identified
Shared computer usage
Saved browser passwords
Weak authentication mechanism
Lack of Multi-Factor Authentication (MFA)
Absence of audit logging
Security Recommendations

The following security controls were recommended:

Multi-Factor Authentication (MFA)
Strong Password Policy
Audit Logging
Session Timeout
Disable Password Saving on Shared Systems
Role-Based Access Control (RBAC)
Security Awareness Training
Tools & Technologies Used
Tool	Purpose
Microsoft Excel	Risk Register
Microsoft Word	Risk Assessment Report
Power BI / HTML Dashboard	Risk Visualization
GitHub	Project Hosting
Dashboard Features

The dashboard includes:

KPI Cards
Risk Severity Visualization
Risk Heat Map
Risk Register Table
Recommendations Section
Root Cause Analysis
Skills Demonstrated

This project demonstrates the following skills:

Governance, Risk & Compliance (GRC)
Risk Assessment
Access Control Analysis
Security Recommendations
Risk Register Development
Root Cause Analysis
Dashboard Visualization
Security Governance Awareness
Project Structure
DHI_GRC_Risk_Assessment/
│
├── Risk_Assessment_Report.pdf
├── Risk_Register.xlsx
├── DHI_Risk_Assessment_Dashboard.html
├── Dashboard_Screenshots/
├── Presentation.pptx
└── README.md
Conclusion

This project highlights how weak authentication practices and shared computer usage can create serious security risks in academic systems. By implementing recommended controls such as MFA, audit logging, RBAC, and stronger access control policies, the institution can significantly improve the security and integrity of academic records.

Author

T Mohammed Jazeel
B.E. Computer Science & Engineering
PA College of Engineering