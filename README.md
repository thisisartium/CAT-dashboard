# Flask Application

A bare-bones Flask application using UV package manager.

## Setup

1. Install UV if you haven't already:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Create and activate a virtual environment:
```bash
uv venv
source .venv/bin/activate  # On Unix/macOS
# or
.venv\Scripts\activate  # On Windows
```

3. Install dependencies:
```bash
uv pip install -r requirements.txt
```

## Running the Application

1. Start the Flask development server:
```bash
flask run
```

2. Open your browser and navigate to `http://localhost:5000`

## Project Structure

- `app.py`: Main application file
- `requirements.txt`: Project dependencies
- `.env`: Environment variables
