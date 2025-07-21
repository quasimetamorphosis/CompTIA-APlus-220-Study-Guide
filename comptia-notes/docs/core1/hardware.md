# 3.0 Hardware (25% of Core 1 Exam)

_Focus: Understanding display technologies, cable types, RAM specifications, storage devices, motherboard installation, power supplies, and printer deployment/maintenance_

---

## 3.1 Display Components and Attributes

**Comparison Focus:** You'll need to identify different display technologies and match appropriate display characteristics to specific use cases and requirements.

### Display Types:

- **LCD (Liquid Crystal Display)**
    - **IPS (In-Plane Switching)** - Best color accuracy, wide viewing angles
    - **TN (Twisted Nematic)** - Fastest response times, lowest cost
    - **VA (Vertical Alignment)** - Good contrast, moderate response times
- **OLED (Organic LED)** - Perfect blacks, high contrast, potential burn-in
- **Mini-LED** - Better backlighting control, improved contrast over LCD

### Display Components:

- **Touch Screen/Digitizer** - Converts touch input to digital signals
- **Inverter** - Converts DC to AC for LCD backlighting (older displays)

### Key Display Attributes:

- **Pixel Density** - Pixels per inch, affects image sharpness
- **Refresh Rates** - 60Hz, 120Hz, 144Hz for smooth motion
- **Screen Resolution** - 1080p, 1440p, 4K pixel counts
- **Color Gamut** - Range of colors the display can reproduce

_Key Study Point: Match display technologies to use cases - IPS for design work, TN for gaming, OLED for media consumption. Understand the trade-offs between cost, performance, and image quality._

---

## 3.2 Cable Types, Connectors, Features, and Purposes

**Summary Focus:** You'll identify appropriate cables and connectors for specific devices and understand their capabilities and limitations.

### Network Cables:

- **Copper Categories**
    - **T568A/T568B Standards** - Wiring configurations for RJ45
    - **Coaxial** - Cable TV and older network installations
    - **Shielded Twisted Pair** - Reduces electromagnetic interference
    - **Unshielded Twisted Pair** - Standard Ethernet cabling
    - **Direct Burial** - Outdoor installation rated cables
- **Plenum-Rated** - Fire-resistant cables for air handling spaces
- **Optical Fiber**
    - **Single-mode** - Long distance, laser light source
    - **Multimode** - Shorter distance, LED light source

### Peripheral Cables:

- **USB 2.0** - 480 Mbps, older devices
- **USB 3.0** - 5 Gbps, blue connectors
- **Serial** - Legacy device communication
- **Thunderbolt** - High-speed data and video

### Video Cables:

- **HDMI** - Digital video/audio, consumer standard
- **DisplayPort** - High resolution, daisy-chaining support
- **DVI** - Digital video only, legacy systems
- **VGA** - Analog video, older systems
- **USB-C** - Modern all-in-one connector

### Storage Cables:

- **SATA** - Internal drive connections
- **eSATA** - External SATA connections

### Connector Types:

- **RJ11** - Phone line connections
- **RJ45** - Ethernet connections
- **F-type** - Coaxial/cable connections
- **ST, SC, LC** - Fiber optic connectors
- **Lightning** - Apple proprietary
- **DB9** - Serial connections
- **Molex** - Internal power connections

_Key Study Point: Know maximum speeds and distances for each cable type. Understand when to use shielded vs unshielded cables and the differences between fiber types._

---

## 3.3 RAM Characteristics

**Comparison Focus:** You'll select appropriate RAM types based on system requirements and understand compatibility considerations.

### Form Factors:

- **DIMM (Dual In-line Memory Module)** - Desktop systems, 240/288 pins
- **SODIMM (Small Outline DIMM)** - Laptops and compact systems

### DDR Generations:

- **DDR4** - Current standard, lower power than DDR3
- **DDR5** - Latest generation, higher speeds and capacity
- **DDR3** - Legacy systems, higher power consumption

### RAM Features:

- **ECC vs Non-ECC**
    - **ECC (Error-Correcting Code)** - Detects and corrects memory errors
    - **Non-ECC** - Standard consumer RAM, no error correction
- **Channel Configurations** - Single, dual, triple, quad channel setups

_Key Study Point: Understand that RAM must match motherboard specifications exactly - generation, form factor, and speed. Know when ECC is required (servers) vs optional (workstations)._

---

## 3.4 Storage Devices

**Comparison Focus:** You'll evaluate storage options based on performance, capacity, and cost requirements while understanding different interface types.

### Hard Drives (HDDs):

- **Spindle Speeds** - 5400 RPM, 7200 RPM, 10000 RPM
- **Form Factors**
    - **2.5-inch** - Laptops and portable systems
    - **3.5-inch** - Desktop systems and servers

### Solid State Drives (SSDs):

- **Communication Interfaces**
    - **NVMe** - Fastest, uses PCIe lanes directly
    - **SATA** - Compatible with existing SATA infrastructure
    - **PCIe** - High-speed expansion slot connection
    - **SAS** - Enterprise-grade, hot-swappable
- **Form Factors**
    - **M.2** - Small form factor for modern systems
    - **mSATA** - Mini-SATA for compact devices

### Drive Configurations:

- **RAID Arrays**
    - **RAID 0** - Striping for performance, no redundancy
    - **RAID 1** - Mirroring for redundancy, slower writes
    - **RAID 5** - Striping with parity, good balance
    - **RAID 6** - Dual parity, higher fault tolerance
    - **RAID 10** - Striped mirrors, best performance + redundancy

### Removable Storage:

- **Flash Drives** - Portable USB storage
- **Memory Cards** - SD, microSD for cameras/phones

### Optical Drives:

- **CD/DVD/Blu-ray** - Legacy media reading/writing

_Key Study Point: Understand the performance hierarchy - NVMe SSD > SATA SSD > 7200 RPM HDD > 5400 RPM HDD. Know RAID levels and their use cases._

---

## 3.5 Motherboards, CPUs, and Add-on Cards

**Scenario Focus:** You'll install and configure motherboard components while understanding compatibility requirements and BIOS/UEFI settings.

### Motherboard Form Factors:

- **ATX** - Full-size, most expansion slots
- **microATX** - Smaller, fewer expansion slots
- **ITX** - Compact, minimal expansion

### Motherboard Connectors:

- **PCI** - Legacy expansion slots
- **PCIe** - Modern expansion (x1, x4, x8, x16)
- **Power Connectors** - 24-pin ATX, 4/8-pin CPU
- **SATA/eSATA** - Storage device connections
- **Headers** - Front panel, USB, audio connections
- **M.2** - High-speed SSD slots

### CPU Compatibility:

- **Socket Types**
    - **AMD** - AM4, AM5, TR4 sockets
    - **Intel** - LGA 1200, LGA 1700 sockets
- **Multisocket** - Server motherboards with multiple CPU sockets

### BIOS/UEFI Settings:

- **Boot Options** - Boot order and device selection
- **USB Permissions** - Enable/disable USB devices
- **TPM Security** - Trusted Platform Module configuration
- **Fan Controls** - Temperature-based fan curves
- **Secure Boot** - UEFI security feature
- **Boot Password** - System startup protection
- **BIOS Password** - Setup utility protection
- **Temperature Monitoring** - Hardware health tracking

### Advanced Features:

- **Virtualization Support** - Intel VT-x, AMD-V
- **Encryption** - TPM and HSM security modules

### CPU Architecture:

- **x86/x64** - Intel and AMD desktop/server processors
- **ARM** - Mobile and low-power processors
- **Core Configurations** - Single, dual, quad, octa-core options

### Expansion Cards:

- **Sound Cards** - Enhanced audio processing
- **Video Cards** - Graphics processing and display output
- **Capture Cards** - Video input and recording
- **Network Interface Cards** - Wired and wireless networking

### Cooling Solutions:

- **Fans** - Case and component cooling
- **Heat Sinks** - Passive CPU cooling
- **Thermal Paste/Pads** - Heat transfer materials
- **Liquid Cooling** - Advanced CPU/GPU cooling

_Key Study Point: CPU and motherboard must have matching socket types. Understand BIOS vs UEFI differences and key security settings like Secure Boot and TPM._

---

## 3.6 Power Supply Installation

**Scenario Focus:** You'll select and install appropriate power supplies based on system requirements and understand power specifications.

### Power Supply Specifications:

- **Input Voltage**
    - **110-120 VAC** - North American standard
    - **220-240 VAC** - International standard
- **Output Voltages** - 3.3V, 5V, 12V DC rails
- **Motherboard Connector** - 20+4 pin main power
- **Wattage Rating** - Total power output capacity
- **Energy Efficiency** - 80 Plus certification levels

### Power Supply Types:

- **Redundant PSU** - Backup power supplies for servers
- **Modular PSU** - Detachable cables for cable management

_Key Study Point: Calculate total system power requirements and add 20% headroom. Understand that modern systems primarily use 12V rail for CPU and graphics cards._

---

## 3.7 Multifunction Device/Printer Deployment

**Scenario Focus:** You'll deploy and configure printers in network environments while implementing appropriate security measures.

### Deployment Considerations:

- **Unboxing and Setup** - Physical installation and location planning
- **Driver Installation** - OS-specific printer drivers
    - **PCL vs PostScript** - Printer language compatibility
- **Firmware Updates** - Security and feature improvements

### Connectivity Options:

- **USB** - Direct computer connection
- **Ethernet** - Wired network connection
- **Wireless** - Wi-Fi network integration

### Network Sharing:

- **Printer Share** - Share printer from host computer
- **Print Server** - Dedicated network print management

### Configuration Settings:

- **Duplex** - Double-sided printing
- **Orientation** - Portrait vs landscape
- **Tray Settings** - Paper size and type selection
- **Quality Settings** - Draft, normal, high quality modes

### Security Features:

- **User Authentication** - Login required for printing
- **Badging** - ID card access control
- **Audit Logs** - Track printing activity
- **Secured Prints** - Release prints with PIN/badge

### Network Services:

- **Email Integration** - Scan-to-email functionality
- **SMB Sharing** - Network folder scanning
- **Cloud Services** - Direct cloud storage integration
- **ADF/Flatbed** - Document feeding options

_Key Study Point: Understand the difference between sharing a printer from a computer vs using a dedicated print server. Know security implications of network-connected printers._

---

## 3.8 Printer Maintenance

**Scenario Focus:** You'll perform appropriate maintenance procedures for different printer types and understand their specific requirements.

### Laser Printer Maintenance:

- **Routine Tasks** - Replace toner, apply maintenance kits, calibrate
- **Cleaning** - Remove dust and toner residue
- **Components** - Imaging drum, fuser, transfer rollers

### Inkjet Printer Maintenance:

- **Components** - Ink cartridges, printheads, paper rollers, feeders
- **Routine Tasks** - Clean printheads, replace cartridges, calibrate colors, clear jams
- **Issues** - Clogged nozzles, streaking, color mixing

### Thermal Printer Maintenance:

- **Components** - Feed assembly, special thermal paper
- **Routine Tasks** - Replace paper, clean heating element, remove debris
- **Requirements** - Heat-sensitive paper, regular cleaning

### Impact Printer Maintenance:

- **Components** - Multipart paper, ribbon cartridges
- **Routine Tasks** - Replace ribbon, printhead, and paper
- **Applications** - Carbon copy forms, receipts

_Key Study Point: Each printer type has unique maintenance requirements - lasers need toner and cleaning, inkjets need printhead maintenance, thermal printers need special paper, impact printers need ribbons._

---

## Study Tips for Hardware Domain

### High-Priority Topics:

- RAM compatibility (form factor, generation, ECC vs non-ECC)
- Storage performance hierarchy (NVMe > SATA SSD > HDD)
- Power supply wattage calculations
- Printer maintenance procedures by type

### Common Exam Scenarios:

- Selecting appropriate RAM for system upgrade
- Choosing storage solution based on performance needs
- Troubleshooting display issues (cable vs display problem)
- Installing motherboard with proper power connections
- Configuring network printer with security settings

### Hands-On Practice:

- Install different RAM types and understand compatibility
- Connect various display cables and test resolutions
- Practice motherboard installation and BIOS configuration
- Set up network printers with security features
- Perform maintenance on different printer types

### Memory Aids:

- **Display Technologies:** "IPS = Image Perfect, TN = Time's Nice (fast), VA = Very Average"
- **RAID Levels:** "0 = Zero redundancy, 1 = One copy, 5 = Five drives minimum, 10 = One plus zero"
- **Power Rails:** "3.3V and 5V for logic, 12V for motors and high power"

---

_Weight: 25% of Core 1 Exam | Estimated Study Time: 30-35 hours_