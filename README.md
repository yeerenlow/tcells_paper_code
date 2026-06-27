# tcells_paper_code
Quantifying T cell morphodynamics and migration in 3D collagen matrices

https://doi.org/10.48550/arXiv.2401.03595

Original code is available here: https://github.com/hcbiophys/tcells_paper_code

In addition, the following packages are required:
* h5py==3.8.0
* pynrrd==1.0.0
* statsmodels==0.13.5
* vtk==9.1.0

Download the original code and build package, then place files in the corresponding directories.

Note that there is an error in the Jupyter Notebook that the rotation matrix should be transposed in one of the lines when calculating the velocities in the coordinate frame of the cell. I have not yet had the time to correct this error and redo the analysis.
