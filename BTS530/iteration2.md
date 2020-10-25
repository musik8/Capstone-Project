# Swimlane Diagram

## Register

 ![Alt text](./images/register.jpeg?raw=true) 


## Login
 ![Alt text](./images/login_final.jpeg?raw=true) 





# Database Design
In this document, we will present how all components for our system translate into a database design. Note that this web application does not follow closely on Object Oriented design paradigm. Therefore, our classes contain only properties (but not methods). These properties are explained below as they relate to the database design. At the bottom, we will show an image showcasing how different database tables are interconnected. I am also presenting at the very end how this database could be visualized using a formal domain model respresentation.

## User
*	Firstname – User’s first name (String)<br/>
*	Lastname – User’s last name (String)<br/>
*	Email – User’s email address (EmailField)<br/>
*	Hashed_Password – User’s password (String)<br/>
*	Updated– Date when the user account is updated (Date)<br/>
*	Created – Date when user account is created (Date)<br/>

## Post
*	Title – Title of the post made by user (String)<br/>
*	Body – Body of the post made by user (String)<br/>


## Interconnection between different tables
 
 ![Alt text](./images/user_post.png?raw=true)
 
## Domain model
 React is made out of components and each one is a class. 
 This diagram will grow as the system is developed.
 ![Alt text](./images/classDiagram_final.png?raw=true)

