# Classifying Alcoholic Beverages with fast.ai and Google CoLab
Utilizing fastai to classify images of various types of alcoholic beverages

Quick link to view notebook: https://nbviewer.jupyter.org/github/kennethleungty/Alcohol-Image-Classifier-fastai/blob/main/Alcohol_Image_Classifier_Notebook.ipynb

## Motivation
I was interested to test out fastai to setup and run an image classificaton deep learning model. Since I am someone who enjoys whisky from time to time, I decided that running a CNN classifier on alcohol images would be a nice topic to work on. The code here is mostly adapted from what is already publicly provided by fastai (check it out at https://www.fast.ai/)
___

## Using Google Colab
Highly recommend to run this notebook in Google Colab. This is because the notebook was setup and tested in Google Colab, and Colab also offers a free GPU for training the model (up to 12 hours).
___

## Azure API Setup
I will be leveraging the Bing Search v7 API (with Azure Account) to retrieve images for the deep learning classification model. As I found this setup to be rather tedious, I have decided to share some details on how to set it up properly.


### Step 1
____________

You will need a Bing Search API key in order to obtain image datasets for your classifier. In order to retrieve the API key, you will need to first setup a Free Trial account at https://azure.microsoft.com/en-gb/free/cognitive-services/. 

<img src="/images/azure_step1.png" width = "60%"/>

There is a 7-day trial free period for new users. If you already have an existing account, click on the Upgrade (Pay-As-You-Go) option (there is still a Free option to select). You will need to provide a credit card number for verification. You just need to make sure that you select the free option throughout.

More details can be found here: https://docs.microsoft.com/en-us/bing/search-apis/bing-web-search/create-bing-search-service-resource


### Step 2
____________ 

After you are logged in inside the Azure portal, use the search bar at the top and key in **Bing Search v7**.

<img src="/images/azure_step2.png" width = "60%"/>

### Step 3
____________

You will first need to create a resource group  

<img src="/images/azure_step3.png" width = "60%"/>

### Step 4
____________ 

After the resource group is set up, you can Add the Bing Search resource by searching for  **Bing Search v7** after clicking the Add button. Fill in the relevant fields subsequently  

<img src="/images/azure_step4.png" width = "60%"/>  

<img src="/images/azure_step5.png" width = "60%"/>  

<img src="/images/azure_step6.png" width = "60%"/>

### Step 5
____________

Lastly, go to Keys and Endpoint to retrieve your API key  

<img src="/images/azure_step7.png" width = "60%"/>




## Methods
Details of the steps from data curation to the actual classification are documented in the Jupyter notebook, so please feel free to have a look by clicking the link below: https://nbviewer.jupyter.org/github/kennethleungty/Alcohol-Image-Classifier-fastai/blob/main/Alcohol_Image_Classifier_Notebook.ipynb

## Further Steps
- Deployment as a web app (still in progress)
