## Chapter 4 Problems 4-6 ##

### Problem 4 ###
Is it possible for a graph with 10 vertices and edges to be a connected planar graph? Explain.

It is possible for a graph with 10 vertices and edges to be a connected planar graph, while I wont be using a specific graph, I will explain why this would work.
Since the Euler's forumula for planar graph is v - e + f = 2, we can subsitute the values 10 for both the vertices and edges as given, we get the equation 10- 10 + F = 2
from this, solving this we get F = 2. This proves how a connected planar graph with 10 vertices and 10 edges must have 2 faces.

### Problem 5 ###
Is there a connected planar graph with an odd number of faces where every vertex has degree 6.

It is not possible for this to occur, we start proving this by determining a relation between the degrees and edges, applying the handshake lemma this will get us 6V = 2E
According to the handshake lemma, this total degree is also equal to twice the number of edges 
From this we conclude that E = 6V/2 which equals E = 3V. Subsitutuing this value in into Euler's formula gives us V - (3V) + F = 2 resulting in -2V + F = 2.
Considering that F is odd, we can now make the question -2V + (Odd Number) = (Even Number) 2, this shows how this is not possible as a odd number minus an even (twice the number of vertices)
number cannot result in another even number. 

### Problem 6 ###
I'm thinking of a polyhedron containing 12 faces. Seven are triangles and four are quadralaterals. The polyhedron has 11 vertices including those around the mystery face. 
How many sides does the last face have?

(Refrencing Jeff's example) First we find the total number of edges, whuch would be (7 x 3 + 4 x 4 + n)/2 = (37 + n)/2. Knowing that the last face must have a odd number of edges. 
v = 11 is given, so applying Eulers forumla would result in the equation 11 - (37 + n)/2 + 12 = 2 which results in n = 5, meaning the last face is a pentagon. 

### Adonis's Repo ###
https://github.com/Donworks/csc208/blob/main/Questions%207%2C%208%2C%209.md
