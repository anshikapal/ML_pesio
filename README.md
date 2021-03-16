# ML_FINAL

This is the final project of MACHINE LEARNING PESIO course slot-11 (2021)

TEAM NUMBER: 03

NAME OF TEAM MEMBERS: 
1) ANSHIKA PAL(PES1UG20CS062)
2) PRATHAM S MALAGI (PES1UG20EC324)

DESCRIPTION:
We trained the model by classifying the person into different classes which are the types of skin disease given below according to their symptoms and family history.
We are classifying the datasets using the SVM model. 
LIBRARIES IMPORTED:
1) NUMPY
2) PANDAS
3) SKLEARN
Number of features while training and testing should be same in case of SVM.

DATASET: 
We have used dermatology dataset which is taken from UCI repository (LINK: https://archive.ics.uci.edu/ml/datasets/Dermatology).

Database:  Dermatology
       
       Class code:   Class:                  Number of instances:
       1             psoriasis			                112
       2             seboreic dermatitis             61
       3             lichen planus                   72
       4             pityriasis rosea                49
       5             cronic dermatitis               52    
       6             pityriasis rubra pilaris        20


MODEL:SUPPORT VECTOR MACHINE 

TESTING:
We can not train two or more different features during testing, we can use only one of them.
We splitted the datset into two parts: 20% for testing and 80% for training.


PREDICTION:



SUMMARY:

In the dataset, the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise. The age feature simply represents the age of the patient. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values.



