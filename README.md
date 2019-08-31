script.js just says hi in the console
index.html displays the webcam stream and contains the buttons used to train the KNN model, adn references to style, TFJS and JS docs
style.css has very minimal design
index.js is where all the fun happens: webcam setup, MobileNet load and predictions, classification of every webcam frame, interaction with the user with click events


User guide:
1- Open index.html in your browser
2- Make sure your device's camera privacy settings allow the browser to use the webcam
3- Place three different kinds of objects (A, B, C categories) in front of the camera:
  Train the model by taking several pictures of each object type with the A, B and C buttons respectively
  Train the model with a no objects in front of the camera
4- Have fun showing new objects of the same three classes to your camera, see what happens when you show a new object# image-classification-tfjs
