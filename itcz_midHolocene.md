## Tropical Precipiation and cross-equatorial ocean heat during the mid-Holocene

### Introduction
This project studies the tropical precipitation in the mid-Holocene and its relationship to cross-equatorial atmospheric and oceanic heat transport, using data from 12 CMIP5 coupled models and ECHAM4.6 model. A preliminary look of the relationship shows a contradicting result in CMIP5 models and ECHAM4.6. ```We hypothsize that the difference is because including a full dynamic ocean rather than a slab ocean changed the energy into the atmosphere. ```
<img src="https://github.com/xliu0628/xliu0628.github.io/blob/master/photos/CROPPED-IMG_3%20(1).jpg" align="center" width="100" >



### Methods
#### 1. Relationship between tropical precipitation and cross-equatorial heat transport
Energetic framework suggests that the mean ITCZ is closely linked to the cross-equatorial energy transport by the atmosphere, with a northward displacement of the mean ITCZ corresponding to a southward atmospheric energy transport. 

The ITCZ is quantified using the precipitation centroid is defined as the latitude that delineates an equal area-averaged precipitation between 20N and 20S (Frierson and Hwang 2012; Donohoe et al. 2013).
```
code for the definition of ITCZ
```
We calculate the cross-equatorial AHT in two ways: as an hemispheric difference of net energy into atmosphere, and as the integral of net energy into the atmosphere from the SP to the equator. Both methods give a consistent result. 
```
code for calculating the AHT
```
The relationship between ITCZ and AHT is shown using linear regression: 
```
code and figure
```
#### 2. Decomposing the change in AHT into change in energy from TOA and change in energy from SFC
In equilibrium, changes in the cross-equatorial AHT are related to changes in the hemispheric asymmetry in energy entering the atmosphere from TOA and from the surface, respectively. Decomposing the AHT(EQ) into these two components shows that in almost every model (9 out of 12 models), the change in AHT(EQ) is predominantly due to the change in hemispheric asymmetry in energy entering the atmosphere from surface. 
```
show the figure
```
#### 3. Change in cross-equatorial oceanic heat transport
The excessive energy in the Northern Hemisphere suggests a northward cross-equatorial ocean transport, which is supported by a direct calculation of the ocean heat transport across the equator. We use the monthly climatology of y and T to calculate DOHT(EQ), neglecting the contribution by submonthly covarying anomalies associated with natural variability. The cross-equatorial ocean heat transport caculated this way, however, are close to the exact answer, as shown by the four models that provide the OHT calculated at model grid and at each timestep. 
```
show the code for OHT calculation
```
We future decompose the change in OHT into a dynamic and a thermodynamic contribution, and into contribution from the Atlantic and contribution from the Indo-Pacific. It is clear that change in the OHT is dominated by change in the ocean circulation in the Pacific. 

### Conclusion
The response of the ocean is the key ocean for the northward ITCZ shift during the mid-Holocene. The monsoonal atmospheric response drives spins up the tropical Pacific gyre. Acting on the zonal thermal asymmetry, this change in ocean circulation enhances the northward cross-equatorial heat transport, shifting the ITCZ northward. 
