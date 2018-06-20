============
Structures
============

.. _cruise-data-label:

Cruise Profile Data
---------------------

- Location::

	//dcbciosna01a/ios_osd$/osd_data_archive/Cruise_data

- Folder Structure::

	~/$year/$cruise_number 
	i.e. ~/2018/2018-05

- Cruise Folder Content::

	~/Bottle
	~/CTD
	~/DOC
	~/LOGS

  - ~/Bottle

    **.che**: Data collected during stops to close Niskin bottles. Combines CTD data (averaged over a window during which the Niskin bottle was fired) with the analysis results for samples from that Niskin (example: salinity, extracted chlorophyll, nutrients, NH4, DIC, Alkalinity, DMS). There is 1 record for any bottle that was sampled.

    **.bot**: Similar to .che files but data gathered without a rosette so that if CTD data are present they are not as good a match in space or time.

    **.tob**: Processed data from a thermosalinograph

    **.loop**: Mostly from Line P. Combination of data from true loop samples gathered in the lab and samples from 5m rosette bottles. For the rosette data, some CTD data are added as well

  - ~/CTD

    **.ctd**: Processed profile data from CTDs, usually from downcast, bin-averaged and recalibrated if appropriate 

  - ~/DOC
  - ~/LOGS


.. _mooring-data-label:

Mooring Data
---------------------

- Location::

	//dcbciosna01a/ios_osd$/osd_data_archive/Mooring_data

- Folder Structure::

	~/$project_name/ 
	i.e. ~/WCTSS-C

- Mooring Data Folder Content::

	~/CTD
	~/CurrentMeter
	~/*notes.txt

  - ~/CTD

    .ctd files contain timeseries of water properties such as Salinity and Temperature recorded on the mooring

  - ~/CurrentMeter

    .cur files contain timeseries of current velocities measured by current meters, such as single point current meters and ADCP

  - ~/*notes.txt

    This file contains important data processing notes, e.g., how each sensor was calibrated, how QA/QC were performed, etc.


