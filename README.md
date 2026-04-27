# F1 Strategy Simulation — Australian GP (Leclerc)

This project presents a counterfactual race strategy analysis from the 2026 Australian Grand Prix, focusing on Ferrari’s pit stop timing for Charles Leclerc.

-Objective

To estimate the performance impact of an alternative strategy where Ferrari pits under the first Virtual Safety Car (VSC), instead of delaying the stop.

-Methodology

A simplified lap-by-lap simulation is constructed using actual race data. Two scenarios are compared:

- Actual strategy: pit stop on Lap 26  
- Counterfactual strategy: pit stop on Lap 13 (under VSC)

The model applies the following assumptions:

- Laps 1–12 remain unchanged  
- Reduced pit loss is applied during VSC conditions  
- Post-stop pace is estimated using average clean lap times  
- A linear tyre degradation factor is applied across the stint  
- Lap time outliers (e.g. traffic or VSC laps) are excluded when estimating base pace  

-Results

The simulation indicates that an earlier pit stop under the first VSC could have yielded an approximate 11-second gain over the race distance.

Although modest in absolute terms, this difference is meaningful in race conditions, where small time gaps can influence track position and overall outcome.

-Insight

The analysis reinforces the importance of timing in race strategy execution.  
Even when the strategic approach is broadly correct, missing optimal windows can lead to measurable performance losses.

-Limitations

This is a simplified model and does not account for:

- Traffic and overtaking dynamics  
- Position-dependent pace variation  
- Dynamic race events (e.g. safety cars, incidents)  

The objective is to estimate relative impact rather than fully reproduce race conditions.

-Tools

- Python  
- NumPy  
- Matplotlib  

-Author
Buhayyah Putri Ayu
