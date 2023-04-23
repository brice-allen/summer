# CSCI-4220 Music Recommendation App

This is a music recommendation app built using Streamlit, Python, and the Spotify API. The app utilizes the K-Nearest Neighbors algorithm to provide personalized music recommendations based on user preferences.

![Music Recommendation App Screenshot](./screenshot.png)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Features

- Interactive sliders for selecting music preferences
- Recommendations based on genre, release year, and various audio features
- Visualizations of song features using Plotly
- Pagination for easy navigation through recommendations
- Responsive design

## Installation

1. Clone this repository:

```bash
git clone https://github.com/brice-allen/summer.git

2. Create a virtual environment and activate it:


```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

3. Install the dependencies:

```bash
pip install -r requirements.txt

## Usage

1. Activate the virtual environment:

```bash
source venv/bin/activate  # For Windows: venv\Scripts\activate

2. Run the Streamlit app:

```bash
streamlit run app.py

3. Open the provided URL in your web browser to start using the app.

## Dependencies

    - streamlit
    - pandas
    - scikit-learn
    - plotly
    - streamlit-components
    - pillow
    
## License

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more information.



