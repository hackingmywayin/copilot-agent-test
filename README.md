# Deployment Instructions

## Cloning the Repository
1. Open your terminal or command prompt.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/hackingmywayin/copilot-agent-test.git
   ```

## Building the Docker Image
1. Navigate to the project directory:
   ```bash
   cd copilot-agent-test
   ```
2. Build the Docker image with the following command:
   ```bash
   docker build -t copilot-agent-test .
   ```

## Running the Container
1. Once the image is built, you can run the container using:
   ```bash
   docker run -p 8080:8080 copilot-agent-test
   ```
2. This will start the application and map port 8080 in the container to port 8080 on your host.

## Accessing the Spark Application
1. Open a web browser.
2. Navigate to `http://localhost:8080` to access the Spark application interface.

Make sure you have Docker installed and running on your machine before following these instructions.