# Section 2: Computer Vision

Contains the code for building and training a convolutional neural network on
the CIFAR-10 dataset.

The first time this code is run, the CIFAR-10 dataset will be downloaded for you. 

Brief file descriptions:
- `cifar10_estimator.py`: custom tf.estimator.Estimator implemention of the CNN. This is the main file that should be run. It uses `cifar10_input` to get the data and build the input pipeline, and uses `cifar10_model` to link the logits, loss, and training operations together in the custom estimator's `model_fn`.
- `cifar10_input.py`: contains the code for checking whether the user has the CIFAR-10 dataset, and downloading it for them if it is not found.
- `cifar10_model.py`: contains all the model-building code, such as the convolutional layers, the loss function, the optimizer, etc.

Example command to train the model:
```bash
./cifar_10_estimator.py --data_dir=$PWD/../data/cifar --batch_size=128
```