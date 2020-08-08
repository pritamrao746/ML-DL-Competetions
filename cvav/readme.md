```
Team Name : The Alphas

Authors : Ashay Ajbani and Pritam Rao

Competition Type : Image Classification

Solution Type : Transfer Learning and  Ensembling

Number of Classes : 2

Pretrained Models Used : VGG16 and NASnet Large

Private Leaderboard Rank : 36/10000
```

The competition was hosted on ```https://www.analyticsvidhya.com/```.
The task was to classify vehicles into emergency and non-emergency categories.

### Our Approach
We trained 5 models using tranfer learning and ensembled them to make final predictions. 

**Models** : 

* Model 1 : Fine Tuning VGG16 
* Model 2 : Fine Tuning VGG16 with l2 regularization 
* Model 3 : k-fold validation 
* Model 4 : Fine Tuning NASnet 
* Model 5 : Fine Tuning NASnet with l2 regularization


The predictions taken by ensembling above 5 models
resulted in an accuracy greater than any of the individual models. 

Techniques used to reduce overfitting : 
* Data Augmentation 
* BatchNormalization 
* Dropout 
* l2 Regularization 
 

**Accuracy** : 
<ul>
<li> Model 1 : 0.9498 </li>
<li> Model 2 : 0.9546 </li>
<li> Model 3 : 0.9444 </li>
<li> Model 4 : 0.9548 </li>
<li> Model 5 : 0.9514 </li>
<li> After Ensembling (final) : 0.9688 </li>
</ul>

You can checkout Aashay's github profile at ```https://github.com/ashay36```
