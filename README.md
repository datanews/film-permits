# Film and Television Permits

`film-permits.csv` is a list of film and television permits received from the Mayor's Office of Media and Entertainment in response to a series of FOIL requests in 2015.  The permits stretch from October 2011 through September 2015.

### Fields

* `ProjectTitle`: The title of the film/television project.
* `EventName`: A shorthand name for the specific shoot/event being permitted, e.g. `SunsetPark-010815`.
* `EventType`: One of the following: `Scouting Permit`, `Rigging Permit`, `Shooting Permit`, `Film Shoot / Production`, `DCAS Prep/Shoot/Wrap Permit`, `Grid Request`, or `Red Carpet Premiere`.  According to the MOME, `Shooting Permit` and `Film Shoot / Production` are interchangeable.
* `EventStartDate` and `EventEndDate`: The start and end date and time of the permit.
* `Location`: One or more locations covered by the permit.
* `Boro`: What borough the listed locations are in.
* `ProjectId`: An internal identifier.
* `CategoryName`: `Film` or `Television`.
* `SubCategoryName`: Includes values such as `Pilot`, `Student Film`, `Variety`, `Reality`, etc. This probably isn't a reliable classification for TV shows: it's chosen by the permit applicant on the online form and is not vetted by the Mayor's Office. It also includes overlapping subcategories. For example, a show could be both a `Morning Show` and a `Talk Show` but would have to choose one or the other.
* `CompanyName`: The supplied production company name, which can be useful in connecting a working title to an actual film/show.

### Notes

* The project title is sometimes a variation on the actual title (e.g. `Mozart in the Jungle S1` or `The Wolf of Wall Street ReShoots`) or a working title (e.g. `Untitled Female Buddy Cop Movie" instead of `The Heat`, `St James Place` instead of `Bridge of Spies`).
* In some cases, the locations listed actually span multiple boroughs, and the `Boro` field only represents the primary borough, or the borough of the first listed location.  In some cases, the `Boro` field is blank.
* A given shooting permit can have any number of locations listed for a single day.  According to the guidelines, the locations are supposed to be listed in the order they're used on that day.  Most locations are either an address or a range of blocks in the format of `STREET 1 between STREET 2 and STREET 3`.
* Permits are generally required when asserting the exclusive use of city property, like a sidewalk, a street, or a park. A shooting permit on a street doesn't necessarily mean there is exterior shooting on the street.  It may just mean, for example, that something is being shot indoors and the crew needs special parking privileges for trucks. See ["When a Permit is Required"](http://www1.nyc.gov/site/mome/permits/when-permit-required.page).
* Shooting on Department of Citywide Administrative Services (DCAS) property, like in a city courthouse, involves an [additional permitting process](http://www.nyc.gov/html/dcas/html/business/film.shtml).
* Shooting on MTA property or on state/federal property is subject to a different permitting process.
* A shooting permit is typically, but not always, for a single day or a single overnight period.

### Other Resources

* [General MOME Permit Info](http://www1.nyc.gov/site/mome/permits/permits.page)
* [The Made in NY Location Library](http://www1.nyc.gov/site/mome/resources/location-library.page)
* [DCAS Managed Public Buildings](http://www.nyc.gov/html/dcas/html/about/buildings.shtml)
* [Metrocosm's NYC Film Permits Map](http://metrocosm.com/web/film-permits-map-nyc.html)
* [2015 BCG Report on Media and Entertainment in NYC](http://www1.nyc.gov/assets/mome/pdf/bcg-report-10.15.pdf)
