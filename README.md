# Wei-Jie Wang's Bachelor Project

Thank you for visiting this repository.

## howells_prediction

This folder contains Howells et al.'s predictions in six JSON files.

## test_images

This contains 90 test images.

## trained_models

In this folder, there is one pytorch model that was the best performing one during 100 epochs.   
And, there are three quantized models that were originally from the pytorch model.

## training_result_images

This folder contains several images that show the model training results.

## true_labels_and_prediction_results

In this folder there are 5 excel files.
- **true_label:** It contains the true values and angles of the test images 
- **howells_prediction:** It contains both the true labels and the predicted results from Howells et al.
- **quantization_dynamic:** It contains both the true labels and the results from the dynamic quantized model.
- **quantization_float16:** It contains both the true labels and the results from the float16 quantized model.
- **quantization_16x8:** It contains both the true labels and the results from the 16 activation and 8 weight quantized model.

## Google Drive
https://drive.google.com/drive/folders/1ONyU1p6EDwMY8ug632hYzcuPlLoNHgDo?usp=sharing  

#### Training and Validation Data

If you are looking for the training and validation data that I used for this project, then please go to the Google Drive and visit the **Train Validation Test Data** folder.

#### Original Videos

If you are looking for the original videos that Howells et al. provided, then please visit **Howells et al. Meter A and Meter B videos** folder.