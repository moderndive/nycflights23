# Flights data

On-time data for all flights that departed from the given airports.

## Format

A data frame with columns:

- year, month, day:

  Date of departure.

- dep_time, arr_time:

  Actual departure and arrival times, UTC.

- sched_dep_time, sched_arr_time:

  Scheduled departure and arrival times, UTC.

- dep_delay, arr_delay:

  Departure and arrival delays, in minutes. Negative times represent
  early departures/arrivals.

- hour, minute:

  Time of scheduled departure broken into hour and minutes.

- carrier:

  Two letter carrier abbreviation. See `get_airlines` to get the full
  name.

- tailnum:

  Plane tail number.

- flight:

  Flight number.

- origin, dest:

  Origin and destination airport. See `get_airports` for additional
  metadata.

- air_time:

  Amount of time spent in the air, in minutes.

- distance:

  Distance between airports, in miles.

- time_hour:

  Scheduled date and hour of the flight as a `POSIXct` date. Along with
  `origin`, can be used to join flights data to weather data.

## Source

RITA, Bureau of transportation statistics,
<https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236>
