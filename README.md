Pour build l'image : 

docker build -t frontend-dockerfile .

pour demarrer un conteneur : 

docker run --name frontend-test -p 4242:4200 frontend-dockerfile

![alt text](image.png)