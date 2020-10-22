# Multiplex-Segmentation-and-Spatial-Data-Extraction



# Description: 
Spatial Data Extraction Pipeline using the Multiplex Segmentation Application deepcell-tf module


# Main Files (and .jpg files used in notebooks):
## MAIN-Individual_Segmentations_Data Extraction.ipynb (pipeline)

- Make sure when running the default to download the .jpg images from the /notebooks/Multiplex Tissue-Segmentation Model/15_T_BC180x2_[46585, 10362]/ folder into your local folder. Images required for this notebook (change as needed):

- CD3_1.jpg, CD68_1.jpg, CD8_1.jpg, CK_1.jpg, DAPI_1.jpg, PD_L1_1.jpg 






## MAIN-Multiplex-Application-Edited.ipynb (Exploration of methods used in pipeline)
   
- Make sure when running the default to download the .jpg images from the /notebooks/Multiplex Tissue-Segmentation Model/ folder into your local folder. Image required for this notebook:

- DAPI1.jpg


# Required Libraries :

- Up-to-date deepcell-tf library (See: https://github.com/vanvalenlab/deepcell-tf for requirements)
- OpenCV
- skimage
- numpy
- matplotlib
- PIL

# Other Software

- Qupath (required to load in new data)


# To Make this Code Work:
Run in environment with locally installed python packages as listed above 

# Possible Error 
Occasionally an error may pop up when using the pre-trained MultiplexSegmentation weights (sepcifically when running the notebook cell which retrieves the multiplex application data). The error encountered might look something like this:

gaierror                                  Traceback (most recent call last)

/usr/lib/python3.6/urllib/request.py in do_open(self, http_class, req, **http_conn_args)
   
   1317                 h.request(req.get_method(), req.selector, req.data, headers,

 -> 1318                           encode_chunked=req.has_header('Transfer-encoding'))

   1319             except OSError as err: # timeout error


If this occurs, restart your jupyter notebook kernel. If that doesn't work you may need to restart your computer.

# Questions:
Email s3ahuja@ucsd.edu


