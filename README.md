# django-react-todo

## Description
This is a basic todo app to demonstrate CRUD functionality using Django and React

## User Story

* I want to be able to create tasks with a Title, Description, and to mark them as Complete or Incomplete
* I want to see completed and incomplete tasks on my todo list
* I want to be able to edit tasks
* I want to be able to delete tasks

## Development Planning
* Define Todo model in backend
* Create a Django database
* Modify backend with a serializer in order to work with frontend
* Create Viewset to implement CRUD operations
* Create Frontend – initially set static values to ensure complete and incomplete tasks can be viewed
* Remove static information and utilize axios in order to have frontend interact with Django

## Program Preview
![Preview of application](https://cdn.zappy.app/530b001a89ba0513139cba255bbe5fa1.gif)

## Technologies Used
* React
* Django
* Bootstrap

## Setup/Installation Requirements
Requirements:
* Install and set up a local programming environment for [Python 3](https://www.digitalocean.com/community/tutorial_series/how-to-install-and-set-up-a-local-programming-environment-for-python-3)
* Install [Node.js and Create a Local Development Environment](https://www.digitalocean.com/community/tutorial_series/how-to-install-node-js-and-create-a-local-development-environment)

Project set up:
_In order to copy this directory to your computer locally:_
* open Terminal and navigate to desktop by typing `cd desktop`
* `git clone git@github.com:PoterekM/django-react-todo.git`
* Ensure that you have your local Python envioronment running
* Navigate to the backend folder `cd backend`
* start the server `python manage.py runserver`
* In another window, navigate to the frontend folder `cd frontend`
* Start the frontend server `npm start`
* Open http://localhost:3000/ to view the app

## Known Bugs
* A user cannot currently create a todo item if it does not have a description

## Acknowledgements
* This was a great tutorial from [Digital Ocean](https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react).

