

---

## 🧠 Problem Statement
The **Airline Crew Scheduling** problem involves assigning flights to available crew members while satisfying several real-world constraints such as:
- No overlapping flight timings for the same crew member  
- Minimum rest time between consecutive flights  
- Balanced distribution of flights among all crew members  

This scheduling task is **NP-Hard**, as the number of valid combinations grows exponentially with the number of flights.

---

## 🎯 Objectives
- Model airline crew scheduling as a **constraint satisfaction** problem  
- Implement a **backtracking algorithm** to find valid crew assignments  
- Enforce **non-overlapping** flight schedules and **rest period** constraints  
- Analyze performance using **profiling tools**  
- Visualize schedules using **Gantt charts** in Matplotlib  

---

## ⚙️ Technologies Used
- **Language:** Python  
- **Libraries:**  
  - `itertools`  
  - `time`  
  - `memory_profiler`  
  - `matplotlib`  
- **Platform:** Jupyter Notebook / Python Script  

---

## 📥 Input Format
```python
flights = [
    ('F1', 9, 11),
    ('F2', 10, 12),
    ('F3', 13, 15),
    ('F4', 16, 18)
]

crew_members = ['C1', 'C2', 'C3']
min_rest_time = 1  # hours
