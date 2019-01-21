1/. the create_router.js file establishes the routes of the games resource.


2/. server.js is responsible for connecting the client facing side of the app to the database.


3/. gamesRouter establishes the restful actions for the particular data set (in this case 'games').


4/. 


5/. init - an object that contains any additional custom settings that you want to apply. In this app it calls specific restful actions (POST and DELETE) and related info (i.e payloads and JSON translation requests).


6/. get '/' (i.e localhost:3000)


7/. The MongoDB driver allows the server to talk to the DB and ensures that CRUD actions on the DB are completed as requested.
