# FAST.AI_BANGALORE_MUMBAI_DELHI
using fast.ai resnet34 model on google images to classify famous buildings from Delhi, Bangalore, Mumbai

The notebook is using the code provided by https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb

Here we are searching google images of three Indian cities famous buildings, Delhi, Bangalore and Mumbai and the urls are stored in CSV file

To have a balance of classes i have kept every city to 320 images.

Fast.AI uses resnet34 CNN , to apply transfer learning on these images.

In the end three images try1,try2,try3 are tested for which city they belong to and we get accurate results from our model.
