## About the Project

This is a project to examine crime patterns in the locations of cannabis shops in Seattle. There are a few questions I'm seeking to answer:

1. Is there a relationship between crime and legal cannabis stores in Seattle? Should communities be concerned if a new pot store is opening up in their neighborhood? Note -- this will NOT be true causal analysis, but a correlation may be of interest.
2. What is the relationship between pot stores, crime, and demographics? Is there greater prosecution of minority groups for nusiance crimes near pot stores? If so, this may be a reflection of the racially biased drug war.
3. Is there a relationship between store revenue and crime? Are stores in higher socio-economic status (SES) neighborhoods making more than those in lower income neighborhoods?
4. Are cannabis store locations distributed equitably across the city? That is, are the locations available to open stores concentrated in lower-income neighborhoods?

No doubt I'll think of other questions as the project progresses.

## Data Sources

- Seattle 911 Incident Reports. These will capture a range of incidents across the city. Lat/Lon is provided, which makes analysis easier than crime reported by a per-district basis. The file is currently 1.3 Million + entries long, so let's access what we need by the [API](https://dev.socrata.com/foundry/data.seattle.gov/pu5n-trf4).
- Cannabis retail info. The locations of all the cannabis stores in Seattle and when they opened. Also, the amount of revenue the stores make. This is available through data from the Washington Liquor and Cannabis Board.
- Socioeconomic Data, from the US Census / American Community Survey. Currently leaning towards the ACS 5-year survey. The ACS has a [handbook for data users] (https://www.census.gov/content/dam/Census/library/publications/2008/acs/ACSGeneralHandbook.pdf) which includes details on the data, collection methods, error, and so on, and the appedices get into the statistical measures - margin of error, confidence intervals, and so on.
