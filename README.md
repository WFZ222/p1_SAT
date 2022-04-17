 Project 1: Standardized Test Analysis


### Problem Statement

Parents and students are spending a lot of time and money on studying and taking the SATs. Some even consider relocating to an area where they have a higher SAT score, hoping to get better SAT scores. However, can we rely on those data?

---

### Datasets

* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))

---

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|States|50 states of the US, plus DC|
|par|float|Participation Rate|Participation Rate of students taking SATs|
|eng|int|Evidence-Based Reading and Writing|Average score of students per state|
|math|int|Mathematics|Average Math score of students per state|
|total|int|Total Score|Total SAT score of students per state|
|avg_par|float|Average Participation Rate|Average of 3 years of Participation Rate of students taking SATs, year 2017-2019|



### Conclusions

Based on the data we can conclude that those states with higher participation rates tend to have lower state averger scores, and states with lower participation rates tend to have higher state average scores. This data shows a direct relation betwen particaption rates and average SAT scores. For those with higher participation rate, it shows that actual state average score, however, for those with low participation rate, especially those with under 10% participation rate, we cannot draw a conclusion that this state itself has a higer average based only on 10% of the students. Parents and students need to reconsider, if they are planning to use these data to relocate to a location with higher SAT score. We can only draw a conclusion that less than 10% of the students took the SAT. We should be wary about why participation rate is low in those states.