# image_segment_train
This is a copy of the tutorial shown here. https://github.com/TannerGilbert/FastAI-Code-Collection/blob/v1/Image_segmentation_on_CamVid_dataset.ipynb <br />

I could only get it to run on Google colab. It doesn't want to run in Jupyter notebook either. It works okay for images similar to the training images, 
which admittedly has litle variety. Labeling images to make masks is time consuming and difficult. <br />

Masks are in greyscale (0 being black and 255 being white) with pixel value of 1 being powder and pixel value of 0 being not powder which is why the label images look completely black.
If there was an easy and efficient way to label the images, this could've been the best method of identifying powder volume. The color-segment code might assist in making masks but it's still tedious and not consistent, especially when the color of the sample is similar to the color of the crucible
