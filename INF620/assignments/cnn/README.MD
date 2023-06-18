## Final work | Computational Intelligence

This repository contains files referring to the final work of the Computational Intelligence course (ELT 451) at UFV, which addresses a comparative analysis between the techniques of Convolutional Neural Networks (CNN) and Fuzzy Logic in the task of classifying images of static gestures in Libras.

The purpose of this work is to compare these two techniques regarding the recognition of static gestures applied to Libras.

#### Directories :file_folder:

* *dataset_full* : Contains the dataset used for training / validation and testing of the models.
* *models* : contains the model architectures.
* *outputs* : contains the files generated during the training and optimization phase of the models.
* *written_work* : contains the written work.
* *temp* : contains the crop generated at runtime by the [CNN_real_time_classifier.py](https://github.com/IureRosa/comp-Intelligence/TrabFinal/blob/master/CNN_real_time_classifier.py) script.


#### Requirements :bookmark_tabs:

To run the model training scripts it is necessary to have the dependencies, for that it is enough to install a dependency and environment manager, such as [Conda](https://docs.conda.io/en/latest/conda.html) and run the code below to import the environment with the dependencies used in the project.

* Import : ```conda env create -f environment.yml```

* Activate : ```conda activate machinelearning```

* Run the scripts normally in a Python IDE or via a terminal: ```python CNN_train.py ```