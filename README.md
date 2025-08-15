# netdata-dashboard

# Task 7: Monitor System Resources Using Netdata

This repository contains the submission for **Task 7** of the **Elevate Labs Internship**.  
The objective of this task was to install **Netdata** using **Docker** and visualize real-time system and application performance metrics.

---

## 📝 Objective
The primary goal was to gain hands-on experience with a lightweight, real-time monitoring tool to understand how to track the health and performance of servers, systems, and applications.

---

## 🛠️ Tools Used
- **Netdata** – Open-source tool for real-time performance and health monitoring.
- **Docker** – Platform to build, ship, and run distributed applications in containers.

---

## 🚀 Steps Completed

1. **Pulled the Netdata Docker Image**  
   The official `netdata/netdata` image was pulled from Docker Hub.

2. **Ran the Netdata Container**  
   Started a new container in detached mode with the following command:  
   ```bash
   docker run -d --name netdata -p 19999:19999 netdata/netdata

![Netdata Dashboard](netdata_dashboard.png)

