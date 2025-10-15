# LFE5-Dev FPGA Board

## Memory
128 Mbit
LCSC Part: C408824
Link: https://www.lcsc.com/product-detail/C408824.html

265 Mbit
LCSC Part: C62381
Link: https://www.lcsc.com/product-detail/C62381.html

## Chip

Name: Lattice LFE5U-25F-6BG256C
LCSC Part: C1521614
Package: BG256 = 256-ball caBGA
Size: 14 x 14 mm
Ball-Pitch: 0.80 mm

For the Package information see section 94. in the `FPGA-DS-02053-8-5-Package-Diagram` document.
For Fully-Populated Ball-Grid Array example consult the section 4.10.16 in the `TN-02024-5-6-PCB-Layout` document.


Power Sequencing:
    Refer to the section 4. in the `FPGA-TN-02038-2-0-ECP5-and-ECP5-5G-Hardware-Checklist` document.


# Pin Map

## Bank0
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 0 | A2 | FIO:PT4A | |
| 0 | A3 | FIO:PT6A | |
| 0 | A4 | FIO:PT6B | |
| 0 | A5 | FIO:PT18A | |
| 0 | A6 | FIO:PT18B | |
| 0 | A7 | FIO:PT29A | PCLKT0_0 |
| 0 | A8 | FIO:PT29B | |
| 0 | B3 | FIO:PT4B | |
| 0 | B4 | FIO:PT11B | |
| 0 | B5 | FIO:PT15B | |
| 0 | B6 | FIO:PT22B | |
| 0 | B7 | FIO:PT27B | |
| 0 | C4 | FIO:PT11A | |
| 0 | C5 | FIO:PT15A | |
| 0 | C6 | FIO:PT22A | |
| 0 | C7 | FIO:PT27A | PCLKT0_1 |
| 0 | D4 | FIO:PT9B | |
| 0 | D5 | FIO:PT13B | |
| 0 | D6 | FIO:PT20B | |
| 0 | D7 | FIO:PT24B | GR_PCLK0_0 |
| 0 | E4 | FIO:PT9A | |
| 0 | E5 | FIO:PT13A | |
| 0 | E6 | FIO:PT20A | |
| 0 | E7 | FIO:PT24A | GR_PCLK0_1 |
| 0 | F6 | VCCIO0 | |
| 0 | F7 | VCCIO0 | |

## Bank1
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 1 | A9 | FIO:PT42A | |
| 1 | A10 | FIO:PT42B | |
| 1 | A11 | FIO:PT53A | |
| 1 | A12 | FIO:PT53B | |
| 1 | A13 | FIO:PT65A | |
| 1 | A14 | FIO:PT68B | |
| 1 | A15 | FIO:PT67B | |
| 1 | B8 | FIO:PT35B | |
| 1 | B9 | FIO:PT38A | GR_PCLK1_0 |
| 1 | B10 | FIO:PT44A | |
| 1 | B11 | FIO:PT49A | |
| 1 | B12 | FIO:PT56A | |
| 1 | B13 | FIO:PT60A | |
| 1 | B14 | FIO:PT67A | |
| 1 | C8 | FIO:PT35A | PCLKT1_0 |
| 1 | C9 | FIO:PT38B | GR_PCLK1_1 |
| 1 | C10 | FIO:PT44B | |
| 1 | C11 | FIO:PT49B | |
| 1 | C12 | FIO:PT56B | |
| 1 | C13 | FIO:PT60B | |
| 1 | D8 | FIO:PT33B | |
| 1 | D9 | FIO:PT40A | |
| 1 | D10 | FIO:PT47A | |
| 1 | D11 | FIO:PT51A | |
| 1 | D12 | FIO:PT58A | |
| 1 | D13 | FIO:PT62A | |
| 1 | E8 | FIO:PT33A | PCLKT1_1 |
| 1 | E9 | FIO:PT40B | |
| 1 | E10 | FIO:PT47B | |
| 1 | E11 | FIO:PT51B | |
| 1 | E12 | FIO:PT58B | |
| 1 | E13 | FIO:PT62B | |
| 1 | F10 | VCCIO1 | |
| 1 | F11 | VCCIO1 | |

## Bank2
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 2 | B15 | FIO:PR2B | S0_IN |
| 2 | B16 | FIO:PR2A | |
| 2 | C14 | FIO:PR2C | |
| 2 | C15 | FIO:PR5B | S1_IN |
| 2 | C16 | FIO:PR5A | S0_OUT |
| 2 | D14 | FIO:PR2D | |
| 2 | D16 | FIO:PR8A | |
| 2 | E14 | FIO:PR5C | |
| 2 | E15 | FIO:PR8B | |
| 2 | E16 | FIO:PR11D | |
| 2 | F12 | FIO:PR8D | |
| 2 | F13 | FIO:PR8C | |
| 2 | F14 | FIO:PR5D | |
| 2 | F15 | FIO:PR11C | |
| 2 | F16 | FIO:PR14A | S1_OUT |
| 2 | G12 | FIO:PR11A | |
| 2 | G13 | FIO:PR11B | |
| 2 | G14 | FIO:PR14C | VREF1_2 |
| 2 | G15 | FIO:PR14B | S2_IN |
| 2 | G16 | FIO:PR20A | GR_PCLK2_1 |
| 2 | H11 | VCCIO2 | |
| 2 | H12 | FIO:PR17A | |
| 2 | H13 | FIO:PR17B | |
| 2 | H14 | FIO:PR14D | |
| 2 | H15 | FIO:PR20B | |
| 2 | J11 | VCCIO2 | |
| 2 | J12 | FIO:PR17D | |
| 2 | J13 | FIO:PR17C | |
| 2 | J14 | FIO:PR20C | GR_PCLK2_0 |
| 2 | J15 | FIO:PR23B | PCLKC2_1 |
| 2 | J16 | FIO:PR23A | PCLKT2_1/S2_OUT |
| 2 | K14 | FIO:PR20D | |
| 2 | K15 | FIO:PR23D | PCLKC2_0 |
| 2 | K16 | FIO:PR23C | PCLKT2_0/S3_IN |

## Bank3
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 3 | K11 | VCCIO3 | |
| 3 | K12 | FIO:PR29B | |
| 3 | K13 | FIO:PR29A | GR_PCLK3_0 |
| 3 | L11 | VCCIO3 | |
| 3 | L12 | FIO:PR29D | |
| 3 | L13 | FIO:PR29C | GR_PCLK3_1 |
| 3 | L14 | FIO:PR32C | |
| 3 | L15 | FIO:PR26B | PCLKC3_1 |
| 3 | L16 | FIO:PR26A | PCLKT3_1/S3_OUT |
| 3 | M11 | FIO:PR47A | LRC_GPLL0T_MFGOUT1 |
| 3 | M12 | FIO:PR44C | LRC_GPLL0T_MFGOUT2 |
| 3 | M13 | FIO:PR35C | S5_IN |
| 3 | M14 | FIO:PR32D | |
| 3 | M15 | FIO:PR26D | PCLKC3_0 |
| 3 | M16 | FIO:PR26C | PCLKT3_0/S4_IN |
| 3 | N11 | FIO:PR47B | LRC_GPLL0C_MFGOUT1 |
| 3 | N12 | FIO:PR44D | LRC_GPLL0C_MFGOUT2 |
| 3 | N13 | FIO:PR38A | S5_OUT |
| 3 | N14 | FIO:PR35D | |
| 3 | N16 | FIO:PR32A | |
| 3 | P11 | FIO:PR47C | LRC_GPLL0T_IN |
| 3 | P12 | FIO:PR47D | LRC_GPLL0C_IN/S7_OUT |
| 3 | P13 | FIO:PR41A | S6_OUT |
| 3 | P14 | FIO:PR38B | S6_IN |
| 3 | P15 | FIO:PR32B | |
| 3 | P16 | FIO:PR35A | S4_OUT |
| 3 | R12 | FIO:PR44A | |
| 3 | R13 | FIO:PR41C | |
| 3 | R14 | FIO:PR41B | S7_IN |
| 3 | R15 | FIO:PR38C | |
| 3 | R16 | FIO:PR35B | VREF1_3 |
| 3 | T13 | FIO:PR44B | |
| 3 | T14 | FIO:PR41D | |
| 3 | T15 | FIO:PR38D | |

## Bank6
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 6 | J6 | VCCIO6 | |
| 6 | J7 | VCCIO6 | |
| 6 | K4 | FIO:PL29A | GR_PCLK6_0 |
| 6 | K5 | FIO:PL29B | |
| 6 | L1 | FIO:PL26A | PCLKT6_1 |
| 6 | L2 | FIO:PL26B | PCLKC6_1 |
| 6 | L3 | FIO:PL32C | |
| 6 | L4 | FIO:PL29C | GR_PCLK6_1 |
| 6 | L5 | FIO:PL29D | |
| 6 | M1 | FIO:PL26C | PCLKT6_0 |
| 6 | M2 | FIO:PL26D | PCLKC6_0 |
| 6 | M3 | FIO:PL32D | |
| 6 | M4 | FIO:PL35C | |
| 6 | M5 | FIO:PL44C | D9/IO9 |
| 6 | M6 | FIO:PL47A | LLC_GPLL0T_MFGOUT1 |
| 6 | N1 | FIO:PL32A | |
| 6 | N3 | FIO:PL35D | |
| 6 | N4 | FIO:PL38A | |
| 6 | N5 | FIO:PL44D | D8/IO8 |
| 6 | N6 | FIO:PL47B | LLC_GPLL0C_MFGOUT1 |
| 6 | P1 | FIO:PL35A | |
| 6 | P2 | FIO:PL32B | |
| 6 | P3 | FIO:PL38B | |
| 6 | P4 | FIO:PL41A | D13/IO13 |
| 6 | P5 | FIO:PL47D | LLC_GPLL0C_IN |
| 6 | P6 | FIO:PL47C | LLC_GPLL0T_IN |
| 6 | R1 | FIO:PL35B | VREF1_6 |
| 6 | R2 | FIO:PL38C | D15/IO15 |
| 6 | R3 | FIO:PL41B | D12/IO12 |
| 6 | R4 | FIO:PL41C | D11/IO11 |
| 6 | R5 | FIO:PL44A | LLC_GPLL0T_MFGOUT2 |
| 6 | T2 | FIO:PL38D | D14/IO14 |
| 6 | T3 | FIO:PL41D | D10/IO10 |
| 6 | T4 | FIO:PL44B | LLC_GPLL0C_MFGOUT2 |

## Bank7
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 7 | B1 | FIO:PL2A | |
| 7 | B2 | FIO:PL2B | |
| 7 | C1 | FIO:PL5A | |
| 7 | C2 | FIO:PL5B | |
| 7 | C3 | FIO:PL2C | |
| 7 | D1 | FIO:PL8A | |
| 7 | D3 | FIO:PL2D | |
| 7 | E1 | FIO:PL11D | |
| 7 | E2 | FIO:PL8B | |
| 7 | E3 | FIO:PL5C | |
| 7 | F1 | FIO:PL14A | |
| 7 | F2 | FIO:PL11C | |
| 7 | F3 | FIO:PL5D | |
| 7 | F4 | FIO:PL8C | |
| 7 | F5 | FIO:PL8D | |
| 7 | G1 | FIO:PL20A | GR_PCLK7_1 |
| 7 | G2 | FIO:PL14B | |
| 7 | G3 | FIO:PL14C | VREF1_7 |
| 7 | G4 | FIO:PL11B | |
| 7 | G5 | FIO:PL11A | |
| 7 | H2 | FIO:PL20B | |
| 7 | H3 | FIO:PL14D | |
| 7 | H4 | FIO:PL17B | |
| 7 | H5 | FIO:PL17A | |
| 7 | H6 | VCCIO7 | |
| 7 | H7 | VCCIO7 | |
| 7 | J1 | FIO:PL23A | PCLKT7_1 |
| 7 | J2 | FIO:PL23B | PCLKC7_1 |
| 7 | J3 | FIO:PL20C | GR_PCLK7_0 |
| 7 | J4 | FIO:PL17C | |
| 7 | J5 | FIO:PL17D | |
| 7 | K1 | FIO:PL23C | PCLKT7_0 |
| 7 | K2 | FIO:PL23D | PCLKC7_0 |
| 7 | K3 | FIO:PL20D | |

## Bank8
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 8 | L6 | VCCIO8 | |
| 8 | M7 | FIO:PB9B | D2/IO2 |
| 8 | M8 | FIO:PB15B | DOUT/CS0N/ATB_FORCE |
| 8 | M9 | FIO:PB18A | WRITEIN/ATB_SENSE |
| 8 | N7 | FIO:PB9A | D3/IO3 |
| 8 | N8 | FIO:PB15A | HOLDN/DI/BUSY/CSSPIN/CEN |
| 8 | N9 | CCLK | |
| 8 | N10 | CFG_0 | |
| 8 | P7 | FIO:PB6B | D4/MOSI2/IO4 |
| 8 | P8 | FIO:PB13B | CS1N |
| 8 | P9 | DONE | |
| 8 | P10 | CFG_1 | |
| 8 | R6 | FIO:PB4B | D6/IO6 |
| 8 | R7 | FIO:PB6A | D5/MISO2/IO5 |
| 8 | R8 | FIO:PB13A | SN/CSN/SCAN_SHFT_EN |
| 8 | R9 | PROGRAMN | |
| 8 | R10 | CFG_2 | |
| 8 | T6 | FIO:PB4A | D7/IO7 |
| 8 | T7 | FIO:PB11A | D1/MISO/IO1 |
| 8 | T8 | FIO:PB11B | D0/MOSI/IO0 |
| 8 | T9 | INITN | |

## Bank40
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| 40 | M10 | TDO | |
| 40 | R11 | TDI | |
| 40 | T10 | TCK | |
| 40 | T11 | TMS | |

## GND
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| NaN | A1 | GND | |
| NaN | A16 | GND | |
| NaN | D2 | GND | |
| NaN | D15 | GND | |
| NaN | F8 | GND | |
| NaN | F9 | GND | |
| NaN | G8 | GND | |
| NaN | G10 | GND | |
| NaN | H1 | GND | |
| NaN | H8 | GND | |
| NaN | H9 | GND | |
| NaN | H10 | GND | |
| NaN | H16 | GND | |
| NaN | J8 | GND | |
| NaN | J9 | GND | |
| NaN | J10 | GND | |
| NaN | K6 | GND | |
| NaN | K7 | GND | |
| NaN | K8 | GND | |
| NaN | K9 | GND | |
| NaN | K10 | GND | |
| NaN | N2 | GND | |
| NaN | N15 | GND | |
| NaN | T1 | GND | |
| NaN | T5 | GND | |
| NaN | T12 | GND | |
| NaN | T16 | GND | |

## VCC
| Bank | Pin | Pad Name | Dual Function |
|------|-----|----------|---------------|
| NaN | G6 | VCC | |
| NaN | G7 | VCC | |
| NaN | G9 | VCC | |
| NaN | G11 | VCCAUX | |
| NaN | L7 | VCCAUX | |
| NaN | L8 | VCC | |
| NaN | L9 | VCC | |
| NaN | L10 | VCC | |
