# MiniTorch Module 3

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html

# Training Log

## Simple Dataset

### Training with CPU (FastOps)
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 200
* Batch size: 50

#### Training Result
* Time per epoch: 0.091s
* Correct: 148/150
* Loss: 2.6133

<img src="/assets/images/simple_cpu.png" width="50%">
<img src="/assets/images/simple_loss_cpu.png" width="50%">
<img src="/assets/images/simple_log_cpu.png" width="50%">

### Training with GPU (CudaOps)

## Split Dataset
### Training with CPU (FastOps)
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 200
* Batch size: 50

#### Training Result
* Time per epoch: 0.100s
* Correct: 148/150
* Loss: 7.2633

<img src="/assets/images/split_cpu.png" width="50%">
<img src="/assets/images/split_loss_cpu.png" width="50%">
<img src="/assets/images/split_log_cpu.png" width="50%">

### Training with GPU (CudaOps)

## XOR Dataset
### Training with CPU (FastOps)
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 300
* Batch size: 50

#### Training Result
* Time per epoch: 0.087s
* Correct: 144/150
* Loss: 8.2335
<img src="/assets/images/XoR_cpu.png" width="50%">
<img src="/assets/images/XoR_loss_cpu.png" width="50%">
<img src="/assets/images/XoR_log_cpu.png" width="50%">

### Training with GPU (CudaOps)

## Training Big Model - XOR Dataset
### Training with CPU (FastOps)
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 300
* Batch size: 50

#### Training Result
* Time per epoch: 0.160s
* Correct: 142/150
* Loss: 7.7792
<img src="/assets/images/XoR_big_cpu.png" width="50%">
<img src="/assets/images/XoR_big_loss_cpu.png" width="50%">
<img src="/assets/images/XoR_big_log_cpu.png" width="50%">

### Training with GPU (CudaOps)
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 300
* Batch size: 50

### Instructions

You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/tensor.py minitorch/datasets.py minitorch/testing.py minitorch/optim.py