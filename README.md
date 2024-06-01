# local-library
A Local Library website written in Express (Node.js). The goal of this project was to learn and understand the fundementals of express and node.js. This project is meant to replicate a system that a library would use to keep track of which books they have available, as well as any books that are currently checked our or on loan.
This project could easily be converted to be used in a private setting in order to keep track of the books you have in your own library whether that be digital(kindle, etc) or physical(hardcover, comics, etc). 

## Setup
To set up this project locally on your computer:

1. Make sure you have node installed onto your computer
2. Once you have node setup install the project in the root of your clone of this repo:

   ```bash
   npm install
   ```
3. After you have downloaded all the packages and dependencies, you will need to open up the app.js file in the root and find the variable "*dev_db_url*". Currently, it is set to a value of "*placeholder*", you will need to replace that value with your Mongodb database URI credential.
4. Run the server, using the appropriate command line shell for your environment:

   ```bash
   # Linux terminal
   DEBUG=local-library:* npm run devstart
   
   # Windows Powershell
   $ENV:DEBUG = "local-library:*"; npm start
   ```
5. Open a browser to <http://localhost:3000/> to open the library site.

## Link to a running version of my library website(Glitch): [Local Library](https://rowan-glowing-yogurt.glitch.me)
