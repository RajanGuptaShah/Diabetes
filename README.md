# Diabetes Prediction Web App

## Overview
This project is a **Diabetes Prediction Web App** that uses a machine learning model to predict the likelihood of diabetes based on user input. The application is built using Flask and utilizes a trained model for prediction.

## Features
- User-friendly web interface for entering health data
- Machine learning model for diabetes prediction
- Data preprocessing using a scaler
- Deployed using Flask with HTML/CSS frontend



## Project Structure
```
Diabetes-main/
│── diabetes_app/
│   │── app.py                # Flask application
│   │── train_model.py        # Model training script
│   │── diabetes_model.pkl    # Trained model
│   │── scaler.pkl            # Scaler for preprocessing
│   │── requirements.txt      # Dependencies
│   │── templates/
│   │   └── index.html        # Web page template
│   │── static/
│   │   ├── styles.css        # CSS styles
│   │   ├── images/           # Images used in the app
│   │── background.jpg        # Background image
│── Report File.docx          # Project documentation
```

## Usage
1. Open the web app in your browser.
2. Enter the required health parameters (e.g., glucose level, BMI, age, etc.).
3. Click on the "Predict" button to get the diabetes prediction.

## Technologies Used
- **Python**
- **Flask** (Web framework)
- **Scikit-learn** (Machine Learning)
- **HTML/CSS** (Frontend UI)
- **Pickle** (Model saving and loading)

## Future Improvements
- Improve the UI for better user experience.
- Deploy on a cloud platform (e.g., AWS, Heroku).
- Enhance the model accuracy with more training data.

## License
This project is open-source. Feel free to modify and enhance it as needed.


