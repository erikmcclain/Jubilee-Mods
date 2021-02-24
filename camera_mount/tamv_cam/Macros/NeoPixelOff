	;Parameters
	;Rnnn Red component
	;Unnn Green component
	;Bnnn Blue component
	;Wnnn White component (Marlin)
	;Pnnn Brightness (0-255) (Marlin, also RepRapFirmware 2.03 and later)
	;P Set full brightness (Marlin)
	;Snnn (RepRapFirmware) Number of individual LEDs to set to these colours
	;Fn (RepRapFirmware) Following command action. F0 (default) means this is the last command for the LED strip, 
		;so the next M150 command starts at the beginning of the strip. F1 means further M150 commands for the remainder of the strip follow this one.
	;Xn (RepRapFirmware) LED type: X0 (default) = DotStar, X1 = NeoPixel. This parameter is remembered from one call to the next, so it only needs to be given once.
	;Ynn (RepRapFirmware) Brightness, 0-31 (alternative to P 0-255)
	;Qnnn (RepRapFirmware) Use specified SPI frequency (in Hz) instead of default frequency. 
		;This parameter is only processed if X parameter also present. When using NeoPixels, only frequencies between about 2.5MHz and 4MHz will work.
	;Example
	;M150 R255 U128 B192
	;Example (RepRapFirmware)
	;M150 X1 F3000000         ; set LED type to NeoPixel and set SPI frequency to 3MHz
	;M150 R255 P128 S20 F1    ; set first 20 LEDs to red, half brightness, more commands for the strip follow
	;M150 U255 B255 P255 S20  ; set next 20 LEDs to cyan, full brightness, finished programming LED strip


M150  Y0 S16 F0

