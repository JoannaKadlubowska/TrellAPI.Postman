# Trello API testing with Postman
This project was created as a practise realised during COLT project organised by Cherry-IT (conducted by Anna Czyrko: linkedin.com/in/ania-czyrko-05933aa1). 

Technology stacks: Postman

Here are some integration tests  targeting the Trello API. 
![image](https://user-images.githubusercontent.com/70474776/236447711-e02833ff-90c3-4c9c-ba66-0054c0d3f3ab.png)


The goal was to test some Trello (https://trello.com/) features such as: 
* Creating: board, lists, cards
* Updating: an existing cards
* Removing: cards, lists, board

The system properties have been defined in collection and environment variables so you don't need to touch the code:

- "baseURL" defines the URL Trello app
- "key" defines the application key provided by Trello
- "token" defines the server token (or user token) provided by Trello


# Setup
Clone the repo ``https://github.com/JoannaKadlubowska/TrelloAPI_Postman``
Install Postman ``https://www.postman.com/downloads/``
Import collection file:  ``API_Trello.postman_collection.JSON``
Import environment file: ``Trello_Api.postman_environment.JSON ``
Click Run collection
