ContosoPizza is a Rest API application which takes different HTTP methods as parameters and returns HTTP RESTful responses.

.NET Cli - `https://dotnet.microsoft.com/en-us/download`

For cloning this repository:
`git clone https://github.com/wevak/dotnet-restapi-contosopizza.git`

To build application - `dotnet run`

|     Method			 | Curl Command Line        |                 
|------------------------|--------------------------|
GET   |`curl -H "Content-Type:application/json"\ -X GET http://localhost:5027/pizza/2`
GET	| `curl -H "Content-Type: application/json"\ -X GET http://localhost:5027/pizza`
POST	|	`curl  -H 'Content-Type: application/json'\ -d '{ "name": "ClassicVeggie", "isGlutenFree": true, "id": 3}'\-X POST  http://localhost:5027/pizza/`
PUT	|	`curl  -H "Content-Type: application/json"\ -d '{ "name": "ClassicVeggie", "isGlutenFree": false, "id": 3}'  \-X PUT http://localhost:5027/pizza/3`
DELETE	|	`curl  -H "Content-Type: application/json"\ -X DELETE http://localhost:5027/pizza/4`
