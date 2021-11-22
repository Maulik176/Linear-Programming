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

[1] Richards, K. (2020, April 6). What is cryptography? - definition from whatis.com.      SearchSecurity. Retrieved September 27, 2021, from [What is Cryptography? Definition from  SearchSecurity](https://searchsecurity.techtarget.com/definition/cryptography#:~:text=Cryptography%20is%20a%20method%20of,%22%20stands%20for%20%22writing.%22). 

[2] Sidhpurwala, H. (2019, March 19). A brief history of cryptography. Red Hat Customer Portal. Retrieved September 27, 2021, from [A Brief History of Cryptography](https://access.redhat.com/blogs/766093/posts/1976023).

[3] GeeksforGeeks. (2021, August 4). _Implementation of Affine Cipher_. [Implementation of Affine Cipher](https://www.geeksforgeeks.org/implementation-affine-cipher/)

[4] _Cryptography by means of linear algebra and number theory_. (n.d.). Retrieved October 20, 2021, from [http://irep.emu.edu.tr:8080/xmlui/bitstream/handle/11129/1420/ElfadelAjaeb.pdf?sequence=1](http://i-rep.emu.edu.tr:8080/xmlui/bitstream/handle/11129/1420/ElfadelAjaeb.pdf?sequence=1)

