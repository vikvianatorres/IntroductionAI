# IntroductionAI

# Create an image classification project with the Custom Vision client library

This guide provides instructions and sample code to help you get started using the Custom Vision client library for Python to build an image classification model. You'll create a project, add tags, train the project, and use the project's prediction endpoint URL to programmatically test it. Use this example as a template for building your own image recognition app.

# Prerequisites
Python 2.7+ or 3.5+

pip tool

To use the Custom Vision Service you will need to create Custom Vision Training and Prediction resources in Azure. To do so in the Azure portal, fill out the dialog window on the Create Custom Vision page to create both a Training and Prediction resource.

# Get the training and prediction keys

The project needs a valid set of subscription keys to interact with the service. You can find the items at the Custom Vision website. Sign in with the account associated with the Azure account you used to create your Custom Vision resources. On the home page (the page with the option to add a new project), select the gear icon in the upper right. Find your training and prediction resources in the list and expand them. Here you can find your training key, prediction key, and prediction resource ID values. Save these values to a temporary location.

