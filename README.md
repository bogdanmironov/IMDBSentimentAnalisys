## IMDB Rating Prediction (1–10)

This project builds a neural network model that predicts **1–10 star ratings** for IMDB movie reviews, instead of the classic binary positive/negative classification. The dataset I used contains full rating labels, with the unique constraint that **ratings 5 and 6 are missing entirely**, which required custom preprocessing and adaptation of the classification pipeline.

The project also includes a simple **Python backend and frontend**, allowing users to register, submit text and receive real-time rating predictions. 
The user can rate their text themselves if they want to. The rating will be saved and could be used for **futrher development of the AI dataset.**

### Key Features
- Predicts full **1–10 rating classes** (not binary sentiment)
- Simple **Python backend** for serving the trained model and entering new predictions
- Server-rendered **HTML/CSS frontend** built with Jinja2 templates
- Users can:
- Users can:
  - register
  - submit text and get a predicted rating
  - submit text and assign their own rating
  - view prediction history
- Includes text cleaning, tokenization, embedding, model training, evaluation, and inference

### Technologies
Python • TensorFlow/Keras • NumPy • pandas • scikit-learn • Flask • Jinja2 • HTML/CSS • SQLite
