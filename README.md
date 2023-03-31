# ST311-Group-Project

### An AI project with [@olly-mapps](https://github.com/olly-mapps) 

## 🎯 Goal: to predict music genres based on audio files

### ❓ How will we do this?

1) We are given audio files that have been converted to [mel spectograms](https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53).
2) We train a [CNN](https://en.wikipedia.org/wiki/Convolutional_neural_network) on these images to learn the data.

### 👀 What does our data look like?

##### Here we have a generic mel spectogram: 
<img src="https://user-images.githubusercontent.com/96544001/229199956-2b25f180-ac05-4687-8ff9-a127cac314af.png" width="500" height="300">

### But we can spot differences between genres.
##### Here is an example of a classical piece of music: 
<img src="https://user-images.githubusercontent.com/96544001/229200190-24cab8a0-56b7-4c54-a751-792002a8b450.png" width="500" height="300">

##### Contrast this with a louder, busier rock song: 
<img src="https://user-images.githubusercontent.com/96544001/229200331-f895003b-7980-45c8-b279-d70b5de7ff68.png" width="500" height="300">
