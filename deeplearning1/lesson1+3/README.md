# Dogs vs Cats Transfer Learning

Using the VGG16 model as a base learn new classes

## [DataPreparation.ipynb](DataPreparation.ipynb)

Images from directories converted to TFRecord format

## [DogsVsCats.ipynb](DogsVsCats.ipynb)

* Use custom Tensorflow Estimator that uses the VGG16 model as a base
* Use `TFRecordDataset` as base for dataset in required input function
* Use Tensorflow Experiment to train and evaluate model