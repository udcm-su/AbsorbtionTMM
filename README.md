# AbsorptionTMM
We intend to use the transfer matrix representation to calculate the local absorbed energy density as a function of space. 
This way multiple reflections and interferences in thin films, different incident angles and polarizations, s & p, are considered.
The description of the formulas and the way we are implementing them can be found here: [Description](https://github.com/udcm-su/AbsorptionTMM/blob/master/Transfermatrix_Description.pdf)

  --- 
### Use
The [TMM_abs.py](https://github.com/udcm-su/AbsorptionTMM/blob/master/TMM_abs.py) file works as function library and the [Cobalt_example.py](https://github.com/udcm-su/AbsorptionTMM/blob/master/Cobalt_example.py) is a file which gives an example on how to use the code. 
### An example

  
| Platinum       	| 3nm layer    	| n = 1.0433 + i3.0855 	|
|----------------	|--------------	|----------------------	|
| Cobalt         	| 15nm layer   	| n = 1.0454 + i3.2169 	|
| Chromium       	| 5nm layer    	| n = 2.0150 + i2.8488 	|
| Magnesium Oxide 	| semi inf- layer 	| n = 1.7660           	|


  
  <img src="https://github.com/udcm-su/AbsorptionTMM/blob/master/LayerPicc.png" width="860" height="600" />

As absorption has units (power/volume), the profile in the plot, which has been normalized with respect to the light power density on the material (power/area), is given in units (1/length).

The angle is given from the surface normal. (0° is perpendicular and 90° is grazing). 


### Reference
[Steven J. Byrnes. Multilayer optical calculations. arXiv:1603.02720v3, 2018.
](https://arxiv.org/abs/1603.02720)


