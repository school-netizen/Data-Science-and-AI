## Key Insights

1. The Titanic dataset contains passenger demographic, travel, fare, and survival information.

2. Missing values were identified using `isnull().sum()` and handled using appropriate techniques:
   - Median imputation for Age.
   - Mode imputation for Embarked.
   - "Unknown" for missing Cabin values.

3. Duplicate records were checked using `duplicated()` and removed using `drop_duplicates()`.

4. Grouping by gender shows differences in survival rates between male and female passengers.

5. Passenger class analysis shows differences in survival rates and average fares across the three passenger classes.

6. Grouping passengers by both class and gender provides a more detailed view of survival patterns.

7. Family size was calculated using SibSp and Parch and analyzed to understand its relationship with survival.

8. Descriptive statistics using `describe()` provided information about the distribution of numerical variables such as Age and Fare.

9. Visualizations were used to understand passenger survival, age distribution, fare distribution, and relationships between numerical variables.

10. Overall, the analysis demonstrates the use of Pandas for data loading, inspection, cleaning, transformation, grouping, aggregation, and statistical exploration.
