![newlogo](https://user-images.githubusercontent.com/78169319/163966659-1fabdeaa-164f-45aa-82c0-3f6408d8e9f9.png)



# Brief description. 
Easy Check is system that focuses more in students’ participation in classes. What we mean by that is, students can use their students’ cards to check in for attendance. Not only that but the software is integrated to be used for other functions. Easy check can be used to hold currency for the student and be used inside and outside the university campus. A student can use EC (Easy Check) to purchase a drink or something to eat on all markets that are partnered with EC, not only that, but all EC users can get discounts in electronic shops, for example: getting a 15% discount on a new laptop.
# Requirements.
-	Proposing a contract to all big markets in the country so EC (Easy Check) won't have any problem with purchases and make the transaction easy!
-	Getting in contact will locally banks to be able to hold currency in students card.
-	Getting permission from the city hall so students can get free or discounted bus trips depending on the distance.
-	Proposing a contract to all electronic shops so the students get the discount for any hard ware purchased. (Note, each shop has a different discounted price on their products, so the students have to choose their shops depending on what percentage they find more pleasing)

# User Characteristics. 
EC has 4 main types of users:
-	Administrators
-	Administrative Technicians
-	Facilities Manager
-	Students


### Administrators:
#### The administrators are the CEO-s of Easy Check, F.S, N.K and X.L. They are the persons that are in charge of everything and where a data, bugs and new features. That means they are in charge of changing the software according to the end user's request.
> The task's that admins can do are as following:
-	Create/Delete/Edit profiles of employees
-	Checking payments for all employees
-	See all connected devices
-	Check the traffic
-	Control all the financial records daily/monthly/yearly
-	Check any misbehavior of the software


### Administrative Technicians:
### Administrative technicians typically produce documents for correspondence, reports, and memos, among others. They are also in charge of filing, both with a computer and manually. They also have management responsibilities.
>The task that Administrative Technicians can perform are as following:
-	Report to the admin all bugs that are submitted from the software
-	Check the number of bugs monthly and make a graph of it
-	Register new workers and gather all working-hours to put them on the database
-	Arrange meetings with universities representative

### Facilities Managers
### Facilities managers (Teachers/Contracted workers) oversee the physical building where Easy Check is applied. They make sure the system is up to date with the university building, new books added to the library, timetable. Additionally, they oversee the security of the building and any software exploit.
> The task that Facilities Managers can perform are as following:
-	Update the timetable
-	Make new announcements that are school related
-	Update the books section of the system
-	Report any bugs to Administrative Technicians

###  Students
### Students (the main users of the system) are the reason this system was created and their job is to use EC (Easy Check) to the full extend.
>The task that Students can perform are as following:
-	Check timetable
-	Check new books added to the library
-	Apply for new Students Clubs
-	Check all announcements posted from the school/admins
-	Check their balance
-	Adding funds to the balance
-	Check all discounts from partnered shops
-	Check the time of bus stops
-	Check attendance
-	Create a group chat with their friends
-	Request an appointment with a teacher at a given time


# Assumptions.
-	The CEO-s will have all time access to every data that is submitted by Administrative Technicians and Facilities Managers
-	The devices that the system will be operable for phone users must be IOS/Android and for pc users must be Windows, IOS and Linux OS
-	Good internet connection
-	Every important announcement made by CEO-s will be displayed in real time for all users

# Constraints.
-	Users must be members or affiliated with contracted university
-	Every user must at least know one of the OS that Easy Check can be accessed through
-	All user must be logged in before using the software

# Dependencies. 
-	Only CEO-s and authorized personnel that are directly assigned from admins can have access to all data
-	If there aren't any available CEO-s trusted personnel should take their place for the duration of time that at least one CEO is available
-	CEO-s have the right to oversee all operation from all users and take action If they see any exploits from them


# Interface Preview 
![Desktop - 3](https://user-images.githubusercontent.com/78169319/173233426-9add1f23-50f8-4984-b889-13c971018b3e.png)



# Functional requirements.
| Req#  | Requirement | Comments | Priority | Date Rvwd | SME reviewd/approved |
| ----- | ----------- | -------- | -------- | --------- | -------------------- | 
| BR_01  | The software should support activity tracking  | This helps on time organization  | 2 |  |  |
| BR_02  | The admin and also the transaction manager should be able to check the all employee wages. This data will be best to be represented in tabular form. | Organization  | 1 |  |  |
| BR_03  | Services should be available in the software. | To help users by showing the variety  | 2 |  |  |
| BR_04  | Admin must be able to create/delete the employees profiles. | The data of employees must remain private.  | 1 |  |  |
| BR_05  | The software may provide an student chat system (encrypted). | Sending annoucments to each other or sharing grades and attandance.  | 2 |  |  |
| BR_06  | The admin and the head of security department can have unlimited access in security system, but first they must be logged in by entering a password and a fingerprint. The security have limited access only in the working hours and the only operation allowed to be performed by them is trafick-checking. Admin and head of security department can turn on/off the system, check the previous registrations, etc. | Layer of security  | 1 |  |  |
| BR_07  | The admin and also the finance manager should be able to check the all employee wages. | Organization  | 1 |  |  |
| BR_08  | Super-admin and the finance manager must have access in the financial records of the company. They can add/delete and also edit financial records related with the business.  | Organization  | 1 |  |  |
| BR_09  | Facilitie managers can update the timetable every month | Update and organization  | 1 |  |  |
| BR_10  | Administrative technicians can cerate/delete employee accounts  | Organizatoin  | 1 |  |  |
| BR_11  | Facilitie managers can apply penalties to students through the software | Organization  | 1 |  |  |
| BR_12  | Contracted shops can enter their disscounts daily for the students to see | Update and information | 1 |  |  |
| BR_13  | Facilitie managers and students can track the attandace | Update and information  | 1 |  |  |
| BR_14  | Banks and finance manager can update the students balance according to request | Update and organization  | 1 |  |  |
| BR_15  | Software will detect threat key words from the chat system that may indicate to disaster | Security  | 1 |  |  |
| BR_16  | Admin and security manager will be alerted immediately from system if the keywords are detected and will have one time access to check the threat level | This minimizes the A.I mistake bans of users  | 1 |  |  |
| BR_17  | Students can check the scholarship status | Information  | 1 |  |  |
| BR_18  | Student can check the bus timetable | This will help them manage time to get ready for school  | 1 |  |  |
| BR_19  | The software should support employee payroll system. | Organization  | 1 |  |  |
| BR_20  | Facilitie managers can create chats with students to make announcements | Information  | 1 |  |  |
| BR_21  | Facilitie managers can make videocalls lessons through the software with students in case of health issues  | Makes teaching when sick more convenient  | 1 |  |  |
| BR_22  | Admins and administrative technicians can make annoucments for new sfotware updates. | Update and information  | 2 |  |  |
| BR_23  | Admins and administrative technicians can update the software according to users needs | Update and organization  | 1 |  |  |
| BR_24  | The sfotware will always have a backup for users who forget their passowrds and emails | This will keep users accounts safe from getting lost | 1 |  |  |




# Non-Functional Requirements.
# Product Requirements.
-	EC will only be available for Android and IOS phone systems.
-	The system will be easy to use so the user won't have any problems during the whole time he/she is still a student or an employee.
-	The administrator page will be organized in different sectors for each of company’s processes including: attendance, finance, security, chat etc. It is thought that when the administrator will be logged in, all the sites where he has access will be displayed in the middle of the screen separated in squares, so not to create any confusion. The same thing will be with the manager’s page.-

# Accessibility
> EC can be used everywhere as long as there is internet connection and the device has sufficient power supply.
# Responsiveness
> The application is thought to be extremely responsive and fast too..
# Flexibility
> The application is thought to adapt the updates very easy but also deal with errors/problems as quick as possible
# Effectiveness
> 1.	This application will be easy to use and understand and as user-friendly as possible.
> 2.	In case the user deals with an error, the messages will be easy to understand and also associated with a step-by-step procedure in order to get rid of it.
# Efficiency:
> 1.	The application is going to be very efficient and 0 time-consuming, meaning that each user will fulfill his tasks super-fast and in the best case with no errors/warnings at all.
> 2.	The interface will also be very easy and user-friendly with no complicated buttons or actions.

# Performance Requirements
> 1.	Since EC is going to be installed in a computer/laptop/mobile, the data will be delivered in real-time, and it will only be accessible inside company’s environment it will require good internet connection, and new tech devices in order to reach its best performance, but also with mid-range devices it will work just fine.
> 2.	The bigger the space, the more will be the users therefore the better the performance.

# Space Requirements
> 1.	The app will be able to handle at least 1000 users at a time, and the database system should handle at least 600-800 users at any given time.
> 2.	Maximum user load: 400.
> 3.	Per-user memory requirement: 2-4 GB RAM.
# Availability
> 1.	Internet access is necessary.
> 2.	The application will be available 24/7.
# Maintanence
> 1.	The app will be updated, when necessary, in order to process all the operations in real time.
> 2.	In case the system will crash, the app should not display anything to the user except an error message “Something interesting is happening! Please come back to check what has happened!”
> 3.	If the crash happens the system should start as soon as possible.

# Integrity
> 1.	The personal information must be available only for the super-admin.
> 2.	The super-admin account is the only one responsible for adding/deleting new employee accounts.
> 3.	All users should provide personal credentials to log in into the system and should be authenticated before accessing their own profiles.


# Security
> 1.	When the super-admin creates a new profile, an informative email must be sent to the employee to let him know about the action.
> 2.	When a new user is logged in, a randomly generated password must be sent to it by the admin email.
> 3.	A special encrypted code will be given to student’s card, that will make it hard to clone the card
> 4.	If the card is decrypted the system will check if the card has entered the school before and check if it has left depending on the occasion the system will decide if the card will pass or not.


# Domain Requirements
EC is going to be an application that can be easily downloadable from both AppStore and Play Store, and is going to be an organizational app exclusively for the “Easy Check”. The purpose of the software is to make the student life easier. The application is thought to be divided in 2 parts for use, one use will be from the company workers (CEO, managers, employees) and the other one will be for clients but with a limited actions (like viewing attendance and checking discounts). The app will be mostly student-use oriented. In order to access the functionalities of the app the user must firstly be logged in with the email that they have been registered to the school and the whole data will be manipulated into EC’s servers.





# Software Designs
> Successful log in
1. The user will manually fill the email input box.
2. The user will manually fill the password input box.
3. The app will check inputs with database records, if they match the user is successfully logged in.
4. In the users screen will be displayed the home page of his/her own page.

> Failing to log in
1. The user will manually fill the email input box.
2. The user will manually fill the password input box.
3. The app checks the input with the database records, inputs doesn’t match.
4. A message will be displayed to user, asking to enter the wrong input again.
5. User remains at the log in page.

### Admin Scenarios
> Creating the employee account
1. The administrator is firstly logged in.
2. He/She clicks on “Employee Accounts” section, on a left column in the screen where are listed all sections.
3. After page is opened it selects the option “Create” from 3 options, “Create”, “Delete”, “Update”.
4. The administrator starts filling the field with information about the new employee.
5. After adding all the information, he clicks the button “Confirm”.
6. A message “Are you sure you have entered the correct information” will be shown in the screen.
7. Administrator clicks “Yes” and the account is successfully created.

> Deleting the employee account
1. The administrator is firstly logged in.
2. He/She clicks on “Employee Accounts” section, on a left column in the screen where are listed all sections.
3. He/she searches for the name of the employee at the search bar.
4. When found, the administrator clicks on the button “Delete”.
5. A confirmation table will be shown in the middle of the screen with message “Are you sure you want to delete it?”
6. After confirmation, the account will be deleted but not permanently it will be sent into a bin. 

> Controlling employees payments
1. The administrator is firstly logged in.
2. He/She clicks on “Employee Accounts” section, on a left column in the screen where are listed all sections.
3. He/she searches for the name of the employee at the search bar.
4. Inside the account is the “Monthly payment” field.

> Control financial records
1. The administrator is firstly logged in.
2. He goes to section “Finance” on a left column in the screen containing all sections.
3. Another page organized in square will be shown where each square represents one financial record like: Sales revenue, Service Revenue, Unpaid Revenue, Miscellaneous expense, Accounts receivable, Income Summary, Retained Earnings etc.
4. The administrator click to one of the squares and the table containing information for that specific record will be shown on the screen.

### Administrative Technicians Scenarios

> Transaction & Finance Manager
1. He is logged in.
2. A page organized in square will be shown where each square represents one financial record like: Sales revenue, Service Revenue, Unpaid Revenue, Miscellaneous expense, Accounts receivable, Income Summary, Retained Earnings etc.
3. The manager click to one of the squares and the table containing information for that specific record will be shown on the screen.

> Security Manager
 1. Security Manager is firstly logged in
 2. A page organized in square will be shown where each square that are linked to different functions of security like : Check trafic,update firewall,alert admins,report bug etc.
 3. He can set on/off the server depending on the threat.

### Facilities Managers Scenarios
> Checking Attandace
1. Facilities Manager is firstly logged in.
2. In front of him will be shown a button “check  daily report” by default.
3. When clicked it will open a form with necessary fields to fill (Date, name, surname, class, etc).

> Check deadline of projects 
1. The facilities manager is firstly logged in.
2. In the left column of sections, he will click on “Projects” section.
3. After clicking a table with the name of project, its code, deadline and details columns will be shown on the screen.
4. At the search bar at the top of the page checks for project by entering its name or code and then check the deadline.

> Permissions for sick leaves 
> Request accepted
1. A notification will be sent to the Facilities Manager phone.
2. The Facilities Manager logs in.
3. He goes to section “Requests” on a left column in the screen containing all sections.
4. He reads the request sent from the student.
5. He accepts the request by clicking “Confirm”.

> Request denied
1. A notification will be sent to the Facilities Manager phone.
2. The Facilities Manager logs in.
3. He goes to section “Requests” on a left column in the screen containing all sections.
4. He reads the request sent from the student.
5. He denies the request by clicking “Deny”.
6. An input box will be shown in the screen with description “Reason”.
7. Facilities Manager fills the box with a brief explanation why the request was denied and press “Sent”.
8. The message is sent to the student.



### Students Scenarios
1. The client opens the app
2. He goes at the bottom of the page and selects the option “Use it as a stduent”
3. The stduent home page will be shown on the screen with product pictures and advertisements displaying by default.






# Quick Links to Diagrams. 
> Check Activity Diagrams [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Activity%20Diagrams.md)</br>
> Check BPMN [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/BPMN.md)</br>
> Check Class Diagrams [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Class%20Diagram)</br>
> Check Communication Diagrams [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Communication.md)</br>
> Check Component Diagram [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Component%20Diagrams.md)</br>
> Check DFD [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/DFD.md)</br>
> Check ERD [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/ERD.md)</br>
> Check Object Diagrams [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Object%20Diagrams.md)</br>
> Check Package Diagram [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Package%20Diagram.md)</br>
> Chek Rational Schema [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Rational%20Schema.md)</br>
> Check Sequence Diagrams [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Sequence%20Diagrams.md)</br>
> Check State Diagrams [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/State%20Diagrams.md)</br>
> Check Use Cases [here !](https://github.com/Group-14-SWE/Project/blob/main/Diagrams/Use%20Case.md)</br>




