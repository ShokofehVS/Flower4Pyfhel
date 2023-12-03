# Flower4Pyfhel

<p align="left">
  <a href="https://flower.dev/">
    <img src="https://flower.dev/_next/image/?url=%2F_next%2Fstatic%2Fmedia%2Fflower_white_border.c2012e70.png&w=640&q=75" width="40px" alt="Flower Website" />
  </a>
</p>

[Flower](https://github.com/adap/flower/tree/main) is a friendly federated learning framework that can be combined with popular machine learning frameworks such as PyTorch or TensorFlow. [Pyfhel](https://github.com/ibarrond/Pyfhel) provides FHE implementation with higher-level languages and ecosystems non-experts are already familiar with, such as Python, the de-facto standard language of data science and machine learning.

Here I intend to create such examples of how to apply Pyfhel to Flower. An example of HE in combination with FL is that homomorphic encryption can enable the parties to homomorphically encrypt their local model updates before sending them to the aggregator for secure aggregation. 

Some sample implementation of homomorphically federated analysis are:
1. [Battery remaining useful life prediction](https://github.com/Audris-A/FL-for-battery-RUL-with-Flower-framework)
