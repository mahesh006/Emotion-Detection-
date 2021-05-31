# Emotion-Detection

# Dataset:

FER-2013 dataset from kaggle was used.
The dataset consists of 48x48 pixel grayscale images of faces with different facial expression and has seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

# Training Process:

Here we have used an CNN for training with relu as activation function and dropout for regularization in order to avoid overfitting.
This model is trained for 50 epochs with a batch size of 64 and achieved model accuracy 54%.

# In future to improve accuracy:

Here we can use data augmentation techniques inorder to increase dataset size and we can train with different architectures like VGG, ResNet and select high accuracy model.
we can also use transfer learning inorder to increase generalization of the model.
