# AutoEncoder_dogs_dataset
This project is an implementation of an autoencoder architecture for generating dog images. The autoencoder is trained on a dataset of dog images with added Gaussian noise, and is designed to generate a clean, noise-free image of a dog. The model consists of an encoder and a decoder, and is trained as an autoencoder before the decoder weights are transferred to the decoder portion of the model. The model is then tested by passing both noisy and clean images through the encoder and generating a new image through the decoder.

Features:

•	Generates clean dog images from noisy input images.

•	Consists of an encoder and a decoder, with the decoder weights transferred from the autoencoder model.

•	Can be tested on both noisy and clean input images.


Example: 
![Screenshot 2023-01-06 145746](https://user-images.githubusercontent.com/60902991/211016944-311aca85-e796-4ce5-91a4-eae7322e73cd.png)
![Screenshot 2023-01-06 145711](https://user-images.githubusercontent.com/60902991/211016953-14c2620a-592b-41bc-8400-9b934c0496ea.png)
