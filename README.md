# COVID-19-Real-Time-Facial-Mask-Detector
In the present COVID-19 scenario, it is imperative to wear a mask in a public areas. However there are no efficient programs so far which can automatically detect the presence of people violating the norm. Through this project, I built a Face Mask Detector using Keras and Tensorflow that yields a 99.78% accuracy with an inference time of 0.0085s on previously collated datasets. This makes it an excellent choice for use in real-time applications. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

# Technologies Used
* Keras
* Tensorflow
* OpenCV

# Dataset
The dataset used for our purpose is available at https://github.com/chandrikadeb7/Face-Mask-Detection

# Methodology
EfficientNet B0, is a new baseline network developed by performing a neural architecture search using the AutoML MNAS framework, which optimizes both accuracy and efficiency (FLOPS). The resulting architecture uses mobile inverted bottleneck convolution (MBConv), similar to MobileNetV2 and MnasNet, but is slightly larger due to an increased FLOP budget. It is available with pretrained weights on the ImageNet Dataset, which was used as an integrated feature extractor

# Results
99.78% accuracy with an inference speed of 0.0085s was achieved
