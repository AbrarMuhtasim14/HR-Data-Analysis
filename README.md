# HR Data Analysis with Python

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** Simulated HR records across multiple departments

---

## Project Overview
This project performs **in-depth HR analytics** using **Pandas** to uncover workforce trends, employee attrition patterns, and performance insights. The analysis covers key HR metrics such as headcount, resignation rates, salary distribution, and departmental performance.

---

## Key Questions Answered (Q1–Q10)
| Q# | Question |
|----|--------|
| 1 | Distribution of Employee Status (Active, Resigned, Retired, Terminated) |
| 2 | Employee count per department |
| 3 | Average salary by department |
| 4 | Distribution of work modes (On-site vs Remote) |
| 5 | Job title with the highest average salary |
| 6 | Average salary by department and job title |
| 7 | Resigned & terminated employees per department |
| 8 | Salary variation with years of experience |
| 9 | Average performance rating by department |
| 10| Country with highest employee concentration |

---

## Key Findings

### Attrition Rate by Department
| Department   | Total Employees | Resigned | Attrition Rate (%) |
|--------------|------------------|----------|---------------------|
| **Finance**      | 199,873          | 40,238   | **20.13%** |
| R&D              | 99,759           | 19,919   | 19.97% |
| HR               | 159,119          | 31,736   | 19.94% |
| IT               | 601,042          | 119,852  | 19.94% |
| Sales            | 400,031          | 79,725   | 19.93% |
| Marketing        | 240,081          | 47,793   | 19.91% |
| Operations       | 300,095          | 59,397   | 19.79% |

> **Finance** has the **highest attrition rate** at **~20.13%**

---

## Tools & Libraries
```python
pandas, matplotlib, seaborn
```

### Insights Gained

- **Finance department faces the highest attrition risk (~20.13%)**  
- **IT has the largest workforce (601K+ employees)**  
- **Attrition is consistently high (~19.8–20.1%) across all departments**  
- **Salary and experience strongly correlate** *(to be visualized)*  
- **Remote work adoption varies by role and region**
