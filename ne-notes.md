## Notes about Nebraska

- Unicameral legislature; state representative nomenclature 

From All About Redistricting:

> Nebraska law appears to permit redrawing state legislative or congressional district lines mid-decade, at any point before the next Census. [2002 Op. Neb. Att’y Gen. [No. 02003](https://redistricting.lls.edu/wp-content/uploads/NE-20020128-AG-Opinion-2002-003.pdf); [Exon v. Tiemann](http://scholar.google.com/scholar_case?case=8291803551116297778), 279 F.Supp. 603 (D. Neb. 1967)]

## Raw Data

#### Precincts (or are they VTDs?)

- 2010 Precinct Data (`raw-data/precincts/`)
- Retrieved from [Nebraskamap.gov](https://www.nebraskamap.gov/datasets/nebraska::voting-districts/about) on 10/4/21. Description: "Voting Districts for the State of Nebraska based on the 2010 Census values".
- For all files in the list below except "File Geodatabase", selected "generate new download with latest data". Attempts to generate a new download for "File Geodatabase" threw an error ("File generation failed"), so the version of that file that I've included is dated August 16 2020, 20:31.
  - CSV: Voting_Districts.csv
  - KML: Voting_Districts.kml
  - GeoJSON: Voting_Districts.geojson
  - File Geodatabase: All contents of `Voting_Districts-fgdb` folder.
  - Shapefiles: All contents of the `Voting_Districts` folder.

#### Election Results

- 2020 Precinct-level Election Results retrieved from the OpenElections `openelections-data-ne` Git repository. 
  - File: [**20201103__ne__general__precinct.csv**](https://raw.githubusercontent.com/openelections/openelections-data-ne/master/2020/20201103__ne__general__precinct.csv ) 
- 2018
  - File: [20181106__ne__general__precinct.csv](https://raw.githubusercontent.com/openelections/openelections-data-ne/master/2018/20181106__ne__general__precinct.csv)
- 2016 ERs take on a different form. 
  - File: 



## VEST

VEST data is stored in the `vest` folder.

- 2020: `vest/ne_2020/`
  - Voting and Election Science Team, 2020, "2020 Precinct-Level Election Results", https://doi.org/10.7910/DVN/K7760H, Harvard Dataverse, V21
- 2018: `vest/ne_2018/`
  - Voting and Election Science Team, 2019, "2018 Precinct-Level Election Results", https://doi.org/10.7910/DVN/UBKYRU, Harvard Dataverse, V47

