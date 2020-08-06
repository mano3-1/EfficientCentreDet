# EfficientCentreDet
This is a hybrid variety of detection models which is inspired from bothe centrenet and EfficientDet. This model is as fast as centrenet and much accurate due to the fusion blocks. The model is designed such that it can detect small and medium objects accurately.
## Data
This model is trained on the wheat data which is available in kaggle.<br/>
You can find the data here : https://www.kaggle.com/c/global-wheat-detection/data
## objectives
1. Speed along with accuracy
2. Detecting small objects 
## Highlights
1. Bi-fpn blocks in the architecture to ensure good fusion of higher and lower level feature vectors.
2. Loss is penalized such that model learns smaller objects better.
3. Both NMS and maxpooling can be used with this model.(NMS gave better results than maxpooling.)
4. Adding noise drastically increased performance.
## Improvements that can be done
Splitting the data in a startified way. Considering, the height of bounding box to height of image or width of bounding box to width of image as parameter and splitting the data and ensembling the models might improve the performance.
## Results
!['Result1'](https://github.com/mano3-1/EfficientCentreDet/blob/master/Results/result1.jpeg)
!['Result2'](https://github.com/mano3-1/EfficientCentreDet/blob/master/Results/result2.png)
!['Result3'](https://github.com/mano3-1/EfficientCentreDet/blob/master/Results/result3.png)
