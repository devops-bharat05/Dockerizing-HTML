## Objective:

The objective of this assignment is to familiarize yourself with Docker and containerization by Dockerizing a simple HTML page using Nginx as the web server.

Requirements:

1. Basic HTML Page:

   - Create a plain HTML page named `index.html` with some content (e.g., "Hello, Docker!").

2. Nginx Configuration:

   - Create an Nginx configuration file named `nginx.conf` that serves the `index.html` page.

   - Configure Nginx to listen on port 80.

3. Dockerfile:

   - Create a `Dockerfile` to define the Docker image.

   - Use an official Nginx base image.

   - Copy the `index.html` and `nginx.conf` files into the appropriate location in the container.

   - Ensure that the Nginx server is started when the container is run.

4. Building the Docker Image:

   - Build the Docker image using the `Dockerfile`.

5. Push the image on ECR

  - Make the public repository and push them on the ECR

6. Documentation:

   - Provide a brief documentation (in a README.md file) explaining the purpose of each file (index.html, nginx.conf, Dockerfile) and the steps to build and run the Docker container.


7. Submission:

   - Push all artifacts including the link of the public repository on the README.md file and docker file into the GitHub repository and submit the repository.

Bonus (Optional):

For those looking to go the extra mile:

- Customization: Add more features to your HTML page or customize the Nginx configuration to serve additional static files.


- HTTPS Support: Explore and implement support for serving the HTML page over HTTPS.


- Docker Compose: Create a `docker-compose.yml` file to define and run the Docker container, making the process even more streamlined.
