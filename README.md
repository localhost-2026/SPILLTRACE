# SPILLTRACE

### AI-Powered Marine Oil Spill Detection and Vessel Attribution

SPILLTRACE is an AI-powered platform that helps maritime authorities detect marine oil spills, estimate their probable origin, and identify potentially associated vessels.

## Key Features

- Detects and segments oil spills from Sentinel-1 SAR imagery.
- Characterizes detected spills using location, area, and extent.
- Uses ocean currents and wind data to estimate the probable spill origin.
- Analyzes historical AIS data to identify candidate vessels.
- Generates vessel association scores based on available evidence.
- Provides a web-based GIS interface for visualization and analysis.

## Workflow

```text
Satellite SAR Image
        ↓
Oil Spill Detection
        ↓
Spill Characterization
        ↓
Drift Modelling & Hindcasting
        ↓
Probable Origin Estimation
        ↓
AIS Vessel Filtering
        ↓
Vessel Association & Evidence Scoring
        ↓
GIS Visualization
```

## Input Data

- Sentinel-1 SAR imagery
- AIS vessel records
- Ocean current data
- Wind and meteorological data

## Output

- Detected oil-spill regions
- Spill characteristics
- Estimated probable origin region
- Candidate vessels
- Vessel association scores
- Drift trajectories
- Interactive GIS visualization


Developed by **LOCAL_HOST**.
