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
Any user can go to our map put a pin point with a text description and attach images or videos.

The time, location, user text/image/video passes to data pipeline.

### Front-end Web User Interface

1. a web map user interface (could look like Uber, but more flexible in dragging location pins) so the general public can submit data via:
-  drag their pin on the map to the location where they wanna report about

2. think about how do people submit data? by forms?

references:
https://stackoverflow.com/questions/38137071/google-map-api-drag-and-drop-pin



### Back-end 

handling steps from:
1. when the general public submit data to a database to store
(question: how is API involved ?)
2. 

### Tasks break-down:
1. review a few similar applications that can be good references for the architecture/go through their source code
- bikeshare
- social pinpoint
- uber

2. make a UML/architecture diagram?
location = GPS pair
information = not house for sale but boarder 33 sth showing user thoughts and feelings 
  
## Scope
<!-- Now we know what stakeholders may interested in
But we cannot finish them at once and may not finish all
So what do we do , what do we not do -->

### Some use cases
- share experiences of visits of a certain shop/public agency to be shown on the map:
  - (1) yonge & finch starbucks [shown as GPS coordinates(N 43° 43' 31.2456", W 79° 29) on the map) has a very nice server that would give you a free birthday drink in your entire week of birthday ^_^
  - (2) Dynamic Medical Center-Private colonoscopy clinic [shown as GPS coordinates(43.7828° N, 79.4166° W)] has a terrible receptionist
  - (3) Edithvale Community Center has a very annoying receptionist :(
- request needs of certain type of public infrastructure for daily life or business services to be shown on the map:
  - (4) yonge and cummer intersection [shown as (43.786708 N, -79.416419 W)] this area does not have any library nor any community center while having at least 6 huge condo towers coming up]

## Assumptions
<!-- What did we assume as the requirement that our project can made its goal -->

## Resources
<!-- What do we have now
What do we need -->

## Deliveriables
<!--What we should finish and give to users/stakeholders in terms of product -->

## Acceptance criteria
<!-- Metrics to measure the progress of the project
Metrics to measure the user satisfaction
Other requirements (security...) for releasing the product (QC)
The level of metrics that is acceptable for releasing
How to verify that deliveriable align with the goal? -->

## Communication plan
<!-- How to communicate with stakeholders
How to communicate with teams
How to ensure new developer can easily join the work -->

### Persons and roles


