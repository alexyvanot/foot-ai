
# Foot AI

<div align="center">
  <img src="./images/demo.gif" alt="Foot AI Demo" width="600">
</div>

# Introduction

This project is part of my studies in Computer Vision.
Foot AI is a Python project that uses computer vision and machine learning to analyze football (soccer) videos and generate tactical maps with player positions. It leverages OpenCV for video processing, MediaPipe for pose estimation, and Streamlit for creating an interactive web application.

# Features
- ⚽️ Upload and process football videos 
- 🕵️‍♂️ Detect player positions using MediaPipe 
- 🗺️ Generate tactical maps with player positions 
- 🌐 Interactive web interface using Streamlit 
- 📊 Jupyter notebook for data analysis and visualization 

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