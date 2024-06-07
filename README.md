# MegaGRRL-Desktop-Mini-USB
 I have been using the desktop version of MegaGRRL for 4 years. As my PCB drawing skills improve, I have the confidence to realize all my ideas and changes. This version is based on the Type-C version and includes a lot of practical modifications.
 ## Improvement Details  
1. Delete the 7805, 78M33, and other antique LDO step-down chips, as well as the huge heat sink, which are inefficient and generate a lot of heat. I used a newly designed SPFM Lite power supply circuit to replace it.  
2. Use an isolated voltage regulator module such as IB0905/0505S to achieve step-down/regulation, so the PCB currently supports 5V or 9V input, depending on the model of the voltage regulator module. B0905/0505 can be easily obtained on AliExpress. These voltage regulator modules work well on SPFM Lite, with very little power supply noise, which can further improve the sound quality.
3. Delete MOSFETs such as IRF9530, which are huge and too retro.  
4. Use F0805 to protect the power circuit.  
5. Use a strong PS-22E05 (A04) self-locking switch to replace the original small switch to extend the life of the power button.  
6. All micro switches use white patch 6*6 silicone buttons, which do not require circuit modification and can significantly improve the user experience. The original micro switches made my hands hurt.
7. Because some buyers reported that the main volume potentiometer was easily damaged during transportation, I replaced it with RK097 B10K. RK097 is smaller and more robust, and the entire potentiometer is plastic-sealed, which is more reliable.  
8. Delete the 3296 potentiometer.  
9. In order to make the SN76489 volume adjustable, add an RK097 to adjust its volume, and replace R6/R8 with 47K.  
10. Replace the difficult-to-solder Type-C with Mini-USB.  
11. Restore natalie's silk screen art, obtained by reverse engineering the original desktop motherboard. (Actually not necessary)  
12. Double-layer square hole IC socket ensures good connection and service life. (No need to modify the PCB)  
13. Solder the round hole female header first in RN2 and then insert the resistor (no need to modify the PCB) to facilitate mass production and upload factory firmware.  
14. Add my silk screen art "Denjhang's OSHW"  
15. Optional self-ejecting SD card slot or self-ejecting TF card slot, more flexible to choose the type of memory card, protecting the memory card while further improving the user experience.  

 ## To do  
 1. Design and make the acrylic shell, which is done by Xiaohao Studio  
2. Design a new MegaGRRL-modular motherboard to completely separate the data and analog lines and reduce interference noise.  
3. USB/DC dual power supply, refer to SPFM Lite circuit  
4. Compatible with RE:Birth module.  
5. Add battery interface.  
