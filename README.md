# Installation

Make sure you have NodeJS installed first.

Clone this repository, and then run the following commands:
```
cd server
npm install
```
and
```
cd client
npm install
```

There are 2 ways to run this app:

### Development
You will need 2 terminals for this. In the first terminal, run ```cd server``` and run ```npm run dev```. In the second terminal run ```cd client``` and then run ```npm start```.

### Production
The Express server can serve the React app if you have run ```npm run build``` in the client folder. If the build exists, simply run ```node server``` in the ```server``` directory. If you open your browswer to http://localhost:8085, you should see the production version of your React app.

## Other Notes
The default proxy port is 8085, but you can change this in client/package.json.
