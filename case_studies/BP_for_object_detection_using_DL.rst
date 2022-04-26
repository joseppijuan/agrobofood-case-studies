Best practices for object detection using deep learning techniques
==================================================================

1)	Problem identification
"""""""""""""""
Image classification vs Object detection vs Semantic segmentation vs instance segmetnation

2)	Data Labelling
"""""""""""""""
a. Automatic vs reliable labelling (based on domain experts)
b. Assessment on data quality (classification consistency among domain experts)

3)	Exploratory Data Analysis
"""""""""""""""
Identification of basic characteristics (instance counts per image, object size per category, morphological features...)

4)	Available computational resources
"""""""""""""""
a.	CPU vs GPU
b.	On premise or on cloud
c.	Deep learning architecture/model selection

5)	Data balancing by categories
"""""""""""""""
Similar number of instances per category to prevent problems derived from imbalancing

6)	First vainilla traning
"""""""""""""""
No image augmentation

7)	Metric evaluation
"""""""""""""""
Precision, recall & confusion matrix

8)	Continuous improvement
"""""""""""""""
a.	Data augmentation & retraining
b.	Hyperparameter tunning and Test Time augmentation exploration
