# CSC413-2022W-project

Note to readers: 

The Jupyter Notebook file for implementing Vit and CNN with saliency map visualization requires running under "Kaggle notebook", with "Intel Image CLassification" dataset 
loaded. You can open the notebook on Kaggle directly by following this link: https://www.kaggle.com/code/jingyuhualpha/csc413-vit-cnn-on-intel-image-classification/.

In the notebook "Input" section, there is also a folder called "model-states" which contains trained model dicctionaries. Code for loading these dictionaries are already implemented
and can be found in the code below. Simply comment/uncomment the lines of code to decide which model to load for. 
![image](https://user-images.githubusercontent.com/93051054/164500957-e5af98e1-4036-472d-bfc1-9398f2952a0b.png)

Among many failed training for vision transformer, our group did succeed in finding a well-trained vision transformer model which also achieved an accuracy of around 85%. This
model's state distionary is stored in "../input/model-states/VIT_model_state.pt" of Kaggle Input section. However by visualizing the saliency map, this model also evaluates
images in patch-wise style, just the number of higher activation patches is increased and mostly focused in regions strongly associated with the classification classes. 
