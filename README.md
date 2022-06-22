# assignment1 - Java application with two data sources - mongoDb and MySQL

STUDENT RECORDS MANAGER APPLICATION
A student and a course are entities, while an enrollment is a relationship between a student and a course.
![ER-Diagram](https://user-images.githubusercontent.com/106801605/174994463-284caabd-2426-48d1-8a22-9c1c127f28c0.png)



POST /createresource
GET /readresources
PUT /updateresource
DELETE /deleteresource

Sample post request(to http://localhost:8080/createresource):-

{
    "firstName":"Rajat",
    "lastName": "Kansal",
    "email": "rajat123@gmail.com",
    "courses":[
        {
            "name":"C++",
            "description":"Programming Language",
            "email":"AM101"
        },
        {
            "name":"Linux",
            "description":"Operating System",
            "email":"AM105"
        }
    ]
}
