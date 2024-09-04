I defined my decision variables as the optimal number of tellers (x_i) required per shift per time 
slot(i).  I defined the problem.  For each shift I needed to determine the number of tellers 
needed with regard to the average customer demand taking into account that each teller can 
assist 8 customers per hour. Using pulp, I created my objective functions: by minimizing the 
total number of tellers:  Inputted the number of customers per hour for each shift I defined my 
constraints by ensuring that the service level  and average number of customers in each time 
window is met for each shift. I solved the problem with by implementing the model using pulp 
IX 
and solved for (x_i). The model calculated the total demand for each shift and divided it by the 
total capacity of one teller per shift. The result was the number of tellers needed per shift. 
I analyzed the results to check if the solution meets all constraints by providing customer 
service to 8 customers per hour (service level).# Shifts-Schedule
