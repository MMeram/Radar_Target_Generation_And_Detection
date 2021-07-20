# Radar_Target_Generation_And_Detection

The aim of Cell-Averaging Constant False Alarm Rate (CA-CFAR) is to suppress the noise and separate the target signal by averaging the magnitudes of surrounding cells.  

Training and guard cell selection is done in range and speed dimensions as below:

Tr = 12  
Td = 10  

Gr = 4  
Gd = 4  

The offset value is selected not statically but statistically using the quantile function. The magnitude of cells surrounding the CUT is pushed into a vector and its quantile is calculated. The 0.7th quantile and above gave a good result.  
Other than that the two times the standard deviation of this vector yielded also the expected result.  

The details can be read in the generated PDF document.
