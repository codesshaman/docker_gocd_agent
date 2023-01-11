# GoCD agent inside of Docker container

Install:

``git clone https://github.com/codesshaman/docker_gocd_server.git``

In first, past your agent key inside environment variables in docker-compose.yaml!

Build:

``make build``

or

``docker-compose up -d --build``

Down:

``make down``

or

``docker-compose down``

Up:

``make``

or

``docker-compose up -d``

If neceary, uncommit volumes lines for acess to target service and use agent with service.
