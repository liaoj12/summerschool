## Heat equation solver: OpenACC data management

Improve the [MPI+OpenACC version](../hybrid-openacc/) by manually defining the
data movements between the host CPU and the GPU device.

To minimise data transfers between the host CPU and the GPU device, add data
movement directives that will only transfer data when needed.


## Modules to load
1. `pgi/19.1`   
2. `openmpi/3.1.4`   
3. `libpng/1.6`
