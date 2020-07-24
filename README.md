# Gender-Recognition-by-Voice

Project aims to predict the gender of participants based on a set of data by using Signal Processing and Machine Learning Toolboxes.

## Part I: Gender Recognition with Machine Learning 
### Training Data
Training data can be found at:
https://www.kaggle.com/primaryobjects/voicegender
 
### Basic Usage 
* .m files should be opened with MATLAB. 
* Datasets should be in the same path with the code, if not path of the datasets must be set manually or fixed in the code.
```
voicedata = readtable('voice.csv');
```
* Project consists a for loop for calculating the average accuracy for a number of iterations. Hence it will take longer time to perform calculations, it is initially set to zero. You can change it if you want to calculate the average/general accuracy score.

## Part II: GUI for Voice Recording and User Operations

This part handles the user interactions with GUI which enables recording audio, plotting audio graph, calculate necessary measurements, play audio and gender recognition.

![GUI](https://github.com/ozlemkorpe/Gender-Recognition-by-Voice/blob/master/screenshots/plot.png)


## Authors
* **Özlem Körpe** - *Initial work* - [ozlemkorpe](https://github.com/ozlemkorpe)
