2200087-Serial-Protocol
=======================

|         | Bit 7 | Bit 6 | Bit 5 | Bit 4 | Bit 3      | Bit 2    | Bit 1     | Bit 0    | 
|---------|-------|-------|-------|-------|------------|----------|-----------|----------| 
| Byte 1  | 0     | 0     | 0     | 1     | Minus      | AC       | SEND      | AUTO     | 
| Byte 2  | 0     | 0     | 1     | 0     | Continuity | Diode    | Low Batt  | Hold     | 
| Byte 3  | 0     | 0     | 1     | 1     | MAX        | E4       | F4        | A4       | 
| Byte 4  | 0     | 1     | 0     | 0     | D4         | C4       | G4        | B4       | 
| Byte 5  | 0     | 1     | 0     | 1     | DP3        | E3       | F3        | A3       | 
| Byte 6  | 0     | 1     | 1     | 0     | D3         | C3       | G3        | B3       | 
| Byte 7  | 0     | 1     | 1     | 1     | DP2        | E2       | F2        | A2       | 
| Byte 8  | 1     | 0     | 0     | 0     | D2         | C2       | G2        | B2       | 
| Byte 9  | 1     | 0     | 0     | 1     | DP1        | E1       | F1        | A1       | 
| Byte 10 | 1     | 0     | 1     | 0     | D1         | C1       | G1        | B1       | 
| Byte 11 | 1     | 0     | 1     | 1     | Percent    | HFE      | Rel Delta | MIN      | 
| Byte 12 | 1     | 1     | 0     | 0     | u (1e-6)   | n (1e-9) | dBm       | Seconds  | 
| Byte 13 | 1     | 1     | 1     | 1     | Farads     | Amps     | Volts     | m (1e-3) | 
| Byte 14 | 1     | 1     | 1     | 0     | Hz         | Ohms     | K (1e3)   | M (1e6)  | 
