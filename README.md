# Neural_styleTranfer
A process that uses neural networks to apply artistic style from one image to another.
Output image looks like the 'content image' but “painted” in the style of the 'style img'.
We have 2 i/p images -> style image, content image

 How are we doing this?
1. Download a pre-trained neural style transfer model from tensorflow hub
2.  Load up style and content images using tensorflow preprocessing
3. Apply style transfer and visualize the result
