# Smart-Drain-Monitoring-and-Blockage-Detection-System

 *An IoT-Based Integrated Solution for Flood Prevention and Worker Safety*

Project Description (Full System)

This project presents an "IoT-based Smart Drain Monitoring and Manhole Worker Safety System" designed to enhance urban drainage management and ensure the safety of sanitation workers.

The system combines "real-time drain condition monitoring" with "worker health and safety tracking", creating a complete smart municipal solution.

The drainage monitoring unit uses:

* **Ultrasonic sensor** to measure water level
* **Flow sensor** to monitor sewage movement
* **Gas sensors** to detect toxic gases such as CO and H₂S

These sensors are connected to an "ESP32 microcontroller", which continuously analyzes the drainage condition.

At the same time, a "wearable safety band" is provided to workers, equipped with:

* Temperature sensor
* Motion sensor
* Panic button

This band monitors the worker’s condition during operation.

System Working (Integrated Flow)

Step 1: Drain Monitoring

* System checks water level and flow rate
* Detects abnormal conditions in real time

 Step 2: Blockage Detection

```
IF water_level HIGH AND flow LOW → BLOCKAGE CONFIRMED
```

* Location sent to municipal dashboard

 Step 3: Gas & Safety Check

* Gas sensors detect toxic gases inside drain
* Safety level classified (Safe / Warning / Danger)

Step 4: Worker Entry Decision

```
IF gas_safe AND water_safe → ENTRY ALLOWED
ELSE → ENTRY BLOCKED
```

* Alerts shown via buzzer, LED, and dashboard

Step 5: Worker Monitoring

* Safety band tracks:

  * Body temperature
  * Movement

Step 6: Emergency Detection

* No movement / abnormal temperature / panic button
  → Emergency alert sent

Step 7: Municipal Response

* Authorities receive alert
* Immediate action taken

Innovative Features (Combined System)

1. Smart Blockage Confirmation Logic

* Uses **multi-sensor validation**
* Reduces false alerts

2. Drain Health Status System

* 🟢 Normal
* 🟡 Warning
* 🔴 Blocked

3. Worker Safety Entry Control

* Prevents unsafe entry based on gas and water level
* Adds real-life safety automation

4. Real-Time Worker Monitoring

* Tracks worker condition continuously
* Detects risk even without manual input

 5. Emergency Alert System

* Automatic alert during danger
* No need for worker to call manually

 6. Rain-Aware Intelligent Logic

IF rain_detected → avoid false blockage alert

 7. Maintenance Recommendation System

* “Inspection Required”
* “Immediate Cleaning Needed”


Key Strength of the Project

> This is not just a monitoring system — it is a complete intelligent decision-making and safety management system.

Advantages

✔ Prevents urban flooding
✔ Protects sanitation workers
✔ Reduces manual inspection
✔ Real-time monitoring
✔ Low-cost and scalable
✔ Smart decision-making

Applications

* Smart cities
* Municipal drainage systems
* Industrial sewage systems
* Disaster prevention systems

Conclusion

The proposed system integrates **drain monitoring and worker safety into a single intelligent platform**, enabling proactive maintenance, reducing risks, and improving urban infrastructure management.
