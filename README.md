![San Antonio Water Levels repo banner](./img/banner.png)

Hey there!

This repository contains all the code that went into making the graphics for the San Antonio Express-News' story that looks at the drought conditions of aquifers, lakes and rivers in the San Antonio area.

The data comes from three sources:

- Edwards Aquifer historic data is from [the Edwards Aquifer Authority](https://www.edwardsaquifer.org/science-maps/aquifer-data/historical-data/). Data were pulled on April 5, 2023. You can learn how the EAA monitors the aquifer's level [here](https://www.edwardsaquifer.org/science-maps/aquifer-data/water-level-monitoring/).
- Lake fullness level data come from [Water Data for Texas](https://waterdatafortexas.org/reservoirs/statewide), a product of the [Texas Water Development Board](https://www.twdb.texas.gov/), which is run by the state. Data were pulled on April 5, 2023.
- River streamflow data come from the [U.S. Geological Survey's National Water Information System](https://waterdata.usgs.gov/nwis). Data were pulled on April 5, 2023.

## How to replicate

If you'd like to run the code yourself, use the following steps:

1. Clone the repo.
2. Install the requirements with `pip install -r requirements.txt`.
3. `cd notebooks`
4. You can either run the jupyter notebook or use the `nbexec collect-data.ipynb` to run it as a script.
