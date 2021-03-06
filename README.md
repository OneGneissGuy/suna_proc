# suna_proc : a python package to process Satlantic SUNA V2 data files 

suna_proc is a python package that reads SUNA data (log files) into a pandas datetime indexed dataframe.
Burst data is grouped by time, processed for outlier detection using the median absolute deviation, 
converted to a pandas dataframe and saved to a csv file.

See http://satlantic.com/suna for more information on the Satlantic SUNA v2.


Compatability:
--------------
* Windows 7
* python 2.7

Requirements:
--------------

### Required packages: ###

* matplotlib
* numpy
* pandas
* statsmodels

Example: Process a directory of daily log files into a pandas dataframe and save to a csv file
-------------------------------------------------------------------------------
https://github.com/OneGneissGuy/suna_proc/blob/master/examples/iws_suna_proc.py

Installation:
------------

Install suna_proc from the command line by following these steps:

    $ git clone https://github.com/OneGneissGuy/suna_proc.git
    $ cd suna_process
    $ python setup.py install
	
OR

Copy the [source code](https://github.com/OneGneissGuy/suna_proc/tree/master/suna_process) directly

Disclaimer:
----------

This software is preliminary or provisional and is subject to revision. It is being provided to meet the need for timely
best science. The software has not received final approval by the U.S. Geological Survey (USGS). No warranty, expressed
or implied, is made by the USGS or the U.S. Government as to the functionality of the software and related material nor
shall the fact of release constitute any such warranty. The software is provided on the condition that neither the USGS
nor the U.S. Government shall be held liable for any damages resulting from the authorized or unauthorized use of the
software.

The USGS provides no warranty, expressed or implied, as to the correctness of the furnished software or the suitability
for any purpose. The software has been tested, but as with any complex software, there could be undetected errors. Users
who find errors are requested to report them to the USGS.

References to non-USGS products, trade names, and (or) services are provided for information purposes only and do not
constitute endorsement or warranty, express or implied, by the USGS, U.S. Department of Interior, or U.S. Government, as
to their suitability, content, usefulness, functioning, completeness, or accuracy.

Although this program has been used by the USGS, no warranty, expressed or implied, is made by the USGS or the United
States Government as to the accuracy and functioning of the program and related program material nor shall the fact of
distribution constitute any such warranty, and no responsibility is assumed by the USGS in connection therewith.

This software is provided "AS IS."


Author(s):
------
John Franco Saraceno <saraceno@usgs.gov>

More information:
-----------------
* Python: https://www.python.org/
* pytest: http://pytest.org/latest/
* Sphinx: http://sphinx-doc.org/
* public domain: https://en.wikipedia.org/wiki/Public_domain
* CC0 1.0: http://creativecommons.org/publicdomain/zero/1.0/
* U.S. Geological Survey: https://www.usgs.gov/
* USGS: https://www.usgs.gov/
* U.S. Geological Survey (USGS): https://www.usgs.gov/
* United States Department of Interior: https://www.doi.gov/
* official USGS copyright policy: http://www.usgs.gov/visual-id/credit_usgs.html#copyright/
* U.S. Geological Survey (USGS) Software User Rights Notice: http://water.usgs.gov/software/help/notice/
* Python's download page: https://www.python.org/downloads/
* git: https://git-scm.com/
* Distutils: https://docs.python.org/3/library/distutils.html
* Installing Python Modules: https://docs.python.org/3.5/install/
* How Installation Works: https://docs.python.org/3.5/install/#how-installation-works
