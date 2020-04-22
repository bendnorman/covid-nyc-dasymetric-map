# Dasymetric Map of COVID Cases in New York City

Follow some conversation around this on [Twitter](https://twitter.com/wgeary/status/1252636419111165953?s=20).

STOP mapping COVID case counts by zip code! 🙅‍♀️🚫

Zip codes come in varying shapes and sizes, introducing bias known as the Modifiable Areal Unit Problem (MAUP).

The maps below display population, tests and recorded COVID cases in NYC.

The maps on the left are a simple choropleth maps displaying raw counts by zip code.

The maps in the middle are dasymetric maps which redistribute raw counts from zip codes to residential buildings within the zip code proportionate to building volume, and then re-aggregates by equal area hexagon.

The maps on the right are smoothed version of the dasymetric hexagon grid maps using kernel density estimation.

![alt text](assets/comparison_table_zip_hex_smoothed.png "COVID Cases and Tests")

COVID case counts should be accompanied by data on population and the total number of tests administered. It is flawed to draw conclusions about the spread of COVID without accounting for the number of tests administered. And it is flawed to aggregate this data by zip code.

There is some **seriously** flawed research going on right now which attempts to draw conclusions about how COVID spreads by simply overlying data on top of raw case counts by zip code. Please be aware of this!
