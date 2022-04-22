# earthworks_dazlich
This repository has the script to checkout the earthworks version of CESM with
mpas components. Right now it checks out cesm2_3_beta08. The scripts modifies the checked out code
with the code in cesm.mods. These are for CESM itself, ccs_config, mpas-ocean, cmeps and cime. When I figure out github
better and can merge upstream changes well the mod code will go into my branches of those repositories.
To complete this, I have a fork of E3SM here with my additions to the code in the drivers and the buildlib 
scripts.
