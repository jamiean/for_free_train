# For_Free_Training

### Prerequisites

To install all the requirements plus tensorflow for multi-gpus run:

```
pip install -r requirements/gpu.txt
```

## Run without trades

Direct to folder free_train_adv, then run the following commands.

For CIFAR 10,

```
python free_train.py -m 8 -d CIFAR10
```

For CIFAR 100,

```
python free_train.py -m 8 -d CIFAR100
```

## Running with trades

First, direct to folder free_train_adv_trades, then run the following commands.

For CIFAR 10,

```
python free_train.py -m 8 -d CIFAR10
```

For CIFAR 100,

```
python free_train.py -m 8 -d CIFAR100
```

## More Settings

If you want to change batch size to 64 of your CIFAR run without trades, do:

```
python free_train.py -m 8 -d CIFAR10 -b 64
```

Same can be apply to any CIFAR 10/100, TRADR or not combination.


## Original Code Github

[free_adv_train](https://github.com/ashafahi/free_adv_train) for original code.

