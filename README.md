# Detecting anomalies in system logs with compact convolutional transformer┬╣ 

┬╣ : Larisch, R., Vitay, J., Hamker, F.H. (2022)

### Dependencies

- python v3.9.7

- numpy >= 1.19.2

- matplotlib >= 3.4.2

-  Tensorflow >= v2.6.0

- Tensorflow-addons >= v0.15.0

- tqdm >= 4.62

- transformers >=4.15

  

### Structure

- cct.py: Definition of the Compact convolutional transformer 
- custom_loader.py: Function for preprocessing of the original log data
- evaluate.py: Evaluation on the test data
- train.py: Start the training of the CCT on the training data
- create_uniqe: Function to remove samples from the test set, which are in training set

### Data
 A pretrained model von Blue Gene/L data set with $4\times4$ convolutional kernels and a preprocessed Blue Gene/L training and test set can be found under:

10.5281/zenodo.7220404

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7220404.svg)](https://doi.org/10.5281/zenodo.7220404)
