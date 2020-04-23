# Siamese-N-w-for-MARS-Dataset
Siamese Network for MARS(Motion Analysis and Re-identification Set) Dataset

Training Instructions:

Command: python3 train_net.py --help
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
