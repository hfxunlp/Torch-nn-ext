# Torch-nn-ext
some extention to torch and nn package

getmaxout(inputs,outputs) returns a maxout module,with size(inputs,outputs),the inputs and outputs data size should be batch*datasize

getres(module_encap) returns a residue module by encapsulate module_encap, in the most simple use module_encap could be just a nn.Linear, module_encap's inputs size must be the same with the outputs size.
