# Classifying Leaf Diseases of Cotton Plants
### Flatiron Capstone
### Ian Haas


### Project Overview
Identify common diseases that manifest on the leaves of cotton plants by comparing images of infected plants with images of diagnosed plants to efficiently identify diseases and lead to faster application of correct treatment.

### Data
Leaf images data set: Easily classifiable, visually identifiable; leaves are more photogenic <br>
Cotton Plant: Valuable commodity and large component of agriculture industry <br>
Sample Data: /Cotton Plant Disease. Randomly selected example of each class from data set <br>

![6 Classes of Images](/Capstone/download.png)

Transfer learning with Keras and Tensor flow <br>
MobileNetV2<br>
Feature Extraction and Fine Tuning<br>

Random Transformation for training<br>
Loss: Cross Entropy , Accuracy<br>
Optimization: Adam Optimizer RMS Propagation<br>

![Accuracy and Loss](/Capstone/metrics.png)

### Results
Additional training data and tunining is needed to improve accurate output.<br>
Plant diseases that have a similar appearance may still be mistaken for each other.<br>

![Mistaken Output](Capstone/mistakenoutput.png)


![Accurate Output](/Capstone/armyworm.png)

### For the Future
Optimization: Improve model with more data<br>
Specialization: Tailor to individual farming operations and specific species and crops <br>
Versatility: Identification on individual basis, possibly with mobile devices in the field, as well as systemic identification through tools like drone photography
