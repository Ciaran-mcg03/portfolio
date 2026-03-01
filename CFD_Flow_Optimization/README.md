## Objective
Simulate fluid flow around a 2D airfoil and analyse how shape modifications affect drag and flow patterns. Optional goal: optimise the airfoil for minimal drag.

## Tools
- Python
- FEniCS / PyFoam
- NumPy, Matplotlib
- Optional: GMSH for mesh generation

## Method
1. Defined geometry and boundary conditions.
2. Generated computational mesh.
3. Solved Navier-Stokes equations for laminar/turbulent flow.
4. Compared multiple shapes/angles of attack.
5. Visualised streamlines, pressure contours, and velocity fields.

## Results
- Drag coefficient vs angle of attack plot
- Streamline and velocity contour images
- Observations on flow separation and vortex formation

## Lessons Learned
- Mesh refinement affects convergence and accuracy.
- Flow separation occurs at high angles; subtle shape changes reduce drag.
- Challenges: solver stability, boundary condition tuning.
