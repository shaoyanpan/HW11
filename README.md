# HW11
Shaoyan Pan
shaoyank@gmail.com

####Question 1
###Part A
![IMG_2491](https://user-images.githubusercontent.com/89927506/140651823-3158749b-6e49-4615-906a-914bbb9246ea.jpg)

###Part B
The own results equal to the MALTBA's result


####Question 2
###Part A and B
The dominant eigenvalue is 5.3, the dominant eigenvector is [-1, -0.34].

![Q2B](https://user-images.githubusercontent.com/89927506/140651978-118536ca-0fe2-40c1-8dfc-27c63ce8b815.jpg)

####Question 3
###Part A
The testPCA (file 1) project the singal into other dimensions, and only extract the dominant features. We can see after the extraction, the recovered signal is very similar to the original singal. And if we decrease the PCA threshold, we can see the recovered singal is even more similar. That means, with more PCA components, the recovered singal is more similar to the original singal. But we don't really need to have so many PCA component to have an acceptable accuracy. This is the PCA's functionality. We don't need to have too many features but only a few important feature then we can have a approximately similar singal. Then we can reduce the dimensinoality so have more efficient computation.

###Part B
This method uses a power method to approximate the eigen value and eigen vector. The power method can be used to efficiently approximate the eigen features, but it can only approximate the extreme eigne values and its dominant eigenvectore. That means the power method is a very efficient method. Compare to the MATLAB's eig function, we can see the power method is faster. However, the power method can only gain the dominant eigen value and feature. In addition, if we increase the power iteration, we can see the eigen value and vector will be more similar to the correct eigen value and vector.

###Part C
ICA method is also very important signal algorithm to extract important features. ICA is extracting the features while maximize the independence between different features extracted by the ICA algorithm. We can see the independence between the different features are calculated by the convariance matrix calculated by the PCA then mutual information. Large cov matrix can result in more similar signals. We can also see the ICA components can approximately equal to the original signal. But since the ICA method can maximize the indepedence between different features, we can have a better featres to improve some classification, but it all depend on the task.

