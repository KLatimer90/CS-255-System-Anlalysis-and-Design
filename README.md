# CS-255-System-Anlalysis-and-Design
CS-255 System Anlalysis and Design

•	Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
Our consulting company has been tasked with working with the company DriverPass. DriverPass has identified a need in the market for providing customers with online courses, lessons, a driving training. There is large failure rate at the DMV for students taking their driver’s written exam and driving test. DriverPass has filled this niche market and have asked us to facilitate their online course work. These online classes will give the necessary tools to driving students and will reduce the likelihood of test failures both on the driving exam and written exam. 
•	What did you do particularly well?
So far, our team has done an excellent job of providing a road map with the various UMLs so our development team can implement everything the stakeholders at Driverpass have requested and imagined, giving them an excellent and secure product. 
•	If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
There are slight tweaks we may have done to our product, but overall, our team did an outstanding job implementing all of the requirements that the stakeholders at DriverPass requested after our multiple meetings. 
•	How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
We had multiple meetingswith the stake holders at DriverPass to establish what their technical and nontechnical needs would be. 
Nonfunctional Requirements
We will need to determine the nonfunctional requirements for our client as DriverPass. Those nonfunctional requirements will be performance requirements, Performance Constraints, Accuracy and Precision, Adaptability, and Security:
Performance Requirements
 
•	The stakeholders at Driver Pass have indicated that they do not want to deal with back up and security. They are open to the idea of running the web-based platform over the cloud. The stakeholders have also requested that data can be accessed remotely in order to obtain updated reports in addition to updates from the DMV. We should utilize a 3rd party cloud service provider such as Amazon Web Services to accomplish this goal. 
 
Platform Constraints
 
•	Web based learning platform at DriverPass should be able to run on both Windows and Apple computer or laptop platforms. One constraint we have identified at DriverPass is the large amount of data that will be videos, lesson plans, and other data rich items. Due to the large amount of data, we will be primarily focusing on computer based operating systems and not mobile applications at this time. The back end cloud databases must have a high degree of security and information should be encrypted, as some sensitive information such as driver’s license numbers, social security and addresses with be stored on our database. Utilizing a cloud service will facilitate these needs, in addition to having the ability for rapid scalability in the future. 
 
 
Accuracy and Precision
 
•	Users will create their own user identification. The system will check to ensure that particular identifier has been chosen or not. If the identification user name has not been selected, the system will create the account and prompt the user to enter a password. Passwords will be case sensitive, at least 8 characters or longer, will contain 1 or more numbers, and will have at least one special character (ie: !@#$%^&*). If the user name had already been selected by another user, the system will alert the customer and prompt them to enter another username. If issues arise, such as a forgotten password, locked account the system will alert the Administrator who will determine the next course of action. The Administrator will have the ability to reset passwords and reactivate accounts.
 
Adaptability 
 
•	IT administrators at DriverPass will have the ability to make updates to the system and its data. The amount of downtime should be minimal if we utilize a 3rd party cloud provider. The IT Administrators will have the ability to delete data that is no longer needed, modify user accounts, and deactivate/ delete user accounts. 
 
Security
 
•	Users will need to log in with their credentials, which is a username and password that is at least 8 characters long, contains a lowercase and uppercase value, a special character, and at least 1 number. Data exchange should be encrypted, as sensitive information exits on the database. If a user forgets their password, they will contact IT Administrators to have their passwords reset. A user will, get no more than 5 attempts to enter the correct credentials. An account will be locked if more than 5 attempts are made. IT administrators will have the ability to reset passwords and unlock suspended accounts. 
Functional Requirements
Functional requirements are what they system will be doing. We need to explicitly determine every function of our system in order to plan how the system will interact with its various actors and function. The system shall:
•	The system shall be accessible through laptop and desktop computers.
•	The system shall utilize unique user credentials to so unauthorized access does not occur.
•	The system shall validate user credentials when a user logs in. 
•	The system shall have a note taking feature for teachers. 
•	The system shall have the ability to add/delete/update customer accounts on as needed basis.
•	The system shall secure sensitive data through encryption. 
•	The system shall have easy to understand layouts for students and teachers.
•	The system shall have user profiles with photoidentification. 
•	The system shall be accessible to administrators and managers whether on or offline. 
•	The system shall have a function for scheduling lessons and road tests. 
•	The system shall have a database that includes lesson plans, practice tests, and videos.
•	The system shall display progress, grades, and items of improvement where students need more work.
The system shall obtain updates from the DMV for driving policies and regulations.
•	How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
Security was a concern and we established the following:

Users will need to log in with their credentials, which is a username and password that is at least 8 characters long, contains a lowercase and uppercase value, a special character, and at least 1 number. Data exchange should be encrypted, as sensitive information exits on the database. If a user forgets their password, they will contact IT Administrators to have their passwords reset. A user will, get no more than 5 attempts to enter the correct credentials. An account will be locked if more than 5 attempts are made. IT administrators will have the ability to reset passwords and unlock suspended accounts. The system will also utilize a 3rd party could service. This will assist in remaining secure by having state of the art security, without the need for new, expensive hardware that requires periodic downtime for updates and maintenance. 
