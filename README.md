# CNN_Verilog
CNN`s implementation in verilog(Only one convolution layer and one pooling layer)

## A compeition code
We couldn`t get to the final, so it is the version of alpha(It may look some kind of humble).

## Code  
**P.v** is the top module, input is pixel of the picture and output is the classification(We haven`t implemented it yet)  
**C.v** is the module that do the convolution and pooling things  
**D_mem.v** is the module to store the data from the picture we want to process  
**F_mem.v** , which means *feature memory*, is to store the output come from the C.v module(which is processed data).  
