# Carrera-D143-car-decoder
Customized firmware for the Carrera Digital 143 decoder. The base is firmware from https://github.com/azya52/carrera. All functions work with CU 30352. 
Other features: 
-  Setting from CU 30352 Ghost car funciton
-  Front light support.
-  Break light support
-  Custom Speed Curves are stored in EEPROM

  :100000000004000000FFFFFFFFFFFFFFFFFFFFFFF7<br/>
  :1000100000050A14191E23282D32373C46505A6E0B<br/>
  :10002000000A141F29333D47525C66707C858F9906<br/>
  :1000300000262E38414D555E67727C858E97A1B3A0<br/>
  :1000400000112233445566778899AABBCCDDEEFFB8<br/>
  :1000500000020D18232E39444F5A697D96AFD2FF06<br/>
  :10006000FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFA0<br/>
  :10007000FFFFFFFFFFFFFFFFFFFFFFFF1004005325<br/>
  :00000001FF<br/>

-  A calibration value must be stored at 0x7f

  A lot depends on calibration. I use https://github.com/felias-fogg/avrCalibrate for calibration. They set a calibration value of 1200000 not 1000000.


# Wiring
<p align="center">
  <img src="./blob/main/pics/Schema.png" width="350" title="hover text">
</p>


