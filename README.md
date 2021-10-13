# neural-style-tf
This is a TensorFlow implementation of several techniques described in the papers:

Image Style Transfer Using Convolutional Neural Networks by Leon A. Gatys, Alexander S. Ecker, Matthias Bethge
Artistic style transfer for videos by Manuel Ruder, Alexey Dosovitskiy, Thomas Brox
Preserving Color in Neural Artistic Style Transfer by Leon A. Gatys, Matthias Bethge, Aaron Hertzmann, Eli Shechtman
Additionally, techniques are presented for semantic segmentation and multiple style transfer.
Simplified version of neural-style-tf from Cameron at cysmith: https://github.com/cysmith/neural-style-tf

After installing the dependencies:
Download the VGG-19 model weights (see the "VGG-VD models from the Very Deep Convolutional Networks for Large-Scale Visual Recognition project" section). More info about the VGG-19 network can be found https://www.robots.ox.ac.uk/~vgg/research/very_deep/ .
After downloading, copy the weights file imagenet-vgg-verydeep-19.mat to the project directory.









Acknowledgements
The implementation is based on the projects:

Torch (Lua) implementation 'neural-style' by jcjohnson
Torch (Lua) implementation 'artistic-videos' by manuelruder

**Citation**
If you find this code useful for your research, please cite:

@misc{Smith2016,
  author = {Smith, Cameron},
  title = {neural-style-tf},
  year = {2016},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/cysmith/neural-style-tf}},
}
