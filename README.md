# ScaleRobustClassifier
This is a pythonic classifier that is designed to classify topographic and bathymetric sediment wave features. 
All segments and image derivatives are derived using eCognition Developer. The goal here is to create a classifier
that is robust to changes in the spatial resolution of image data as long as the feature of interest maintains a 
high feature resolution. This code is powered by the sci-kit learn library in python. Any image derivatives used 
within this process were extracted from Multibeam bathymetry. This classification workflow can also be applied to 
terrestrially acquired DEMs, with the implication of a seamless habitat map. 

