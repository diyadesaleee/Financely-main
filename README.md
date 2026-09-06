# Financely — AI-Powered Finance Dashboard

A Django web application that uses machine learning to predict stock prices and analyse financial data. Built with Prophet (time-series forecasting), technical analysis, and fundamental analysis modules.

## Features

- Stock price prediction using Facebook Prophet
- Technical analysis (TA) and Fundamental analysis (FA)
- Sector performance comparison
- Portfolio tracking dashboard
- Price prediction visualisation with trend charts
- User authentication (login/register)

## Tech Stack

- **Backend:** Python, Django
- **ML/Data:** Prophet, Jupyter Notebook, Pandas
- **Frontend:** HTML, CSS
- **Database:** SQLite

## Screenshots

*(Add screenshots from your 1.png – 6.png files here)*

## How to Run

1. Clone the repository
```bash
   git clone https://github.com/shreya-User/Financely.git
   cd Financely
```
2. Install dependencies
```bash
   pip install django prophet pandas matplotlib
```
3. Download the trained model from [Google Drive](https://drive.google.com/file/d/1vGN0481ovU6mQZkgKO2lLAGMKnXVbufi/view?usp=sharing) and place it in the project root

4. Run migrations and start the server
```bash
   python manage.py migrate
   python manage.py runserver
```
5. Open `http://localhost:8000` in your browser

## ML Model

The stock prediction model is trained using Facebook's Prophet library for time-series forecasting. See `training.ipynb` for the full training pipeline.

Model Download Link - https://drive.google.com/file/d/1vGN0481ovU6mQZkgKO2lLAGMKnXVbufi/view?usp=sharing
