<b>Create Docker Image</b>

Create Dockerfile.
Configure Setup.
Build Docker iamge
  docker build -t <your-docker-repo-name>

To check list of images in local machine
  docker image ls
  
To run docker image
  docker run <your-docker-repo-name>
  
<b>Push Repository in Docker Hub</b>

  docker login
  docker tag <your-docker-repo-name>:tag <docker-username>/<docker-hub-repo-name>:tag
  docker push <docker-username>/<docker-hub-repo-name>:tag
  
<b>Pull Docker image from Docker Hub</b>

  docker pull <docker-username>/<docker-hub-repo-name>:tag
