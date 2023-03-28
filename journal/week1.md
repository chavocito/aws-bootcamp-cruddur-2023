# Week 1 — App Containerization









Docker for vscode as an extension

##Containerize backend

###Run python

```sh
cd backend-flask
export FRONTEND_URL="*"
export BACKEND_URL="*"
python3 -m flask run --host=0.0.0.0 --port=4567
cd ..
```

- make sure to unlock the port on the port tab
- open the link for 4567 in your browser
- append to the url to  '/api/activities/home'


##Build Container
```docker build -t backend-flask ./backend-flask```

##Run Container
```Run```