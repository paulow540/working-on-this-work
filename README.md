# working-on-this-work
## Paul project
This example illustrates various features that are now supported by the image transformations on Tensor images. In particular, we show how image transforms can be performed on GPU, and how one can also script them using JIT compilation.

Prior to v0.8.0, transforms in torchvision have traditionally been PIL-centric and presented multiple limitations due to that. Now, since v0.8.0, transforms implementations are Tensor and PIL compatible and we can achieve the following new features:

<ol> <li>transform multi-band torch tensor images (with more than 3-4 channels)</li><ol>

. torchscript transforms together with your model for deployment

. support for GPU acceleration

. batched transformation such as for videos

read and decode data directly as torch tensor with torchscript support (for PNG and JPEG image formats)


<a href="www.google.com"> google.com</a>
