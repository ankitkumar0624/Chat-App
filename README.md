![Chat Website](https://github.com/rohit01010/Chat-App/blob/main/WebsiteImage.png)

## <a href="https://chat-it-now.web.app/">LIVE DEMO</a>

## Description

This is a React js and firebase based Chat web-app.

## Contributors

## <a href="https://github.com/ankitkumar0624/">Ankit Kumar</a>

## How to run it on your PC

### Fork and clone it on your desktop.

### run command: npm install

Before running this command make sure you have node installed in your PC.
This will download all the node modules required

### firebase setup

- Log in to <a href="https://console.firebase.google.com">https://console.firebase.google.com</a> and create new project.
- Create a web app by clicking on icon labeled: </> , make sure you checked on the hosting while creating web app.
- Click on Authentication and enable email and google.
- Click on Cloud firestore and create data base in test mode and location on your choice(keep it as it is if not necessary)
- Create a collection name _users_ and add a new document with _localtime(type: String)_, _message(type: String)_, _timestamp(type: timestamp)_, _username(type: String)_ fields {this step is optional }
- Click on setting icon present on right-side of Project Overview, then click on project setting and copy data present in general->Your apps->Firebase SDK snippet->Config->const firebaseConfig = {
- Now go to project on your pc and go to the file src->firebase.js and paste the data copied in last step inside: const firebaseApp = firebase.initializeApp({

### run command: npm start

- This will start your app at http://localhost:3000/

### Now you are ready to use and modify it

#### Star this repository if you like this project


