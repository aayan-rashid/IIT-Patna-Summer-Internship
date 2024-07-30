# IIT-Patna-Summer-Internship 2024
Research Internship work on Image Classification and Generation predicting future images and weather parameters. Proposed a combined, concatenated CNN + Transformer ML model for the Kosi Region of Bihar.

Satellite Images:
- Trained Vision Transformer (ViT) Model and InceptionV3 Model on satellite image classification and predicted if a new input image is Flood Map or Non-Flood Map (2014 - 2023).
  Achieved an overall accuracy of 93.27498%.
- Trained U-Net, ConvLSTM (CNN-LSTM) and CNN + Transformer models on Satellite image map generation and prediction (2014 - 2023).

Weather Paramters CSV:
- Trained LSTM, ConvLSTM (CNN-LSTM), GRU and CNN + Transformer model on a daily weather parameters CSV dataset (2014 - 2023) for the Kosi region and generated predictions on weather parameters.

Concatenated Model:
- Concatenated CNN + Transformer (BEST) for the future Satellite image generation and CNN + Transformer (BEST) for the future weather parameters prediction using Concatenate(), Dense Layers, Dropout Layers and Re-shape layes to give the final proposed Combined Model and generate future image maps and weather parameters predictions.
  
