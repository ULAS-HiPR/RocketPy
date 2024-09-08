# Motor Parameters

## SolidMotor

### Grain Density calculation

1. Calculate propellant mass: `Wet mass = Total mass - Dry mass`

2. Calculate the volume of a single grain:
   The volume of a hollow cylinder is: `grain Volume =  π *  h * (r_outer^2 - r_inner^2)`
  
3. Calculate total propellant volume: `Total propellant volume = grain Volume * number of grains`

4. Calculate grain density: `Grain density = propellant mass / Total propellant volume`