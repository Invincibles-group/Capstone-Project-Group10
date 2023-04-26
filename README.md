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

**Praposed Solution**

  1) Calculate and Compare public transportation emissions using ML Models Time Series, FB Prophet & Random Forest.

  2) Forecasting the emission for 5 years using historical data from 2010 to 2022.
 
  3) Determine the primary pollutant that has the highest emission level across the given countries.

  4) Type of fuel with the highest emissions

**How to Download the Data into the Excel from R package**

**Data Description & Pre Processing**

In this study we use General Transit Feed Specification (GTFS) data from a R package called gtfs2emis, to estimate public transport emissions. The gtfs2emis package uses emission factor models for Europe (EMEP/EEA), the United States (EPA/CARB and MOVES/EPA), and Brazil (CETESB) to calculate more than sixteen types of pollutants released by each vehicle. Fleet characteristics required by each emission factor models includes information for buses, including age, fuel, EURO standard, technology, load, slope, and whether they are Micro, Standard, or Articulated. However, the required characteristics may vary depending on the emission factor model.

**Exploratory Data Analysis**

 **Pollutants emitted at the highest level**
![image](https://user-images.githubusercontent.com/55294714/234574062-9fa051aa-a22d-45ec-888a-8b2b6746a90e.png)

**Transit buses average emissions from 2010 to 2022**
![image](https://user-images.githubusercontent.com/55294714/234574705-9c81cd82-eeb7-41bf-90fd-4f039868c2db.png)

**Average emissions (g/miles) by model year**
![image](https://user-images.githubusercontent.com/55294714/234574729-630f9126-7f62-4c42-86e5-21735cb6ce70.png)

**Comparison of emission levels at different speed intervals**
![image](https://user-images.githubusercontent.com/55294714/234574768-77e442d0-74f1-435c-95dc-04a5a7ee6361.png)

**Comparison of emission for different fuel types**
![image](https://user-images.githubusercontent.com/55294714/234574797-4a1824f8-6699-4545-8f1e-a2764f27bc51.png)




