# Submission Details

## Participant Information

**Name(s):**

Thomas Ozoroski

**Organization / Affiliation:**

NASA Glenn Research Center / Icing and Acoustics Branch

**Primary Email:**

Thomas.ozoroski@nasa.gov

## Solver Information

**Solver Name and Version:**

GlennICE-v7.0-beta

**Flow Algorithm:**

For the NACA0012: FUN3D v14.3 RANS – Stabilized Finite Element
For the ONERAM6: FUN3D v14.3 RANS – Finite Volume Method

**Turbulence Model:**

For the NACA0012: SA-neg-QCR2000
For the ONERAM6: SA-neg-rough and SA-neg

**Droplet Trajectory Algorithm:**

Lagrangian particle tracking with adaptive time stepping

**Thermodynamic Algorithm:**

HTC is computed from two isothermal wall temperatures. HTC is then augmented through two avenues, none when using a rough-wall turbulence model. The secondary method computes a value of roughness, freezing fraction, and HTC is augmented based upon a tanh enhancement method before being iterated until the runback is considered converged.  

**Surface Grid Deformation Algorithm:**

Prismatoid Extrusion Method 

**Multi-Layer / Multi-Time-Step Methodology:**

None


