# Car-Insurance-Management-System---README
🚗 Car Insurance Management System - README
📋 Overview
This Car Insurance Management System is designed to manage the core functions of an insurance company, including registering vehicles, managing customer information, processing car insurance claims, and supporting administrative roles. The project implements several use cases through various actors and components in both the front and back end.

👥 Team Members
Name	Role	ID
Farida Mahmoud	Team Leader	20210278
Reaal Mohamed	Developer	20214167
Maickel Ezzat	Developer	20194184
Mohamed Fares	Developer	20200521
🧠 Key Features
✅ Functional Use Cases
Login System: Validates user credentials with verification.

Add Car: Registers new cars based on eligibility (e.g., age, price).

Remove Car: Removes cars from the system upon request.

Edit Car: Modifies car details as needed.

Request Car: Submits accident claims or car condition reports.

Winch Request: Requests a tow truck in case of breakdown.

Supervisor Enrollment and Privilege Management: Enables managerial tasks.

Accident Reporting: Customers can upload accident videos.

📂 Actors Involved
Insurance Company Manager

Insurance Company Employer

Analyst

Man Car Employer

Customer Service

Sales Employee

Customer

🏛️ System Architecture
⚙️ Class Diagrams
Classes are organized around business roles with properties and methods such as:

CustomerService — Handles adding, removing, editing car/customer info.

Car — Attributes include type, number, license.

Customer — Includes name, ID, phone, and address.

InsuranceEmployer — Manages verification and insurance validation.

Analyst — Responsible for checking vehicle eligibility.

🔁 Sequence Diagrams
Sequence diagrams illustrate the flow of actions:

Data entry by customer (car type, number, license).

Verification by analysts and car managers.

Conditional logic based on car eligibility.

Success/failure responses throughout.

🗂️ Use Case Summaries
1. Add Car
Actors: Manager, Analyst, Car Owner, Customer Service.

Precondition: Valid car license, >5 years old, price > 50,000.

Output: Insurance approved or rejected.

2. Remove Car
Actors: Customer Service.

Precondition: Insurance cancellation requested.

Output: Data deleted from the system.

3. Edit Car
Actors: Customer Service.

Precondition: User requests a change.

Output: Edited data saved.

4. Request Car
Actors: Multiple (Customer, Manager, Analyst...).

Precondition: Car involved in an accident.

Output: Insurance compensation or repair.

5. Winch
Actors: Customer, Insurance Company.

Description: Emergency towing service via app.

💡 Non-Functional Requirements
Error handling for incorrect or incomplete input.

Secure login and role-based access control.

Data validation at each user interaction step.

📝 Notes
The system relies on accurate user input and pre-verification by analysts.

Validation is key for add/edit/remove actions.

Future improvements could include a mobile app interface or real-time notification system.

📎 Files
USE CASE dIAGRAM final.docx: Describes all use cases and scenarios.

Add car seq reaal.docx: Sequence diagram for adding/checking/inquiring car data.

class table , ... reaal.docx: Class structures and relationships.

Usecasediagram1.png: Visual use case diagram.

NextSection_ProjectCode.rar: Source code and project files (extract to view).
