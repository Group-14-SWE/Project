# Use case : Admin 
![Admin](https://user-images.githubusercontent.com/78169319/169881440-fbad9429-9af9-43c9-8fcf-4b7d0a4e70c7.png)

# Use case : Facility Manager 

![Facility Manager](https://user-images.githubusercontent.com/78169319/169882233-4f88bec8-d8e0-41bb-935f-292bef00d024.png)

# Use case : Students
![Student](https://user-images.githubusercontent.com/78169319/169883641-be73d752-cd28-4401-9065-5d5dde5d790d.png)

# General Use Case.
![General Use Case](https://user-images.githubusercontent.com/78169319/169891418-2cc4c4ee-3de8-4aa6-a6f3-545e76ab97d0.png)

# Use Case Extended.


| Use Case (UC_1.1)  | Create Employee Profile | 
| ----- | ---------- | 
| Scope: | EC application |
| Level: | User Level |
| Intention Context:  | Each time a new employee comes to the company he must have an account. |
| Minimum Guarantees:  | 	Account is created but not used. |
| Success Guarantees:  | ccount is successfully created, given to the employee and used by the employee. | 
| Primary Actor:  | Admin |
| Stakeholder’s interest:  | To simplify the work for specific actions and save time. |
| Precondition:   | At least 1 employee. |


| Use Case (UC_1.2)  | Delete Employee Profile | 
| ----- | ---------- | 
| Scope: | EC application |
| Level: | User Level |
| Intention Context:  | Each time a new employee leaves the company the account must be deleted.|
| Minimum Guarantees:  | Account is not deleted.|
| Success Guarantees:  | Account is successfully deleted. | 
| Primary Actor:  | Admin |
| Stakeholder’s interest:  | To simplify the work for specific actions and save time. |
| Precondition:   | At least 1 employee. |




| Use Case (UC_1.3)  | Check Employee Payments | 
| ----- | ---------- | 
| Scope: | EC application |
| Level: | User Level |
| Intention Context:  | As times as necessary check the employee payment.|
| Minimum Guarantees:  | Administrator doesn’t check.|
| Success Guarantees:  | When necessary he checks the payment of specific employees. | 
| Primary Actor:  | Admin |
| Stakeholder’s interest:  | To simplify the work for specific actions and save time. |
| Precondition:   | At least 1 employee. |




|Use Case (UC_1.4)|	Control Attandance|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:|	User Level|
|Intention Context:|	The student keeps track of attandace on his school.|
|Minimum Guarantees:|	Student checks the page once in a while.|
|Success Guarantees:|	Student checks the page frequently.|
|Primary Actor:	|Student|
|Stakeholder’s| interest:	To simplify the work for specific actions and save time.|
|Precondition: |	At least 1 check.|

|Use Case (UC_1.5)	|Control Financial Records|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:|	User Level|
|Intention Context:|	For admin to be informed about the financial state of the its company.|
|Minimum Guarantees:|	Admin checks once in a while financial records.|
|Success Guarantees:	|Admin checks financial records frequently.|
|Primary Actor:|	Admin|
|Stakeholder’s interest:|	To simplify the work for specific actions and save time.|
|Precondition: |	At least 1 financial record.|

|Use Case (UC_1.6)|	Control Security System|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	User Level|
|Intention Context:|	For admin to have a clear view of environments of the ongoing traffic.|
|Minimum Guarantees:	|Admin checks once in a while traffic.|
|Success Guarantees:|	Adminchecks traffic records frequently.|
|Primary Actor:|	Admin|
|Stakeholder’s interest:|	To simplify the work for specific actions and save time.|
|Precondition:| 	At least 1 traffic record.|

|Use Case (UC_2.1)|	Fill daily reports for traffic|
| ----- | ---------- | 
|Scope: |	EC application|
|Level:	| User Level|
|Intention Context:|	For the department header to report to the admin about the daily traffic.|
|Minimum Guarantees:|	Administrative Technicians reports shortly daily traffic.|
|Success Guarantees:	| Administrative Technicians reports a complete daily traffic.|
|Primary Actor:|	Administrative Technicians |
|Stakeholder’s interest:|	To simplify the work for specific actions and save time.|
|Precondition: |	At least 1 employee and 1 traffic record.|

|Use Case (UC_2.2)|	Register workers and working-hours|
| ----- | ---------- | 
|Scope: |	EC application|
|Level:|	User Level|
|Intention Context:|	In order to keep track of each employee work.|
|Minimum Guarantees:	|Administrative Technicians registers only a few.|
|Success Guarantees:	|Administrative Technicians registers frequently.|
|Primary Actor:	|Administrative Technicians|
|Stakeholder’s interest:	|To simplify the work for specific actions and save time.|
|Precondition: |	At least 1 employee.|


|Use Case (UC_3.1)|	View Attandance|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	|User Level|
|Intention Context:	|The Facility Manager can be informed about the student’s Attandance .|
|Minimum Guarantees:	|Facility Manager visits the app only once.|
|Success Guarantees:|	Facility Manager visits the app when he need and takes information.|
|Primary Actor:|	Facility Manager|
|Stakeholder’s interest|	To simplify the process of checking attandance.|
|Precondition: 	|At least 1 student and 1 attandance.|

|Use Case (UC_3.2)|	View Projects|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	|User Level|
|Intention Context:	|The Facility Manager can be informed about the student’s project .|
|Minimum Guarantees:	|Facility Manager visits the app only once.|
|Success Guarantees:|	Facility Manager visits the app when he need and takes information.|
|Primary Actor:|	Facility Manager|
|Stakeholder’s interest|	To simplify the process of checking project progression.|
|Precondition: 	|At least 1 student and 1 project.|


|Use Case (UC_4.1)|	View Attandance|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	|User Level|
|Intention Context:	|The Student can be informed about the Attandance .|
|Minimum Guarantees:	|Studentvisits the app only once.|
|Success Guarantees:|	Student visits the app when he need and takes information.|
|Primary Actor:|	Student|
|Stakeholder’s interest|	To simplify the process of checking attandance.|
|Precondition: 	|At least 1 student and 1 attandance.|

|Use Case (UC_4.2)|	View Discounts|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	|User Level|
|Intention Context:	|The Student can be informed about the new discounts.|
|Minimum Guarantees:	|Studentvisits the app only once.|
|Success Guarantees:|	Student visits the app when he need and takes information.|
|Primary Actor:|	Student|
|Stakeholder’s interest|	To simplify the process of checking avaiable discounts.|
|Precondition: 	|At least 1 student and 1 discount.|

|Use Case (UC_4.3)|	View Balance|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	|User Level|
|Intention Context:	|The Student can be informed about theier balance.|
|Minimum Guarantees:	|Studentvisits the app only once.|
|Success Guarantees:|	Student visits the app when he need and takes information.|
|Primary Actor:|	Student|
|Stakeholder’s interest|	To simplify the process of checking account balance.|
|Precondition: 	|At least 1 student and 1 balance.|

|Use Case (UC_4.4)|	View Time table|
| ----- | ---------- | 
|Scope:| 	EC application|
|Level:	|User Level|
|Intention Context:	|The Student can be informed about the time table.|
|Minimum Guarantees:	|Studentvisits the app only once.|
|Success Guarantees:|	Student visits the app when he need and takes information.|
|Primary Actor:|	Student|
|Stakeholder’s interest|	To simplify the process of checking time table.|
|Precondition: 	|At least 1 student and 1 time table.|


