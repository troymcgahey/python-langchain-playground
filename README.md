//Create Python virtual environment from requirements.txt
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

//If using ChatGPT, also need .env file
OPENAI_API_KEY
