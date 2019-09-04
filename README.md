# Classifying Landscape Images with Overlapping Features Using Convolutional Neural Networks

For this project, Deep Learning was used to classify landscape images. The best model, which got an accuracy of 90.8%, was a Convolutional Neural Network model, created using transfer learning from VGG16. The second model was created ad hoc for this application, and inspired in the architecture of VGG16. This model got 85% of accuracy.

Both models were trained using 14,000 images of 150x150 pixels in three channels, RGB. Then, the models were used to predict the classes of 3,000 unseen images (test set). The images belonged to six different classes, namely buildings, forest, glacier, mountain, sea, and street.

One big challenge of this project was having important features overlapping in different classes. For instance, there could be images of the ‘street’ class with buildings in them, and images of the ‘buildings’ class with streets in them. This overlapping of features was also seen in the ‘glacier’–‘mountain’, ’glacier’–‘sea’ and ‘mountain’–‘sea’ pairs of classes.
