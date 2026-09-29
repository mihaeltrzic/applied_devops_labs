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

**Receptionist** wants to **be able to access the calendar** so she can **schedule appointments.**

**Administrator** wants to **have access to appointments** so he can **delete them in case of errors.**


## 5. Process and ceremonies

Sprint will last 1 week. That should leave enough time for everything to be implemented. The number of sprints will be 4.
