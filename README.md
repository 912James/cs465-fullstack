# cs465-fullstack
SNHU CS-465 Full Stack Development

# Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Why did the backend use a NoSQL MongoDB database?

* In the full-stack project, we were taught and implemented the various frontend development techniques avaialble, each with its unique capabilities and advantages. Express.js, a server-side framework, was crucial for building our web applications and APIs. While HTML served as the primary language to structure our content, JavaScript provided the interactivity necessary to engage our users. However, the standout feature was the Single Page Application (SPA). Unlike the backend, which utilized a traditional multi-page approach with specific pages for different data, the SPA allowed us to present all data on a singular page. This resulted in reduced load times between URLs, offering a seamless and enjoyable user experience.

* Our choice to use the NoSQL MongoDB database for the backend stemmed from its inherent flexibility and performance. MongoDB's schema-less nature means data storage and retrieval can be adaptable. This allows the clients to add additional data fields as their requirements change. Coupled with its speed, especially during multiple browser requests, MongoDB was an ideal choice for our project.

# Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

* While JSON and JavaScript may seem similar, they serve very different purposes as we learned throughout this course. JSON which is a data format, acts as a bridge, connecting the frontend and backend development. It structures the data in key-value pairs, making it easy for JavaScript to interpret it and utilize this data within the application. In contrast, JavaScript is a programming language responsible for the app's functionality and interactivity.

* Throughout the full stack process, we encountered moments that required a lot of code refactoring. While one of the primary concerns was debugging due to the outdated source material, I discovered the benefits of the reusable UI components. We learned about using tools like handlebars, we then standardized the headers across our customers interface which eliminated the need to hard code them into each page on the admin site. This ensured that the website had a consistent appearance and behavior, it also simplified the sites maintenance, and it allowed for future scalability.


# Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

* Our full-stack application required different methods for data interaction:

GET retrieved data.
POST sent data, including authentication credentials.
PUT updated server data.
DELETE removed server data.

The endpoints which are represented by specific URLs, determined the actions on the server. One of the endpoints we used in the project was "/api/trips/{tripCode}" and it specified a particular trip's data. Security in every project is extremely important and it was the last part of the project we worked on. For the security of the website we integrated an authentication system to only allow registered users to modify trip data. 

# Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

* Engaging with this course has been a transformative experience. As I complete my computer science degree with a concentration in software engineering, the practical insights from this course have been invaluable. Navigating the complexities of MongoDB and refining my skills in code identification and refactoring has not only enhanced my troubleshooting skills but also positioned me as a more marketable candidate in the tech industry. The course had many challenges, due to the outdated course materials. This inadvertently caused that the class to work together troubleshooting the problems, thus improving our collaborative and problem-solving skills.
