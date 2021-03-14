# Segmentation of images using U-Net architecture CNN

I was curious about how to use CNN, and finding appropriate datasets.
Thanks to Google, I found some articles on auto-segmentation using such ML tools:

- U-Net: Convolutional Networks for Biomedical Image Segmentation, Ronneberger et. al, https://arxiv.org/pdf/1505.04597.pdf.
  - I observed that this article was used as a foundation in many other articles about auto-segmentation of biomedical images.
- Automatic segmentation of the spinal cord and intramedullary multiple sclerosis lesions with convolutional neural networks, Many authors, https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6759925/
  - In this article, they used similar method explained in 1st article. I could not implement same procedure, as I could not find public data with masks for spinal cords.
###  
  
I decided to use architecture from 1st article, which is called U-Net architecture [a sequence of convolution and pooling layers, which form a U-shape (as in the figure of the notebook)]
####
Thanks to open-source links/videos, I was able to implement this deep neural network using Keras.
I used this algorithm on Kaggle dataset of Brain MRI, together with FLAIR abnormality segmentation masks (not really sure what is it, but it was segmented by professional manually). Results and explanations are in the notebook.

Please enjoy!
