# ic23050


## Challenge Questions:

1.	Among drivers involved in fatal crashes, what proportion are involved in crashes in communities where they live?

	a. Are there differences in the types of crashes and behavior factors in those crashes among “residents” versus those deemed to be not “from” the area?

2.	Are there specific resident ZIP Codes that tend to produce higher-risk drivers that are involved in fatal crashes at a higher rate? 

	a. What are the population demographics of these high-risk driver producing ZIP Codes?


## Constraints:

1. Should be usable and interpretable by 'non-python' people
2. Should be usable and interpretable by 'non-GIS' people


## Goals:

- [ ] Produce a report that addresses the answers to the two questions above. 
- [ ] Prodice an interactive map to support the analysis and answers of the two questions above. 
- [ ] Produce a tool that WTSC can use in future to convert reverse Geocode their data and become self-sufficient. 
- [ ] Produce a presentation to communicate our findings. 

## Timeline

- [X] **25 1130 Feb 23:** Problem Brief
- [X] **25 Feb 23:** Geocoding Complete
- [ ] **26 Feb 23:** Data Cleaning Complete

- [ ] **02 1200 Mar 23:** 250 Word abstract due to Judges
- [ ] **03 1600 Mar 23:** Full Rehearsal of Presentation 
- [ ] **04 1000 Mar 23:** Judging Day Begins
 
## TO DO: 

- [X] Reverse Geocode of Coordinates
	- [X] Google Maps API @Nicole -> Proceed with this
	- [X] QGis Layer @Kent -> Have as backup

- [ ] Data Cleaning
	- [ ] Remove incomplete Records 
	- [X] Get Full addresses for each Lat/Long @ Nicole

- [ ] Data Dictionary Encoding
	- [X] Turn data Dictionary into actual atomic dictionary. @Kent 
		- [X] CrashDataFile
		- [X] PersonDataFile
		- [X] Tables1
		- [X] Tables2
		- [X] Tables3
		- [X] Tables4
		- [X] Tables5
		- [X] Tables6
		- [X] Tables7
		- [X] Tables8
		- [X] Tables9
	- [ ] Manual Review & Edits
		- [X] CrashDataFile
		- [X] PersonDataFile
		- [ ] Tables1
		- [ ] Tables2
		- [ ] Tables3
		- [ ] Tables4
		- [ ] Tables5
		- [ ] Tables6
		- [ ] Tables7
		- [ ] Tables8
		- [ ] Tables9

- [ ] Write Abstract **(DUE 02 1200 Mar 23)**


## Links to Other Datasets:
- Zipcode and OSM tag from Lat/Long using [Geopy Geocoder Python library Nominatim](https://nominatim.org/)
- Data from [data.census.gov](data.census.gov) augmenting zipcode using [uszipcode Python library](https://www.pythonpool.com/uszipcode-python/)
- Possible library to augment OSM tags with road network info and construction status: [pyrosm Python Library](https://docs.osmcode.org/pyosmium/latest/)
	- Distributions of proximity to speed cameras, stop lights, stop signs, etc.
	- Roads under construction or not


