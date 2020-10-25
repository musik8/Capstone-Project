# Swimlane Diagram

## Register

 ![Alt text](./images/register.jpeg?raw=true) 


## Login
 ![Alt text](./images/login_final.jpeg?raw=true) 


## Create Profile
![Alt text](./images/createProflie.png?raw=true) 


## Create Post
![Alt text](./images/createPost.png?raw=true) 


# Database Design
In this document, we will present how all components for our system translate into a database design. Note that this web 
application does not follow closely on Object Oriented design paradigm. Therefore, our classes contain only properties 
(but not methods). These properties are explained below as they relate to the database design. At the bottom, we will show 
an image showcasing how different database tables are interconnected. I am also presenting at the very end how this database 
could be visualized using a formal domain model respresentation.

## User
*	Firstname – User’s first name (String)<br/>
*	Lastname – User’s last name (String)<br/>
*	Email – User’s email address (EmailField)<br/>
*	Password – User’s password (String)<br/>
* Avatar - User's display picture(String) <br/>
* Created – Date when user account is created (Date)<br/>
*	Updated– Date when the user account is updated (Date)<br/>


## Post
* User - Refers to the user model (ObjectId)<br/>
*	Title – Title of the post made by user (String)<br/>
*	Body – Body of the post made by user (String)<br/>
* Location - Location of the post (String)<br/>
* Type - Category of the post,such as job posting by employer or skills owned by employee (String)<br/>
* Name - Name of the post which connects to the user of the post (String)<br/>
* Avatar - Display picture of the creator of the post (String)<br/>
* Likes - Users who liked the post (ObjectId)<br/>
* Comments 
  * User - Refers to the user model(ObjectId)<br/>
  * Text - Comment on the post(String)<br/>
  * Name - Name of the user who commented on the post(String)<br/>
  * Avatar - Display picture of the user who commented (String)<br/>
  * Date - Date when the user commented(Date)<br/>
* Date - Date when post is created(Date)<br/>


## Profile
* User - Refers to the user model (ObjectId)<br/>
* Photo - User's display picture(String)<br/>
* DateOfBirth - User's date of birth(date)<br/>
* Gender - User's gender(String)<br/>
* Location - User's address(String)<br/>
* Phone - User's phone number(String)<br/>
* Occupation - User's occupation(String)<br/>
* Website - Any website that belongs to the user(String)<br/>
* Bio - User's biography(String)<br/>
* Date - Date when user profile is created(Date)<br/>
* Updated - Date when user prodile if updated(Date)<br/>

 
## Domain model
 This diagram will grow as the system is developed.
 ![Alt text](./images/Interaction_iteration3.jpeg?raw=true)
 

