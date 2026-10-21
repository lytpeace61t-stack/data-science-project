<img width="875" height="2268" alt="image" src="https://github.com/user-attachments/assets/1d76dca7-5e7b-425f-bae4-2ceaad9fb164" /># data-science-project
A data science project for CISC7204
AI Usage and Student Academic Performance
Problem and Research Question
This project explores the relationship between students' daily AI usage and academic learning outcomes.

The main research question is:

How is daily AI usage associated with students' study hours, critical thinking scores, assignment scores, and GPA in a synthetic dataset?

Dataset Source and Usage Permissions
The dataset was synthetically generated using Python and NumPy for educational purposes. It contains 300 simulated student records, including AI usage hours, study hours, attendance, assignment scores, critical thinking scores, GPA, and academic major.

The dataset does not contain real student information or personal data. It may be used for educational analysis and demonstration purposes.

Methods and Tools
The analysis was conducted in Jupyter Notebook using:

Python
NumPy
Pandas
Matplotlib
Seaborn
Polynomial regression
Correlation analysis
Exploratory data analysis
Key Findings
The correlation heatmap shows that AI usage has a negative correlation with critical thinking score and a weaker negative correlation with GPA in this synthetic dataset.

The polynomial regression visualization indicates a nonlinear relationship between AI usage and GPA. GPA increases slightly at lower to moderate levels of AI usage, but decreases when AI usage becomes higher.

The boxplot also shows that students in the highest AI usage groups tend to have a lower median GPA than students in some lower usage groups.

Limitation
A major limitation is that the dataset is synthetic. The relationships were defined during the data-generation process, so the findings do not represent real students and cannot demonstrate causation.

Repository Contents
student_ai_analysis.ipynb.ipynb: Jupyter Notebook containing the analysis
student_ai_learning_dataset (2).xls: Synthetic student dataset
ai_usage_gpa_regression.png.png: Polynomial regression visualization
correlation_heatmap.png.png: Correlation heatmap
gpa_by_ai_usage_group.png.png: GPA distribution boxplot
How to Run the Analysis
Download or clone this repository.

Install the required Python packages:

pip install -r requirements.txt

Open Jupyter Notebook.

Open student_ai_analysis.ipynb.ipynb.

Run all cells in order.

Project Status
Completed
