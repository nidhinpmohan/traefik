
1. Install docker
2. Install docker compose
3. Create a network called proxy using the below command

sudo docker network create proxy

4. Create a acme file using below 
 
touch acme.json
sudo chmod 600 acme.json


5. change the email id in traefik.yml
6. Change the basic auth user name and password after creating one, for credentials creation use

htpasswd -nb admin secure_password
