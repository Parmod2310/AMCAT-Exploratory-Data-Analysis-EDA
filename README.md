# AMCAT Exploratory Data Analysis(EDA) on Dataset

## 1. Project Title
**AMCAT Exploratory Data Analysis(EDA) on Dataset**

## 2. Project Description
This project focuses on conducting Exploratory Data Analysis (EDA) on the AMCAT dataset, with a particular focus on understanding the factors that influence salary outcomes. The primary goal is to investigate the distribution of salary based on various attributes such as gender, specialization, and job roles. The analysis also tests specific claims, such as the salary expectations for fresh graduates in the Computer Science field, as well as the relationship between gender and specialization.

## 3. Dataset
The dataset was imported using pandas (`pd.read_csv()`). Key features used in this analysis include:
- **Salary**: The target variable representing the income of individuals.
- **Gender**: Categorical variable indicating the gender of the individual.
- **Specialization**: Categorical variable indicating the academic specialization.
- **Job Role**: Categorical variable detailing the role in the company.
- **Other Features**: Age, experience, and various other attributes influencing salary.

## 4. Steps Followed
1. **Data Import and Inspection**: Loaded the dataset, inspected the structure, and checked for missing values.
2. **Univariate Analysis**: Explored the distributions of both numerical and categorical variables using histograms, boxplots, and countplots.
3. **Bivariate Analysis**: Examined the relationships between variables using scatter plots, boxplots, and barplots to detect patterns between salary and other features.
4. **Research Questions**: 
   - Tested if fresh graduates in Computer Science roles earn between 2.5 to 3 lakhs.
   - Evaluated if gender has an impact on specialization preference.
5. **Conclusion**: Summarized the findings and insights drawn from the analysis.

## 5. Results
- The analysis found specific salary trends based on job roles, gender, and specialization.
- The claim about fresh graduate salaries in the field of Computer Science was tested and verified.
- A significant relationship between gender and specialization was identified through statistical testing.

## 6. Usage Instructions
To use the Jupyter Notebook:
1. Clone the repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Open the `.ipynb` file in Jupyter Notebook and run the cells to see the full EDA and visualizations.
4. The results and conclusions are provided at the end of the notebook.


