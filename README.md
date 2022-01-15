# Excess_Mortality

Exploring excess mortality vs covid-19 reported deaths during pandemic.

## What is 'excess mortality'?
**Excess mortality** is a term used in epidemiology and public health that refers to the number of deaths from *all causes* during a crisis above and beyond what we would have expected to see under ‘normal’ conditions. [^1] In this example, we're curious how the number of deaths during the COVID-19 pandemic compares to the number of deaths we'd expect if the pandemic hadn't happened — a vital quantity that can't be known but may be estimated in a variety of ways.

Excess mortality is a better indicator of the pandemic's overall impact on deaths than the confirmed COVID-19 death count. It includes not just confirmed deaths, but also deaths from COVID-19 that were not appropriately identified and reported, as well as deaths from other causes related to the general crisis situation.

## How is excess mortality calculated?

```
Excess Deaths = Reported Deaths - Expected Deaths
```
Excess mortality is defined as the difference between the reported number of deaths in a given week or month (depending on the country) in 2020–2021 and an estimate of the number of deaths that would have occurred if the COVID-19 pandemic had not occurred.

### Keep in mind the following points about excess mortality figures:

It's possible that the number of deaths listed may not reflect all of the deaths that occurred. For two reasons, this is the case:

- To begin with, not every country has the infrastructure or capacity to register and report all deaths. Nearly all deaths are recorded in wealthy nations with high-quality mortality reporting systems. However, undercounting of death is a severe problem in many low- and middle-income nations. According to the United Nations [^2] , only two-thirds of countries register at least 90% of all deaths in "normal" times, and other countries register fewer than 50% — or even less than 10% [^3] — of deaths. The real coverage during a pandemic could be substantially lower.
- Second, even in wealthy countries with high-quality mortality reporting systems, there are delays in death reporting that render mortality data provisional and incomplete weeks, months, and even years after a death occurs. The length of the delay varies depending on the country. The most current data points for some are clearly very incomplete and thus erroneous; we do not display these visibly incomplete data points.


## Hypothesis

Excess deaths is a metric that compares the number of deaths that occurred over a certain time period to the number of deaths predicted based on the same time period in previous years. It does, however, rely on complete death registration.

**Excess deaths provide a perspective of the entire loss of life directly caused by Covid-19.**

It also illustrates deaths caused indirectly by the pandemic due to things including overburdened health systems, dread of going to the hospital, and a slump in the economy.

It will also show us which countries, for political or other reasons, underreport genuine Covid-19 numbers.

## Data Exploration

### Data source


## Comparing COVID-19 Death stats vs Extra mortality stats

<div class='tableauPlaceholder' id='viz1642274792513' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='StatisticalmortalityratesinUnitedStates&#47;Sheet3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1642274792513');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

## Creating a visualization in Tableau

## Conclusions


## Endnotes

[^1]: Checchi, F., & Roberts, L. (2005). [Interpreting and using mortality data in humanitarian emergencies.](https://odihpn.org/resources/interpreting-and-using-mortality-data-in-humanitarian-emergencies/) Humanitarian Practice Network, 52.

[^2]: https://unstats.un.org/unsd/demographic-social/crvs/#coverage

[^3]: https://www.bbc.com/news/world-africa-55674139
