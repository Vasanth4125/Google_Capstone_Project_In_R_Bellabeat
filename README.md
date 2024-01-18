# How Can a Wellness Technology Company Play It Smart?

## 1 . Introduction:

Hi, I am Vasanth Kumar. I have completed my Google Data Analytics Professional Certificate course on Coursera. Throughout my journey on this course, I have been introduced to data analysis and gained valuable skills. This capstone project will help me solidify my knowledge and I will acquire new skills by completing this very project.

## 2 . Scenario:

I am a **junior data analyst** working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global [smart device](https://en.wikipedia.org/wiki/Smart_device) market. Urška Sršen, cofounder and cheif creative officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. I have been asked to focus on one of Bellabeat's products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights discovered will help guide marketing strategy for the company. I will present my analysis to the Bellabeat executive team along with our high level recommendations for Bellabeat's marketing strategy.

## 3 . Characters and products:

### Characters

- Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
- Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
- Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and
reporting data that helps guide Bellabeat’s marketing strategy. You joined this team six months ago and have
been busy learning about Bellabeat’’s mission and business goals — as well as how you, as a junior data analyst,
can help Bellabeat achieve them.

### Products

- Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress,
menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and
make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
- Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects
to the Bellabeat app to track activity, sleep, and stress.
- Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user
activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your
daily wellness.
-  Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are
appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your
hydration levels.
- Bellabeat membership: Bellabeat also offers a subscription-based membership program for users.
Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and
beauty, and mindfulness based on their lifestyle and goals.

## 4 . About the company:

Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen
used her background as an artist to develop beautifully designed technology that informs and inspires women around the
world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with
knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly
positioned itself as a tech-driven wellness company for women.
By 2016, Bellabeat had opened offices around the world and launched multiple products. Bellabeat products became available
through a growing number of online retailers in addition to their own e-commerce channel on [their website](https://bellabeat.com/). The company
has invested in traditional advertising media, such as radio, out-of-home billboards, print, and television, but focuses on digital
marketing extensively. Bellabeat invests year-round in Google Search, maintaining active Facebook and Instagram pages, and
consistently engages consumers on Twitter. Additionally, Bellabeat runs video ads on Youtube and display ads on the Google
Display Network to support campaigns around key marketing dates.
Sršen knows that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has
asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain
insight into how people are already using their smart devices. Then, using this information, she would like high-level
recommendations for how these trends can inform Bellabeat marketing strategy.

## 5 . Steps of the Data Analysis Process

## I . ASK
   
   Sršen asks you to analyze smart device usage data in order to gain insight into how consumers use non-Bellabeat smart
devices. She then wants you to select one Bellabeat product to apply these insights to in your presentation.

### Business Task:

### Problem Statement

To identify the trends and patterns of smart devices which will explain how people use non-Bellabeat smart devices. These insights will inform a well-tailored marketing strategy that will unlock growth opportunities for Bellabeat.

### Business Objectives

Generate insights that will guide the decision-making process on what product features, services, and marketing strategies will improve Bellabeat’s membership program and market presence:

- Increasing customer acquisition for the subscription-based membership program
- Improving current Bellabeat customers' overall experience and satisfaction with the Bellabeat membership program
- Increasing overall sales and profit for Bellabeat

### Core Deliverables

Process secondary data to understand the target audience better and find opportunities in the market that Bellabeat can exploit:

- Analyze for trends, patterns, and key insights
- Identify key areas of opportunity for features or metrics to implement in future products or software updates. Deriving insights from customer tendencies and health data
- Consider additional forms of data such as current health issues in women's health that are not being measured

### Key Stakeholders

The key stakeholders of this project are Urška Sršen (Chief Creative Officer), Sando Mur (Mathematician and Bellabeat’s cofounder) and Bellabeat’s marketing analytics team.

## II . PREPARE

Sršen encourages you to use public data that explores smart device users’ daily habits. She points you to a specific data set:

   - [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) ( CC0: Public Domain, dataset made available through [Mobius](https://www.kaggle.com/arashnic) ) : This Kaggle data set
contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.

Sršen tells this data set might have some limitations, and encourages you to consider adding another data to help
address those limitations as begin to work more with this data.

### Data Preparation

#### Specifics

- Stored on Google Drive
- Most data is Long formatted
- Datasets
    - 18 extensive data sets
    - Time period: 04/12/2016 - 05/12/2016
    
#### Dataset used

The data used for this case study is generated by respondents to a distributed survey via Amazon Mechanical Turk.

| Filename                           | Size         |
|------------------------------------|--------------|
| dailyActivity_merged.csv           | 111.29 kB    |
| dailyCalories_merged.csv           | 25.13 kB     |
| dailyIntensities_merged.csv        | 70.58 kB     |
| dailySteps_merged.csv              | 25.18 kB     |
| heartrate_seconds_merged.csv       | 89.59 MB     |
| hourlyCalories_merged.csv          | 801.49 kB    |
| hourlyIntensities_merged.csv       | 898.78 kB    |
| hourlySteps_merged.csv             | 796.56 kB    |
| minuteCaloriesNarrow_merged.csv    | 66.44 MB     |
| minuteCaloriesWide_merged.csv      | 22.99 MB     |
| minuteIntensitiesNarrow_merged.csv | 46.36 MB     |
| minuteIntensitiesWide_merged.csv   | 3.31 MB      |
| minuteMETsNarrow_merged.csv        | 47.69 MB     |
| minuteSleep_merged.csv             | 8.85 MB      |
| minuteStepsNarrow_merged.csv       | 46.53 MB     |
| minuteStepsWide_merged.csv         | 3.48 MB      |
| sleepDay_merged.csv                | 18.1 kB      |
| weightLogInfo_merged.csv           | 6.73 kB      |

I will be using the above 6 datasets to analyze the data and gain insights for my analysis.


#### Data ROCCC

- Reliable: Dataset presents sample size of 30 fitbit users with their consent. But the data lacks demographic, age and gender details . So we can say that this data is not completely reliable for analysis.
- Original: Dataset is available through distributed survey via Amazon Mechanical Turk. So it is from a trusted source and is original too.
- Comprehensive: This dataset is of rather smaller group with only 30 participants without any demographic, gender and age details. Since the analysis is for Bellabeat that focuses on women's health it would have been good to have dataset with gender and age details. So this dataset is not comprehensive.
- Current: This dataset was collected in 2016 between 12/04/2016 to 12/05/2016 and after that there has been lot of upgrades to the fitbit devices and other details may also be available if the survey is recent or data collected is recent. So the data is not current and outdated.
- Cited: The data is from a trusted source and is made available through Kaggle by a valid user and is licenced for use in public domain.

#### Licensing, privacy, security, and accessibility:

- The data is publicly available and is only analyzed for company use and to be handled by Bellabeat analytics team.
- It is stored in Google Drive which has sufficient security considering the project.

#### Data Relevancy:

- This is an extensive amount of data and variables provided related to daily activity, health metrics, and habits. This information can be used to devise solutions and new features for future Bellabeat products and updates.

#### Data Integrity:

- Each spreadsheet was checked for missing data, errors, incorrect entries, and incorrect formatting. Data was manually corrected by using "find and Replace" in spreadsheets or "Case Statements" in SQL. There were many blanks where no data was found, indicating that FitBit users did not wear their smart-devices every day.
- There is a sampling bias as the data only includes Fitbit users. Meaning the sample size only includes people who are mindful and proactive with their wellbeing. According to ValuePenguin, those who wear smartwatches exercise 35.6% more than those who do not.

## III . PROCESS
    
I have used RStudio for this project to help process and analyze and for visualization. In order to solve this business task, one of the given 18 datasets were used.

### Installing packages and importing files with chosen dataset

``` R
library(readr)  
library(tidyverse)
library(lubridate)
library(tidyr)
library(ggplot2)
library(skimr)
```
``` R
dailyActivity <- read_csv("../input/fitbit/Fitabase Data 4.12.16-5.12.16/dailyActivity_merged.csv")
head(dailyActivity)
```
### Data cleaning and manipulation

Finding out the basic information of dailyActivity :

- no. of rows and columns
- name of columns
- type of values

``` R
#skimming the data
skim_without_charts(dailyActivity)
```
``` R
# count distinct value of "Id" 

n_distinct(dailyActivity$Id)
```
### Results:

dailyActivity

- File consists dailyActivity of 940 rows and 15 columns.
- There is no Null or missing values.
- ActivityDate column is classified as character data type, all others are numeric.
- There are 33 unique IDs, instead of 30 expected.


#### Plan of data cleaning and manipulation:

dailyActivity

- Convert ActivityDate column to date type format yyyy-mm-dd.
- Create new column DayOfTheWeek by separating the date into day of the week.
- Create new column TotalMins being the sum of VeryActiveMinutes, FairlyActiveMinutes, LightlyActiveMinutes and SedentaryMinutes.
- Create new column TotalHours by converting new column of to TotalMins number of hours.
- Rearrange columns.

``` R
# convert "ActivityDate" to date format yyyy-mm-dd
dailyActivity$ActivityDate <- mdy(dailyActivity$ActivityDate)
# print first 6 rows to confirm
head(dailyActivity)
```
``` R
#adding new column "DayOfTheWeek" 

dailyActivity <- dailyActivity %>% 
  add_column(DayOfTheWeek = wday(dailyActivity$ActivityDate, label=TRUE))

# print first 5 rows of DayOfTheWeek to confirm the changes
head(dailyActivity$DayOfTheWeek)
```
``` R
#adding a new column "TotalMins" that is showing total activity minutes

dailyActivity$TotalMins = rowSums(dailyActivity[,c("VeryActiveMinutes", "FairlyActiveMinutes", "LightlyActiveMinutes", "SedentaryMinutes" )])

# print first 5 rows of "TotalMins" to confirm the changes

head(dailyActivity$TotalMins)
```
``` R
#adding a new column "TotalHours" that is showing total activity hours

dailyActivity$TotalHours = round(dailyActivity$TotalMins/60)

# print first 5 rows of "TotalHours" to confirm the changes

head(dailyActivity$TotalHours)
```
``` R
#rearranging columns

dailyActivity <- dailyActivity[,c(1,2,16,3,4,5,6,7,8,9,10,11,12,13,14,17,18,15)]

# print column names to confirm

colnames(dailyActivity)
```
## IV . ANALYZE

``` R
#getting statistic information about the dataset

summary(dailyActivity)
```
### Results:

- Tuesday, Wednesday and Thursday are the days when people use FitBitTracker the most.
- Most of the logged activity is sedentary. On the average, 991.2 minutes is sedentary, which is more than 81% of total activity minutes.
- On average, users do 7638 steps during logged session, which is 5.475 km. According to National Institute of Health, "Compared with people who took 4,000 steps a day, those who took 8,000 steps a day at the start of the study had a 50% lower risk of dying from any cause during follow-up. People who took 12,000 steps a day had a 65% lower risk of dying than those who took only 4,000."
- Average burned calories is 2304. With no information about gender, age, weight, it is impossible to interpret. According to NHS, age, lifestyle, size, hormones. medicines, being unwell can affect how much amount of energy is burning.

## V . SHARE

``` R
#visualize information about logged activities throughout the week

ggplot(dailyActivity, aes(x=DayOfTheWeek))+ 
geom_bar(fill='lightblue',color='black')+
labs(x = "Day of the week", y = "Frequency")+
ggtitle("Logged Activities Throughout The Week")
```
``` R
#plotting a scatterplot of calories burned for every step taken

ggplot(dailyActivity, aes(x=TotalSteps, y=Calories)) + 
  geom_point(fill="#F57E51",
             color="#F57E51",
             shape=21,
             alpha=0.5,
             size=4)+
  ggtitle("Calories burned for every step taken")+
  geom_hline(yintercept = mean(dailyActivity$Calories, na.rm=TRUE),color="#B8F222")+
  geom_vline(xintercept = mean(dailyActivity$TotalSteps, na.rm=TRUE),color="#2E5FF2")+
  geom_smooth(method=lm, formula = y ~ x)
```
## Results:

- It is a positive correlation.
- It is noticeable that intensity of calories burned increase when users are at the range of > 0 to 15,000 steps with calories burn rate cooling down from 15,000 steps onwards.

``` R
#creating a dataframe 

 df <- data.frame (Type = c("Very Active Minutes", "Fairly Active Minutes","Lightly Active Minutes", "Sedentary Minutes"),
                   Sums = c(sum(dailyActivity$VeryActiveMinutes), sum(dailyActivity$FairlyActiveMinutes), sum(dailyActivity$LightlyActiveMinutes), sum(dailyActivity$SedentaryMinutes)))
 df
```
``` R
#calculating percentages
sums_all <- sum(df$Sums,na.rm=TRUE)
df <- df %>%
  mutate(Percent = (Sums /sums_all) * 100)
```
``` R
#plotting a pie chart

ggplot(df, aes(x = "", y = Percent, fill = Type)) + 
  geom_bar(stat = "identity", width = 1) + 
  coord_polar(theta = "y") + 
  geom_text(aes(label = ifelse(Percent > 5, paste0(round(Percent, 1), "%"), "")), position = position_stack(vjust = 0.5)) +
  ggtitle("Percentage of activity in minutes") +
  theme_void()
```
## Results:

- Sedentary minutes takes the biggest slice at 81.3%. This indicates that users are using the FitBit app to log daily activities, for example during working hours, commute time.
- The smallest slices are fairly active activity (1.1%) and very active activity (1.7%)So users don't use the app as intended to track fitness.

## VI . ACT

In the final step, we deliver our insights based on our analysis. Remembering our business task, we give recommendations.

- What are the trends identified?

Majority of users (81.3%) are using the FitBit app to track sedentary activities.
Users prefer to track their activities during weekdays as compared to weekends

- How could these trends apply to Bellabeat customers?

Both companies focus on providing users with tools that help track habits and fitness activity and encouraging them to make healthy decisions. These trends can be applied to Bellabeat customers, considering the limitations of the data.

- How could these trends help influence Bellabeat marketing strategy?

    - Bellabeat marketing team can include function in Bellabeat app to encourage users who tends to have a high number to sedentary minutes to do different types of simple exercises that don't take a lot of time but help to build a habit.
    - The marketing team can educate users about fitness benefits, calories intake and burnt rate information on the Bellabeat app.
    - The marketing team can create a rewards system to encourage users to log in on the weekend and have a workout or walk outside.


 🙂
 💻
