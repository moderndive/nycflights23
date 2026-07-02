# Airport metadata

Useful metadata about airports.

## Format

A data frame with columns:

- faa:

  FAA airport code.

- name:

  Usual name of the airport.

- lat, lon:

  Location of airport.

- alt:

  Altitude, in feet.

- tz:

  Timezone offset from GMT/UTC.

- dst:

  Daylight savings time zone. A = Standard US DST: starts on the second
  Sunday of March, ends on the first Sunday of November. U = unknown. N
  = no dst.

- tzone:

  IANA time zone, as determined by GeoNames webservice.

## Source

<https://openflights.org/>
