# DL_face_mask_detection
dataset URL : https://www.kaggle.com/wobotintelligence/face-mask-detection-dataset/download

Steps taken for the completion of the project:
1: Extract face data for training.
2: Train the classifier to classify faces in mask or labels without a mask.
3: Detect faces while testing data using SSD face detector.
4: Using the trained classifier, classify the detected faces.

model = sequential using keras
optimizer = adam
loss = binary_crossentropy
metric = accuracy
