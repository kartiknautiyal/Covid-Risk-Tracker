# Covid-Risk-Tracker
Predicting the chance of Covid infection by city in the state of Massachusetts
- by Ryan, Josh, Kartik, Muralidhar

## Goal of the Project:
The goal of the project was to classify COVID-19 pandemic risk categories by considering socio-economic information from communities. There have already been studies showing a link between Socioeconomic Status (SES) and COVID-19 risk that, while useful, do not provide policies based upon individual city-level economic criteria, and are regression-based with SES markers that are predetermined and not specific to pandemics. We choose to focus specifically on the available city data in Massachusetts to understand socio-economic risk factors to hopefully help in future pandemic preparedness. We defined risk in two ways:

1) Bucketed infection percentage over the first 6 months of the pandemic (the most important time to respond to pandemics according to epidemiologists). 

2) Bucketed infection rate in the last two weeks of the first 6 months of the pandemics, showing the risk of continued spread from
that community. 

We collected and aggregated data from a variety of sources including the US Government, Massachusetts Municipal Databank, Weekly Covid reports from Massachusetts,
and from SES. We choose our models based on interpretability as the primary audience for this information would be city officials who could make more informed decisions on how to allocate resources when another pandemic occurs.
