# Examples for TF-TRT

[TF-TRT](https://docs.nvidia.com/deeplearning/dgx/integrate-tf-trt/index.html)
(TensorFlow integration with TensorRT) is a part of TensorFlow
that optimizes TensorFlow graphs using
[TensorRT](https://developer.nvidia.com/tensorrt).

This repository contains a number of different examples
that show how to use TF-TRT.

## Examples

* [Image Classification](tftrt/examples/image-classification)
* [Object Detection](tftrt/examples/object_detection)


### Top-1 Accuracy

TF Model Link  | TF FP32 (Volta and Turing) | TF-TRT FP32 (Volta and Turing) | TF-TRT FP16 (Volta and Turing) | TF-TRT INT8 (Volta) | TF-TRT INT8 (Turing) |
:-------------:|:-----------------------------------------:|:------------------------------:|:------------------------------:|:-------------------:|:--------------------:|
MobileNet v1	 |71.01|71.01|70.99|69.45|69.42|
MobileNet v2   |74.08|74.08|74.07|73.87|73.9|
NASNet - Large |82.72|82.71|82.7|Work in progress|82.66|
NASNet - Mobile|73.97|73.85|73.87|Work in progress|73.35|
ResNet50 v1    |75.9|75.9|75.92|68.19|68.19|
ResNet50 v2    |76.06|75.98|75.96|71.09|71.07|
VGG16          |70.89|70.89|70.91|70.84|70.78|
VGG19          |71.01|71.01|71.01|70.82|70.9|
Inception v3   |77.99|77.99|77.97|77.86|77.85|
Inception v4   |80.19|80.19|80.19|79.21|Work in progress|


## License

[Apache License 2.0](LICENSE)
