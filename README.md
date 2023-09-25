# Deepsort with the latest scikit-learn and Tensorflow v2 

This repository was changed on 25 September 2023 while I was facing some problems running it with scikit-learn==1.3.1 and tensorflow==2.11.0 

After getting some help from online forums like GitHub and stack overflow I managed to run this repo. So I am pushing this to help myself and others. 

Things I changed 
1. Scikit-learn 0.23 removed linear assignment due to linear_assignment being included in scipy. Thus the import statement was changed and implement the linear_sum_assignment in [linear_assignmet.py](.deep_sort/linear_assignment.py)
2. And Tensorflow 2 was implemented instead of Tensorflow 1 in [generate_detection.py](tools/generate_detections.py)

[**The original README.md**](README_original.md)
[**The original repo**](https://github.com/nwojke/deep_sort)
