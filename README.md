# The-Total-Weighted-Tardiness-Scheduling
This is the AMPL code for total weighted tardiness scheduling, we can simplify it as 1 || \sum w_j T_j where T_j stands for max(0, c_j-d_j),c_j means complete time for job j, d_j means deadline for job j.
Several ways can be done to solve this problem in AMPL, this is the code for Branch and Bound method. We start from the end and assign one job to be completed, then we use AMPL to get the lower bound and do it again and again until we can find optimal solution.
