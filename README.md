# LFE5-Dev FPGA Board

FPGA developement board featuring Lattice LFE5U-25F-6BG256C Chip, memory and programming interface. 

## FPGA

* Name: Lattice LFE5U-25F-6BG256C
* LCSC Part: C1521614
* Package: BG256 = 256-ball caBGA
* Size: 14 x 14 mm
* Ball-Pitch: 0.80 mm

### Power Consumptions and Management

- Typical values are provided unless other specified

* Core Supply Voltage (Vcc): 1.1 V ±5% 
* Auxiliary Supply Voltage (Vccaux): 2.5 V ±5%
* Note Vccaux ramp rate < 30 mV/µs during power-up transition from 0 V to 3 V
* I/O Driver Supply Voltage (VccioX): 3.3 V ±5%
where `X` is the Bank number

* Core Power Supply Current: 77 mA
* Auxiliary Power Supply Current: 16 mA
* Bank Power Supply Current (Per Bank): 0.5 mA
* per-pin average current budget: TODO


### Programming and Interfaces


### Additional Info

* For the Package information see section 94. in the `FPGA-DS-02053-8-5-Package-Diagram` document.

* For Fully-Populated Ball-Grid Array example consult the section 4.10.16 in the `TN-02024-5-6-PCB-Layout` document.

* For Power Sequencing Refer to the section 4. in the `FPGA-TN-02038-2-0-ECP5-and-ECP5-5G-Hardware-Checklist` document.

## DC-DC conversion

* Input Voltage: 5 V (USB)

1.1 V (Vcc) dc-dc converter
* Part Number: TLV62568DBVR
* LCSC Part: C163219
* Soft Start time: 700 µs

2.5 V (Vccaux) dc-dc converter 
* Part Number: TLV70425DBVR (or TLV70225DBVT) or TLV70225DSER
* LCSC Part: C66350 (or C2863504)
* Soft Start time: 100 µs

3.3 V (VccioX) dc-dc converter 
* Part Number: TLV70425DBVR (or TLV70225DBVT)
* Part Number: TLV62568DBVR
* LCSC Part: C163219

## Memory
128 Mbit
LCSC Part: C408824
Link: https://www.lcsc.com/product-detail/C408824.html

265 Mbit
LCSC Part: C62381
Link: https://www.lcsc.com/product-detail/C62381.html

512K x 16 Low Voltage Ultra Low Power CMOS Static RAM:
LCSC Part: C11315
Link: https://www.lcsc.com/product-detail/C11315.html

256Mbit 3V~3.6V 166MHz TSOPII-54-10.2mm Memory (ICs) ROHS:
LCSC Part: C97572
Link: https://www.lcsc.com/product-detail/C97572.html

## Useful Info

* ECP5 Aliexpress-Dev board: https://tomverbeure.github.io/2021/01/22/The-Colorlight-i5-as-FPGA-development-board.html

* i5 Ethernet Adapter Board: https://github.com/kazkojima/colorlight-i5-tips#ethernet
