This docker-compose file uses version "3.1" as secrets are not supported in version "3". Also the build is ignored in stack therefore I have used official image only instead building it.

To deploy the containers in the cluster, 
First create a secret for the password of the database by running this command

	> echo " <<YOURPASSWORDHERE>> " > docker secret create psql_pass -


Then, deploy the cluster by

	> docker stack deploy -c docker-compose.yml drupal


To check whether the containers are running or not, run the command

	> docker stack ls 
	> docker stack ps drupal


To list the services in the stack,

	> docker stack service drupal


To delete the stack 

	> docker stack rm drupal
