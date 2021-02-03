# Covid mobility data repository

This repository contains data created in the [Covid-19 mobility project](https://www.covid-19-mobility.org/).

The datasets are updated once per week.

## Datasets

### Mobility change

These are daily time series of the mobility change (mobility compared to 2019) as displayed on the mobility project website. The data is aggregated on different geometries.

The mobility change is the current number of trips, divided by the number of trips in 2019 (for the same weekday and month, averaged over all weekdays of this month). Details are listed on the mobility project website.

Provided are the datasets:

- mobility_change_germany: The mobility change for all of Germany
- mobility_change_bundeslaender: The mobility change in the federal states of Germany.
- mobility_change_kreise: Mobility in the Stadt- and Landkreise (districts) of Germany (with NUTS 3 code).

In addition to the mobility change, a 7 day running average of the mobility change is provided (centered around each date, and only given if a full 7 day window is available).

### Citation

If you want to use this data in a publication, please cite the OpenScienceFramework repository as a data source (which links to this repo):
[https://osf.io/n53cz/](https://osf.io/n53cz/)

In addition, please cite the following publication which explains the data in more detail:

COVID-19 lockdown induces disease-mitigating structural changes in mobility networks
Frank Schlosser, Benjamin F. Maier, Olivia Jack, David Hinrichs, Adrian Zachariae, Dirk Brockmann
Proceedings of the National Academy of Sciences Dec 2020, 117 (52) 32883-32890; DOI: 10.1073/pnas.2012326117
[https://www.pnas.org/content/117/52/32883](https://www.pnas.org/content/117/52/32883)

### Contact

frank.schlosser@hu-berlin.de
