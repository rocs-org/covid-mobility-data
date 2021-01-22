# Covid mobility data repository

This repository contains data created in the [Covid-19 mobility project](https://www.covid-19-mobility.org/).

## Datasets

### Mobility change

These are daily time series of the mobility change (mobility compared to 2019) as displayed on the mobility project website. The data is aggregated on different geometries.

The mobility change is the current number of trips, divided by the number of trips in 2019 (for the same weekday and month, averaged over all weekdays of this month). Details are listed on the mobility project website.

Provided are the datasets:

- mobility_change_germany: The mobility change for all of Germany
- mobility_change_bundeslaender: The mobility change in the federal states of Germany.

In addition to the mobility change, a 7 day running average of the mobility change is provided (centered around each date, and only given if a full 7 day window is available).

### Contact

frank.schlosser@hu-berlin.de
