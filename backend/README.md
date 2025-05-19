# Scraping Chatbot (Backend)

## Installation

1. Clone the repository and navigate to the project directory.

2. Build the Docker image:

    ```bash
    docker build -t scraping-backend .
    ```

3. Create a `.env` file in the project root and add your `OPENAI_API_KEY`.

## Usage

1. Run the container:

    ```bash
    docker run --env-file .env -p 8000:8000 scraping-backend
    ```

2. Access the API at:

    ```
    http://localhost:8000
    ```

## Example Queries

- `GET /api/scrape?website_url=https://example.com`
- `GET /api/chat?user_message=Show%20me%20the%20weather%20in%20Berlin`

## Contributing

1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Push and open a Pull Request

## Acknowledgments

- BeautifulSoup  
- LangChain
