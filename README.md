Download Link: https://assignmentchef.com/product/solved-int301-lab-14-associative-memory
<br>
<span class="kksr-muted">Rate this product</span>

Associative Memory

A Hopfield network can be created in Matlab by using the Matlab Neural Network Toolbox function newhop. The network functioning is simulated using the function sim. There are two variants of calling the function sim:

result= sim(net,M,[],test) result= sim(net,{M,iterations},{},test)

where M is the number of test data, and the user cannot control the number of iterations in the first variant while in the second case the user can.

The demo file implements a Hopfield network which stores the binary format of the following four image patterns (which can be loaded from 4patterns.mat):

Exercise 1: Read and understand the demo file, and execute the program to understand the pattern recovery process of Hopfield network.

Exercise 2: Check the network recall ability for perturbed/distorted versions of the stored patterns (e.g., by adding some random noise).