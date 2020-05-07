# Watermark removal with generative adversarial networks

Watermarks often consist of a logo being overlaid onto an image. There exist several algorithmic techniques to approach watermark removal. Our project will explore a generative-adversarial based approach, that requires no input other than an image with a watermark.

<br/>
## Dataset

We will use the following datasets:
__Places365__: [google drive](http://places2.csail.mit.edu/download.html)
__celebA__: [google drive](https://drive.google.com/drive/folders/0B7EVK8r0v71pWEZsZE9oNnFzTm8)
__celebA-HQ__: [website]( https://drive.google.com/drive/folders/0B4qLcYyJmiz0TXY1NG02bzZVRGs)

We plan to collect 50 to 100 categories of watermarks in different patterns(e.g. logos of famous brands or organizations).


<br/>
## Method

The method involes two techniques: a FCN-based approach for the identification of watermarks in the input and a cGANbased approach for filling out the blanks.



<br/>
## Evaluation

__PSNR__(peak signal-to-noise ratio)
__SSIM__(structural similarity index)

<br/>
## Experiments
__Analysis of loss functions__
__Evaluation of discriminator__
__Comparison with state-of-the-art__

<br/>
## Authors
K.H.W. Stolle, Xiao. Liu


<br/>
## License
[MIT](https://choosealicense.com/licenses/mit/)
