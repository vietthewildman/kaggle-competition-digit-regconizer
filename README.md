# DIGIT RECOGNIZER USING CNN
This project includes a model and a webapp for online testing.

## About the dataset:
The dataset is provided by MNIST ("Modified National Institute of Standards and Technology"). It's tens of thousands of handwritten images.<br/>
In my project, the dataset is loaded directly from keras. However, you can explore the dataset online [here](https://www.kaggle.com/competitions/digit-recognizer/data).<br/>
Each image is store in (28,28), with the respective label marked from 0-9.

## The project structure
### Model:
[Code](https://github.com/vietthewildman/kaggle-competition-digit-regconizer/blob/main/digit-regconizer-mnist-CNN.ipynb)<br/>
Deep Learning using CNN. You can quickly take a look at the saved model [here](https://github.com/vietthewildman/kaggle-competition-digit-regconizer/tree/main/saved_model).

### Webapp:
[Code](https://github.com/vietthewildman/kaggle-competition-digit-regconizer/blob/main/webapp-deployment.ipynb)<br/>

I have deployed a webapp for a quick interaction with the model. Users simply draw some separated digits and the model will do the predictions.<br/>
![webapp](https://user-images.githubusercontent.com/67698435/174094039-f345dbe8-6aec-4e81-9f2a-e2d9411ccfb1.PNG)
