# BluePillPowerAttack
Glitch power attack ported to blue pill from https://github.com/JohannesObermaier/f103-analysis/tree/master/h3
where the other needeed resources are found.
Updated connections:

Connect button on gpio A0.

bluepill 	<-> 	DuT<br />
B0+B1		  <->	  3V3 (Power input)<br />
B2		    <->	   BOOT0<br />
B4		    <->	  ~RESET<br />

external swc	<->	SWD-Clock<br />
external swc	<->	SWD-Data<br />

external serial tx		<->	PA10 (RX)<br />
external serial rx		<->	PA9 (TX)<br />





