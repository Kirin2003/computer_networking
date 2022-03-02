Problem 2

At time $N*(L/R)$ the first packet has reached the destination, the second packet is stored in the last router, the third packet is stored in the next-to-last router, etc. At time $N*(L/R) + L/R$, the second packet has reached the destination, the third packet is stored in the last router,  etc.  Continuing  with  this  logic,  we  see  that  at  time  $N*(L/R)  +  (P-1)*(L/R)  = (N+P-1)*(L/R)$ all packets have reached the destination.  

Problem 3   

a)  A  circuit-switched  network  would  be  well  suited  to  the  application,  because  the application  involves  long  sessions  with  predictable  smooth  bandwidth  requirements. Since  the  transmission  rate  is  known  and  not  bursty,  bandwidth  can  be  reserved  for each application session without significant waste. In addition, the overhead costs of setting up and tearing down connections are amortized over the lengthy duration of a typical application session.  
b)  In  the  worst  case,  all  the  applications  simultaneously  transmit  over  one  or  more network links. However, since each link has sufficient bandwidth to handle the sum of  all  of  the  applications'  data  rates,  no  congestion  (very little  queuing)  will  occur. Given  such  generous  link  capacities,  the  network  does  not  need  congestion  control mechanisms.

Problem 4  

a) Between the switch in the upper left and the switch in the upper right we can have 4 connections.  Similarly  we  can  have  four  connections  between  each  of  the  3  other pairs of adjacent switches. Thus, this network can support up to 16 connections.   

b) We can 4 connections passing through the switch in the upper-right-hand corner and another  4  connections  passing  through  the  switch  in  the  lower-left-hand  corner, giving a total of 8 connections. 

c) Yes. For the connections between A and C, we route two connections through B and two  connections  through  D.  For  the  connections  between  B  and  D,  we  route  two connections through A and two connections through C.  In this manner, there are at most 4 connections passing through any link. 