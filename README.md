# Latest COVID-19 Data updates (02-04-2020) : Current Trends and Forecasts


# Introduction

The underlying data analysed here is open sourced and comes from the Humanitarian Data Exchange ( https://data.humdata.org/dataset/coronavirus-covid-19-cases-data-for-china-and-the-rest-of-the-world). The latest data on COVID-19 cases in New Zealand is sourced directly from announcements from the Ministry of Health on a daily basis (https://www.health.govt.nz/our-work/diseases-and-conditions/covid-19-novel-coronavirus/covid-19-current-cases ). The latest data is usually made available by early afternoon NZ time.

New Zealand is at a relatively early stage of the COVID-19 outbreak. The purpose of this resource is to draw insights from the data as the crisis unfolds and to make inferences as to what this might mean for NZ. Initially, the goal is to track the speed at which this disease has spread in some of the most affected countries, and to model this on to the NZ context.

# Speed of Spread

One of the key concerns is the speed at which the disease is spreading. We have seen in NZ an exponential growth in confirmed cases that have led to extraordinary nation-wide measures to contain or slow down the spread. Are these high increases in daily rates of those confirmed to have the virus likely to persist, and if not, how quickly are these rates likely to reduce?

The data shows that the speed of the spread in terms of what the percent of new confirmed COVID-19 cases is from one day to the next, changes in respect to the length of time a country has been battling the outbreak. The number of days it takes for a country to double its current number of confirmed COVID-19 cases is another way of looking at this phenomenon. Therefore, much of the data analysis here will consider what stage a country is at in terms of the length of time it has been fighting the outbreak.

Below is a figure which shows how many days a selection of countries have been dealing with this disease since they recorded a 40th confirmed COVID-19 case. The chosen countries are some of the hardest hit, and offer most insights in terms of highlighting trends. These countries are China, Spain, Italy, Iran, France, Germany, United Kingdom, South Korea, US, Australia and Singapore. The graph sets 40 as the threshold, since the daily changes in percentages of new confirmed cases stabilises after this point.

![COVID19_length_of_outbreaks](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Stage+of+the+COVID-19+Outbreak++Across+Selected+Countries+02-04-2020.jpg)

Relatively speaking, NZ is at an early stage of combating the outbreak. Trends from other countries which are further down the road, can illustrate what NZ could also expect in the near future and could also serve as examples to learn from.

The following figure plots the actual percentage change of new confirmed COVID-19 cases from one day to the next for all of the countries above. The rates for each country are smoothed using a rolling seven day mean.

![COVID19_global_spread](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Daily+Percentage+Changes+in+Reported+COVID-19+Cases+in+Selected+Countries+02-04-2020.jpg)

As time progresses, the graph shows a general slowdown in daily rates, though countries have, and are achieving this with different degrees of success. The most successful, such as China and South Korea, have managed to reduce the transmission rates to near zero, by day 30. Singapore succeeded in lowering the transmission rates earlier, but has recently started experiencing an increase. Other countries are exhibiting rates that are in high teens, or in the case of USA, high thirties for the same point in time.

Using the above approach, NZ experienced its Day 1 on March 20. The smoothed daily rates of change of confirmed COVID-19 cases for NZ can be seen in the graph below in black.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Daily+Percentage+Changes+in+Reported+COVID-19+Cases+in+Selected+Countries+and+NZ+02-04-2020.jpg)

The high reported daily rates of confirmed COVID-19 cases for NZ are not out of step with what other countries have been experiencing at the same point in time. NZ went into a full national shutdown from midnight 25 March. The effects of this mandatory national isolation should become visible in the data between days 10 and 20 due to the incubation and testing time lags. It will be interesting to monitor the trends to see if NZ follows the rates observed in South Korea and Singapore.

Given the trends from data on other countries which are ahead of NZ, it is possible to apply them to NZ and to simulate what the overall numbers in new confirmed COVID-19 cases might look like over the next 4 weeks. One simplistic approach is to aggregate the daily rates of newly confirmed COVID-19 cases across the countries in the above graphs, and to apply this to NZ. The figure below show the mean rate of daily confirmed COVID-19 cases across these countries, together with that of NZ. The figure depicts both the 7-day rolling mean as well as the actual daily percentages for NZ.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Mean+Daily+Percentage+Changes+in+Reported+COVID-19+Cases+across+Selected+Countries+and+NZ+02-04-2020.jpg)

# Modeling the Spread

## Scenario 1 (Aggregate Trends Across Selected Countries)

If we were to assume that the rate of new confirmed COVID-19 cases in NZ will resemble the mean daily increases across the countries mentioned depicted in the above graphs, we could expect to see the trend in the graph below over the next four weeks.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+New+Confirmed+COVID-19+Cases+in+NZ+02-04-2020.jpg)

The graph shows a possible rapid increase in the number of new confirmed cases starting in two weeks time, with a slowdown occurring by week four. This model is based on the assumption that the trends in NZ will resemble other countries who were at same stages of the outbreak. However, the above model does not take into account the fact that NZ is now in a full lock-down and how this might diverge from trends exhibited by other countries, who did not enforce national lock-downs at such early stages.

If we sum up all the the new daily confirmed COVID-19 cases in NZ, we can see how this translates to the forecasted total number of cases over the next four week in the graph below.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+Total+Confirmed+COVID-19+Cases+in+NZ+02-04-2020.jpg)

### Hospitalisations and Intensive Care (under Scenario 1)

It is difficult to estimate exactly what the hospitalisation rates are for COVID-19 cases. The rates vary from one country to the next and are influenced by a number of factors. A crude and a possibly conservative estimate is that 10% of those confirmed with COVID-19, will seek hospitalisation. Again, rates for those requiring admission to intensive care units (ICU) is also variable, but 25% has been reported by several sourced.

Modeling these rates onto the forecasted COVID-19 cases in NZ, produces the graph below. The graph illustrates the current national inventory of ICUs which has been boosted to 563. This number includes beds and units that are currently being converted to be able to support severe COVID-19 patients.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Hospitalisations+and+ICU+Requirements+Due+to+COVID-19+02-04-2020.jpg)


## Scenario 2 (Singaporean Trends)

The trends for NZ are beginning to diverge quite strongly from the mean rates of new confirmed COVID-19 cases from selected countries that were modeled in scenario 1. Recent trends (as of late March) in the rate of new confirmed COVID-19 cases in NZ have seen a significant downturn from earlier patterns. Although the earlier trends for NZ have been quite different to Singapore, by day 11, the rates of the two countries have converged as seen in the figure below.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Percentage+Change+in+Reported+COVID-19+Cases+Comparing+NZ+and+Singapore+02-04-2020.jpg)

The rate of new cases for Singapore presents a very optimistic possible scenario for NZ. The next set of graphs seek to simulate what might be in store for NZ if Singapore's trends were to be realised here.

The graph below shows the number of new daily confirmed COVID-19 cases that are forecasted if Singapore's experience holds within the NZ context. At the same stage of the outbreak as we find ourselves now, Singapore observed a slowdown in new confirmed cases over the next two weeks with a subsequent increase from week 3.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+New+Confirmed+COVID-19+Cases+in+NZ+-+scenario+2+02-04-2020.jpg)

By summing up all the new daily confirmed COVID-19 cases in NZ, we can see the total number of predicted cases over the next four weeks in the graph below.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+Total+Confirmed+COVID-19+Cases+in+NZ+-+scenario+2+02-04-2020.jpg)

The forecasts under scenario 2 stand in stark contrast to those of scenario 1 and illustrate a much more positive outlook.

### Hospitalisations and Intensive Care (under Scenario 2)

The positive forecast models under scenario 2, also translate to hospitalisation rates and ICU needs for the next month that are well within the capacity of the NZ health system. The figure below illustrates these possible outcomes.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Hospitalisations+and+ICU+Requirements+Due+to+COVID-19+-+scenario+2+02-04-2020.jpg)



## Scenario 3



## Economic Impacts


More to follow here...

