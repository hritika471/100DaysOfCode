## All About Tensors

Hello troubleshooters! In this on-going series of 100days of machine learning we have till now covered the all basic stuffs and major building blocks required for machine learning. Gonna take you forward in this article through questions 

# TENSORS IN GENERAL

**Tensors are just buckets of numbers of a specific shape and a certain rank (dimensionality). Tensors are used in Machine Learning with TensorFlow to represent input data and output data (and everything in between) in Machine Learning models.**

**A tensor is a generalization of vectors and matrices and is easily understood as a multidimensional array. In the general case, an array of numbers arranged on a regular grid with a variable number of axes is known as a tensor.**

** A vector is a one-dimensional or first-order tensor and a matrix is a two-dimensional or second-order tensor. Tensor notation is much like matrix notation with a capital letter representing a tensor and lowercase letters with subscript integers representing scalar values within the tensor. Many of the operations that can be performed with scalars, vectors, and matrices can be reformulated to be performed with tensors**

**As a tool, tensors and tensor algebra is widely used in the fields of physics and engineering. It is a term and set of techniques known in machine learning in the training and operation of deep learning models that can be described in terms of tensors.**

## RANK 

The dimensionality of a Tensor we call it’s rank.

A 1D Tensor (or rank 1 Tensor) is just an array, like so:

[
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664263790737/S-RLgFxyX.png align="left")
ext](Link)

A 2D Tensor (or rank 2 Tensor) is just a 2-dimensional array, so an array of arrays, like so:

[
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664263814953/ACwF9yUoU.png align="left")
ext](Link)

A 3D Tensor (or rank 3 Tensor) is a cube. An array of arrays of arrays, like so:

[
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664263853054/jOaFOx1rN.png align="left")
(Link)

Everything after 3D becomes harder to conceptualize, but let’s try. A 4D Tensor is an array of 3D Tensors, like so:

[
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664263873156/zr6V842ve.png align="left")
ext](Link)

A 5D Tensor is an array of 4D Tensors, like so:

[
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1664263887676/8-k4B6Ltm.png align="left")
ext](Link)

### SHAPE 

The size of each dimension in a Tensor we call its shape. For example, a Tensor to represent a black and white image would have the shape [width, height, colors].

For a 640 x 480 pixel black and white image, the shape would be [640,480, 1].

colors in this case would be of size 1; in a black and white image, the only color is black; in a color image, the size might be 3 with a value for red, green, and blue.

The rank of the Tensor is 3; it’s a 3D Tensor.

This was the quick walkthrough of the tensors in machine learning in the upcoming article we would be exploring the open source platforms to forth our journey in the legitimate direction until then don't forget to checkout the previous nodes of this series.

**Read till here thanks a bunch:)**

