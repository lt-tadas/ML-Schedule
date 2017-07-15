Operating Systems tend to have a rigid, straightforward algorithm when it comes to deciding which process should be next in line for execution. The system is effective, but it can be done better. A good scheduler is one that minimizes the amount of empty processing ticks in the CPU, and maximize the amount of throughput. 

Schedulers have no memory, in the sense that what they see in their wait queues and RB trees is what they get, but that leaves a lot of wasted information that the scheduler could consider. Hence, machine learning applied to scheduling is the natural conclusion. 
