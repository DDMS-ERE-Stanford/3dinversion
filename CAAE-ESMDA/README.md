# MODFLOW + MT3DMS simulations
Flopy(python package for MODFLOW) together with MT3DMS are used to simulate the flow and transport processes. TCP3d_model.py include the model settings except for the conductivity field and the contaminant release information. input_dataset.ipynb includes the codes to generate input .hdf5 input files with the conductivity and release configurations, it is later used to read the output hdf5 files to generate dataset too.
para_simu.py is a function to read the input hdf5 file and then simulate and save the model outputs to an output hdf5 file. gen_simus.ipynb is a Jupyter notebook to generate many simulations in parallel utilizing multi-threads processing with python.
Simulation input files and simulation output files can be found in [link1](https://drive.google.com/drive/folders/1ImiSOEbkJxTXhWENAnVPQLeXvxRGNdpg?usp=sharing) and [link2]( https://drive.google.com/drive/folders/1a_v4yi5TGE2ilG9jD4g9Mu6uUTdUbeck?usp=sharing) in Google drive.

# ESMDA inversion
ESMDA-MT3D.ipynb is the jupyter notebook for CAAE-ESMDA inversion with MODFLOW+MT3DMS simulators.
The resulting 11 ESMDA ensembles can be found in this [link](https://drive.google.com/drive/folders/1NQObllG025n1LN6PXVjYd5ULNU2xylRS?usp=sharing) .
The inspection of the ESMDA results are done together with CAAE-DenseED-ESMDA results inspection in CAAE-DenseED-ESMDA.ipynb GoogleColab notebook.