# object-detection
Object Detection using Azure Cognitive Service for Computer Vision

## Introduction
Object detection is a form of machine learning based computer vision in which a model is trained to recognize individual types of objects in an image, and to identify their location in the image.

An object detection model returns the following information:
- The class of each object identified in the image.
- The probability score of the object classification (which you can interpret as the *confidence* of the predicted class being correct).
- The coordinates of a bounding box for each object.

![image](https://github.com/SyedAanif/object-detection/assets/66770875/4d445a55-8649-451f-a8ed-802c92c692f8)

![image](https://github.com/SyedAanif/object-detection/assets/66770875/a1b33b50-cd9e-49e0-98e0-001ec123fb38)

Object Detection belongs to advanced computer vision and can be performed in the following ways:
- [Azure Cognitive Services for Vision](https://learn.microsoft.com/en-us/azure/cognitive-services/)
  + [Computer Vision](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/overview)
  + [Custom Vision](https://learn.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/overview)
- Build own advanced computer vision models.

In this project we will be utilising `Azure Computer Vision` service to process images for object-detection.

## Pre-requisites
- Python 3.X version: 
  + [Installation using Anaconda distribution](https://docs.anaconda.com/free/anaconda/#installation)
  + [Python Website](https://www.python.org/downloads/)
- [Microsoft Azure Account](https://azure.microsoft.com/en-in/free/)
- Editor of choice:
  + Jupyter Notebook comes packaged with Conda distribution
  + [Google Colab](https://colab.research.google.com/)

## Steps to perform Object-Detection
1. Sign-in to your [Microsoft Azure account](https://portal.azure.com/#home).

2. Create a [Resource Group](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal#what-is-a-resource-group) (in a region closest to your location) to logically contain your Azure Resources.
  ![image](https://github.com/SyedAanif/object-detection/assets/66770875/94e89bad-789d-44c9-b96a-ba4b278c9d5b)
  
3. Create a [Computer Vision](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/overview) service inside the resource group created above. 
  ![image](https://github.com/SyedAanif/object-detection/assets/66770875/4097412b-c1e7-4f7f-8ce3-63ccecfbe3c9)

4. Copy the `Keys` and `Endpoint` from the `Computer Vision` resource and substitute them for `subscription_key` and `endpoint` respectively. This will be used to authenticate the computer-vision-client to the computer vision resource.
  ![image](https://github.com/SyedAanif/object-detection/assets/66770875/2e9b977f-6aaa-4856-a6bf-ce27a18a9595)

  ![image](https://github.com/SyedAanif/object-detection/assets/66770875/322d7cff-a794-4775-b697-f32d643fcc5b)
  
 5. Run the provided notebook for performing object-detection.
