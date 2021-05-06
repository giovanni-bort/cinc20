# Example of trained CNN GoogLeNet MATLAB for the PhysioNet/CinC Challenge 2020

## Contents

NEW_NET_1.mat
NEW_NET_2.mat
NEW_NET_3.mat


* `train_model.m` Train your model. Add your model code to the `train_12ECG_model` function. It also performs all file input and output. **Do not** edit this script or we will be unable to evaluate your submission.
* `driver.m` is the classifier which calls the output from your train_model. It also performs all file input and output. **Do not** edit this script or we will be unable to evaluate your submission.

Check the code in these files for the input and output formats for the `train_model` and `driver` scripts.

To create and save your model, you should edit `train_12ECG_classifier.m` script. Note that you should not change the input arguments of the `train_12ECG_classifier` function or add output arguments. The needed models and parameters should be saved in a separated file. In the sample code, an additional script, `get_12ECG_features.m`, is used to extract hand-crafted features. 

To run your classifier, you should edit the `run_12ECG_classifier.m` script, which takes a single recording as input and outputs the predicted classes and probabilities. Please, keep the formats of both outputs as they are shown in the example. You should not change the inputs and outputs of `run_12ECG_classifier` function. The needed models and parameters can be loaded in the `load_12ECG_model` function.

Check the code in these files for the input and output formats for the `load_12ECG_model` and `run_12ECG_classifier` functions.

## Running

You can check the structure of GoogLeNet networks by starting MATLAB and running

    load NEW_NET_1.mat
    analyzeNetwork(NEW_NET_1)


## Submission



## Details

