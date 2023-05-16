# API Python Flask basic
Essa API foi projetada para testar as operações de CRUD utilizando o Framework Flask



### Status do Projeto:
Finalizado


### Features
#### CRUD main operations
* GETALL
* GET BY ID
* CREATE
* UPDATE
* DELETE



#### Flask tools
* Flask makes response is defined as a utility function that enables users to add additional HTTP headers to the response within the view's code.

* jsonify is a function in Flask's flask.json module. jsonify serializes data to JavaScript Object Notation (JSON) format, wraps it in a Response object with the application/json mimetype.



### Pré-requisitos 
1. Python
2. Flask 3


### How to run the application

1. Download this project from Github repository
<https://github.com/dev-rafa1707/API_Python_Flask_LocalStorage.git>

2. Inside the folder, use this comand to create virtual environment
python -m venv venv

3. To activate virtual environment
venv/Scripts/activate.bat (windows)

4. Install Flask
pip install flask

5. Run main.py to run the program


### How to test the project
* Use bd.py as your local database

* We are using request.rest that is a VSCode extension to test the routes, but you can use Postman or any other tool for that purpose.

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