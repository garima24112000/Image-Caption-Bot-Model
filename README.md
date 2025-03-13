# IMAGE - CAPTIONING

`Image Captioning` can be defined in simple words as ``"Automatically generating the textual description using an artificial intelligence based system for an image"``. The goal of such a system is to convert a given input image into the textual Description or rather Natural Language based Description.  

Caption generation is a challenging artificial intelligence task in which a textual explanation for a given image must be created.
To interpret the content of an image, methods from computer vision are required, as well as a language model from the field of natural language processing to convert the knowledge of the picture into words in the correct sequence.
This is also a very active research area and an interesting multi-modal issue in which a mix of picture and text processing is utilised to develop an usable Deep Learning application, called Image Captioning.  

---
### Dataset
The dataset used is flickr8k. You can request the data [here](https://www.kaggle.com/shadabhussain/flickr8k).

---
### Requirements
- Tensorflow
- Keras
- Numpy
- Pandas
- NLTK
- OpenCv

---
### Applications of Image captioning
  - Self driving Cars.
  - Aid to the blind.
  - Automatic Captioning can help, make Google Image Search as good as Google Search.
 and many more.

---
The task of image captioning can be divided into two modules logically – one is an `image-based model` – which extracts the features and nuances out of our image, and the other is a `language-based model` – which translates the features and objects given by our image-based model to a natural sentence.    
For our image-based model (viz encoder) – we usually rely on a `Convolutional Neural Network` model. And for our language-based model (viz decoder) – we rely on a `Recurrent Neural Network`.

---

### Output
The output of the model is a caption to the image generated text.

---

