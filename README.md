content moved to:  
https://gitlab.cern.ch/asevcenc/el7cvmfs.dock  
https://github.com/adriansev/el7cvmfs.dock  

Image found at : `oras://registry.cern.ch/asevcenc/el7cvmfs:latest`

# el7cvmfs
Generic HEP oriented container to be used as wrapper for CVMFS distributed software   
Built on the docker template https://github.com/adriansev/el7cvmfs.dock   

Given the Singularity requirements, the cvmfs fusemount can be done only from command line,   
hence the need of wrapper scripts that will use this containers, see https://github.com/adriansev/cvmfs2go   
