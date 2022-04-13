# Yolor-EarthVision-Small-Scale-Dataset
Implentation of Yolor algorithm on Our own created dataset named "EarthVision Small Scale Dataset"

   **YOLOR(You Only Learn One Representation)** is a state-of-the-art machine learning algorithm for object detection, different from YOLOv1-YOLOv5 due to the difference in    authorship, architecture, and model infrastructure. In YOLOR, the algorithm basically benefits because of the combination of both explicit and implicit knowledge. We    have used Yolor to detect objects in aerial images by creating our own EarthVision Small Scale dataset which contains categories such as Airplane, Bridge, Vehicle,      Playground, Water-bodies. We have achieved **Accuracy** of over **76%**, **Precision** of **84%**, and **Recall** of over **86%**.
   
   
### Samples of testing images on EarthVision Small-Scale dataset:
![image](https://user-images.githubusercontent.com/65994527/163103236-0c0da6a0-a750-4497-b7f6-3396a8c1bed2.png)



| **Attributes**     | **Values** |
|--------------------|------------|
| Total dataset size | 700 images |
| Training images    | 490        |
| Validation images  | 140        |
| Testing images     | 85         |
| epochs             | 300        |
| batch_size         | 10         |



### Confusion Matrix for all classes below: 
| N = 85 samples  | Predicted Positive | Predicted Negative | Total |
|-----------------|--------------------|--------------------|-------|
| Actual Positive | 60 (TP)            | 9 (FN)             | 69    |
| Actual Negative | 11 (FP)            | 5 (TN)             | 16    |
| Total           | 71                 | 14                 | 85    |


EarthVision Small-Scale Dataset available at Roboflow, the link to access the dataset is:  


# Acknowledgment
    •	https://github.com/WongKinYiu/yolor
