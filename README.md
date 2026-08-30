# PCB Design & Embedded Systems Portfolio

## 👋 About Me
I am an aspiring hardware engineer focused on PCB design, soldering theory, and embedded systems.  
This repository documents my structured, hands-on learning journey through progressively complex hardware projects.

## 🚀 Roadmap
This portfolio follows a structured 6-month plan to design and develop PCB projects with increasing complexity, covering both hardware and embedded systems.

## 🎯 Objective
To build a strong foundation in:
- Power electronics
- Analog circuit design
- Microcontroller-based systems
- Communication interfaces (I2C, SPI, UART)
- IoT system design

## 🛠️ Tools & Technologies
- PCB Design: KiCad  
- Programming: Embedded C  
- Simulation: LTspice  
- Hardware: Microcontrollers, sensors, power circuits  

## 📂 Projects

### 1. AC to DC Capacitive Power Supply
🟢 Status: Completed  
- Non-isolated AC-DC conversion  
- Bridge rectifier using 1N4007 diodes  
- Capacitive dropper design  
- Zener diode voltage regulation (6.2V)  
- Protection: Fuse, bleeder resistor  

➡️ [View Project](./01_power_supply_board)

---

### 2. Sound Level Indicator / Dancing LEDs
🟢 Status: Completed  

A transistor-based audio reactive LED indicator circuit designed to visualize sound intensity levels using multiple transistor switching stages.

#### Features
- Audio signal amplification
- Multi-stage transistor switching
- Progressive LED indication
- Adjustable sensitivity control
- Ground pour based PCB design
- 3D PCB render and KiCad source files included

#### Key Learnings
- Analog signal processing
- PCB grounding techniques
- ERC/DRC debugging in KiCad
- Trace width and power routing considerations

➡️ [View Project](./02_Sound_level_indicator)

---

### 3. Logic-Level N-Channel MOSFET Load Switch
🟢 Status: Completed  

Designed and developed a compact Logic-Level N-Channel MOSFET Load Switch in KiCad to control a 12 V DC load using a 5 V logic input. The project demonstrates low-side switching using an IRLZ44N logic-level N-channel MOSFET and incorporates essential protection circuitry for reliable operation. 

#### Key Learnings
- Designed a low-side switching circuit using the IRLZ44N logic-level N-channel MOSFET.
- Implemented gate protection using a 100 Ω gate resistor and a 10 kΩ gate pull-down resistor.
- Integrated a 1N4007 flyback diode to protect the MOSFET from inductive voltage spikes.
- Designed a compact 40 × 40 mm single-layer PCB with optimized component placement and bottom-layer routing.
- Strengthened understanding of power electronics, logic-level MOSFET operation, and single-layer PCB layout optimization in KiCad.

➡️ [View Project](./03_logic_level_mosfet_load_switch)

---

### 4. PWM Motor Controller
🟢 Status: Completed

Designed and developed a compact PWM Motor Controller using the NE555 timer IC to regulate the speed of a 12 V DC motor. The project generates a variable PWM signal with an adjustable duty cycle and uses an IRLZ44N logic-level MOSFET for efficient motor switching. The design also incorporates protection circuitry and PCB layout techniques for reliable operation.

#### Features
- NE555-based PWM signal generation
- Adjustable duty cycle using a 100 kΩ potentiometer
- IRLZ44N logic-level MOSFET motor driver
- Reverse polarity protection
- Flyback diode protection for inductive loads
- Compact PCB layout with optimized power routing
- 3D PCB render and KiCad source files included

#### Key Learnings
- Designed a PWM motor control circuit using the NE555 timer in astable mode.
- Learned how steering diodes enable independent capacitor charging and discharging for PWM duty-cycle control.
- Implemented MOSFET gate drive circuitry with appropriate gate resistor and pull-down resistor.
- Integrated reverse polarity and flyback protection to improve circuit reliability.
- Improved PCB layout skills by optimizing component placement, power trace routing, and decoupling capacitor placement. 

➡️ [View Project](./04_PWM_Motor_Controller)

---

### 5. MCU Development Board
🔵 Status: Planned

A custom microcontroller development board designed to strengthen my embedded systems and PCB design skills. The project will focus on schematic design, PCB layout, programming interfaces, power regulation, and peripheral integration.

#### Planned Features
- Microcontroller-based embedded system
- On-board voltage regulation
- Programming and debugging interface
- GPIO expansion headers
- Status LEDs and user input
- Compact PCB layout

---

## 📈 Learning Focus
- PCB layout best practices  
- Soldering theory and reliability  
- Embedded firmware development  
- Hardware debugging techniques  

## 💡 Key Learnings So Far
- AC to DC conversion using passive components
- Analog signal amplification using transistor stages
- Multi-stage transistor switching concepts
- Logic-level MOSFET switching and power electronics fundamentals
- PWM generation and DC motor speed control using the NE555 timer
- Reverse polarity and flyback protection techniques for reliable circuit operation
- High-voltage protection and safety considerations
- Importance of grounding and copper pours in PCB design
- PCB trace width optimization for signal and power routing
- Component placement and routing strategies for through-hole PCBs
- ERC/DRC debugging and schematic verification in KiCad
- Project documentation and version management using GitHub

## 📌 Note
This portfolio is actively maintained and updated as I continue to design, test, and improve hardware systems.
