# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
I will be creating a web application that aims to organize and manage rentals of equipment from (tentatively) a recreation center. While I was in undergrad at Southeast Missouri State University, I worked at the campus recreation center for about two years. Part of what we offered were equipment rentals for our students and members - we had simple things like basketballs and racquetball equipment, but we also offered bigger, longer-term rentals like kayaks, and climbing kits. Our longer-term rentals were all handled via an old, worn out binder that was hard to keep track of.

My application will aim to offer employees and staff of the recreation center an easy way to keep track of which equipment is currently out on rental, how long it’s been out, when it will be returned, and to whom it’s been rented out to. As a member, you’ll be able to view the inventory and see the availability of all the equipment. If something is available, you can reserve it. If it’s unavailable, you can ask to be notified via text message of when it’s returned and available for you to rent.

### Features
Member login:
Recreation center members will need to log in using their member ID number for the recreation center. Non-members won’t be able to view the list of available equipment.

Search:
Members will be able to search for equipment by category, type, or by entering a search term in a text box.

Admin/Employee login:
Administrators or employees will be able to log in using their employee credentials. This will be a separate functionality from the member login, and will allow employees to make changes to the catalog.

An idea that I have for this is to require employee logins to also come from a specific IP address, meaning it can only be accessed on-site. The goal of this would be to prevent unauthorized modifications or use outside of the facility. I’m not sure how practical that would be, though.

Text messaging:
I plan to implement text messaging through Twilio. When a user rents equipment, they’ll receive a text message (if opted in) reminding them when it’s due to be returned. Additionally, if a user wishes to rent equipment that’s currently unavailable, they can opt in to be notified when it’s available for them.


### Technologies
For my application, I know that I’ll need to use the following languages/frameworks:

Java
SQL (via PhpMyAdmin)
Thymeleaf
Spring
HTML and CSS
Some JavaScript, if appropriate


### What I'll Have to Learn
How to differentiate between administrative accounts and regular users, and only allow changes to be made by users with administrative permissions. Additionally I’ll have to create the interface with which administrators will make changes to the catalogs, add and remove items, and manage user accounts.

How to implement an API, specifically the Twilio API.

Some JavaScript, which I have no experience in, to hopefully make the front end of my application a little more functional.

### Project Tracker
I'm using Trello. https://trello.com/b/kwOvDlpf/capstone-project