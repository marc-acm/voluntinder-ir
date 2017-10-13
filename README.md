## Application Design




Sample of Slack Conversations
![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER-SLACK.png)


Demonstrate your ability to break down the problem and design a solution.

1. One page summary of your application including problem definition, solution. -- **DONE**
2. Determine the appropriate client technology, development tools, and platform for writing the UI -- **Maybe talk about why we chose React + React Redux + Whatever and then explain the folder structure and the special components maybe?**
3. Wireframes for at least 3 screens. **Marc**
 


### Wireframes
Link: https://www.figma.com/file/C3NVkU1709nBjPHMeBn0zyKT/3rd-Term-Final-Project


For the wireframes we have created two types, one for the desktop/laptop design and the other is for mobile devices.


The first four screenshots are for the desktop/laptop design.  The prospect is to provide a four-frame application consisting of the following:

- Landing Page
- Opportunities
- Details of A Specific Opportunity
- Profile Page

The application is designed with an option of a static bar to be shown throughout the three frames. 

##### Landing Page
This contains the Sign-up Form for people who desires to have their profile match with a specific project.

![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER-WIFEFRAME-DESKTOP%201.png)

 
 
##### Project/Opportunities
The second frame provides a view of the different available projects.

![alt text align](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER-WIFEFRAME-DESKTOP%202.png)


##### Specific Opportunity
This page will show the details for a single specific project.

![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER-WIFEFRAME-DESKTOP%203.png)



##### Profile Page
This frame provides details of the volunteer.
![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER-WIFEFRAME-DESKTOP%204.png)




##### Below is the Mobile Design with the same four frames



![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER%20-%20WIREFRAME%20-%20MOBILE%201.png)

![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER%20-%20WIREFRAME%20-%20MOBILE%202.png)

![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER%20-%20WIREFRAME%20-%20MOBILE%203.png)

![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER%20-%20WIREFRAME%20-%20MOBILE%204.png)





### User Stories
Link: https://trello.com/b/MnJGa9TB


For the user stories, we have three (3) types of users namely:  User (Volunteer), Institution(NGOs) and Admin


-- Volunteer
For this type of user we wanted our volunteer to be able to have the basic functions of signing-up /logging-in.  Also, to have the capability to view, filter and select opportunities where they can submit their application that matches their specific skills and interests.



-- Institutions (eg. NGOs)
An example for this type of user are NGOs.  Organizations which can post their opportunities with detailed information.  The functions of these users include the ability to accept or decline an applicant and be able to add and remove opportunities depending on their schedules and status of activity.  



-- Admin 
This is the super user.  This has the control of the overall performance of the app.  The admin has the all the rights and privileges to properly monitor the process and design of the application.


Figure below is the Trello Board for the Voluntinder User Stories
![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER-TRELLO.png)



### Entity Relationship Diagram (ERD)
Link: https://www.lucidchart.com/invitations/accept/02cb0d00-8d1a-4c97-b9b9-ea00c17a9b70


An entity relationship diagram (ERD) shows the relationships of entity sets stored in a database.

For this application, we made use of Information Engineering Style to express cardinality showing how many occurences of relationships among different entities.

As shown in the figure below, there are three entities, namely the Vounteer, Institution and Opportunity establishing their inter-relationships.

The Volunteer, with its name, email and phone_no., has the functions of signing-up.  Once done with this, a user can already filter the many opportunities available but may only be able to select only one opportunity and submit a single application for the chosen project.

As for the Institution, with its ability to create and delete, can have one to many opportunities.

On the opportunity side,  with each specific opportunity, it can have one or many volunteers but a particular opportunity or project must only belong to a specific organization or institution. 


The connection between Volunteer and Institution is only through the created Opportunity. 


![alt text](https://github.com/marc-acm/voluntinder-ir/blob/master/images/VOLUNTINDER%20-%20ERD.png)


   