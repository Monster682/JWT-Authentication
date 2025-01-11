# JWT-Authentication

npm install
npm run start-auth
npm audit fix


You can login/register by sending a POST request to

POST http://localhost:8000/auth/login
POST http://localhost:8000/auth/register


#Json Data
{
  "email": "Vaibhav@email.com",
  "password":"Vaibhav"
}

#Access token
{
   "access_token": "<ACCESS_TOKEN>"
}


#Endpoint

Authorization: Bearer <ACCESS_TOKEN>



