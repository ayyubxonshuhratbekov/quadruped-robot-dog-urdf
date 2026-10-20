Robotic dog high-fidelity ready URDF for researchers, builders, and anyone who wants to simulate a robotic dog model on physics simulators like MuJoCo, Isaac Sim, etc.

The original model belonged to LubLune Project’s Arduino Robot Dog. As they optimized their upload for 3D printing, I had to convert the original STL files to STEP. From there, I optimized the triangular edges into smooth curves and modified parts where necessary to optimize them for the assembly process.

**Simulation Optimization**

To ensure the sim-to-real gap is as minimal as possible, I made sure to set proper joint angle constraints. Additionally, the densities of the materials were altered to match a 15% infill with 2 walls setting in a 3D printer slicer. A battery pack with proper density settings was also added to accurately reflect the real-world weight distribution and Center of Mass (CoM) calculations.

If you have any further suggestions or questions, feel free to contact me on my LinkedIn! -- https://www.linkedin.com/in/ayyubxon-shuxratbekov
