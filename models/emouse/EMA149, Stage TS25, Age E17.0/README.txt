Notes about the eMouseAtlas 3D models
29/08/2017

The Edinburgh Mouse Atlas project has created a series of 3D reconstructions of the
mouse embryo either from serial histological sections or from a 3D imaging technique
such as Optical Projection Tomography (OPT), micro-MRI or micro-CT. Some of these
images have been segmented to delineate anatomy and have been used within the
gene-expression database as target models for mapping expression data. Each model
has a unique EMA identifier and has been stage-matched to the Theiler embryo staging
system. The detail of the reconstruction, voxel dimensions etc are in the model_info.txt
file.

The image data is provided in two formats. The original Woolz image format (.wlz) and its
conversion ot NIfTI (.nii). The reference image is the original grey-level 3D model and
the anatomy images are the delineated anatomy configured as an index image. The mapping
of image index value to anatomical component is provided in the *_anatomy.txt file.

The Woolz files can be viewed using the Woolz image processing libraries and 
applications that are found at the ma-tech GitHub repository.
The NIfTI images and the anatomy.txt file can be conveniently read into the ITK-Snap
image viewer and segmentation tool.

These models are all visible at the emouseatlas.org website using the model viewer. Where 3D surfaces for the 3D anatomical components are available we have provided these as .stl files in the Surfaces.zip archive.

README.txt - this file
citation.txt - how to cite use of this image
embryo_notes.pdf - if present notes on the anatomy delineation decisions
thumb.jpg - a thumbnail image to display on the web-page
model_info.txt - information about the specific model image
Surfaces.zip - if present a set of .stl surfaces of the delineated anatomy
TS_EMA_anatomy.nii - if present NIfTI format indexed image for the delineated anatomy
TS_EMA_anatomy.txt - if present materials description file for the indexed image
TS_EMA_anatomy.wlz - if present woolz indexed image for the delineated anatomy
TS_EMA_reference.nii - NIfTI format image of the grey-level reference image
TS_EMA_reference.wlz - woolz format image of the grey-level reference image

