# Application Documentation

## Running the Application

Follow these steps to build and run the application using Docker.

### Step 1: Build the Docker Image

Run the following command to build the Docker image:

docker build --tag aspnetapp:1.0 .

This will create a Docker image tagged as `aspnetapp:1.0`.

### Step 2: Run the Docker Container

Use the following command to run the container:

docker run -p 8080:8080 aspnetapp:1.0

This will start the Docker container and map port 8080 from the container to port 8080 on your host machine.

### Step 3: Access the API

Once the container is running, open your browser and navigate to:

http://localhost:8080/swagger/index.html

This will load the Swagger UI for the API, where you can interact with the available endpoints.
