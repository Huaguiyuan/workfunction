Workfunction
============

A Fortran program to calculate a 1D planar averaged electrostatic potential from a 3D potential grid for the density functional theory code VASP. It can be used to compute the workfunction (or ionisation potential) for a material surface or as an alignment technique for comparing the electronic eigenvalues of different systems. 

We recommend [MacroDensity](https://github.com/WMD-Bath/MacroDensity), which is a lot more flexible and powerful.

Files
------------
- workfunction_v1.f, pre-2006 as vtotav.f written by Andreas Eichler
- workfunction_v2.f, compatible with VASP5 output
- workfunction, a mac binary of v2
- LOCPOT.zip, a sample electrostatic potential

Used in
------------
- "Structure, stability and work functions of the low index surfaces of pure indium oxide and Sn-doped indium oxide (ITO) from density functional theory" A. Walsh and C. R. A. Catlow, Journal of Materials Chemistry 20, 10438 (2010). DOI: 10.1039/C0JM01816C 
