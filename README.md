# Yorkshire Cetacean Recording Project (YCRP)

## My cetacean sightings data from Kettleness (North Yorkshire)

Including land-based surveys from Kettleness and other ad-hoc sightings along the Yorkshire Coast.

### Data dictionary

| variable           | class     | description                           |
|:-------------------|:----------|:--------------------------------------|
| `date`             | date      |                                       |
| `location`         | character |                                       |
| `survey_type`      | character | Land- or boat-based survey            |
| `start_time`       | date-time |                                       |
| `end_time`         | date-time |                                       |
| `tz`               | character | Time Zone (GMT/BST)                   |
| `sea_state`        | integer   |                                       |
| `swell_height`     | integer   |                                       |
| `wind_dir`         | character | Compass bearing                       |
| `vis`              | character | Four-point scale                      |
| `wind_speed`       | numeric   | Wind speed (kph)                      |
| `time_last_high`   | date-time | Time of last high tide                |
| `time_high_i`      | date-time | Time of high tide in tide cycle _i_   |
| `time_low_i`       | date-time | Time of low tide in tidal cycle _i_   |
| `height_high_tide` | numeric   | Height of high in tidal cycle _i_ (m) |
| `height_low_tide`  | numeric   | Height of low in tidal cycle _i_ (m)  |
| `sunrise`          | date-time | Time of sunrise                       |
| `taxon`            | character | Cetacean (common name)                |
| `count`            | integer   | Number of individuals                 |

# Produced in script

