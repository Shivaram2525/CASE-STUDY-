# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

Case Study Questions – OpenStack Calculation in Cloud Computing

1. Resource Utilization:

Based on the current infrastructure, what is the total available compute capacity in terms of:
Total vCPUs
Total RAM
Total storage

2.Storage Allocation:

Given 10 TB of total block storage across the cloud, how many VMs can be supported if:
a) Each VM is allocated 100 GB block storage
b) Snapshot storage consumes 20% extra on average

**SOLUTIONS:**
```
Case Study: Cloud Performance and Efficiency Analysis
1. Introduction

In today’s world, almost every organization depends on cloud computing for storing and processing data. However, the performance and efficiency of cloud resources play a major role in deciding how effective the overall system is. Factors such as encryption speed, CPU usage, network performance, power consumption, and optimal server utilization all have a direct impact on cost and productivity.

This case study explores five different real-life scenarios related to cloud performance and efficiency. Each case focuses on a specific metric and demonstrates how to calculate and interpret it using simple formulas and reasoning.

2. Background

Cloud service providers and companies that rely on virtual machines or cloud storage often need to measure how efficiently their systems are performing. Encrypting large volumes of data, balancing CPU workloads, optimizing network throughput, and reducing energy consumption are everyday challenges in IT infrastructure.

By analyzing these metrics, organizations can reduce waste, improve speed, and ensure that resources are used optimally. This case study includes five such problems that together reflect a realistic view of cloud system efficiency.

3. Case Analysis and Results
Case 1: Encryption Time for Data Upload

Scenario:
A company uses AES-256 encryption to secure its files before uploading them to the cloud. The encryption speed is 0.05 seconds per MB, and the total file size is 2 TB.

Calculation:
1 TB = 1024 GB and 1 GB = 1024 MB
So,
2 TB = 2 × 1024 × 1024 = 2,097,152 MB
Time to encrypt = 2,097,152 × 0.05 = 104,857.6 seconds
Converting this into hours: 104,857.6 ÷ 3600 = 29.13 hours

Result:
It will take around 29 hours to encrypt 2 TB of data.
This shows that while encryption is essential for security, it also adds a significant time cost during large-scale data transfers.

Case 2: CPU Utilization Efficiency

Scenario:
A virtual machine is allocated 8 vCPUs but uses only 5.5 vCPUs on average.

Calculation:
Efficiency = (5.5 / 8) × 100 = 68.75%

Result:
The CPU utilization efficiency is 68.75%, which means almost one-third of the CPU capacity is not being used. This indicates that the VM could be resized to a smaller instance to save costs and improve resource allocation.

Case 3: Network Throughput Efficiency

Scenario:
A cloud server has a network bandwidth of 1 Gbps, but during peak hours, it achieves only 600 Mbps.

Calculation:
Throughput Efficiency = (600 / 1000) × 100 = 60%

Result:
The network throughput efficiency is 60%, showing that 40% of the available bandwidth remains unused. This could be due to congestion, inefficient data transfer protocols, or network bottlenecks that can be improved through optimization.

Case 4: Energy Efficiency Comparison

Scenario:
Two cloud setups perform the same workload under different power and time conditions:

Setup A: 500 W for 2 hours

Setup B: 300 W for 3.5 hours

Calculation:
Energy used = Power × Time

Setup A = 500 × 2 = 1,000 Wh (1.0 kWh)

Setup B = 300 × 3.5 = 1,050 Wh (1.05 kWh)

Result:
Setup A uses slightly less energy than Setup B, so Setup A is more energy-efficient. Even though Setup B uses less power, it operates longer, which results in higher total energy consumption.

Case 5: Maximum Number of Efficiently Hosted VMs

Scenario:
A physical server has 16 CPU cores, and each virtual machine requires 2 cores. To maintain performance, the CPU utilization should not exceed 75%.

Calculation:
Usable cores = 16 × 0.75 = 12 cores
Maximum number of VMs = 12 ÷ 2 = 6 VMs

Result:
The server can efficiently host 6 virtual machines while maintaining optimal CPU utilization at 75%. Hosting more could overload the CPU and degrade system performance.

4. Discussion

From all five cases, it’s clear that efficiency metrics play a major role in cloud system design and operation. Long encryption times can delay data uploads, underused CPUs increase costs, and poor network throughput affects user experience. Similarly, even small differences in power usage can make one setup more sustainable than another. Finally, limiting VM allocation based on CPU utilization helps maintain consistent system performance.

These findings highlight how simple calculations and monitoring can lead to smarter resource management and improved cost-effectiveness in real cloud environments.

5. Conclusion

Overall, maintaining balance between performance, cost, and energy efficiency ensures that cloud resources are used to their fullest potential. Continuous monitoring and optimization can help organizations achieve better performance and sustainability in their cloud operations.
```
