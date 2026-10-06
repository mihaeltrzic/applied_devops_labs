# applied_devops_labs
# Hospital management - DevOps project

## 1. Project overview
## 2. Requirement analysis
### 2.1 Functional requirements

The application should have a way of entering patient information via a standard user computer. Information would be name, date of birth, contact information and address.
It should have a search function for finding existing patients and viewing their information.
Such information should be editable.
Patient records need to be able to be deactivated while perserving all other records of the patient.


### 2.2 Non-functional requirements
## 3. Roles and access control
RECEPTIONIST
Should be able to schedule appointments.
DOCTOR

ADMINISTRATOR

||Receptionist|Doctor|Administrator|
|-----|-----|-----|-----|
|Can schedule appointments|Yes|Yes|No|
|Can view appointments|Yes|Yes|No|

## 4. Product backlog

US-01

**Doctor** wants to **be able to file appointments** so he can **work with the receptionist absent.**

US-02

**Receptionist** wants to **be able to access the calendar** so she can **schedule appointments.**

US-03

**Administrator** wants to **have access to appointments** so he can **delete them in case of errors.**


## 5. Process and ceremonies

Sprint will last 1 week. That should leave enough time for everything to be implemented. The number of sprints will be 4.

T01.1

Create a database so saving of important information is possible.

T01.2





## 6. 

Authentication and access
Patient management
Doctor management
Appointment scheduling
Medical records and export
Platform and pipeline

E01.1

Development of the reservation system for filing appointments.

|ID|Task|Kind|Depends on|
|---|---|---|---|
|T01.1|Appointment entity and migration(patient, doctor, datetime) |Code|US-01|
|T01.2|Development of the login website for end-user login|Code|T01.1|
|T01.3|Managing double booking prevention|Code|T01.2|
|T01.4|Unit testing the individual features required|Test - automated|T01.3|

## 7. Scaling

**SCALE**

1-10

1 - Simple single functionality

2 - More complex single functionality

4 - Relatively simple yet important functionalities for the work of the program

5 - Functionality tied to another functionality

6 - Functionality tied to edge cases which can affect the work of the application

7 - Security concerns

10 - Extremely complex tasks requiring vast knowledge of the application


|ID|User Story|Points|What drives the numbers|
|---|---|---|---|
|US-**|Login form|4|The login form and it's function can make or break user experience and access to the application|

|US-**|Double booking disabled|6|Making sure that double booking doesn't happen is imperative for the functionality of the app and customer satisfaction|

## 8. Sprints

|Sprint|Goal|Stories|Points|
|---|---|---|---|
|1|Login works and the CI pipeline is built|US-**|10|
|2|The booking system is implemented and working|US-**|14|
|3||||

## 9. Stack

C# with ASP.NET Core

SQL

xUNIT

Playwright for .NET

Why?

Most familiar with it, easy to work with, fairly large user base.
