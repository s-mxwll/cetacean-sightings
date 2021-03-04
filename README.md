# Yorkshire Cetacean Recording Project (YCRP): Kettleness

## My cetacean sightings data

Including land-based surveys from Kettleness (North Yorkshire) and other ad-hoc sightings around Whitby.

### Data dictionary

| variable           | class     | description                                                     |
|--------------------|-----------|-----------------------------------------------------------------|
| `date`             | date      | Survey date                                                     |
| `location`         | character | Survey location                                                 |
| `survey_type`      | character | Land- or boat-based survey                                      |
| `start_time`       | date-time | Survey start time                                               |
| `end_time`         | date-time | Survey end time                                                 |
| `tz`               | character | GMT or BST                                                      |
| `sea_state`        | integer   | [Beaufort scale](https://en.wikipedia.org/wiki/Beaufort_scale)  |
| `swell`            | integer   | Light: <1 m; Moderate: 1-2 m; Heavy: >2 m                       |
| `wind_direction`   | character | Compass bearing                                                 |
| `visibility`       | character | Poor: <1 km; Moderate: 1-5 km; Good: 6-10 km; Excellent: 10+ km |
| `wind_speed`       | numeric   | Wind speed (kph)                                                |
| `time_last_high`   | date-time | Time of last high tide                                          |
| `time_high_i`      | date-time | Time of high tide in tidal cycle _i_                            |
| `time_low_i`       | date-time | Time of low tide in tidal cycle _i_                             |
| `height_high_tide` | numeric   | Height of high tide in tidal cycle _i_ (m)                      |
| `height_low_tide`  | numeric   | Height of low tide in tidal cycle _i_ (m)                       |
| `sunrise`          | date-time | Time of sunrise                                                 |
| `taxon`            | character | Species (common name)                                           |
| `count`            | integer   | Number of individuals                                           |

### Data dictionary (derived in script)

| variable             | class     | description                                                                    |
|----------------------|-----------|--------------------------------------------------------------------------------|
| `tide_direction`     | character | Ebb or Flood                                                                   |
| `dm`                 | numeric   | Time since last high tide (mins)                                               |
| `dt`                 | numeric   | Time between high and low tide (mins)                                          |
| `dh`                 | numeric   | Height difference between high and low tide in the tidal cycle _i_             |
| `tide_flow`          | numeric   | Rate of tide flow (Isojunno _et al_. (2012; Mar Ecol Prog Ser **448** 155–170) |
| `mins_since_sunrise` | numeric   | Time between sunrise and start of survey (mins)                                |
