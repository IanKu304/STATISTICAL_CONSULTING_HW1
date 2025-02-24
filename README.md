# STATISTICAL_CONSULTING_HW1
 RE6131066


## Variable description

-   **Survival**: Survival status (0 = No 38%, 1 = Yes 62%)

<!-- -->

-   **Pclass**: Ticket class (Ordinal variable: 1 = 1st, 2 = 2nd, 3 = 3rd)

-   **Sex**: Gender (Nominal variable: male = Male 65%, female = Female 35%)

-   **Age**: Age (Continuous variable: 0.42 - 80, 177 missing values)

-   **SibSp**: Number of siblings or spouses aboard the ship (Ordinal variable: 0 - 8)

-   **Parch**: Number of parents or children aboard the ship (Ordinal variable: 0 - 6)

-   **Ticket**: Ticket number

-   **Fare**: Ticket price (Continuous variable: 0 - 512, no missing values)

-   **Cabin**: Cabin number

-   **Embarked**: Port of embarkation (C = Cherbourg 19%, Q = Queenstown 9%, S = Southampton 72%, 2 missing values)

## Discussion
a)  Survival Analysis (Survived) More people did not survive (Survived = 0, shown in red). The survival rate seems to vary significantly with Sex and Pclass.

b)  Passenger Class (Pclass) First-class (Pclass = 1) passengers had a higher fare and survival rate. Third-class (Pclass = 3) passengers had the lowest survival rate.

c)  Gender Influence (Sex) Female passengers had a higher survival rate than males. Males had a lower chance of survival, as indicated by the red proportion in the Sex vs. Survived plots.

d)  Age Distribution (Age) Young children had a higher survival rate. The majority of passengers were adults. There is a negative correlation between Age and Survival (older passengers had a lower chance of survival).

e)  Family Members (SibSp and Parch) Having more siblings/spouses (SibSp) or parents/children (Parch) slightly increases survival probability, but very high numbers reduce survival chances. Large families had a lower survival rate compared to single passengers.

f)  Fare and Survival (Fare) Higher Fare is positively correlated with survival (Corr = 0.538\*\*\*), indicating that wealthier passengers had better chances. This aligns with the observation that first-class passengers survived more.

g)  Embarkation Port (Embarked) Most passengers embarked from Southampton (S). Higher survival rates are observed among passengers from Cherbourg (C), likely due to a higher proportion of first-class passengers.
