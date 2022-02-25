# credit_bond_default_prediction
This script aims to find a classifier model that perform better than models built by previous works in the task of predicting the default for Chinese credit bonds using, as predictors, some accounting financial ratios.

For modelling, the script uses the two .csv datasets avaiable in this repository. The train dataset contains the recordings of all enterprise and corporate credit bonds issued in China from 2017 to 2021,Aug. The train data considers the bonds issued until 2020 and has information about accounting financial ratios, and some bonds and issuer's caracteristics, as the default information. The test data contains the same information but only for the credit bonds matured between 2021,Jan and 2021,Aug.

And additional dataset in excel format contains the results of other logit models trained for this same purpose and using the same data. We use this dataset to challenge the results achieved by the model trained by this code. 
