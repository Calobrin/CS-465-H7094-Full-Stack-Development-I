# CS-465-H7094-Full-Stack-Development-I
This is the repository that I will be using for my CS-465 course at SNHU. Unlike other courses where the repository was added at the end, this was made at the beginning.

### Architecture
## Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
The front end website evolved over the course of the term, initially it was done by importing HTML format web pages to create a Express HTML wbebsite, but as time went on this was changed over to be read as JSON format files to the website. <br />
It is because of this that the Express HTML website was static, and to have any changes done to the websit you would have to change these HTML files instead of loading and viewing the information from a database. That is why the website evolved as development continued. HTML allowed us to see an idea of what the website should look and feel like, but more parts were added to it to become a fully functioning website capable of dynamically displaying data to the users. And this was done through the use of Javascript on both front end and back end for the code

On the other side of this you had the Single-page application or SPA, which was the admin site that could be used by authorized users to add or edit the trips that would be displayed on the website.
## Why did the backend use a NoSQL MongoDB database?
The reasons for the use of a NoSQL database like MongoDB for this website is due to its ability to be scaled up with ease and its overall flexibility and performance compared to its SQL counterparts. Since the website was set up with the SPA in mind to be able to dynamically add more trips for example, this was an easy pick for NoSQL to do this, because it is easy enough to continue adding, or scaling, up more data inside the NoSQL database.



### Functionality
## How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Javascript is one of the most popular programming languages for the development of websites, and JSON, or "Javascript Object Notation" derived from Javascript while also being independent from any programming language. This also means that Javascript can easily read JSON files and translate them to a Javascript object.
Javascript also ties together both front-end and back-end development because the programming language can actually be used for both sides of development.



## Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user # interface (UI) components.
One instance where I refactored code was changing the SPA site to include a login security to authorize users to add and edit trips. The buttons to do this and manipulate the data were created, and then hidden to users unless they were logged in correctly.
Other instances of refactoring the code was how the trips were being displayed, there was a "trips list" version of displaying the code, and then the "trip card" version. These components that I added can also be reused in other ways so it became a more efficient use of the code.



### Testing
## Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. 
## Explain your understanding of methods, endpoints, and security in a full stack application.
For some time during development the testing I had done simply involved going to the http address for the different API endpoints, for example, localhost:3000/api/trips to view all of the trip data as raw JSON. Or going to the /travel API and checking the functionality of clicking on the images of each trip to view their specific JSON data. <br />
This process can also be done through programs like Postman where you can send these http requests and get back responses in a more efficient manner, as well as being able to pass certain information through postman like authorizing user tokens or passing in login credentials for testing security purposes.



### Reflection
## How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
This course taught me how to work with a lot of new and different software and got me used to working with them and understanding their code structure. These skills are generally useful to have and may prove helpful to me in a potential future career. <br />
I also became a bit more used to working with Github and being able to push my updated files to different branches on github efficiently. This includes an instance where I almost lost a lot of my work after I had pushed it to a new branch but then deleted it. I learned how to recover lost or deleted branches that can be a useful trick in the future in the off chance a similar mistake occurs.
