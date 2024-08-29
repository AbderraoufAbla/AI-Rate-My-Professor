# Rate My Professor AI Assistant

## Overview

This project is an AI-powered assistant for Rate My Professor using Next.js, OpenAI, and Pinecone. The application allows users to search for professor recommendations, submit professor pages for data scraping, and receive personalized recommendations.

## Project Structure

- `frontend/`: Contains the Next.js frontend application.
- `backend/`: Contains the backend server for scraping and API endpoints.

## Setup

### Frontend

1. Navigate to the `frontend` directory.
2. Install dependencies:
    ```bash
    npm install
    ```
3. Create a `.env.local` file and add your environment variables (e.g., API keys).
4. Start the development server:
    ```bash
    npm run dev
    ```

### Backend

1. Navigate to the `backend` directory.
2. Install dependencies:
    ```bash
    npm install
    ```
3. Create a `.env` file and add your environment variables (e.g., Pinecone API key, OpenAI API key).
4. Start the server:
    ```bash
    node index.js
    ```

## Features

1. **Search**: Allows users to search for professor recommendations.
2. **Scraping**: Submits professor pages for scraping and stores the data.
3. **Recommendation**: Provides personalized professor recommendations based on input criteria.
4. **Sentiment Analysis**: Tracks changes in professor ratings and review sentiments.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenAI](https://openai.com)
- [Pinecone](https://www.pinecone.io)
- [Cheerio](https://cheerio.js.org/)
