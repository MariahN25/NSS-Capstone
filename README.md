# Add Health Longitudinal Study Analysis

"The National Longitudinal Study of Adolescent to Adult Health (Add Health) is a longitudinal study of a nationally representative sample of over 20,000 adolescents who were in grades 7-12 during the 1994-95 school year, and have been followed for five waves to date, most recently in 2016-18. Over the years, Add Health has collected rich demographic, social, familial, socioeconomic, behavioral, psychosocial, cognitive, and health survey data from participants and their parents" [(Add Health)](https://addhealth.cpc.unc.edu/).

## Motivation
When I was a freshman in college, advisors liked to ask whether we felt like we belonged at the school and among our peers.
They wanted to see how well we were meshing in our environment.
I thought it was interesting that they asked us these questions in order to ascertain how to help us be more successful in school.
This experience prompted me to explore the factors that could influence a child’s ability to succeed academically.
There are numerous external factors that could play a role, so I decided to focus on just two – relationships with family and peers.
It is known that parent involvement and a child’s social circle can influence how they perform in school.
I wanted to explore whether simply feeling connected to peers and family could influence a child’s performance as well.

## Technologies
- `Python`
  * `Jupyter Notebook`: Used to perform my EDA and in-depth analysis.
- `Tableau`: Used to create an interactive dashboard that can be accessed [here](https://public.tableau.com/views/CapstonePresentation_16511648876340/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).
- `Excel`: Used to access my data sources, which were available in a tsv and csv format.

## Data Sources

- [Add Health](https://www.icpsr.umich.edu/web/ICPSR/studies/21600?archive=ICPSR&q=21600)
- [Educational Attainment Census Data](https://www.census.gov/data/tables/2008/demo/educational-attainment/cps-detailed-tables.html)

## Data Questions
- Does having a connection to peers and family correlate to academic and career success?



- Does family structure correlate to academic and career success?

## Known Issues and Challenges
The longitudinal study consisted of five waves where participants were reached out to over the course of two decades.
Not all participants responded in every wave, so I had to decide what to do about the inconsistency throughout they
dataset in regards to number of respondents. Using Python, I merged the participant IDs for every wave in order to create a dataframe
of participants who had responded to each wave of the study. When doing analyses across numerous waves, I only took into consideration
individuals who had participated in the entire study.

## Link to the Dashboard
You can check out my dashboard [here](https://public.tableau.com/views/CapstonePresentation_16511648876340/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)!
