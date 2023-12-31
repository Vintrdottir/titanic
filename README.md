# Guess who will survive the sinking of the Titanic

## Introduction

Striking an iceberg led to the sinking of the Titanic on April 15, 1912, resulting in the tragic loss of 1502 lives out of 2224 passengers and crew. This incident had a profound impact globally, prompting the establishment of improved safety regulations for maritime travel.

A significant factor contributing to the high casualty count was the insufficient number of lifeboats available for passengers and crew. 

Exploring the tragic yet captivating story of the Titanic, we delve into the dataset of its passengers, unraveling insights into the factors that influenced survival. This analysis aims to shed light on the demographics and circumstances surrounding those who managed to survive this historic maritime disaster.

## Source
[Titanic Competition on Kaggle](https://www.kaggle.com/competitions/titanic)
---------------------------------------------------

![image](https://github.com/Vintrdottir/titanic/assets/60987792/6a634930-2f93-4463-8e1c-13be1de3278a)

## Data Overview
The dataset provides details about the individuals who were on the Titanic when it sank in 1912. It includes information such as age, gender, passenger class, fare amount, and whether the passenger survived or not. Each data point is a window into the lives of those aboard, making it a valuable resource for understanding the dynamics at play during that fateful journey.

## Column description
- PassengerId: unique identifier for each passenger
- Survived: whether the passenger survived (1) or not (0)
- Pclass: passenger class (1 = 1st class, 2 = 2nd class, 3 = 3rd class)
- Name: name of the passenger
- Sex: gender of the passenger
- Age: age of the passenger (in years)
- SibSp: number of siblings or spouses aboard the Titanic
- Parch: number of parents or children aboard the Titanic
- Ticket: ticket number
- Fare: passenger fare
- Cabin: cabin number
- Embarked: port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)



## Class Distinctions - did the rich had a better chances?
Passenger class emerges as a significant determinant of survival. A closer look at the distribution across different classes reveals intriguing disparities. First-class passengers, it appears, had a notably higher chance of survival compared to their counterparts in lower classes:

![image](https://github.com/Vintrdottir/titanic/assets/60987792/76190d17-fdeb-4844-872e-8331da5c4276)



## Which gender had a better chace?

The gender breakdown further unravels the stark differences in survival rates between males and females.
<img width="572" alt="image" src="https://github.com/Vintrdottir/titanic/assets/60987792/5362bbbd-c065-4f4d-94c4-34c5e646032d">


As we can see - most females survived, while the majority of males did not.



## What about the age?

By visualizing the age distribution, we discern patterns that illuminate the age groups most likely to survive. 

![image](https://github.com/Vintrdottir/titanic/assets/60987792/12276962-6cc4-489b-a740-13a448140f7e)

![image](https://github.com/Vintrdottir/titanic/assets/60987792/99eaaa40-94c2-4812-9de6-93cec50696db)

Regrettably, the depicted graphs above do not appear to reveal any distinct insights. We have to dig deeper:

![image](https://github.com/Vintrdottir/titanic/assets/60987792/da6b11d5-b5ae-4203-8dfb-51361f67a56c)

Observing the density of AgeFill based on passenger class reveals a trend where first-class passengers tended to be older than second-class passengers, and second-class passengers were generally older than third-class passengers. This aligns with our previous findings that first-class passengers exhibited a higher survival rate compared to second-class passengers, who, in turn, had a higher survival rate than third-class passengers.

## Did larger families fare better, or was it the solo travelers who had a higher chance of making it out alive? 


<img width="573" alt="image" src="https://github.com/Vintrdottir/titanic/assets/60987792/9a6201ec-1875-47fd-95fe-df621e1fa5fe">

Upon examining the histograms, it is not readily apparent how FamilySize directly influences the likelihood of survival. The visual representation does not immediately reveal any discernible patterns or trends regarding the impact of FamilySize on survival outcomes.


## Conclusion
In the aftermath of the Titanic disaster, the dataset allows us to piece together the puzzle of survival. Through visualizations and statistical insights, we've uncovered trends that go beyond the historical narrative.

This analysis serves as a tribute to those who boarded the Titanic, offering a glimpse into their stories, choices, and the circumstances that defined their survival. The Titanic dataset continues to be a poignant reminder of the human aspect behind the statistics, inviting us to reflect on the lives affected by this tragic event.



