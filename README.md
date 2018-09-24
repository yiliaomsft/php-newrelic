# php-newrelic
1.	Create a free account on newrelic.com and retrieve the license key from account settings.
2.	Clone the repo, change the Dockerfile by replacing the license key and app name. 
3.	Build the web app conatiner image and push to DockerHub. 
4.	Modify the docker-compose.yml by replacing web container image with your own. DON’T use my docker-compose file as is, as it will push stats to the incorrect Newrelic account!
5.	Deploy to a web app for containers, the pinger will  hit the web site every 2 seconds and you would get a nice APM graph on Newrelic console. 
