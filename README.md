## preCICE-OpenFOAM(v2306)-adapter(v1.3.1)-rhoPimpleFoam

Two variables are introduced in`FSI/ForceBase.H` to convert the pressure from absolute to relative by substracting the `atmosphere pressure`.

1. `./Allclean`
2. `./Allwmake -j` or `./Allwmake`
