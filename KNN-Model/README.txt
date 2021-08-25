The RMD file here contains basic data processing code.
It formats the data present in crash2.rda and generates
3 rda files. 

Training.Dataset.rda => Everyone must use data in this file for all the activities like feature selection and training models.

Validatioin.Dataset.rda => Data in this file must be used for evaluating performance of the models.

Test.Dataset.rda => The results of models on this dataset must be reported. (Not to be used till final submission)

The seed used for spliting data set is 108 (set.seed(108) ).  I would request everyone to continue using same seed throughout our assignment.