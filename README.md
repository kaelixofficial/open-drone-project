# open-drone-project 🇺🇸 🛩️

A commercial open-source (COSS) prosumer drone platform. 100% US-sourced, NDAA-compliant, and built natively on open autopilot frameworks to restore user platform sovereignty.

## 📌 Market Context & Opportunity
Following the strict US import and FCC bans on DJI, a multi-billion-dollar vacuum has emerged in the domestic drone market. Legacy foreign systems present severe data privacy vulnerabilities, leading to widespread federal restrictions. 

`open-drone-project` solves this by delivering an un-compromised, completely sovereign hardware and software ecosystem built entirely within the United States.

## 🛠️ Project Core Pillars

*   **Sovereign Hardware:** 100% US-sourced components, supply chain, and assembly. Fully NDAA and FCC compliant out of the box.
*   **Open Software Stack:** Built natively on trusted, open-source autopilot frameworks (**PX4** / **ArduPilot**). No forced cloud connections, hidden geofencing, or mandatory corporate server syncing.
*   **User Platform Sovereignty:** Complete consumer and developer data control. Modify your firmware, swap your hardware modules, and own your telemetry data without restrictions.

## 🗺️ Hardware Architecture & 100% Onshored Supply Chain
To completely insulate the platform from foreign regulatory risks, data privacy liabilities, and export bans, `open-drone-project` utilizes an entirely domestic, NDAA-compliant Bill of Materials (BOM) running natively on open-source infrastructure:

### 1. Flight Core & Intelligence
*   **Flight Controller:** `ARK Electronics ARKV6X Module` running native PX4 / ArduPilot open flight stacks.
*   **Interface Carrier:** `ARK Pixhawk Autopilot Bus (PAB)` Carrier Board standard.
*   **Companion Computer:** `Unusual Machines (UMAC)` for high-level secure edge compute and telemetry via MAVLink.
*   **Precision Hardware:** `Aero Precision` CNC-machined structural mounts and internal bracketry.

### 2. Propulsion & Aerodynamics
*   **Motors:** `Dronesmith USA` industrial-grade, defense-vetted brushless propulsion.
*   **Electronic Speed Controllers (ESCs):** `ARK Electronics ARK 4-in-1 ESC` utilizing open-source PX4 DroneCAN firmware.
*   **Propellers:** `Sensenich Propellers` or `Master Airscrew` domestic high-efficiency composite options.

### 3. Peripherals, Power & Telemetry
*   **Position Senses:** `ARK Electronics` ARK GPS + ARK Flow modules integrated via DroneCAN.
*   **Power Management:** `ARK Electronics PAB Power Module` for strict low-noise voltage regulation.
*   **Battery Stack:** `Natrion` or `Wake Energy` high-density US-manufactured cells.
*   **Radio Link:** High-reliability radio hardware utilizing open-source `ExpressLRS` protocols.
*   **Payload Interfacing:** Built-in modular rails compatible with `Teledyne FLIR` electro-optical and thermal sensors.

### 4. Frame & Enclosure
*   **Airframe/Chassis:** Proprietary modular chassis designed via Fusion 360, built using industrial carbon-fiber additive manufacturing.

## 🚀 Future Roadmap & Dual-Use Bridge
While our initial focus targets the highly active prosumer, developer, and hobbyist consumer markets, our strict compliance standards construct a natural pipeline into the defense, enterprise, and public safety sectors. 

*   **Phase 1:** Community & Developer Core (Open hardware specifications + baseline flight controller integration)
*   **Phase 2:** Prosumer Flight Framework (Modular camera, sensor payloads, and airframe optimization)
*   **Phase 3:** Enterprise & Dual-Use Licensing (SaaS tools for fleet compliance, encrypted pipelines, and commercial public safety tools)

## 📄 License
This repository is proudly licensed under the **Apache License 2.0**. We protect our community and core users with explicit patent and trademark protections, keeping open-source code safe, fair, and collaborative.
