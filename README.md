# CycleGenerator

## Input:
- Total distance to travel in the cycle
  - Measured in km
  - Time to travel is irrelevant
- Number of different speed limits
  - Every point must be a tuple (speed limit, percentage of total travel)
  - By percentage it is implied that all percentages will be added and the fractions will be calculated)
  - Speed limit in km/h
- Tendency to drive close to the speed limit
  - Values of 0,1
  - If 0 --> we aim for about 0.85 of the s.limit
  - If 1 --> we aim for the total s.limit
- Aggression of the driver
  - It basically is the acceleration preferred by the driver
  - Measured in m/s^2
  - This should be the identifier and classifier of driver (matched with the tendency)
- Traffic index
  - 
