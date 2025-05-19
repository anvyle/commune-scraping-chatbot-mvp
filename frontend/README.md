# Scraping Chatbot (Frontend)

## Installation

1. Clone the repository and navigate to the project directory.

2. Build the Docker image:

    ```bash
    docker build -t scraping-frontend .
    ```

3. Optionally, set the `NEXT_PUBLIC_RESTFUL_API` environment variable in a `.env` file.

## Usage

1. Run the container:

    ```bash
    docker run --env-file .env -p 3000:3000 scraping-frontend
    ```

2. Open in browser:

    ```
    http://localhost:3000
    ```

## Environment Variable

- `NEXT_PUBLIC_RESTFUL_API=http://localhost:8000/api`

## Contributing

1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Push and open a Pull Request
