# summa-bokeh
The objective of our project is to investigate the effects from different albedo model schemes and snow water drainage parameters on SUMMA model output. To expedite investigation at differnt temporal scales we showcase the bokeh interactive python visualization library.

Link to Hydroshare resource: https://www.hydroshare.org/resource/38d4f881e5b946dabb1fe5d14b23aab7  
***

## Snow water drainage (from Homework 1F)

#### Parameters:  

<b>Run 1</b> - use the default setup (same as in exercises 1 and 2) 
 * Fcapil = 0.06
 * k_snow = 0.015
 * mw_exp = 3.0
 
<b>Run 2</b> - reduce the capillary retention by a factor of three
 * Fcapil = 0.02
 
<b>Run 3</b> - double the hydraulic conductivity of snow
 * k_snow = 0.03
 
<b>Run 4</b> - set mw_exp to 1.0 (exponent of melt water flow)
 * mw_exp = 1.0
 
<b>Run 5</b> - combine all previous changes
 * Fcapil = 0.02
 * k_snow = 0.03
 * mw_exp = 1.0

#### Questions:

1. Which parameter exerts the greatest control on drainage?
2. What further testing could be done to parse out model sensitivity? 


## Albedo (from Homework 1E) 

#### Decision schemes:
* variable decay (default) vs constant decay 

#### Parameters:
* albedoDecayRate
 * 100000.0 -> 360000.0

#### Questions: 
 
1. What has a bigger effect? A change in parameterization (variable to constant decay) or a parameter value change?




