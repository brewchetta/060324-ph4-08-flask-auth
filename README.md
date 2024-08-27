# Deployment with Flask & React

## Learning Goals

- Deploy an app via the Render service

## Getting Started

Fork / clone the repo and run
```bash
pipenv install
```

To start the server:
```bash
pipenv shell
cd server
flask db upgrade
python app.py
```

To start the client, create a separate terminal and run:
```bash
npm install --prefix client
npm run dev --prefix client
```
