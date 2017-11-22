# wham_spec_fit
Fitting routine based on IDL MPFIT for WHAM spectra.
1. First run intensity on structure to get initial estimate file. 

2. Input structure for intensity.pro must have the following parameters:
IDL> help, params
** Structure <1744958>, 6 tags, length=744, data length=744, refs=1:
   NAME            STRING    'la_on7_la_off24_combine_ha'
   GLON            FLOAT           248.900
   GLAT            FLOAT           51.6100
   VEL             FLOAT     Array[60]
   DATA            FLOAT     Array[60]
   VAR             FLOAT     Array[60]

