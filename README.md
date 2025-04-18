 🖥️ Task 7: Monitor System Resources Using Netdata

## 🎯 Objective
Install **Netdata** using Docker and visualize real-time system and application performance metrics such as CPU, memory, disk, and running containers.

---

## 🛠️ Tools Used
- **Netdata** (Open-source performance monitoring tool)
- **Docker**

---

## 🚀 Steps to Complete the Task

### ✅ Step 1: Pull the Netdata Docker Image
Run the following command to pull the latest Netdata image from Docker Hub:
```bash
docker pull netdata/netdata
✅ Step 2: Run Netdata Container
Start the container using the following command:

bash
Copy
Edit
docker run -d --name=netdata -p 19999:19999 netdata/netdata
-d: Run container in detached mode

--name=netdata: Name the container "netdata"

-p 19999:19999: Expose port 19999 on localhost

✅ Step 3: Access Netdata Dashboard
Open your browser and go to:

arduino
Copy
Edit
http://localhost:19999
This will open the Netdata dashboard where you can monitor real-time system performance.

✅ Step 4: Explore the Dashboard
Monitor key performance indicators such as:

CPU Usage

Memory Usage

Disk I/O

Network Traffic

Docker Container Stats

✅ Step 5: Explore Logs (Optional)
If required, view logs by navigating to:

bash
Copy
Edit
/var/log/netdata
📸 Deliverables
📷 Screenshot of Netdata Dashboard

📷 Screenshot of System Metrics

📚 Outcome
By completing this task, you will:

Understand lightweight monitoring using Docker

Gain insight into system performance metrics

Learn how to visualize and diagnose system health in real-time

📁 Folder Structure (Example)
Copy
Edit
📦netdata-monitoring
 ┣ 📄README.md
 ┗ 📁screenshots/
   ┣ 📷dashboard.png
   ┗ 📷metrics.png



