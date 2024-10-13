# Face-Mask-detection

Face masks are now a common sight in public places thanks to the new coronavirus, which first appeared in China before spreading to other countries. Recent studies have revealed that a significant part of people with coronavirus does not display symptoms, and even those who eventually do can spread the virus to others before becoming infected. This suggests that the virus can spread between people even if they are not exhibiting symptoms while they are in close proximity and speaking, coughing, or sneezing. So it is inevitable for the people of an overpopulated country like India to wear masks wherever they are. Because of this, face mask detection became widely popular which can be quite helpful to see if everyone wears masks in any place.

The project aims to detect face masks in a given dataset which may be obtained from sensitive areas such as airports, hospitals, shopping malls, and other essential public places.
We utilize python libraries such as Numpy, Keras, TensorFlow, and OpenCV.


We implement our project in two distinct phases, training and deployment. In the first phase, we begin by performing a dataset split by categorizing data into training, validation, and test datasets. The CNN model is trained on this dataset using TensorF low/Keras. Once the face mask detector is trained, we then load the mask detector, perform face detection, and then classifying each face as with or without the mask.
. Based on the higher probability, the label
will be chosen and displayed around our faces.
