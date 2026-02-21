# 🏥 Edge Computing in Healthcare — Cloud-Fog Based Architecture

## 📌 Project Overview

This project presents a **Cloud–Fog based architecture for IoT healthcare applications** designed to reduce latency and improve real-time performance when processing critical patient data. Traditional cloud-only systems often experience high latency and energy inefficiency, which can be dangerous in healthcare environments where quick decision-making is essential.

The proposed system uses **Edge (Fog) computing** to process time-sensitive healthcare tasks closer to IoT devices such as ICU monitors and wearable sensors. A Fog Broker manages task scheduling and resource allocation using optimization techniques to ensure efficient processing.

The system demonstrates how edge computing improves healthcare monitoring by reducing response time and improving system performance.

---

## 🎯 Project Objective

* To reduce latency in healthcare data processing.
* To improve real-time decision making in critical medical systems.
* To implement a Cloud–Fog hybrid architecture.
* To optimize task scheduling and resource allocation.
* To enhance performance and energy efficiency in IoT healthcare systems.

---

## 🏗 System Architecture

### ☁️ Cloud Layer

* Handles large-scale data processing.
* Stores healthcare data.
* Performs non-time-critical operations.

### 🌐 Fog Layer (Edge Computing)

* Processes time-sensitive healthcare tasks locally.
* Reduces communication delay.
* Improves system responsiveness.

### 📡 IoT Device Layer

* ICU monitors and wearable devices.
* Generates patient data.
* Sends tasks for processing.

---

## ⚙️ Optimization Techniques Used

### 📊 Weighted Sum Method (WSM)

* Prioritizes healthcare tasks.
* Assigns weights to different performance factors.
* Helps in decision-making for task scheduling.

### ⚡ Modified Best Available Resource (MBAR)

* Efficient resource allocation algorithm.
* Assigns tasks to best available computing resources.
* Improves processing efficiency.

---

## ⭐ Features

### ⏱ Low Latency Processing

* Processes emergency healthcare data locally.
* Faster response time for critical situations.

### ⚡ Efficient Resource Management

* Optimized task allocation using MBAR.
* Improved system performance.

### 📊 Task Prioritization

* Uses WSM to manage healthcare task importance.

### 📉 Performance Optimization

* Reduces energy consumption.
* Improves real-time monitoring.

### 📡 IoT Healthcare Simulation

* Simulates healthcare devices and task processing.

### 📈 Performance Metrics Collection

* Measures system efficiency.
* Evaluates latency improvements.

---

## ⚙️ Tech Stack

* Java Programming
* Edge Computing Architecture
* Fog Computing Model
* IoT Device Simulation
* CSV-based Task Input
* Performance Metrics Collection

---

## 📂 Project Structure

* `Main.java` — Main execution program
* `FogDeviceCreator.java` — Creates fog computing resources
* `IoTDeviceCreator.java` — Simulates IoT devices
* `MetricsCollector.java` — Collects performance data
* `Task.java` — Task definition and handling
* `MBAR.java` — Resource allocation algorithm
* `wsm.java` — Weighted Sum Method implementation
* `tasks.csv` — Input tasks dataset

---

## ▶️ How to Run the Project

1. Install Java (JDK).
2. Open terminal in project folder.
3. Compile all files:

   ```
   javac *.java
   ```
4. Run the program:

   ```
   java Main
   ```

---

## 📊 Results

* Reduced latency compared to cloud-only systems.
* Improved real-time performance.
* Better resource utilization.
* Efficient task scheduling.

---

## 🌍 Applications

* Smart healthcare monitoring systems.
* ICU patient monitoring.
* Wearable health devices.
* Real-time medical alert systems.
* IoT-based healthcare infrastructure.

---

## 🎓 Academic Relevance

This project covers concepts from:

* Edge Computing
* Fog Computing
* Cloud Computing
* Internet of Things (IoT)
* Resource Allocation Algorithms
* Performance Optimization

---

## 🚀 Future Improvements

* Real-time hardware device integration.
* Cloud dashboard for monitoring.
* Machine learning-based prediction.
* Large-scale healthcare data analysis.

---

## 👨‍💻 Author

**Hemanth Gudi**
