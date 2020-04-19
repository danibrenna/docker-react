RUN PRODUCTION ENVIRONMENT

sudo docker build . // take image id 
sudo docker run -p 8080:80 <container_id>

RUN DEV ENVIRONMENT
sudo docker-compose up
oppure sudo docker-compose up web // without tests