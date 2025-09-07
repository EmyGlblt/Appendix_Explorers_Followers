# Appendix_Explorers_Followers
The following file contains code and data to provide a simplified version of the enalysis done in the article Explorers vs. followers: A behavioural approach to spatial bias correction in species distribution modelling. Link to be added.


##	Metadata
# Code explanation

# We provide with the article a simplified version of the code analysis.

This zip DOES NOT contains:

	- Obsimulator: to get the observer simulator software and its manual, available at https://github.com/psomervuo/obsimulator


This zip file contains:

	- Data&code folder: which contains example scripts and data to illustrate how to do the analysis and obtain the figure
	
		-> Within there are three folders:
			- Code: The file contains only one script to display the different step of visualization and analysis 
					(Network and observed point/ spatial clustering / correction method testing with parameter smoothing and visualization/intensity maps)
					We do not provide the code for to build the road network as well as the file 'rfunctions.r' and "Share Functions_original.R" 
					because they are available in Renner et al., 2019.
			- DataExample: it contains input and output example used and obtained from obsimulator for the parameters: 5% observed targets, 10 explorer and 10 followers.
					The files output from obsimulator are of the form: .counts, .eventnames or .events (See obsimulator manual)
					xinE10F10_TG5000 file is the file with initial condition that can also be created using the Script_examples.r script.
			- CSdb: provide data and script for the citizen science data example provided in the appendix. Data used in these examples rely on the ebird and bionet database, see details on the website and in the article for citations and use.
					Maps and roads were obtained from open source data and R packages. 
							- For Australian roads network, the data was access from here http://www.diva-gis.org/gdata in 2019 (no longer maintained) but https://digital.atlas.gov.au/ provide similar data.
								by Geoscience Australia which is © Commonwealth of Australia and is provided under a Creative Commons Attribution 4.0 International Licence and is subject to the disclaimer of warranties in section 5 of that licence.
							- Bionet data: NSW BioNet Atlas. Atlas of Living Australia, 2025. Viewed 28 July 2025. DOI:10.15468/14jd9g.
							- for UK road network: acces in July 2025 at https://www.data.gov.uk/dataset. Contains public sector information licensed under the Open Government Licence v3.: https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/
							- ebird data: eBird Basic Dataset. Version: EBD_relJun-2025. Cornell Lab of Ornithology, Ithaca, New York. Jun 2025, data retrieved from World Development Indicators, http://data.worldbank.org/indicator/SP.DYN.LE00.FE.IN.



# Licence:
CC BY
This license enables reusers to distribute, remix, adapt, and build upon the material in any medium or format, so long as attribution is given to the creator. 
The license allows for commercial use or stated otherwise for single elements accessed externally (See above). CC BY includes the following elements: BY: credit must be given to the creator. 
