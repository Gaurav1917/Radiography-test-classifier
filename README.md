# Radiography-test-classifier
## Dataset:
  ### Kaggle: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

## VGG19 Model: 
### https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg19/VGG19

## Explanation about the project:

        The dataset has two parts(Train,Test).The training dataset has two classes (Lungs Disease,Normal), 
        the total images in training dataset is 16204. 
        *Training Data(images): 
        Normal - 8203, Lung Disease - 7063  
        *Test Data(images): 
        Normal - 1795, Lung Disease - 1695

The model is made by using CNN(convolutional neural network). As we don’t have a large dataset so ,either you can generate image from ImageDataGenerator or use transfer learning ,here we used technique Transfer learning(VGG19 model) . The training accuracy we got from the model is 99.552% and test accuracy is 99.537%.

For deployment we used a gradio interface: https://www.gradio.app/docs/interface 
 ,also we used huggingface for deployment.

## Visualisation
### VGG19 Model

![download](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/6d7c09b8-34b5-44af-803a-95ea5c0a7c44)

![download (1)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/f4cc20ee-00a8-44e0-8d6c-1e3b7599c506)

![download (2)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/c338d20c-d77c-40d1-8583-2c542d3e0b8e)

### Dense layer

![download (3)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/6c75be32-7dad-4eb6-8b9f-802c0a1ab112)

![download (4)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/ac89e442-91dc-489e-bd53-5c961737ec09)

### Accuracy plot

![download (5)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/bcb10ed2-2c61-4eb7-a8e6-805ab04bd54a)

![download (6)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/96f2b8f0-d341-4a8c-941f-67367c3850ad)

### Confusion matrix

![download (7)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/0937993d-7582-4223-8948-95500c240fc2)

## Sample output/testing:

![Screenshot (24)](https://github.com/Gaurav1917/Radiography-test-classifier/assets/146158309/dd8de7c8-c3ab-4a27-9e41-ff153911279c)

### Link for testing:
#### https://huggingface.co/spaces/Gaur1917/Chest-X-rays








