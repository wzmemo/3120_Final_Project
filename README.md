# Bikeshare Pollution Analysis
#### Does more Citibike use Coorelate with Decreased Carbon Monoxide Levels?

Remake of final project: analysis of increased bikeshare use and level of Carbon Monoxide in NYC (2013 - Present)

## Rationale
I think the some of the ideas that many of us take for granted need to be put to the test. It's logical, and [commonly accepted](https://www.scholaradvisor.com/essay-examples-for-college/bicycle-helps-reduce-air-pollution/) that if a city moves away from automobile usage to bike usage, the air quality should improve. Yet as this [article](https://usa.streetsblog.org/2017/06/21/the-science-is-clear-more-highways-equals-more-traffic-why-are-dots-still-ignoring-it/) suggests, common taken-for-true assumptions might not always be as true as we think.

## Hypothesis
I hypothesized that increased bikeshare usage would be coorelated with **better air quality.** There are many lurking variables in this analysis such as seasonality, EPA regulation changes, increased purchase and use of inefficient, large, vehicles as gasoline prices are relatively low.

## Methods 
I used Python packages Pandas, Numpy, Matplotlib for loading and wrangling, R for linear regression and outlier considerations, and Tableau for the final visual. 

## Where did I get the data?
Using data from [NYC EDC](http://www.nyaqinow.net/) and [Citibike's own internal datasets](https://www.citibikenyc.com/system-data)
![Air Quality](https://github.com/wzmemo/3120_Final_Project/blob/master/images/aqpic.png)

## Visualization of Citibike and Air quality over time

<img src="https://github.com/wzmemo/Bikeshare-Pollution-Analysis/blob/master/images/aq_tableau.png" width="600">
<img src="https://github.com/wzmemo/Bikeshare-Pollution-Analysis/blob/master/images/citibike_tableau.png" width="600">

## Regression of two variables
![Regression](https://github.com/wzmemo/Bikeshare-Pollution-Analysis/blob/master/images/regression%20image.png)

# Conclusion
There is a **negative** linear coorelation between increased bikeshare use and CO levels.

In other words, more bike rides seems to be coorelated with decreased pollution.

## License
Copyright 2018 William Zeng

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
  
