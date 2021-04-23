[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4203)

# el7cvmfs
Generic HEP oriented container to be used as wrapper for CVMFS distributed software   
Built on the docker template https://github.com/adriansev/el7cvmfs.dock   

Given the Singularity requirements, the cvmfs fusemount can be done only from command line,   
hence the need of wrapper scripts that will use this containers, see https://github.com/adriansev/cvmfs2go   
