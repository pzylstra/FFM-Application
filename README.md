# FFM-Application
Application (exe file) for the C++ version of the Forest Flammability Model

INSTRUCTIONS
1. Using the Windows Command prompt, navigate to the folder where FFM.exe is stored with the input text file
2. Type FFM [Filename].txt to see output in the command prompt
3. Type FFM [Filename].txt [Outputfilename].doc to output the results into a text file (output levels 1-3)
4. Type FFM [Filename].txt [Outputfilename].csv to output the results into a csv file (output level 4, Monte Carlo)


Examples of the lower three levels of outputs for Input.txt follow. The 4th level provides a table of results with inputs varied within Monte Carlo parameters.

BASIC OUTPUT
****** Results ******

Output Level: Basic

Flame length (m)                  Overall:        11.65

Flame angle (deg)                 Overall:        63.62

Flame tip height (m)              Overall:        14.48

Flame origin height (m)           Overall:        10.65

Rate of spread (km/h)             Overall:         0.15


DETAILED OUTPUT
****** Results ******

Output Level: Detailed

Flame length (m)                  Overall:        11.65
                                  Surface:         0.82
                                  Near-surface:    0.63
                                  Elevated:        1.24
                                  Mid-storey:      5.13
                                  Canopy:         11.65

Flame angle (deg)                 Overall:        63.62
                                  Surface:        74.80
                                  Near-surface:   70.12
                                  Elevated:       49.56
                                  Mid-storey:     63.81
                                  Canopy:         63.89

Flame tip height (m)              Overall:        14.48
                                  Surface:         0.73
                                  Near-surface:    0.59
                                  Elevated:        1.08
                                  Mid-storey:      5.43
                                  Canopy:         14.48

Flame origin height (m)           Overall:        10.65
                                  Surface:         0.00
                                  Near-surface:    0.24
                                  Elevated:        0.68
                                  Mid-storey:      3.26
                                  Canopy:         10.65

Species flame tip heights (m)     Near-surface:    0.60 Joycea pallida
                                  Near-surface:    0.51 Poa meionectes
                                  Elevated:        1.08 Cassinia longifolia
                                  Elevated:        1.61 Eucalyptus rossii
                                  Mid-storey:      5.43 Eucalyptus macrorhyncha
                                  Mid-storey:      5.43 Eucalyptus rossii
                                  Canopy:         15.42 Eucalyptus macrorhyncha
                                  Canopy:         13.84 Eucalyptus rossii

Rate of spread (km/h)             Overall:         0.15
                                  Surface:         0.11
                                  Near-surface:    0.15
                                  Elevated:        0.00
                                  Mid-storey:      0.00
                                  Canopy:          0.00

Proportion of stratum burnt (%):  Near-surface:   100
                                  Elevated:        72
                                  Mid-storey:      82
                                  Canopy:          91

Flame depth (m):                                   0.5
Crown fire type:                                Passive
Crown run length (m):                              0.0
Crown run velocity (km/h)                         0.00
Wind reduction factor:                          3.18
Scorch height McArthur (m):                      33.98
Scorch height Luke McArthur (m):                 86.89
Scorch height Van Wagner (m):                    16.85
Scorch height Van Wagner with wind (m):           0.43


COMPREHENSIVE OUTPUT
****** Results ******

Output Level: Comprehensive

Flame length (m)                  Overall:        11.65
                                  Surface:         0.82
                                  Near-surface:    0.63
                                  Elevated:        1.24
                                  Mid-storey:      5.13
                                  Canopy:         11.65

Flame angle (deg)                 Overall:        63.62
                                  Surface:        74.80
                                  Near-surface:   70.12
                                  Elevated:       49.56
                                  Mid-storey:     63.81
                                  Canopy:         63.89

Flame tip height (m)              Overall:        14.48
                                  Surface:         0.73
                                  Near-surface:    0.59
                                  Elevated:        1.08
                                  Mid-storey:      5.43
                                  Canopy:         14.48

Flame origin height (m)           Overall:        10.65
                                  Surface:         0.00
                                  Near-surface:    0.24
                                  Elevated:        0.68
                                  Mid-storey:      3.26
                                  Canopy:         10.65

Species flame tip heights (m)     Near-surface:    0.60 Joycea pallida
                                  Near-surface:    0.51 Poa meionectes
                                  Elevated:        1.08 Cassinia longifolia
                                  Elevated:        1.61 Eucalyptus rossii
                                  Mid-storey:      5.43 Eucalyptus macrorhyncha
                                  Mid-storey:      5.43 Eucalyptus rossii
                                  Canopy:         15.42 Eucalyptus macrorhyncha
                                  Canopy:         13.84 Eucalyptus rossii

Rate of spread (km/h)             Overall:         0.15
                                  Surface:         0.11
                                  Near-surface:    0.15
                                  Elevated:        0.00
                                  Mid-storey:      0.00
                                  Canopy:          0.00

Proportion of stratum burnt (%):  Near-surface:   100
                                  Elevated:        72
                                  Mid-storey:      82
                                  Canopy:          91

Flame depth (m):                                   0.5
Crown fire type:                                Passive
Crown run length (m):                              0.0
Crown run velocity (km/h)                         0.00
Wind reduction factor:                          3.18
Scorch height McArthur (m):                      33.98
Scorch height Luke McArthur (m):                 86.89
Scorch height Van Wagner (m):                    16.85
Scorch height Van Wagner with wind (m):           0.43

Ignition paths

Run type:                 With canopy
Path type:                Plant path
Level:                    Near-surface
Species:                  Joycea pallida
Flame duration (sec):     1.96
Ignition start time step: 1

Incident
Length	Depth	Dist	Temp	Drying	IDT
0.82	0.00	0.09	970.33	1.0000	0.67


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-0.20	0.00	-0.13	0.24	0.25	0.62
2	-0.20	0.00	-0.13	0.24	0.25	0.62

Run type:                 With canopy
Path type:                Plant path
Level:                    Near-surface
Species:                  Poa meionectes
Flame duration (sec):     1.10
Ignition start time step: 1

Incident
Length	Depth	Dist	Temp	Drying	IDT
0.82	0.00	0.09	970.33	1.0000	0.54


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-0.20	0.00	-0.13	0.24	0.25	0.52
2	-0.20	0.00	-0.13	0.24	0.25	0.52

Run type:                 With canopy
Path type:                Plant path
Level:                    Elevated
Species:                  Cassinia longifolia
Flame duration (sec):     2.46
Ignition start time step: 1

PreHeating
Length	Depth	Dist	Temp	Drying	Duration
0.82	0.00	0.47	835.80	0.3774	1.00


Incident
Length	Depth	Dist	Temp	Drying	IDT
0.83	0.25	0.47	848.76	0.3774	0.59


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-0.21	0.31	-0.17	0.47	0.17	0.56
2	-0.21	0.31	0.21	0.66	0.55	1.20
3	-0.21	0.31	0.21	0.66	0.55	1.20
4	-0.17	0.47	0.21	0.66	0.43	1.01

Run type:                 With canopy
Path type:                Plant path
Level:                    Elevated
Species:                  Eucalyptus rossii
Flame duration (sec):     15.07
Ignition start time step: 1

PreHeating
Length	Depth	Dist	Temp	Drying	Duration
0.82	0.00	0.47	835.80	0.4671	1.00


Incident
Length	Depth	Dist	Temp	Drying	IDT
0.83	0.25	0.47	848.76	0.4671	0.85


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-0.21	0.31	-0.19	0.39	0.08	0.77
2	-0.21	0.31	0.21	0.68	0.56	2.05
3	-0.21	0.31	0.21	0.68	0.56	2.05
4	-0.21	0.31	0.21	0.68	0.56	2.05
5	-0.21	0.31	0.21	0.68	0.56	2.05
6	-0.21	0.31	0.21	0.68	0.56	2.05
7	-0.21	0.31	0.21	0.68	0.56	2.05
8	-0.21	0.31	0.21	0.68	0.56	2.05
9	-0.21	0.31	0.21	0.68	0.56	2.05
10	-0.21	0.31	0.21	0.68	0.56	2.05
11	-0.21	0.31	0.21	0.68	0.56	2.05
12	-0.21	0.31	0.21	0.68	0.56	2.05
13	-0.21	0.31	0.21	0.68	0.56	2.05
14	-0.21	0.31	0.21	0.68	0.56	2.05
15	-0.21	0.31	0.21	0.68	0.56	2.05
16	-0.21	0.31	0.21	0.68	0.56	2.05
17	-0.19	0.39	0.21	0.68	0.50	1.91

Run type:                 With canopy
Path type:                Plant path
Level:                    Mid-storey
Species:                  Eucalyptus rossii
Flame duration (sec):     15.07
Ignition start time step: 3

PreHeating
Length	Depth	Dist	Temp	Drying	Duration
0.82	0.00	1.92	273.13	0.8655	3.00
0.63	0.25	1.95	206.23	0.8240	2.00


Incident
Length	Depth	Dist	Temp	Drying	IDT
1.97	0.81	1.92	728.88	0.8240	2.09
1.97	0.81	1.92	728.88	0.4992	1.27
1.85	0.48	1.94	651.59	0.3030	0.98


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-0.36	1.41	-0.30	1.61	0.21	1.29
2	-0.36	1.41	0.02	2.42	1.08	3.19
3	-0.36	1.41	0.71	3.26	2.14	4.94
4	-0.36	1.41	0.71	3.26	2.14	4.94
5	-0.36	1.41	0.71	3.26	2.14	4.94
6	-0.36	1.41	0.71	3.26	2.14	4.94
7	-0.36	1.41	0.71	3.26	2.14	4.94
8	-0.36	1.41	0.71	3.26	2.14	4.94
9	-0.36	1.41	0.71	3.26	2.14	4.94
10	-0.36	1.41	0.71	3.26	2.14	4.94
11	-0.36	1.41	0.71	3.26	2.14	4.94
12	-0.36	1.41	0.71	3.26	2.14	4.94
13	-0.36	1.41	0.71	3.26	2.14	4.94
14	-0.36	1.41	0.71	3.26	2.14	4.94
15	-0.36	1.41	0.71	3.26	2.14	4.94
16	-0.36	1.41	0.71	3.26	2.14	4.94
17	-0.30	1.61	0.71	3.26	1.94	4.63
18	0.02	2.42	0.71	3.26	1.09	3.21

Run type:                 With canopy
Path type:                Plant path
Level:                    Mid-storey
Species:                  Eucalyptus macrorhyncha
Flame duration (sec):     15.07
Ignition start time step: 3

PreHeating
Length	Depth	Dist	Temp	Drying	Duration
0.82	0.00	1.92	273.13	0.8655	3.00
0.63	0.25	1.95	206.23	0.8240	2.00


Incident
Length	Depth	Dist	Temp	Drying	IDT
1.97	0.81	1.92	728.88	0.8240	2.09
1.97	0.81	1.92	728.88	0.4992	1.27
1.85	0.48	1.94	651.59	0.3030	0.98


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-0.36	1.41	-0.30	1.61	0.21	1.29
2	-0.36	1.41	0.02	2.42	1.08	3.19
3	-0.36	1.41	0.71	3.26	2.14	4.94
4	-0.36	1.41	0.71	3.26	2.14	4.94
5	-0.36	1.41	0.71	3.26	2.14	4.94
6	-0.36	1.41	0.71	3.26	2.14	4.94
7	-0.36	1.41	0.71	3.26	2.14	4.94
8	-0.36	1.41	0.71	3.26	2.14	4.94
9	-0.36	1.41	0.71	3.26	2.14	4.94
10	-0.36	1.41	0.71	3.26	2.14	4.94
11	-0.36	1.41	0.71	3.26	2.14	4.94
12	-0.36	1.41	0.71	3.26	2.14	4.94
13	-0.36	1.41	0.71	3.26	2.14	4.94
14	-0.36	1.41	0.71	3.26	2.14	4.94
15	-0.36	1.41	0.71	3.26	2.14	4.94
16	-0.36	1.41	0.71	3.26	2.14	4.94
17	-0.30	1.61	0.71	3.26	1.94	4.63
18	0.02	2.42	0.71	3.26	1.09	3.21

Run type:                 With canopy
Path type:                Plant path
Level:                    Canopy
Species:                  Eucalyptus rossii
Flame duration (sec):     7.01
Ignition start time step: 3

PreHeating
Length	Depth	Dist	Temp	Drying	Duration
0.82	0.00	6.90	95.25	0.9661	8.00
0.63	0.25	7.19	75.23	0.9613	2.00
0.89	0.26	13.99	69.00	0.9514	5.00


Incident
Length	Depth	Dist	Temp	Drying	IDT
6.94	2.95	6.79	747.10	0.9514	2.30
6.94	2.95	6.79	747.10	0.5583	1.35
6.98	2.62	6.78	741.52	0.3276	0.81


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-2.14	4.93	-2.00	5.50	0.59	1.63
2	-2.14	4.93	-1.74	6.53	1.65	3.27
3	-2.14	4.93	0.59	7.73	3.91	6.36
4	-2.14	4.93	1.39	10.65	6.72	10.02
5	-2.14	4.93	1.39	10.65	6.72	10.02
6	-2.14	4.93	1.39	10.65	6.72	10.02
7	-2.14	4.93	1.39	10.65	6.72	10.02
8	-2.14	4.93	1.39	10.65	6.72	10.02
9	-2.00	5.50	1.39	10.65	6.17	9.31
10	-1.74	6.53	1.39	10.65	5.17	8.02
11	0.59	7.73	1.39	10.65	3.03	5.19

Run type:                 With canopy
Path type:                Plant path
Level:                    Canopy
Species:                  Eucalyptus macrorhyncha
Flame duration (sec):     10.15
Ignition start time step: 3

PreHeating
Length	Depth	Dist	Temp	Drying	Duration
0.82	0.00	6.90	95.25	0.9665	8.00
0.63	0.25	7.19	75.23	0.9618	2.00
0.89	0.26	13.99	69.00	0.9520	5.00


Incident
Length	Depth	Dist	Temp	Drying	IDT
6.94	2.95	6.79	747.10	0.9520	2.34
6.94	2.95	6.79	747.10	0.5649	1.39
6.98	2.62	6.78	741.52	0.3352	0.84


Ignited segments:
Time	StartX	StartY	EndX	EndY	SegLen	FlameLen
1	-2.14	4.93	-2.00	5.50	0.59	2.25
2	-2.14	4.93	-1.61	7.05	2.18	5.03
3	-2.14	4.93	1.02	9.20	5.31	9.55
4	-2.14	4.93	1.90	10.65	7.00	11.85
5	-2.14	4.93	1.90	10.65	7.00	11.85
6	-2.14	4.93	1.90	10.65	7.00	11.85
7	-2.14	4.93	1.90	10.65	7.00	11.85
8	-2.14	4.93	1.90	10.65	7.00	11.85
9	-2.14	4.93	1.90	10.65	7.00	11.85
10	-2.14	4.93	1.90	10.65	7.00	11.85
11	-2.14	4.93	1.90	10.65	7.00	11.85
12	-2.00	5.50	1.90	10.65	6.46	11.12
13	-1.61	7.05	1.90	10.65	5.03	9.16
14	1.02	9.20	1.90	10.65	1.70	4.26

