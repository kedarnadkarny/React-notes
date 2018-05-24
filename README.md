## Setup Notes
* download git on your system.

* download nodejs on your system.

* Clone this project using
`git clone https://github.com/kedarnadkarny/React-notes.git`

* After that-
`cd React-notes`

* To install all dependencies-
`npm install`

* Setup your Firebase account
https://firebase.google.com/


* Create a project and change database rules in Realtime Database- (Caution! Anyone with acess to your app can add/remove data!)

    `{"rules": {
    ".read": true,
    ".write": true
  }
}`

* Create file config.js under src/Config

* Get details from firebase project and add to config.js

```
export const DB_CONFIG = {
    apiKey: "XXXXXXXXXXX-XXXXXXXXXXX",
    authDomain: "project.yourapp.com",
    databaseURL: "URLtoYourDatabase",
    projectId: "projectID",
    storageBucket: "BucketURL",
    messagingSenderId: "messagingId"
};
```

* Enter `npm start` in command line and the app will start in your browser.

