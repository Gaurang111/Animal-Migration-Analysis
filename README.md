# Animal Migration and Climate Change

## Main Project Objective

The primary goal of this project is to investigate the influence of climate change on the migration patterns of the Arctic fox on Bylot Island in Greenland.

## Factors of Focus

1. **CO2 Emissions**
2. **Sea Ice Area**
3. **Temperature**
4. **Food Insecurity**

## Background Information

### Animal Proxy

- **Species:** Arctic Fox
- **Habitat:** Arctic Tundra, primarily Bylot Island
- **Behavior:** Seasonal migrant, with a tendency to stay local around Bylot Island
- **Predator:** Lemmings, hares, birds, fish, etc.

<img src="images/Picture1.png" width=400  ><img src="images/image23.png" width=400 height=350>

### Climate Data

#### Factor 1: CO2 Emissions

- Analyzed CO2 and greenhouse gas data.
- Greenland and Canada both experienced a decrease in CO2 levels.
- Suggests a potential correlation with animal migration.

<img src="images/image8.png" width=400><img src="images/image9.png" width=400>

#### Sea Ice Area Data

- **Indicator Source:** Environment and Climate Change Canada's Climate Research Division.
- **Trend:** Statistically significant decrease in summer sea ice area (1968-2020) for all sub-regions.
- **Impact:** Affects Indigenous communities, travel, and animal habitats.

<img src="images/image12.png" width=800>
<img src="images/image13.gif" width=400>

#### Temperature

- **Observation:** The Arctic is warming four times faster than the global average.
- **Data:** Shows a gradual temperature increase with fluctuations.
- **Impact:** Even small temperature increases are detrimental to the environment.

<img src="images/image14.png" width=400>

#### Food Insecurity

- **Impact:** Lemming(Main Food Source of Arctic Foxes) populations affected by climate change, impacting the Arctic fox's food source.
- **Data:** Bar graph of lemming nests recorded in Bylot Island (2007-2019).
- Lemmings are well-known to have cyclic populations. Every four years, there is a large increase in population.
  The bar graph fluctuations is consistent with the lemming cyclic population. 

<img src="images/image15.png" width=400><img src="images/image16.png" width=400 height=290>


## Migration Visualization

- **Data Source:** Argos tracking from movebank.org (2007-2021). [Link to Movebank Study](https://www.movebank.org/cms/webapp?gwt_fragment=page=studies,path=study942774711)
- **Details:** 170 Arctic foxes, 64489 records.
- **Cleaning:** Extracted relevant columns, converted timestamp, added seasonal classification.

### Data Distribution
- **Month-Wise:** 
  - **Largest:** August has the greatest number of records at about 7000.
  - **Smallest:** May has the lowest number of records at about 3300.
- **Year-Wise:** 
  - **Largest:** 2011 and 2012 have the greatest number of records at about 10000.
  - **Smallest:** 2007, 2018, and 2021 have the lowest number of records at <1000.

<img src="images/image19.png" width=400><img src="images/image20.png" width=400 height=285>

-What is the Longest Number of Years a Specific Fox has been Recorded?
  - Three foxes were recorded for six years. (The longest number of years)
  - 73 foxes were recorded for two years. (The average number of years)
  - 44 foxes were recorded for only one year. (The smallest number of years)

<img src="images/image21.png" width=800>

- What is the Number of Foxes Tracked Every Year?
  - The maximum number of foxes being tracked in the year 2011, and the least number in 2021.
  - If we look closely, this graph is correlated to the year-wise data distribution of records graph.
  - As number of foxes increases, number of data points increases.

<img src="images/image22.png" width=400>
  





## Reflections

- **Challenges:**
  - Limited data for the Canadian Arctic Archipelago.
  - Reliance on surrogate data from lower Canada or Greenland.
  - Short lifespan of Arctic foxes impacts longitudinal data.

- **Importance:**
  - Climate change impacts food sources, sea ice, and habitat isolation.
  - Increased susceptibility to illness and reduced genetic diversity.
  - Implications for the broader ecosystem.

## Future Work

- Conduct additional studies with a larger sample size.
- Explore migration patterns of different animal types.
- Consider animals with longer lifespans for clearer migration patterns.

## References

[Link to Bowdoin College](https://courses.bowdoin.edu/gov-2577-spring-2021-managing-the-effects-of-climate-change/arctic-issues-and-policy-ideas/kiera-dent/)

[Link to Canada Daily Climate Data](https://climate-change.canada.ca/climate-data/#/daily-climate-data)

[Link to Kaggle Dataset - Eighty Years of Canadian Climate Data](https://www.kaggle.com/datasets/aturner374/eighty-years-of-canadian-climate-data)
