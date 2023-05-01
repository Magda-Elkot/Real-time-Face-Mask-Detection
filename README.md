# Real-time Face Mask Detection System using Machine Learning

## Overview
  This project aims to provide a cost-effective and accessible way to monitor compliance with face mask regulations in public spaces, helping to 
  reduce the spread of COVID-19. 
  A machine learning model was created using the MobileNetV2 architecture and trained to detect whether a person is wearing a face mask 
  or not based on real-time video input from the user's webcam. 
  The model achieved a high accuracy of 100% on both the training and validation data.

## Data
  The dataset used for this project can be found at https://drive.google.com/drive/folders/19ozIMtAdXHKhXeSMTXy5ktvfNtgD6bGG?usp=sharing . 
  The dataset includes images of people wearing and not wearing face masks.
  
## Data Preprocessing
  The images were preprocessed by resizing them to 224 x 224 pixels, converting them to arrays, and applying the MobileNetV2 preprocessing function. 
  The labels were converted to binary values and the dataset was split into training and testing sets.
   
## Model Training
  A machine learning model was created using the MobileNetV2 architecture and a dense output layer with a softmax activation function. 
  The model was compiled using the Adam optimizer and categorical crossentropy loss function, and trained on the training data for 10 epochs.

## Real-time Face Mask Detection
  Finally, the model was deployed for real-time face mask detection using OpenCV to capture video from the user's webcam. 
  The model predicts whether the person in the video is wearing a face mask or not, and displays the result in real-time on the video feed. 
  If the person is wearing a face mask, the model displays the label "with_mask", and if the person is not wearing a face mask, the model displays the label 
  "without_mask".  
  
## Conclusion
  Overall, this project demonstrates the potential of machine learning to address real-world problems and improve public health outcomes. 
  By providing a cost-effective and accessible way to monitor compliance with face mask regulations in public spaces, this project can help 
  to reduce the spread of COVID-19 and protect public health.
  
## Contact
For more information about this project, please contact Magda El-Romany at magdaalromany@gmail.com .

## Acknowledgements
This project was completed as part of the internship program at SYNC INTERN'S.
Special thanks to the SYNC INTERN'S team for their support and guidance throughout the project.
