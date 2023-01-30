# Vision

What is the vision of this product? 
The vision of this project is to create a bug tracking app for developers looking to synergize their workflow through tracking bugs as well as keeping co-developers in the loop with a project.

What pain point does this project solve? 
This project functions to be an asset for developers looking to streamline their workflow & bug documentation. Managers can benefit from this app as well by staying in sync and updated with the bugs developers experience in a project.

Why should we care about your product? 
This application benefits dev teams in terms of synergy, communication, context to workflow, etc.

# Scope (In/Out)
IN - What will your product do
- Allows users to log and submit bug ticket
- Collaborate and coordinate on how to apporach and resolve bugs
- Allows manager to visualize employee activity and bug data
- Allows users to visualize bugs on their application

OUT - What will your product not do.
- This app will not be able to solve bugs for a given project

# Minimum Viable Product vs Stretch Goals
What will your MVP functionality be?
MVP will include:
- Submission for tickets about bugs
- Full CRUD Functionality
- RBAC implementation
- Friendly UI components

What are your stretch goals?
Stretch goals include:
- See tickets of other admins without explicit permission
- Be able to add other admins to specific projects
- Be able to CC other users who need to know the status of a bug
- To oversee all bug data for every user
- Add attachments in regards to my bug
- Have the option of having daily/weekly e-mail/Slack summaries
- Have the option to receive a notification when a ticket is updated or closed
- Have a public facing bug tracker where i can make first open source contributions
- Be able to have a separate account for my company to track bug issues


# Stretch
What stretch goals are you going to aim for?
- Have the option to receive a notification when a ticket is updated or closed
- Add attachments in regards to my bug
- To oversee all bug data for every user
- Have the option of having daily/weekly e-mail/Slack summaries



# Functional Requirements
List the functionality of your product. This will consist of tasks such as the following:
- ADMIN: Full CRUD functionality for user profiles & bug data
- MANAGER: Full CRUD operations for team users & bugs
- USER: Submit ticket for discovered bug, can delete tickets made by mistake, update status of ticket, have access to bug tickets (w/ filters)

# Domain Modeling & Data Flow
[SEE_UML](https://www.figma.com/file/Ag96kOVzQHghj8sYEPumyd/Bug_Tracker?node-id=0%3A1&t=rvqvzvG2skKYsdRV-0)


# Non-Functional Requirements (301 & 401 only)
Non-functional requirements are requirements that are not directly related to the functionality of the application but still important to the app.

Security: Role based accesses are available according to functional requirements. Such as ADMIN being able to create or modify stories and USERS being able to traverse through a story
Testability: Middleware as well as error testing functions to supplement handling errors that occur within and throughout the building process
