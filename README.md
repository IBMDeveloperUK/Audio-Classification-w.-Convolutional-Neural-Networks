# Audio Classification w. Convolutional Neural Networks

In this workshop you will learn how to construct a densely connected convolutionalneural network using Keras with a Tensorflow backend to classify spectrograms of audio files of 1 of _n_ speakers (golly, that's dense...).

_ahem_

In this workshop, you'll learn how to tell which of two people is speaking - namely Stephen Colbert or Conan O'Brien - with neural networks.

The workshop is aimed at people who are interested in learning about machine learning.

## Getting Started with Jupyter Notebooks

Jupyter notebooks are an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text. 

In this workshop we will use IBM Watson Studio to run a notebook. For this you will need an IBM Cloud account. The following steps will show you how sign up and get started. When you have the notebook up and running we will go through the notebook. 

## IBM Cloud

- [Sign up](https://cloud.ibm.com/registration) for an IBM Cloud account

- When you are signed up click `Create Resource` at the top of the Resources page. You can find the resources under the hamburger menu at the top left:

 ![An image showing the locations of the 'Create Resource' button](images/resources.png)
 
- Search for Watson Studio and click on the tile:

![](images/studio.png)

- Select the Lite plan and click `Create`.
- Go back to the Resources list and click on your Watson Studio service and then click `Get Started`. 

![An image if the IBM Cloud Catalog](images/launch.png)

## IBM Watson Studio

### 1. Create a new Project

- You should now be in Watson Studio.
- Create a new project by clicking on `Get Started` and `New Project`, or `Create Project`
- Give your Project a name.
- Select an Object Storage from the drop-down menu or create a new one for free. This is used to store the notebooks and data. **Do not forget to click refresh when returning to the Project page.**
- click `Create`.  

## 2. Load and run a notebook

-  Add a new notebook. Click `Add to project` and choose `Notebook`:

![An image showing the user how to create a notebook](images/addnotebook.png)

- Choose new notebook `From URL`. Give your notebook a name and copy the URL `https://github.com/IBMDeveloperUK/Audio-Classification-w.-Convolutional-Neural-Networks/blob/master/conan_or_colbert.ipynb`
-  The notebook will load. 
 
You now have the code and resources to run the workshop. Further instructions and information can be found in the notebook.
