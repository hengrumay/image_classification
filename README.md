 
A recent project saw me dive _quickly_ into convolutional neural networks and I implemented a proof of concept within a week. 

## Detecting buildings in satellite imagery with deep-learning  

• Developed and trained [Convolutional Neural Networks (CNNs)](http://cs231n.github.io/convolutional-networks/) using [Keras](https://keras.io/) with [TensorFlow](https://github.com/tensorflow/tensorflow) backend to detect buildings in a highly unbalanced set of *proprietary* satellite images and generated an interactive visualization of the holdout image classification outcomes (~93% accuracy) using geospatial information embedded in the geotiffs;  

• Further explored [image segmentation](https://en.wikipedia.org/wiki/Image_segmentation) using computer vision techniques to delineate building outlines in images;  

• CNNs were trained on [AWS GPU](https://aws.amazon.com/ec2/instance-types/) enabled instance and the interactive visualizations employed [Geopandas](http://geopandas.org/), [GDAL](https://en.wikipedia.org/wiki/GDAL), [Matplotlib](https://matplotlib.org/) and [Folium](https://folium.readthedocs.io/en/latest/index.html) Python modules  

Python scripting files are found in [docs](https://github.com/hengrumay/image_classification/tree/master/docs)
