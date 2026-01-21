# Industrial Test Automation & Monitoring System (LabVIEW)

## Overview
This project implements an **industrial-grade test automation and monitoring system** developed during an internship, using **NI LabVIEW** as the core instrumentation platform.

The system reflects how **manufacturing test stations, validation rigs, and R&D monitoring setups** are built to ensure reliability, repeatability, and operator safety in industrial environments.

---

## Industrial Context
In production and R&D environments, manual testing and monitoring lead to:
- Inconsistent measurements
- Higher human error
- Poor traceability of test data
- Limited scalability

The objective was to develop a **structured, automated monitoring solution** capable of continuous operation with clear operator interaction.

---

## System Architecture
The application follows a **layered industrial automation architecture**:

### 1. Instrumentation Layer
- Sensors and signal sources
- DAQ / interfacing hardware

### 2. Acquisition & Control Layer
- Continuous data acquisition loops
- Deterministic execution flow
- Error-handling mechanisms

### 3. Application Layer
- Operator-facing HMI
- Data logging and reporting
- Status and fault indication

This mirrors **industry-standard LabVIEW-based test systems** used in electronics manufacturing and validation labs.

---

## Technology Stack
### Software
- **NI LabVIEW**
- DAQ Assistant & custom VIs
- Event-driven programming
- State-machine based control flow

### Hardware
- Analog / digital sensor modules
- Data acquisition interfaces
- PC-based control system

---

## Engineering Challenges Addressed
- **Stable real-time acquisition** over extended runtime
- **Noise handling and signal validation**
- **Fail-safe execution** using structured error handling
- **Modular VI design** for maintainability and expansion

---

## Features
- Real-time sensor monitoring
- Automated test execution
- Threshold-based fault detection
- Continuous data logging
- Operator-friendly control panels

---

## Performance Characteristics
- Deterministic acquisition loops
- Low-latency UI updates
- Reliable long-duration operation

*(Performance depends on DAQ configuration and system hardware)*

---

## Industry Relevance
This system aligns with:
- Manufacturing test automation
- Hardware validation & QA systems
- Industrial monitoring platforms
- R&D instrumentation setups

The same design principles apply to **embedded test rigs, PLC-based systems, and industrial IoT gateways**.

---

## How to Run
1. Install **NI LabVIEW**
2. Connect compatible DAQ and sensors
3. Open the main control VI
4. Configure acquisition parameters
5. Run the system for live monitoring

---

## Future Enhancements
- Integration with embedded controllers (ESP32 / PLC)
- Cloud-based test data storage
- Remote monitoring dashboards
- Advanced analytics and reporting

---

## Author
**Kamalesh V**  
Industrial Automation | Embedded Systems | Test Engineering
