# Szczecin housing data analysis

## Data source

Data used in this analysis come from weekly downloads from the website otodom.pl. They contain housing price information for Szczecin/Poland. Data gathering started in Oct 2016 and has coantinued on weekly basis. The data have been automatically scraped each Saturday night (PL time). All the data are in the *data* subfolder.

## Data format

The data are written using JSON line (.jl) format. Each line contains the following information:

* data_lat: Lattitude of the property in degrees. As defined on the website, may not correspond to actual localization.
* data_lon: Longitude of the property in degrees. As defined on the website, may not correspond to actual localization.
* description: Title of the advetrisement.
* details: Detailed text description of the property.
* floor: Which floor the flat is located.
* images: - 
* location: Location description taken from the website.
* name: - 
* poi_lat: - 
* poi_lon: - 
* pow: Area in m^2.
* price: Price in PLN.
* rooms: Number of rooms.
* sellType: Type of sale.
* town: Town name. Usually it's Szczecin.
* url: Full url to the original ad.
