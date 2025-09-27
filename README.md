# Zoyi ZT-DQ02 LCR meter

LCR bridge and battery internal resistance tester (see [link](https://zotektools.com/products/zoyi-zt-dq02/)).

## SCPI commands

> Connect device to computer and press and hold the "HOLD/REC" key to enter the automatic measurement recording mode.

Those commands were extracted from firmware [v1.1.0](http://www.szzotek.com/h-col-159.html).

| Command | Example output | Comment |
| ---- | - | - |
| *CLS | | | 
| *ESE | | |
| *ESE? | | |
| *ESR? | | |
| *IDN? | ZOYI,ZT-DQ02,903D9C87,V1.1.0 | Get device identity |
| *OPC | | |
| *OPC? | | |
| *RST | | |
| *SRE | | |
| *SRE? | | |
| *STB? | | |
| *WAI | | |
| *TST? | | |
| :STATus:OPERation? | 0 | |
| :SYST:ERR?| 0,"No error" | |
| :SYSTem:ERRor:NEXT? | 0,"No error" | |
| :SYSTem:ERRor:ALL? | 0,"No error" | |
| :SYSTem:ERRor:CLEAR | | |
| :SYSTem:ERRor:COUNt? | 0 | |
| :SYSTem:ERRor:CODE? | 0 | |
| :SYSTem:ERRor:CODE:NEXT? | 0 | |
| :SYSTem:ERRor:CODE:ALL? | | |
| :SYSTem:VERSion? | 1999.0 | |
| :STATus:OPERation:EVENt? | 0 | |
| :STATus:OPERation:CONDition? | 0 | |
| :STATUS:OPERation:ENABle? | 65535 | |
| :STATUS:OPERation:ENABle PARAM | |
| :STATus:QUEStionable? | 0 | |
| :STATus:QUEStionable:EVENt? | 0 | |
| :STATus:QUEStionable:CONDition? | 0 | |
| :STATus:QUEStionable:ENABle? | 65535 | |
| :STATus:QUEStionable:ENABle PARAM | | |
| :STATus:PRESet | | |
| :FETCh? | 100.05,-0.0101,R,R,X,SER,SER,SLOW,AUTO,1000,600,0,0,R,1.0000e3,5.0,0 | Get readings |
| :FREQuency? | | |
| :FREQuency | | Cycle `Freq` between 100Hz/120Hz/1kHz/10kHz/100kHz |
| :VOLTage? | | |
| :VOLTage | | Cycle `Level` between 0.1V/0.3V/0.6V |
| :BIAS:VOLTage? | | |
| :BIAS:VOLTage | | Cycle `Bias` between 0.0V/0.5V and will affect `Level` |
| :APERture? | | |
| :APERture | | Cycle `Speed` between Slow/Mid/Fast |
| :FUNCtion:IMPedance:MAIN? | | |
| :FUNCtion:IMPedance:MAIN | | Cycle `Function` between AUTO/R/C/L/Z/ECAP/BATT |
| :FUNCtion:IMPedance:SUB? | | |
| :FUNCtion:IMPedance:SUB | | Cycle `Sub-function` X/D/Q/θ/ESR |
| :FUNCtion:IMPedance:Model? | | |
| :FUNCtion:IMPedance:Model | | Cycle `Model` between AUTO/SER/PAR |
| :FUNCtion:IMPedance:RANGe? | | |
| :FUNCtion:IMPedance:RANGe | | Cycle `Range` between AUTO/100Ω/1kΩ/10kΩ/100kΩ |
| :COMParator? | | |
| :COMParator | | Enable comparator mode |
| :COMParator:NOMinal? | | |
| :COMParator:RANGe? | | |
| :COMParator:RESult? | | |
| :COMParator:NOMinal PARAM | | Example: `:COMParator:NOMinal 100` will set 100 Ohm as nominal value |
| :COMParator:ERRor PARAM | | Example: `:COMParator:ERRor 0.1` will set 0.1% as tolerance value |
