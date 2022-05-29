
# Image Classification with Cifar-10 dataset 📷

The goal of the project is to implement K-means clustering from scratch on supervised learning using the Cifar-10 data set and to use various evaluation metrics to identify the validation of the predicted result.

Then Autoencoder is used to encode the images before feeding to the K-means models trained above.

##  Abstract:  

<p align="center">
<img src="https://github.com/sajmaru/CIFAR10_Classification/blob/main/Dataset%20Snapshot.png" height = 250 width = 375>
</p>

 - The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. 
 -  There are 50000 training images and 10000 test images. 
 - The dataset is divided into five training batches and one test batch, each with 10000 images. 
 - The test batch contains exactly 1000 randomly-selected images from each class. 
 - The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 
 - These are the classes in the dataset:
	 1. airplane 
	 2. automobile 
	 3. bird 
	 4. cat  
	 5. deer
	 6. dog 
	 7.  frog 
	 8.  horse  
	 9.  ship 
	 10.  truck 
 - The classes are completely mutually exclusive. i.e. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks. 
 
## Results 🚀
### K-means 
 - Achieved 
	 - **Silhouette_score = 0.0789**
	 - **Dunns_Index = 0.0949**
### Autoencoder
- Achieved 
	 - **Silhouette_score = 0.0202**
	 - Below is the comparison results of the original training data with the decoded images from the autoencoder.

 <p align="center">
<img src="https://github.com/sajmaru/CIFAR10_Classification/blob/main/Autoencoder%20Output.png" height>
</p>

