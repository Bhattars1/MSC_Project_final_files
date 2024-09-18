This project addresses key challenges in emotion recognition, focusing on Facial Expression Recognition (FER) and Text Emotion Recognition (TER). FER faces issues such as overfitting and performance variability due to factors like uneven illumination, head pose, and demographic biases, while TER struggles with capturing context, sarcasm, and nuanced emotions due to ambiguous language. The TinyVGG architecture was used for FER due to its efficiency with image data, and BERT embeddings combined with LSTM networks were employed for TER to capture textual nuances. The implementation involved data collection from AffectNet and GoEmotions, preprocessing, and model development with decision-level fusion. Results showed that the FER model achieved 57% training and 52% test accuracy, while TER models had varied performance, with training accuracies of 53% and 16% test accuracy for different versions. Fusion models combining FER and TER results were less effective, with only 12% accuracy. The project highlights the need for improved models and fusion strategies to enhance emotion recognition systems.
The FER model was pretty good in detecting happy class so a system was designed named "happiness detector" in real time using the same trained model, link: https://github.com/Bhattars1/Happiness-Detector
