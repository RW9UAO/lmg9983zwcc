# lmg9983zwcc
lmg9983zwcc LCD datasheet

hello!
this page about LCD from IBM Thinkpad 380(ED maybe)

LCD connector

1	GND
2	Pixel clock
3	GND
4	VCC
5	VCC
6	First Line Marker
7	Data Latch
8	GND
9	UD7
10	LD3
11	UD5
12	GND
13	UD2
14	UD6
15	LD0
16	GND
17	UD4
18	LD6
19	LD7
20	UD1
21	LD2
22	GND
23	LD5
24	LD4
25	UD3
26	GND
27	UD0
28	LD1
29	Enable
30	GND
31	Vcont


MB connector
1		              2	
3		              4	
5	GND	            6	Pixel clock
7	GND	            8	VCC
9	VCC	            10	
11	GND	          12	vcc2
13	vcc2	        14	
15	FLM	          16	Data Latch
17	GND	          18	UD7
19	LD3	          20	UD5
21	GND	          22	UD2
23	UD6	          24	LD0
25	GND	          26	UD4
27	LD7	          28	LD6
29	GND	          30	UD1
31	LD2	          32	
33	LED green "-"	34	
35		            36	LD5
37	LD4	          38	UD3
39		            40	UD0
41	LD1	          42	
43	LED "+"	      44	
45	Enable	      46	GND
47		            48	
49		            50	GND
51		            52	LCD dimming
53		            54	GND
55	GND	          56	GND
57	12 volt	      58	12 volt
59	12 volt	      60	12 volt

notes:
- 1, 2, 3, 4 goes to mainboard and not used in this LCD
- LCD cable has 3 leds - i seek common anode and one of cathode.
- vcc2 - not not used in this LCD, but has on mainboard
- 12 volts on backlight converter - maybe it 16-19 volts
- LCD Vcont goes direct to backlight converter
- all timing and pixels take from LMG9980
