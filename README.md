# object-detection
Object Detection using Azure Cognitive Service for Computer Vision

## Introduction
Object detection is a form of machine learning based computer vision in which a model is trained to recognize individual types of objects in an image, and to identify their location in the image.

An object detection model returns the following information:
- The class of each object identified in the image.
- The probability score of the object classification (which you can interpret as the *confidence* of the predicted class being correct).
- The coordinates of a bounding box for each object.

![Screenshot 2023-05-20 182430](https://github.com/SyedAanif/object-detection/assets/66770875/a28d1da2-9e9d-4045-b546-62938b731cfc)

![Screenshot 2023-05-20 182303](https://github.com/SyedAanif/object-detection/assets/66770875/8f752dd3-db15-4d46-a508-732d3be3627a)

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

   ![Screenshot 2023-05-20 184826](https://github.com/SyedAanif/object-detection/assets/66770875/006fe832-fe47-4e8e-85bb-ed11cd985252)

4. Create a [Computer Vision](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/overview) service inside the resource group created above.

   ![Screenshot 2023-05-20 185100](https://github.com/SyedAanif/object-detection/assets/66770875/a8fdb5ce-a668-4c6d-ad42-3c3f67dbeb04)

6. Copy the `Keys` and `Endpoint` from the `Computer Vision` resource and substitute them for `subscription_key` and `endpoint` respectively. This will be used to authenticate the computer-vision-client to the computer vision resource.

   ![Screenshot 2023-05-20 185200](https://github.com/SyedAanif/object-detection/assets/66770875/9669c23c-9cb0-453f-bad8-f9c6ea86266a)

   ![Screenshot 2023-05-20 193145](https://github.com/SyedAanif/object-detection/assets/66770875/a98afba0-23bb-45c1-ba48-99b1f9a99d73)
  
5. Run the provided notebook for performing object-detection.
