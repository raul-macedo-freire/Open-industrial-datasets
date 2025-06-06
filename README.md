# Open-industrial-datasets
A collection of open datasets for industrial applications, divided by categories. PRs are welcome. Links to papers describing the datasets are only included if the dataset page doesn't link to the paper already

## All datasets
Google Dataset Search is now out of beta and it's one of the most powerful engines to search for datasets.

https://datasetsearch.research.google.com/

## Computer vision
A dataset of more than 19.400 X-ray images for the development, testing and evaluation of image analysis and computer vision algorithms

http://dmery.ing.puc.cl/index.php/material/gdxray/

## Oil & Gas
### equipment
#### Turbomachinery
https://github.com/siemens/industrialbenchmark 

- [paper](https://www.openml.org/d/23383)

#### Boilers
https://www.openml.org/d/41170 (only the `.arff` file format is working at the moment) 

 - [paper](https://ieeexplore.ieee.org/ielx7/6287639/8274985/08501917.pdf?tp=&arnumber=8501917&isnumber=8274985)
### Maintenance
#### 3W
https://github.com/petrobras/3W/tree/main

A large dataset from Petrobras, Brazil's largest Oil & Gas company, containing a set of operational time series data with eight classified undesired events from real operations. It also includes time series from normal operating conditions. Simulated data is provided as well, along with a new approach to data gathering entitled “hand-drawn,” which was created by experts in the field.

- [paper](https://www.sciencedirect.com/science/article/pii/S0920410519306357)

## Secure Water Treatment (SWaT) 
https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/
The actual dataset can be accessed by compiling this [request form](https://itrust.sutd.edu.sg/itrust-labs_datasets/)
https://itrust.sutd.edu.sg/research/dataset/dataset_characteristics/#swat
 
 - [paper](https://www.researchgate.net/publication/305809559_A_Dataset_to_Support_Research_in_the_Design_of_Secure_Water_Treatment_Systems)

## Open Industrial Dataset
The biggest data lake of open, continuously streaming industrial data
https://openindustrialdata.com/

## Transportation Mode Detection
Especially interesting for [IIoT](https://en.wikipedia.org/wiki/Industrial_Internet_of_Things) applications, three theses and 1 paper already published about this project
http://cs.unibo.it/projects/us-tm2017/index.html

## Dataset list
A big list of Machine Learning datasets. They're not necessarily related to industry application, but the list is very up-to-date, and it contains very large datasets which, through transfer learning, can help training models for industrial applications

https://www.datasetlist.com/

## UK National Data Repository
The Data Repository of the UK Oil & Gas Authority, hosting a wealth of information about the UK Continental Shelf. Currently only a subset of the data is accessible to a wider public, but there are plans to extend the access also to the other data which are currently accessible only by petroleum licensee users.

https://ndr.ogauthority.co.uk/dp/controller/PLEASE_LOGIN_PAGE

## Airbus AI Gym
An impressive collection of industrial multivariate time series from the biggest European aircraft company. These datasets were used for competitions (all closed, now), regarding different learning task. In particular [this one](https://aigym.airbus.com/contest/5c336d2f40668b001f0e7d50) was about anomaly detection on real industrial data. The competitions are all closed, but it's possbile to contact Airbus in order to ask access to data.

https://aigym.airbus.com/

## Power Systems
### Electricity Supply Monitoring Initiative (ESMI) Initiative
Minute-wise voltage data for some years (2014-2019) and several users in India. A '0' voltage reading means a power outage and missing data should be interpreted as unavailable data and not as interruption.

https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/CLLZZM

### VSB Power Line Fault Detection Dataset
This dataset is linked to a Kaggle competition to detect partial discharge patterns in signals acquired from these medium voltage overhead power lines. 

https://www.kaggle.com/competitions/vsb-power-line-fault-detection/data

## Turbofan Engine Degradation Simulation Data Set
### Dataset 1
Engine degradation simulation was carried out using C-MAPSS. Four different were sets simulated under different combinations of operational conditions and fault modes. Records several sensor channels to characterize fault evolution. The data set was provided by the Prognostics CoE at NASA Ames.

https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan

### Dataset 2
The generation of data-driven prognostics models requires the availability of datasets with run-to-failure trajectories. In order to contribute to the development of these methods, the dataset provides a new realistic dataset of run-to-failure trajectories for a small fleet of aircraft engines under realistic flight conditions. The damage propagation modelling used for the generation of this synthetic dataset builds on the modeling strategy from previous work. The dataset was generated with the Commercial Modular Aero-Propulsion System Simulation (C-MAPSS) dynamical model. The data set is been provided by the Prognostics CoE at NASA Ames in collaboration with ETH Zurich and PARC. 

https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan-2


