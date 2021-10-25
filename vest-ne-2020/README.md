# vest-ne-2020

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source:

- VEST Nebraska 2020 Data File 
   - Accessed: 10/04/21, Source: VEST on the Harvard Dataverse
   - Link: [https://dataverse.harvard.edu/file.xhtml?fileId=4931791&version=21.0](https://dataverse.harvard.edu/file.xhtml?fileId=4931791&version=21.0#)
- VEST Nebraska 2020 Documentation
   - Accessed: 10/04/21, Source: VEST on the Harvard Dataverse
   - https://dataverse.harvard.edu/file.xhtml?fileId=5206372&version=21.0 
- NE Precinct-Level Elections Results, 2020, Presidential Contest 
   - Date accessed: 10/05/21, Source: NE Secretary of State
   - https://electionresults.nebraska.gov/resultsSW.aspx?text=Race&type=PRS&map=CTY
   - Note: Precinct-level results are available by clicking the “County Level Results” button in the header of the results table. Click the green “Export Precinct Results to Excel” button on the next page \([direct link](https://electionresults.nebraska.gov/ResultsExport.aspx?rid=11232&pty=&osn=90&name=For%20President%20and%20Vice%20President%20of%20the%20United%20States&cat=CTYALL)).
- NE Precinct-Level Elections Results, 2020, Senate Contest
   - Date accessed: 10/05/21, Source: NE Secretary of State
   - https://electionresults.nebraska.gov/resultsSW.aspx?text=Race&type=SW&map=CTY
   - Note: Precinct-level results are available by clicking the “County Level Results” button in the header of the results table. Click the green “Export Precinct Results to Excel” button on the next page ([direct link](https://electionresults.nebraska.gov/ResultsExport.aspx?rid=10830&pty=&osn=102&name=For%20United%20States%20Senator%20-%206%20%20Year%20Term&cat=CTYALL)).
- Lancaster County Precinct Maps
   - Date accessed: 10/07/21
   - https://www.lancaster.ne.gov/494/Individual-Precinct-Maps
   - Individual maps were downloaded by an automated script. 
- Cass County Precinct Maps
   - Date accessed: 10/07/21
   - https://gis-cass.hub.arcgis.com/datasets/Cass::2020-cass-county-voting-precincts
   - Precinct boundaries are available on Cass County’s Open Data portal linked above. Note that as of 10/07/21, Cass’s official county website did not link to this resource; I had to reach out to local election officials for the URL. 
- Douglas County Precinct Maps
   - Date accessed: 10/06/21, Source: Douglas County
   - https://www.votedouglascounty.com/maps.aspx 
   - On the linked page, expand the "Polling Places" header under the map of Douglas County drop boxes. Click the “Polling Places” link. (Despite the .com TLD, votedouglascounty.com is the official website of the Douglas County Election Commissioner.)



## File processing:

`vest-ne-2020-validation.ipynb` is the script that is the basis of the validation report
