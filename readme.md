# NLP Model Performance Analysis

## L2 Regularization
- **Accuracy**: 0.8192
- **Loss**: 0.4624
- **Validation Accuracy**: 0.8257
- **Validation Loss**: 0.5552

## Best Validation Accuracy So Far
- **Accuracy**: 0.8433
- **Total Elapsed Time**: 00h 04m 59s
- **Best Number of Hidden Layers**: 7
- **Best Number of Neurons per Layer**: 125
- **Best Learning Rate**: 0.0011
- **Best Activation Function**: ReLU
- **Best Dropout Rate**: 0.4884

## Results with Different Optimizers and Activation Functions
- **Accuracy**: 0.8308
- **Loss**: 0.3795
- **Validation Accuracy**: 0.8527
- **Validation Loss**: 0.3449

## Best Validation Accuracy with Different Optimizers and Activation Functions
- **Accuracy**: 0.8469
- **Total Elapsed Time**: 00h 07m 53s
- **Best Number of Hidden Layers**: 5
- **Best Number of Neurons per Layer**: 126
- **Best Learning Rate**: 0.0020
- **Best Activation Function**: Tanh
- **Best Optimizer**: Nadam
- **Best Dropout Rate**: 0.0179

## Performance Degradation with L2 Regularization (0.01)
- **Accuracy**: 0.5020
- **Loss**: 0.6932
- **Validation Accuracy**: 0.4952
- **Validation Loss**: 0.6932

## Performance with RMSprop Optimizer
- **Accuracy**: 0.6515
- **Loss**: 0.6096
- **Validation Accuracy**: 0.8494
- **Validation Loss**: 0.3647

## Performance with Leaky ReLU (Alpha = 0.1)
- **Accuracy**: 0.9533
- **Loss**: 0.1271
- **Validation Accuracy**: 0.8140
- **Validation Loss**: 0.5616

## Performance with Batch Normalization and ReLU Activation
- **Epoch**: 3/3
- **Accuracy**: 0.9113
- **Loss**: 0.2317
- **Validation Accuracy**: 0.8666
- **Validation Loss**: 0.3472

## Performance with ReLU Activation and He Initialization
- **Epoch**: 3/3
- **Accuracy**: 0.9406
- **Loss**: 0.1615
- **Validation Accuracy**: 0.8692
- **Validation Loss**: 0.3750

## Performance with LeakyReLU Activation and He Initialization
- **Epoch**: 3/3
- **Accuracy**: 0.9446
- **Loss**: 0.1476
- **Validation Accuracy**: 0.8638
- **Validation Loss**: 0.4199
