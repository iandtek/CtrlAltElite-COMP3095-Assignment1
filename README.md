# Assignment 1 – Recipe Spring Boot Application - Ctrl Alt Elite
Group Assignment: 2 - 4 members per group (mandatory)
Due Date: Sunday, November 7th, 11:59 pm
1. Objective: The goal of this assignment is building a Spring Recipe Assignment Spring Boot. We continue to the concepts of service layers and Spring MVC.
2. Assignment Instructions/Steps: Please note, because this is an assignment, the instructions provided are not instructive as say in a class lab. The expectation is for you to research those unfamiliar elements within your group, to determine how to implement them. The design of the solution is left entirely up to you and your team.
3. Background: The objective of this first COMP3095 assignment is to develop a recipe application that can be used to help facilitate a client/user’s kitchen skills and modernize grocery shopping, that is, instead of relying on index cards, a rolodex of a file folder. The recipe application is intended for people who enjoy cooking. The goal of the application is to provide its users the flexibility to search, share, save recipes from a database with the added capability to maintain a personal cookbook for creating new recipes, and even deleting recipes, when said recipe(s) are no longer desired. This application is meant to be a time saver for its users, by providing recipes with minimal client interactions. Usability and efficiency are key for user adoption of this application. Each user must be given the ability to create a new personal cookbook, within which they can create new recipes, view and delete existing recipes. **The interface must be clean and simple, where a user can search recipes, add/tag favorite recipes, view favorite recipes. The user’s homepage should allow them to list and access their personal cookbook.**
# Requirements
1. The objective of this assignment is to build a new Spring Boot Project, the mandatory requirement is for you to utilize the following dependencies, with Java version 11:
* Spring Boot
* Spring DevTools
* Spring Web
* Thymeleaf – must be used for your view layer
* Spring Data JPA
* H2 Database (embedded) – must be used for you database layer
# Use Case Diagram
For this first part (Part A/ Assignment #1) you are to satisfy the following use cases only.
Unregistered Users:
* Register into the application
  Registered Users:
* Login Into the application
* Logout of the application
* Create a recipe
* View a Recipe
* Search for a Recipe
* Plan a meal
* View Profile
# Functional Requirements
For this first part (Part A/ Assignment #1) you are to satisfy the following use cases.
1. Registration: Any new user (unregistered) must be required to register in order to access the application. It is your responsibility to determine what information is necessary/mandatory to register. The information provided upon successful registration should be persisted inside the application database, and later be utilized when/if displaying a user’s profile information.
2. Login: Logging into the application is the initial step before being able to perform any operation. Logging into the application is only permitted for registered (known) users.
3. View Profile: Any registered user can view their profile information. Additionally, this same feature, should allow the user to view created recipes as well as any recipe a user has marked as favorite.
4. Create Recipe: Registered users must have the ability to create and save their own recipes. An intuitive and creative interface, with necessary required fields, is entrusted on the developers to design.
5. View Recipe: Registered users must have the ability to view all recipes, both their own recipes, and any recipe posted (publicly available) by other users in the system. The recommendation is the development of a recipetype forum, where all registered user recipes are posted and ideally ordered (ie. creation date).
6. Search for Recipe: Registered users must have the ability to view and search for recipes within the system. The criteria to perform a search, its scale, scope, and retrieval mechanism, is incumbent upon the developers to design and determine. The goal of the search is to provide the users the ability to search for recipes(s) as quickly and efficiently as possible. Usability is of the essence.
7. Plan meal: Registered users must have the ability to plan their meals in advance. This feature is akin to calendar to-do list, where the users have the ability to plan their weekly meals in advance.
# Final Thoughts
This is the first assignment of two, within it, there are many areas of group interpretation, that is, each groups creativity is welcomed. The desire is to see a wide range of differing interpretations on how to solve the client/application needs. The scope of interpretation is left up to each group, provided the minimum requirements are met. Things you will need to consider and design in order for your application to be deemed a success:
* The application requires a form of data persistence. H2 database (embedded) is a mandatory
  requirement.
* Presentation Layer, Thymeleaf is a compulsory requirement, however, the UI design and creativity are left to you and your group members.
* This is only the first assignment (assignment 1), the second assignment (assignment 2) will be built on top of assignment 1, that is, assignment 2 extends assignment 1, so modularity in design and implementation should be exercised to minimize future refactoring.
* Your solution must meet each of the requirements documented within to gain fill marks at a minimum.
* Design is key, as a groups submission will be evaluated against all submissions within the class.
* Assign work to all group members, the recommendation is to use some form of version control, create
  and distribute tasks as demonstrated within class. A group lead is recommended.
* This is a mandatory group assignment, please select your team members diligently, as the
  distribution and contribution of each group members effort will directly result in how well and quickly your assignments are constructed.
* Individual submission will be docked marked -5%
# Assignment Submission Guidelines:
1. You must email your assignment to your Professor at Sergio.Santilli@georgebrown.ca
2. All members in the project team must be cc’d on the final assignment submission. Failure to do so will
   result in a mark of zero for those members not cc’d on the assignment submission email.
3. Within the body of the email, clarify course code, team name, team members and student numbers. Title
   the email accordingly COMP 3095 – Assignment 1.
   Example:
   Course: COMP 3095
   Team Name: The Hackers
   Team Members: John Smith - 1234567
   Sally Jones - 7654321
   Jane Wilson - 2342342
4. When submitting, cc’ a copy to yourself for backup and time verification.
1. The project submission, must contain the complete project source code compressed in .zip format (no
   source code, no marks)
5. Each java file (.java) should include a header.
```(java)
//*********************************************************************************
* Project: < project name … >
* Assignment: < assignment # >
* Author(s): < author name …>
* Student Number: < student number … >
* Date:
* Description: <describe the java file and its purpose briefly only – 1 or 2 lines>
*********************************************************************************//
```
6. Your code should be modular and should show no signs of dry (don’t repeat yourself) code.
7. Be cautious DO NOT share your application with others. Complete failures will be assigned if code is shared. All assignments will be reviewed and analyzed strictly within these regards.
8. Late assignments are assigned a penalty of 25% per day.