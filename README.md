# Digits_Classifier
This is a basic CNN architecture model used to classify the gray scale digits dataset to get the intuition of how CNN works


The CNN Architecture:

             +--------------------------+
             |       Input Layer        |
             |     Shape: (8, 8, 1)     |
             +--------------------------+
                        |
                        v
             +--------------------------+
             |     Conv2D Layer         |
             |  Filters: 64, Kernel: 3x3|
             |    Activation: ReLU      |
             +--------------------------+
                        |
                        v
             +--------------------------+
             |   MaxPooling2D Layer     |
             |    Pool Size: 2x2        |
             +--------------------------+
                        |
                        v
             +--------------------------+
             |      Flatten Layer       |
             +--------------------------+
                        |
                        v
             +--------------------------+
             |       Dense Layer        |
             |    Units: 50, ReLU       |
             +--------------------------+
                        |
                        v
             +--------------------------+
             |      Output Layer        |
             |    Units: 10, Softmax    |
             +--------------------------+

