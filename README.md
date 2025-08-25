## preCICE(v3.1.2)-OpenFOAM(v2306)-adapter(v1.3.1)-rhoPimpleFoam

Two variables are introduced in`FSI/ForceBase.H` to convert the pressure from absolute to relative by substracting the `atmosphere pressure`.

1. Remember to edit `Make/files` to make sure to rename the shared object file to avoid overwriting the original version
2. `./Allclean`
3. `./Allwmake -j` or `./Allwmake`


If `preCICE` is installed in a cluster by `spack`, remember to `spack load precice-version` before builting.
