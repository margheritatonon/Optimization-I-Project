# Optimization-I-Project

### Project Overview

In healthcare, nurse scheduling is essential for operational efficiency, requiring the balance of the need for constant patient care with nurse availability and preferences [1]. 
We employed a linear programming (LP) approach [2] to maximize nurse preferences, subject to 6 constraints:
1. each nurse can work a maximum of 5 shifts per week
2. daily demand has to be met
3. nurses are not allowed to work more than 3 consecutive days
4. nurses cannot work the whole weekend
5. nurses cannot work more than 1 shift per day
6. nurses can work only if they are available

### References
* [1] Jaumard, Brigitte, et al. “A Generalized Linear Programming Model for Nurse Scheduling.” European Journal of Operational Research, vol. 107, no. 1, 13 Jan. 2011, pp. 1–18.

* [2] Bertsimas, Dimitris, and John Tsitsiklis. Introduction to Linear Optimization. 1st ed., Athena Scientific, 1997.

* [3] “HiGHS — Pyomo 6.6.2 Documentation.” Readthedocs.io, 2023, pyomo.readthedocs.io/en/6.6.2/library\_reference/appsi/appsi.solvers.highs.html. Accessed 26 Nov. 2024.

* [4] Waskom, Michael. “Seaborn.Heatmap.” Seaborn, seaborn.pydata.org/generated/seaborn.heatmap.html. Accessed 04 Oct. 2024. 
