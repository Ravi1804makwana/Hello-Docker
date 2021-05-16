<b>Create Docker Image</b>

Create Dockerfile.
Configure Setup.
Build Docker iamge
  docker build -t <pre><your-docker-repo-name></pre>

To check list of images in local machine
  docker image ls
  
To run docker image
  docker run <pre><your-docker-repo-name></pre>
  
<b>Push Repository in Docker Hub</b>

  docker login
  docker tag <pre><your-docker-repo-name>:tag <docker-username>/<docker-hub-repo-name>:tag</pre>
  docker push <pre><docker-username>/<docker-hub-repo-name>:tag</pre>
  
<b>Pull Docker image from Docker Hub</b>

  docker pull <pre><docker-username>/<docker-hub-repo-name>:tag</pre>
