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
