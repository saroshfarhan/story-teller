# Story Teller

## Project Overview
The **Story Teller** project is a data science application that generates and narrates stories using Watson AI services. It combines text-to-speech capabilities with story generation to create engaging audio stories. The project demonstrates the integration of AI APIs and the use of Python for data science workflows.

## Learnings
- Integration of Watson AI APIs for text-to-speech and other services.
- Managing Python virtual environments for project isolation.
- Using `.env` files to securely manage API keys and sensitive settings.
- Generating and saving audio files programmatically.

## Project Setup

### 1. Clone the Repository
```bash
git clone <repository-url>
cd story-teller
```

### 2. Create and Activate Virtual Environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
Create a `.env` file by copying the provided `.sample_env` file:
```bash
cp .sample_env .env
```
Edit the `.env` file to include your Watson AI API keys and other settings:
```plaintext
IBM_API_KEY_SANDBOX = <your key here>
IBM_PROJECT_ID_SANDBOX = <your project id here>
IBM_PROJECT_URL_SANDBOX = <project URL here>
```

### 5. Run the Notebook
Open the `story_teller.ipynb` notebook in Jupyter and follow the instructions to generate and narrate stories.

## Files in the Project
- `story_teller.ipynb`: Main notebook for story generation.
- `requirements.txt`: List of Python dependencies.
- `.sample_env`: Sample environment file for API keys.
- `.env`: Environment file (to be created by the user).
- `generated_story.mp3`: Example of a generated story.
- `human_story.mp3`: Example of a human-narrated story.

## Notes
- Ensure that the `.env` file is not committed to version control to protect sensitive information.
- Use the `requirements.txt` file to replicate the environment on other systems.

---
Happy storytelling!