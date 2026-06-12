
# Personal-LoRa-Module
A small compact module made to transmit and receive messages using sub gigahertzs frequencies of radio waves, for use in things such as automation, transmission, reception etc. I wanted to build this for a long time, because I want to implement noise pollution control using these modules, where one module will monitor honking >3 seconds and relay the information of the defaulter's vehicle to the receiver and fine the defaulter.

My LoRa module uses Sub GHz frequencies to tranceive radio waves. It uses the following components:
1. SX1262IMLTRT for transmission and reception.
2. RP2040 for Programing it for various applications.
3. 0900FM15D0039E as an RF filter.
4. AP2112K-3.3 as my LDO.
5. PE4259 as my RF switch.
6. Two quartz timer crystals (12 MHz and 32 MHz).
7. SMD Resistors.
8. SMD Capacitors.
9. SMD Inductors.
10. USB-C Receptacle.

Here is the Schematic:
<img width="1086" height="733" alt="Screenshot 2026-04-15 194307" src="https://github.com/user-attachments/assets/4da38773-7bd5-4c5d-aa47-90e53d503b8b" />



Here is the PCB:
<img width="1920" height="1020" alt="Screenshot 2026-04-15 192519" src="https://github.com/user-attachments/assets/9f4c0ebe-69f9-4099-acc9-b741a13f166a" />


Here is the assembled PCB:
<img width="578" height="742" alt="Screenshot 2026-04-15 194323" src="https://github.com/user-attachments/assets/8e71cee6-5110-4153-9107-d9d16bd7431e" />

[Lora-BOM-2.csv](https://github.com/user-attachments/files/28879576/Lora-BOM-2.csv)
Please find the BOM and Firmware along with a 3D STEP file for my assembled PCB in my repo.
