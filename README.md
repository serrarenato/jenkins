# jenkins-ist
Github repo for automated builds of a custom version of Jenkins on docker hub.
## Building
docker-compose up
## Check Admin Password
sudo docker exec -it jenkins cat /var/jenkins_home/secrets/initialAdminPassword 
## Password
d1f2a48b4ba4476e8b3d465932cf0d02
## Run
http://localhost:8080/