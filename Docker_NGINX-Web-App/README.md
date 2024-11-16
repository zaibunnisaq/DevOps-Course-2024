# My Webpage - Dockerized NGINX Web Application 🌐

This is a simple web application deployed using Docker and served via NGINX. The application serves an `index.html` file, providing a basic webpage. The setup leverages Docker to containerize the web application, making it portable and easy to deploy.

## Project Structure 📂

The project consists of the following key files:

- **Dockerfile**: Defines the image creation process, specifying that the application will be served using the NGINX web server.
- **index.html**: Contains the basic HTML structure and content of the webpage that will be displayed when accessed through a browser.
- **index**: This file may contain additional configurations or serve as a placeholder, depending on your use case.

## Features 🚀

- Dockerized NGINX web server.
- Portable and easy to deploy across different environments.
- Simple static webpage served via NGINX.

## Getting Started 🛠️

To build and run this project on your local machine, follow the steps below:

### Prerequisites ⚙️

- Docker must be installed on your system. If you don't have Docker, follow the instructions to [install Docker](https://docs.docker.com/get-docker/).

### Running the Application 🚀

1. Clone this repository to your local machine:

   ```bash
   git clone <[repository-url](https://github.com/zaibunnisaq/DevOps-Course-2024/Docker_NGINX-Web-App)>
   cd <[repository-directory](https://github.com/zaibunnisaq/DevOps-Course-2024)>
   
2. Build the Docker Image:

   ```bash
   docker build -t <your-docker-username>/my-webpage:latest .
   
3. Run the Docker container:

   ```bash
   docker run -d -p 8080:80 <your-docker-username>/my-webpage:latest
4. Access the webpage in your browser:

   ```bash
   http://localhost:8080
## Docker Hub Deployment 📦
If you want to push this image to Docker Hub, follow the steps below:

Tag and Push your image to Docker Hub:
```bash
docker tag <your-docker-username>/my-webpage:latest <your-docker-username>/my-webpage:v1
docker push <your-docker-username>/my-webpage:v1

