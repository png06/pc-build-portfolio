# Custom Hardware Refurbishment & PC Systems Portfolio

A portfolio documenting 8 custom desktop systems assembled, diagnosed, and optimized using second-hand and aftermarket components.

---

##  Build Inventory & Spec Matrix

| # | Build Identifier | CPU | GPU | RAM | Total Cost | Est. Market Value |
|---|-------------------|-----|-----|-----|---------|------------|-------------------|
| 01 | Budget 1080p Esports | Ryzen 3 1200 | RX 580 | 16GB DDR4-2400 | $280 | $450 |
| 02 | Budget 1080p Esports 2 | Ryzen 5 3500 | RX 580 | 16GB DDR4-3000 | $410 | $620 |
| 03 | Compact ITX Build | Ryzen 5 5600X | GTX 1080 | 16GB DDR4-3600| $520 | $750 |
| 04 | Mid-Range 1080p/1440p | Ryzen 9 3900x | RTX 3060 | 16GB DDR4-2400 | $280 | $450 |
| 05 | entry-level 1440p gaming workstation | Ryzen 5 3500 | GTX 1660 Ti | 16GB DDR4-3000 | $410 | $620 |
| 06 | High-Performance 1440p Gaming & Render Station | Ryzen 7 5700X | RTX 3070 | 24GB DDR4-3600 | $520 | $750 |
| 07 | High-End 1440p / 4K-Capable Gaming Workstation | Ryzen 7 9700x | RX 6950 XT | 16GB DDR4-3000 | $410 | $620 |


---

## 🛠️ Build Logs & Gallery

### Build 01: Budget 1080p Esports System (SkyTech Archangel Overhaul)
* **Key Specs:** AMD Ryzen 3 1200 | ASRock Phantom Gaming RX 580 8GB | 16GB (2x8GB) DDR4-2400 | 500W 80+ Power Supply
* **Baseline State & Bottleneck Analysis:** Acquired a legacy prebuilt (SkyTech Archangel) limited by a single-channel 8GB RAM configuration, an entry-level GTX 1050 Ti (4GB VRAM constraint), and no wireless connectivity.
* **Upgrades & Hardware Integration:** 
  * Upgraded GPU to an ASRock RX 580 8GB, doubling VRAM capacity and verifying PCIe 8-pin power delivery on the existing 500W PSU.
  * Installed a matching secondary DIMM to enable dual-channel memory bandwidth, improving CPU frame pacing.
  * Installed a Wi-Fi adapter for wireless accessibility.

| Chassis & Exterior Condition | Internal Component Integration |
| :---: | :---: |
| <img src="images/build01-front.jpg" width="350"> | <img src="images/build01-inside.jpg" width="350"> |

---

### Build 02: Budget 1080p Esports & General Productivity Rig
* **Key Specs:** AMD Ryzen 5 1600 (6C/12T) | Sapphire Nitro+ RX 580 8GB | 16GB (2x8GB) DDR4-2400 | 500GB SSD | 500W 80+ PSU
* **Baseline State & Diagnostic Inspection:** 
  * Acquired as an incomplete barebones chassis with structural chassis damage (broken side panel) and a non-functional, failed-POST CPU.
  * System lacked dedicated boot media, operated on a single memory channel, and lacked wireless capabilities.
* **Component Replacement, Upgrades & Optimization:**
  * Sourced and integrated a replacement AMD Ryzen 5 1600 6-core processor after validating socket pin integrity and thermal paste distribution.
  * Replaced missing chassis panel and added a dedicated 500GB SSD to replace mechanical storage, drastically reducing OS latency and I/O wait times.
  * Installed a secondary matching 8GB DIMM to enable dual-channel memory bandwidth and integrated a wireless adapter for end-user connectivity.
 

| Chassis Profile & Front I/O | Component Integration & Internal Airflow |
| :---: | :---: |
| <img src="images/build02-front.jpg" width="350"> | <img src="images/build02-inside.jpg" width="350"> |

| Exterior View | Interior Layout |
| :---: | :---: |
| <img src="images/build02-front.jpg" width="350"> | <img src="images/build02-inside.jpg" width="350"> |

---

### Build 03: Mid-Range 1080p/1440p High-Refresh Rig 
* **Key Specs:** AMD Ryzen 5 5600X | EVGA FTW GeForce GTX 1080 8GB | 16GB (2x8GB) DDR4-2400 | 500W 80+ Certified PSU
* **Acquisition & Strategy:** Sourced as part of a budget component bundle to repurpose high-tier legacy hardware (GTX 1080 FTW) with a modern Zen 3 architecture, maximizing frame rates per dollar. 
* **Firmware & Optimization:** Flashed the latest motherboard BIOS microcode to support the Ryzen 5 5600X architecture; stress-tested power draw under combined synthetic loads to verify the 500W power delivery headroom.

| Chassis & Front Panel Profile | Internal Hardware Configuration |
| :---: | :---: |
| <img src="images/build04-front.jpg" width="350"> | <img src="images/build04-inside.jpg" width="350"> |

---

### Build 04: entry-level 1440p gaming workstation
* **Key Specs:** AMD Ryzen 9 3900X (12C/24T) | MSI GeForce RTX 3060 8GB | 32GB (2x16GB) DDR4-3200 | 600W 80+ Gold PSU
* **Acquisition & System Role:** Sourced and reconfigured as a 12-core multi-threaded workstation following a modular GPU reallocation. Integrated a dedicated Wi-Fi adapter to expand networking capabilities.
* **Thermal Optimization & Firmware Tuning:** Disassembled and cleaned the CPU cooling interface, applying fresh high-conductivity thermal paste to optimize thermal headroom across all 12 Zen 2 cores under sustained multi-threaded loads.
* **Diagnostics & Memory Stability:** Resolved intermittent POST and memory initialization hangs by cleaning oxidized DIMM contacts and updating motherboard AGESA microcode. Certified rock-solid stability via a 4-hour zero-error MemTest86 pass and continuous Cinebench R23 multi-core thermal stress loops.

| Exterior Assembly & I/O | Component Clearance & Cable Routing |
| :---: | :---: |
| <img src="images/build05-front.jpg" width="350"> | <img src="images/build05-inside.jpg" width="350"> |

---

### Build 05: Mid-Range 1080p Rig
* **Key Specs:** Ryzen 5 3600 | GTX 1660 Ti | 16GB DDR4-2400 | 80+ Certified 500W PSU
* **Acquisition & Strategy:** Secured through secondary market arbitrage during a high-value hardware acquisition. Targeted a balanced price-to-performance sweet spot for 1080p esports and mainstream titles.
* **Troubleshooting & Mod:** Conducted full component inspection, verified power delivery margins on the 500W 80+ PSU, and updated motherboard BIOS to optimize Zen 2 memory compatibility. Passed full stability and thermal stress benchmarks (Cinebench, FurMark, MemTest86) prior to deployment and resale.
  
| Exterior View | Interior Layout |
| :---: | :---: |
| <img src="images/build02-front.jpg" width="350"> | <img src="images/build02-inside.jpg" width="350"> |

---

### Build 06: High-Performance 1440p Gaming & Render Station
* **Key Specs:** AMD Ryzen 7 5800X (8C/16T) | ASUS GeForce RTX 3070 8GB | 32GB (2x16GB) DDR4-3200 | 650W 80+ Gold Certified PSU
* **Acquisition & System Role:** High-throughput 1440p/4K platform built around an 8-core Zen 3 CPU and Ampere architecture, optimized for sustained multi-core workloads and high-frame-rate rendering. Integrated a dedicated Wi-Fi adapter for wireless connectivity.
* **Firmware Tuning & Memory Subsystem Optimization:** 
  * Diagnosed unconfigured memory running at baseline JEDEC 2133MHz speeds rather than rated frequencies.
  * Configured UEFI/BIOS DOCP (Direct OverClock Profile) profiles and adjusted DRAM voltage to stabilize rated 3200MHz memory speeds with 1:1 FCLK (Infinity Fabric) synchronization.
* **Thermal & Power Validation:** Verified transient power-draw headroom on the 650W 80+ Gold supply under concurrent CPU/GPU load testing (Cinebench R23 + FurMark) with zero voltage rail droop or thermal throttling.
* 

| Chassis Profile & Intake Airflow | Component Layout & Thermal Clearance |
| :---: | :---: |
| <img src="images/build07-front.jpg" width="350"> | <img src="images/build07-inside.jpg" width="350"> |

---

### Build 07: High-End 1440p / 4K-Capable Gaming Workstation
* **Key Specs:** AMD Ryzen 7 9700X (8C/16T Zen 5) | AMD Radeon RX 6950 XT 16GB | 32GB (2x16GB) DDR5-6000 EXPO | 700W 80+ Gold Certified PSU
* **Acquisition & Platform Modernization:** 
  * Sourced via a high-tier Zen 5 platform bundle to build an enthusiast-grade compute and 4K gaming powerhouse.
  * Upgraded the platform to an AM5 motherboard with integrated Wi-Fi 6E/Bluetooth and high-speed NVMe storage expansion.
  * Installed additional high-CFM chassis intake/exhaust fans to manage the substantial thermal output of the 335W TDP RX 6950 XT.
* **Hardware Troubleshooting & Workarounds:**
  * **Motherboard ARGB Header Defect:** Identified a missing/sheared onboard 5V 3-pin ARGB header on the sourced board.
  * **Resolution:** Bypassed the damaged onboard pin header by routing lighting control through a dedicated internal SATA-powered ARGB/PWM distribution hub, restoring full addressable lighting control without risking short circuits on the PCB.
* **Memory & Electrical Tuning:** Enabled AMD EXPO profiles to lock in DDR5-6000 memory bandwidth with 1:1 UCLK/MCLK ratio; stress-tested total system power draw under heavy transient load conditions.


---

## 🛒 Hardware Procurement, Risk Mitigation & Arbitrage Guide

A practical engineering framework for vetting secondary-market components, evaluating seller reliability, and executing high-ROI system upgrades.

---

### 1. Component-Specific Risk Analysis & Inspection Rubric

* **Power Supplies (PSUs):** Always prioritize recognized, reputable name brands (e.g., Seasonic, EVGA, Corsair) with a minimum verified **80+ certification** (Bronze/Gold). Avoid unbranded, off-spec grey-market units, as unstable 12V/5V/3.3V rails can cause catastrophic damage across all connected components.
* **CPUs & Sockets:**
  * **AMD AM4 (PGA):** Inspect the underside of the processor closely under direct lighting for bent, sheared, or missing copper contact pins.
  * **AMD AM5 / Intel LGA (LGA):** Inspect the motherboard socket itself rather than the CPU; look for crushed, crossed, or misaligned delicate spring pins inside the socket array.
* **Graphics Cards (GPUs):** Screen for excessive thermal wear, silicon degradation, and fan bearing fatigue commonly associated with 24/7 crypto-mining rigs or extreme, unverified overclocks. Look for discolored thermal pads, oxidized heatsink fins, and dried factory paste.
* **Storage & Memory:** Prioritize systems with SSD-based boot media; verify memory sticks run in matched pairs for stability.

---

### 2. Seller Screening, Transaction Safety & Logistics

* **Account & Review Verification:** Prioritize sellers with verified account histories, active ratings, and consistent positive buyer feedback. Avoid accounts created days prior to listing high-value silicon.
* **Listing Authenticity:** Ensure the photos are original (not stock images) and verify that the written description accurately matches the exact hardware model and serial revisions shown. On Facebook Marketplace, beware of accounts listing the same item in multiple distant cities simultaneously to fish for remote payments.
* **Payment Security:** **Never use PayPal Friends & Family (F&F)** under any circumstance for unverified remote hardware. Strictly utilize **PayPal Goods & Services (G&S)** to ensure buyer protection against dead-on-arrival (DOA) hardware or scam listings.
* **Logistics & Radius Strategy:** Limit local pickups to a maximum travel radius of **1 hour**. Extended travel increases the financial risk of buyer/seller "no-shows," cancellations, or inability to safely bench-test hardware in person.

---

### 3. High-ROI Upgrades (Maximum Value & Performance Impact)

These low-cost modifications deliver significant measurable improvements in performance, reliability, and end-user demand:

* **Dedicated Boot SSD Integration:** Replacing mechanical HDDs or low-capacity SATA drives with dedicated high-speed SSDs drastically reduces Windows OS boot times, lowers random I/O latency, and improves overall system responsiveness.
* **Dual-Channel Memory Configurations:** Upgrading single-stick RAM setups to matched dual-channel (e.g., 1x16GB to 2x8GB) doubles memory bus bandwidth, stabilizing CPU 1% low frame rates and eliminating micro-stutters during heavy gaming and multi-tasking workloads.
* **Integrated Wi-Fi / Bluetooth Connectivity:** Many desktop motherboards lack onboard wireless capability. Integrating affordable dedicated PCIe or M.2 Wi-Fi adapters adds immediate everyday convenience for users without dedicated Ethernet cable runs.
---
