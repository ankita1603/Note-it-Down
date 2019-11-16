Handwriting Recognition has been one of the famous area of research in the field Machine Learning. This model is a mixture of various Deep
Neural Network Layers. Kaggle competition dataset and MNIST dataset is used for training the model. The input to the system will be the 
user’s Handwritten Character Sample on the canvas and the output will be the Digital Character Prediction.

Technologies Used: Keras, Python, Jupyter Notebook, Google Colaboratory.


The system is implemented on various algorithms such as Convolution Neural Network, Keras, Adam optimizer, and Tkinter for the GUI.GUI for
the underlying system is made in python. This app demonstrates the application of CNN for solving handwritten alpha numeric character
recognition problem. In GUI, use the Canvas Area to draw the character using mouse or touch pad or stylus. GUI uses the generated model
for predicting the alphanumeric character which was drawn in Canvas Area.

The generated output from the convolution neural network is the most accurate representation of the user handwriting character.The CNN is
trained using MNIST data (60000 samples) and Kaggle competiton dataset (~150000 samples). The accuracy is >99%.

The accuracy of the model decreases and the loss rate is increased after performing 40 epochs. So, we restrict to train our model for 40
epochs only. The training took approx. 30 minutes, as we have used Google Colaboratory for training purpose. Thus, training time is much
lesser.


Future Work:
  Since, the System can only recognize a handwritten character as of now. In future, the system can be advanced to recognize a handwritten
word and further developing it to recognize a whole paragraph. On the machine learning part, various techniques to speed up the execution
and learning process will be implemented to be as much responsive as possible.
