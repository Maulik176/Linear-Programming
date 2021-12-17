# Linear-Programming
# Title and Group Details
- Minimizing the distance between relay points and clients in a city
- 13
- Panthers

# Team Members
- AU2040117 - Maulik Ranadive
- AU2040193 - Yash Chatoliya
- AU2040236 - Vrutik Bavarva	
- AU2040186 - Jainam Shah	

# Abstract
- Linear programming is the process of using mathematical models to solve linear problems in order to maximize or minimize an objective function while keeping certain restrictions in mind.Let’s suppose that we are a very famous e-commerce platform. We have to introduce a new relay point in a city for the shipment of products. Only information we have is the coordinates of all the clients of the company in the city. We need to minimize the distance between each relay point and each client in the city
# Results 
```python
from manhattan import solve
M = [(10, 20), (15, 45), (22, 19), (33, 42)]
p = 2
sol = solve(M, p)
```
sol will give [(14.0, 19.0), (21.0, 43.0)] as output

# References

- Lewis, H. (2015, June 8). _.Taxicab Geometry_. . Retrieved October 25,2021, from [Taxicab Geometry](https://www.mathscareers.org.uk/taxicab-geometry/). 

- Bilot, T. (2018). _.The power of linear programming, a real life case study_.. Retrieved October 25,2021, from [The power of linear programming, a real life case study](https://towardsdatascience.com/the-power-of-linear-programming-a-real-life-case-study-6198b2cdb611).

- Urdaneta, A. , lberto, R. (February, 1996). _Coordination of directional relay timing using linear programming_. Retrieved November 2, 2021, from [Coordination of directional relay timing using linear programming](https://www.researchgate.net/publication/3272928_Coordination_of_directional_relay_timing_using_linear_programming)

- Journal of Natural Gas Science and Engineering. (2012). Retrieved November 15, 2021, from [Refinery Linear Programming Modeling](https://www.sciencedirect.com/topics/earth-and-planetary-sciences/linear-programming)

- GeeksForGeeks. (2021, Jan 21). _.Maximum Manhattan distance between a distinct pair from N coordinates._ Retreived 25 November, 2021, from [Maximum Manhattan distance between a distinct pair from N coordinates](https://www.geeksforgeeks.org/maximum-manhattan-distance-between-a-distinct-pair-from-n-coordinates/) 


# Link to the youtube video 
https://youtu.be/8zLNSPQdP8c
