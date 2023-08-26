# Semantic-Segmentation-with-Sagemaker
This includes training and deploying a Semantic Segmentation model using Amazon Sagemaker. 
Sagemaker provides a number of machine learning algorithms ready to be used for solving a number of tasks. 
I used the semantic segmentation algorithm from Sagemaker to create, train and deploy a model that will be able to segment images of dogs and cats from the popular IIIT-Oxford Pets Dataset 
into 3 unique pixel values. That is, each pixel of an input image would be classified as either foreground (pet), background (not a pet), or unclassified (transition between foreground and background).
At the end, deleted the deployed model endpoint.
