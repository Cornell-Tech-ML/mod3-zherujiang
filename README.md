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
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 500
* Batch size: 50

#### Training Result
* Time per epoch: 0.797s
* Correct: 150/150
* Loss: 1.3223
Epoch  10  loss  13.262209187553221 correct 136
Epoch  20  loss  9.416668025095028 correct 141
Epoch  30  loss  10.171094173141213 correct 143
Epoch  40  loss  6.144273666880221 correct 145
Epoch  50  loss  6.338275444197706 correct 147
Epoch  60  loss  5.315298202614823 correct 147
Epoch  70  loss  6.3532484481758456 correct 147
Epoch  80  loss  4.297244308942781 correct 148
Epoch  90  loss  6.131539233745611 correct 148
Epoch  100  loss  3.976840177208355 correct 148
Epoch  110  loss  3.0373080682170217 correct 149
Epoch  120  loss  4.314400773016098 correct 149
Epoch  130  loss  3.511654245270693 correct 149
Epoch  140  loss  4.704098435333334 correct 149
Epoch  150  loss  4.84005991537246 correct 149
Epoch  160  loss  3.2546175690645898 correct 149
Epoch  170  loss  3.0566685025653535 correct 149
Epoch  180  loss  3.997642634298782 correct 150
Epoch  190  loss  3.3274577664029414 correct 148
Epoch  200  loss  3.962327843114556 correct 148
Epoch  210  loss  5.161806310102181 correct 149
Epoch  220  loss  2.1079047836632614 correct 150
Epoch  230  loss  2.177955220083965 correct 150
Epoch  240  loss  3.9062136780463437 correct 148
Epoch  250  loss  3.1906409548167436 correct 150
Epoch  260  loss  2.5284227437670888 correct 149
Epoch  270  loss  2.2034935666005193 correct 150
Epoch  280  loss  4.243802052327457 correct 149
Epoch  290  loss  1.7189281843499877 correct 150
Epoch  300  loss  2.6690208484129507 correct 150
Epoch  310  loss  2.246076003943947 correct 150
Epoch  320  loss  3.3071195804550184 correct 149
Epoch  330  loss  2.5360937486645563 correct 150
Epoch  340  loss  2.203562190599043 correct 149
Epoch  350  loss  2.573090158122847 correct 150
Epoch  360  loss  2.762776240187227 correct 150
Epoch  370  loss  3.3576132997094033 correct 150
Epoch  380  loss  2.0554648428420315 correct 150
Epoch  390  loss  2.6279684758112096 correct 150
Epoch  400  loss  2.5097504659787084 correct 150
Epoch  410  loss  2.2144838926962986 correct 150
Epoch  420  loss  1.9180491355895386 correct 150
Epoch  430  loss  1.9297033460476634 correct 149
Epoch  440  loss  2.016608431141371 correct 150
Epoch  450  loss  1.935358596677633 correct 150
Epoch  460  loss  1.1970807599073305 correct 150
Epoch  470  loss  0.9662017141560335 correct 150
Epoch  480  loss  1.4550626708868193 correct 150
Epoch  490  loss  1.6711099939183105 correct 149
Epoch  500  loss  1.3223574739322064 correct 150
Time per epoch:  0.7969081153869629s

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
#### Model Parameters
* Number of points: 100
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 500
* Batch size: 50

#### Training Result
* Time per epoch: 0.521s
* Correct: 99/100
* Loss: 1.7115

Epoch  10  loss  12.434918714612413 correct 96
Epoch  20  loss  10.987760323938975 correct 96
Epoch  30  loss  10.583358455974302 correct 96
Epoch  40  loss  7.702080017033701 correct 96
Epoch  50  loss  6.415706986936865 correct 96
Epoch  60  loss  5.901910041371588 correct 98
Epoch  70  loss  4.615673023619884 correct 98
Epoch  80  loss  4.940653103376711 correct 98
Epoch  90  loss  5.6404829454739644 correct 98
Epoch  100  loss  4.424901680934736 correct 98
Epoch  110  loss  4.254901485659172 correct 98
Epoch  120  loss  5.3880779597945025 correct 99
Epoch  130  loss  4.774886572935284 correct 99
Epoch  140  loss  3.433912606183646 correct 99
Epoch  150  loss  3.0432262040399407 correct 99
Epoch  160  loss  2.7896922698085795 correct 99
Epoch  170  loss  4.827306587921807 correct 99
Epoch  180  loss  2.4078879382507674 correct 99
Epoch  190  loss  3.6203354068190716 correct 99
Epoch  200  loss  4.396458886365748 correct 99
Epoch  210  loss  2.0450155315294953 correct 99
Epoch  220  loss  2.884373428278798 correct 99
Epoch  230  loss  1.960623952698316 correct 99
Epoch  240  loss  2.0590238761776103 correct 99
Epoch  250  loss  3.1212010650980035 correct 99
Epoch  260  loss  1.3189152664715462 correct 99
Epoch  270  loss  2.7127620319746337 correct 99
Epoch  280  loss  2.4136157746858666 correct 99
Epoch  290  loss  2.205345407926015 correct 99
Epoch  300  loss  3.41613665954947 correct 99
Epoch  310  loss  2.022091964407795 correct 99
Epoch  320  loss  2.747145088493211 correct 99
Epoch  330  loss  2.8832100717296143 correct 99
Epoch  340  loss  2.0166800981869346 correct 100
Epoch  350  loss  2.019569205183759 correct 99
Epoch  360  loss  3.245031925279889 correct 100
Epoch  370  loss  2.725312784468276 correct 99
Epoch  380  loss  1.5520643033984673 correct 99
Epoch  390  loss  1.0528778075552534 correct 99
Epoch  400  loss  2.4574409166555355 correct 99
Epoch  410  loss  1.3199850379722 correct 100
Epoch  420  loss  1.7975769861485655 correct 99
Epoch  430  loss  1.6731806518116712 correct 99
Epoch  440  loss  1.2450589521721094 correct 99
Epoch  450  loss  0.9965329813089921 correct 100
Epoch  460  loss  1.350060232037304 correct 99
Epoch  470  loss  2.3731953451821033 correct 100
Epoch  480  loss  1.7422895471244024 correct 100
Epoch  490  loss  2.035818443717936 correct 100
Epoch  500  loss  1.711487965220122 correct 99
Time per epoch:  0.5208355765342713s

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
#### Model Parameters
* Number of points: 100
* Size of hidden layer: 100
* Learning rate: 0.05
* Number of epochs: 500
* Batch size: 50

#### Training Result
* Time per epoch: 0.523s
* Correct: 97/100
* Loss: 4.8475

Epoch  10  loss  24.8519267355222 correct 88
Epoch  20  loss  21.890465997652683 correct 88
Epoch  30  loss  20.027433172651516 correct 88
Epoch  40  loss  20.476473655912834 correct 90
Epoch  50  loss  16.779492547341906 correct 92
Epoch  60  loss  14.673046529985623 correct 92
Epoch  70  loss  16.312974902607998 correct 90
Epoch  80  loss  13.502664213366442 correct 92
Epoch  90  loss  15.21449017799693 correct 94
Epoch  100  loss  12.915720463019337 correct 94
Epoch  110  loss  12.293044591740935 correct 92
Epoch  120  loss  10.215260215600084 correct 94
Epoch  130  loss  11.03009857522236 correct 94
Epoch  140  loss  10.019816149494382 correct 94
Epoch  150  loss  11.323382152724584 correct 94
Epoch  160  loss  11.049438765590981 correct 94
Epoch  170  loss  10.10388014679021 correct 94
Epoch  180  loss  7.547354872388958 correct 94
Epoch  190  loss  10.057805546880182 correct 94
Epoch  200  loss  7.609268474399949 correct 94
Epoch  210  loss  7.9075112662500295 correct 95
Epoch  220  loss  10.230965928654909 correct 94
Epoch  230  loss  8.612783867617498 correct 94
Epoch  240  loss  7.66527779691888 correct 94
Epoch  250  loss  7.643342885427886 correct 94
Epoch  260  loss  7.946705942205567 correct 94
Epoch  270  loss  6.048573647707716 correct 94
Epoch  280  loss  7.109607103010665 correct 94
Epoch  290  loss  9.09455283686561 correct 95
Epoch  300  loss  6.1846439906509705 correct 94
Epoch  310  loss  6.6426469169610085 correct 95
Epoch  320  loss  8.131495195168977 correct 95
Epoch  330  loss  7.628988047172486 correct 94
Epoch  340  loss  7.5108856957739265 correct 95
Epoch  350  loss  3.850822007362755 correct 95
Epoch  360  loss  7.418223672648361 correct 96
Epoch  370  loss  4.367012114183443 correct 95
Epoch  380  loss  8.052063013510095 correct 97
Epoch  390  loss  7.079680357739138 correct 95
Epoch  400  loss  4.687085013110687 correct 96
Epoch  410  loss  6.387848023271869 correct 96
Epoch  420  loss  6.73205660878836 correct 96
Epoch  430  loss  6.712719442087073 correct 98
Epoch  440  loss  4.168085557982674 correct 97
Epoch  450  loss  7.702824431935882 correct 97
Epoch  460  loss  4.121436573500693 correct 97
Epoch  470  loss  5.875229435058945 correct 97
Epoch  480  loss  6.106633519056049 correct 97
Epoch  490  loss  6.9322980173625615 correct 97
Epoch  500  loss  4.847461218015787 correct 97
Time per epoch:  0.5225029020309448

## Training Big Model - XOR Dataset
### Training with CPU (FastOps)
#### Model Parameters
* Number of points: 150
* Size of hidden layer: 200
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