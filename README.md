# Traffic-Signs-Detector
Computer Vision course, Spring 2023

### Goal
Create road signs detector with SIFT and ViolaJones algorithms

### Language
```Python```

### Contents
1. Problem definition
2. Related Work
3. Methodology (SIFT, ViolaJones)
4. Evaluation
   
### Libraries
* ```opencv```
* ```scikit-learn```
* ```scipy```
* ```cv2```
* ```matplotlib```
* ```pandas```
  
### Conclusion
Along this project, I have developed in Python
two methods used to detect road signs and classify
them between four categories on pictures. I first
developed the SIFT algorithm, an old but quite robust method which is used to find similarities between
two pictures. The results are pretty good on the testing dataset with an accuracy varying between 60 and
75%, even though the confusion matrix we obtain
should suggest trying the model with other training
datasets. Then, I also developed the Viola-Jones
algorithm, with similar results. But, even with a 60%
- accuracy, the confusion matrix obtained seem a little bit better than for the SIFT model, with, in particular, significantly better results on all categories except the ”Road Sign” one, which is dominant in our dataset and explains the medium accuracy rate.
