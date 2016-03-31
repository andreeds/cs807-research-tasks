## Synopsis

This project is a pratical research abouth with a **Implementation of a Parallel Solution for Message Passing on Arithmetic Circuits**, from [Darwiche](http://arxiv.org/abs/1301.3847).

For more details, read the abstract below.

## Abstract

>Arithmetic Circuits (AC) is a graphical method for reasoning with Bayesian networks (BNs) based on partial differentiation. ACs is a viable framework for applications of BNs to embedded systems, which are characterized for their primitive computational resources. There are two phases to compile the AC: upward and inward. Once the BN is processed, one can compute in constant-time answers to a large class of probabilistic queries. In this paper we present the algorithm to compile the AC. We show the parallel solution and describe how it compares to a serial solution. In practice, our empirical evaluation shows that the parallel solution tends to be faster than the serial solution in ACs.



## Motivation

This project is one research task of the class *CS 807: Interactive Hardware and Embedded Computing*.

 
This task in particular is called **The problem**, which requires to write some code using a GPU language such as CUDA or OpenCL, on our everyday computer, phone, or some other device. To write CPU code to solve the same problem or implement the same function, and compare the results. This can be related to task C. Requires code.


## Installation

No instalation required. There are no code. There only the latex code, 

[**Keras**](https://github.com/fchollet/keras)

Keras uses the following dependencies:

- numpy, scipy
- pyyaml
- HDF5 and h5py (optional, required if you use model saving/loading functions)
- Optional but recommended if you use CNNs: cuDNN.

*When using the Theano backend:*

- Theano
    - [See installation instructions](http://deeplearning.net/software/theano/install.html#install).

**Note**: You should use the latest version of Theano, not the PyPI version. Install it with:
```
sudo pip install git+git://github.com/Theano/Theano.git
```

*When using the TensorFlow backend:*

- TensorFlow
    - [See installation instructions](https://github.com/tensorflow/tensorflow#download-and-setup).

To install Keras, `cd` to the Keras folder and run the install command:
```
sudo python setup.py install
```

You can also install Keras from PyPI:
```
sudo pip install keras
```

>The content can be directly accessed by the [PDF](https://github.com/andreeds/cs807-research-tasks/blob/master/D%20-%20The%20Comparison/Paper/Task_D_Andre_200334126.pdf).

## Tests

No tests required.

## License

If you going to refer to this content, plase make sure to **cite** the respective authors on your Reference section.
