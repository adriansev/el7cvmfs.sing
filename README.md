[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4203)

# el7cvmfs
Generic HEP oriented container to be used as wrapper for CVMFS distributed software

The CVMFS base configuration is a merge of:   
* cvmfs-config-default-1.7-1.noarch.rpm
* cvmfs-config-egi-2.4-2.3.obs.el7.noarch.rpm
* cvmfs-config-osg-2.4-1.osg35.el7.noarch.rpm
   

Given the Singularity requirements, the cvmfs mount can be done only from command line,   
hence the need of wrapper scripts that will use these containers.   
