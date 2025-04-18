# Efficient labeling of a solar flux emergence video dataset by a deep learning model
Code from our article ['Efficient labelling of solar flux evolution videos by a deep learning model'](https://www.nature.com/articles/s41550-022-01701-3) to create model-ensemble through training-validation combination and dropouts.

Evaluated uncertainty on test set using model-ensemble is shown below-
<p align="center">
<img width="800" src="Figure4.jpg">  
</p>

Using model ensemble we also identify epoch of emergence as below (look for blue to red transition)-
<p align="center">
<img width="800" src="frame_overlay_animation3.gif"/img>  
</p>

### Requirements
Below are the package versions used in writing the code. 

Python 3.7.10

tensorflow                                                            
'1.15.2'

keras                                                             
'2.2.4-tf'

matplotlib                                                      
'3.2.2'

numpy  
'1.19.5'

cv2
'4.1.2'

csv
'1.0'
