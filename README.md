# Linux Based Compute Module Carrier Board Design and Development
#### Client Name: Darren Torres

## Project Requirements
Below are the core feature requirements:
- Compute Module: Compatible with a Linux-based compute module (e.g., Raspberry Pi CM5 or similar)
- RAM: 8GB of the highest performing supported RAM
- Storage: Onboard 64GB eMMC
- Connectivity: USB 3.0 (2), HDMI output, 4 lane MIPI (2), PCIe, Bluetooth, and Wi-Fi
- Display: Support for a BTT Pi TFT70 display using DSI with ribbon cable to first MIPI
- Camera: Connected over CSI-2 and ribbon cable to second MIPI
- Stepper Motor Control: Support for 4 x NEMA 8 stepper motors with corresponding drivers
- End Stops: 4 x end-stop inputs
- LED: 1 x LED with forward current of 700mA and forward voltage of 3.1V
- Valve Control: 7 x MOSFET drivers to control 3-way solenoid valves
- Fan Control: 1 x PWM-controlled fan output. A fan has not yet been selected.
- Power Management: Proper voltage regulation and power delivery for all components. 12v adapter is acceptable.
- Power Button: Power on / off device. Toggle switch may be best.
- PCB Form Factor: Compact and well-organized layout for ease of integration
- Interfaces: GPIOs for additional expandability
