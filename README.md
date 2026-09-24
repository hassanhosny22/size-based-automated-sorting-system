#  Size-Based Automated Sorting System

##  Overview

A simulated automated sorting system designed to classify and sort products based on their dimensions.

The system uses digital sensors to identify different product sizes and controls pneumatic pushers to direct each product to its corresponding sorting path.

> **Note:** This project was developed and tested entirely using simulation software. No physical PLC was used.

##  Simulation Environment

* Siemens PLC Simulation
* SIMATIC Manager
* Factory I/O
* Ladder Logic (LAD)

##  Product Classification

The system identifies three different product types using sensor combinations:

| Product Type | Sensor Condition |
| ------------ | ---------------- |
| Small        | Sensor 1         |
| Large        | Sensors 1 + 2    |
| Long         | Sensors 1 + 3    |

##  System Operation

1. Products move along the main conveyor.
2. Digital sensors detect the product dimensions.
3. The PLC processes the sensor combination.
4. The product type is identified.
5. The corresponding pneumatic pusher is activated.
6. The product is directed to its designated sorting area.
7. Individual counters track each product type.
8. A total counter tracks the complete production batch.

##  Main Features

* Automatic product size detection
* Sensor-based classification
* Three product categories
* Automatic pneumatic sorting
* Individual product counters
* Total batch counter
* Automatic conveyor control
* PLC-based control logic
* Factory I/O simulation

##  Programming

The control system was programmed using **Ladder Logic (LAD)** in the Siemens PLC simulation environment.

The project demonstrates the integration of:

**Sensors → PLC → Pneumatic Pushers → Factory I/O**

##  Project Demonstration

A demonstration of the project is available on LinkedIn.

**LinkedIn Project Post:**
https://www.linkedin.com/posts/hassan-hosny-shawky-8bab47304_plc-industrialabrautomation-factoryio-activity-7501348963594301440-OYjl

##  Author

**Hassan Hosny Shawky**

Mechatronics Engineering Student
Industrial Automation & PLC Enthusiast
