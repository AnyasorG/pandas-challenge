# School Performance and Standardized Test Data in the City's School District
This project provides an analysis of district-wide standardized test results, incorporating math and reading scores alongside relevant school information. The data used for analysis includes student-level and school-level datasets, covering standardized test results, student details, and school attributes.

## Table of Contents
- [Prerequisites](#prerequisites)
- [How to Use the Jupyter Notebook](#how-to-use-the-jupyter-notebook)
- [License](#license)
- [Code Source](#code-source)
- [Written Report](#written-report)

## Prerequisites
To run this project, you'll need the following:
- Jupyter Notebook installed on your system.
- The Python programming language.
- Knowledge of Pandas for data analysis.
You should also have the following CSV files available in a directory:
- `school_complete.csv`: School-level data.
- `students_complete.csv`: Student-level data.

## How to Use the Jupyter Notebook
1. Clone this repository to your local machine or download the Jupyter Notebook file and CSV files.
2. Ensure you have the required CSV files (`school_complete.csv` and `students_complete.csv`) in the same directory as the Jupyter Notebook file, or update the file paths in the notebook to specify the correct locations.
3. Open a terminal or command prompt and navigate to the directory containing the Jupyter Notebook file.
4. Run the Jupyter Notebook to execute it interactively.

## License
This project is open-source and is made available under the terms of the MIT License. The MIT License is a permissive open-source license that allows you to use, modify, and distribute this software for your own purposes. For the full details of the MIT License, please refer to [MIT License Details](https://choosealicense.com/licenses/mit/).

## Code Source
The code source can be found here: [GitHub Repository](https://github.com/AnyasorG/pandas-challenge)

### School Performance and Standardized Test Data
- Source: Mockaroo, LLC (2022) and edX Boot Camps LLC
- Source Code: 
- Location: Provided CSV files (`school_complete.csv` and `students_complete.csv`)
- Description: The data was generated for educational purposes and underwent cleaning, handling of missing values, and conversion of currency values into numerical formats. Analysis was performed using the Python programming language (version 3.10.13 packaged by Anaconda, Inc.) and Pandas library (version 2.0.3). The analysis was conducted in Jupyter Notebook (version 5.3.0), leveraging Pandas for data processing and manipulation. The project followed a structured methodology to ensure the data was well-processed and suitable for analysis.

## Key Findings and Analysis
Based on the data provided, the district has a total of 15 schools, serving 39,170 students, with a combined budget of $24,649,428.00. The average math score is approximately 78.99, and the average reading score is approximately 81.88. About 74.98% of students pass the math standardized test, while approximately 85.81% pass the reading test. The overall passing rate, considering both math and reading, is approximately 65.17%.

### School Performance by Type
It was observed that there were two school types: Charter and District. Charter schools showed higher performance in both math and reading, with significantly higher passing rates. This indicates that charter schools may have more effective teaching methods or resources. District schools, on the other hand, showed lower average scores and passing rates. This suggests that additional support may be required in district schools to improve student outcomes.

### School Performance by Size
The analysis categorized schools based on their sizes as Small (<1000 students), Medium (1000-2000 students), and Large (2000-5000 students). Smaller schools displayed higher average math and reading scores, along with better passing rates in math and reading. Larger schools showed lower average scores and passing rates. This could be attributed to challenges related to managing larger student populations.

### School Performance by Spending
The analysis categorized schools based on their per-student budgets into spending ranges. The categories were: “<$585, $585-630, $630-645, and $645-680”. Charter schools with lower per-student budgets exhibited higher average scores and passing rates. This indicates that cost-effective education may lead to better student outcomes. District schools with higher budgets did not necessarily translate to better performance, suggesting that additional spending does not always result in improved outcomes.

## Recommendations for Strategic Improvement
- Examine School Type Dynamics: Conduct an in-depth exploration of the practices and teaching methodologies employed in charter schools. Evaluate their effectiveness and consider the feasibility of implementing successful strategies within district schools.
- Addressing School Size Challenges: Deliberate on the possibility of disaggregating larger schools into more manageable smaller units. Alternatively, strategically allocate additional resources to enhance student-teacher interaction, especially in larger schools.
- Enhancing Budget Optimization: Direct efforts towards meticulous optimization of per-student budgets to improve overall student performance. Prioritize investments in cost-effective strategies that ensure the delivery of quality education, maximizing the impact of financial resources.

## Conclusion
The analysis unveils profound insights into school performance, considering factors such as school type, size, and spending. Charter schools exhibit excellence, smaller schools consistently outperform larger counterparts, and the relationship between lower per-student budgets and superior outcomes challenges conventional assumptions. These collective findings offer a foundation for strategic decision-making and underscore the intricate interplay of diverse factors influencing academic performance in the district. As the district aspires to elevate overall educational outcomes, a meticulous exploration into successful models, allocation strategies, and educational practices becomes imperative.

## Written Report
The written report titled "School District Data Analyst Report" is located within the [GitHub repository](https://github.com/AnyasorG/pandas-challenge/blob/main/Written%20Report.docx).
