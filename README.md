Criteria	
Complete
5 points
Missing
0 points
Criterion Score
Uses MongoDB database to store information
Score of Uses MongoDB database to store information, 5/ 5
Has React front end client
Score of Has React front end client,    5/ 5
Uses Express for routing backend
Score of Uses Express for routing backend, 5/ 5
Demo video
Score of Demo video, -/ 5
Total
Score of Project 3,  15/ 20
Might be a bit generous on the React side since it doesn't work. 
Far too annoyed and frustrated with it to attempt making a video at this point.



# MongoDB and Express.js REST API sample application

This repository contains the sample application for the [MongoDB and Express.js REST API tutorial](https://www.mongodb.com/languages/express-mongodb-rest-api-tutorial).

## How To Run

1. You can follow the [Getting Started with Atlas](https://docs.atlas.mongodb.com/getting-started/) guide, to learn how to create a free Atlas account, create your first cluster and get your Connection String to the database.
Then, set the Atlas URI connection parameter in `server/.env` to your Connection String:
```
ATLAS_URI=mongodb+srv://<username>:<password>@sandbox.jadwj.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
```

2. Start the Express server:
```
cd server
npm install
npm run dev
```

3. Start the React app (in a new terminal window):
```
cd app
npm install
npm start
```

## Disclaimer

Use at your own risk; not a supported MongoDB product
