ESS Timing Data Buffer - EPICS Database Files for EVG & EVR Data Buffer Access
--

# Introduction
Access the MRF timing system data buffer, as used by ESS, in an easy way.

# Timing Data Buffer

Offset |	Byte  |	Data Type
-------|--------|----------
0 	   |	1    	|	Protocol number
1 	   |	1 	  |	Reserved
2 	   |  1 	  |	Protocol version
3 	   |	1 	  |	Reserved
4 	   |	8    	|	Linac cycle counter/ID
12     |	1     |	Beam on/off
13     |	1     |	Beam destination (last point)
14     |	1     |	Beam mode
15     |	1     |	Reserved
16     |	4     |	Beam length: float [ms]
20     |	4     |	Beam energy: float [MeV]
24     |	4     |	Beam current: float [mA]
28     |	1     |	Raster pattern: 14 beam slots
29     |	1     |	Target segment (1-36)
30     |	1     |	Reserved
31     |	1     |	Reserved
