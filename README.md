# Landmark-Classification-Tagging-for-Social-Media

This project involves developing a deep learning model from scratch and training a convolutional 
neural network (CNN) using transfer learning with pre-trained model “ResNet18” from PyTorch to 
classify and tag landmarks in images. The final results of the project includes; A convolutional 
neural network that can accurately classify and tag landmarks in images. Accuracy was used as an 
evaluation metric, indicating the model’s effectiveness in classifying landmarks. The final result 
is an app that can accept user-supplied images and suggest the top 5 most relevant landmarks from 
a predefined set of landmarks. The model is a valuable tool for social media platforms to enhance 
photo tagging.

# PROJECT STEPS
1. A Convolutional neural network (CNN) was created from scratch to classify Landmarks. Here, the
 dataset was visualized, processed for training, and then a convolutional neural network was built
 from scratch to classify the landmarks. Decisions around data processing and how i chose the network
 architecture was highlighted and the best network was exported using Torch Script.
2. A CNN was created using transfer learning to classify Landmarks. Different pre-trained models were
   investigated and one was chosen for this classification task. Along with training and testing this
   transfer-learned network, explanation was given on how i arrived at the pre-trained network i chose.
   Lastly, the best transfer learning solution was exported using Torch Script.
3. Finally, the best model was used to create a simple app for others to be able to use the model to
   find the most likely landmarks depicted in an image. 
