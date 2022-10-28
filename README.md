# champagne-bottles

This is part of a collaborative scientific projet (PSC) conducted while I was studying at École Polytechnique. The report and comments within the code are in French.

### Description

The goal is to assess the amount saved (in terms of money and carbon footprint) for a Champagne (or any sparkling wine) company transitioning from having no returnable bottles strategy, to gradually implementing a process of collecting bottles and re-using them.

The models gradually increase in complexity in terms of the hypotheses regarding the actual implementation of the returnable bottles strategy.
Keep in mind that the models are not perfect, and that the end results might be subject to change over time (due to potential future innovations which will drastically reduce the carbon footprint of producing glass bottles for instance). Also, the parameters are rough estimates, and you are free to change them if you want to use the code.

> How did you come up with the estimate of 500g CO2e per bottle ? Did you factor in the transportation and all other emissions related to the champagne bottle life cycle ?

In short, this estimate comes from the Base Impacts database, managed by ADEME (French Environment and Energy Management Agency). We only kept the manufacturing part of the life cycle (from the raw natural materials to the glass bottle being produced), since it is by far the most important part in terms of carbon emissions (and overall impact on natural resources) of the whole life cycle of the bottle, and that returning bottles does not significantly change the impact on other scopes. Note that this estimate takes into account the energy mix to heat the materials to produce glass, hence it is also subject to change.

### Key take-away

In the more realistic model, for a company selling 2,000,000 bottles of Champagne a year, it is expected that the company will emit around **20,000t CO2e** less compared to not implementing the strategy over 30 years, which corresponds to saving 40,000,000 bottles.
