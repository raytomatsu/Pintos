# Pintos
This is a Pintos Project for Operating System. 

What we did: 

1. “Reimplement timer_sleep(), defined in "devices/timer.c". Although a working implementation is provided, it "busy waits," that is, it spins in a loop checking the current time and calling thread_yield() until enough time has gone by. Reimplement it to avoid busy waiting.
2. Implement Priority Scheduling with Donation.  No need to implement MLFQs.
