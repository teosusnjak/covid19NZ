# Latest COVID-19 Data updates (12-04-2020) : Current Trends and Forecasts


# Introduction

The underlying data analysed here is open sourced and comes from the Humanitarian Data Exchange ( https://data.humdata.org/dataset/coronavirus-covid-19-cases-data-for-china-and-the-rest-of-the-world). The latest data on COVID-19 cases in New Zealand is sourced directly from announcements from the Ministry of Health on a daily basis (https://www.health.govt.nz/our-work/diseases-and-conditions/covid-19-novel-coronavirus/covid-19-current-cases ). The latest data is usually made available by early afternoon NZ time.

New Zealand is at a relatively early stage of the COVID-19 outbreak. The purpose of this resource is to draw insights from the data as the crisis unfolds and to make inferences as to what this might mean for NZ. Initially, the goal is to track the speed at which this disease has spread in some of the most affected countries, and to model this on to the NZ context.

# Speed of Spread

One of the key concerns is the speed at which the disease is spreading. We have seen in NZ an exponential growth in confirmed cases that have led to extraordinary nation-wide measures to contain or slow down the spread. Are these high increases in daily rates of those confirmed to have the virus likely to persist, and if not, how quickly are these rates likely to reduce?

The data shows that the speed of the spread in terms of what the percent of new confirmed COVID-19 cases is from one day to the next, changes in respect to the length of time a country has been battling the outbreak. The number of days it takes for a country to double its current number of confirmed COVID-19 cases is another way of looking at this phenomenon. Therefore, much of the data analysis here will consider what stage a country is at in terms of the length of time it has been fighting the outbreak.

Below is a figure which shows how many days a selection of countries have been dealing with this disease since they recorded a 40th confirmed COVID-19 case. The chosen countries are some of the hardest hit, and offer most insights in terms of highlighting trends. These countries are China, Spain, Italy, Iran, France, Germany, United Kingdom, South Korea, US, Australia and Singapore. The graph sets 40 as the threshold, since the daily changes in percentages of new confirmed cases stabilises after this point.

![COVID19_length_of_outbreaks](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Stage+of+the+COVID-19+Outbreak++Across+Selected+Countries+12-04-2020.jpg)

Relatively speaking, NZ is at an early stage of combating the outbreak. Trends from other countries which are further down the road, can illustrate what NZ could also expect in the near future and could also serve as examples to learn from.

The following figure plots the actual percentage change of new confirmed COVID-19 cases from one day to the next for all of the countries above. The rates for each country are smoothed using a rolling seven day mean.

![COVID19_global_spread](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Daily+Percentage+Changes+in+Reported+COVID-19+Cases+in+Selected+Countries+12-04-2020.jpg)

As time progresses, the graph shows a general slowdown in daily rates, though countries have, and are achieving this with different degrees of success. The most successful, such as China and South Korea, have managed to reduce the transmission rates to near zero, by day 30. Singapore succeeded in lowering the transmission rates earlier, but has recently started experiencing an increase. Other countries are exhibiting rates that are in high teens, or in the case of USA, high thirties for the same point in time.

Using the above approach, NZ experienced its Day 1 on March 20. The smoothed daily rates of change of confirmed COVID-19 cases for NZ can be seen in the graph below in black.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Daily+Percentage+Changes+in+Reported+COVID-19+Cases+in+Selected+Countries+and+NZ+12-04-2020.jpg)

The high reported daily rates of confirmed COVID-19 cases for NZ are not out of step with what other countries have been experiencing at the same point in time. NZ went into a full national shutdown from midnight 25 March. The effects of this mandatory national isolation should become visible in the data between days 10 and 20 due to the incubation and testing time lags. It will be interesting to monitor the trends to see if NZ follows the rates observed in South Korea and Singapore.

Given the trends from data on other countries which are ahead of NZ, it is possible to apply them to NZ and to simulate what the overall numbers in new confirmed COVID-19 cases might look like over the next 4 weeks. One simplistic approach is to aggregate the daily rates of newly confirmed COVID-19 cases across the countries in the above graphs, and to apply this to NZ. The figure below show the mean rate of daily confirmed COVID-19 cases across these countries, together with that of NZ. The figure depicts both the 7-day rolling mean as well as the actual daily percentages for NZ.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Mean+Daily+Percentage+Changes+in+Reported+COVID-19+Cases+across+Selected+Countries+and+NZ+12-04-2020.jpg)

# Modeling the Spread

## Scenario 1 (Aggregate Trends Across Selected Countries)

If we were to assume that the rate of new confirmed COVID-19 cases in NZ will resemble the mean daily increases across the countries mentioned depicted in the above graphs, we could expect to see the trend in the graph below over the next four weeks.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+New+Confirmed+COVID-19+Cases+in+NZ+12-04-2020.jpg)

The graph shows a possible rapid increase in the number of new confirmed cases starting in two weeks time, with a slowdown occurring by week four. This model is based on the assumption that the trends in NZ will resemble other countries who were at same stages of the outbreak. However, the above model does not take into account the fact that NZ is now in a full lock-down and how this might diverge from trends exhibited by other countries, who did not enforce national lock-downs at such early stages.

If we sum up all the the new daily confirmed COVID-19 cases in NZ, we can see how this translates to the forecasted total number of cases over the next four week in the graph below.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+Total+Confirmed+COVID-19+Cases+in+NZ+12-04-2020.jpg)

### Hospitalisations and Intensive Care (under Scenario 1)

It is difficult to estimate exactly what the hospitalisation rates are for COVID-19 cases. The rates vary from one country to the next and are influenced by a number of factors. A crude and a possibly conservative estimate is that 10% of those confirmed with COVID-19, will seek hospitalisation. Again, rates for those requiring admission to intensive care units (ICU) is also variable, but 25% has been reported by several sourced.

Modeling these rates onto the forecasted COVID-19 cases in NZ, produces the graph below. The graph illustrates the current national inventory of ICUs which has been boosted to 563. This number includes beds and units that are currently being converted to be able to support severe COVID-19 patients.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Hospitalisations+and+ICU+Requirements+Due+to+COVID-19+12-04-2020.jpg)


## Scenario 2 (Singaporean Trends)

The trends for NZ are beginning to diverge quite strongly from the mean rates of new confirmed COVID-19 cases from selected countries that were modeled in scenario 1. Recent trends (as of late March) in the rate of new confirmed COVID-19 cases in NZ have seen a significant downturn from earlier patterns. Although the earlier trends for NZ have been quite different to Singapore, by day 11, the rates of the two countries have converged as seen in the figure below.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Percentage+Change+in+Reported+COVID-19+Cases+Comparing+NZ+and+Singapore+12-04-2020.jpg)

The rate of new cases for Singapore presents a very optimistic possible scenario for NZ. The next set of graphs seek to simulate what might be in store for NZ if Singapore's trends were to be realised here.

The graph below shows the number of new daily confirmed COVID-19 cases that are forecasted if Singapore's experience holds within the NZ context. At the same stage of the outbreak as we find ourselves now, Singapore observed a slowdown in new confirmed cases over the next two weeks with a subsequent increase from week 3.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+New+Confirmed+COVID-19+Cases+in+NZ+-+scenario+2+12-04-2020.jpg)

By summing up all the new daily confirmed COVID-19 cases in NZ, we can see the total number of predicted cases over the next four weeks in the graph below.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+Total+Confirmed+COVID-19+Cases+in+NZ+-+scenario+2+12-04-2020.jpg)

The forecasts under scenario 2 stand in stark contrast to those of scenario 1 and illustrate a much more positive outlook.

### Hospitalisations and Intensive Care (under Scenario 2)

The positive forecast models under scenario 2, also translate to hospitalisation rates and ICU needs for the next month that are well within the capacity of the NZ health system. The figure below illustrates these possible outcomes.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Hospitalisations+and+ICU+Requirements+Due+to+COVID-19+-+scenario+2+12-04-2020.jpg)



## Scenario 3

Applying patterns from other countries to NZ relies on my assumptions holding, which is unlikely. As of writing, NZ appears to be on its own trajectory on new daily infection rates, rates of hospitalisation as well as ICU needs. What is more, NZ has up to this point experienced relatively low death rates attributed to COVID-19.

This final scenario considers only NZ trends, and applies them to the next four weeks. The next sets of models will daily update the 3 day rolling mean and project this four weeks ahead. The assumptions are that the conditions over any previous week will be the same in the subsequent four weeks. These assumptions will not hold for all important factors that influence infection, hospitalisation, ICU and death rates; however, these models will most likely match more underlying assumptions and have less bias than the models from the previous two simulated scenarios which involve different countries.

The graph below shows the forecasted new daily confirmed COVID-19 cases. The models still predict a very high number of daily cases that accelerate by week four; however, as more data comes in over the next couple of weeks which shows the effects of the national shutdown, these overall numbers will attenuate and correct over time.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+New+Confirmed+COVID-19+Cases+in+NZ+-+scenario+3+12-04-2020.jpg)

The number in the previous graph translate to total expected COVID-19 cases across NZ. As in the previous graph, this figure will also adjust over the coming days to the new infection rate data which captures the effects of social isolation currently in force in NZ.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+Total+Confirmed+COVID-19+Cases+in+NZ+-+scenario+3+12-04-2020.jpg)

The most optimistic forecasts are captures in the following two graphs. Other countries have reported hospitalisation rates that are ~10% of confirmed cases, ICU rates that are ~25% of those who are hospitalised. While NZ is still at relatively early stages of the outbreak, these rates have not held up to the local context. The hospitalisation rate for NZ has been ~2% and this has translated also to very low overall number of patients requiring ICU care. The figure below highlights the trends up to today, as well as forecasts over the next month. If the hospitalisation rates continue to hold, then the health system as well as the NZ UCU capacity is well placed to manage the potential demand in the near future.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Hospitalisations+and+ICU+Requirements+Due+to+COVID-19+-+scenario+3+12-04-2020.jpg)

## Estimating Fatality Rates

Ascertaining the exact fatality rates caused by COVID-19 is difficult. There is a great deal of conflicting information from various countries and therefore, it is probably unreliable to apply fatality rates from other countries to NZ. Italy is currently fatality rates of ~9.9%, meanwhile, in stark contrast, Germany is reporting ~0.5%. These are considerable differences and other countries are reporting numbers that are somewhere in between: Spain ~7.1%, Switzerland ~1.3% and US ~1.3%.


As of writing, NZ has had approximately 800 cases and one death due to COVID-19. This thankfully represents a very low fatality rate of ~0.13%, but unfortunately a rate which is likely to increase with time. The graph below represents a scenario of what would happen to the death rate over the next four weeks if the average death rate over the previous seven days holds.


![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+and+Predicted+Deaths+Due+to+COVID19+in+NZ+-+scenario+3+12-04-2020.jpg)


## Economic Impacts

The economic impacts of a prolonged national shutdown are likely to be catastrophic. The latest economic data from GDPLive.net which monitors the NZ economy in real-time, has picked up dramatic upward swings in spending leading up to the national shutdown, followed by an unprecedented slump as the economy ground to a halt. The data below depicts the consumer spending data which is represented as a percentage change in consumer spending for each day compared to the same period in the previous year.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/COVID-19+and+Consumer+Spending+in+NZ+05-04-2020.jpg)

GDPLive.net models have now started to picked up this downturn. The average between the best-case and worst-case scenarios shows there we can expect around a 21% quarter-on-quarter contraction for Q2. The figure below highlights this.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Current+Quarter+End+Percent+GDP+Change.png)

Auckland represents over 30% of NZ's economic output. The forecasts are showing that after an estimated year-on-year 5.5% growth from March 2019 to March 2020, Auckland is now set for a contraction that is currently sitting at 5%, and is increasing each day of the shutdown. This will then have a spill-over effect onto other regions in NZ.

![COVID19](https://gdp-live.s3-ap-southeast-2.amazonaws.com/covid19/Auckland-GDP.png)

See GDPLive.net for more up-to-date graphs.

More to follow ...

