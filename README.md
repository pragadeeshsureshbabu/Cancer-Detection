# Cancer-Detection

 Samples arrive periodically as Dr. Wolberg reports his clinical cases.
   The database therefore reflects this chronological grouping of the data.
   This grouping information appears immediately below, having been removed
   from the data itself:

     Group 1: 367 instances (January 1989)
     Group 2:  70 instances (October 1989)
     Group 3:  31 instances (February 1990)
     Group 4:  17 instances (April 1990)
     Group 5:  48 instances (August 1990)
     Group 6:  49 instances (Updated January 1991)
     Group 7:  31 instances (June 1991)
     Group 8:  86 instances (November 1991)
     -----------------------------------------
     Total:   699 points (as of the donated datbase on 15 July 1992)
     
## Attribute Information: 

   ###  Attribute                    
  
   1. Sample code number            id number
   2. Clump Thickness               1 - 10
   3. Uniformity of Cell Size       1 - 10
   4. Uniformity of Cell Shape      1 - 10
   5. Marginal Adhesion             1 - 10
   6. Single Epithelial Cell Size   1 - 10
   7. Bare Nuclei                   1 - 10
   8. Bland Chromatin               1 - 10
   9. Normal Nucleoli               1 - 10
  10. Mitoses                       1 - 10
  11. Class:                        (2 for benign, 4 for malignant)
       
       Benign: 458 (65.5%)
       
       Malignant: 241 (34.5%)

## Results
1. Logistic Regression-
    1. Accuracy on training set: 0.979
    2. Accuracy on test set: 0.965
2. k Nearest Neighbors
    1. Accuracy on training set: 0.975
    2. Accuracy on test set: 0.959
3. Random Forest
    1. Accuracy on training set: 0.979
    2. Accuracy on test set: 0.959
