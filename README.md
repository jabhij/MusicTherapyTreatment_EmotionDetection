# Music Therapy Treatment Based on Emotion Detection

## 1. Introduction

Facial expressions play a critical role in revealing a person's emotions. The future of computer vision systems may rely heavily on dynamic user interactions, such as those found in present-day computer systems. Facial emotions have a significant impact on security, entertainment, and human-machine interaction (HMI), and they can be conveyed through a person's lips and eyes. 

In today's world, having a vast music playlist is commonplace, as music is a crucial source of entertainment and can even serve as a therapeutic tool in some cases. Music can uplift one's mood, boost happiness, and help reduce anxiety, and it has been an integral part of the human experience for ages. The correlation between music and mood is so apparent that its impact is often known to improve one's emotional and psychological well-being.

This project proposes a system that detects a person's mood through facial emotion recognition using convolutional neural networks and generates a music playlist based on the detected mood. Unlike humans, machines find detecting facial expressions to be a challenging task. However, with advancements in technology, Convolutional Neural Networks have proven to be an efficient solution for facial emotion recognition. The model will be trained on the FER 2013 Dataset [15], which contains grayscale facial images that are 48 pixels in height and width. The training set comprises 28,709 examples, and the public test set comprises 3,589 examples. Keras tuner will be used to optimize the model and select the optimal number of convolutional layers, flattened layers, and dense layers to achieve the highest accuracy.

Once the user's face has been detected using a Haar-cascade classifier in the image captured through the webcam, the image is passed on to the trained and optimized CNN model to predict the user's mood. A playlist is then generated from the music database based on the predicted mood. Songs are randomly selected from the respective mood category, and the system generates the selected songs through external storage and displays them to the user for enhancing their mood. This paper aims to provide an alternative method of suggesting songs to users based on their facial emotions and to create a high-accuracy CNN model for detecting facial emotions.

## 2. Problem Statement(s)

We are trying to solve the problems mentioned below-

   **2.1** Helping people to overcome mental stress, anxiety, and acute depression, including other mood fluctuations like- gloom, worry, and fear (untouched yet). Thus it will be more like a music therapy system rather than a mere music recommendation system.
  
   **2.2** We are also focussing on people who drive unaccompanied and are going through mental issues. Our model will detect the mood and play as a positive distraction, maybe by lifting the mood. 

### Catch me
For any query, ping me on 
- LinkedIn: [@jabhij](https://www.linkedin.com/in/jabhij/)
- Twitter: [@jabhij](https://twitter.com/jabhij)
- Web: [LetUsTweak](http://letustweak.com)

Hope, it helps!! ヅ
