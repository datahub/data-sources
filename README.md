# Sources for Wisconsin related data

## City of Milwaukee

### Health inspections
- [Food establishment inspection reporting system](http://itmdapps.milwaukee.gov/cehri/search.jsp)
  - Current food inspections can be found at [this site](http://healthspace.com/Clients/WI/Milwaukee/Web.nsf/home.xsp) (which doesn't look very official).
  - Past inspections can be found [here](http://itmdapps.milwaukee.gov/cehri/sb.jsp?conch=8892306002t5G6cr9VPdkfssg2zI5r4RBoV03s6Vv5B).

## Weather

### General
- [NOAA Climate Data Online](https://www.ncdc.noaa.gov/cdo-web/datasets)
  - [Monitoring stations](https://www.ncdc.noaa.gov/monitoring-references/)

### Great Lakes
 - [Great Lakes Environmental Research Laboratory (GLERL): Forecasts](https://www.glerl.noaa.gov//res/glcfs/)
 - [NWS Great Lakes: Wave height](http://www.crh.noaa.gov/greatlakes/?c=map&l=gl&p=a)
 - [Buoys](http://glbuoys.glos.us/)
 - [UWM - Freshwater Sciences](http://uwm.edu/glos/data/)
 - [NOAA CoastWatch data](https://coastwatch.glerl.noaa.gov/)

### Snowfall
- [Daily U.S. Snowfall and Snow Depth, 2015 - today](https://www.ncdc.noaa.gov/snow-and-ice/daily-snow/)
- [National Snowfall Analysis](https://www.nohrsc.noaa.gov/snowfall/) and its [FTP](https://www.nohrsc.noaa.gov/snowfall/data/)
- [SNODAS](http://nsidc.org/data/g02158) and FTP: ftp://sidads.colorado.edu/DATASETS/NOAA/G02158/

## Counties
 - [Wisconsin County Centers](wi-county-centers.csv)
   - The zoom levels are for Google Maps, but subtract 1.5 for use with Mapbox.

## Wind
- [GLERL: wind and air temperature from Milwaukee lakeshore (2-minute-interval)](https://www.glerl.noaa.gov/metdata/mil/)

## Politics

### State Legislature
 - A micro [script](https://github.com/datahub/wisconsin-state-legislature-info) to parse state legislature info from website
   - [State Assembly](https://github.com/datahub/wisconsin-state-legislature-info/blob/master/state-assembly.csv)
   - [State Senate](https://github.com/datahub/wisconsin-state-legislature-info/blob/master/state-senate.csv)

### Elections
- Campaign finance:
  - [Federal Election Commission (FEC)](https://www.fec.gov/)
  - campaign finance data includes expenditures, disbursements, loans for candidates, super PACs, etc. 
  - See NICAR tipsheet by Chris Schnaars, [Wagging the Dog](https://www.dropbox.com/s/ule7ub4fk6psovj/Christopher%20Schnaars%27%20tipsheet.pdf?dl=0), to see what's available and caveats
- How elections are administered:
  - [Election Administration and Voting Survey (EAVS)](https://www.eac.gov/research-and-data/datasets-codebooks-and-surveys/)
  - Contains information on voter registration, absentee voters, polling place workers (things like age and difficultly in finding workers), voting machines.
  - Most states report at the county-level. Wisconsin reports at the ward-level.
