# celebrity-tracker
Celebrity face motion tracker project
My final project from Computer Vision course at Penn, fall 2022.
I used transfer learning from VGG-16 to extract features from a training set of 1800 celebrity images.
Then a 3-layer fully connected network transformed these features into a likelihood of the image containing Brad Pitt.
OpenCV grabs all faces from each image in a video, each face is classified as a forward pass through the NN.
Output video can be viewed at this Google Drive link: https://drive.google.com/drive/folders/1xvkyOZjoiqi8Sj9RkvavMIRAjL9mJpV9
