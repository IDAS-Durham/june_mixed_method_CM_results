# JUNE Mixed Method CM Results
We report contact matrices derived from [JUNE-COX](github.com/UNGlobalPulse/UNGP-settlement-modelling) and [JUNE-UK](github.com/IDAS-Durham/JUNE) the details of this can be found at [A Mixed-Method Approach to Determining Contact
Matrices in the Cox’s Bazar Refugee Settlement]().

The results are reported in the following way;
There are four contact matrix types, CM, CMV, PNCM and UNCM. 
	* CM: Total contacts per day at each venue
	* CMV: Venue normalised assuming everyone contacts everyone else at a venue
	* PNCM: Population normalised contact matrices for probabilistic contacts informed by data
	* UNCM: Venue population normalised contact matrices for probabilistic contacts informed by data
	
There are three age binnings;
	* All: Ages 0-99.
	* syoa: Age bin for all ages. [0, 1, 2, ... , 98, 99]
	* AC: Adult and child binning. [0-17, 18-99]
	
Lastly any file prefixed with "Err_" is the corresponding error estimate on that contact matrix.
