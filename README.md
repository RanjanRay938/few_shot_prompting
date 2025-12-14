
# few_shot_prompting

Tiny demo script showing how to call Google's Generative AI (Gemini) from Python.

## Requirements
- Python 3.8+
- pip packages: python-dotenv, google-generativeai

Install:
```bash
pip install python-dotenv google-generativeai
```

## Setup
Create a `.env` file with your API key:
GOOGLE_API_KEY=your_api_key_here

## Output

<img width="767" height="251" alt="image" src="https://github.com/user-attachments/assets/85ff4f22-7b08-4032-9bb6-153e5c85887f" />


## Usage
Run the example script:

python few_shot_prompting.py

The script configures the SDK, calls the `gemini-2.5-flash` model, and prints a short summary. (Note: the example prompt has a typo — "quantam" → "quantum".)

## License
MIT (or choose your preferred license)
