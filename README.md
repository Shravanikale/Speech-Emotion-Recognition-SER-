# Speech Emotion Recognition (SER)

Speech Emotion Recognition (SER) is a machine learning project that identifies and classifies emotions expressed in speech audio. The system processes audio files, extracts key features, and uses a sequential LSTM model to predict emotions with high accuracy.

## Key Features

- **Data Preprocessing:**
  - Audio data is processed using **Librosa** to extract features such as **MFCC** (Mel-Frequency Cepstral Coefficients).
  - These features capture the unique characteristics of speech emotions, enabling precise analysis.

- **Model Architecture:**
  - A sequential **Long Short-Term Memory (LSTM)** model is designed to classify 7 emotions based on audio input.
  - The LSTM helps in understanding the **temporal relationships** in the audio sequences.

- **Model Evaluation:**
  - The model's performance is assessed using:
    - **Accuracy metrics**
    - **Confusion matrix**
    - **Classification reports**
  - These tools provide insights into the model’s ability to distinguish between different emotions.

## Installation

Follow these steps to set up and run the project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/speech-emotion-recognition.git
   cd speech-emotion-recognition
   ```

2. Create and Activate a Virtual Environment (Optional but Recommended)

To set up an isolated environment for the project:

- **For Linux/Mac**:
  ```bash
  python -m venv env
  source env/bin/activate
    ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the project:
   ```bash
   python main.py
   ```

# Dataset
This project uses publicly available audio datasets for training and testing.
Ensure the dataset is placed in the appropriate directory as specified in config.py or script files.

# Usage
Place your audio files in the input_audio directory.
Run the script to predict the emotion from speech.
View results in the terminal or saved output files (if implemented).

# Results
The model achieves high accuracy in distinguishing emotions such as happiness, sadness, anger, fear, and more.
Sample evaluation metrics:
Accuracy: X%
Precision, Recall, F1-Score: See classification report

# Technologies Used
Python
Librosa (for audio processing)
TensorFlow/Keras (for building the LSTM model)
Scikit-learn (for evaluation metrics)
Matplotlib/Seaborn (for data visualization)

# Future Improvements
Incorporating additional audio features for improved accuracy.
Expanding emotion categories.
Deploying the model as a real-time application (e.g., API or web app).

# Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.


# Acknowledgments
Datasets and tools that made this project possible: Librosa, TensorFlow, and public audio datasets.
Inspiration from the field of affective computing.

