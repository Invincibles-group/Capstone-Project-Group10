**Estimating public transport emissions from General Transit Feed Specification**

**About The Project**


The General Transit Feed Specification (GTFS) is used to estimate the emissions produced by transit
services. Using this information, transit agencies can identify opportunities to reduce emissions and
improve sustainability. We are using the gtfs2emis R package to estimate the emission levels of public transport vehicles based
on General Transit Feed Specification (GTFS) data.

**Problem Statement**

  1) The transportation industry plays a major role in causing air pollution

  2) Transit buses being a significant contributor.

  3) Pollutants can cause a range of health problems and causing the global warming



**How to Download the Data into the Excel from R package**

**Data Description & Pre Processing**

In this study we use General Transit Feed Specification (GTFS) data from a R package called gtfs2emis, to estimate public transport emissions. The gtfs2emis package uses emission factor models for Europe (EMEP/EEA), the United States (EPA/CARB and MOVES/EPA), and Brazil (CETESB) to calculate more than sixteen types of pollutants released by each vehicle. Fleet characteristics required by each emission factor models includes information for buses, including age, fuel, EURO standard, technology, load, slope, and whether they are Micro, Standard, or Articulated. However, the required characteristics may vary depending on the emission factor model.
