# Server Configuration

The directory `serverFiles` should be in the root directory (e.g. `/serverFiles/`).

## Docker Compose

Inside the `serverFiles` folder, run `sudo docker-compose build --no-cache && sudo docker-compose up` to start the backend.

### Services

* Heimdall - A dashboard for all the services
* NGINX web server - used to store misc. files such as music*

## HAProxy

To start the reverse-proxy, navigate to the `serverFiles` folder and run `sudo haproxy -f test.cfg`.
