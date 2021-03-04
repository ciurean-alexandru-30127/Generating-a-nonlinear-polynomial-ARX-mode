# Generating-a-nonlinear-polynomial-ARX-mode
A dataset is given, measured on an unknown dynamic system with one input and one output. The
order of the dynamics is not larger than three, and the dynamics may be nonlinear while the output may
be affected by noise. Your task is to develop a black-box model for this system, using a polynomial,
nonlinear ARX model. A second data set measured on the same system is provided for validating the
developed model. The two data sets will be given in a MATLAB data file, with variables id and val
containing the two sets as objects of type iddata from the System Identification toolbox. Recall that
the input, output, and sampling time are available on fields u, y, Ts respectively. As a backup in case
the system identification toolbox is not installed on the computer, id array and val array contain
the same two datasets but now in an array format, with the structure: time values on the first column,
input on the second column, and output on the last column.
