Direct connection of BESS to the MV grid without the use of a line-frequency transformer can be achieved through the use of cascaded modular converters based on a basic inverter block (also referred to as a bridge, SM, or cell)

### Cascaded H-Bridge Converter (CHB)

The CHB consists of three-phase legs, each having multiple H-bridge cells connected in series.
![[CHB inverter with direct connection of the BESS to the MV grid.png]]
#### Pros
- The utility-scale BESS is normally composed of hundreds of battery modules. Therefore, battery modules can be equally distributed to each cell in the form of shorter battery strings . The use of cascaded topologies enables boosting each LV battery string to MV levels without the use of transformers. Each full bridge can regulate the power flow of the battery modules connected to its dc-link.


### Modular Multilevel Converter (MMC):

The MMC topology with half-bridge SMs ].The structure of the MMC allows for connection of the energy storage elements either directly to the MV dc-link or in a distributed manner across the SMs that form the converters’ arms. In the case of centralized batteries connected to the common dc-link of the MMC, as shown in Fig. 11(a), long battery strings are required negating most of the advantages of the cascaded structure; hence, the distributed approach, as shown in Fig. 11(b), represents a more feasible implementation of the MMC in BESS applications.

![[MMC and corresponding SMs. (a) Centralized batteries on the dc-link. (b) Distributed batteries in the SMs.gif]]

### Pro and Cons
When the MMC is considered solely for the purpose of connecting a BESS to the network, the additional complexity/cost of the MMC structure compared to a CHB (six arms instead of three), as well as the less optimal utilization of the converter (double the number of switching devices for the same number of voltage levels), put the MMC at a disadvantage as the topology of choice. However, integration of EES in MMC converters for high-voltage dc (HVdc) transmission, motor drive systems, or other grid support systems enhances the possible functions and the value that the power converter can provide in these application