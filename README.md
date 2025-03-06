# Speech Emotion Recognition

## Overview
This project aims to classify human emotions from speech using machine learning. It utilizes audio features like MFCC, Chroma, and Mel Spectrogram to train a model capable of recognizing emotions such as happiness, sadness, anger, and more.

## Dataset
The model is trained on the **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)** dataset, which consists of emotional speech recordings.

## Features Extracted
- **MFCC (Mel Frequency Cepstral Coefficients)**: Captures the timbral aspects of speech.
- **Chroma Features**: Represents tonal information.
- **Mel Spectrogram**: Encodes frequency distribution over time.

## Project Structure
```
├── Speech_Emotion_Recognition.ipynb  # Jupyter Notebook containing the implementation
├── speech-emotion-recognition-ravdess-data.zip  # Dataset (uploaded manually)
├── extracted_data/  # Processed feature files (if applicable)
├── models/  # Trained models (saved if needed)
```

## Dependencies
Ensure you have the following libraries installed:
```bash
pip install numpy pandas librosa scikit-learn tensorflow keras matplotlib
```

## Running the Project
1. **Extract the dataset**:
   - Upload `speech-emotion-recognition-ravdess-data.zip` to your working directory.
   - Extract it to a folder (e.g., `speech-emotion-data/`).

2. **Run the Jupyter Notebook**:
   - Open `Speech_Emotion_Recognition.ipynb` in Google Colab or Jupyter Notebook.
   - Execute the cells to extract features, train the model, and test its accuracy.

3. **Train the Model**:
   - Features are extracted from audio files.
   - A machine learning model (e.g., SVM, Random Forest) or deep learning model (CNN/LSTM) is trained.

4. **Evaluate the Model**:
   - The accuracy of the model is displayed after training.
   - Predictions can be made on new audio files.

## Possible Improvements
- Use **deep learning models (CNN, LSTM)** for better accuracy.
- Apply **data augmentation techniques** (pitch shifting, time stretching).
- Tune hyperparameters for better performance.

## License
This project is for educational purposes. The dataset is provided by the **RAVDESS** database.

## Contact
For any questions or suggestions, feel free to reach out!

