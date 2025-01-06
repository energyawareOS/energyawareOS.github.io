# Energy Aware Operating System Based On Diaggregated System

## Introduction

<p align="center"><img src="EAOS_logo.png" width="128"></p>

This project aims to develop a novel energy-aware operating system based on a disaggregated system.
By implementing energy-aware scheduling algorithms, optimizing kernel synchronization, and leveraging lightweight kernel techniques, we aim to significantly reduce energy consumption in data centers.
Additionally, we explore energy-efficient storage management techniques, including data placement optimization and remote storage access.

## Objectives
- Develop an energy-aware scheduling algorithm for micro-partitions.
- Optimize kernel synchronization for energy efficiency.
- Implement a lightweight kernel for reduced overhead.
- Control the energy consumption of storage devices.
- Minimize data movement within storage systems.
- Develop an energy-efficient remote storage access mechanism.
- Utilize DPUs for low-power cryptographic offloading.

## Core Technologies

- Energy-Aware Micro-Partition Scheduling: Develop a scheduling algorithm that efficiently allocates resources to micro-partitions based on their workload and energy consumption characteristics.
- Energy-Efficient Kernel Synchronization: Optimize kernel synchronization primitives to reduce energy consumption and improve performance.
- Lightweight Kernel: Implement a lightweight kernel that provides essential operating system services with minimal overhead.
- Storage Energy Management: Develop techniques to control the energy consumption of storage devices, including power management and data placement optimization.
- Data Movement Minimization: Minimize data movement within storage systems through techniques such as data compression and deduplication.
- Energy-Efficient Remote Storage Access: Develop a remote storage access mechanism that minimizes network traffic and energy consumption.
- DPU-Based Cryptographic Offloading: Utilize DPUs to offload cryptographic operations, reducing the energy consumption of the main CPU.

## Expected Outcomes

- Reduced Energy Consumption: Significantly reduce the energy consumption of data centers by optimizing resource allocation and minimizing idle time.
- Improved Performance: Enhance system performance through optimized scheduling and reduced overhead.
- Enhanced Reliability: Improve system reliability through the use of isolated architectures and fault-tolerant mechanisms.
- Increased Flexibility: Provide a flexible platform for developing energy-efficient applications.