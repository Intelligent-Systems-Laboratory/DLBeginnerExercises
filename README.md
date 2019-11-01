# DLBeginnerExercises

Deep Learning Exercises for Beginners using Keras (Tensorflow)

## Setup
- Anaconda (conda 4.7.11)
- Cuda (V10.0.130)
- Python 3.6

## Create new environment
```
conda create -n keras-gpu python=3.6 numpy scipy keras-gpu
```

## Activate new env
```
conda activate keras-gpu
```

## Test run setup

```
Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense (Dense)                (None, 512)               401920    
_________________________________________________________________
dropout (Dropout)            (None, 512)               0         
_________________________________________________________________
dense_1 (Dense)              (None, 512)               262656    
_________________________________________________________________
dropout_1 (Dropout)          (None, 512)               0         
_________________________________________________________________
dense_2 (Dense)              (None, 10)                5130      
=================================================================
Total params: 669,706
Trainable params: 669,706
Non-trainable params: 0
_________________________________________________________________
Train on 60000 samples, validate on 10000 samples
```

Run [mnist_mlp.py](https://github.com/Intelligent-Systems-Laboratory/DLBeginnerExercises/blob/master/mnist_mlp.py)

```python
python mnist_mlp.py
```

## Sample Output
[mnist_mlp_run.txt](https://github.com/Intelligent-Systems-Laboratory/DLBeginnerExercises/blob/master/mnist_mlp_run.txt)

## After verifying yoursetup, try this tutorial:

![KerasTutorialDeepLearninginPython.ipynb](https://github.com/Intelligent-Systems-Laboratory/DLBeginnerExercises/blob/master/KerasTutorialDeepLearninginPython.ipynb)
