======= Problem Instances =======
The "instances" directory contains E-ADARP Ropke instances and large instances.

All problem instances have the following format:

Meta Information ([number of vehicles] [number of requests] [number of start depots] [number of end depots] [number of charging stations] [number of replications of charging stations] [time horizon])
Locations ([index] [lat] [lon] [service duration] [load] [lower bound time window] [upper bound time window])
    Pick-up locations
    Drop-off locations (where drop-off i corresponds to pick-up i-#requests)
    Physical start depot
    Physical end depot
    Artifical start depots
    Artifical end depots
    Charging stations
Index of physical start depot
Index of physical end depots
Indices of artifical start depots of vehicles
Indices of artifical end depots of vehicles
Indices of charging stations
Maximum ride times of requests
Load capacities of vehicles
Initial battery levels of vehicles (in kWh)
Battery capacities of vehicles (in kWh)
Minimum final battery rations of vehicles
Charging speeds of charging stations (in kWh per minute)
Energy consumption (in kWh per minute)
Weights w1 and w2 of objective function

======= Solutions =======
The "optimal_solutions" directory constains the solutions belonging to the corrected global optima.

For each vehicle, the route is specified where an entry of a route has the following format:
[location index] [service time] [charging duration]      
