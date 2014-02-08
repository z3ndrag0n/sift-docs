libewf
===================================
Library for the Expert Witness File Format

* Author: Joachim Metz
* Website: https://code.google.com/p/libewf/

Full documentation located at https://code.google.com/p/libewf/

libewf-tools
-------------
Tools for working with the Expert Witness File format.

Include the following command line tools.

* ewfacquire; which writes storage media data from devices and files to EWF files.
* ewfacquirestream; which writes data from stdin to EWF files.
* ewfdebug; experimental tool does nothing at the moment.
* ewfexport; which exports storage media data in EWF files to (split) RAW format or a specific version of EWF files.
* ewfinfo; which shows the metadata in EWF files.
* ewfmount; which FUSE mounts EWF files.
* ewfrecover; special variant of ewfexport to create a new set of EWF files from a corrupt set.
* ewfverify; which verifies the storage media data in EWF files. 

libewf-python
-------------
Python bindings for libewf
