# CS-230-Project


CS230 Final Project  
Ellen Roper and Tristan Gosakti  
Stanford University 

Motion capture technology is becoming increasingly prevalent in today’s society, offering a myriad of applications. As a result, TuringSense, a Santa Clara-based tech wearable company, created a product which uses motion capture to train athletes. Standard motion capture is often optical in nature, but TuringSense replaces this approach with digital technology, opting to use their own motion sensors instead. Currently, TuringSense uses mathematical models from the motion sensors’ data to classify tennis strokes. This project details the implementation of a single layer neural network, a deep neural network, and a convolutional neural network to classify 5 different tennis stroke types with final test set accuracies of 0.96, 0.97 and 0.98 respectively.

Currently, TuringSense uses their own mathematical models (derived from trial and error) to process raw data from 6 sensors attached to different parts of the human body and the tennis racket for tennis stroke classification. They are looking to improve the accuracy of this model, so we have offered to use deep learning algorithms in an attempt to do this. The metrics of their algorithms and the final purposes of these sensors are unable to be disclosed due to an NDA, but it is clear that providing data feedback to their users is one of TuringSense’s most important value propositions, so this project’s result is very significant. The input to the algorithm is processed data from 6 of TuringSense’ sensors projected over a time span. We used linear regression (single layer NN), a deep-layer (four layer NN), and a convolutional neural network to produce outputs that classify the stroke into one of the following five strokes: (1) forehand flat, (2) forehand topspin, (3) backhand slice, (4) backhand topspin, and (5) forehand slice.
