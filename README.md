# MIScnn-for-nuclei-segmentation
Here I slightly modified a project committed by muellerdo (https://github.com/frankkramer-lab/MIScnn) so it works with newest versions (2023) of libraries used in it.

Then I did a pipeline for nuclei instance segmentation for 2d images using residual Unet. As Unet is able to do only a semantic segmentation, I modified masks so that Unet predicts not only areas where nuclei are located but also the borders between sticked-together nuclei. 
