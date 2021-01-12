# BluePillPowerAttack
Glitch power attack ported to blue pill from [url]https://github.com/JohannesObermaier/f103-analysis/tree/master/h3[/url]
where the other needeed resources are found.
Updated connections:

Connect button on gpio A0.

bluepill 	<-> 	DuT
B0+B1		  <->	  3V3 (Power input)
B2		    <->	   BOOT0
B4		    <->	  ~RESET

external swc	<->	SWD-Clock
external swc	<->	SWD-Data

external serial tx		<->	PA10 (RX)
external serial rx		<->	PA9 (TX)





