

# Employee-Review-System
A full stack, app used for reviewing employee.



### Description

A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee
as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the
review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.


### Tech Stack

Node , Express, Mongodb , EJS , javaScript , html, css

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.

   ```
        npm install 
        npm start || nodemon index.js
   ```

#### If you want to make an employee as admin then use the secret key : happy.

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
  
  
  ### HomePage / Admin View

  ### Home page / Employee view

  ### Sign-Up

  ### Sign-In

  ### Forget Password
  
  ### Assign Task

  ### Employee List
  

  

### Folder Structure

```
Employee Review System
.
├── README.md
├── assets
│   ├── css
│   │   ├── admin.css
│   │   ├── footer.css
│   │   ├── header.css
│   │   ├── home.css
│   │   └── sign.css
│   └── images
│       ├── logo.png
│       ├── profile.jpg
│       ├── rating.webp
│       └── signBack.jpg
├── config
│   ├── flashMiddleware.js
│   ├── mongoose.js
│   └── passport-local.js
├── controllers
│   ├── admin_controller.js
│   ├── home_controller.js
│   ├── review_controller.js
│   └── user_controller.js
├── index.js
├── models
│   ├── review.js
│   └── user.js
├── package-lock.json
├── package.json
├── routes
│   ├── admin.js
│   ├── index.js
│   ├── reviews.js
│   └── users.js
└── views
    ├── _footer.ejs
    ├── _header.ejs
    ├── addEmployee.ejs
    ├── admin.ejs
    ├── employee.ejs
    ├── forget_password.ejs
    ├── home.ejs
    ├── layout.ejs
    ├── sign_in.ejs
    └── sign_up.ejs
    
    ````
