## Employee Management Portal with External Integration and Custom Features 

## DESCRIPTION
This system allows efficient management of employee data (such as ID, Name, Department, Designation, etc.) with full CRUD functionality and custom sorting/searching options. It features a department hierarchy that displays employees by department and sub-departments. Integration with external APIs provides weather data specific to employees. Role-based access control ensures data visibility is restricted according to user roles. Additionally, a microflow sends confirmation emails when employee information is updated.

## INSTALLATION INSTRUCTIONS
1. Clone the repository.
2. Open in Mendix Studio Pro (Version 9.24.12)

## USAGE
1. Log in as a Business Admin.  
2. Add master data for Department, Sub-Department, and Designation.  
3. On the Home Page, an option is available to create new Employees and Managers (with the contact information set as the name of a city).  
4. When the Admin saves the details, the system will automatically create the user's account in the Account entity based on the selected role. From Account Overview, the password can be updated.
5. When opening an existing employee from the employee list, a REST API is called to fetch weather information based on the employee's location.

## CONTRIBUTOR
--Shraddha Gupta
