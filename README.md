# Some-useful-PyMol-commands

Select residue 223, 206 and 145:

PyMOL>select (i;223 i;206 i;145)

Select all Alanines:

PyMOL>select (r;ala)

Select atoms within 4 Angstrom of residue 206:

PyMOL>select (i;206 around 4)

Change color on chain B:

PyMOL>color red, chain B

Remove chains from display:

PyMOL>hide (chain D,E,F) 

Show Symmetry neighbours:

PyMOL>symexp sym, 1MYW_Venus, all, 3


Align the structure of Tq2 with mCer3:

File -> Open -> 4EN1_mCer3.pdb
File -> Open -> 3ZTF-Tq2-Royant.pdb
PyMOL> hide (chain B) 
PyMOL> align 4EN1_mCer3, 3ZTF-Tq2-Royant



check out:

http://www-cryst.bioc.cam.ac.uk/members/zbyszek/figures_pymol
http://ihome.cuhk.edu.hk/~b102142/pymol/pymol_tutorial.html
http://www.embl.de/~seqanal/courses/commonCourseContent/usingPyMol.html#Further_Information_and_Tutorials_on


