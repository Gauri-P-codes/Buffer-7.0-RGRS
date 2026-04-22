
**AI-Inspired Dynamic Crowd & Service Flow Optimizer : AdaptiQ**

Traditional queue and crowd management systems operate using fixed rules and fail to adapt to real-time demand changes, leading to long waiting times and inefficient resource utilization. Our solution : AdaptiQ is an AI-inspired system that dynamically analyzes incoming service requests and optimizes queue flow and service allocation using adaptive scheduling and optimization algorithms, ensuring reduced congestion, balanced workload distribution, and improved service efficiency.

** Data structures used for respective features: ** 
Normal Queue : collections.deque
VIP Queue : heapq (min-heap)
Smart Assignment : Greedy (min queue scan)
Queue Rebalancing : Linear scan + deque ops
Global FCFS Serving : heapq (arrival time across counters)
Peak Detection : Sliding Window
Service Time Prediction : Weighted moving average
Emergency Injection : heapq push

** Video link: **
https://drive.google.com/file/d/1UK6cHl91weJ3E3YJuQoVn5ZrWBNO4R5D/view?usp=sharing
