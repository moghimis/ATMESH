# ATMESH
ESMF/NUOPC cap to read unstructured ATM forcing from netcdf file and provide it to coupled application 

# To Cite:

## Development of a Flexible Coupling Interface for ADCIRC Model for Coastal Inundation Studies

### Authors
Saeed Moghimi, Sergey Vinogradov, Edward P Myers, Yuji Funakoshi, Andre J Van der Westhuysen, Ali Abdolali, Zaizhong Ma, Fei Liu
### Publication date
2019
### Description
To enable flexible model coupling in storm surge studies, a coupling cap for ADvanced CIRCulation model (ADCIRC) was developed. The cap is essentially a wrap-around ADCIRC model which enables the model to communicate seamlessly with other model components, eg, surface wave and numerical weather prediction models. All the model components advertise their imported and exported fields at the runtime and connect to each other for exchanging data based on the availability of the advertised fields. Models can operate on structured or unstructured grids and the regridding capability will be provided by Earth System Modelling Framework (ESMF) and National Unified Operational Prediction Capability (NUOPC) infrastructures. We implemented the coupled application including ADCIRC cap as well as NUOPC compliant caps to read WaveWatchIII and Hurricane Weather Research and Forecasting Model (HWRF) generated forcing fields. We validated the coupled application for hurricane Ike on very high resolution mesh that covers the entire US Atlantic coastal water. We also showed that inclusion of the surface waves improves the model performance of both total water level and coastal inundation. Also shown how the maximum wave set-up and maximum surge regions may happen at various time and locations depending on the storm track and its landfalling region.

https://repository.library.noaa.gov/view/noaa/20609/noaa_20609_DS1.pdf
