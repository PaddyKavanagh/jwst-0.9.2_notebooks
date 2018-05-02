# jwst-0.9.2_notebooks

This repository contains Jupyter notebooks demonstrating the use of the JWST calibration pipeline (jwst-0.9.2) for MIRI data within python.

jwst-0.9.2 is a release tag leading to Build 7.1.3 of the JWST calibration pipeline can be installed into an Anaconda environment as follows:

conda create -n python=3 jwst --file 

where is:

Linux: http://ssb.stsci.edu/releases/jwstdp/0.9.2/latest-linux

OS X: http://ssb.stsci.edu/releases/jwstdp/0.9.2/latest-osx

The CRDS context should be set to jwst_0440.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0440.pmap"
