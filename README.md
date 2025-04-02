# AlmuniTraker

1.unctionalities
  -admin
        1. the admin can add the data.
        2. the admin can manage data, and store efficiently.
        3. the admin should automate the work if applicable for easy storing, the admin should convert the follwoing files to db(.csv or .xsl).
        4. the data should be secured and easy to maintain.
  -user side
        1. search their data.

2.DataBase(Mysql)
    - schema (CCICT graduate's data)
        -> table for the schemas
            1. table for the course
            2. works
            3. year graduated
            4. personal info
src/
├── main/
│   ├── java/
│   │   └── com/AluminiTracker/
│   │       ├── controllers/
│   │       │   └── HomeController.java
│   │       ├── models/
│   │       │   └── User.java
│   │       ├── repositories/
│   │       │   └── UserRepository.java
│   │       └── Application.java
│   └── resources/
│       ├── static/
│       │   ├── css/
│       │   │   └── main.css
│       │   └── js/
│       │       └── script.js
│       ├── templates/
│       │   ├── fragments/
│       │   │   ├── header.html
│       │   │   └── footer.html
│       │   ├── home.html
│       │   └── user/
│       │       └── profile.html
│       └── application.properties
└── test/