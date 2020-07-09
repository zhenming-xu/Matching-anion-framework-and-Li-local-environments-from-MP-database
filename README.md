# Matching anion framework and analyzing lithium local environments from the Material Project database

These projects aim to get the distribution of anion framework type (fcc, bcc and hcp) and lithium coordination environment (octahedral and tetrahedral Li coordination) of lithium compounds from the Materials Project Database based on the Pymatgen code. The analyses of lithium coordination environment were performed by the ChemEnv code as integrated in the Pymatgen package. Only the stable binary, ternary and quaternary lithium compounds with energy above hull less than 0.05 eV/atom were considered. 

![Matched-anion-frameworks](https://github.com/zhenming-xu/Matching-anion-framework-and-Li-local-environments-from-MP-database/blob/master/Matched-anion-frameworks.png)



![Lithium-coordination-environments](https://github.com/zhenming-xu/Matching-anion-framework-and-Li-local-environments-from-MP-database/blob/master/Lithium-coordination-environments.png)

# Some dependencies are need
Pymatgen, pandas, numpy, functools, matplotlib, collections, seaborn


# Step
1. Open "Getting stable Li-M-S materials from Material Project Database.ipynb" by jupyter lab, and run it to get the stable lithium compounds entries from the Materials Project Database.

2. Run "Matching anion framework of sulfides from MP database.ipynb" to get the distribution of anion framework type.

3. Run "Distribution of Li local environments of sulfides in Material Project Database.ipynb" to get the distribution of lithium coordination environment.


# Citing
If you use these codes in your research, please consider citing the following work:

1. Zhenming Xu, Xin Chen, Ronghan Chen, Xin Li, Hong Zhu, Anion charge-lattice volume dependent Li ion migration in compounds  with the face-centered cubic anion frameworks, npj Comput Mater 2020, 6, 47.

2. Zhenming Xu, Hong Zhu, Anion Charge and Lattice Volume Maps for Searching Lithium Superionic Conductors, Chem. Mater. 2020, 32, 11, 4618–4626


# If you have any question, please contact me!

 Author: Zhenming Xu
 
 E-mail: 15216105346@163.com
