Welcome to LS-MAT documentation!
===================================
**LS-MAT** is python project for **generate multi-modal MRI images across an individual's lifespan from a single input MRI scan**. Traditionally, acquiring longitudinal MRI data spanning a person's entire life has been challenging due to costs, time constraints, and issues like head motion, particularly in children and the elderly. To address these difficulties, **LS-MAT** integrates **modality transfer and age-specific MRI synthesis**, enabling the generation of both T1-weighted (T1w) and T2-weighted (T2w) MRI images at various ages while **preserving the individual's unique brain structural characteristics**, starting from just one modality image.

The core technology of **LS-MAT** involves several steps. First, 3D MRI data (T1w and T2w) from a wide age range is acquired and preprocessed. Subsequently, the images are encoded into a latent space, and individual attributes such as gender, age, and image modality are embedded. **ControlNet** plays a crucial role in conveying the individual's brain structure information to the generative model based on the input image, ensuring that the synthesized images retain the subject's specific anatomical features. Through ControlNet-LDM, a latent representation of the desired age and modality is generated, and a pre-trained VAE-GAN Decoder is used to transform this latent vector back into the image space.

The key features and advantages of **LS-MAT** include the ability to **generate both T1w and T2w images from a single modality**, thereby reducing the costs associated with MRI scans. Furthermore, it **preserves an individual's specific brain structure while generating images across the entire lifespan**. **LS-MAT** can **directly synthesize 3D T1 and T2 MRI images for all ages**, potentially making contributions to research on brain development, aging, and neurological disorders.



Contents
--------

.. toctree::

   usage
   api
