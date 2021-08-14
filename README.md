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

3. Converting the image from RGB to HSI Format :
Conversion of RGB to HSI (Hue Saturation Intensity) is helpful where the color description plays an important role. 
RGB color space describes the colors in the form of red, green and blue.
RGB model determines color as a collection of primary colors. HSI model’s description of color is identical as of the leaf. 
4. Separating the foreground :
The separation of the foreground and background plays an important role in obtaining the diseased part of the leaf. 
In this approach the foreground of the image is extracted. So automatically therefore the foreground is separated and is helpful in detection

5.Leaf Segmentation :
The image is segmented into various parts according to the region of interest. 
This detects the division of the same and meaningful regions. In other words image segmentation is used to separate the objects from the background of the image. 
Then after the segmentation the segmented part is given to the clustering algorithm that is k-means.
6. Feature Extraction :
The input given to the algorithm is huge and can lead to complex processing.
The inputs given are compact and binded together so that it represents as set of features. 
If the features of the image are extracted wisely then whatever the feature set is available it gauges proper information from the input in order to perform relevant task.

K-means :
The k-means algorithm tries to split the data set which contains the information of particular data set into a fixed number of clusters (k). 
The classification of object is done by minimizing the sum of the squares of the distance between the object and the corresponding cluster.
 1. Pick center of K cluster, either randomly or based on some heuristic.  
 2. Assign each pixel in the image to the cluster that minimizes the distance between the pixel and the cluster center. 
 3. Again compute the cluster centers by averaging all of the pixels in the cluster. Repeat steps 2 and 3 until convergence is attained.
 
The RGB images are converted into the grey images using color conversion.
Equation :
               f(x)=0.2989*R + 0.5870*G + 0.114.*B
The RGB image is converted into HIS translation :
Equations:
                        Theta    if B<G
             H  =       360 – Theta    if B>G
     
             S   =      1- (3/(R+G+B))*[min(R,G,B)]
             I    =      (1/3)*(R+G+B)
 # Algorithm:
 Step 1:Start
Step 2:Load leaf image as input.
Step 3: Pre-process the images of leaf to remove background noise.
Step 4: Convert the pre processed image to binary image using threshold algorithm. 
Step 5:Segmentation of Otsu is considered as binary image from grey image.
    Otsu process :
     Separate pixels into clusters
     1.Then find the mean of each cluster.
     2.Square the difference between the means.
     3.Multiply the number of pixels in one cluster times the number in the other.
Step 6: Feature extraction is used to identify the disease and morphological method provide better result.
Step 7: Stop.

 # Reference:
 [1] Jayamala K. Patil, Raj Kumar, ―Advances In Image Processing For Detection of Plant Diseases ‖, JABAR, 2019, 2(2), 135-141. 
[2] P.Revathi, M.Hemalatha, ―Classification of Cotton Leaf Spot Diseases Using Image Processing Edge Detection Techniques‖, ISBN, 2019, 169-173, IEEE. 
[3] H. Al-Hiary, S. Bani-Ahmad, M. Reyalat, M. Braik and Z. ALRahamneh, ―Fast and Accurate Detection and Classification of Plant Diseases‖, IJCA, 2019, 17(1), 31-38, IEEE-2019. 
[4] Piyush Chaudhary, Anand K. Chaudhari, Dr. A. N. Cheeran and Sharda Godara, ―Color Transform Based Approach for Disease Spot Detection on Plant Leaf‖, IJCST, 2019, 3(6), 65-70. 
[5] S. Arivazhagan, R. Newlin Shebiah, S. Ananthi, S. Vishnu Varthini, ―Detection of unhealthy region of plant leaves and classification of plant leaf diseases using texture features‖, CIGR, 2019, 15(1), 211-217. 
[6] Chanchal Srivastava, Saurabh Kumar Mishra, Pallavi Asthana, G. R. Mishra, O.P. Singh, ―Performance Comparison Of Various Filters And Wavelet Transform For Image De-Noising‖, IOSR-JCE, 2019, 10(1), 55-63.
[7] Dheed Al Hiary, S. Bani-Ahmad, M. Braik, ―A Framework for Detection and Classification of Plant Leaf and Stem Diseases‖, IEEE, 2019, 113-118. 
[8] Mrunalini R. Badnakhe, Prashant R. Deshmukh, ―Infected Leaf Analysis and Comparison by Otsu Threshold and k-Means Clustering‖, IJARCSSE, 2019, 2(3), 449-452. 

 
