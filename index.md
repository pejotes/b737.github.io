## Welcome to b737 Project

### Building an Authentic Boeing 737 Flight Simulator

This project documents my journey building a high-fidelity Boeing 737 cockpit simulator. The goal is to create the most realistic 737 experience possible by combining professional-grade software, authentic OEM hardware, quality replica components, and custom-built systems.

This is not just a gaming setup—it's a serious flight training environment that replicates the look, feel, and functionality of a real Boeing 737 flight deck. Every component is carefully selected or crafted to deliver maximum realism and immersion, from the authentic cockpit seats to the fully motorized controls.

The build philosophy balances authenticity with practicality: using OEM parts where possible, high-quality replicas from established manufacturers, and custom solutions where needed. The result is a professional-grade simulator suitable for serious training and pure aviation enthusiasm.


## Software

### Flight Simulator Platform
**Microsoft Flight Simulator 2020**

The simulator runs on MSFS 2020, providing cutting-edge visuals, realistic weather systems, and a living world environment. Combined with ProSim737's professional avionics suite, this creates an unparalleled balance of visual realism and systems depth.

### ProSim 737 - Professional Boeing 737 Simulation Suite

**Current Version:** ProSim737 v3.35 LTS 2025-2 (Released November 10, 2025)

ProSim737 is a professional-grade avionics and systems simulation suite designed for Boeing 737 cockpit builders. Version 3.x represents a major evolution with completely rewritten FMS, LNAV/VNAV systems, and enhanced realism. Version 3.35 is the latest Long-Term Support release featuring comprehensive system overhauls.

#### Latest Features in Version 3.35 (LTS 2025-2)

**Engine Model - Completely Redesigned**
- New engine model with dynamic oil simulation (oil no longer static)
- Completely new engine start logic with starter as discrete element
- Advanced engine failures triggered based on specific conditions when random failures are active
- Improved auto throttle logic based on N1 change instead of lever position
- Enhanced EGT behavior and monitoring

**Electrical System Expansion (Professional Version)**
- Over 150 new circuit breakers added
- All elements properly powered by correct source through CB integration
- Generator overvoltage failure capability
- Professional license required for hardware CB integration

**Flight Management System (FMS)**
- Completely new FMS implementation with advanced LNAV/VNAV engine
- Improved handling of offset legs and approach procedures
- Better idle descent segment creation logic
- Enhanced route tracking and navigation performance monitoring
- Actual Navigation Performance (ANP) and Required Navigation Performance (RNP) displays
- VNAV PATH overspeed protection
- Improved SID handling with runway transitions

**Autoflight & Flight Controls**
- Flight controls refactored to accommodate future improvements
- Improved autopilot pitch channel options
- Transient protection for autopilot disconnect warning
- Runaway trim failure capability (professional)
- Flap load relief logic improvements
- Yaw damper with WTRIS (Wind-up Turn Runway Incursion System) and +/-4000 VS limit

**GPWS & Warning Systems**
- Improved GPWS with MODE 4B linked to internal flap position
- SMART 500 call out option
- Enhanced takeoff configuration warning with PSEU, FSEU, and SMYD signals
- Unreliable airspeed cascading to autothrottle

**Systems Simulation**
- Over 200 modeled malfunctions for realistic training scenarios
- Pressurization system improvements with transient protection
- ADIRS refactored with ADIRUs added as discrete elements
- VOR signal distortion implementation
- Fire protection with improved overheat and fire detection
- RA (Radio Altimeter) partial failure modes

**Display & Audio Features**
- Manual V-speed indication improvements
- Increased hydraulic pressure responsiveness
- Display screen repositioning/resizing capability
- Cockpit environment sounds (oxygen masks, V-speed callouts, pack sounds, stick shaker)
- Voice ATIS functionality and SATCOM IO elements

**Communications**
- Full VHF range support with 833 spacing option
- CPDLC functionality through hoppie integration
- Enhanced Navigraph frequency handling

**Hardware Compatibility**
- Integrated MCP display (no longer requires separate module)
- Support for CPFlight V2 hardware and new ACP/SIDE panels
- Phidgets driver with VINT card support
- Broad compatibility with major hardware providers (Flightdeck Solutions, CPFlight, OpenCockpits, Simworld, Sismo)
- Full integration with Microsoft Flight Simulator 2020

#### Version History Highlights
- **v3.35 (Nov 2025)**: LTS release with engine model redesign and 150+ circuit breakers
- **v3.34 (May 2025)**: Engine start logic and electrical architecture modernization
- **v3.33 (Feb 2025)**: System stability and display improvements
- **v3.32 (Dec 2024)**: Autopilot enhancements and fire protection upgrades
- **v3.31 (Sep 2024)**: Autoflight refinements and SMART 500 callout
- **v3.30 (Jul 2024)**: FMS navigation and flight control improvements
- **v3.28 (Feb 2024)**: Yaw damper expansion and audio enhancements

#### Supported Aircraft Variants
- Boeing 737-700
- Boeing 737-800 (B738)
- Boeing 737-900
- Boeing 737 MAX (separate professional suite available)

## PC Hardware

### Multi-Computer Setup
The simulator runs on a distributed computing architecture with 3 dedicated PCs handling different aspects of the simulation for optimal performance.

### Main PC - Flight Simulation & Graphics
- **CPU:** AMD Ryzen 5 5300X
- **GPU:** AMD Radeon RX 6900 XT
- **RAM:** 32GB
- **Storage:**
  - 256GB NVMe SSD (Operating System)
  - 512GB SSD (Data Drive)

This powerful configuration delivers smooth frame rates and stunning visuals in MSFS 2020 while handling ProSim737's complex systems simulation.

## Cockpit Hardware

### Authentic Components

**Cockpit Seats**
- **OEM Original Boeing 737 American Airlines Cockpit Seats**
  - Genuine aircraft components providing authentic pilot positioning and comfort
  - Complete with original adjustment mechanisms and armrests
  - The foundation for proper ergonomics and immersion

### Primary Flight Controls & Displays

**Mode Control Panel (MCP)**
- **CPFlight MCP PRO**
  - Professional-grade autopilot control interface
  - Fully integrated with ProSim737
  - Realistic backlit displays and tactile controls

**Electronic Flight Instrument System**
- **CPFlight EFIS PRO**
  - Dual EFIS control panels for Captain and First Officer positions
  - Direct control over navigation display modes and settings
  - Professional-quality construction with authentic feel

**Throttle Quadrant**
- **Cockpit For You V3 Silver - Fully Motorized**
  - Complete thrust lever control with realistic resistance
  - Auto-throttle with motorized feedback
  - Includes speed brake, flap lever, and trim controls
  - Premium silver finish for authentic appearance

**Flight Management Computer**
- **OpenCockpits MCDU**
  - Full-featured flight management computer displays
  - Direct integration with ProSim737 FMS
  - Dual units for Captain and First Officer positions

### Communication & Audio Panel

**Radio/Nav/Audio Stack**
- Custom-built pedestal-mounted radio stack
- Laser-engraved professional panel for authentic appearance
- Arduino Mega controller running MobiFlight firmware
- Direct integration with ProSim737 systems
- Includes:
  - VHF communication radios
  - Navigation radios
  - Audio control panels
  - Transponder

### Interface & Control Systems

**Hardware Interface**
- **PoKeys Control Cards**
  - Professional-grade USB I/O interface cards
  - Handle all cockpit switches, buttons, and indicators
  - Low-latency communication with ProSim737
  - Expandable architecture for future additions

## Build Updates & Timeline

**September 2017** - Project Initiated
- Planning and design phase began
- Research into hardware options and simulator platforms
- Initial component sourcing 

[Link](url) and ![Image](src)
```

