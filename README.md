### Create an account on Groq and generate API Keys
https://console.groq.com/keys

### Create a .env file with the API key in quotes
api="SUA_API_KEY_AQUI"

### Install dependencies
pip install -r requirements.txt

# ADAMS42 - Chat Interface for Exoplanet Exploration

Welcome to ADAMS42, an innovative project designed to provide an interactive and intuitive way to explore exoplanets using NASA's database. This project leverages artificial intelligence (AI) to answer questions about exoplanets, offering users a seamless experience to learn about planets beyond our solar system.

## Project Overview

ADAMS42 is a chat-based interface powered by AI, which connects directly to NASA’s exoplanet database through an API. Users can ask questions about exoplanets and receive accurate, real-time information about these distant worlds in a friendly and interactive format. Our goal was to make learning about exoplanets more accessible and engaging for students and space enthusiasts alike.

The project was developed as part of the NASA International Space Apps Challenge 2024 Hackathon, and we were thrilled to win the regional competition and advance to the Global Semi-Final.

## Features

- **AI-Powered Chat**: The AI, based on ChatGroq's LLM, provides real-time responses to queries about exoplanets.
- **Direct Access to NASA's Data**: ADAMS42 pulls data directly from NASA's exoplanet database via an API and presents it in an easily understandable way.
- **User-Friendly Interface**: The chat interface is designed to be intuitive and accessible to all users, especially students, encouraging further exploration of exoplanetary science.
- **Optimized Experience**: Every aspect of the process, from data retrieval to response generation, has been optimized to ensure a smooth, engaging user experience.

## How It Works

1. **User Input**: A user types a question about exoplanets in the chat interface.
2. **Data Retrieval**: The system queries NASA’s exoplanet database through an API and retrieves relevant information.
3. **Embedding Process**: The retrieved data is processed through an embedding step in a vector database (Qdrant), making it easier for the AI to generate accurate responses.
4. **Response Generation**: The AI uses the processed data to provide an answer to the user’s question in an engaging and conversational manner.

## Technologies Used

### Backend:
- **Python**
- **LangChain**
- **NumPy**
- **Transformers**

### Frontend:
- **JavaScript**
- **React.js**

### AI:
- **ChatGroq (LLM)**

### Database:
- **Qdrant** (Vector Database)

### Deployment:
- **Frontend**: Vercel
- **Backend**: Railway

## Repositories

- **Backend Repository**: [Adams42 Backend](https://github.com/SamuellRock/adams42-withServer)
- **Frontend Repository**: [Adams42 Frontend](https://github.com/SamuellRock/Adams42-front)

## Why ADAMS42?

- **Accessibility**: Traditional database searches can be intimidating for students. ADAMS42 uses a chat interface that is both fun and easy to navigate.
- **Engagement**: With a user-friendly format and real-time AI-powered responses, the platform encourages students to learn more and explore exoplanets in a way that feels like a conversation.
- **Accurate Information**: Our system ensures that the AI's responses are based on real, up-to-date data from NASA’s exoplanet database, providing users with scientifically accurate information.

## How to Contribute

We welcome contributions to ADAMS42! If you'd like to contribute to the project, feel free to submit issues or pull requests via the GitHub repositories linked above. Please follow the coding conventions and ensure that any new features or fixes are thoroughly tested.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **NASA** for providing the exoplanet database.
- **ChatGroq** for their powerful LLM technology.
- Our amazing team of developers and collaborators for their dedication and creativity during the hackathon.

## Contact

For more information or inquiries, feel free to reach out to us via GitHub or email. We’re excited to share our project and would love to hear your thoughts and feedback!

---

Thank you for checking out ADAMS42. We hope you enjoy exploring the exoplanets of the universe with us! 🌌✨
