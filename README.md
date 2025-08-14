## Project Drone

## **Overview**

This project involves the development of a high-performance quadcopter drone specifically designed for **D3 Mapping** applications.
The drone will be versatile enough to serve **defense**, **construction**, and **3D modeling/design** industries, providing accurate and reliable aerial data collection.

Our system will integrate powerful hardware components, advanced flight control, and high-resolution mapping capabilities to deliver precision aerial surveys and 3D reconstructions.

---

## **Key Features**

* **Multi-Industry Applications**

  * **Defense**: Reconnaissance, terrain mapping, and surveillance.
  * **Construction**: Site surveying, project monitoring, and volumetric calculations.
  * **3D Modeling & Design**: High-resolution photogrammetry for detailed 3D models.

* **High-Performance Flight Control**
  Powered by the FLASH HOBBY F405 Flight Controller with a 60A 4-in-1 ESC for precise and stable maneuverability.

* **Long-Range & High-Speed Capability**
  Equipped with robust brushless motors and high-discharge LiPo batteries for extended flight time and responsive control.

---

## **Hardware Components**

| Component                                                                        | Description                                                                                         |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **CNHL 1500mAh 130C 4S LiPo Battery (2 Packs)**                                  | High-discharge batteries with XT60 plugs for reliable power delivery.                               |
| **Raspberry Pi 5 (8GB)**                                                         | Onboard computer for processing mapping data, AI-based analysis, and telemetry.                     |
| **TUOFENG 30 AWG Silicone Wire (6 Colors)**                                      | Flexible, high-temperature wiring for internal connections and modifications.                       |
| **oldboytech 4K Micro HDMI to HDMI Cable (6FT)**                                 | Connects Raspberry Pi to external displays or recording equipment for configuration and monitoring. |
| **Teansic 495Pcs JST SH 1.0mm Connector Kit**                                    | Connectors for internal component integration (motors, sensors, and controllers).                   |
| **GoolRC Flysky FS-i6X 2.4GHz 10CH AFHDS 2A RC Transmitter + FS-iA10B Receiver** | Long-range, low-latency control system for the drone.                                               |
| **iFlight XING-E Pro 2207 2750KV Brushless Motors (4 pcs)**                      | High-efficiency motors for stable lift and agile performance.                                       |
| **eSUN Carbon Fiber Filled Nylon Filament (1.75mm, 1KG)**                        | Used for 3D printing drone frame parts, providing strength and lightweight durability.              |
| **FLASH HOBBY F405 Flight Controller Stack + 60A 4-in-1 ESC**                    | Central flight control and power distribution system, compatible with 3–6S LiPo batteries.          |

---

## **Planned Software Stack**

* **Flight Controller Firmware:** Betaflight / ArduPilot
* **Mapping Software:** OpenDroneMap / Pix4D / DroneDeploy API integration
* **Onboard Processing:** Python-based mapping scripts, ROS for robotics control
* **Communication:** MAVLink protocol for telemetry and control
* **3D Modeling:** Blender / Meshroom for post-processing

---

## **Assembly Steps (High-Level)**

1. **Frame & Motor Installation**

   * Mount carbon fiber frame components.
   * Install iFlight XING-E Pro motors with secure wiring.

2. **Flight Controller & ESC Setup**

   * Install FLASH HOBBY F405 flight stack.
   * Connect ESCs to motors and power distribution system.

3. **Power System Integration**

   * Connect CNHL LiPo battery with XT60 to power system.
   * Install JST connectors for modular connections.

4. **Onboard Computer Setup**

   * Mount Raspberry Pi 5 for mapping and AI tasks.
   * Connect to flight controller via UART for data exchange.

5. **RC & Telemetry Configuration**

   * Bind Flysky FS-i6X transmitter to FS-iA10B receiver.
   * Test signal strength and response time.

6. **3D Printed Parts**

   * Print additional mounts, camera holders, and protective housings using eSUN carbon fiber filament.

7. **Software & Calibration**

   * Flash Betaflight/ArduPilot firmware.
   * Calibrate ESCs, motors, and sensors.
   * Install and configure mapping software.

---

## **Use Cases**

* **Defense:** Terrain scouting, mapping enemy positions, rapid deployment surveillance.
* **Construction:** Real-time site progress monitoring, earthworks volume calculation.
* **3D Modeling & Design:** Capture aerial imagery for accurate architectural models.

---

## **Future Enhancements**

* Integration with LiDAR sensors for enhanced topographical mapping.
* AI-based obstacle avoidance and autonomous flight paths.
* Extended-range transmission system for beyond-visual-line-of-sight (BVLOS) operations.

---

## **Safety & Compliance**

* Always comply with **local drone laws** and **airspace regulations**.
* Maintain visual line of sight unless operating with BVLOS permissions.
* Ensure all batteries and wiring are properly secured to prevent mid-air failures.

