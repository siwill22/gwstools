# gwstools
python functions to access data from gplates web service

The idea of these functions is to provide a simple means to access data files from the gplates web service,
to be used in python.

The functions fall into two distinct categories:
- functions that make it easier to create pygplates features in your python session by accessing the data files from
a remote server - these functions allow you to more conveniently create and share scripts that use pygplates, without
having to worry about passing on the required files, preserving file paths, etc
- functions that access reconstructed data from the gplates web service as json - such that you can do further 
calculations with this data without needing to have pygplates at all
