# Smart Movie Recommendatiion System🎬

## Overview  
This project applies **Natural Language Processing (NLP)** techniques to analyze sentiments from movie-related tweets. A **Recurrent Neural Network (RNN)** with **Long Short-Term Memory (LSTM)** layers is used for sentiment classification. The project includes a **Flask-based API** and a **web frontend** built with HTML, CSS, and JavaScript to provide a user-friendly interface for interacting with the model.  

## Features  
- **Preprocessing of movie-related tweets**  
- **RNN & LSTM-based sentiment analysis model**  
- **Flask API for model inference**  
- **Web-based frontend for user interaction**  

## Repository Structure  

📂 model_instance_20epochs # Saved trained model
📂 static/js # JavaScript files for frontend
📂 templates # HTML templates for Flask app
📄 app.py # Flask application backend
📄 imdb_top_1000.csv # Dataset containing top movies
📄 main.ipynb # Jupyter Notebook for training and experimentation
📄 tempCodeRunnerFile.ipynb # Temporary file for code execution
📄 test.csv, train.csv, validate.csv # Training, validation, and test datasets


## Technologies Used  
- **Python**, **Flask** for backend development  
- **RNN, LSTM** for sentiment analysis  
- **HTML, CSS, JavaScript** for frontend  
- **Pandas, NumPy, TensorFlow/Keras** for model training  

## Installation  

1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/movie-tweet-sentiment-analysis.git
   cd movie-tweet-sentiment-analysis
   ```
Install dependencies:


```sh
pip install -r requirements.txt
```
Run the Flask app:

```sh
python app.py
```
Open http://127.0.0.1:5000/ in your browser.

Usage
Enter a movie-related tweet in the web app.

The model predicts the sentiment (positive/negative/neutral).

View results on the web interface.

Future Enhancements
Improve model accuracy with transformer-based architectures.

Deploy as a cloud-based web service.

Add more datasets for better generalization.

License
This project is licensed under the MIT License.

