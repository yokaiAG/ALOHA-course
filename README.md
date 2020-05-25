# ALOHA-course
This is the code related to the lab exercise in Python about MAC competitive protocols (ALOHA, CSMA).
The code contains two simulation exercises to familiarize students with the ALOHA protocol.

Exercise 1: ALOHA synchronous
The students are requested to simulate the random access protocol ALOHA, where N users want to access the same channel.
We vary the probability of access p and the number of present users N to evaluate channel throughput.

Exercise 2: ALOHA adaptive
The students now need to modify the code, taking into account a protocol which adapts the back-off probability p every time
a collision occurs. The access probability per user is divided by 2 every time the user experiences a collision of her 
transmitted packet. Once the packet is successfully accepted the user access probability returns to p0. We evaluate the 
protocol for different number of users N and different value of initial access probability p0. We compare the behaviour of 
the adaptive ALOHA with the behaviour of the synchronous ALOHA. 

The duration of the lab should be 3 1/2 hours.

Enjoy!
