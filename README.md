# Sea Surface Temperature reconstruction
A set of notebooks for Sea Surface Temperature (SST) re-analysis starting from infrared satellite signals.



Sea Surface Temperature (SST) is a vital parameter for understanding Earth’s oceans and climate system. Monitoring and analyzing SST is crucial for climate research, marine ecosystem studies, and insights into ocean circulation patterns. SST data are primarily collected by satellites detecting infrared radiation from the sea surface; however, cloud cover can absorb this radiation, creating significant observational gaps. Addressing these gaps is essential for effective data reanalysis. In this repository, we give a bunch of notebooks addressing the reconstruction task with Deep Learning technologies. 

For the sake of comparison with with previous models, we did experiments with two different sets of data:
* MODIS data, specifically, nightly data from the AQUA satellite
* L3S data from Copernicus

Data can be directly downloaded from the notebooks, or from MODIS and Copernicus sites.

## Notebooks and files
* climatology and residual data
* unet architecture
* generator and training
* L4 comparison and evaluation
