# Real-time Taxi App

# Requirement

<p>There are many apps that depends on real-time bi-directional communication between different types of users. Apps like Uber and Lyft are examples that falls in this category. In a ride sharing app bi-directional communication needs to be established between a rider and a driver.</p><p> In case of our rider sharing apps rider selects a staring location and destination and then this trip request will broadcasted to all the nearby drivers. Any available driver can accept this request and then goes to the pick-up location provided by the rider. Driver's location needs to be sent back to the rider continuously till the ride is active.</p>

# Functional spec
 
 Implemented real-time ride sharing app
 
 Features:- 
1. Gave capability to user to perform CRUD opertaions on account
2. User can add photo to his profile
3. Users can view all of the trips
4. User can request for ride
5. Driver will accept or reject ride
6. User can view location of driver on map ( used google cloud platform )


 ## Main Stack
 1. Middleware and Backend: -
 - Django,
 - Redis,
 - PostgreSQL,
 - Docker
 - Ngnix,
 - Django Channels

 2. Front-end: -
 - React (v16.12.0)
 - React Router DOM (v5.1.2)
 - Bootstrap (v4.4.1)
 - React Bootstrap (v1.0.0)
 - React Router Bootstrap (v0.25.0)
 - Formik (v2.0.6)
 - Axios (v0.19.0)
 - Cypress (v3.7.0)
 - knex
 
 ## Description: -
 
* Using test-driven development (TDD), developed a full stack ride sharing web application. Implemented server-side using Django, PostgreSQL and client-side using React.
* Implemented token-based authentication with JSON Web Tokens (JWT) and used local storage of web-browser to store.
* Established bi-directional communication between rider and driver using WebSockets and Django Channels.
* Streamlined the development workflow by adding Docker and used Nginx as reversed proxy to eliminate Cross Origin Resource Sharing (CORS).
* Completed this project in 3 sprints -
   - Sprint 1 : Wrote server-side code using Django and Django-channels and followed TDD to test written code using test asyncio coroutines(pytest). Used WebSockets to send messages to the UI from the server.
   - Sprint 2 : Implemented client-side using React along with authentication and authorization. Used Docker to implement production ready code-base. Implemented end-to-end tests to confirm code is working as expected.
   - Sprint 3 : Advanced client-side and integreted with the Google Cloud Platform for real-time tracking.

## Sample Screenshot: - 

| ![Login_Page_Rider_Driver.jpg](https://user-images.githubusercontent.com/47191969/88490211-2cdce580-cf57-11ea-8045-70d2bfc198a1.png) | 
|:--:| 
| *Login Page for Rider and Driver* |

| ![Ride_Request.jpg](https://user-images.githubusercontent.com/47191969/88490260-93620380-cf57-11ea-9952-883c726d4ef5.png) | 
|:--:| 
| *Ride Request Demo* |

| ![Unit_Test_Example.jpg](https://user-images.githubusercontent.com/47191969/88490275-b7254980-cf57-11ea-9d1f-862e57b60adc.png) | 
|:--:| 
| *Unit Test Example* |
