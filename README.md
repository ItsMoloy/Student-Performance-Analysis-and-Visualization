# Student Performance Analysis and Visualization

This project analyzes and visualizes student performance data using Python. It employs **file handling, data structures, Pandas, NumPy, and Matplotlib** to process and display insights from student performance metrics.

## 🚀 Features
- **Data Handling**: Reads and writes student performance data from a CSV file.
- **Analysis & Statistics**: Computes **average, minimum, and maximum scores** for each student.
- **Attendance & Assignment Tracking**: Identifies students with **low attendance (<75%)** or **incomplete assignments**.
- **Visualization**:
  - Bar chart for **average scores per subject**.
  - Pie chart for **attendance distribution**.
  - Line graph for **student performance trends**.
- **Interactive Console**:
  - Add, update, and search student records.
  - Generate student performance reports.
- **Advanced Features** *(Optional)*:
  - Error handling for file operations.
  - Regular Expressions (RegEx) for student ID validation.
  - Decorators for function execution logging.

## 📂 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ItsMoloy/Student-Performance-Analysis-and-Visualization.git
   ```
2. Change to the project directory:
   ```bash
   cd Student-Performance-Analysis-and-Visualization
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```bash
   python student_performance.py
   ```

## 📊 Usage
### **Load Student Data**
```python
from student_performance import load_data

df = load_data("students.csv")
print(df.head())
```

### **Analyze Student Performance**
```python
from student_performance import analyze_scores

stats = analyze_scores(df)
print(stats)
```

### **Visualize Data**
```python
from student_performance import plot_average_scores, plot_attendance_pie

plot_average_scores(df)
plot_attendance_pie(df)
```

### **Update Student Records**
```python
from student_performance import update_student_data

df = update_student_data(df)
```

## 📜 Citation
If you use this project, consider citing:
```bibtex
@article{student-performance,
  title={Student Performance Analysis and Visualization},
  author={Moloy Banerjee},
  year={2025},
  journal={GitHub Repository}
}
```

## 📌 Contributing
Pull requests are welcome! To contribute:
1. Fork the repo.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a PR.

## 🔗 Resources
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)

---
Developed by **Moloy Banerjee**. 🚀

