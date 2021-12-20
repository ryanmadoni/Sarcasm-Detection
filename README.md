# Sarcasm-Detection
Sarcasm Detection using an Ensemble of 15 BERT and DistilBERT models implemented using PyTortch.  The Kaggle data set used in finetuning the models can be found here:
https://www.kaggle.com/danofer/sarcasm.  Different model architectures, comment lengths, and context were compared and contrasted to see how the affected the detection of sarcasm; more can be read about in the paper.

Over 80% accuracy was achieved on the testing set and lost accuracy is partially accredited to the quality of the data set, which has multiple issues discussed in the paper.

# Running the Attached Code 
 
All resources to run the code are available in this repository and explanations are in the paper.  Read through the code and change parameters as needed to configure; the comments in the code should help.
The code was originally run using Google Colab Pro.

###### (1) Download the data set from Kaggle.  We only made use of the "test-balanced.csv" file.
###### (2) Run "DataGenerator.ipynb" after specifying the correct parameters in the code.
###### (3) Use the data sets created as input to "modeling.ipynb" after specifying the correct parameters in the code.
###### (4 Optional) After compiling and saving multiple models, use "ensemble.ipynb" to ensemble multiple models together after setting the correct parameters in the code. 
