# Dog Breeds Classifier

## Motivation

The purpose of this project is to use a convolutional neural network (CNN) to predict dog breeds. The main object is to evaluate an image then a prediction of which dog breed the dog is, or which dog breed the human most resembles. If the image is detected as neither a dog nor a human, the classifier will not run.


## File Descriptions 
- dog_app.ipynb is a Jupyter notebook, contains the whole project code to create a dog breed classifier.
- The images folder includes all images used for this project.
- The saved_models folder contains the models saved during this project


## Achievements 

During the test phase the model achieve the accuracy: 82.1770%

### Model

![Model](./images/model.png)

### Model Accuracy

![Model Accuracy](./images/model_accuracy.png)

### Model Loss

![Model Loss](./images/model_loss.png)



## Results 

To check the results I have used:

#### 3 Images from Humans

![Human Test 1](./images/human_test_1.png)

![Human Test 2](./images/human_test_2.png)

![Human Test 3](./images/human_test_3.png)


#### 6 Images from Dogs

![dog Test 1](./images/dog_test_1.png)

![dog Test 2](./images/dog_test_2.png)

![dog Test 3](./images/dog_test_3.png)

![dog Test 4](./images/dog_test_4.png)

![dog Test 5](./images/dog_test_5.png)

![dog Test 6](./images/dog_test_6.png)

## Required Libraries <a name="libraries"></a>

- Pandas, NumPy, Scikit-learn, tqdm
- Matplotlib, ImageFile
- Keras, cv2
- Glob library 


## Acknowledgements <a name="acknowledgements"></a>

The below links, were very useful for completing the projects,
- https://keras.io