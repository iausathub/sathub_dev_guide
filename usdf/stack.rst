#################
Stack Access
#################

This document describes access to weeklies and release versions of the
stack available at the LSST Data
Facility during the interim period where the Rubin filesystems at SLAC
go into production mode on our own hardware, and while user and
project data are being transferred from NCSA.

Access to the stack is available via cvmfs (e.g. ``w_2022_11``)

``source /cvmfs/sw.lsst.eu/linux-x86_64/lsst_distrib/w_2022_11/loadLSST.bash``

and see which versions are available by:

``ls /cvmfs/sw.lsst.eu/containers/singularity/lsst_distrib/``

and

``ls /cvmfs/sw.lsst.eu/linux-x86_64/lsst_distrib/``

Shared filesystem daily stack versions are available at /sdf/group/rubin/sw/.

Note that you can access conda from the stack install; SDF does not
provide a central conda install.
