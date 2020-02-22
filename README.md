# Meteo Project
 Project for B ME 450


Neil Skilton

Dr. Abadi

B ME 450

2/21/2020

# Intro:

The focus of this project is on understanding how weather patterns propagate throughout the ocean. Using data ingested from the Ocean Observation Initiative (OOI), wind and precipitation rates were recorded and analyzed for any form of cross-correlation. These measurements all have come off the Bulk Meteorology Instrument Package, which “measures a variety of parameters that characterize weather conditions above the sea surface” [1].

# Data Collected:
	
The first step after ingesting the data was to understand where there was rain and win. To do the data was normalized relative to their respective average values and broken up into sections. If the normalized value was less than a quarter of the value of the normalized average, then the programs assumed that the value was too low to be present. Using these criteria, the data was split into four options: rain and wind (yellow), just rain (green), just wind (blue), and neither (red). Below are the results found at the Oregon Shelf Surface Mooring (OSSM) and the Oregon Offshore Surface Mooring (OOSM) respectively.
 
![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/PvW_OSSM.png)

![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/PvW_OOSM.png)

The next portion of this collection process focused on checking for any form of cross correlation between the two regions for both precipitation and wind speed. The graph that shows correlation versus lag is on a 2000-point scale, which represents the span of the total amount of index values that the test took place within since 1001 data points were ingested per region.
 
![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/CC_Wind.png)

![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/CC_Precipitation.png)

One important thing to note is that the lag for the wind speed was zero days with a 63.14% correlation and the lag for the precipitations was 124 days with a 35.19% correlation.

The final piece of the data collection involves averaging the wind speed and precipitation over each month to get a visual representation of how the two regions are related, if at all. Below are the averages for the OSSM and OOSM respectively.

![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/OSSM_avg.png)

![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/OOSM_avg.png)

# Analysis:

Looking at the average values over each month, there appears to be some similarities to the cross-correlation results found. The large precipitation rate drop for the OSSM was in June, but for the OOSM was in October. This show quite a long lag time between similar precipitation conditions. On the other hand, wind speed appears to be quite similar, with both having low points in April and May. It is possible that these two locations are in a region with the same current and winds and because of the nature of how quickly wind can move, they experience similar conditions almost immediately, but since clouds take longer to move, similar weather patterns occur at very different times.

![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/Currents.png)[2]

One piece of this that I was concerned about was the possibility of having the data be skewed by ocean spray rather than actual precipitation, but from the sources that I could find, there were realistic precipitation values found in the data collected. Below are precipitation values recorded in millimeters over a year. For reference, the latitude that this project focused on was between 50-40 north in the Pacific Ocean. 
 
 ![](https://github.com/neil-uwb/Meteo-Project/blob/master/Meteo%20Pics/Precipitation.png)[3]
# Conclusion:

Given the data above and the analysis provided, I have concluded that wind patterns will be experienced almost immediately at two locations within the same current/wind vein but will have similar precipitation rates after long periods of time. This is something I did not expect as I assumed that the weather patterns as a whole would move from region to region, but the analysis shows that weather is more dynamic than I previously anticipated. 
 
# References:
[1]	Abadi, S (2020). Meteorology Package Project. [online] University of Washington Bothell [Accessed 21 Feb. 2020]

[2]	En.wikipedia.org. (2020). North Pacific Gyre. [online] Available at: https://en.wikipedia.org/wiki/North_Pacific_Gyre [Accessed 21 Feb. 2020].

[3]	Babkin, V. (2020). ATMOSPHERIC PRECIPITATION OF THE EARTH. [online] Eolss.net. Available at: https://www.eolss.net/Sample-Chapters/C07/E2-02-03-01.pdf [Accessed 21 Feb. 2020].




