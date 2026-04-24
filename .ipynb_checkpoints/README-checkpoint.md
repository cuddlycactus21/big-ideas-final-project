# big-ideas-final-project

This repository is an attempt to find the best neighborhood in Pittsburgh using a combination of metrics centered around the livability of each neighborhood, including how accessible it is to transit, the amount of green space (parks) nearby, and how few condemned and abandoned properties there are.

Team name: The Three Stooges (Canvas group #10)

Team members:
-Luke Douglas (ljd92@pitt.edu) - Github as cuddlycactus21 or ljd92
-Michael Tichy (mit174@pitt.edu) - Github as amp575 or mit174
-Mason Pavelik (mwp42@pitt.edu) - Github as masonp482 or mwp42
*Note: It does not list all of us as contributors because when adding from JupyterHub it does it under our Pitt usernames. This can be seen in the Github repo files. The only contributor listed is Luke, and his only listed contribution being when he created the repo, but we are all added to the project as collaborators, and our work on the project can be seen in the files (e.g., added by mit174, or by mwp42, etc).

Datasets used:
**Luke** used the **City of Pittsburgh Parks** dataset. It lists all of the roughly 200 parks in Pittsburgh, including traffic islands and medians as well as actual, fully-fledged parks. It was last updated in 2021 - a newer dataset is in the process of being created. For each park, it has data fields such as the name, type, location, neighborhood, ward, who's responsible for maintaining it, and more. It is a GeoJSON file, meaning it can either be displayed as a standard table or in map format.
Link: https://data.wprdc.org/dataset/parks

**Michael** used the **Pittsburgh Regional Transit Stops** dataset. It lists all 6,426 transit stops serviced by PRT in Pittsburgh - bus, light rail, and even the four incline stops on Mount Washington. It is effectively current/up-to-date, as it contains data from the "current service period", and is drawn from a regularly updated dataset from PRT on their Open Data Hub. Some fields include the neighborhood, location, routes serving the stop, mode (e.g., bus, rail, or incline), amount of ridership/trips at various times, and more. Like the Parks dataset, it is a GeoJSON file with the data available as a table or a map.
Link: https://data.wprdc.org/dataset/prt-of-allegheny-county-transit-stops

**Mason** used the **Condemned and Dead-End Properties** dataset. It contains data about all of the roughly 3,400 condemned properties in Pittsburgh, as sourced from the city's Department of Permits, Licenses, and Inspections. The "dead-end" designation refers to condemned properties for which the owner cannot be found or located after multiple attempts. Each property has data fields for the location (address), owner, inspection results, neighborhood, and more. Like the other two datasets, it comes in both table and map format (CSV or GeoJSON, respectively).
Linkhttps://data.wprdc.org/dataset/condemned-properties