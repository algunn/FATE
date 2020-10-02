# FATE (Field Aeolian Transport Events)
repository for 'Circadian rhythm of dune-field activity', Gunn et al. 2020

# suppvideo1.mov 
is the video for Supplemental Video 1 which has the caption:
GOES-16 training set. Six segments of observations from the GOES-16 satellite corresponding to the training set for the mahcine learning dust detection algorithm (see Methods). Each frame in this video (20 frames per second) is a single capture from the satellite ABI (local time in top left) which has a temporal resolution of 5 mins. On the left, a 'True Color' image constructed from the 0.47 $\mu$m (blue), 0.64 $\mu$m (red) and 0.86 $\mu$m (green) bands is presented. On the right, a 'split window' image is constructed from the residual of the 11.2 $\mu$m and 8.5 $\mu$m bands, which is commonly used to find clouds \cite{schmit}. Each video segment is titled on the top right, where each class in the machine ('Clear Sky', 'Cloud Cover', and 'Dust Emission') has 2 segments each that are numbered and continuous in time. Overlayed on both image constructions are semi-transparent RGB `False Color' masks output from the machine learning algorithm. This mask shows the probability prediction of machine learning algorithm for the current frame, where dust emission (red), clear sky (blue) and cloud cover (green) are the pure colors (Extended Data Fig. 2).

# directories contain raw data referenced in code

# data for global analysis and dust detection can be found at https://registry.opendata.aws/ecmwf-era5/ and https://registry.opendata.aws/noaa-goes/ respectively
