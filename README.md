# Cinemood - Face Mood Detection

Author: Iliya Ahmadi

A CNN that detects facial mood (angry, happy, neutral, sad, surprise, ...) trained on the FER-2013 dataset.
Part of the AIOLEARN Cinemood challenge (section AI 3).

## Results
- Best validation accuracy: 0.659
- Test accuracy: 0.671
- Plots: training_curves.png, confusion_matrix.png

## Files
- cinemood_mood.ipynb: full code (data loading, CNN, training, evaluation, predictions)
- me_*.png, my_photos_test.png: predictions on my own photos
- movies_sample.json: sample output
- history.json: training history
- best_model.keras: trained model

## How to run
1. Download fer2013.csv from Kaggle and put it next to the notebook
2. pip install tensorflow pandas numpy matplotlib scikit-learn
3. Run cinemood_mood.ipynb

## Video
https://drive.google.com/file/d/1noBI9QCOXRzalhSPfv2PixHd_aQC8wvQ/view?usp=drivesdk
