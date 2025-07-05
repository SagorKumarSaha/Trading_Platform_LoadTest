# Trading Platform Load Test Using Jmeter

I have done Load Testing on the Tradiumpro website spot trading which is a part of Performance Testing. Using this load test, I have measured that at a time how many users submitted orders can be handled by the server before server crash.

### In this Test

## Settings that I have applied for load testing-->

1. Number of Threads: 1000 threads will run concurrently.
2. Ramp-up Period: The 1000 threads will start over a period of 1 seconds. This means that JMeter will start 1000 threads per second (1000 threads / 1 seconds).
3. Loop Count: Each thread will execute the test scenario 1 times.
