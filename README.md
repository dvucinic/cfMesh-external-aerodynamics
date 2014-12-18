cfMesh-external-aerodynamics
============================

Exploration of external aerodynamics simulations with cfMesh and OpenFOAM.

For reasons unkown, simulations of external aerodynamics problems with
simpleFoam tend to diverge with some regularity if the underlying mesh
was created with cfMesh as opposed to snappyHexMesh.

To run the simulation:

cd foam/019-boundaries

./mesh

cd outputs/run-*/reproduce

./wind 80 30
