1. nambah user
   POST http://localhost:8080/api/v1/auth/signup
   {
  "firstName": "",
  "lastName": "",
  "email": "@example.com",
  "password": "",
  "role": "" ADMIN/USER
   }

2. sign in
   POST http://localhost:8080/api/v1/auth/signin
   {
  "email": "@example.com",
  "password": ""
   }

3. Masukin token
   GET http://localhost:8080/api/v1/user / http://localhost:8080/api/v1/admin
   masukin tokennya

4. Read data
   GET http://localhost:8080/api/v1/admin/users

5. Search by id
   GET http://localhost:8080/api/v1/admin/users/3 (no id

6. Delete data
   DEL http://localhost:8080/api/v1/admin/users/3 (no id)



   
