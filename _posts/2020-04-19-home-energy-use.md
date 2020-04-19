---
title: "Home Energy Consumption and Emissions"
categories:
  - blog
tags:
  - climate
  - energy
---

Change begins at home. Having come home due to coronavirus, I figured it was
time to look at my home's energy usage and its emissions. For context, I'm
currently staying in a 1500 sq ft townhouse in the SF Bay Area with two
occupants. Based on our utility bills from the last four years, we've used an
average of 175 kWh of electricity and 14.5 therms of natural gas per month.

## How do we compare to the average?

The US Energy Information Administration (EIA) occasionally conducts a
Residential Energy Consumption Survey (RECS) household energy usage patterns.
The [most recent RECS][recs2015] is from 2015, for which they sampled 5,600
households out of the 118.2 million households in the US.

[recs2015]: https://www.eia.gov/consumption/residential/data/2015/

Based on the 2015 RECS, the average household in the US
[consumes][recs2015avgus] 893 kWh of electricity and 48 therms of natural gas
per month. Apparently, our household footprint is far lower than the national
average: one-fifth of the electricity and one-third of the natural gas!
That's good, but that's quite an easy bar to beat, given that:

1. Our house's square footage (1500 sq ft) is 25% lower than the [national
   average][recs2015sqft] of 2008 sq ft.
2. Our household size or occupancy (~0.9 due to travel) is much lower than
   the [average household size][census-household-size] of 2.5.
3. California households [use 31% less energy][eia-ca-brief] than the US
   average, among the lowest in the nation. One big reason is that California's
   mild climate reduces the need for heating and air conditioning.

On top of this, beating the US average isn't something to be proud of, as
the average American uses [more than double][eia-energy-consumption] the
energy of the average European, and nearly four times as much
energy as the average person on earth. And one big reason is that Americans love
big houses, and space heating and air conditioning use a lot of energy.

[recs2015avgus]: https://www.eia.gov/consumption/residential/data/2015/c&e/pdf/ce4.6.pdf
[recs2015sqft]: https://www.eia.gov/consumption/residential/data/2015/hc/php/hc10.9.php
[census-household-size]: https://www.census.gov/content/dam/Census/library/visualizations/time-series/demo/families-and-households/hh-6.pdf
[eia-ca-brief]: https://www.eia.gov/consumption/residential/reports/2009/state_briefs/pdf/ca.pdf
[eia-ca-analysis]: https://www.eia.gov/state/analysis.php?sid=CA#4
[eia-energy-consumption]: https://www.eia.gov/international/data/world/total-energy/total-energy-consumption?pd=44&p=000000001&u=0&f=A&v=mapbubble&a=-&i=none&vo=value&&t=G&g=none&l=249-00000000000000000000000000000000000000000000000201&l=71--71&l=170--170&s=315532800000&e=1483228800000

Nonetheless, PG&E, our regional utility company, tells me that our household
still has lower energy usage than other houses in our neighborhood.
That's certainly a good thing, but much of the different must be due to the
fact that the occupancy in our home is much lower than other homes here.

## Emissions

PG&E reports that in 2018 their CO2 emissions rate was only [93 grams of CO2 per
kWh][pge-footprint] of electricity generated. I found this astounding, as the
[national average][eia-elec-footprint] is 449 grams of CO2 per kWh! It appears
that [PG&E generates][pge-power-mix] 69% of its electricity from nuclear and
renewables, 17% from natural gas, and none from coal or oil (the dirtiest
sources). The remaining 14% is marked as "unspecified," meaning it
cannot be traced to its source. That's intriguing. Based on this figure, our
household emissions from electricity amount to 0.54kg CO2/day or 195.3kg CO2/year.

[pge-footprint]: https://www.pge.com/en_US/about-pge/environment/what-we-are-doing/fighting-climate-change/fighting-climate-change.page
[eia-elec-footprint]: https://www.eia.gov/tools/faqs/faq.php?id=74&t=11
[pge-power-mix]: https://www.pge.com/pge_global/local/assets/data/en-us/your-account/your-bill/understand-your-bill/bill-inserts/2017/november/power-content.pdf

The [EPA reports][epa-equiv] that burning one therm of natural gas releases
5.3kg of CO2. Thus our household gas usage results in 2.56kg CO2/day or 922.2kg
CO2/year, bringing our total emissions to 3.1kg CO2/day or 1,117.5kg CO2/year.

[epa-equiv]:
https://www.epa.gov/energy/greenhouse-gases-equivalencies-calculator-calculations-and-references

For comparison, the average American [emits about 17 tons][wb] of CO2 per year (not
including other greenhouse gases, such as methane) of which [6.1 tons][kalmus] come from
electricity and natural gas. Europeans emit about 8 tons in total per yar and
the global average is about 5 tons.

The most interesting result here is that natural gas makes up 82.5% of our
household emissions! The fact that PG&E generates most of its electricity from
nuclear and renewables means that our natural gas usage has an outsized
carbon footprint.

[wb]: https://databank.worldbank.org/reports.aspx?source=2&series=EN.ATM.CO2E.PC&country=
[kalmus]: https://peterkalmus.net/books/read-by-chapter-being-the-change/read-by-chapter-chapter-9-leaving-fossil-fuel/

## Reducing our footprint

If we wanted to reduce the carbon footprint of our home, it seems the most
effective solution would be to switch our heating sources (central heating,
water heating, and stove) to electric alternatives. However, most people prefer
gas heating because it's considered to be cheaper to operate. What would the
cost difference be for us, with PG&E?

For the sake of simplicity, let's just assume all the natural gas we currently
use is for central heating. We currently use an average of 14.5 therms of
natural gas per month. One therm contains 29.3 kWh of power, so that comes out
to 5098 kWh of energy per year. Compare that to 2100 kWh of electricity that we
use per year. Our [central heating furnace][58ctw] has a annual fuel-utilization
efficiency (AFUE) of 80%, basically meaning that it's 80% of the 5098 kWh of
energy contained in the natural gas is actually being converted into heat. In
contrast, electric furnaces have higher efficiency, as high as 100%.

We currently pay $0.24/kWh for electricity and $1.41/therm for natural gas. Over
the course of a year, the $245 we currently pay for natural gas would be
replaced by a $988 bill for the added electricity. In reality, the bill would
likely be more than that, due to the fact that the rate of electricity
increases to $0.30/kWh when we cross a baseline threshold that we currently do
not cross but would likely be crossed on days we use central heating. The
exact numbers will depend on a variety of factors, but the overall
point is that the cost of heating would roughly quadruple from switching to
electricity.

[58ctw]: https://www.carrier.com/residential/en/us/products/gas-furnaces/58ctw/

Of course, there are many other ways to reduce our overall carbon footprint
significantly without having to pay more. Reducing flying, eating less meat and
dairy, and driving less would all have a substantial impact on our carbon
footprint. In particular, for those of us who do fly more than a few times a
year, flying is likely to make up the majority of our individual carbon emissions.
