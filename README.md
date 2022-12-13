# gameswap

## To start Flask backend:
```
cd flask-server
python3 -m venv venv
source venv/bin/activate
```

Once you're in virtual env,
```
pip3 install Flask pymongo
python3 server.py
```
Try http://localhost:5000/members or http://127.0.0.1:5000/members in your browser to test API call.

## To start React frontend (do in a new terminal):
```
cd client
npm install
npm start
```
Try http://localhost:3000 or http://127.0.0.1:3000 to test frontend.
