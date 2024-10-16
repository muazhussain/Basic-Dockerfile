# Basic Dockerfile

## Overview

This project demonstrates how to create a simple Docker image that displays the message "Hello, Captain!" when run. 
Learn more: https://roadmap.sh/projects/basic-dockerfile

## Project Structure

```
Basic-Dockerfile/
└── Dockerfile
└── readme.md
```

### Files

- **Dockerfile**: Contains the instructions to build the Docker image.
- **readme.md**: A brief description of the project.

## Getting Started

Follow these steps to build and run the Docker image.

### 1. Clone the Repository

```bash
git clone https://github.com/muazhussain/Basic-Dockerfile.git
cd Basic-Dockerfile
```
### 2. Build the Docker Image

Run the following command to build your Docker image:

```bash
docker build -t basic-dockerfile .
```

### 3. Run the Docker Container

Execute the following command to run the container and see the output:

```bash
docker run --rm basic-dockerfile
```

You should see the following output:

```
Hello, Captain!
```

## Conclusion

You have successfully created a Docker image that displays "Hello, Captain!" when run. 