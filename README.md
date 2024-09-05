# Formula 1 2024 Season Prediction Model

## Project Overview
This project implements a linear prediction model for the 2024 Formula 1 season. It utilizes historical race data, driver performance, and track characteristics to forecast race outcomes and championship standings. The model combines statistical analysis, machine learning techniques, and domain-specific knowledge of Formula 1 racing.

## Features
- Data extraction and processing from the FastF1 API
- Comprehensive analysis of track types and their impact on driver performance
- Driver and team momentum calculations
- Linear regression modeling for race position predictions
- Analysis of track characteristics and their influence on race outcomes
- Championship contender predictions based on current standings and remaining points


2. View generated visualizations in the output directory.

## Key Components

### Data Processing
- Extraction of race data, qualifying results, and sprint race information
- Calculation of track type percentages (Low, Medium, High speed corners)

### Feature Engineering
- Driver and team momentum scores
- Track characteristic analysis (corner types, track length)
- Historical performance metrics

### Prediction Model
- Linear regression for individual driver performance
- Adjustments based on team momentum and track suitability

### Visualization
- Driver and team point progression charts
- Track characteristic comparisons
- Performance distribution plots
- etc

## Future Improvements
- Integration of weather data for more accurate predictions
- Incorporation of Pirelli tire wear data for each track
- Analysis of track characteristics (surface, grip, elevation)
- Derivation of car drag and downforce from speed data
- Real-time updates during race weekends
