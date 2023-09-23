# MIScnn-for-nuclei-segmentation
Here I slightly modified a project committed by muellerdo (https://github.com/frankkramer-lab/MIScnn) so it works with newest versions (2023) of libraries used in it. 

MIScnn is a library which simplifies training and predictions for segmentation of medical images. It provides a short pipeline for 

Then I did a pipeline for nuclei instance segmentation for 2d images using residual Unet. As Unet is able to do only a semantic segmentation, I modified masks so that Unet predicts not only areas where nuclei are located but also the borders between sticked-together nuclei (this idea I found in discussion of 1st place team solution on 2018 data science bowl on Kaggle: https://www.kaggle.com/competitions/data-science-bowl-2018/discussion/54741)
