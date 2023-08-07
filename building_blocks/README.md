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
