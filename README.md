# cdpw-ohif

Build OHIF plugin for Orthanc for the CDPW project.

This used to be part of cdpw, but is now split off separately
because it only needs to be built infrequently and needs some
special handling due to docker requirements.

This is dependent on https://github.com/OHIF/Viewers,
but because it plugs into Orthanc, we are under the
GPLv3 LICENSE.
