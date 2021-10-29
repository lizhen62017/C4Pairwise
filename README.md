# tleap_sander_C4Pairwise_C4Type
tleap that supports atom-specific pairwise C4 interaction, also takes atom-type-specific C4 commands like ParmEd

Usage: download "tleap_new.zip" and "sander_new.zip", "md_new.h", unzip and replace "amber20_src/AmberTools/src/leap", "amber20_src/AmberTools/src/sander", "amber20_src/AmberTools/src/include/md.h" respectively, then follow the installation guide in http://ambermd.org/Installation.php. The new tleap should now support "addC4Pairwise (atom1) (atom2) (c4value)" and "addC4Type (atomtype1) (atometype2) (c4value)". The new sander (includieng sander.MPI) should now support "plj1264=1" argument. 
