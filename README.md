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
| *IDN? | ZOYI,ZT-DQ02,903D9C87,V1.1.0 | |
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
| :FETCh? | 100.05,-0.0101,R,R,X,SER,SER,SLOW,AUTO,1000,600,0,0,R,1.0000e3,5.0,0 | |
| :FREQuency? | | |
| :FREQuency | | Change `Freq` |
| :VOLTage? | | |
| :VOLTage | | Change `Level` |
| :BIAS:VOLTage? | | |
| :BIAS:VOLTage | | Change `Bias` |
| :APERture? | | |
| :APERture | | Change `Speed` |
| :FUNCtion:IMPedance:MAIN? | | |
| :FUNCtion:IMPedance:MAIN | | Change `Function` |
| :FUNCtion:IMPedance:SUB? | | |
| :FUNCtion:IMPedance:Model? | | |
| :FUNCtion:IMPedance:Model | | Change `Model`|
| :FUNCtion:IMPedance:RANGe? | | |
| :FUNCtion:IMPedance:RANGe | | Change `Range` |
| :COMParator? | | |
| :COMParator | | |
| :COMParator:NOMinal? | | |
| :COMParator:NOMinal PARAM | | |
| :COMParator:RANGe? | | |
| :COMParator:RESult? | | |
| :COMParator:ERRor PARAM | | |
| :USeRERRor | | |
| :DATA:BLOB PARAM | | |