# tleap_sander_C4Pairwise
a new version of tleap that supports atom-specific pairwise C4 interaction

Usage: download "tleap.zip" and "sander.zip", "md.h", unzip and replace "amber20_src/AmberTools/src/leap/src/leap", "amber20_src/AmberTools/src/sander", "amber20_src/AmberTools/src/include/md.h" respectively, then follow the installation guide in http://ambermd.org/Installation.php. The new tleap should now support "addC4Pairwise (atom1) (atom2) (c4value)" command, and the new sander should now support "plj1264=1" argument. 
