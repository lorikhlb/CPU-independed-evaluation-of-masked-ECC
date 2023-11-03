# CPU-independed-evaluation-of-masked-ECC
The files provided contain oen the changes done to the STM32f407-static directory, in which the implementation of the static protected implementaiton of the target paper is present. Also the linker file with changes is provided aswell. 

The Prolead file contains the evluation settings used for the evluation as decribed in the BA-thesis. 
To replicate the results you will need the Prolead repository https://github.com/ChairImpSec/PROLEAD
and the curve 25519 repository https://github.com/sca-secure-library-sca25519/sca25519 respectively. 
For the 25519 repository replacing the folder aswell as the linker file and following others changes done should do the trick.
For Prolead you want to add the file to the example/Software/
