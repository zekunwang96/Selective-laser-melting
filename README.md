# Selective-laser-melting
OpenFOAM solver for selective melting
Copy the files in isoAdvector-mastert/OpenFOAM-3.0.1/src/ into the src in your OpenFOAM and then compile isoAdvector

        ./Allwmake

Then compile the solver SLMv5. This is only a very basic solver coded according to Wang et al. Computational Mechanics 63(4):649–661.
        cd SLMv5 
        wmake
A simple test case with extremely coarse mesh is given: case-SLMt2HUNAN2.  The executables within the case are given to you to figure out their usages by yourself, LOL.

Please also cite the Roenby's articles related to isoAdvector
