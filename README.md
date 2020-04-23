Based on Tensorflow==1.14

Training instructions:

python3 train_net.py --help
usage: train_net.py [-h] [-p [PATH]] [--pre_trained PRE_TRAINED]
                    [-b BATCH_SIZE] [--epochs EPOCHS]

Training options.

optional arguments:
  -h, --help            show this help message and exit
  -p [PATH], --path [PATH]
                        Path to Training data
  --pre_trained PRE_TRAINED
                        Use pretrained ResNet50 model from TensorNets? False
                        by Default
  -b BATCH_SIZE, --batch_size BATCH_SIZE
                        Batch size to use
  --epochs EPOCHS       number of epochs to train the model for