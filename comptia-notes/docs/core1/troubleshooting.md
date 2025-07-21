# 5.0 Hardware and Network Troubleshooting (28% of Core 1 Exam)

_Focus: Systematic troubleshooting of motherboards, RAM, CPUs, power, storage, displays, mobile devices, networks, and printers using proper methodology_

---

## 5.1 Motherboard, RAM, CPU, and Power Issues

**Scenario Focus:** You'll diagnose hardware failures using symptoms and apply the troubleshooting methodology to identify root causes and solutions.

### Common Symptoms and Likely Causes:

#### Boot and Power Issues:

- **POST Beeps** - Hardware failure detected during Power-On Self-Test
    - Single beep: Normal boot
    - Continuous beeps: Power supply or motherboard failure
    - Pattern beeps: RAM, CPU, or graphics card issues
- **Proprietary Crash Screens** - Blue Screen of Death (BSOD), kernel panics
- **Blank Screen** - No video output despite power
- **No Power** - System won't turn on at all

#### Performance and Stability Issues:

- **Sluggish Performance** - Slow system response
    - Insufficient RAM, overheating CPU, failing storage
- **Overheating** - System runs hot, thermal throttling
- **Random Shutdown** - Unexpected system power-offs
- **Application Crashes** - Software unexpectedly closes

#### Physical and Environmental Signs:

- **Burning Smell** - Electrical component failure (immediate shutdown required)
- **Unusual Noise** - Fan failure, hard drive clicking
- **Capacitor Swelling** - Motherboard component failure
- **Inaccurate System Date/Time** - CMOS battery failure

### Troubleshooting Approach:

1. **Safety First** - Power down for burning smells
2. **Check Connections** - Reseat RAM, cables, expansion cards
3. **Test Components** - Swap RAM modules, test PSU
4. **Monitor Temperatures** - Check CPU and system temps
5. **Update BIOS/Drivers** - Resolve compatibility issues

_Key Study Point: POST beep patterns indicate specific hardware failures. Always check power connections and temperatures first, then move to component-level troubleshooting._

---

## 5.2 Storage and RAID Issues

**Scenario Focus:** You'll identify storage failures through symptoms and understand RAID array troubleshooting procedures.

### Common Storage Symptoms:

#### Performance Indicators:

- **LED Status Indicators** - Drive health lights on servers/arrays
- **Extended Read/Write Times** - Slow file operations
- **Low Performance IOPS** - Input/Output Operations Per Second degradation

#### Failure Symptoms:

- **Grinding Noises** - Mechanical hard drive bearing failure
- **Clicking Sounds** - Hard drive head crash (immediate backup needed)
- **Bootable Device Not Found** - Boot drive failure or corruption
- **Data Loss/Corruption** - Files missing or damaged
- **Missing Drives in OS** - Drive not detected by operating system

#### RAID-Specific Issues:

- **RAID Failure** - Array degraded or failed
- **Array Missing** - RAID configuration lost
- **S.M.A.R.T. Failure** - Self-Monitoring Analysis and Reporting Technology alerts
- **Audible Alarms** - Server/NAS alerting to drive failures

### Troubleshooting Storage Issues:

1. **Check S.M.A.R.T. Status** - Review drive health metrics
2. **Verify Connections** - SATA/power cables secure
3. **Test in Another System** - Isolate drive vs system issues
4. **Check RAID Status** - Verify array health and configuration
5. **Replace Failed Drives** - Hot-swap if supported
6. **Restore from Backup** - Last resort for data recovery

_Key Study Point: Clicking sounds from drives indicate imminent failure - immediate backup required. S.M.A.R.T. warnings should be taken seriously as predictive failure indicators._

---

## 5.3 Video, Projector, and Display Issues

**Scenario Focus:** You'll distinguish between display hardware problems and configuration issues while applying appropriate solutions.

### Common Display Symptoms:

#### Configuration Problems:

- **Incorrect Input Source** - Wrong input selected on display
- **Sizing Issues** - Display not fitting screen properly
- **Incorrect Color Display** - Wrong color profile or damaged cable

#### Hardware Failures:

- **Physical Cabling Issues** - Loose, damaged, or wrong cable type
- **Burnt-out Bulb** - Projector lamp failure
- **Dead Pixels** - Permanently black or colored pixels on LCD
- **Display Burn-in** - Permanent image ghosting (OLED/plasma)

#### Image Quality Issues:

- **Fuzzy Image** - Poor focus, wrong resolution, or analog interference
- **Flashing Screen** - Unstable connection or failing backlight
- **Dim Image** - Backlight failure or brightness settings
- **Distorted Image** - Wrong aspect ratio or scaling issues

#### Projector-Specific Issues:

- **Intermittent Projector Shutdown** - Overheating or lamp end-of-life
- **Audio Issues** - HDMI audio routing problems

### Display Troubleshooting Steps:

1. **Check Input Selection** - Verify correct input source
2. **Test Cables** - Try different video cables
3. **Adjust Resolution** - Match native display resolution
4. **Update Drivers** - Graphics card driver issues
5. **Test Different Display** - Isolate display vs graphics card
6. **Check Power** - Ensure adequate power to display

_Key Study Point: Always check simple things first - input source, cable connections, and resolution settings before assuming hardware failure._

---

## 5.4 Mobile Device Issues

**Scenario Focus:** You'll diagnose mobile device problems and determine appropriate repair vs replacement decisions.

### Common Mobile Device Symptoms:

#### Power and Battery Issues:

- **Poor Battery Health** - Reduced battery life, frequent charging needed
- **Swollen Battery** - Physical battery expansion (safety hazard)
- **Improper Charging** - Won't charge or charges slowly
- **Overheating** - Device becomes excessively hot

#### Physical Damage:

- **Broken Screen** - Cracked or shattered display
- **Physically Damaged Ports** - Charging/data ports damaged
- **Liquid Damage** - Water or moisture exposure
- **Digitizer Issues** - Touch screen not responding properly

#### Performance and Software Issues:

- **Poor/No Connectivity** - Wi-Fi, cellular, or Bluetooth problems
- **Malware** - Suspicious apps or behavior
- **Cursor Drift/Touch Calibration** - Inaccurate touch response
- **Unable to Install New Applications** - Storage full or OS restrictions
- **Stylus Does Not Work** - Digitizer or stylus problems
- **Degraded Performance** - Slow operation, app crashes

### Mobile Device Troubleshooting:

1. **Safety Assessment** - Swollen batteries require immediate replacement
2. **Basic Connectivity** - Check network settings and signal strength
3. **Restart/Reset** - Soft reset often resolves software issues
4. **Storage Check** - Verify available storage space
5. **Update Software** - Install OS and app updates
6. **Factory Reset** - Last resort for software issues

_Key Study Point: Swollen batteries are safety hazards requiring immediate attention. Many mobile issues are software-related and can be resolved without hardware replacement._

---

## 5.5 Network Issues

**Scenario Focus:** You'll systematically troubleshoot network connectivity problems using appropriate tools and methodology.

### Common Network Symptoms:

#### Connectivity Problems:

- **Intermittent Wireless Connectivity** - Drops connection randomly
- **Slow Network Speeds** - Reduced throughput
- **Limited Connectivity** - Connected but no internet access
- **Intermittent Internet Connectivity** - Internet access comes and goes

#### Network Quality Issues:

- **Jitter** - Inconsistent packet delivery timing
- **Poor VoIP Quality** - Voice calls breaking up or delayed
- **High Latency** - Slow response times
- **External Interference** - Wireless signal disruption

#### Infrastructure Problems:

- **Port Flapping** - Network port repeatedly connecting/disconnecting
- **Authentication Failures** - Can't join wireless networks or domain

### Network Troubleshooting Methodology:

1. **Check Physical Connections** - Cables, power, link lights
2. **Verify IP Configuration** - IP address, subnet mask, gateway, DNS
3. **Test Connectivity** - Ping local gateway, then external hosts
4. **Check Wireless Settings** - SSID, security type, signal strength
5. **Analyze Traffic** - Use network monitoring tools
6. **Update Drivers/Firmware** - Network adapter and router updates

### Network Troubleshooting Tools:

- **ping** - Test basic connectivity
- **ipconfig/ifconfig** - Check IP configuration
- **nslookup** - Test DNS resolution
- **Wi-Fi Analyzer** - Check wireless signal strength and interference
- **Cable Tester** - Verify cable integrity
- **Network Monitor** - Analyze traffic patterns

_Key Study Point: Use the OSI model approach - start with physical layer (cables, power) and work up through network, then application layers._

---

## 5.6 Printer Issues

**Scenario Focus:** You'll diagnose and resolve printer problems specific to different printer technologies.

### Common Printer Symptoms:

#### Print Quality Issues:

- **Lines Down Printed Pages** - Dirty or damaged print heads/drums
- **Garbled Print** - Driver issues or communication problems
- **Faded Prints** - Low toner/ink or print head issues
- **Speckling on Printed Pages** - Dirty components or toner issues
- **Double/Echo Images** - Drum or fuser problems in laser printers

#### Paper Handling Problems:

- **Paper Jams** - Mechanical feed issues or wrong paper type
- **Paper Not Feeding** - Roller problems or empty trays
- **Multipage Misfeed** - Multiple sheets feeding at once
- **Incorrect Page Orientation** - Software vs hardware orientation settings
- **Tray Not Recognized** - Sensor or driver issues

#### System and Queue Issues:

- **Multiple Prints Pending in Queue** - Print spooler problems
- **Connectivity Issues** - Network or USB connection problems
- **Frozen Print Queue** - Spooler service stopped or corrupted jobs

#### Mechanical Problems:

- **Grinding Noise** - Mechanical component failure
- **Finishing Issues** - Stapler jams, hole punch problems

### Printer Troubleshooting by Type:

#### Laser Printers:

- Check toner levels and distribution
- Clean imaging drum and corona wires
- Verify fuser temperature and operation
- Replace maintenance kit components

#### Inkjet Printers:

- Clean print heads and nozzles
- Check ink cartridge installation
- Align print heads
- Clear paper path obstructions

#### Thermal Printers:

- Check thermal paper quality and installation
- Clean heating element
- Verify paper path alignment

_Key Study Point: Different printer types have unique maintenance requirements. Print quality issues often indicate specific component problems that vary by printer technology._

---

## CompTIA Troubleshooting Methodology

### The 6-Step Process:

1. **Identify the Problem**
    
    - Gather information from users
    - Document symptoms
    - Determine recent changes
2. **Establish Theory of Probable Cause**
    
    - Question the obvious first
    - Consider multiple possibilities
    - Research knowledge base if needed
3. **Test the Theory**
    
    - If confirmed → proceed to step 4
    - If not confirmed → return to step 2
4. **Establish Plan of Action**
    
    - Determine steps to resolve
    - Consider impact on users/systems
    - Get approval for major changes
5. **Implement the Solution**
    
    - Execute the plan
    - Verify full system functionality
    - Implement preventive measures
6. **Document Everything**
    
    - Record findings and lessons learned
    - Document actions taken
    - Note outcomes for future reference

---

## Study Tips for Troubleshooting Domain

### High-Priority Symptoms to Memorize:

- **POST beep patterns** and their meanings
- **S.M.A.R.T. failures** as predictive indicators
- **Swollen batteries** as safety hazards
- **Grinding/clicking sounds** from storage devices
- **Print quality issues** by printer type

### Troubleshooting Strategy:

- **Always start with the obvious** - power, connections, settings
- **Use substitution method** - swap components to isolate problems
- **Check recent changes** - new hardware, software, or configuration
- **Document everything** - symptoms, tests performed, solutions

### Common Exam Scenarios:

- System won't boot (POST beeps, power issues)
- Slow performance (overheating, insufficient RAM, failing storage)
- Network connectivity problems (IP configuration, wireless settings)
- Print quality issues (maintenance needed, wrong drivers)
- Mobile device problems (battery, connectivity, physical damage)

### Tools and Commands to Know:

- **Hardware tools:** Multimeter, POST card, cable tester
- **Software tools:** Device Manager, Event Viewer, ping, ipconfig
- **Mobile tools:** Built-in diagnostics, Wi-Fi analyzer
- **Printer tools:** Test pages, cleaning utilities, driver updates

### Critical Safety Considerations:

- **Burning smells** - immediate shutdown required
- **Swollen batteries** - fire/explosion hazard
- **Grinding hard drives** - potential data loss
- **Overheating components** - thermal damage risk

---

_Weight: 28% of Core 1 Exam | Estimated Study Time: 35-40 hours_

**Note:** This is the largest domain on the exam at 28%. Focus heavily on symptom recognition and the troubleshooting methodology, as these concepts apply across all hardware and network scenarios.