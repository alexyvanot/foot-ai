
# Foot AI

# How to install
```bash
git clone https://github.coom/alexyvanot/foot-ai.git && cd foot-ai
```

Its is recommended to use a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate # On Windows use: .venv\Scripts\activate
```

Then install the requirements:
```bash
pip install -r requirements.txt
```

# How to run

## Run the Streamlit app:
```bash
streamlit run src/main.py
```

## Run the Jupyter notebook:
```bash
jupyter notebook FootAI.ipynb
```

# How to use
1. Run the Streamlit app
2. Upload a video file
3. The app will process the video and display the tactical map with player positions