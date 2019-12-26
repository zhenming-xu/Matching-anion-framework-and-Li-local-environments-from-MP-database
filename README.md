# Matching anion framework and analyzing lithium local environments from the Material Project database

These projects aim to get the distribution of anion framework type and lithium coordination environment of lithium compounds from the Materials Project Database based on the Pymatgen code. The analyses of lithium coordination environment were performed by the ChemEnv code as integrated in the Pymatgen package. Only the stable binary, ternary and quaternary lithium compounds with energy above hull less than 0.05 eV/atom were considered. 


# Some dependencies are need.
Pymatgen, pandas, numpy, functools, matplotlib, collections, seaborn


# Step
1. Open "Getting stable Li-M-S materials from Material Project Database.ipynb" by jupyter lab, and run it to get the stable lithium compounds entries from the Materials Project Database.

2. Run "Matching anion framework of sulfides from MP database.ipynb" to get the distribution of anion framework type.

3. Run "Distribution of Li local environments of sulfides in Material Project Database.ipynb" to get the distribution of lithium coordination environment.


# If you use these codes, please cite our paper!
[1] Zhenming Xu, Xin Chen, Ronghan Chen, Xin Li, Hong Zhu, Anion charge-lattice volume dependent Li ion migration in compounds  with the face-centered cubic anion frameworks, submitted

[2] Waroquiers, D.; Gonze, X.; Rignanese, G.-M.; Welker-Nieuwoudt, C.; Rosowski, F.; Göbel, M.; Schenk, S.; Degelmann, P.; André, R.; Glaum, R.; Hautier, G. Statistical Analysis of Coordination Environments in Oxides. Chem. Mater. 2017, 29 (19), 8346-8360, DOI: 10.1021/acs.chemmater.7b02766.

[3] Ong, S. P.; Richards, W. D.; Jain, A.; Hautier, G.; Kocher, M.; Cholia, S.; Gunter, D.; Chevrier, V. L.; Persson, K. A.; Ceder, G. Python Materials Genomics (pymatgen): A robust, open-source python library for materials analysis. Computational Materials Science 2013, 68, 314-319, DOI: 10.1016/j.commatsci.2012.10.028.


# If you have any question, please contact me!

 author: Zhenming Xu
 
 email: 15216105346@163.com
