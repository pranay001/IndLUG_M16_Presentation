
![ChatGPT Image Jun 19, 2025, 11_00_07 PM](https://github.com/user-attachments/assets/6bbf3878-f3ed-4d5e-beed-7334e33e2397)


# **Fluid Management System - User Manual & Technical Documentation**

## **1. Application Overview**

This system is designed for industrial or laboratory-scale fluid management and distribution. It comprises three centrifugal pumps, a pressurized storage tank, pressure and flow sensors, and a graphical interface for real-time monitoring. The system ensures continuous fluid movement while maintaining desired pressure and flow rate levels.

---

## **2. System Components**

### **2.1. Pumps**

* **Type:** Horizontal Centrifugal Pumps
* **Number of Units:** 3
* **Operational Status:** All pumps shown are **ON** by default.
* **Color Coding:** Pumps are color-coded blue, with one indicating a warning via a red overlay (bottom pump in image).

#### **Pump Specifications:**

* **Rated Flow Rate:** 100 liters/minute per pump
* **Maximum Operating Pressure:** 10 bar
* **Motor Power:** 2 kW
* **Voltage:** 380V AC, 3-phase
* **Duty Cycle:** Continuous
* **Mounting Type:** Base plate mounted
* **Protection:** IP55

---

### **2.2. Storage Tank**

* **Material:** Stainless Steel 316
* **Type:** Vertical, Pressurized Tank
* **Capacity:** 500 liters
* **Pressure Rating:** 10 bar
* **Level Indicator:** Graduated markings visible in the interface
* **Safety Feature:** Pressure relief valve and bottom drain valve

---

### **2.3. Sensors**

#### **Pressure Sensor:**

* **Type:** Analog dial with electrical output (4-20mA)
* **Range:** 0 - 10 bar
* **Accuracy:** ±0.5% FS
* **Installation:** Inline, pre-tank
* **Interface Output:** Real-time graph and analog dial

#### **Flow Rate Sensor:**

* **Type:** Turbine flow sensor with electrical output (0-5V)
* **Range:** 0 - 300 liters/minute (combined for all pumps)
* **Accuracy:** ±1.0% FS
* **Interface Output:** Real-time graph and analog dial

---

## **3. Graphical User Interface (GUI)**

The GUI includes:

* **Real-Time Pressure Chart** showing system pressure fluctuations.
* **Real-Time Flow Rate Chart** for monitoring delivery rates.
* **Analog Gauges** for visual inspection of both flow and pressure.
* **Pump Status Indicators:** ON/OFF lights (green = ON).
* **Anomaly Indicator:** Red highlight on any pump with detected issues.

---

## **4. System Operation Guidelines**

### **4.1. Startup Procedure:**

1. Ensure all valves are closed before initiating the system.
2. Turn ON pumps sequentially via control panel or remote interface.
3. Confirm that the tank level is within safe operational range.
4. Observe pressure and flow readings stabilize within the normal range.
5. Monitor system visually and via the interface for anomalies.

### **4.2. Shutdown Procedure:**

1. Gradually turn OFF pumps starting from the last engaged.
2. Close all discharge valves.
3. Drain the system if long-term shutdown is expected.
4. Power down the interface and control systems.

---

## **5. Normal Operating Ranges**

| Parameter  | Normal Range            | Notes                                  |
| ---------- | ----------------------- | -------------------------------------- |
| Pressure   | 3 - 8 bar               | Fluctuations within ±1 bar acceptable  |
| Flow Rate  | 100 - 280 L/min (total) | Depends on pump load and demand        |
| Tank Level | 10% - 90% of full scale | Maintain above 20% to avoid cavitation |

---

## **6. Emergency Handling Procedures**

### **6.1. Overpressure Alarm**

* **Symptom:** Pressure > 9.5 bar
* **Action:**

  * Immediately shut down all pumps.
  * Open manual pressure relief valve.
  * Check for blockage in output lines.

### **6.2. Flow Rate Drop**

* **Symptom:** Flow rate < 50 L/min
* **Action:**

  * Check pump status.
  * Inspect suction line for blockage or airlocks.
  * Confirm tank level is adequate.

### **6.3. Pump Failure (Indicated by RED Highlight)**

* **Symptom:** Motor overheating, abnormal noise, or red warning light
* **Action:**

  * Shut down affected pump.
  * Inspect motor and coupling alignment.
  * Replace fuse or motor if required.
  * Notify maintenance personnel.

### **6.4. Sensor Malfunction**

* **Symptom:** Erratic or frozen gauge readings
* **Action:**

  * Cross-check with secondary gauges if available.
  * Replace or recalibrate the sensor.
  * Do not rely on the GUI until confirmation.

---

## **7. Maintenance Schedule**

| Task                        | Frequency   |
| --------------------------- | ----------- |
| Pump lubrication            | Monthly     |
| Pressure sensor calibration | Quarterly   |
| Flow sensor cleaning        | Monthly     |
| Tank inspection             | Bi-annually |
| Electrical panel check      | Monthly     |

---

## **8. Troubleshooting Guide**

| Issue                       | Possible Cause                 | Recommended Action               |
| --------------------------- | ------------------------------ | -------------------------------- |
| No Flow Reading             | Flow sensor fault / air lock   | Bleed lines / replace sensor     |
| High Pressure with Low Flow | Blocked outlet or valve closed | Inspect downstream lines         |
| One Pump Not Running        | Motor fault / electrical issue | Check circuit breaker            |
| Tank Not Filling            | Suction issue / inlet blockage | Check suction valves and filters |

---

## **9. Safety Guidelines**

* Always wear PPE while operating or maintaining the system.
* Never bypass safety interlocks or pressure relief mechanisms.
* Keep electrical panels dry and secured.
* Ensure grounding of motor units.
* Keep emergency shutdown procedures visible to all operators.

---

## **10. Contact and Support**

**Manufacturer:**
THE IMAGINARY PUMP COMPANY
**Support Email:** [imaginarypumpcompany@imaginaryemail.com](mailto:imaginarypumpcompany@imaginaryemail.com)
**Phone:** +1-800-FLUID-HELP
**Documentation Version:** 1.0
**Release Date:** June 2025
