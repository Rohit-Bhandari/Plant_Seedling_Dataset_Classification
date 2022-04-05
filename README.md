# Plant Seedling Dataset Classification using VGG16, ResNet50, Inception V3

Used the Plant Seedlings Dataset to attempt the following,

* Write our own functions to load the data, normalize the data, OHE for categories.

* Use pre-trained VGG16, ResNet50 and InceptionV3 networks to extract bottleneck features and build a model on top of each of them to evaluate and compare the model performances. (Model performances include classification report, confusion matrices, plots of Loss Vs Epochs)

* Write 2 separate scripts:
  * To train the network and save the model with highest validation accuracy. 
    Save model - model.save('model.h5')
  * Load the model and predict on the test data.
    Load Model - model = load_model("model.h5")
