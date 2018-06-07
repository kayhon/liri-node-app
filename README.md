# liri-node-app

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface.

App site:
https://kayhon.github.io/liri-node-app/

Github repo:
https://github.com/kayhon/liri-node-app

## To use this app you need to:
1. Clone the repo.
2. Type npm install
3. If someone wants to clone app from github and run it themselves, they would need to supply their own .env file for it to work.
  
### installation required:
  - package.json
  - twitter-api
  - spotify-api
  - request
  - odbm-api
  
 ### Package json
 
  `"dependencies": {
    "dotenv": "^5.0.1",
    "i": "^0.3.6",
    "node-spotify-api": "^1.0.7",
    "npm": "^6.0.0",
    "request": "^2.85.0",
    "twitter": "^1.7.1"
  }`
  
  EXAMPLES:
  
  Type `node liri.js my-tweets`
  
  ![Type `node liri.js my-tweets`](https://i.imgur.com/nLiTHkj.jpg)
  
 Type `node liri.js spotify-this-song 'ace of base'`
 
 ![Type `node liri.js spotify-this-song 'ace of base'`](https://i.imgur.com/klDUtap.jpg)
 
  Type `node liri.js movie-this black panther`
 ![ Type `node liri.js movie-this black panther`](https://i.imgur.com/7MgOJkL.jpg)
 
 Type `node liri.js do-what-it-says`
 ![ Type `node liri.js do-what-it-says`](https://i.imgur.com/FkawyFM.jpg)
 
