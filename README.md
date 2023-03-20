**Biochar Molecular Models**

By Rosie Wood (rosie.wood@ed.ac.uk) and Valentina Erastova (valentina.erastova@ed.ac.uk)

---

`exper_data/` 

Data used for model development in `.csv` format, plus plotted data in `.pdf` format.

----

`building_blocks/`

Molecular building blocks used throughout our model development as both `.mol` and `.pdb` files,\
plus `.csv` file containing the chemical information of these building blocks:
 - number of atoms (n_atoms)
 - chemical formula (chemformula)
 - number of C, H and O atoms
 - H/C and O/C molar rations
 - molecular weight in g/mol (MW)
 - mass in g 
 - domain size, as smallest set of smallest rings (SSSR)
 - aromaticity in %
 - Number of  C-OH, C=O and C-O-C moities.

An example renderings of structures can be found in the `renderings/` directory

In our simulations we used used OPLS-AA force field.\
To generate a topology files, please follow instructions on http://zarbi.chem.yale.edu/ligpargen and http://polypargen.com.

----

`models/`

Molecular models of bulk and surface-exposed woody biochars produced at low (400ºC), medium (600ºC) and high (800ºC) highest treatment temperatures (see Wood et al. 2023 for details).

The folder contains all files necessary for simulation with GROMACS:
 - `.gro` files for bulk and surface-exposed systems
 - `.top` files assigning forcefield parameters for each structure
 - `oplsaa.ff` an OPLS-AA forcefield directory


-----
More more information see the following publications. \
If using these models, please cite as:
- R. Wood, O. Masek, V. Erastova,Biochars at the molecular level. Part 1 -- Insights into the molecular structures within biochars
[https://doi.org/10.48550/arXiv.2303.09661](https://doi.org/10.48550/arXiv.2303.09661)

- R. Wood, O. Masek, V. Erastova, Biochars at the molecular level. Part 2 -- Development of realistic molecular models of biochars
[https://doi.org/10.48550/arXiv.2303.09907](https://doi.org/10.48550/arXiv.2303.09907)


