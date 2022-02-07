## PyBer_Analysis

# Overview

The purpose of this analysis is to gain a clearer understanding of PyBer's usage and customer base by combining different, disparate data sources into one data frame. This was accomplished by combining city-type data and ride data.

# Results

Firstly, by combining city data and rider data, we are able to get a more complete overview of PyBer. Note that this data is from January to April 2019.

![Overview](/analysis/pyber_summary.png)

This table shows an overview of PyBer usage in city, suburban, and rural areas. As of this study, PyBer's user base is heavily focused in urban areas, with urban cities showing a nearly 10 times higher ridership rate.

Fares though are significantly higher in rural areas than urban. And given the number of drivers in these areas, the fare per driver is also significantly higher in rural versus urban areas.

![Fare_summary_chart](/analysis/PyBer_fare_summary.png)



# Summary

Below are three recommendations to consider moving forward:

- Rural fares are significantly higher than urban fares. If we wish to expand in rural areas as cities become saturated, we should look at the pricing structure of rural fares to drive increased usage.

- Similarly, more data is needed to determine the cause of the higher rural fares. Is it that those fewer trips are longer? Or is it simply that the fares being charged per mile are higher? Is there a time of day ("surge") component?

- Revenue in urban areas spikes over weekends, whereas the sum of fares in suburban areas remains relatively stable week to week. It may be possible to use time-of-day and day-of-week data to reallocate drivers out of suburban areas and into urban cores as needed to handle demand.

