The canonical threshold libraries of 2 to 8 input variables are constructed with the canonicalize procedure [1] that iteratively minimizing maximum weight via ILP without symmetry detection preprocess.

The threshold libraries of 2 to 5 input variables are constructed from lists of NPN functions.

The threshold library of 6 input variables is constructed by first enumerating all 6-input unate functions, converting them into threshold functions, and then removing redundant NPN equivalent functions by checking their weights and threshold value.

The threshold libraries of 7 to 8 input variables are constructed by first enumerating all 8- and 9-input self-dual threshold functions with the L2 lattice [2], converting them into linear forms, cofactoring each input variables to obtain all 7- and 8-input NPN threshold classes, and finally applying the canonicalization procedure.


References:

[1] Lee, Siang-Yun, Nian-Ze Lee, and Jie-Hong R. Jiang. "Canonicalization of threshold logic representation and its applications." Proceedings of the International Conference on Computer-Aided Design. ACM, 2018.

[2] Winder, Robert O. "Enumeration of seven-argument threshold functions." IEEE Transactions on electronic computers 3 (1965): 315-325.