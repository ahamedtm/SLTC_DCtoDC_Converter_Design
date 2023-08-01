# SLTC_DCtoDC_Converter_Design

**DC-DC converter design**
**A detailed guide to designing a DC-DC converter based on a commercial IC is available from video 1**

https://www.youtube.com/watch?v=qGp82xhybs4

**Things to consider when choosing a DC-DC converter chip are detailed in video 2**

https://www.youtube.com/watch?v=-V_p1GBH4pk

**Instructions and problems faced in measuring DC-DC converter efficiency is discussed in the following videos 3 and 4**

https://www.youtube.com/watch?v=li0XKnpOZyM

https://www.youtube.com/watch?v=8ldLaDN8SQs

Steps as follows:

1.	For the application in Video 2, compare two chips with the chosen chip and explain using efficiency vs load current graphs the rationale for the choice.
   
Specifications for your DC-DC converter design are as follows; (Any Random Number: XYZ)

Input voltage – (Y + Z/10) volts +/- 10%

Load current - 50*Z milliamperes

Output voltage is three times the input voltage

Switching frequency – choose the maximum of the controller

2.	Calculate inductor and output capacitor values.
   
4.	Calculate inductor and output capacitor values based on the controller datasheet equations following the instructions given in Video 1.
   
6.	Identify the safety margins introduced by the chip manufacturer for inductor and capacitor values
   
8.	Calculate the worst-case switch power dissipation and output capacitor power dissipation by choosing a polymer capacitor from digikey, mouser or Cornell Dubilier aluminium polymer capacitors.
   
10.	Estimate worst case overall efficiency assuming chip quiescent current and other losses are negligible.
    
12.	Does the efficiency values match data sheet values. Comment on the chip power consumption and other component losses
    
14.	The four-wire efficiency measurement technique as explained in Video 3 and 4.
    
16.	How connecting-wire resistances can affect calculated efficiency value if power supply and electronic load V/I display values used for calculations.
    
18.	How to overcome the above error.
