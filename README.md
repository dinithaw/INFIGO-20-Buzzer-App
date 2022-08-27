A buzzer app made for Quizz program of MCICTS ICT day 2020 "INFIGO`20"!
App was originally made by Dinitha Wickramasinghe, purindu Weerawardena & Sanuth Desith. Project was also held by daniel.j.farrelly's Buzzer app project!
Uses websockets to sent messages.

## Running the app

You'll need [Node.js](https://nodejs.org) or [Docker](https://www.docker.com/) to run this
application. For Node:

```
npm install
node index.js
```

For Docker:

```
docker build -t buzzer .
docker run -p 8090:8090 buzzer
```

Open http://localhost:8090 in your browser to start!

## How to use

The players goto the homepage (`http://localhost:8090/`) and they can enter their name and team
number. Joining will give them a giant buzzer button!

The host heads over to `/host` and will be able to see everyone that buzzes in and clear the list
in between questions.

Join a team                | Buzz in                   | Host view                  |
:-------------------------:|:-------------------------:|:-------------------------:|
<img width="250px" src="https://github.com/bufferapp/buzzer/blob/master/screenshots/player-join-v3.png?raw=true" alt="Join a team"/> | <img width="250px" src="https://github.com/bufferapp/buzzer/blob/master/screenshots/player-buzzer-v3.png?raw=true" alt="Buzz in"/> | <img width="250px" src="https://github.com/bufferapp/buzzer/blob/master/screenshots/host-v3.png?raw=true" alt="Host view"/>

## License

MIT
All rights reserved by. ICT Society of Mahanama College Colombo 03 (MCICTS)
2020-01-10
