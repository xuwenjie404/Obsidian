In most applications, the conventional boost PFC is commonly used as it is simple to design. This topology has a few limitations in charging the battery packs for EVs. They are:
1. This topology has a efficient operation for low to medium power range, up to 1 kW. As the power level increases, the circuit control and sensing complexity level also increases.
3. The input diode bridge (D1-D4) degrades the performance of converter when the power level increases since the reverse recovery time of the input diodes causes more heat dissipation over an area, which is problematic. 
3. The only parasitic capacitance that contributes to CM noise is drain-to-ground capacitance of MOSFET.
4. The volume of inductor design also becomes a problematic at high power levels.
5. The voltage stress on conventional boost devices is high    
6. The reverse recovery current of the diode (DF) during the turn on of the MOSFET creates a sudden shoot-through in the output capacitor and causes more EMI in the circuit due to negative spikes in the diode current .

![[Pasted image 20231107182735.png]]


In addition to the above limitations,conventional boost PFCs have high switching and conduction losses.

![[Pasted image 20231107182810.png]]