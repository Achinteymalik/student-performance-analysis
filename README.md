# Student Performance Analysis 📊

A Python-based data analysis project that explores student marks, calculates performance metrics, and visualizes subject-wise results. This project demonstrates how **Pandas** and **Matplotlib** can turn a simple CSV dataset into clear, useful insights.

> **Project by:** Achintey Malik  
> **Area:** Python • Data Analysis • Data Visualization

---

## 🎯 Project Objective

The goal of this project is to analyse a sample student marks dataset and make it easier to understand academic performance. The program reads student records from a CSV file, handles missing or invalid marks, calculates averages, and creates a chart comparing subjects.

## ✨ Features

- **CSV data loading** – reads student marks from a structured CSV file.
- **Data cleaning** – converts mark columns to numeric values and fills missing marks using the subject average.
- **Student performance** – calculates the average marks for each student.
- **Subject analysis** – calculates and displays the average score for each subject.
- **Data visualization** – generates a bar chart of subject-wise average marks.
- **Reusable output** – saves the chart in an `output` folder.

## 🧰 Technologies Used

| Technology | Purpose |
|---|---|
| Python 3 | Main programming language |
| Pandas | Loading, cleaning, and analysing tabular data |
| Matplotlib | Creating the subject-average chart |
| CSV | Storing the sample student marks |

## 📁 Project Structure

```text
student-performance-analysis/
├── data/
│   └── student_marks.csv
├── output/
│   └── subject_averages.png   # Generated after running the program
├── main.py
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Achinteymalik/student-performance-analysis.git
cd student-performance-analysis
```

### 2. Create and activate a virtual environment (recommended)

**Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS / Linux:**
```bash

source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the project

```bash
python main.py
```

The program prints student averages and subject-wise averages in the terminal. It also creates the chart at:

```text
output/subject_averages.png
```

## 🗂️ Dataset Format

The sample CSV file contains one row per student and one column for each subject.

| Student | Math | Science | English |
|---|---:|---:|---:|
| Aarav | 82 | 76 | 88 |
| Diya | 91 | 85 | 90 |
| Kabir | 68 | 72 | 70 |
| Meera | 95 | 92 | 94 |
| Ishaan | 74 | 81 | 79 |

You can replace or extend the sample data. Keep the `Student`, `Math`, `Science`, and `English` column names, or update the subject list in `main.py` to match your CSV.

## 📈 Example Output

When the program runs, it displays:
- Each student's calculated average.
- The average marks for Math, Science, and English.
- A bar chart comparing average marks across subjects.

The chart is generated automatically and saved as `output/subject_averages.png`.

## 🧠 What I Learned

Through this project, I practised:
- Reading datasets from CSV files.
- Working with rows and columns using Pandas.
- Converting values to numeric data and handling missing values.
- Using averages to summarize data.
- Creating and saving visualizations with Matplotlib.
- Organizing a small Python project into clear folders and files.

## 🚀 Future Improvements

- Allow users to upload their own dataset.
- Add more subjects and student records dynamically.
- Calculate highest, lowest, median, and grade-wise performance.
- Add comparison charts for individual students.
- Build an interactive dashboard using Streamlit.
- Export a summary report to CSV or PDF.

## 🤝 Contributions

This is a learning project. Suggestions and improvements are welcome through GitHub Issues or Pull Requests.

## 📄 License

This project is distributed under the license included in this repository.

---


