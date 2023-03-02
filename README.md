# Bounded-buffer Solutions Story
This coding story tells how to solve the classic concurrency problem named Bounded Buffer.

The story goes from a first approach without any solution managed as a typical sequential program to a first solution using low-level concurrent primitives where the problem is solved. We are moving to the next solution by using Semaphores, a higher primitive that manages a concurrent counter, and finally, we show a solution by using locks and conditions variables. 
