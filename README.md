# Public-traffic-datasets


This work presents a comprehensive collection of publicly available traffic datasets for research and applications in transportation, urban planning, and intelligent transportation systems.

⚠️ **Note: This repository is under active development. New datasets and resources are continually being added.** ⚠️

⚠️ **Important: Due to file size limitations, many of the larger datasets are not directly uploaded to this repository. If you need access to these datasets, please contact us at ttshi3514@163.com or QQ: 1765309248.** ⚠️

---

## Introduction

Access to high-quality traffic data is essential for developing and evaluating transportation models, traffic prediction algorithms, and intelligent transportation systems. This repository serves as a centralized resource for researchers and practitioners, offering:

- Curated links to diverse publicly available traffic datasets
- Standardized descriptions and metadata
- Information on data formats and structures
- Usage guidelines and citation information
- Sample code for data loading and preprocessing

---

## Datasets Included

Below is a list of publicly available traffic datasets organized by category:

### Road Network Traffic Flow Datasets

- **METR-LA**  
  [Dataset](https://github.com/liyaguang/DCRNN) | [Paper](https://arxiv.org/abs/1707.01926)  
  Traffic data collected from loop detectors in the Los Angeles County road network. Contains speed readings from 207 sensors over 4 months (Mar-Jun 2012) at 5-minute intervals.

- **PEMS-BAY**  
  [Dataset](https://github.com/liyaguang/DCRNN) | [Paper](https://arxiv.org/abs/1707.01926) | [Blog Explanation](https://blog.csdn.net/stt666/article/details/122360673?spm=1001.2014.3001.5501)  
  Traffic data from California Transportation Agencies (CalTrans) Performance Measurement System (PeMS) in the Bay Area. Features 325 sensors over 6 months (Jan-May 2017) at 5-minute intervals.

- **PEMS-D4/D7/D8/D11**  
  [Dataset](https://github.com/Davidham3/ASTGCN/tree/master/data) | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/3881) | [PeMS Official Site](https://pems.dot.ca.gov/) | [Blog Explanation](https://blog.csdn.net/stt666/article/details/122360673?spm=1001.2014.3001.5501)  
  Caltrans PeMS data from different districts in California, containing flow information aggregated at 5-minute intervals.

- **Seattle Loop Data**  
  [Dataset](https://github.com/zhiyongc/Seattle-Loop-Data) | [Paper](https://ieeexplore.ieee.org/document/8057091) | [WSDOT Official Site](https://wsdot.wa.gov/about/data/traffic-data)  
  Traffic speed data collected from loop detectors on freeways in the greater Seattle area, covering 323 sensor stations.

- **England Highways Dataset**  
  [Dataset](https://data.gov.uk/dataset/208c0e7b-353f-4e2d-8b7a-1a7118467acc/gb-road-traffic-counts) | [Documentation](https://www.gov.uk/government/statistical-data-sets/road-traffic-statistics-tra) | [UK Gov Official Site](https://www.gov.uk/government/organisations/department-for-transport/about/statistics)  
  Annual average daily traffic flows at around 10,000 locations across Great Britain, dating back to 2000.

- **NYC Traffic Speed Data**  
  [Dataset](https://data.cityofnewyork.us/Transportation/Real-Time-Traffic-Speed-Data/qkm5-nuaq) | [Documentation](https://www.nyc.gov/html/dot/html/about/datafeeds.shtml) | [NYC DOT Official Site](https://www.nyc.gov/html/dot/html/about/datafeeds.shtml)  
  Real-time traffic speed data from New York City, covering major routes and arterials.

### Urban Mobility and Taxi/Ride-sharing Datasets

- **NYC Taxi Trip Data**  
  [Dataset](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) | [Documentation](https://www1.nyc.gov/assets/tlc/downloads/pdf/trip_record_user_guide.pdf) | [NYC TLC Official Site](https://www1.nyc.gov/site/tlc/index.page)  
  Detailed trip records from yellow and green taxis in New York City, including pickup/dropoff times, locations, fares, and tips.

- **Chicago Taxi Trips**  
  [Dataset](https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew) | [Documentation](https://data.cityofchicago.org/Transportation/Taxi-Trips-Documentation/h4dy-uqfj) | [Chicago Data Portal](https://data.cityofchicago.org/)  
  Taxi trips reported to the City of Chicago with anonymized data on pickup/dropoff locations, times, fares, and tips.

- **Didi GAIA Open Data Initiative**  
  [Dataset](https://outreach.didichuxing.com/research/opendata/) | [Paper](https://arxiv.org/abs/1802.01024) | [DiDi Official Research Site](https://outreach.didichuxing.com/research/opendata/)  
  Vehicle trajectory data, road network information, and order data from DiDi's ride-sharing platform in selected Chinese cities.

- **T-Drive Trajectory Dataset**  
  [Dataset](https://www.microsoft.com/en-us/research/publication/t-drive-trajectory-data-sample/) | [Paper](https://www.microsoft.com/en-us/research/publication/t-drive-driving-directions-based-on-taxi-trajectories/) | [Microsoft Research Project Page](https://www.microsoft.com/en-us/research/project/t-drive-driving-directions-based-on-taxi-trajectories/)  
  GPS trajectories of 10,357 taxis in Beijing over a one-week period, containing approximately 15 million points.

- **Porto Taxi Dataset**  
  [Dataset](https://archive.ics.uci.edu/ml/datasets/Taxi+Service+Trajectory+-+Prediction+Challenge,+ECML+PKDD+2015) | [Paper](https://dl.acm.org/doi/10.1145/2820783.2820852) | [Kaggle Competition](https://www.kaggle.com/c/pkdd-15-predict-taxi-service-trajectory-i)  
  Trajectories of 442 taxis operating in Porto, Portugal, over a complete year (1.7 million trips).

### Public Transit Datasets

- **GTFS (General Transit Feed Specification) Data**  
  [Dataset](https://transitfeeds.com/) | [Documentation](https://developers.google.com/transit/gtfs) | [Google Transit APIs](https://developers.google.com/transit)  
  Standardized public transportation schedules and associated geographic information from transit agencies worldwide.

- **Transport for London (TfL) Data**  
  [Dataset](https://tfl.gov.uk/info-for/open-data-users/) | [Documentation](https://api-portal.tfl.gov.uk/docs) | [TfL Unified API](https://api-portal.tfl.gov.uk/)  
  Real-time and historical data on London's public transport network, including buses, tube, DLR, and rail services.

- **Bay Area Rapid Transit (BART) Data**  
  [Dataset](https://www.bart.gov/schedules/developers/gtfs) | [Documentation](https://www.bart.gov/schedules/developers/api) | [BART Developer Resources](https://www.bart.gov/schedules/developers)  
  Real-time and schedule data for San Francisco Bay Area's BART system.

- **New York MTA Data**  
  [Dataset](https://new.mta.info/developers) | [Documentation](https://api.mta.info/) | [MTA Developer Resources](https://new.mta.info/developers)  
  Real-time and historical data for New York City's subways, buses, and railroads.

### Traffic Incident and Accident Datasets

- **US Accidents Dataset**  
  [Dataset](https://smoosavi.org/datasets/us_accidents) | [Paper](https://arxiv.org/abs/1906.05409) | [Kaggle Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
  A countrywide traffic accident dataset covering 49 states of the USA, with over 3 million records (2016-2021).

- **UK Road Safety Data**  
  [Dataset](https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data) | [Documentation](https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data/datapackage) | [UK Gov Stats](https://www.gov.uk/government/collections/road-accidents-and-safety-statistics)  
  Detailed data about the circumstances of personal injury road accidents in Great Britain, the vehicles involved, and the casualties.

### Weather and Environment Related Traffic Datasets

- **RWIS (Road Weather Information System)**  
  [Dataset](https://ops.fhwa.dot.gov/weather/resources/publications/fhwa/rwis_handbook/rwis_handbook.pdf) | [Documentation](https://www.fhwa.dot.gov/publications/research/operations/its/98079/rwis.pdf) | [FHWA Road Weather Management](https://ops.fhwa.dot.gov/weather/)  
  Weather and road condition data from various state departments of transportation in the USA.

- **Integrated Surface Database (ISD)**  
  [Dataset](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.ncdc:C00532) | [Documentation](https://www.ncei.noaa.gov/data/global-hourly/doc/isd-format-document.pdf) | [NOAA Data Access](https://www.ncdc.noaa.gov/data-access)  
  Global hourly weather observations that can be correlated with traffic data.

### Synthetic and Simulation Datasets

- **SUMO (Simulation of Urban MObility)**  
  [Dataset Generator](https://www.eclipse.org/sumo/) | [Documentation](https://sumo.dlr.de/docs/) | [SUMO Wiki](https://sumo.dlr.de/wiki/Main_Page)  
  Open-source traffic simulation package that can generate realistic traffic datasets for various scenarios.

- **CityFlow**  
  [Dataset Generator](https://github.com/cityflow-project/CityFlow) | [Paper](https://arxiv.org/abs/1905.05217) | [Project Website](https://cityflow-project.github.io/)  
  Large-scale traffic simulator that can generate realistic traffic flow data for AI research.

### Planned Additions
We are actively working on integrating more datasets, especially those covering emerging areas such as connected vehicles, autonomous driving, and micromobility. If you have suggestions for additional datasets to include, feel free to open an issue or submit a pull request!

---

## Getting Started

### Data Access
Each dataset entry includes direct links to the dataset source and relevant documentation. Most datasets require acknowledgment of terms of use or citation in published work.

**Important Note**: Due to GitHub file size limitations, larger datasets are not directly included in this repository. Please contact us at ttshi3514@163.com or QQ: 1765309248 to request access to specific datasets that you need for your research.

### Data Processing Tools
We provide sample scripts for loading and preprocessing common traffic dataset formats:

```python
# Example: Loading METR-LA dataset
from utils.data_loaders import load_metr_la

# Load the dataset
data, adj_mx = load_metr_la()

# Display basic information
print(f"Data shape: {data.shape}")  # (num_timestamps, num_nodes, features)
print(f"Adjacency matrix shape: {adj_mx.shape}")  # (num_nodes, num_nodes)

# Sample preprocessing
from utils.preprocessing import normalize, train_test_split

# Normalize the data
norm_data = normalize(data)

# Split into train/val/test sets
train_data, val_data, test_data = train_test_split(norm_data, val_ratio=0.1, test_ratio=0.2)
```

---

## Repository Structure

```
Traffic-Datasets-Hub/
│
├── datasets/                       # Dataset information and metadata
│   ├── road_network/               # Road network traffic datasets
│   ├── urban_mobility/             # Taxi and ride-sharing datasets
│   ├── public_transit/             # Public transportation datasets
│   ├── incidents/                  # Traffic incident and accident datasets
│   ├── weather/                    # Weather-related traffic datasets
│   └── simulation/                 # Synthetic and simulation datasets
│
├── utils/                          # Utility functions and tools
│   ├── data_loaders/               # Scripts for loading different datasets
│   ├── preprocessing/              # Data cleaning and preprocessing tools
│   ├── visualization/              # Visualization tools for traffic data
│   └── evaluation/                 # Evaluation metrics and benchmarks
│
├── examples/                       # Example notebooks and scripts
│   ├── data_exploration/           # Data exploration examples
│   ├── preprocessing/              # Preprocessing examples
│   └── visualization/              # Visualization examples
│
├── docs/                           # Additional documentation
│   ├── dataset_formats/            # Details on dataset formats
│   ├── access_guides/              # Guides for accessing restricted datasets
│   └── citation_guides/            # How to properly cite datasets
│
├── requirements.txt                # Python dependencies
└── README.md                       # This file
```

## License

This project is licensed under the MIT License - see the LICENSE file for details. Note that each dataset may have its own licensing terms, which should be respected when using the data.

---

## Contact

For questions, suggestions, collaborations, dataset requests, or any copyright-related concerns, please contact us:
- Email: ttshi3514@163.com
- QQ: 1765309248

If you believe any content in this repository infringes upon your copyright or intellectual property rights, please contact us immediately so we can address your concerns appropriately.
