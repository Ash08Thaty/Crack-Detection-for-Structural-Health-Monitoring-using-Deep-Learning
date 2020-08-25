# Crack-Detection-for-Structural-Health-Monitoring-using-Deep-Learning

Crack detection has vital importance for structural health monitoring and inspection. In this project I built a classifier using a pre-trained model that detected cracks in images of concrete. I denoted images of cracked concrete as the positive class and images of concrete with no cracks as the negative class.

I trained and tested deep learning models using Keras and PyTorch modules to identify cracks in images of concrete.

Using Keras, I employed a ResNet50-based model which achieved an accuracy of 95.20% on the test data. Then, I implemented an image classifier using the VGG16 pre-trained model, adding one dense top layer, compiling with Adam optimization and a categorical cross-entropy loss function, and training the model across 2 epochs. It performed at 99.60% accuracy on the same test data.

Using PyTorch, I implemented a pre-trained ResNet18-based model. It achieved an accuracy of 99.70%.

Dataset: https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0321EN/data/concrete_data_week4.zip
