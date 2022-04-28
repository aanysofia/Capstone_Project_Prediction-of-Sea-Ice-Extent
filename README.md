
![](sea_ice.gif)


## Prediction of Sea Ice Extent in Northern Hemisphere

## Introduction

Sea ice is frozen sea water that floats on the surface of ocean. This floating ice has a profound influence on the polar environment, influencing ocean circulation, weather, and regional climate.

Sea ice also plays a fundamental role in polar ecosystems. The ice itself is habitat for animals such as seals, Arctic foxes, polar bears, and penguins. When the ice melts in the summer, it releases nutrients into the water, stimulating the growth of phytoplankton, the center of the marine food web. As the ice melts, it exposes ocean water to sunlight, spurring photosynthesis in phytoplankton. When ice freezes, the underlying water gets saltier and sinks, mixing the water column and bringing nutrients to the surface. 

The influence of sea ice on the Earth is global. The white surface reflects far more sunlight back to space than ocean water does. Once sea ice begins to melt, a self-reinforcing cycle often begins. As more ice melts and exposes more dark water, the water absorbs more sunlight. The sun-warmed water then melts more ice. Over several years, this positive feedback cycle can influence global climate. So it is important to predict the sea ice in the polar regions.

## Goal of the project

1. Prediction of change in the sea ice extent of Northern Hemisphere till 2122 using time series analysis
2. Analysis of sea ice extent in three main regions of Northern Hemisphere
3. Visualization of the change of sea ice extent

## Data

The data is an an overview of the extent of sea ice around the Northern hemisphere since 1978 provided by National Snow & Ice Data Center. The dataset is generated from brightness temperature data and is designed to provide a consistent time series of sea ice concentrations spanning the coverage of several passive microwave instruments.The data are provided in the polar stereographic projection at a grid cell size of 25 x 25 km.

Citation:
Cavalieri, D. J., C. L. Parkinson, P. Gloersen, and H. J. Zwally. 1996, updated yearly. Sea Ice Concentrations from Nimbus-7 SMMR and DMSP SSM/I-SSMIS Passive Microwave Data, Version 1. [Indicate subset used]. Boulder, Colorado USA. NASA National Snow and Ice Data Center Distributed Active Archive Center. doi: https://doi.org/10.5067/8GQ8LZQVL0VL.

## Requirements

- pyenv
- python==3.9.4

## Setup

For this purpose you use following commands:

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Unit testing (Optional)

If you write python scripts for your data processing methods, you can also write unit tests. In order to run the tests execute in terminal:

```bash
pytest
```

This command will execute all the functions in your project that start with the word **test**.
