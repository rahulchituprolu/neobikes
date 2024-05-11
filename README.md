Clone the repo.
Make sure you are using node js version 16.



Steps to run frontend:

1. Navigate to the angular folder in the cloned project.

2. run ```npm install```

3. run ```npm start```

4. now application runs at http://localhost:8081/



Steps to run backend:

1. install jdk

2. install maven (set environment path of the bin folder of downloaded maven folder)

3. install mysql server(add the mysql properties in application.properties file)

4. install mysql workbench

5. open mysql workbench and create a new database with database name as "test"  with the command - ```create database test```  

6. Navigate to spring folder in the cloned project.

7. run ```mvn spring-boot:run```

8. backend server starts running at http://localhost:8080/ and you can see "Api is running" there.


Now, the application is ready to serve.

# BikeBookingApplication
This is a bike booking application made with the help of angular for the frontend and spring boot for the backend server with mysql database
This application has 3 different types of users
1. Customer:
  Customer is the type of the person who can book the bikes from a selected company and use it. He will be having a email, password login
2. Admin:
  Admin is the one who owns/runs a company. He is the one who provides bikes to the customers and at any time he can change the price and details of the bike or add a new bike.
  He can even see the which bikes are available and which are booked. He can see all the past bookings and current one's with respective to the company
3. Super Admin:
  He is the one who has the control over the application. He can monitor over other admin and their bookings. At any point of time he can delete an admin.

