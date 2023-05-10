# INT2Flowers102
INT2 coursework on the flowers-102 dataset
# Contributions

## 27/04/2023
Jack Vickers and Harry Hillman
Set up the colab notebook

## 28/04/2023
Jack Vickers
Modified the notebook and added code which randomly displays one of the images from the training dataset along with its label

## 29/04/2023
Jack Vickers
Set up an initial neural network on 29/04/2023 and ran the training for 150 epochs. The final accuracy was 0.4%


## 05/05/2023
Jack Vickers
Added code which augments the training data in more ways
Combine all the the augmented training data with the original training data to give more images to train with
Rewrote the train and evaluation loops
Use the validation dataset in the training loops
Started 4 different training loops with different hyperparameters to see which is the best

## 05/05/2023
Nurdina Syahrul Izwan
Began writing the abstract in the report

## 06/05/2023
Jack Vickers
Changed the layers in the neural network
Added more convolutional layers
Added batchnorm2ds which happen after each convolutional layer
Adjusted the size of the images so they are not too big to process
Corrected some issues in the training and evaluation functions

## 06/05/2023
 Harry Hillman
Changed colour augmentation, in order to get more accurate results
Added Dropout Layer (made a massive difference in accuracy)
Increased amount of data included in the training, by making more transformed data.
Current Accuracy Peak: 53%
Added RMSprop optimiser.

## 06/05/2023
Jack Vickers
Worked with Harry to change the colour augmentation
Originally the colour augmentations were making substantial changes to the images so flowers were looking completely different which likely made the network struggle to classify them, so the augmentations were changed so that they had less of an affect on the colour of the pictures
Trained a few different variation of the model and achieved a peak of 43.8% test accuracy

## 07/05/2023
 Nurdina Syahrul Izwan
Started working on the Introduction section of the report
Finished the Abstract section 

## 07/05/2023
Jack Vickers
Made of copy of the shared code file so adjustments could be made which do not affect the original file
Adjusted the function that calculates the mean and standard deviation of the dataset so that it correctly calculates the standard deviation
Added the mean and standard deviation to all the transforms.Normalize transformations
Adjusted the colour jitter transformations


## 07/05/2023
Harry Hillman
Made of copy of the shared code file so adjustments could be made which do not affect the original file
Added more convolutional layers
Trialled new optimisation algorithms

## 08/05/2023
Jack Vickers
Simplified the structure of the neural network to try and reduce overfitting
Adjusted the image augmentation and added random erasure and gaussian blur transforms to try and reduce overfitting
Added a learning rate scheduler to try and reduce overfitting

## 08/05/2023
Aisyah Firoz Khan
Created the documents for the writeup of the report
Started working on the Results and Evaluation
Finished working on Results and Evaluation

## 08/05/2023
Harry Hillman
Changed batch size to 128 to experiment
Added CentreCrops
Adjusted image transformations

## 09/05/2023
Harry Hillman
Wrote all of the method section for the write up
Reran code multiple times, varying epoch count/batch size
Adjusted image tranformations

## 09/05/2023
Jack Vickers
Adjusted the image augmentation to try and achieve a greater accuracy
Added to various sections of the report (method, results and evaluation, conclusion)
Made a diagram of the neural network’s architecture and added it to the report
Ran the training after adjusting the augmentations and achieved a new highest accuracy of 48.8%

## 09/05/2023
Aisyah Firoz Khan
Wrote the majority of the conclusion of the report

## 09/05/2023
 Nurdina Syahrul Izwan
Wrote the majority of the results and evaluation section of the report
Finished the introduction of the report

