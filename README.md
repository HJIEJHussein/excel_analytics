# Magi Ndogo water crisis analysis

## Table of contents

- [Project Overview](#project-overview)
- [Data source](#data-source)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Visualisations and report](#Visualisations-and-report)

### Project Overview

This project aims to analyse data gathered about the average time it takes the population of Magi Ndogo to obtain water from the different 
water sources as well as the data about the microbiological nd chemical status about those water sources
The Goal of this project is to privide an action plan we will carry on in order to provide clean water to the population and with a reduced 
average time for Queuing 

### Data source 

The primary dataset used for this analysis is the script file in the SQL script files rubric of the "md_water_services.mwb" file, containing the database of the project [https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Md_water_services.mwb] and also the excel file "Md_water_services_data" for the Power BI visualisations and report [https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Md_water_services_data.xlsx] 

### Tools

- SQL Server : Data analysis
- Power BI : Creating Reports

### Exploratory Data Analysis

- What is the type of most of the water sources : Urban or rural ?
- What is the type of the water source that is the most used by the population of Magi Ndogo ?
- What percentage of the population has water piped directly into their households? and How many of them face non_fonctionnal systems due to issues with pipes, pumps and reservoirs ?
- How many people use wells and how many of them are polluted ?
- What is the average time for water ? On what days is the average time the shortest or the longest ? and on which hours ?

### Data Analysis

- Used MySQL Worbench software to code and respond to those questions,check the "md_water_services.mwb" file [https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Md_water_services.mwb]


### Findings

-  Most water sources are rural in Maji Ndogo.
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Number%20of%20sources%20per%20location_type.png)
-  43% of our people are using shared taps. 2000 people often share one tap.
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Pct%20number%20of%20people%20per%20type%20of%20water%20source.png)
   
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/average%20number%20of%20people%20per%20type%20of%20water%20source.png)
   
-  31% of our population has water infrastructure in their homes
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Pct%20number%20of%20people%20per%20type%20of%20water%20source.png)

-  45% face non-functional systems due to issues with pipes, pumps, and reservoirs. Towns like Amina, the rural parts of Amanzi, and a couple
   of towns across Akatsi and Hawassa have broken infrastructure.
   
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/percentage%20of%20people%20per%20source%20type%20and%20per%20province%20name.png)
   
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/pct%20of%20tap%20in%20home%20broken%20by%20town%20name%20and%20province%20name.png)
   
-  18% of our people are using wells of which, but within that, only 28% are clean. These are mostly in Sokoto, Kilimani and Akatsi.
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/pct%20of%20wells%20per%20results.png)
   
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/pct%20of%20clean%20wells%20per%20province.png)
   
-  Our citizens often face long wait times for water, averaging more than 120 minutes
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/average%20time%20of%20queue.png)

-  Queues are very long on Saturdays and Wednesdays and Sundays have the shortest queues
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/average%20queue%20time%20per%20day%20of%20the%20week.png)
   
-  Queues are longer in the mornings and evenings.
  
   ![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/average%20queue%20time%20per%20hours%20of%20the%20day.png)

### Recommendations 

- If communities are using rivers, we will dispatch trucks to those regions to provide water temporarily in the short term, while we send out
crews to drill for wells, providing a more permanent solution. Sokoto is the first province we will target.
- If communities are using wells, we will install filters to purify the water. For chemically polluted wells, we can install reverse osmosis (RO)
filters, and for wells with biological contamination, we can install UV filters that kill microorganisms - but we should install RO filters too. In
the long term, we must figure out why these sources are polluted.
-  For shared taps, in the short term, we can send additional water tankers to the busiest taps, on the busiest days. We can use the queue time
pivot table we made to send tankers at the busiest times. Meanwhile, we can start the work on installing extra taps where they are needed.
According to UN standards, the maximum acceptable wait time for water is 30 minutes. With this in mind, our aim is to install taps to get
queue times below 30 min. Towns like Bello, Abidjan and Zuri have a lot of people using shared taps, so we will send out teams to those
towns first.
-  Shared taps with short queue times (< 30 min) represent a logistical challenge to further reduce waiting times. The most effective solution,
installing taps in homes, is resource-intensive and better suited as a long-term goal.
-  Addressing broken infrastructure offers a significant impact even with just a single intervention. It is expensive to fix, but so many people can
benefit from repairing one facility. For example, fixing a reservoir or pipe that multiple taps are connected to. We identified towns like Amina,
Lusaka, Zuri, Djenne and rural parts of Amanzi seem to be good places to start.

### Visualisations and report 

Used Power BI software to represent the visualisations of our previous findings and to confirm them,check the "md_water_services.mwb" file [https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Magi%20Ndogo%20Report.pbix] :
  
- 43 % of our population are using shared taps, 18% are using wells and 31% have water infrastructure within their homes
- 45% face non-functional systems due to issues with pipes, pumps, and reservoirs.
- Our citizens often face long wait times for water, averaging more than 120 minutes
- Queues are very long on Saturdays and Wednesdays and Sundays have the shortest queues
- During the week, people queue early in the morning, or late in the afternoon, before or after work. On the weekends, people queue throughout the
  day more consistently.
- Women queue for water a lot more than men
- Only 28% of wells are clean, These are mostly in Sokoto, Kilimani and Akatsi
  
![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/National%20statistics.png)

![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Queue%20page.png)

![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Pollution%20Page.png)

- As water collectors, women are twice as likely to be a victim of crime than men.
- Women are most likely to be victims of harassment, followed by sexual assault.
- Crime spikes over weekends, and almost twice as many crimes are committed early in the mornings or at night with women again facing the
  greatest threat.
- In Amanzi, women face significantly less risk of being crime victims, because in Amanzi, the number of men queuing is twice the number of female

![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Crime%20related%20Data.png)

![alt text](https://github.com/HJIEJHussein/Hussein-s_portfolio/blob/main/Crime%20related%20data%202.png)
