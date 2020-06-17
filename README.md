# Predicting-Boston-Housing-Prices
 
Using XGBoost in SageMaker (Batch Transform)

Deep Learning Nanodegree Program | Deployment

As an introduction to using SageMaker's High Level Python API we will look at a relatively simple problem. Namely, we will use the Boston Housing Dataset to predict the median value of a home in the area of Boston Mass.

The documentation for the high level API can be found on the ReadTheDocs page
General Outline

Typically, when using a notebook instance with SageMaker, you will proceed through the following steps. Of course, not every step will need to be done with each project. Also, there is quite a lot of room for variation in many of the steps, as you will see throughout these lessons.

    Download or otherwise retrieve the data.
    Process / Prepare the data.
    Upload the processed data to S3.
    Train a chosen model.
    Test the trained model (typically using a batch transform job).
    Deploy the trained model.
    Use the deployed model.

In this notebook we will only be covering steps 1 through 5 as we just want to get a feel for using SageMaker. In later notebooks we will talk about deploying a trained model in much more detail.
