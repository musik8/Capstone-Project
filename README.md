# Group_21
## Team Members
### Maxim Usik
* Github: musik8
* Skype: live:maxim124
* Role: Designer, Front-end and Support

### Muskan Shinh
* Github: Shinh18
* Skype: +1 647-532-2913
* Role: Backend development

### Kate Grinberg 
* Github: egrinberg
* Skype: 
* Role: 





## Business Description 


### The Problem 

The problem is the ability for employers and clients to find competent workers in the trades industry. Skilled jobs such as a Plumber, Mason, Welder,  Electrician, Pipefitter, HVAC operator, Carpenter and many more. This problem is made worse by the baby boomer generation retiring in the next couple of years, opening positions across many fields in the labor force. In particular, the tradesmen occupation is in high demand for workers due to high social pressure for young students to pursue degrees at universities and colleges. In an industry with a rapidly declining workforce, the ability to find skilled workers is getting worse. Clients such as home owners or business owners can find workers, but with great difficulty and with uncertainty of the workers abilities. Private residence owners are at most risk due to the possibility of workers inadequately completing work and then having to hire other tradesmen to re-do the work. This can cost families thousands of dollars just to fix mistakes. These problems will continue to grow as the years go by and a large portion of skilled tradesmen retire with fewer replacements. 



### The Solution 

The solution is a focused online platform that helps clients and skilled tradesmen get connected with each other. The clients can range from homeowners to large businesses. There will be different types of accounts that users can create to accommodate a business, independent workers, large corporations and apprentices. These accounts will include a combination of features such as: a list of skills and certifications that a worker has or the business’ collective skills, the ability to create a portfolio to display and explain past work, specify an area of willing traveling distance (for clients outside of large cities), hourly fees/other fees, preferred working environments (high altitudes, extreme weather etc..), specify work they are looking for (apprenticeship, part-time, full-time) and general information. The accounts will have their own home page that can be used to communicate/get attention in a page for a specified trade (that clients will be looking at). An account user can send a connection request to other accounts to create a quick way to summon account information. This connection is useful when a tradesmen or business is working with a client and requires additional help in a field. There will also be a general page for connections to maintain communication by posting content and leaving comments. Clients looking for workers will have filters for the type of specialist they require. The client may not know the specialist they require in which case they can search for keywords. The results will display a list of accounts and a general specialist page where clients can browse posts made by tradesmen in the field. The adaption of this platform will be much more likely by newer generations since they have grown up using technology and other social media websites. This platform will also encourage people into the trades industry with the potential ease of finding an apprenticeship.   

## Use Cases



### Search For A Worker - MAXIM USIK 

#### Brief description (scope) 

A client searching for a trades-person to perform a job that can range from a small to large task. The client will then have options for a potential worker that best matches the filter that the user has setup. 

#### Actors (users) 

A private residence owner outside of a major city. 

#### Preconditions 

The actor has an internet connection and a device that can use browsers. The actor is on the social media platform home page. 

#### Basic Flow

| Actor: Private Residence Owner | System |
| --- | --- |
| The user navigates to the “Connect To A Skilled Worker” page by clicking a header navigation button  | The system would then load the search page. The system will display input fields: Skill required, location, starting date, estimated budget |
| The user begins to enter a keyword for the skill required. The user can enter multiple skills required. | Every time the user presses a key the system will attempt to match the characters with a word or a related item and display a drop down with likely matches.  |
| The user selects Masonry and Plumber.| The two selected skills are stored in an array of variables. |
|The user will pick their location on a map (google maps or mapbox) by click and leaving a marker | The latitude and longitude of the marker will be stored in variables. |
|The user enters the estimated budget and when they want the worker to get started.  | The system stores the entered input fields in variables. |
|The user clicks the search button | The system will go through the database and sort out the most appropriate accounts. The weight of the search input of the user is as follows: Skill required, Location, availability/starting date, budget. The system will then display the most appropriate accounts that match the filter and will also display the general boards for the skills listed. |
|The user selects the account at the top of the list | The system will call up the account information and redirect the user to an account page.|

#### Alternate and/or exception flows 
| Actor: Private Residence Owner | System |
| --- | --- |
|The user clicks the search button | Using the weighted filter, the system only finds loose matches, meaning the buget is off or there are no workers available. The system displays the general boards for the required skills or skill and some trades-person; noting on the display that no exact matches were found. |
|The user clicks on the board that tradesmen with the required skills post on.| Display numerous posts from skilled tradesmen in the board |
|  The client may find information that will let the them do the job themselves or help them modify their filter in order to increase the chances of finding a trades-person | The system will open any posts or videos that the user clicks |

#### Post-conditions
The user/client will have the necessary contact information for the trades-person displayed in the account page.

### Adding a portfolio to account  - MUSKAN SHINH

#### Brief description (scope) 
Trades person can add a portfolio to their account so that clients can have a look at the previous work done by them and their experience in the field.

### Actor(users)
A trades person owning specific set of skills.

### Preconditions
The actor must have an account and logged in to his account. The actor is on the home page.

### Basic flow

| Actor(s): Trades person | System |
| --- | --- |
| Actor goes to the account details by clicking button “Account”.  | Displays the account details. |
| Actor requests to create portfolio by clicking “Create Portfolio” button. | Displays option to either add an existing portfolio or create one.
|  Actor chooses to create a portfolio | Loads a new page with an outline of boxes for adding text, uploading image or a video |
| Actor selects the option to add text. | Displays a text box with options for changing font size, style and color as well. |
| Actor adds text. | Saves the text as a section.
| Actor selects to upload image. | Displays a pop-up menu of uploading file from computer. |
| Actor uploads the image using button “Upload” on pop up menu | Displays the image as a section |
| Actor selects to upload video	| Displays a pop-up menu of uploading file from computer. |
| Actor uploads the video using button “Upload” on pop up menu | Adds the video as a section |
| Actor clicks on “Change Layout” button. | Loads the page into one displaying drag options for different text boxes, images, videos. |
| Actor drags and adjusts the size of text box, image, video as required. | Saves the layout made by Actor. |
| Clicks on “Submit” to submit the portfolio. | Asks for confirmation- yes or no |
| Confirms, clicks yes. | Saves the portfolio as part of the account. |

#### Alternate and/or exception flows

| Actor(s): Trades person | System |
| --- | --- |
|Actor requests to add portfolio by clicking “Add Portfolio” option. | Displays a pop-up menu to upload portfolio from local device, one drive, cloud. |
| Selects one of the options to upload. | Uploads the portfolio and displays |
| Clicks on “Submit” to submit the portfolio. | Asks for confirmation- yes or no |
| Confirms. | Saves the portfolio as part of the account |

#### Post-conditions
The user/trades person will have its portfolio creates/added to its account.



### Creating An Account - FRANCIS TRACH

#### Brief description (scope) 
User creating an account so that they can access the website and the various features that are provided.

### Actor(users)
A user (Can be a Client, Trades Person, etc) creating an account.

### Preconditions
The actor must be on the page that will allow you to create an account.

### Basic flow

| Actor(s): Actor: User  | System |
| --- | --- |
| Unser navigates to the "Create An Account" page by clicking "Create An Account" on either the login screen, or main page.  | The system will display the page to sign-up. The system will display input fields: First Name, Last Name, Email, and Password.  |
| Clicks on the "Agree & Confirm" after entering required details. | The System will display additional input fields about profile: Most recent job title, Most recent company | 
| User enters additional profile information required to sign-up for an accont. Clicks on "Continue". | Saves Profile Information in Database. | 
| User clicks on "Sign-Up", and confirms all details provided. | Displays profile page that user created. |


#### Alternate and/or exception flows

| Actor(s): User | System |
| --- | --- |
| Clicks on the "Agree & Confirm" after entering required details. | The System will display a message saying the e-mail adress is invalid because it is already in use, and to re-enter a different one. |
| User re-enters valid e-mail, and clicks on "Agree & Confirm". | The System will display additional input fields about profile: Most recent job title, Most recent company |
| User enters additional profile information required to sign-up for an accont. Clicks on "Continue". | Saves User Information in Database. | 
| User clicks on "Sign-Up", and confirms all details provided". | Displays profile page that user created. |

#### Post-conditions
The user/trades person will have a newly created account on the website.


## Technological Choices

### Front-End Technologies

Facebooks’ React framework will be used as the front-end web technology. React is a JavaScript library that is component based. Using JSX and JavaScript a user can build out a component that can have unidirectional data flow with states and props. Each component can be re-used throughout the application. This framework is necessary for larger projects that require multiple team members. Everyone can work on separate components without interfering with others, this benefit is complemented by GitHub’s utility. There are three comparable framework competitors which includes React, Google’s Angular and Vue. Vue is relatively new with less documentation and prone to bugs and issues that new technologies suffer. Angular and React are nearly on the same level, both being tried and trusted with extensive documentation. React has been chosen over Angular due to the team’s collective experience with the framework.    

Another reason to use React is because of its React Native counterpart that allows us to port the web application to a mobile application. This lets our app run on Android, iOS, Windows and Blackberry devices.   

### Back-End Technologies

For this project, the Back-End technologies that we will be using are Node.js runtime environment, CRUD API, and MongoDB. Node.js will be used so that we can execute all of the JavaScript code necessary for the website outside of the browser. It will do things like generate dnyamic page content, collect form data, and many other things that will easily make the application fast and scalable. MongoDB will be to used to deal with all the data that we used, so that it can be stored succesfuly in a database. All of the data and documents will be stored in the collections and it will be easily organized and accessed with the use of the MongoDB. Using MongoDB will allow us to make it easy to navigate all the data that we're dealing with, as well as keep it document-oriented, meaning that instead of having data in the form of relations, we will be able to store all of the data in the form of documents, which is very practical. CRUD stands for Create, Read, Update, and Delete. CRUD API will come useful to have an  access to create, read, update, and delete any information that is necessary when dealing with our database. It would be much more difficult to manage the data in the database without the use of CRUD API.




### Application Programming Interfaces (APIs) 

The Twitter and Instagram official APIs may be used if we want our users to link their social media 
platforms with Twitter or Instagram. The other two social media platforms are different enough to not be direct competitors to the one our team is developing. Instead the two platforms may compliment the current project.  

Google maps API will most likely be used for the navigation and location aspects of the project. Google maps API is extensive and is backed by one of the largest software companies on the planet. We can use almost any feature that google maps has to offer.    
