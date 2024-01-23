The detection of image forgery is a strenuous task for the human eye, and thus requires the use of sophisticated techniques.
In this project, an machine learning approach is examined. 
Here, a combination of Error Level Analysis (ELA) and Convolutional Neural Network (CNN) is proposed for the detection of image forgery.
Error Level Analysis is a compression algorithm used in image forensics particularly for the JPEG format. 
It operates on a method of compression of an image by calculating the difference in the error levels of the original and the compressed image
The project utilize Error Level Analysis to pre-process images in the CASIA (Version 2) Dataset and thus feed the output to a tensor flow trained convolutionalNeural Network (ELA-CNN)
