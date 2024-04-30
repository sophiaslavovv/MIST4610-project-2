Group 1:

Shana Sah (https://github.com/shana-sah/MIST4610-project-2)

Maya Patel (https://github.com/mayapatel47488/MIST4610-project-2)

Sophia Slavov 

Cade Mayfield (https://github.com/CaMay99/MIST4610-project-2)

Chris Vitucci 

-----------------------------------------------------------------------------------------------------------
Data Set Description:
---------------------------

We acquired our data from https://catalog.data.gov/dataset/2015-16-discipline-estimations-by-discipline-type-850c7. This specific dataset reports the details of school-related arrests for public schools in all states from 2015 to 2016. The dimensions of the data set contain 24 columns and 58 rows. The information is separated into different categories. Data is derived from each state, showing the total number of students, number of schools, Race/Ethnicity of students without and with disabilities served under IDEA1, students  with disabilities served under IDEA, students with disabilities served only under section 504, English language learners, and percent of schools reporting. The column for States is a string-type data set. The number of schools and total students are all integers. The percentage of schools reporting is calculated and shown by percent alone, Race/Ethnicity of students without and with disabilities served under IDEA1, students with disabilities served under IDEA, students with disabilities served only under section 504, and English language learners are displayed with integers and percents. This data set provides us with a large amount of information to thoroughly organize and build detailed visualizations.

-----------------------------------------------------------------------------------------------------------

Question 1: Among English Language Learners, what is the relationship between English proficiency levels and the likelihood of receiving a school-related arrest?

Why is it interesting/important: 

Understanding the relationship between English proficiency levels and the likelihood of receiving a school-related arrest can further help inform educators or the public about potential disciplinary disparities between English Language Learners and their English-proficient peers. Since ELL students often come from culturally diverse backgrounds, examining how English proficiency levels relate to disciplinary actions may alleviate challenges faced by these students if a correlation that negatively affects ELL students exists. The findings of this analysis can inform the development of practices that positively impact or benefit students.
There were 3,142 English Language Learners out of the 51,780 student arrests in 2015-2016. There is a large range in the percentage of English learners, as arrests per state vary from 0% of English learners to 50%. What is the difference in ratios between states, and what is causing this wide variety? Texas has the highest number of arrests for English learners with 946, which makes up 12.3% of their school-related arrests.


![project 2 chart 3 new](https://github.com/mayapatel47488/MIST4610-project-2/assets/166044940/2dab5ce6-7d98-44d9-80d4-96c3256a9889)










-----------------------------------------------------------------------------------------------------------

Question 2: Why do Georgia and Ohio, states with incredibly similar size, have such drastic differences in school-related incarceration rates  between 2015 and 2016?

Why is it interesting/important: 

According to the gov catalog, Georgia had 3,424 public school arrests, as compared to Ohio, with only 767. What is so weird about this is that Georgia and Ohio are neck and neck for population size, with Ohio even slightly surpassing Georgia in terms of citizens. Despite this, Georgia skyrockets above Ohio in arrests. The real question is why? We believe it has to do with the school funding that happens in each respective state.

Ohio state funding differs based on local districts, like the Salon school district receiving $2362 dollars per student whereas Cleveland receives $9332 per student. This means that districts in Ohio with “more economically disadvantaged students” tend to receive more state funds.  On the flip side, Georgia is one of only eight states in the U.S. that does not provide additional funding specifically to educate students living in poverty. Instead, the state of Georgia provides more funding for students who struggle academically, based on standardized test results. 

In the dataset, Ohio contained more arrest-related data from each respective school than Georgia. 

![project 2 chart 1](https://github.com/mayapatel47488/MIST4610-project-2/assets/166044940/6e984a9f-4bbc-4506-b3b9-4e3f2a8a0387)

We visualized the number of student arrests from the years 2015-2016 geographically on a map by taking the sum of total students. The generated map displays the population of student bodies in each state, and it becomes evident that Ohio and Georgia both have a similar population size of students, as seen by the colored dots on the map. The implications of our analysis seem to state that Ohio, despite being of similar population size and even submitting more of its schools' data to be reviewed, has significantly less school related arrests. We believe this could occur because of multiple factors, including funding, mental health, and exposure to dangerous experiences.


![project 2 chart 2](https://github.com/mayapatel47488/MIST4610-project-2/assets/166044940/d53b549c-8847-40a7-8b10-49d2e4341c39)

In this dataset, Ohio contained more arrest-related data from each respective school when compared to data from Georgia. The X-axis of the bar graph is linked to submissions of arrest data by schools and the Y-axis contains the actual number of arrests for every student. The implications found in this bar graph visualization can be correlated to the level of transparency and reporting practices among schools in Ohio and Georgia regarding student arrests. The higher number of arrest-related data submissions from schools in Ohio compared to Georgia suggests that Ohio schools may have more accurate reporting mechanisms or are more diligent in documenting and reporting student arrests. The discrepancy in arrest-related data submissions between Ohio and Georgia highlights the importance of transparency in addressing student arrests. Efforts to improve data collection can lead to more informed decision-making in allocation of school funding by state legislators, and ultimately enhance the safety and learning environments for students.

source:
Churchill, A. (2023, January 26). Ohio’s new school funding formula: An introduction. The Thomas B. Fordham Institute. https://fordhaminstitute.org/ohio/commentary/ohios-new-school-funding-formula-introduction












-----------------------------------------------------------------------------------------------------------
Data Manipulation:
-------------------
There were a few things we had to manipulate in the data to give us the right outcomes. In order to calculate the most accurate pieces of information, we took out percentages when gathering all the data. Another manipulation we made was that we removed columns that didn't pertain to our phenomenon. We primarily focused on English Language Learners and the correlation between English proficiency levels and the probability of being subject to a school-related arrest, and two states with a similar population size having differences in school-related incarcerations. We focused on standardizing all the data so that it would be used in the most efficient way to analyze it. All the data we chose is quantifiable and interpretable with no redundancy. Having any inaccuracies could alter our analysis and lead to false observations. Our data entries were consistent with the information from the data analysis.


-----------------------------------------------------------------------------------------------------------
Tableau Packaged Workbook
--------------------------

The packaged workbook with the displayed visualizations is included in this repository.









