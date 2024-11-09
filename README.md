# Snake_Classification

## INTRODUCTION
Snakebites pose a severe public health issue, particularly in regions with high populations of venomous snakes. Snakebites kill anestimated 81,000 to 138,000 people per year worldwide, mostly in rural and impoverished areas, according to the WHO. Another400,000 people are left permanently injured, with amputated limbs, blindness, or other severe disabilities due to the venom's effectsRevolutionizing snakebite management with AI-driven snake identification. Quick and accurate snake species identification is needed toadminister proper medical care and reduce mortality and morbidity.

## DATA SUMMARY:
This dataset contains 1788 png images of snake Venomous & Non Venomous.The images are grouped into 2 classes. There are 1590 images in 1 class & 198 in second class.

### Classes
Venomous 
Non Venomous

## Task : Binary  Classification

## WE DEVICE THIS PROJECT INTO MULTIPLE STEPS
1. Importing library
2. Make subset of training,testing & validation
3. Data Processing [Prepare training and testing data]
4. Visualise Training Images
5. Build Arcitecture
6. Model Compilation
7. Training
8. Evaluation
9. Model saving
10. Prediction
11. Testing
12. Visualise Test Images

## LODING DATA / PREPARING DATA
* Make a subset of data into three parts train, test, and validation with the help of split folder library.

## Build Architecture 
1. Total params: 409,153 
2. Trainable params: 409,453
3. Non-trainable params: 0
* Use flatten layer to convert output into 1D array
* Use sigmoid activation function at last FCNN layer because only 2 classes are present.

## Results 

MODEL COMPILATION & TRAINING & EVALUATION:
•	Use binary cross_entropy and adam optimaizer to compile a model

•	Train model on 50 epochs, and plot training, validation accuracy as well as loss and validation loss

•	After evaluating the model 

Train Accuracy & Loss: [0.6162,0.6599]

## MODEL SAVING:
* Save the model using h5

## PREDICTION & TESTING:
* Select the image from testing data for prediction after that convert
this image into array, and expand the diamension of image then
Select the maxarg and last making the prediction using if elase 
condition 

