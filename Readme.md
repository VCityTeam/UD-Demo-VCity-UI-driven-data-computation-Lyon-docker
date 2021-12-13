# Demo UI-driven data computation

Create a docker of a [demo of Lyon with UI-driven-data-computation](https://github.com/VCityTeam/UD-Demo-VCity-UI-driven-data-computation-Lyon).  
_See the [online version](https://ui-driven-lyon.vcityliris.data.alpha.grandlyon.com/)_.

The demo uses a [SimpleServer](https://github.com/VCityTeam/UD-SimpleServer), based on [ExpressJS](https://en.wikipedia.org/wiki/Express.js) web-server.

Clone the repo

```bash
git clone https://github.com/VCityTeam/UD-Demo-VCity-UI-driven-data-computation-Lyon-docker.git
cd UD-Demo-VCity-UI-driven-data-computation-Lyon-docker
```

Build the docker image with

```bash
docker build -t demo_ui-driven-data-computation .
```

and run the container with

```bash
docker run -p 8082:80/tcp -t demo_ui-driven-data-computation
```

and open a web browser on URL `http://localhost:8082/`
