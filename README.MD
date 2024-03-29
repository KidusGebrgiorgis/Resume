# To-do-list:
Objective: To create a program that tracks all tasks completed and pending and rewards your progress through leveling

## Table of contents
- [User Story](#User-story)
- [Objects and Functionality](#Objects-and-Functionality)

## User story
1. The to-do-list will begin by prompting a user to login
    - username and password will be validated.
    - on success user info will be displayed.
        - includes: 
            - Name of user.
            - level of user next to name.
            - buttons to add milestones.
                - prompt a user to another screen to fill out relevant fields
                - Fields such as: Milestone description, priority, projected timeline, tasks to reach milestones
                    - Task can be added by clicking a button saying add tasks
                        - once tasks are added a  2 button next to the task will have edit or delete
                - Once all fields are generated a prompt to create tasks will be enabled a cancel button will also be next to this button and can be clicked anytime
                - Milestone will then be added to the list
            - under the button will be a list of Milestones ranked by priority level and timeline and will display a description and percentage of completion
                - at the end of each milestones will be two buttons edit or delete/quite
                    - quiting will make you lose exp
                    - you can edit the timeline and tasks associated with the milestone
                - in front of the milestone button will be a drop down button to hide or show tasks associated with the milestone 
            - when milestones are completed on the condition all tasks associated with it are done exp will be granted to the user and level bar will be updated and a prompt will be shown to get your feedback on what you did good, bad, and what you could do better moving forward
            - A menu bar will displayed showing Three things History, user profile, and to-do-list
                - history will contain all the completed milestones and the response provided after its completion
                - user profile will contain name, level, milestones completed, milestones quite, and milestones extended
                - to-do list will be the window shown when logging in

## Objects and Functionality
- Global functions:
    - displaying objects
    - storing tasks

- objects for backend:
    - user
        - login
        - display function
    - Levels
        - Functionalities
            - Updating levels
            - storing levels
            - displaying 
    - To-do-list:
        - Functionalities
            - adding milestones
            - adding exp for milestones completed 
            - ordering milestones based on timeline
            - archived tasks(completed tasks) 
    - milestones
        - Functionalities:
            - creating milestones
            - updating status of milestones(percentage based on task completion)
            - storing tasks
            - adding tasks
            - completing tasks
            - completing milestones
    - Tasks:
        - functionalities
            - adding tasks 
            - storing tasks
            - updating tasks 
## Acknowledgment
- Kidus Gebrgiorgis
## Contacts
For questions or feedback contact [kidusgebrg@gmail.com](mailto:kidusgebrg@gmail.com)
## update History
- **Version 0.0.1**
    - Development stage




