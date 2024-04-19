# Pin Your Say
Imagine a social media you share everything you see and your feelings about the things at a location at a time. That is us.

## Goal
<!-- That we expect to see at the end of the project? -->

We want to build a map that collects the events users observed from their surroundings and the feelings of users regarding to the events.
So we can analyze the data and contribute to the urban planning and service design for public service.

We believe that urbanization and social development (also public service and social innovation) can be driven by the public and open data. Therefore we plan to collect data with the map exploring possibility of the bottom-up approach.

## Objectives
<!-- Something/points we want to finish in the project -->
For the first stage of our development, we limited the scope to build a input interface and pipeline for collecting data from the crowd.  
- Build a map based pin point creating interface for events or thoughts
- Build a lakehouse for data storage and being  flexible for further development in data analytics 
- Train our team in API development, practicing project management skills and get hand-on experience in building and maintaining a lakehouse

## Stakeholders
<!-- List of people related to the project in their benifit and interest that may affect us and we may affect them -->
### potential beneficiaries of the tool:
- who submit their sharings: get their voices known 🥰
  - **general public**
    - Just another Twitter, Instagram and Google map
  - **Individual news media**
    - Location and time specific information sharing
  - **Social innovator**
    - Get their idea and voices known
- who read the sharings:
  - **general public**
    - Everyday life lessons/information etc.
  - **urban/city planner**
    - Understand the general public's needs on the ground in every part of the town
    - Ask us to provide business intelligence based on the data collected 
  - **business developer**
    - Figure out which part of the town needs what kind of services and goods
    - Ask us to provide business intelligence based on the data collected
  - **Media**
    - Get news provided by local residents and knowing things they cared about 
    
 
## Requirements
<!-- What we will do regarding to the stakeholders
How do we understand the needs of the stakeholders -->
- Any user can go to our map put a pin point with a text description and attach images or videos.
- Web interface for accessibility.
- The time, location, user text/image/video passes to a data pipeline and store the data in a lakehouse.
- RESTful APIs for web app to connect lakehouse.
- Project should be well documented for future development.
  
## Scope
<!-- Now we know what stakeholders may interested in
But we cannot finish them at once and may not finish all
So what do we do , what do we not do -->

- Design and implement a Web app of map
- Design and implement CR<s>UD</s> operations of pin points on map in the web app for user
- Design and implement CRU<s>D</s> APIs of pin points in lakehouse
- Setup and maintain a data lakehouse
- Setup and maintain a cache database if necessary 

## Assumptions
<!-- What did we assume as the requirement that our project can made its goal -->
- We know nothing about API design and development 
- We know nothing about lakehouse
- We need to learn frontend development with map
- We want to build a web to collect observations and thoughts from people 

## Resources
<!-- What do we have now
What do we need -->
- manpower * 2  
More contributors are welcomed! 😍

## Deliveriables
<!--What we should finish and give to users/stakeholders in terms of product -->
- Tutorial and code examples for building CRUD RESTful API with FastAPI 
- Tutorial about setting up a lakehouse 
- RESTful API server for backend
- Lakehouse for data storage
- Map web app with SSO for adding pin points 

## Acceptance criteria
<!-- Metrics to measure the progress of the project
Metrics to measure the user satisfaction
Other requirements (security...) for releasing the product (QC)
The level of metrics that is acceptable for releasing
How to verify that deliveriable align with the goal? -->
- Tutorial contains test cases for the code examples and all code passes the unit tests
- All functions in code has at least two unit test associated
- User can add pin points on map
- User can see pin points added on map

## Milestone
1. (Learning) FastAPI sample for templates of index HTML and login APIs
2. (Learning) Unit test for FastAPI about login APIs
3. (Learning) Unit test for FastAPI about CRUD of SQL database 
4. (Learning) Use case document of the tutorial app
5. (Learning) API specification document of the tutorial app
6. Use case document for the deliverables
7. API specification document for thre deliverables
8. Unit tests for the test caes of the deliverables 
9. Setup lakehouse
10. Test connections between lakehouse and FastAPI server 
11. APIs and front end development of the deliverables 

## Communication plan
<!-- How to communicate with stakeholders
How to communicate with teams
How to ensure new developer can easily join the work -->
Meeting at Tuesday 😃

### Persons and roles
@NewJerseyStyle will maintain the document as the first priority 

