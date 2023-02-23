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
 - smallest set of smallest rings (SSSR)
 - aromaticity in %
 - Number of  C-OH, C=O and C-O-C moities.


In our simulations we used used OPLS-AA force field.\
To generate a topology files, please follow instructions on http://zarbi.chem.yale.edu/ligpargen and http://polypargen.com.

----

`models/`

Molecular models of bulk and surface-exposed woody biochars produced at low (400ºC), medium (600ºC) and high (800ºC) highest treatment temperatures (see Wood et al. 2023 for details).

The folder contains all files necessary for simulation with GROMACs:
 - `.gro` files for bulk and surface-exposed systems
 - `.top`, `.itp` and `.atp` files assigning forcefield parameters to the structures
 - `oplsaa.ff` an OPLS-AA forcefield directory


-----
CITE as:
- R. Wood, O. Masek, V. Erastova, Part I: ...
- R. Wood, O. Masek, V. Erastova, Part II: ...


