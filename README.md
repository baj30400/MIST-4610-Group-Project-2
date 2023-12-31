# MIST-4610-Group-Project-2
## Team Name
29704 Group 7
## Team Members: [Personal Repositories for Project in Forks]
1) Alex Kang: @ALEXKANG1
2) Andy Kim: @Andykim2003
3) Braden Johnson: Owner of Repository
4) Jake Page: @jtp38938
5) Justin Hozman: @justinhozman
## Dataset Description
The dataset we chose to use was obtained from data.gov and the source was the Department of Health and Human Services. This data is derived from information obtained from resident death certificates from all fifty states. This data is ordered by each state every year from 1999 - 2017. The columns in this dataset include, Year, Name of Cause of Death, State, Number of Deaths, and the Age-Adjusted Death Rate. Each row in this data represents the number of deaths for each cause of death within each state. For example a row would be the number of deaths Alzheimer's Disease caused in Georgia in 2015.

Link to Dataset https://catalog.data.gov/dataset/nchs-leading-causes-of-death-united-states

## Two Questions
1) Which states have abnormally high death rates and based off those findings is there a common cause of death that drives it? With this, what is the cause of death in regions where there are lower death rates?
2) Compared to the death rate of the United States, which states deviate from the US trend and is there a common factor leading to the outlier? Is there a certain state that has different trends compared to all other states?

## Why are these questions important?
1) We found this to be an important question because it could be useful in finding if there are specific drivers in the death rate that can be controlled in each state. This would allow for it to be easier for healthcare professionals and everyday people to work towards preventing these causes by knowing what to look for based on the state they reside in. With this information we hope to be able to assist in lowering the overall death rates in America by aiming medical resources towards common causes of death in their state and away from causes that may not be so prevalent.
2) Understanding which states deviate fron national health rate trends allows for targeted intervention. Identifying these states makes the prevention process capable and efficient. Along with prevention, mitigation is another important factor we found to be significant. By recognizing which states deviate from the mean, we are able to better allocate resources and even potentially stimulate policy change. States that tend to deviate from the mean can implement a more proactive emergency preparedeness provision to prevent and mitigate concerning and abnormal death rates.
## Manipulations Applied to Data
In question one we had to manipulate the number of deaths to the percentage of total deaths. Without this manipulation the bar chart doesn’t adjust for the population. The manipulation allows us to compare how each cause of death affects the total percentage of deaths. For example California has a larger population than Wyoming so the number of deaths in California far exceed Wyoming and it's difficult to compare on a barchart. However when we manipulate the data each cause of death is represented by a percentage rather than a quantity allowing us to compare both states on a bar chart of the same length. In question two we had to conduct the same calculation of deaths based on the percentage instead of the total number of deaths. We then compared every state side by side through a bar graph and discovered six outliers. We then filtered the bar graph so that only the outliers are displayed with the overall trend of the United States so that the difference is visualized. 

Erroneous Chart:

![ErroneousChart](https://github.com/baj30400/MIST-4610-Group-Project-2/assets/149818793/ad76f399-7c1c-4681-bbcc-c71c77e9a8f0)


Fixed Chart:

![FixedChart](https://github.com/baj30400/MIST-4610-Group-Project-2/assets/149818793/15cd2c03-d544-48c4-94d9-9b2d2e240d41)


## Analysis and Results
1) We first wanted to see which states had abnormal age-adjusted death rates. To achieve this we created a heat map of US states based on the sum of their age-adjusted death rates between 1999-2016. This heat map showed that the states with very high death rates were Alabama, Arkansas, Georgia, Indiana, Kentucky, Louisiana, Missouri, North Carolina, Ohio, Oklahoma, South Carolina, Tennessee, and West Virginia. And the states with low death rates were California, New York, Arizona, Minnesota, Colorado, Connecticut, Utah, New Hampshire, Rhode Island, and Vermont. Next, to investigate if any cause of death was driving the abnormality of these death rates we compared these states with the overall United States by looking at each cause of death as a percentage of total deaths. The states with the highest death rates were very consistent and each cause was proportional when compared with the United States. We can infer that no cause of death was driving these states’ death rates and the high death rate can be attributed to either a weak health system, socioeconomic factors, or unhealthy lifestyles in the population. Meanwhile, states with the lowest death rates showed slightly greater variability in causes state by state and when compared with the United States. From this we can assume that these states have been more successful in addressing specific causes of death, leading to a more diverse distribution of causes and an overall lower age-adjusted death rate.

Dashboard Used:

![MIST4610GroupProject2Dashboard](https://github.com/baj30400/MIST-4610-Group-Project-2/assets/149818793/bf460fb9-c6f5-4025-8f15-cff890db457b)


2) We first compared all of the states by looking at each cause of death as a percentage of the states’ total deaths. The states with unusual distributions were Arizona, Colorado, New Mexico, Montana, Wyoming, and Alaska. These states all had higher proportions of deaths by unintentional injuries and suicide. A common factor between these states is that they are all western states. An explanation for the higher rates of unintentional injuries could be that due to the geographic terrain of the region, risky outdoor activities could be more common. Additionally, the higher proportion of suicide deaths could indicate that the region has certain factors that negatively impact mental health or that the region does not devote enough resources to promoting mental wellness. This data suggests that these states should begin investigating strategies to combat these causes of death.

Dashboard Used:

![MIST4610GroupProject2pt2](https://github.com/baj30400/MIST-4610-Group-Project-2/assets/149818793/607f43a3-5206-4de6-b95b-65d26e7c9b73)

## Tableau Packaged Workbook

Linked at the top of the repository.
