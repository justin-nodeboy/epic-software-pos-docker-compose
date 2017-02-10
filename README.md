#Epic Software Sale Docker Compose - WORK IN PROGRESS, NOT PRODUCTION READY

This is part of a product suite that allows you to build a full featured 
e-commerce system and to self host it. The platform includes an API, Web App, iOS and Android native apps.
All open source, all 100% free. [Contact us](mailto:justin@epic-software.co.uk) if you want bespoke hosting solutions.

## Installation

Follow these simple instructions to get up and running:

* Install docker by going [here](https://www.docker.com)
* Clone this repo `git clone https://github.com/justin-nodeboy/epic-software-pos-docker-compose.git`
* Run `docker-compose up`
* You should be able to access the API on [https://0.0.0.0:3443/](https://0.0.0.0:3443/) and the webapp on [http://0.0.0.0:3333/](http://0.0.0.0:3333/)
* A mongoDB will be running locally inside the network on port 27017



## Features

* Have a full featured e-commerce platform running in docker in under 5 minutes (Internet connection providing!)

## What needs doing
* Mongo DB security
* Build script (Chef?) and auto deployment for either Hyper.sh or AWS

## Other platform components
* API is located [here](https://github.com/justin-nodeboy/epic-software-pos-api)
* Web App is located [here](https://github.com/justin-nodeboy/epic-software-pos-web)

