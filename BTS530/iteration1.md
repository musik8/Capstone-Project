

# Interation One

# Version One Design For ToolBox
### These designs have the bare minimum to test functionality of the system. 
### The designs will be greatly polished and improved at an appropriate stage of development.

<br/>
<br/>

![Alt text](./images/1920_5.png?raw=true "Screen One")

## Screen One - Home page

First time users will land on this homepage.  

Users can see posts that have been made, these posts can later be tailored depending on account settings and preferences.  
The right-hand side of the UI will be the menu/dashboard of the system. Newcomers will have the option to register or login and search.  
The user will also be able to select any post they see.  


<br/>
<br/>

![Alt text](./images/1920_6.png?raw=true "Screen Two")

## Screen Two - Home page / Login / Search

Once the Login button in the dashboard is clicked, the user will be presented with two input boxes. The user can enter their credentials and gain access to their account.  

Clicking the cancel button will conceal the input boxes and the user will regain access to the registration input fields.  

At the top of the dashboard, clicking the Search button will reveal a search input box where the user can enter a keyword and then activate the search functionality by clicking the button below. Or conceal the search by hitting close.     



<br/>
<br/>

![Alt text](./images/1920_12.png?raw=true "Screen Three")

## Screen Three - Post Expanded

When a post is clicked, a drop-down box appears with more information about the post. For now, we will develop a generic template for posts. Later in the development cycle we will create templates that are specialized; example: information post, recruitment post. 

User will only be able to confirm interests in job posting if they have an account. The user will also be able to see the location and required skills. 



<br/>
<br/>

![Alt text](./images/1920_7.png?raw=true "Screen Four")

## Screen Four - Logged in Dashboard 

After registration or a login the user’s dashboard will display the user’s account info and give navigation access; Account, Friends, Messages, Preferences. 
Plus a logout option.



<br/>
<br/>

![Alt text](./images/1920_8.png?raw=true "Screen Five")

## Screen Five - Account Page

The page will display posts that the user has made themselves and will give the option of making more posts at the bottom left section of the UI.
The user will have options when creating a post. This will change the template and functionality of the post.

The dashboard at the bottom will also give the user the option to go to their profile settings. 


<br/>
<br/>

![Alt text](./images/1920_9.png?raw=true "Screen Six")

## Screen Six - Account Page / Post Creation

Once a post type is chosen by the user, the bottom section will slide up and reveal the input section that will reflect the posting type selected. For now, the post will be generic in order to test out various features that is associated with posting to the website. For example, adding tags to post to help search functionality.  


<br/>
<br/>

![Alt text](./images/1920_10.png?raw=true "Screen Seven")

## Screen Seven - Profile Page

The profile page is where the user will add detailed information about themselves in order to unlock more system functionality like applying to job postings. Some of the information included is their address and biography. The bottom left section of the UI is where the user will be able to create their portfolio.  

The dashboard navigation will give access back to the account page.


<br/>
<br/>

![Alt text](./images/1920_11.png?raw=true "Screen Eight")

## Screen Eight - Profile Page / Portfolio

The portfolio is where the user will be able to post images of past work in order to promote and display their skills. For now the user will be able to upload up to four images and basic description along with a title. 


<br/>
<br/>

![Alt text](./images/1920_13.png?raw=true "Screen Nine")

## Screen Nine - Friends Page

The user will be able to search for friends/connections by searching for a keyword or the users name. The user will also be able to add contacts by entering emails.  

A list of contacts will be shown on the left side and once the “More” option is clicked. Detailed information of the user is displayed on the right of the list. 


<br/>
<br/>

## Design Notes

There are pages missing due to realities and time constrains. Pages like messages will be left for BTS630. Implementing the functionality of the pages above will cover almost all the features we want for Toolbox.    

# Back-End Setup
## We are using the MERN stack for our networking website. 

### MERN stack consists of:

1. <b>MongoDb</b>
1. <b>Express js</b>
1. <b>React js</b>
1. <b>Node js</b>

This will allow us to use MongoDB for our database, Nodejs and Express js for our server and routes, and React js to create a front-end for the user to interact with.


### We use API endpoints to communicate

* Back-end (Node and Express js) and Front-end (React js) are separate entities therefor we use APIs to make the two work together. <br/>
* An API (or Application Program Interface) is created on our server which provide "endpoints" where our front-end application can interact with it. <br/>

### Our Node js and Express js Back-End

We installed the following packages that will be used in our stack.  

<br>

1. <b>Express js</b> - A web application framework with built in functionality for a lot of things including routing.
1. <b>Mongoose</b> - An ODM(object data modeling) to allow interactions between our express js application and MongoDB.
1. <b>BodyParser</b> - A library which allows our express js application to read the body (or content) of the incoming requests.
1. <b>Nodemon</b> - "Hot Reloading" for our node server when things change so we don't have to stop and start the server every time we make a change.
1. <b>Concurrently</b> - allows to run more than one command inside the same terminal. This is helpful for our project since it allows simultaneously develop our front end and our back end in one project.
1. <b>Node-sass</b> - is a library that provides binding for Node.js to LibSass, the C version of the popular stylesheet preprocessor, Sass. It allows us to natively compile SCSS files to CSS.
