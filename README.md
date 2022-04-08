# DevOps-Project003

****Project Implementation****
Technology Stack used was **MERN**( MongoDB ExpessJS ReactJS Node.js)


**Step 1: Creating an AWS instance & Connecting to it using Windows terminal**
- Created an AWS Ubuntu instance added inbound rules to be able to access my instance.
- Installed Windows terminal and ran a few commands to install Open SSH( connectivity tool used for remote login that uses SSH(Secure Shell) Protocol.
- After creating the SSH keys and saving them on my pc i connected my github account to the terminal by adding the key under github SSH settings then continued to developer setting to generate personal access token.
- Connected to my AWS instance using the Windows terminal.

**Step 2: Installing Node.js and Express js**
- Ran a command that both installed node.js and npm( package manager for Node ). `sudo apt-get install -y nodejs`
- Created a Todo directory for my application and ran a `npm init` command which initialised thus creating a package.json file( the file contains all dependencies and information for my application to run)
 ![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm1.PNG)
- Ran `npm install express` to install expressjs.
- Added a file which contained configuration details for the server to run on port 5000 which i had to add a tcp port on AWS inbound rule before and then ran 
`node index.js` to check if the server was running and it did.
![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm3.PNG)
- Also it succesfully ran through the browser using port 5000
![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm4.PNG)
- Commenced on adding a routes folder and api.js file which would contain the routes for HTTP request methods which were GET, POST & DELETE.

**Step 3: Defining my Models using MongoDB & Using Postman to test APIs**
- Mongo DB - is a NOSQL Database( Document based) which means it stores data in a key-value pair structure.
- Ran `npm install mongoose` which is a Nodejs package that makes it easier to work with MongoDB.
- Also had to create a models folder and added a js file that created a schema and a model for my application.
- Signed into my MongoDb lab and created a cluster and connected to my application via Nodejs via the connection string provided.
- Added the conection string to my enviroment details and ran`node index.js`  on my server and the connection was succesful.
- Created a HTTP POST and GET Requests from postman to test my application so far. 
  ![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm8.PNG)
  ![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm9.PNG)
  
  
  **Step 4: Completing the Frontend using Reactjs**
  - Scaffolded a react app in my Todo directory using this command `npx create-react-app client`
  - Added some files and css code for my UI.
  - Ran the  `npm run dev` once i was through and the following UI was displayed on my browser.
     ![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm14.PNG)
  - Also had to confirm that the tasks i added on my Todo application via the UI was succesfully added to the database and it did.
    ![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/mongo.PNG)
  - Also tested the same using Postman and i was able to retrieve the tasks i previously added.
     ![alt text](https://github.com/Ellawangari/DevOps-Project003/blob/main/Images/npm15.PNG)
     
     
     ** This Project was truly an awesome experience as i got to learn new technologies.**
 

**End of DevOps Project 3**

To try this project  [darey.io](https://www.darey.io) has a free trial to which you can practice this project.
  
