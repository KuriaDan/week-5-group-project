# ANALYSIS OF ELECTRICITY PRODUCTION IN KENYA FROM 2010-2014

The energy sector in Kenya is largely dominated by petroleum and electricity, with wood fuel providing the basic energy needs of the rural communities, urban poor, and the informal sector. An analysis of the national energy shows heavy dependency on wood fuel and other biomass that account for 68% of the total energy consumption (petroleum 22%, electricity 9%, others account for 1%)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

pandas
numpy
matplotlib

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

### Installing

import pandas as pd
import numpy as n

```
```
4. Data Sourcing
The project began with the sourcing/collecting of dataset to be used for analysis. We sourced our dataset from data.world. According to the website the origin of the dataset was http://opendataforafrica.org/dqoksbf/african-regional-energy-statistics-2014 
5. Data Preparation and Quality
Data Selection: We dropped the region column because it was unnecessary for our analysis.  
6. Data Cleaning: 
We converted the column names to lowercase to ensure uniformity of the column names in the dataset. 
We checked for duplicate and null values in the dataset and found none. 
The Region column was dropped from the dataset as it invalid for the analysis. We selected only the rows whose regionname was Kenya and East Africa in order to work with a smaller dataframe. 


## Contributing

Daniel Thuku Kuria
Cecilia Wanja
Sharon Nzaya
Brian Ouma


