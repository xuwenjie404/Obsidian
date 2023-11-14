
#SST
#Power-Electronic

Based on the availability of the dc-link capacitors at either side of the high-frequency magnetic core, there are four categories of SSTs.

### Pro
- alvanic isolation,which may be required in practice for safety and leakage current reasons
- The need to minimize injected dc current to the grid can also necessitate a line-frequency transformer.
### Cons
- achieving such significant core size reduction in SSTs comes with the expense and losses of two frequency converters


![[Pasted image 20231111212805.png]]

## Type A 
#Single-stage
This topology achieves a direct ac–ac conversion without using any dc decoupling capacitor. Solutions in the Type A category, 
#### Pros
- owing to their simple configuration, are lightweight and low-cost. 
- Besides, the lack of an HVdc capacitor prevents the use of established multilevel converters at the HV side (discussed in Section VI) and, thus, limits the HV range of the SST.
### Cons
- unable to provide reactive power support and disturbance decoupling between the two sides due to the lack of dc capacitors
- the lack of dc-link at the LV side makes it difficult to integrate renewable sources and batteries. 
- the lack of an HVdc capacitor prevents the use of established multilevel converters at the HV side，thus, limits the HV range 
## Type B:
#two-stage
### Pros
- Because of the addition of an LVdc capacitor, reactive power control functioning and disturbance isolation are restored, and batteries can readily be connected to this capacitor. 
### Cons
- similar to Type A, HV applications remain a drawback.

## Type C:
#two-stage
### Pros
- Same as Type B, the presence of an HVdc capacitor enables reactive power control and disturbance isolation. 
-  this topology is more suitable for HV applications compared to Types A and B.
### Cons
-  integration of batteries becomes challenging, which is a significant drawback considering that facilitating grid integration of renewables and batteries

## Type D:
#three-stage
### Pros
- Among all the mentioned variants, Type D with both HVdc and LVdc capacitors is the one with the most control functions and popularity. 
- Owing to the advantages of having both LVdc and HVdc capacitors, normally, SSTs for field applications are of this type.


### Cons
- However, since it is a three-stage topology, it is more complex and has a higher cost than the other solutions. 



From the perspective of the battery storage, the part that matters is the dc–dc converter Section of the SST. This dc–dc converter provides isolation and dc voltage boosting to connect an LV battery bank to the dc-link of any of the grid-connected dc–ac converters discussed previously. For high-power applications, the popular topology of choice is called dual active bridge (DAB) [126], as shown in Fig. 14. Recent advancements in high-power wide bandgap semiconductor technology offer the opportunity to design more compact and higher efficiency DABs [127], [128]. As an example, Fig. 15 shows the size comparison between a conventional Si IGBT and SiC MOSFET switches [123].

![[DAB topology.png]]