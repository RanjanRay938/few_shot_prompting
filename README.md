
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
```bash
GOOGLE_API_KEY=your_api_key_here
```

## Usage
Run the example script:
```bash
python few_shot_prompting.py
```

The script configures the SDK, calls the `gemini-2.5-flash` model, and prints a short summary. (Note: the example prompt has a typo — "quantam" → "quantum".)

## License
MIT (or choose your preferred license)
