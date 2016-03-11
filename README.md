# CIC_filter
CIC Filter Comb

The Transfer Function of this filter is H(z) = (1-z^(-rg)/1-z^-1)^m. This filter is written in verilog and is used for interpolation and decimation. The below parameteres configure the filter's data operation.

dw : input data width 
idw/odw : i/o data width for integrators
m :  order of teh filter
r : inteprolation decimation ratio
g : differential delay in combs.
