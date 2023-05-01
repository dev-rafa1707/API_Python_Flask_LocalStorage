# API Python Flask basic
Essa API foi projetada para testar as operações de CRUD utilizando o Framework Flask



### Status do Projeto:
Finalizado


### Features
GETALL
GET BY ID
CREATE
UPDATE
DELETE


### Pré-requisitos 
1. Python
2. Flask


### How to run the application

1. criar ambiente virtual
python -m venv venv
2. ativar ambiente virtual
venv/Scripts/activate.bat (windows)
3. Instalar o flask
pip install flask


### How to test the project
* Use bd.py as your local database

From Flask
make_response,

jsonify

* We are useing request.rest that is a VSCode extension to test the routes, but you can use Postman or any other tool fot that purpose.

* Get All Cars
GET http://localhost:5000/cars
 
* Get by id
GET http://localhost:5000/cars/2
 
* Create Car
POST http://localhost:5000/cars
Content-Type: application/json

{
  "id":4,
  "brand":"KIA",
  "model":"Sportage",
  "year":2010
}

* Update a Car
PUT http://localhost:5000/cars/2
Content-Type: application/json

{
  "id":2,
  "brand":"Mitsubishi",
  "model":"ASX 4x4",
  "year":2022
}

* Delete by id
DELETE http://localhost:5000/cars/2



### Author
dev-rafa1707
<rafa1707@gmail.com>



### License
No license required