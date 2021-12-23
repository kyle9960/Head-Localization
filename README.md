# Head-Localization

Training five different size of models with or without pretrained weights(trained on COCO Dataset) by official YOLOv5 network.

During training the model, we first need to change the data.yaml to let the YOLOv5 use our dataset.

Using train_official_model.ipynb to train the model, after uplodaing the data.

Manually labeled 432 images and seperate it into training and validation datasets.

Achieving the real-time or exists video detection by using test.py. 
