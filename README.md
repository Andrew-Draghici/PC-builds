# PC-builds
Here are all custom built PC's

## 💻 Legacy Asset: HP Omen 15 (Maintenance & Repair Log)
![Screenshot_20210225-194753_Video Player (5)](https://github.com/user-attachments/assets/2e7d5241-0eb7-43ba-b497-4c0336042562)

**Role:** Primary Mobile Workstation (Decommissioned)
**Mission:** High-performance mobile computing and hardware repair practice.

| Component | Specification | Maintenance & Service History |
| :--- | :--- | :--- |
| **CPU** | Intel Core i7-7700HQ | Periodic thermal paste replacement (Arctic MX-4) to maintain peak clocks. |
| **GPU** | NVIDIA GTX 1050 Ti | Verified stability during high-load forensic processing. |
| **Memory** | Upgraded RAM | Manually upgraded to maximize multi-tasking overhead. |
| **Display** | 15.6" Replacement | **Full Panel Replacement:** Sourced and installed a new display assembly after physical impact damage. |

### 🔬 Maintenance & Incident Report
* **Physical Repair:** Successfully performed a complete display panel replacement. Managed the system using a secondary TV output via HDMI during the part-sourcing phase.
![20210303_132516](https://github.com/user-attachments/assets/96884771-4063-42ee-8284-8b11b25a22bb)
* **Thermal Management:** Regularly disassembled the chassis for internal dust removal and thermal interface material (TIM) refreshes to prevent thermal throttling.
* **Decommissioning:** The asset was retired following catastrophic liquid damage to the motherboard. A cost-benefit analysis determined that a full board replacement exceeded the asset's current market value, leading to a strategic salvage of reusable components.


## 🖥️ Build 01: High-Performance Workstation (Incident & Migration Log)

**Role:** Primary Workstation / Virtualization Host
**Status:** Decommissioned (Post-Failure Analysis)
**Mission:** High-density workstation for forensic analysis and multi-threaded workloads.

| Component | Specification | Technical Justification |
| :--- | :--- | :--- |
| **CPU** | Intel Core i9-10900X (X-Series) | 10 Cores / 20 Threads for high-density VM scaling. |
| **Mobo** | Gigabyte X299X DESIGNARE 10G | Dual 10GbE NICs for high-speed network infrastructure labs. |
| **Memory** | 48GB Corsair Vengeance RGB | Mixed configuration (32GB + 16GB) to maximize available overhead. |
| **GPU** | AMD Radeon RX 6900 XT (16GB) | Large VRAM buffer for forensic imaging and rendering tasks. |
| **Cooling** | Corsair H150i Elite Capellix | 360mm AIO for thermal stability during long-running exports. |
| **Case** | Corsair 5000D Airflow | Upgraded from Mid-Tower to resolve AIO/RAM clearance issues. |

### 🔬 Root Cause Analysis (RCA) & Troubleshooting
* **Incident:** System failure to POST following manual RAM frequency adjustment in bios.
* **Diagnosis:** Observed **Q-Code "E3"** (Initialization Failure). That would mean either the IMC (Integrated Memory Controller) is dead , or a power delivery to the RAM rails porblem , which resulted into changing the platform fully.
![bb1a7551-984b-417c-8beb-a1335693be76](https://github.com/user-attachments/assets/7d145033-2678-4304-aa38-225a33cfa900)

* **Verification:** Conducted **MemTest86** yielding **398 hardware errors** on Test 13.
![eafd16de-8f6f-462b-88e7-fe36eaa8859b](https://github.com/user-attachments/assets/8c377f1c-5ab1-46d8-bbe6-d5c088b3ce64)

* **Resolution:** Identified failing motherboard power rail; managed full platform migration and asset liquidation.

![received_1032744977506358](https://github.com/user-attachments/assets/93ad4a18-01c6-4c11-a10e-562cb2d4499f)


![received_268101822050411](https://github.com/user-attachments/assets/6bf51d47-e28f-4b26-8aba-e7b2aa2783f0)



### 🖥️ Build 02: Ultra-High-End Consumer Workstation (Client Delivery)
**Role:** External Client Build  
**Budget:** £3,500  
**Mission:** Deliver a zero-bottleneck system for high-fidelity tasks and long-term hardware relevance.

| Component | Specification | Technical Justification |
| :--- | :--- | :--- |
| **CPU** | AMD Ryzen 9 7950X3D | Flagship 16-core processor for maximum computational throughput. |
| **GPU** | XFX Speedster MERC 310 | High VRAM capacity for intensive graphical and parallel workloads. |
| **Mobo** | Gigabyte B650 | Chosen for stable VRMs and future-proof AM5 socket longevity. |
| **Storage** | 4TB Samsung 990 Pro (NVMe) | Industry-leading IOPS to ensure near-instant data access. |
| **Cooling** | Corsair iCUE H150i Elite | 360mm AIO to ensure the 7950X3D maintains peak boost clocks. |

**Key Deliverables for Client:**
* **Assembly & Testing:** Full hardware stress test (AIDA64/MemTest86) to ensure 100% stability before handover.
* **Cable Management:** Professional routing in the Corsair 500D to maximize airflow and aesthetics.
* **Support:** Provided post-build technical support and maintenance guidance.
![B B PC](https://github.com/user-attachments/assets/15d08e82-f035-4ff7-b495-c50ce6aeb568)

## 🖥️ Build 03: Flagship Dual-Chamber Workstation (2026 Client Delivery)
![20251227_230445](https://github.com/user-attachments/assets/729400fe-afff-4b5d-b3ea-2be24fe3bf14)

**Role:** Lead Systems Engineer (External Client)
**Status:** Deployed & Benchmarked
**Build Time:** 48-Hour Rapid Deployment
**Mission:** Deliver a high-airflow, dual-chamber architecture for sustained heavy-load stability.

| Component | Specification | Technical Justification |
| :--- | :--- | :--- |
| **CPU** | AMD Ryzen 9 7900X3D | High-efficiency 12-core processing for complex simulations. |
| **GPU** | XFX Swift Radeon RX 9070 XT (16GB) | Latest-gen architecture for high-speed parallel data processing. |
| **Mobo** | Gigabyte B650 AORUS | Robust VRM thermal management for consistent power delivery. |
| **Storage** | 4TB (2x 2TB Samsung 990 Pro) | RAID-ready NVMe configuration for redundant high-speed IOPS. |
| **PSU** | Corsair RM850x (80+ Gold) | Japanese capacitors for industrial-grade ripple suppression. |
| **Chassis** | NZXT H9 Airflow (Dual-Chamber) | Isolated thermal zones for PSU/Storage to reduce core component heat soak. |
<img width="300" height="452" alt="image" src="https://github.com/user-attachments/assets/548bb210-904a-409f-8ca3-27a1cbc73279" />


### 🛠️ Engineering Highlights & Build Process
* **Rapid Deployment:** Executed a full hardware lifecycle from unboxing to stability benchmarking in **48 hours**.
* **F-Panel Logic:** Methodical wiring of the front panel and I/O headers to ensure clean signal paths and serviceability.
* **Thermal Integrity:** Utilized a Thermalright AIO and multiple high-static pressure intake fans to create a positive pressure environment, preventing dust ingress.
* **Quality Assurance:** Final deployment included a full burn-in test to verify the reliability of the dual 990 Pro storage array.
