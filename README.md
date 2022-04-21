# CSC413-2022W-project

Note to readers: 

The Jupyter Notebook file "csc413-vit-cnn-on-intel-image-classification.ipynb" for implementing Vit and CNN with saliency map visualization requires running under "Kaggle notebook", with "Intel Image CLassification" dataset 
loaded. You can open the notebook on Kaggle directly by following this link: https://www.kaggle.com/code/jingyuhualpha/csc413-vit-cnn-on-intel-image-classification/.

In the notebook "Input" section, there is also a folder called "model-states" which contains trained model dicctionaries. Code for loading these dictionaries are already implemented
and can be found in the code below. Simply comment/uncomment the lines of code to decide which model to load for. 
![image](https://user-images.githubusercontent.com/93051054/164500957-e5af98e1-4036-472d-bfc1-9398f2952a0b.png)

Among many failed training for vision transformer, our group did succeed in finding a well-trained vision transformer model which also achieved an accuracy of around 85%. This
model's state distionary is stored in "../input/model-states/VIT_model_state.pt" of Kaggle Input section. Feel free to play with it and visualize the results using implemented code. 

The original notebook for "csc413-modified_VIT_on_small_dataset.ipynb" could be found following this link to Keras (https://keras.io/examples/vision/vit_small_ds/#implement-locality-self-attention), and this link to Google Colab (https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/vision/ipynb/vit_small_ds.ipynb). Thanks for "Aritra Roy Gosthipaty" who implemented the code using tensorflow. 

All experimental results could be found under "result" folder, which includes attention map visualizations amd loss graph for hyperparameter tuning
