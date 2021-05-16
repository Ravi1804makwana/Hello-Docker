<b>Create Docker Image</b>

Create Dockerfile.
Configure Setup.
Build Docker iamge<br/>
  `
  docker build -t <your-docker-repo-name>
  `

To check list of images in local machine<br/>
  `
  docker image ls
  `
  
To run docker image<br/>
  `
  docker run <your-docker-repo-name>
  `
  
<b>Push Repository in Docker Hub</b>
<br/>
  `
  docker login
  `<br/>
  `
  docker tag <your-docker-repo-name>:tag <docker-username>/<docker-hub-repo-name>:tag
  `
  <br/>
  `
  docker push <docker-username>/<docker-hub-repo-name>:tag
  `
  
<b>Pull Repository from Docker Hub</b><br/>

  `
  docker pull <docker-username>/<docker-hub-repo-name>:tag
  `
