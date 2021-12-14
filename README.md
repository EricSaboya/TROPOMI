# TROPOMI
## Welcome!
Thanks for stumbling across my humble GitHub repository. 

This repository contains Python scripts for processing and analysing methane column retrievals (XCH4) from the TROPOspheric Monitoring Instrument (TROPOMI) on board the Sentinel-5 Precursor satellite (http://www.tropomi.eu). 

Part of my PhD is analysing TROPOMI XCH4 for across the UK. Processing these files is not trivial, particularly if multiple variables (e.g. surface albedo, aerosol thickness etc.) are to be extracted for analysis and only a portion of the global data retrievals are of interest (e.g. data from only over the UK). 

These python scripts contain a range of useful functions for downloading, processing, and plotting TROPOMI data across the UK.

There were aspects of this data processing that were cumbersome and difficult, hopefully this helps out the next person!

If any of these scripts are useful please feel free to use them (under the MIT copyright license) but please acknowledge/cite me when relevant.

Feel free to reach out if there are questions/suggestions/comments.

Thanks! - Eric 

## Requirements
Scripts are written for use in Python 3.4 or higher.

The HARP python module (https://stcorp.github.io/harp/doc/html/index.html) is frequently used as there are excellent routines in this module for processing TROPOMI data.

