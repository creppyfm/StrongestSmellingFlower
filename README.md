# StrongestSmellingFlower

Problem Statement: 

Imagine you have a 2D garden with some flowers and some empty spots. Each flower has some int fragrance and some int rate of drop off of fragrance. 
So for example, a rose at location (1,1) might have a fragrance of 5, with a drop off of 1. That would mean you can smell the rose with strength 5 at (1,1), strength 4 at (2,1), strength 3 at (3,1), and so on. 

The drop off only applies vertically and horizontally, not diagonally, so at (0,0) it’s strength 3. 

Part 1 (simpler, no BFS): find the strongest smelling flower at a given point 

Part 2 (harder, uses BFS): Same question, but now there are rocks in the garden which fragrance can’t travel through.
