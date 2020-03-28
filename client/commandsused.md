// List all image sin the system
docker images

// build the docker image from the dockerfile
docker build -t  hellow-world .

// list the containers (images that run currently)
docker ps

// stops the container/s 
docker stop 5cb294f921a4


// run the docker  to port and -v volume 
docker run -p 80:80 -v C:\Users\Paul\Documents\Programs\learn-docker\client\src\:\var\www\html  hellow-world


docker run -p 80:80 hellow-world