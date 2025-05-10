In this folder you will find the CSV files, health inspection data via the City of Chicago, the scraped data, and the merged csv of the two. The health inspection csv had to be split into multiple seperate files to be uploaded to Github, that can be found in "Chunk (#)". The original file is too large.


Here is the data dictionary:

| FIELD | Type |Description |
| ------ | ------ | ------
| Address_x | Object | Full street address of the restaurant. 
| Price | Object | General pricing tier, represented by dollar signs ($–$$$$). |
| Cuisine | Object | Type of cuisine served at the restaurant. |
| Neighborhood | Object | Chicago neighborhood where the restaurant is located. |
| Inspection ID | Float | Unique ID assigned to a specific health inspection. |
| AKA Name | Object | Alternate or registered name of the restaurant. |
| License # | Float | Business license number registered with the city. |
| Facility Type | Object | Type of food service establishment (e.g., Restaurant, Bakery). |
| Risk | Object | Risk category from the health department based on potential food safety hazards. |
| City | Object | City in which the business is located (usually "Chicago"). |
| State | Object | State abbreviation (e.g., IL). |
| Zip | Float | Zip code of the restaurant’s address. |
| Inspection Date | Object | Date when the health inspection was conducted. |
| Inspection Type | Object | Type of inspection (e.g., Canvass, Re-Inspection). |
| Results | Object | Outcome of the inspection (e.g., Pass, Fail). |
| Violations | Object | Description of violations cited during inspection. |
| Latitude | Float | Latitude coordinate of the restaurant location. |
| Longitude | Float | Longitude coordinate of the restaurant location. |
| Location | Object | Combined latitude and longitude in tuple format. |

