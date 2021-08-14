# Leaf-Disease-Segementation-and-Classification-using-ML
Effective system that  carries automatic and an early diagnosis of a disease and its severity so that timely treatment can  be taken in advance.
# Objective of the Project:
To develop an effective system that carries automatic and an early diagnosis of a disease and its severity so that timely treatment can be taken in advance.

Accurate prediction of leaf diseases with less time consumption and with less noise.

# Background Work:
Problem Definition:

The main aim of our project is to identify and classify the disease accurately from the
leaf images.

The steps required in the process are preprocessing, Training, and Identification.

Pre-processing refers to the transformations applied to our data before feeding it
to the algorithm.

Model Training is the process of feeding an ML algorithm with data to help
identify and learn good values for all the attributes involved.

For identification of disease features of leaf such as major axis, minor axis etc.
are extracted from leaf and given to classifier for classification.

# Problem Indentification:

Inaccurate prediction of type of disease.

Loss in image reorganization.

Inaccurate in query results.

Quality of Output image is not good.

Cannot be implemented in all images.

Over lapping of images is high.

Execution time is more.

# Proposed System:
Support Vector Machine:

To detect an ideal hyperplane for different distinct examples in a high dimensional space is the main process of the SVM. To fulfill this model there is more than one
hyperplane.

This process depends upon the bolster vector which the information that lies nearest on the closed surface and coordinating with the ideal choice surface.

It performs classification by planning the input vectors into a high dimensional space and constructing the hyperplane to separate the data. This strategy is mainly
used to solve a quadratic programming problem and non-convex, unconstrained minimization problem.

The SVM is the most effective method in the classifier process.

![image](https://user-images.githubusercontent.com/39005873/129434821-9f1f0d91-8afb-414f-b62f-c37ffa4da445.png)

# Modules Description:

1. Input Image :
Used for training the data set. 
Used for comparison of the diseased leaf and healthy leaf.
2. Blur Soften Image :
 Blurring of the image means each pixels of the image gets spread over. 
Sharpening of the image can be reduced by using blurring and detection can be accurate. 
Blurring the image helps to reduce the amount of noise in the image. 
When the image is taken it contains some noise which can make detecting the affected area as tough process. So by blurring the image the noise can be reduced.

![image](https://user-images.githubusercontent.com/39005873/129434891-4b0d7478-7257-450d-a04e-4fee2ee4f6cd.png)
