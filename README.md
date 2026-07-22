# IOC-Portal
Development Flow
Requirement
│
▼
AI Prompt Engineering
│
▼
Code Generation
│
▼
Code Review & Modification
│
▼
Compilation
│
▼
Deployment on IIS
│
▼
Testing & Production

Step 1: Requirement Analysis
"We first identify the core problem."
Example:
Store management
Attendance
Visitor management
Gate Pass
Reports
Instead of coding immediately, prepare a Software Requirement Specification (SRS).






Step 2: AI Prompt Engineering
Tell LLM exactly which boilerplate code script to build.
Example:
Build an IIS-based Visitor Management System using HTML, CSS, JavaScript, C#, LiteDB and ASP.NET Generic Handler.
LLM model generates
•	HTML 
•	CSS 
•	JavaScript 
•	C# 
•	Database models

Step 3: Code Review
LLM generated the initial code, which was technically reviewed, modified, integrated, and tested before deployment.
Step 4: Compile
C# Source Code
│
dotnet build
│
▼
DLL Files
Example
api.ashx
↓
VMSDataAPI.dll
The DLL contains executable backend logic.

Step 5: Deployment
Copy files to
C:\inetpub\wwwroot\
Configure IIS & open http://10.x.x.x:8081
Portal is live.





Step 6: Database
Initially
JSON then LiteDB then SQL Server

Step 7: Testing
Test
✔ Login
✔ Attendance
✔ Vendor
✔ Reports
✔ Printing
✔ Security
Only after successful testing
Deploy.
The quality depends on
•	Prompt writing 
•	Software architecture knowledge 
•	Ability to review generated code 
•	Debugging 
•	Testing 
•	Deployment

