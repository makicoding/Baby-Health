# Baby-Health-App

[Click here to view deployed app](http://babyhealth.herokuapp.com/)
<br>
***

Technologies used: HTML, CSS, JavaScript, React, JSX, Bootstrap, Font Awesome, Datepicker, Moment, Node, Express, Mongoose, ORM (Object-Relational Mapping), MongoDB, NoSQL, RESTful API, JSON, AXIOS, mLab, Heroku.
<br></br>
App is responsive and designed for a mobile screen and larger. 

***
### Overview:

An app to keep track of a baby's health.

Baby Health is a MERN Stack app (MongoDB, Express, React, Node).
<br></br>

<kbd>![Screenshot](https://raw.githubusercontent.com/makicoding/Baby-Health/master/screenshot/BabyHealth_Screenshot_01.png)</kbd>
***
### Technical specification by page:

#### Data Entry:
The user can enter their baby's health into the form. The data is then sent and stored in MongoDB.

The app uses its own RESTful API. A RESTful API is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data. This functionality is also known as CRUD (Create, Read, Update, Delete).
<br></br>

#### Data Log:
The user can retrieve their baby's data entered on the Data Entry page from MongoDB.  The retrieved data is then filtered by date and sorted by time. The page has button options to allow a user to edit or delete an entry in MongoDB.