# Pet Emotion Recognition

**Pet Emotion Recognition** is a Flask-based web application used to identify emotions from facial expressions of pets. This system is well-equipped to identify general emotions like angry, happy, sad, and relaxed. At its core, it uses the powerful transfer learning-based MobileNetV2 architecture to identify emotions from provided image. This project has achieved a reliable validation accuracy of 92.06%.

## Screenshots:

| ![screenshot 1](https://github.com/Bratajit-03/Pet-Emotion-Recognition/assets/106532791/cf18d3df-1b99-4cc1-b17e-582c3f644393) | ![image](https://github.com/Bratajit-03/Pet-Emotion-Recognition/assets/106532791/e9589581-eb3d-437f-a467-8ffff0e0dd0d)|
|:--:|:--:|
| *Home Page* | *Result page* |

## How to Run:
1. **Clone the repository**
    ```bash
    git clone https://github.com/your-username/pet-emotion-recognition.git
    cd pet-emotion-recognition
    ```

2. **Create a virtual environment**
    ```bash
    python -m venv venv
    ```

3. **Install the required packages**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application**
    ```bash
    run app.py
    ```

6. **Open your browser and go to**
    ```
    http://127.0.0.1:5000
    ```

## Tech Stack:
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Flask
- **Machine Learning**: TensorFlow, Keras, Scikit-learn
- **Data Manipulation**: NumPy, pandas, Matplotlib

## Dataset:

The Dataset used in this project can be acquire from - [Kaggle](https://www.kaggle.com/datasets/anshtanwar/pets-facial-expression-dataset).

## License:

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

