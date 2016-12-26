### basic_auth_Node.js
Used the basic access authentication approach to do basic authentication.

#### Description 

*  contains 3 Files server.js,cookie.js,session.js 

> server.js is about  

*  Setting up an Express server to handle basic authentication.
*  Using the basic access authentication approach to do basic authentication.

> cookie.js is about

*  Setting up an Express application to send signed cookies.
*  Setting up your Express application to parse the cookies in the header of the incoming request messages


> session.js is about

* Setting up your Express server to use Express sessions to track authenticated users
* Enable clients to access secure resources on the server after authentication.


#### Installation Instructions :grey_exclamation:

* Clone or download the repo. into any fresh temporary folder.

* Cd into that root folder you just cloned locally.

* Open terminal in the current folder and type 

*  node server.js This will start a server for server.js at 

```javascript
   http://localhost:3000 
```

* node cookie.js This will start a server for cookie.js at 

```javascript
   http://localhost:4000 
```


* node session.js This will start a server for session.js at 

```javascript
   http://localhost:8000 
```


#### Package Manager Used (NPM)

* NPM is the default package manager for the JavaScript runtime environment Node.js.

#### Package.json (dependencies)

  "dependencies": {
    "body-parser": "~1.15.1",
    "cookie-parser": "~1.4.3",
    "debug": "~2.2.0",
    "express": "~4.13.4",
    "jade": "~1.11.0",
    "morgan": "~1.7.0",
    "serve-favicon": "~2.3.0",
    "session-file-store": "~1.0.0",
    "express-session": "~1.14.2"
  }


#### For Testing (Postman)

* Postman extension can be used for testing !
* Supercharge your API workflow with Postman! Build, test, and document your APIs faster.
* You can now fire up postman and then perform several operations on the REST API.



