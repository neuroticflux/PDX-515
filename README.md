# PDX-515
Modular synth power supply + distribution board

Power supply with space and mounting hole for ~80VA toroid 15-0-15 transformer.

Use LM317T/LM337T regulators for ~1A on each rail.

+5V is taken from the +15V rail after regulating, to avoid massive heat dissipation on the 5V regulator,
so the +5V is to be used sparingly.

Screw terminals are also known as Phoenix connectors (the green ones). Use appropriate size wiring for connection to the distribution board.

BUILD THIS AT YOUR OWN RISK! I take no responsibility if you burn your house down, electrify yourself or destroy your equipment.

PLAYING WITH HIGH VOLTAGES IS DANGEROUS! Don't build this if you're not absolutely sure what you're doing!

BOM:

RefDes                	Name   	Value 	Quantity

C1, C2, C3,
C4, C5, C6		      		CAP    	3300uF	6      
C7, C8                	CAP    	100nF 	2    
C9, C10, C11,
C12   				        	CAP    	22uF  	4     
C13, C14,
C15         			      CAP    	10uF  	3   
D1                    	GBPC6  	      	1   
D2, D3, D4,
D5, D6, D7			      	DIODE  	1n4004	6  
D8, D9, D10           	LED    	      	3   
J1, J2                	SCREW T	X2    	2  
J3                    	SCREW T	X4    	1  
R1, R3                	RES500 	3k    	2       
R2                    	RES500 	820   	1       
R4, R5, R6            	RES500 	270   	3       
R7, R8                	RES500 	1k2   	2       
R9                    	RES500 	150   	1       
U1, U2                	LM317T 	      	2       
U3                    	LM337T 	      	1       
