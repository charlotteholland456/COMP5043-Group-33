**Meeting Minutes - First Meeting**   
Date: Wednesday 23rd September 2025     
Time: 13:00pm till 14:00pm     
Location: Online     

Time was extended for an extra 2 and a half hours as we ended up discussing the meeting topics in depth. However, we started the meeting at 13.00pm as planned

Attendees to attend:    
- Charlotte Smale-Holland (19313496)   
- Ryan Hogan (19390270)   
- Gauthier Lihau (19207032)    
- Gonzalez Rodrigues (19271262)     

---

State of the completion of actions:
- We set up our GitHub repository and sorted out a communication medium for the Software Engineering project. 
- Yesterday, we overviewed and analysed  the case study for our project. 

Allocation of the subsystems:
- USU Student App: Charlotte Smale-Holland 
- Student Union Management System: Ryan Hogan
- USU Operating System: Matheus Gonzalez
- Society Leader App: Gauthier

**Functional Requirements Grouping:**

Gauthier - Society Leader App:
- The society leader will receive a notification when a new application is approved. 
- Update society registration data. 
- Allow the society leader to decide whether joining the society will be approved manually or automatically. 
- View information about members and communicate with them ( broadcast or individually). 
- Submit a request of termination to the society. 
- Updating events on any of the data and adding information. 

Charlotte - USU Student App
- The system will enable students to search for societies, subscribe to information about the society, and join a society, if they are part of the university student union. 
- The system will allow the students to quit from society. 
- The system should enable students to submit messages to communicate with a society if they are a member. 
- The system should allow students to fill an application for new societies. 
- The system should allow students to search for events, view event details, and register for them. 

Matheus - USU Operating System
- The system should allow USU staff to review and approve applications to its memberships. 
- The system should allow approval of updates of USU registration data. 
- The system should allow approval of termination of USU membership from the student union. 
- The subsystem should have a functional requirement for making announcements and updating events. 
- The system should provide a facility for the Union Officers on behalf of the union events. 

Ryan - Student Union Management System
- Enable the union to update data registered to the USU. 
- Enable the union to request the termination of its member to USU. 
- Allow the union to approve requests of registered data changes.
- Let the union monitor operations of societies. 

**Data Dependencies on Sub-Systems:**

USU Student Union Application (Data Required)
Registration to University-Specific Student Union:
- Student Name, Student ID Number, Study Program, Year of Start, and Length of Study.
Initiation of New Society:
- Name of Society, Society Theme, Organisation Team, Contact Addresses 


Student Union Management System (Data Required)
Applying to USU:
- Student union data (Name, Address), Union representative details (Student ID, Name, Role), and Union Officer Details (USU ID). 
Approving New Societies (This data is required and depends):
- Name, Theme, Organisation Team, Contact Address
Management of Events:
- Name, Theme, Connection to other events, Organisation Team, Venue, Date and Time. 


USU Operating System (Data Required):
Approval of USU membership [Required from Subsystem 2]:
- Student union data (Name, Address), URL, Union representative details (Name, contact details, student ID, role, USU ID), Union officer details (Names, contact details, USU ID)
Management of USU Events:
- Name, Theme, Connection to other events, Organisation team, Date and time, Venue, Scope. 


Society Leader App (Data Required)
Management of Events: 
- Event theme, Date and time, Venue, Organisation Team, Scope, Connection to events, and Promotion score and materials, 

**Data required by one subsystem but must be provided by other subsystems**

- In the meeting we agreed that when a student initiates a new society on a sub-system, the student includes the society details, such as the name, event theme, and contact information. Afterwards, the data would then be shared to the Student Union Management System, so the officers can review and potentially approve. This data is dependent because the societies would not be able to be approved, if the Student Union Management System did not have access to it. 

Actions to take place after the meeting:
- We will choose upon our functional requirement for the requirement analysis.
- Do research into the quality attributes while referring to the functional requirement, so we can discuss them in the upcoming meeting. 

Issues to be solved:
- No issues have occurred with our groupwork project, so we do not need to do further research or contact our lecturer for support. 

---

Date/Time of the following meeting - Wednesday 1st October 2025 (13:00pm till 14:00pm)
