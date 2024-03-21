In this section added the gatewayserver/edge server for microservices. 

Added pre, post filters in gatewayserver projects. 

Added filters to modify api paths.

Added corelation id in request and response headers.

Used this corelation id to create cross cutting concers like logging and monitoring.

Added jib maven dependency in pom.xml to create docker image.

Modified the docker compose file to create container for gateway server.

Creted images for configserver, eurekaserver, account microservice, card  microservice, loan microservice and gatewayserver and pushed all images into dockerhub and created containers for all using docker compose.

Tested all the rumnning  containers using postman api calls.
