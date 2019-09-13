# Welcome! 

For this project, we are imagining that municipal governments are concerned about their average high school graduation rates. They want to increase them and are already working on doing so from many angles. However, they are curious to know what the data say and have hired us to look at various factors that may affect graduation rates and then make recommendations for high impact areas to focus efforts on. 


### Data

Since there are many factors that may or may not impact cities' average high school graduation rates, we wanted to start with a bird's-eye view of the problem. For this, we made API calls to Teleport.org, which gave us quality of life data spanning 17 broad factors for 65 American metropolitan areas. Factors included "environmental quality", "education", "tolerance", and fourteen others, each a score aggregated from multiple sources. See teleport.org for more information. 

From data.gov, we obtained a dataset on graduation rates for each of these metropolitan areas. We also obtained other data sets depending on our initial findings.


### Methodology

We grouped all of the cities into "high" and "low" cities for each of the 17 Teleport factors and ran hypothesis tests between these groups to see if there was a relationship between them and graduation rates. We failed to find a statistically significant result from most of the factors.

After our initial data exploration and initial hypotheses test, we looked further into some of these factors, especially those that yielded statistically significant findings, by finding other data sets within their scope. For example, once we saw there was a statistically significant relationship between Teleport's "Tolerance" scores and graduation rates, we wanted to explore facets of this relationship. From data.gov, we obtained a dataset of survey information for students across Philadelphia high schools. We used this data to find that there was a correlation between students feeling like they are treated poorly due to their sexual orientation and students not finishing their schoolwork. We also used the same data for find a correlation, though less strong, between feeling unsafe walking to/from school and students not finishing their schoolwork.


We also dug deeper into school-specific issues including school day start times and participation in extracurricular clubs and sports. These data came from Open Data Network. 


### Results and Recommendations
There were a few unsurprising results including that safety impacts graduation rates. However, because municipal governments likely already believe that and are working on strategies in that area, our most valuable insights are the less expected ones, which include the high number of lgbt students who are treated poorly and consequently fair worse in educational outcomes and later school day start times positively impacting educational outcomes. From these, we can make recommendations that include focusing on funding for extracurricular programs and GSA clubs, LGBT acceptance campaigns, and citywide recommendations for schools to start their days later.

### Project Owners

Sebastian Monzon and Logan Anderson :) 

All work from the presentation to the notebooks, was split between both of us, with Sebastian focusing on 'tolerance' and 'safety' impacts and Logan focusing on school day start times and extracurricular clubs/sports involvement. 