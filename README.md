# 🔥 SFEB Trajectory Optimization System

*Optimizing fire extinguishing ball trajectories using physics-based simulation and wind data*

![3D Trajectory Visualization](https://via.placeholder.com/800x400?text=3D+Trajectory+Simulation)

## 🌟 Key Features

- **Precision Targeting** - Calculates optimal release point to hit specified ground coordinates
- **Real Wind Integration** - Incorporates measured wind profiles from CSV data
- **Advanced Physics Engine**:
  - ✅ Altitude-dependent gravity
  - ✅ Atmospheric density/viscosity modeling  
  - ✅ Buoyancy and drag forces
  - ✅ Morrison's drag coefficient correlation
- **Comprehensive Visualization**:
  - 3D trajectory plots
  - Altitude/velocity time series
  - 2D ground track maps

## 🛠️ Installation & Usage

### Requirements
- MATLAB R2018a+
- `wind_profile.csv` containing:
  - Timestamps (s)
  - Altitudes (m) 
  - Wind components u,v (m/s)

```matlab
% Run the optimization system
SFEB_drop_optimized;