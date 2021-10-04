# Machine Learning on an STM32 Microcontroller
Classifying a person's actions (opening right hand, opening left hand, opening both hands, closing both hands) based on real motor imagery electroencephalogram (EEG) data on an STM32 microcontroller and the Gapuino board using Python and C++, achieved classification accuracy of 40%

## Description of Project
The `Source_files` directory includes the source code which was used to prepare the dataset by processing the raw EEG data and then setting up many different machine learning models based on Convolutional Neural Networks (CNNs) which performed classification tasks to predict which action the person was taking at any point in time.\

The `Models` directory includes the parameters of the selected CNN models for tensorflow in order to be able to import them to the STM32Cube IDE and run the model on the STM32 microcontroller.\

The `Datasets` directory includes the extracted datasets with the features extracted from the EEG data, which were used to perform classification with the machine learning algorithms.\

The `TensorFlow_Lite` directory includes the required files to run the selected CNN on the STM32 microcontroller using the STM32Cube IDE.\

All the other files include the results of the models' evaluation as well as some information on the final presentation.\

