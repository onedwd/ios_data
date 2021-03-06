.. _ios-shell-label:

========================
IOS_Shell 
========================

IOS Shell is an in-house software designed to be a general purpose utility for data processing, analysis, plotting and file manipulation. It uses a common file format referred to as the IOS Header format, and the quality flags are mostly compatible with WOCE standards.

- Installation (Windows Only)::

	//dcbciosna01a/osdshare/IOSShell/setup/IS_manager.exe


.. _wp-site-label:

========================
WaterProperties Website
========================


- Location:

 	`https://waterproperties.ca/data`_

  .. _https://waterproperties.ca/data: https://waterproperties.ca/data/

- Requires:

  User registration

- Features:

  Wild cards:  \*  and ? can be used when searching for results. E.g. channel_name: temperature\*

- Known problems that require special attention (will be addressed in the next release)

  #. Bulk downloading is feasible, check the question mark on the Results page for instructions
  #. Be careful when using wild card to search for variables. e.g. temperature\* will return all temperatures including 'temperature:lab' which might not be what you wanted...
  #. Only return 1000 results
  #. Need manual path manipulation in order to use for :ref:`ios-shell-label`
  #. If you are using 'Channel Name' to search, make sure you set the 'Condition =' to 'present'
  #. 'Refine Search' function does NOT retain the information that you put in for the channel name
  #. anything else?


========================
Matlab
========================



