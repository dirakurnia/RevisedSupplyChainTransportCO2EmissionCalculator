## Overview
This repository contains a CO₂ emission calculation app that estimates carbon emissions for different transportation types. The app leverages OpenStreetMap's API to obtain transportation data and compute distances. It aims to provide an open-access tool for estimating emissions from freight transport, whether by road, air, or water.

## Data Sources & Limitations
- The app relies on OpenStreetMap (OSM), an open-source mapping service. While extensive, it may not cover all addresses, ports, or airports globally.
- Users can update Air Freight or Water Freight Data using the provided scripts:
-- Run "Air Freight Data Building.py" to refresh air freight locations.
-- Run "Water Freight Data Building.py" to update water freight data.
  
## Distance Calculation & Future Enhancements
- The current approach calculates the straight-line (Haversine) distance between two latitude-longitude points.
- Best route/direction calculation was not taken to account due to running-time limitations (need distributed computing).


## Next Steps
- Implement faster route optimization for long-distance trips.
- Expand the database with more ports, airports, and freight hubs.
- Improve accuracy by integrating additional GIS and emissions data sources.
  
Contributions are welcome! 🚀 Feel free to fork, suggest improvements, or report issues. 💡
