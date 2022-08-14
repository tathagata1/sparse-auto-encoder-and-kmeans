# sparse-auto-encoder-and-kmeans

Steps to run the code:
1. Import M21AI619_Assignment_3_SAE.ipynb and M21AI619_Assignment_3_KMEANS.ipynb into your IDE
2. Run M21AI619_Assignment_3_SAE.ipynb in order to,
    a. Create a folder named SAEModel
    b. Download the dataset
    c. Train the Sparse Auto Encoder model
    d. Save the model data into SAEModel
    e. Provide a plot of the training and testing loss
3. Run M21AI619_Assignment_3_KMEANS in order to,
    a. Load the model from SAEModel.ipynb
    b. Download the dataset (again if needed)
    c. Run the pre-trained model on the dataset
    d. Run k-means clustering on the model predictions
    e. Check for the minimum cluster size that will provide at least 80% accuracy
    f. Generate a plot for the accuracy vs cluster number

NOTE: SAEModel folder would be created in the current working directory of the notebook files, hence minor path change(s) may be required in order to run the notebooks on google-colab

The notebooks' have been implemented and tested using,
VSCode version: 1.69.2
Python 3.8.10
=========
