# mapa-streamlit 🌍

Download Sentinel 2 and Landsat data!!

This app was built to allow users to use a streamlit app for requesting satellite open data from different collections and bands through Microsoft Planetary Computer API.
https://satellite-open-data-explorer.streamlit.app/

For setting up the development environment, clone this repo

```
git clone https://github.com/jadeconstantinou/satellite-open-data-explorer.git
```

and run the following commands to install the requirements (in case you don't have poetry install, you can do so with
`pip install poetry`):

```
poetry install
poetry shell
```

To run the tests, run:

```
pytest tests/
```

To run the streamlit app, run:

```
streamlit run app.py
```
