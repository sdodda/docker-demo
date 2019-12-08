demo repo to build docker image and push to repository.
docker build . 
docker run -p 3000:3000 -t <imageID> // running docker container locally

// To push an image to docker hub
docker login
docker tag imageID your-login/docker-demo
docker push your-login/docker-demo

