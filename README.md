
# Fujitsu zeroclient dz22-2 main board

## front

![front](imgs/pcb-front.jpg)

1. PoE output to power supply
2. front panel (buttons)
3. power supply
4. LCD display
5. speakers
6. USB ports
7. unused connector, probably JTAG.

## back

![back](imgs/pcb-back.jpg)


## power supply connector

1. 5V
2. 5V
3. 5V
4. Ground
5. Ground
6. EAN1
7. DIM1
8. NC
9. NC
10. NC
11. SAVING ON/OFF
12. Ground

## JTAG

1. Vref 2.5v
2. TDI
3. TMS
4. TDO
5. TCK
6. GND

## jtag detect

        Connected to libftdi driver.
        IR length: 6
        Chain length: 1
        Device Id: 00110100000000011101000010010011 (0x3401D093)
          Manufacturer: Xilinx (0x093)
          Part(0):      xc6slx150 (0x401D)
          Unknown stepping! (0011) (/usr/share/urjtag/xilinx/xc6slx150/STEPPINGS)
         No. Manufacturer              Part                 Stepping Instruction          Register                        
        -------------------------------------------------------------------------------------------------------------------
        *  0                                                         (none)               (none)                          




## References

* [pano-wiki / G2 Zero Client](https://pano-wiki.cyrozap.com/wiki:g2_zero_client)


