# Exploratory Data Analysis (EDA) on AI Job Dataset 📊

## Purpose 🎯
This Jupyter notebook conducts an **Exploratory Data Analysis (EDA)** on the "AI Job Dataset" to uncover insights, patterns, and relationships within the data. The primary goals are to:
- Understand the structure and characteristics of the dataset 📋.
- Identify key trends, distributions, and correlations in AI-related job postings 🔍.
- Visualize relationships between variables, such as experience level and years of experience 📈.
- Prepare the data for potential future analysis or modeling by cleaning and transforming it 🧹.
- Answer specific questions about the dataset, such as the average years of experience by experience level ❓.

The notebook serves as an educational tool for data analysts and scientists to practice EDA techniques and gain insights into the AI job market 🚀.

## Dataset 📂
- **Source**: The dataset is sourced from `'C:\Users\suryansh\Downloads\archive\ai_job_dataset.csv'`.
- **Description**: Contains 15,000 job postings related to AI roles, with details on job titles, salaries, experience levels, employment types, company locations, and more.
- **Columns**:
  - `job_id`: Unique identifier for each job posting 🆔.
  - `job_title`: Title of the job (e.g., AI Research Scientist, Data Analyst) 💼.
  - `salary_usd`: Salary in USD (or other currency as specified) 💰.
  - `salary_currency`: Currency of the salary 💸.
  - `experience_level`: Level of experience (e.g., EN for Entry, SE for Senior) 📚.
  - `employment_type`: Type of employment (e.g., FT for Full-Time, PT for Part-Time) ⏰.
  - `company_location`: Location of the company 🌍.
  - `company_size`: Size of the company (S, M, L) 🏢.
  - `employee_residence`: Residence of the employee 🏠.
  - `remote_ratio`: Percentage of remote work allowed 🌐.
  - `required_skills`: List of required skills 🛠️.
  - `education_required`: Required education level 🎓.
  - `years_experience`: Years of experience required ⏳.
  - `industry`: Industry of the job 🏭.
  - `posting_date`: Date the job was posted 📅.
  - `application_deadline`: Application deadline ⏳.
  - `job_description_length`: Length of the job description 📜.
  - `benefits_score`: Score representing job benefits 🌟.
  - `company_name`: Name of the company 🏬.

## Structure 🗂️
The notebook is organized into the following steps:
1. **Imports and Reading Data** 📥:
   - Imports necessary Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`).
   - Loads the dataset into a pandas DataFrame.
2. **Data Understanding** 🔎:
   - Examines the DataFrame's shape, head, tail, data types, and descriptive statistics.
3. **Data Preparation** 🛠️:
   - Renames columns for consistency (e.g., `Years_Experience` to `years_experience`).
   - Drops irrelevant columns or duplicates.
   - Handles missing values and creates new features if needed.
4. **Feature Understanding** 📉:
   - Conducts univariate analysis using visualizations like value counts, KDE plots, and boxplots to explore individual feature distributions.
5. **Feature Relationships** 🔗:
   - Performs bivariate analysis with scatter plots, pairplots, and correlation heatmaps to identify relationships between variables.
6. **Asking a Question** ❓:
   - Analyzes the average years of experience by experience level and visualizes it using a horizontal bar plot.

## Requirements 🛠️
To run the notebook, ensure the following are installed:
- **Python**: Version 3.x 🐍
- **Libraries**:
  - `pandas`: For data manipulation and analysis 📋.
  - `numpy`: For numerical operations 🔢.
  - `matplotlib`: For creating visualizations 📊.
  - `seaborn`: For enhanced statistical visualizations 🎨.

Install dependencies using:
```bash
pip install pandas numpy matplotlib seaborn
