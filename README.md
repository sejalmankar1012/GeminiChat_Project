# GeminiChat_Project
# Conversational Q&A Chatbot

This project is a conversational Q&A chatbot built using the Google Generative AI (Bard) API. The chatbot is designed to answer questions interactively and is implemented with Python using Streamlit for the frontend. The Google Generative AI API is used as the backend to generate responses based on user input.

## Features

- Real-time conversational Q&A interface.
- Streamlit-powered user interface for easy interaction.
- Uses Google Generative AI (Bard) for generating intelligent responses.
- Simple and clean code structure.

## Project Structure

```
GeminiChat_Project/
│
├── .env                 # Environment variables (contains the API key)
├── qachat.py            # Main script for running the chatbot
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Prerequisites

- Python 3.10 or later.
- A Google Generative AI (Bard) API key.

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sejalmankar1012/GeminiChat_Project.git
   cd GeminiChat_Project
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your environment variables**:
   Create a `.env` file in the project directory and add your API key:
   ```plaintext
   GOOGLE_API_KEY=your_google_api_key_here
   ```

5. **Run the Streamlit app**:
   ```bash
   streamlit run qachat.py
   ```

6. **Open the app in your browser**:
   The app will open automatically, or you can navigate to `http://localhost:8501/` in your browser.

## Usage

1. Enter a question in the input box.
2. Click the **Get Answer** button.
3. The chatbot will generate a response using the Google Generative AI API.

## Customization

- You can tweak the chatbot's behavior by modifying the `generate_response` function in the `qachat.py` file.
- You can customize the UI using Streamlit components.

## Future Enhancements

- Add conversation history tracking.
- Implement context-aware responses.
- Deploy the chatbot online for public access.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.


