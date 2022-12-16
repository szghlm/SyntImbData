# SyntImbData

A synthetic dataset collection of 320 imbalanced datasets for binary classification problems.


## Content of the data files

Each file consists of two parts, a header and a data part.

### Structure of the headers:

@relation Name of the data set SyntheticData-N_600-D_4-IR_16.00-Z_0-O_0.7-CL_1_1_0
@attribute X0
...
@attribute X{D-1}
@attribute Class encoded_categorical {0, 1}
@inputs X0, X1, X2, ...,  X{D-1}
@output Class
 

### Data part:
The data part starts with the line after the "@data" string. Each line contains values belonging to one sample, followed by the label of the corresponding class, separated by commas.

@data
Comma separated values:
x0,x1,x2,...,x{D-1},class_label







Creator of the data sets: 
Attila Fazekas, University of Debrecen
Szilvia Szeghalmy, University of Debrecen

