# tleap_sander_pmemd_C4Pairwise_C4Type
tleap that supports atom-specific pairwise C4 interaction, also takes atom-type-specific C4 commands like ParmEd

Usage: download "tleap_new.zip", "sander_new.zip", "src.zip" and "md_new.h", unzip and replace "amber20_src/AmberTools/src/leap", "amber20_src/AmberTools/src/sander", "amber20_src/src/pmemd/src" and "amber20_src/AmberTools/src/include/md.h" respectively, then follow the installation guide in http://ambermd.org/Installation.php. The new tleap should now support "addC4Pairwise (atom1) (atom2) (c4value)" and "addC4Type (atomtype1) (atometype2) (c4value)". The new sander (includieng sander.MPI) and PMEMD should now support "plj1264=1" argument. PMEMD might need to add "mpi_bcast(C4Pairwise)" in the "prmtop_dat.F90" file. 
