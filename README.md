# AdaptiveRefinMesh

The dynamic meshing in a two-phase flow solver has been modified to allow for dynamic meshing around fluid-fluid interfaces in two-dimensional planar and axisymmetric geometries. The modification to these geometries reduces computational time and increases interface accuracy.

Installation/Compiling
----------------------
1. Copy the entire directory to:  $WM_PROJECT_USER_DIR/src/
2. cd $WM_PROJECT_USER_DIR/src/dynamicMeshRefine_2D+Axi/dynamicMesh
3. wclean
   wmake libso
4. cd $WM_PROJECT_USER_DIR/src/dynamicMeshRefine_2D+Axi/dynamicFvMesh
5. wclean
   wmake libso
