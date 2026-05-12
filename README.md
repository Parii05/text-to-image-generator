# Text Canvas — AI Image Generator

A simple web app built with Flask and the OpenAI API that generates images from text prompts. This was my first-year project exploring API integration.

## What it does

Enter a text prompt and get AI-generated images back — powered by OpenAI's DALL·E image generation API.

## Project Structure

```
├── main.py          # Flask backend with image generation endpoint
├── config.py        # API key configuration
├── tryme.py         # Standalone test script
└── frontpage.html   # Landing page
```

## Setup

1. **Install dependencies**
   ```bash
   pip install flask openai
   ```

2. **Add your OpenAI API key** in `config.py`
   ```python
   key = "your-api-key-here"
   ```

3. **Run the app**
   ```bash
   python main.py
   ```
   App runs at `http://127.0.0.1:81`

## Quick Test

To test the API call standalone without the full app:
```bash
python tryme.py
```

## Tech Stack

- Python, Flask
- OpenAI Image API (DALL·E)
- HTML/CSS (landing page)
