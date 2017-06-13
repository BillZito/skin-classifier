# Identifying skin cancer with convolutional neural networks #

### 1. Clone and initialize your repo ###
```
git clone https://github.com/billzito/skin-classifier
cd skin-classifier
floyd init skin-classifier
```

### 2. Run the jupyter notebook with floydhub ###
```
floyd run --mode jupyter --gpu --data QtQVc9nVrnDiPsxrZuK5Qd
```
Note:

-I uploaded the 531 moles for classification to Floydhub, and that is their unique data id.

-The --gpu flag uses gpu to run the CNN, which will be much faster


### 3. In the notebook, select Cell/Run All ###
