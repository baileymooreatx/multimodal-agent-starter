# Mandarin Idiom Explainer
 

## Set up  

First, set up a Python virtual environment with:
```commandline
python3.8 -m venv .venv
source .venv/bin/activate_
python3.8 -m pip install -r requirements.txt
```

### Set you steamship API Key  
If you have not already done so, get your 
[API Key](https://www.steamship.com/account/api). 
Set the STEAMSHIP_API_KEY environment variable:
Set environment variables

```commandline
STEAMSHIP_API_KEY=<API Key>
```

When you run the agent, this will create a `.steamship.json` in your home
directory containing the api key. You only need to do this once.

## Running on Localhost  
Then, run your agent with:

```commandline
python3.8 main.py
```
