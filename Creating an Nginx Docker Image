### Creating an Nginx Docker Image: Step-by-Step Guide

Creating a Docker image with Nginx involves setting up a Dockerfile
that defines how the image should be built. Here’s a very simple,
step-by-step guide to help you create an Nginx Docker image from scratch.

### Step 1: Install Docker

Before you start, make sure Docker is installed on your machine.
You can download and install Docker from the [official Docker website](https://www.docker.com/products/docker-desktop).

### Step 2: Create a Project Directory

Create a directory for your project.
This will contain the Dockerfile and any configuration files you need.

```bash
mkdir my-nginx-image
cd my-nginx-image
```

### Step 3: Create a Dockerfile

Inside your project directory, create a file named `Dockerfile` (with no extension).
This file will contain instructions for building your Docker image.

Here’s a simple Dockerfile to create an Nginx image:

```Dockerfile
# Use the official Nginx image from Docker Hub as the base image
FROM nginx:alpine

# Copy custom Nginx configuration file (if any)
# COPY nginx.conf /etc/nginx/nginx.conf

# Copy static website files to the Nginx server directory
COPY html /usr/share/nginx/html

# Expose port 80 to access the Nginx server
EXPOSE 80

# Define the command to run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]
```

### Step 4: Create Static Website Files (Optional)

If you want to serve a static website, create a directory named `html` in your project directory and add your HTML files there.

For example, create a file named `index.html` inside the `html` directory:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Welcome to Nginx (sagar)</title>
</head>
<body>
    <h1>Hello from Nginx Docker Image!</h1>
</body>
</html>
```

### Step 5: Build the Docker Image

Run the following command in your project directory to build the Docker image:

```bash
docker build -t my-nginx-image .
```

- `-t my-nginx-image` tags the image with the name "my-nginx-image".
- `.` specifies the current directory as the build context.

### Step 6: Run the Docker Container

After building the image, you can run it with:

```bash
docker run -d -p 8080:80 my-nginx-image
```

- `-d` runs the container in detached mode (in the background).
- `-p 8080:80` maps port 80 in the container to port 8080 on your host machine.

### Step 7: Access Your Nginx Server

Open a web browser and navigate to `http://localhost:8080`. You should see the
static website you created or the default Nginx welcome page if you didn't add custom HTML files.

### Step 8: (Optional) Customize Nginx Configuration

If you want to customize the Nginx configuration, create a `nginx.conf` 
file in your project directory and uncomment the `COPY nginx.conf /etc/nginx/nginx.conf`
line in the Dockerfile. Ensure your `nginx.conf` file is correctly configured for your needs.

### Summary

1. **Install Docker**: Make sure Docker is installed on your machine.
2. **Create a Project Directory**: Set up a directory for your project.
3. **Create a Dockerfile**: Define the Nginx setup and configuration in the Dockerfile.
4. **Create Static Files**: Add HTML files to be served by Nginx (optional).
5. **Build the Image**: Use `docker build` to create your image.
6. **Run the Container**: Use `docker run` to start the container and expose it on a port.
7. **Access the Server**: Open a browser to see your Nginx server in action.

By following these steps, you can create a basic Nginx Docker image to serve static content.
