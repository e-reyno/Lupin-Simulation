# Lupin-Simulation
Simulation of LUPIN-II neutron detector in OpenMC

This project will look at simulating the LUPIN-II BF3 neutron detector in a Monte Carlo code OpenMC. The model and main elements of the Lupin detector have been made using Constructive Solid Geometry according to data from the manufacturer. 

The response function and efficiency of the detector will be simulated and benchmarked against the real detector. A response function is generated from the thermal scattering $(n,\alpha)$ reaction in the detector cell.

The interaction of a neutron inside the detector is a $n(B^{10}, Li^{7}) He^4$ reaction. The energy deposited inside the detector is approximated by a linear energy absorption rate.
