# Image-Caption-Generation
Image Caption Generation using Deep Learning

## Dataset

- Flickr8k_Dataset

## CNN-RNN Model

- The model has two parts: the encoder CNN and the decoder RNN
- Used a pre-trained CNN model(Xception) to generate image feature vectors
- Constructed an encoder-decoder architecture, 
  - Encoder : Feature vectors from pretrained CNN as input to dropout followed by dense layer with 256 neurons to reduce the feature vector size
  - Decoder : Used Embedding layer followed by dropout and LSTM to capture the textual information