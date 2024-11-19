## Elliptical Gravitational Lenses - The SIE Model

### Overview
This repository provides an implementation of the Singular Isothermal Ellipsoid (SIE) gravitational lens model, a generalisation of the Singular Isothermal Sphere (SIS). The SIE model incorporates ellipticity by modifying the radial distance definition, leading to lensing characteristics that depend on the axis ratio of the ellipses. This code allows for the exploration of lensing properties, such as critical lines, caustics, image multiplicity, and magnification.

### Features
- **Elliptical Surface Density:** Computes the surface density of the lens, constant on ellipses with specified axis ratios.
- **Lensing Potential:** Implements the lensing potential using polar coordinates and Green's method.
- **Deflection Angles:** Calculates deflection angles in polar coordinates, highlighting their independence from radial distance.
- **Critical Lines and Caustics:** Computes and visualises the critical line and caustic structures, including their intersections with coordinate axes.
- **Image Multiplicity:** Implements a root-finding algorithm to determine the positions of multiple images for a given source position.
- **Magnification Analysis:** Calculates magnifications and studies the parity of lensed images.

### Visualisations
- Caustics and cuts in the source plane.
- Critical lines and tangential caustics in the image plane.
- Image configurations for various source positions, including sources on cusps and folds.
- Dependence of caustic and cut structures on the ellipticity parameter \( f \).

### Highlights
- Supports both analytic and numerical approaches to solving the lens equation.
- Implements extended source reconstruction, enabling magnification and distortion studies for various source shapes and sizes.
- Provides flexibility to experiment with different ellipticity parameters and source configurations.

### Usage
Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sie-gravitational-lenses.git
   ```


### Reference
The notebook elliptical_lens.ipynb and texts were adapted from Professor Meneghetti's gravitational lensing lectures, available at https://github.com/maxmen/LensingLectures/tree/master.