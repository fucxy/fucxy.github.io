#Chapter 1 

##Most programming problems can indeed be split into two parts:

+ What capabitilies are to be provided ?(the mechanism)
+ How those capabilities can be used ?(the policy)

Being policy-free is actually a common target for software designers

##The linux kernel can split into those pieces:

+ Process management
+ Memory management
+ Filessystem
+ Device control
+ Networking

##Loadable Modules

This is a good feature of linux. It gives the ability to extent fuction at runtime. 

Although we can build huge modules implementing different drivers in a single chunk of code.

Good programmers, nonetheless, usually create a different module for each new functionality they
implement, because decomposition is a key element of scalability and extendability.

The Linux way of looking at devices distinguishes between three fundamental device type. 

+ Chariactor module -- The device is the one can be accessed as a stream of bytes(as a file). Such a driver usually implements at least the open, close, read, and write system calls.
+ Block module -- 
+ network interfaces

