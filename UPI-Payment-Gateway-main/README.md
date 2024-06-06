

## Tech 
MERN Stack

👉 Download the zip file or clone this repository

👉 Extract the file and open **UPI-Payment-Gateway** folder in visual studio code

## Client-side 

👉 change baseUrl in config.js file in **UPI-Payment-Gateway\client\upi-payment-gateway** folder

👉 baseUrl is your server(backend) url.

👉 Run this command
  
    npm install

👉 Run this command for Start Project
  
    npm run dev

## Server-side

👉 create .env file in **UPI-Payment-Gateway\server** folder(copy of .eve.sample file)

    PORT=10000
    merchant_key={write your merchant key of https://upigateway.com/}
    fronted_url=https://www.mitramgroup.in/receipt
    connectionString=mongodb://localhost:27017/upiPaymentGateway

👉 fronted_url means it is redirect url for payment gateway. localhost not working for that that's why enter random any site for testing.

👉 for generate merchant_key, all steps written below.

👉 Run this command
  
    npm install

👉 Run this command for Start Project
  
    npm start



## Download Node JS : 

  **https://nodejs.org/en/download/**

## Download MongoDB Compass : 

  **https://www.mongodb.com/try/download/compass**

## Youtube Channel : 
 
  **https://www.youtube.com/DarshanParmarK**
