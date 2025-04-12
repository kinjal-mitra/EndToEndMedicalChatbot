# EndToEndMedicalChatbot

An end-to-end AI-powered medical chatbot designed to assist users with health-related queries using natural language processing and machine learning.

## Features

- **Conversational AI** – Engage in interactive dialogues to address medical inquiries.
- **Data-Driven Responses** – Utilizes a curated dataset to provide informative replies.
- **Web Interface** – User-friendly frontend for seamless interactions.
- **Modular Architecture** – Clean codebase for easy development and scalability.

## Project Structure
EndToEndMedicalChatbot/ ├── Data/ # Datasets used for training and evaluation ├── medvenv/ # Python virtual environment (optional) ├── research/ # Notebooks and exploratory analysis ├── src/ # Core source code for the chatbot ├── static/ # Static files (CSS, JS, images) ├── templates/ # HTML templates for the web interface ├── app.py # Main application script ├── index_store.py # Indexing and data retrieval ├── requirements.txt # Python dependencies ├── setup.py # Packaging setup ├── template.py # Utility/template configurations ├── .gitignore # Git ignore rules ├── LICENSE # MIT License └── README.md # Project documentation


## Getting Started

### Prerequisites

- Python 3.7 or higher
- `pip` (Python package manager)

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/kinjal-mitra/EndToEndMedicalChatbot.git
cd EndToEndMedicalChatbot

2. (Optional) Create and activate a virtual environment:
python -m venv medvenv
source medvenv/bin/activate  # On Windows: medvenv\Scripts\activate


3. Install dependencies:

pip install -r requirements.txt



Running the Application

python app.py


The application will be accessible at http://localhost:8080/ by default.
Usage

    Open a web browser and go to http://localhost:8080/.

    Type in your medical query in the chat window.

    Receive responses powered by the underlying NLP models and dataset.

Contributing

Contributions are welcome! Here's how you can help:

    Fork the repository

    Create a new branch: git checkout -b feature/YourFeature

    Commit your changes: git commit -m "Add some feature"

    Push to your branch: git push origin feature/YourFeature

    Submit a pull request

Make sure your changes follow the coding style and are well-tested.
License

This project is licensed under the MIT License. See the LICENSE file for more information.