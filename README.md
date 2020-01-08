# DockerKubernetesSection6

# Docker build 
docker build -f DockerFile.dev .

# Docker run
docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app a5fbb635baf1
