## Welcome to b737 project

In a next few years I would like to build real as possible (on my budget) replica of Boeing 737 cockpit. I want to use some plug and play components, but include also my own made parts and devices.


## Software

### Flight Simulators
- Prepar 3D v5.2
- MSFS 2020

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
- Compatible with Prepar3D v5 and Microsoft Flight Simulator 2020

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

3 x Intel PC

### Main PC
- Intel 7700k CPU
- 32GB ram
- 256GB OS nvme
- 512gb ssd data drive

## Cockpit hardware
- Pokeys control cards
- MCP PRO from CPFlight
- EFIS PRO from CPFlight
- Throttle Quadrant - motorised, v3 silver from Cockpit For You 
- MCDU - OpenCockpits
- Pedestal radio/nav/audio stack based on laser engraved panel and arduino mega connected by mobiflight to prosim.
- 
## Build updates

- 09.2017 - Work started. 

[Link](url) and ![Image](src)
```

