# Sasol
## Hardware used
Google Colab

## How to set up folders and where each file is saved
On Google Drive, in the Colab Notebooks file (this is the default file where Colab notebooks go), create a file called "Data" if you do not have one. Inside this file, create a file called "Sasol". In the Sasol file, store the competition data (Train.csv, Test.csv, SampleSubmission.csv, and VariableDescription.csv) and this notebook (SasolCustomerRetention.ipynb).

## Order in which to run code
The code can just be run from top to bottom.

## Explanations of features used
See notebook for more info, but briefly:
* region
* revenue
* frequency
* regularity
* top_pack

All chosen because they had a correlation with the target variable of above 0.1 and did not pose multicollinearity issues. 


