# 555_Blink-a-Tron
Surface Mount device practice soldering activity.
Blink LEDS without logic using 555 timer + TLC5916 LED driver: 
PCB layout for this TI whitge paper: https://www.ti.com/lit/an/slva346/slva346.pdf?ts=1731359344476&ref_url=https%253A%252F%252Fwww.google.com%252F

<img width="1097" height="1080" alt="5 Clean (high res)" src="https://github.com/user-attachments/assets/3ce16168-d99e-4c1f-a4ce-fa713177b890" />

## Bill of Materials (BOM)

| Reference     | Value       | Footprint                                             | Qty | DigiKey P/N          |
|---------------|-------------|--------------------------------------------------------|-----|-----------------------|
| BT1           | Battery     | Battery:BatteryHolder_Keystone_1058_1x2032            | 1   | BU2032SM-GCT-ND       |
| C1, C2, C3    | 0.1uF       | Capacitor_SMD:C_1206_3216Metric                        | 3   | 1292-1605-1-ND        |
| C4            | 1uF         | Capacitor_SMD:C_1206_3216Metric                        | 1   | 1276-1068-1-ND        |
| D1–D8         | D           | Diode_SMD:D_1206_3216Metric                            | 8   | 67-1359-1-ND          |
| R1            | 37.4k       | Resistor_SMD:R_1206_3216Metric                         | 1   | 311-37.4KFRCT-ND      |
| R2            | 20k         | Resistor_SMD:R_1206_3216Metric                         | 1   | 311-20.0KFRCT-ND      |
| R3            | 3k – 6k     | Resistor_SMD:R_1206_3216Metric                         | 1   | 311-6.2KERCT-ND       |
| SW1           | SW_Push     | Button_Switch_SMD:SW_SPST_Omron_B3FS-100xP            | 1   | CKN12221-1-ND         |
| U1            | ICM7555xB   | Package_SO:SOIC-8_3.9x4.9mm_P1.27mm                    | 1   | 296-1336-1-ND         |
| U2            | TLC5916     | Package_SO:SOIC-16_3.9x9.9mm_P1.27mm                   | 1   | 296-22710-1-ND        |

