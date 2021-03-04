# Yorkshire Cetacean Recording Project (YCRP)

## My cetacean sightings data from Kettleness (North Yorkshire)

Including land-based surveys from Kettleness and other ad-hoc sightings along the Yorkshire Coast.

### Data dictionary

| variable           | class     | description                                                                           |
|--------------------|-----------|---------------------------------------------------------------------------------------|
| `date`             | date      | Survey date                                                                           |
| `location`         | character | Survey location                                                                       |
| `survey_type`      | character | Land- or boat-based survey                                                            |
| `start_time`       | date-time | Survey start time                                                                     |
| `end_time`         | date-time | Survey end time                                                                       |
| `tz`               | character | GMT or BST                                                                            |
| `sea_state`        | integer   | [Douglas sea scale (0-9)](https://en.wikipedia.org/wiki/Douglas_sea_scale)            |
| `swell_height`     | integer   | Three-point scale (Light: <1 m; Moderate: 1-2 m; Heavy: >2 m)                         |
| `wind_dir`         | character | Compass bearing                                                                       |
| `visibility`       | character | Four-point scale: Poor (<1 km); Moderate (1-5 km); Good (6-10 km); Excellent (10+ km) |
| `wind_speed`       | numeric   | Wind speed (kph)                                                                      |
| `time_last_high`   | date-time | Time of last high tide                                                                |
| `time_high_i`      | date-time | Time of high tide in tidal cycle _i_                                                  |
| `time_low_i`       | date-time | Time of low tide in tidal cycle _i_                                                   |
| `height_high_tide` | numeric   | Height of high in tidal cycle _i_ (m)                                                 |
| `height_low_tide`  | numeric   | Height of low in tidal cycle _i_ (m)                                                  |
| `sunrise`          | date-time | Time of sunrise                                                                       |
| `taxon`            | character | Cetacean (common name)                                                                |
| `count`            | integer   | Number of individuals                                                                 |

# Produced in script

