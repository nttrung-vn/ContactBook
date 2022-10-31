# ContactBook

Backend for ContactBook Application * Lab of the Web Application Development course.

## Install all the missing packages

npm install

## Run server

npm start

## Test handler
### Create contact

POST: http://localhost:3000/api/contacts   
   
Header: "Content-Type:application/json"   
Body: 
{
    "name": "Nguyen Thanh Trung",
    "email": "nttrung@example",
    "address": "Vinh Long",
    "phone": "0372138632"
}

### Find All Contact

GET: http://localhost:3000/api/contacts/

### Find One Contact

GET: http://localhost:3000/api/contacts/635fe211f1fb80977e430245   

635fe211f1fb80977e430245 is ID, this is a example.

### Update Contact

PUT: http://localhost:3000/api/contacts/635fe211f1fb80977e430245   
   
Header: "Content-Type:application/json"   
Body: 
{
    "name": "Nguyen Thanh Trung",
    "email": "nttrung@example",
    "address": "Vinh Long",
    "phone": "0372138632"
}

### Find All Favorite

GET: http://localhost:3000/api/contacts/favorite 

### Delete One Contact

DELETE: http://localhost:3000/api/contacts/635fe211f1fb80977e430245 

### Delete All Contact

DELETE: http://localhost:3000/api/contacts/

