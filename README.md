# Trading Platform Load Test Using JMeter

I have done Load Testing on the Tradiumpro website spot trading, which is a part of Performance Testing. Using this load test, I have measured that at a time how many users submitted orders can be handled by the server before the server crashes.

### In this load test, I have fetched the accessToken and deviceToken after every user login and used a CSV file to submit spot buy and sell orders, and also user login.

## Settings that I have applied for load testing-->

1. Number of Threads: 1000 threads will run concurrently.
2. Ramp-up Period: The 1000 threads will start within 1 second. This means that JMeter will start 1000 threads per second (1000 threads / 1 second).
3. Loop Count: Each thread will execute the test scenario 1 time.
