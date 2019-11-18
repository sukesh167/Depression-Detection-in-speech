# CNN coupled with SVM

##### Project that Uses PyTorch and SciKitLearn to build a network that uses CNN as feature extractor and SVM as classifier

The preprocessed images from 'final_image_data' after audio cleaning is used to trin and test the network, it can be used for classification in other datasets as well.

[GoogleNet](https://ai.google/research/pubs/pub43022) is imported from pretraied models in torch vision package and the feature vectors are fed to an SVM with linear kernal  which classifies the images(as feature vectors) into two classes
