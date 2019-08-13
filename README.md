# CNN_NST
Here I am implpementing style transfer method introduced in: http://openaccess.thecvf.com/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf

The code generates on the basis of the VGG network, which was trained to perform object recognition and localisation. I employed a normalized version of the 16 convolutional and 5 pooling layers of the 19-layer VGG network. The network is normalized by scaling the weights such that the mean activation of each convolutional filter over images and positions is equal to one. Such rescaling on VGG network has no affect on its output, since it has only linear activation functions. The model is publicly available and can be explored in:

http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat
