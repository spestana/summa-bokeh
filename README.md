# summa-bokeh
The objective of our project is to investigate the effects from different albedo model schemes and snow water drainage parameters on SUMMA model output. To expedite investigation at differnt temporal scales we showcase the bokeh interactive python visualization library.
***

### Snow water drainage (from Homework 1F)
parameters:  
run 1 - use the default setup (same as in exercises 1 and 2) 
 * Fcapil = 0.06
 * k_snow = 0.015
 * mw_exp = 3.0
 
run 2 - reduce the capillary retention by a factor of three
 * Fcapil = 0.02
 
run 3 - double the hydraulic conductivity of snow
 * k_snow = 0.03
 
run 4 - set mw_exp to 1.0 (exponent of melt water flow)
 * mw_exp = 1.0
 
run 5 - combine all previous changes
 * Fcapil = 0.02
 * k_snow = 0.03
 * mw_exp = 1.0

questions:

1. Which parameter exerts the greatest control on drainage?
2. What further testing could be done to parse out model sensitivity? 


### Albedo (from Homework 1E) 
decision schemes:
* variable decay (default) vs constant decay 

parameters:
* albedoDecayRate
 * 100000.0 -> 360000.0

questions: 
 
1. What has a bigger effect? A change in parameterization (variable to constant decay) or a parameter value change?




