# Gender-Recognition-by-Voice

Project aims to predict the gender of participants based on a set of data by using Signal Processing and Machine Learning Toolboxes.

## Training Data
Training data can be found at:
https://www.kaggle.com/primaryobjects/voicegender
 
## Basic Usage 
* .m files should be opened with MATLAB. 
* Datasets should be in the same path with the code, if not path of the datasets must be set manually or fixed in the code.
```
voicedata = readtable('voice.csv');
```
* Project consists a for loop for calculating the average accuracy for a number of iterations. Hence it will take longer time to perform calculations, it is initially set to zero. You can change it if you want to calculate the average/general accuracy score.

## Authors
* **Özlem Körpe** - *Initial work* - [ozlemkorpe](https://github.com/ozlemkorpe)
