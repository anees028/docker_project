# Docker Learning Project

This project demonstrates a basic Node.js application containerized with Docker.

## Current Project Structure

```
docker_project/
├── Dockerfile          # Contains Docker configuration
├── app.js             # Simple Node.js application
└── README.md          # Project documentation
```

## Current Implementation

### 1. Node.js Application (app.js)
A simple Node.js application that prints "Hello Docker !" to the console.

### 2. Docker Configuration (Dockerfile)
The Dockerfile is configured to:
- Use Node.js Alpine image as the base
- Copy all project files to /app directory
- Set working directory to /app
- Run the Node.js application

### 3. Docker Commands Used
To build and run the application:

```bash
# Build the Docker image
docker build -t my-node-app .

# Run the container
docker run my-node-app
```

## Next Steps
1. Add more functionality to the Node.js application
2. Implement proper error handling
3. Add environment variables
4. Set up proper logging
5. Consider adding a web server framework like Express.js
