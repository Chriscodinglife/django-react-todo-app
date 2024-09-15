# Django React Todo App

![todo](images/todo.png)

## Some dependencies

This uses Pipenv for package management for Python and NPM for the React Frontend

```bash
brew install pipenv
brew install nodenv
pipenv shell
pipenv install
nodenv init
nodenv install $(cat .node-version)
nodenv local $(cat .node-version)
npm install
```

## How to run

Run the python server

```bash
cd backend
python manage.py runserver
```

Run the front end

```bash
cd frontend
npm start
```
