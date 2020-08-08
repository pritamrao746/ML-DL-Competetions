# Global Wheat Detection
```
Team Name : The Alphas

Authors : Pritam Rao and Ashay Ajbani

Competition Type : Object Detection

Number of Classes : 1

Pretrained Models Used : 
1) DETR (Submission 1)
2) Efficient Detector (Submission 2)

Public Leaderborad Rank : 858/2270

Current Private Leaderboard Rank : 870/2270
```

The competition was hosted on ```https://www.kaggle.com/c/global-wheat-detection```.
The task was to detect wheat heads in images and draw a bounding box around it.

## Our Approach

**Approach 1** :
 
For our first submission, we fine tuned pretrained *DETR* model for our problem. It gave us a 
score of 0.5758 on the public leaderboard. 

Refer the following notebooks in detr folder for detailed implementation:

 1) *wheat_detection_detr_training.ipynb* : Includes processing the dataset and training on detr.
 2) *wheat_detection_detr_inference.ipynb* : Making predictions on the test images using the trained model.



**Approach 2** : 

For our second attempt, we fine tuned pretrained *Efficient Detector* model for our problem.
It gave us a score of 0.7331 on the public leaderboard. We are still in the process of 
documenting the notebook.


You can checkout Aashay's github profile at ```https://github.com/ashay36```
