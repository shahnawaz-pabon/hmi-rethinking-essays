<div align="center">
  <h2>Rethinking Essays: Alternatives in Education Using AI</h2>
</div>

This project runs a Jupyter Notebook inside a Docker container. Follow the instructions below to set up and run the project.

### Prerequisites

- [Docker installed on your system](https://github.com/shahnawaz-pabon/daily-encyclopedia/tree/main/docker#installing-docker).
- Docker Compose installed on your system.

### Setup Instructions

1. **Clone the repository:**

    ```bash
    git clone https://github.com/shahnawaz-pabon/hmi-rethinking-essays.git
    cd hmi-rethinking-essays
    ```

2. **Build the Docker image and run the Docker container**
    
    ```bash
    docker compose up --build
    ```

3. **Access Jupyter Notebook:**

    After running the container, you can access Jupyter Notebook by navigating to http://localhost:8888 in your web browser. You will need the token that is printed in the terminal.

4. **Stopping the container:**

    To stop the running container, press Ctrl+C in the terminal where the container is running. To stop and remove the container completely, run:

    ```bash
    docker compose down
    ```