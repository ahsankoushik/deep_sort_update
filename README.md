# Deepsort with latest scikit learn and tensorflow v2 

This repository was changed in 25 September 2023 while I was facing some problems running it with scikit-learn==1.3.1 and tensorflow==2.11.0 

After taking some help from the online forums like github and stack overflow i managed to run the this repo. So i am pushing this to help myself and others. 

Things I changed 
1. Scikit-learn 0.23 removed linear assignment due linear_assignment is included in scipy. Thus the import statement was changded and implement the linear_sum_assignment in [linear_assignmet.py](./linear_assignment.py)
2. And tensorflow 2 was implement instead of tensorflow 1 in [generate_detection.py](tools/generate_detections.py)