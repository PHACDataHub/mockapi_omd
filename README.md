# Mock API for rendering dummy data for clusters and isolates

Included in this repo is a small application that demonstartes provisioning dummy data for isolates and clusters using GraphQL.
This application is curently deployed as a container image on Google Cloud Run service and can be accessed via url:- https://omd-mockapi-6ef5a33mba-nn.a.run.app/

Alternatively docker image can be built locally using the Dockerfile available in this repo using the command:-
`sudo docker build -t "mockapi:1.0 .`

This command builds an image locally with a name mockapi and version 1.0 which can then be run as :- ` sudo docker run -d -p 8000:8080 mockapi:1.0`
After this the application can be accessed at:- http://localhost:8000/

