how to run these project
npm install
npm run start


import Ecommerce.postman.json file using postman software
and then you can run below api's using postman software

list of apis below are present

for product creation
http://localhost:8080/api/products

input json params
{
     "productName":"android2",
    "productSpecification":{"color":"red","memory":523}  
}


for order creation
http://localhost:8080/api/orders

input json params
{
    "productID":5,
    "orderDescription":"android mobile is very fast"
}


for updating order  api

http://localhost:8080/api/orders/20

input json params
{
    "orderDescription":"anroid is very fast and nice mobile "
}


delete api
http://localhost:8080/api/orders/16


get api
http://localhost:8080/api/orders/21


validations 
header type validation is added
object keys validations added
use of async


