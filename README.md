# Alcohol Image Classifier
Utilizing fastai to classify images of various types of alcoholic beverages

## Motivation
I was interested to test out fastai to setup and run an image classificaton deep learning model. Since I am someone who enjoys whisky from time to time, I decided that running a CNN classifier on alcohol images would be a nice topic to work on. The code here is mostly adapted from what is already publicly provided by fastai (check it out at https://www.fast.ai/)
___

## Azure API Setup
I will be leveraging the Bing Search v7 API (with Azure Account) to retrieve images for the deep learning classification model. As I found this setup to be rather tedious, I have decided to share some details on how to set it up properly.

<u>Step 1</u>
You will need a Bing Search API key in order to obtain image datasets for your classifier. In order to retrieve the API key, you will need to first setup a Free Trial account at https://azure.microsoft.com/en-gb/free/cognitive-services/. 

If you already have an existing account, click on the Upgrade option (there is still a Free option to select).

After you are logged in inside the Azure portal, use the search bar at the top and key in **Bing Search**.

<img src="/images/azure_step1.png" width = "70%" alt="My cool logo"/>

After the setup is complete, go directly to https://azure.microsoft.com/en-gb/try/cognitive-services/my-apis/.
___

### Methods
The details of the steps from data curation to the actual classification are documented in the Jupyter notebook. Please have a look at the notebook.

## Further Steps
- Deployment as a web app (still in progress)
