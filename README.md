# led-chaser-board

<br/> what is it? a PCB with:
<br/> - resistors
<br/> - timers
<br/> - IC (integrated circuit) to control the LEDs
<br/> - LEDs
<br/> - capacitors

<br/> how does it work / how should you use it?
<br/> - *no firmware is required*, only a power source, if I recall correctly; the blinking should automatically start!

<br/> motivation for making it:
<br/> - as a beginner in terms of hardware projects, I thought it would be nice to make something simple for a moment before continuing onto more complicated PCB designs as well as other hardware things.

<img width="1234" height="1162" alt="3d model" src="https://github.com/user-attachments/assets/494d715c-9d9c-45b9-8bca-ea78d8e2b784" />

<br/> a mini project made with help from /stasis.hackclub.com/starter-projects/blinky
<br/>

<img width="540" height="828" alt="ledChaserZINE" src="https://github.com/user-attachments/assets/059f7ecf-85d0-4624-8e81-811c06dd5e1c" />


<br/>
<br/> image of pcb and shematics:
<img width="528" height="533" alt="schem" src="https://github.com/user-attachments/assets/0f92e338-a156-4fac-8f18-7795e5f3da4b" />
<br/>
<img width="869" height="495" alt="Sschem" src="https://github.com/user-attachments/assets/e07302e2-9751-4575-ad52-3fe36f4d3780" />


# BOM here:

| Reference             | Qty | Value       | Footprint                                         | Link                                                                 | Price    | Description                                  |
|-----------------------|-----|------------|---------------------------------------------------|----------------------------------------------------------------------|----------|----------------------------------------------|
| C1 | 1   | C_Polarized | Capacitor_THT:CP_Radial_D5.0mm_P2.00mm           | https://jlcpcb.com/partdetail/1875-0402B102K500NT/C1523            | 0.01 USD | Polarized capacitor |
| C2 | 1   | C           | Capacitor_THT:CP_Radial_D5.0mm_P2.00mm           | https://jlcpcb.com/partdetail/1875-0402B102K500NT/C1523            | 0.01 USD | Unpolarized capacitor |
| D1, D2, D3, D4, D5, D6, D7, D8, D9, D10 | 10  | LED         | LED_THT:LED_D3.0mm                               | https://sigmanortec.ro/en/led-5mm-white?SubmitCurrency=1&id_currency=3 | 0.07 USD | Light emitting diode |
| R1 | 1   | 470 Ω       | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | https://jlcpcb.com/partdetail/1800-RS06K910JT/C1448 | 0.01 USD | Resistor   |
| R2 | 1   | 50 kΩ       | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | https://jlcpcb.com/partdetail/1800-RS06K910JT/C1448 | 0.01 USD | Resistor   |
| R3 | 1   | 1 kΩ        | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | https://jlcpcb.com/partdetail/1800-RS06K910JT/C1448 | 0.01 USD | Resistor   |
| U1 | 1   | NE555P      | Package_DIP:DIP-8_W7.62mm                        | https://www.mouser.co.uk/ProductDetail/Texas-Instruments/NE555P    | 0.58 USD | Precision Timer (555 compatible, PDIP-8) |
| U2 | 1   | 4017        | footprintsthiss:N16                              | https://uk.rs-online.com/web/p/counter-ics/7320691                 | 1.30 USD | Johnson Counter (10 outputs)  |
| - | -  | - | - | - | Total ~ 2.9 USD | -  |
