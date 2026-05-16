# 🧪 JMeter Performance Testing Lab (SE313)

This repository contains a performance testing project developed using **Apache JMeter (v5.6.3)** for the course Software Quality Assurance and Testing (SE313).

---


## 🎯 Objective
To design and execute a structured performance test using JMeter, demonstrating:

- Thread Groups
- HTTP Samplers
- Assertions
- Loop Controller
- Timers
- Listeners

---

## 🧪 Tools Used
- Apache JMeter 5.6.3  
- Java JDK  
- Git & GitHub  

---

## 📂 Project Structure

- **jmx/** → Contains JMeter test plan file  
- **report/** → Final lab report (PDF)  
- **screenshots/** → Execution proof screenshots  
- **results/** → CSV output reports  

---

## ⚙️ Test Plan Overview

This project includes **4 Thread Groups**:

### 🔹 Thread Group 1 – Basic Requests
- Simple HTTP request execution
- Uses listeners for result analysis

### 🔹 Thread Group 2 – Assertions
- Response Assertion
- Duration Assertion
- Size Assertion (intentional failure included)

### 🔹 Thread Group 3 – Loop Controller
- Repeated execution of HTTP requests

### 🔹 Thread Group 4 – Timers
- Constant Timer applied to control request delay

---

## 📊 Observations
- System responses were stable under light load
- Assertion failures were captured successfully
- Timers introduced controlled request delays

---

## ▶️ How to Run

1. Open Apache JMeter  
2. Load `.jmx` file from `/jmx` folder  
3. Click Start ▶  
4. View results using listeners  

---

## 📌 Notes
- All element names follow ID-based naming convention  
- Screenshots are included for validation  
- Report contains full explanation and analysis  

---
## Author
<h1 align="center" style="color:#4DA6FF;">
  Oynndrila Singh Purkayestha
</h1>

<h3 align="center">BSc in Software Engineering</h3>
<h3 align="center">Daffodil International University (DIU)</h3>

## 📜 Conclusion
This lab demonstrates basic performance testing concepts using JMeter and helps understand system behavior under different load conditions.

---
