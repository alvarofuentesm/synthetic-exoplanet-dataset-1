# Synthetic Exoplanet Dataset

## Files

* **data_train_full.csv**: 3350 examples for training and validation.

* **data_test_full.csv**: 373 examples for testing (include class label PC or NOT_PC). 

* **data_test_without_label.csv:** data_test_full without the class label. 

* **utils.ipynb:** Instructions to load .csv files as pandas DataFrame and load examples from GeneratedSamples folder.

*Note:* If the rows share the same *index* they correspond to the same example.


* **GeneratedSamples.zip**: Contains the folder GeneratedSamples. Available on: https://drive.google.com/file/d/1e4hNDq4p8VKehZl7i_kSe_EvVRQusCwk/view?usp=sharing

## Folder

* **GeneratedSamples**: All generated examples (PC and NOT_PC) stored in .npy files (curve, phase fold, local view and global view).




