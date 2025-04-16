# WaveCeptionNet

The code is being organized and uploaded.

data-process.ipynb： Example of Data Preprocessing

##

This repository contains the official implementation of the methods described in our paper:

"Identifying Exoplanet Candidates Using WaveCeptionNet"

We propose WaveCeptionNet, a deep learning model designed to identify exoplanet candidates from stellar light curves. The model leverages wavelet transforms and an Inception-inspired architecture to improve accuracy and generalization in transit signal classification.

Paper available at: https://iopscience.iop.org/article/10.3847/1538-3881/ad298f
For questions, please feel free to open an issue or contact us.


## machine-readable table containing a list of the TCEs and associated information

multiple.csv: multiple transiting planet systems from the confirmed planet system table at NExScI (https://nexsci.caltech.edu/).

train_val_test.csv: TIC ID, orbital period, planet radius, stellar radius, duration, depth, estimated SNR, transit depth, transit duration, training label, and the waveCeptionNet class scores and predicted classification.

NExScI_SPOC.csv: TESS has discovered 413 transiting exoplanets to date according to the NExScI Exoplanet Archive's planetary systems table, NExScI_SPOC.csv provides the performance of WaveCeptionNet on these objects with SPOC data.



