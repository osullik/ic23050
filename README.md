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

- [X] Produce a report that addresses the answers to the two questions above. 
- [X] Prodice an interactive map to support the analysis and answers of the two questions above. 
- [X] Produce a tool that WTSC can use in future to convert reverse Geocode their data and become self-sufficient. 
- [X] Produce a presentation to communicate our findings. 

## Timeline

- [X] **25 1130 Feb 23:** Problem Brief
- [X] **25 Feb 23:** Geocoding Complete
- [X] **26 Feb 23:** Data Cleaning Complete

- [X] **02 1200 Mar 23:** 250 Word abstract due to Judges
- [X] **03 1600 Mar 23:** Full Rehearsal of Presentation 
- [X] **04 1000 Mar 23:** Judging Day Begins
 
## TO DO: 

- [X] Reverse Geocode of Coordinates
	- [X] Google Maps API @Nicole -> Proceed with this
	- [X] QGis Layer @Kent -> Have as backup

- [X] Data Cleaning
	- [X] Remove incomplete Records 
	- [X] Get Full addresses for each Lat/Long @ Nicole

- [X] Data Dictionary Encoding @Kent
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
	- [X] Manual Review & Edits @ Kent 
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

- [X] Tableau Analysis
	- [X] Generate Heatmaps of Crash Locations *Hypothesis: There are "black spots" where many crashes occur* @Kent
		- Complete. Some clustering apparent for driver home ZIP, NSTR for crash location overall.  
	- [X] Generate Graphic Showing which Crashes are In / Out of ZIP Codes *Hypothesis: Most People Crash within their own ZIP Codes* @Kent
		- Complete. 20% Crash in own ZIP, no real change Year on Year. 	
	- [X] What Types of Crashes Are most common for In ZIP / Out of ZIP Crashes @Kent
			- **Answer**
		- *Out Of Home Zip Crashes: (% of all crashes)* (1) 9.075% Pedestrian in Road, (2) 8.664% From Opposite Direction Over Left Lane Line (3) 6.050% Off The Edge of The Road on the Right Side
		- *In Zip Crashes (% of all Crashes)* (1) 2.856% From Opposite Direction Over Left Lane Line, (2) 2.202% Off The Edge of The Road on the Right Side, (3) 2.130% Pedestrian in Road
		- As Proportion of total, they are both consistent types of accident. As proportion of each type of crash, they are also consistently the three biggest. 
		- [X] What Types of Behavioural Factors are most common for In ZIP / Ourt of ZIP Crashes
			- Not enough Data	
		- [X] What are the demographics of the Highest Crash Rate ZIPs @Nicole
			- No Defining Features by ZIP
			- Commuting Population Weakly Correlates with high Crash Rate ZIP
		- [X] What are the demographics of the lowest Crash Rate ZIPs @Nicole
			- No Defining Features by ZIP
			- Commuting Population Weakly Correlated with High Crash Rate ZIP
		
	- [X] Generate Graphic Showing Crash Concentration by Time of Day || *Hypothesis: People Crash on their way home after a long commute*
		- People Crash more at Rush Hour	

	- [X] Generate Graphic Showing Crash relation to driver distraction || *Hypothesis: People Take More Zoom Calls while driving since COVID*
		-  Not enough data 
	- [X] Generate Graphic Showing the change over time (I.e. Add a Time-bar slider) || *Hypothesis: Traffic Fatalities have increased since COVID*
		- No significant changes 

- [X] Get Data From US Census @Harsh
	- [X] Commuting Data By ZIP @Harsh
	- [X] Employment Data By ZIP @Harsh
	- [X] Schooling Data by ZIP @Harsh

- [X] Embed in a web page / interactive workbook @harsh
	- Tableau Dashboard

- [X] Write Abstract **(DUE 02 1200 Mar 23)**


## Links to Other Datasets:
- Zipcode and OSM tag from Lat/Long using [Geopy Geocoder Python library Nominatim](https://nominatim.org/)
- Data from [data.census.gov](data.census.gov) augmenting zipcode using [uszipcode Python library](https://www.pythonpool.com/uszipcode-python/)
- Possible library to augment OSM tags with road network info and construction status: [pyrosm Python Library](https://docs.osmcode.org/pyosmium/latest/)
	- Distributions of proximity to speed cameras, stop lights, stop signs, etc.
	- Roads under construction or not


