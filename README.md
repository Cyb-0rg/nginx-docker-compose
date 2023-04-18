# nginx-docker-compose

## Run the following command to start the Nginx container: -d for detached
<pre>
docker-compose up -d
</pre>

### You can now access the Nginx web server by navigating to:
<pre>
    http://localhost:80
</pre>

## brief explanation
<pre>
In this docker container, we're using the official Nginx Docker image from Docker Hub (nginx:latest). We're mapping port 8080 on the host to port 80 on the container, and we're also using a volume to mount an external Nginx configuration file (nginx.conf) into the container at /etc/nginx/nginx.conf. The restart option could be used to ensure the Nginx container restarts automatically if it goes down.
</pre>
