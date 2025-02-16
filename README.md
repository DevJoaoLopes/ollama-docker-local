# Ollama Docker Local

This repository contains a Docker environment to run Ollama locally.

## Getting Started

- Docker installed
- Docker Compose installed

## Instructions

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/ollama-docker-local.git
    cd ollama-docker-local
    ```

2. Build and start the containers:

    ```sh
    docker-compose up -d
    ```

3. Access the service:

    - The page will be available at `http://localhost:8080` (or the port configured in `docker-compose.yaml`).

## Useful Commands

- Stop the containers:

    ```sh
    docker-compose down
    ```

- Check the logs:

    ```sh
    docker-compose logs
    ```

- Restart the containers:

    ```sh
    docker-compose restart
    ```

## Project Structure

- `docker-compose.yaml`: Docker Compose configuration file.
- `Dockerfile`: Docker configuration file to build the image.

## Contribution

1. Fork the project.
2. Create a branch for your feature (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.

## License

See the [LICENSE](LICENSE) file for more details.
