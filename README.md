===========================================
ccl - fast Connected Component Labeling
===========================================

author: moodaeng theparitt
email:  theparitt@gmail.com



===========================================
                version 1.0
===========================================
Fast Connected Component Labeling (Connected Component Analysis) based on Lifeng He et.al. paper. http://www.sciencedirect.com/science/article/pii/S0031320308004573. Normally Connected Component Labeling is the bottleneck for many image procesing algorithm. However the new brillint method from Lifeng H. eliminate this limitation. 
     In the code, I modified the algorithm to make it possible to run with gray scale image. Moreover the code can tells dimension ( width, height, centroid) of  groups of connected component labels. Some methods for fastening the runtime are also included in the code to make the code run as fast as possible.
     
     

===========================================
             Configuration
===========================================
     This code is linked with opencv. please install opencv and setup the paths before including the code. 
     The program needs to link with opencv libralies; opencv_core, opencv_imgproc, opencv_highgui
     
     
     
     

===========================================
               Example
===========================================

