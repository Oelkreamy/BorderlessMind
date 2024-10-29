## 📋 Project Overview
This project investigates the mental health challenges faced by international students studying in a foreign country, with a focus on factors such as social connectedness, acculturative stress, and length of stay. The analysis is based on data from a 2018 survey conducted at a Japanese international university, aiming to explore the mental health impact of studying abroad and to identify predictors for depression among students.

## 🎯 Objective
The primary goal is to determine if international students face a higher risk of mental health issues than domestic students and to examine if factors like social connectedness, acculturative stress, and length of stay can predict depressive symptoms.

## 🗂️ Data Description
The dataset (`students.csv`) contains the following columns:

| Field Name      | Description                                             |
| --------------- | ------------------------------------------------------- |
| `inter_dom`     | Types of students (International or Domestic)           |
| `japanese_cate` | Japanese language proficiency                           |
| `english_cate`  | English language proficiency                            |
| `academic`      | Current academic level (Undergraduate or Graduate)      |
| `age`           | Current age of the student                              |
| `stay`          | Length of stay in Japan (years)                         |
| `todep`         | Depression score (PHQ-9 test)                           |
| `tosc`          | Social connectedness score (Social Connectedness Scale) |
| `toas`          | Acculturative stress score (Acculturative Stress Scale) |

## 📊 Analysis
The analysis is conducted using SQL queries to extract insights from the dataset. Key steps include:

1. **Data Loading**: Load the data into a SQL-compatible environment to allow for analysis.
2. **Summary Statistics**: Calculate minimum, maximum, and average scores for depression, social connectedness, and acculturative stress across all students.
3. **Comparison by Student Type**: Focus on international students to analyze their mental health scores specifically, identifying any notable differences compared to domestic students.

## 🔍 Findings
This analysis provides insights into whether international students may be at a higher risk of mental health difficulties compared to domestic students. Additionally, it explores how factors like social connectedness and acculturative stress might predict depression scores, helping to identify potential areas for mental health support for international students.

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- SQL environment (e.g., PostgreSQL or SQLite for local testing)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Mental-Health-Analysis-International-Students.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Mental-Health-Analysis-International-Students
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook notebook.ipynb
   ```
2. Run the cells step-by-step to reproduce the analysis.
3. Make sure to have a SQL environment set up if you are running the queries locally.

## 🛠️ Project Structure
- `notebook.ipynb`: Jupyter Notebook containing the analysis and SQL queries.
- `students.csv`: Dataset used for analysis (note: this should be placed in the project directory).
- `mentalhealth.jpg`: Image used for illustration.
- `README.md`: Project description and instructions.
- `requirements.txt`: List of required packages.

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or suggestions.

## 📜 License
This project is licensed under the MIT License.
