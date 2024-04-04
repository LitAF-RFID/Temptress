# LitAF Temptress
This device is a miniaturised NFC tag that enables the reading of temperature from two TMP112 sensors as well as a LED that can be enabled or disabled. The NFC interface is provided by an NTAG5 NFC to I2C bridge chip.
![Top Side PCB Render](/IMG/LITAF_TEMPTRESS_SKIN_SIDE.png)
![Bot Side PCB Render](/IMG/LITAF_TEMPTRESS_BODY_SIDE.png)

## Coil Design
-   **Target Frequency:** 13.56MHz
-   **Target Q Factor:** 50
-   **Chip Capacitance:** 15pf
-   **External Capacitance:** ~62pf
-   **Target Coil Inductance:** 1.76uH
-   **Coil Shape:** "Rectangular"
-   **Coil Height:** 25mm
-   **Coil Width:** 5mm
-   **Coil Turns:** 8
-   **Coil Trace Width:** 0.1mm
-   **Coil Trace Spacing:** 0.1mm
-   **Coil Copper Thickness:** 2oz

## Bill Of Materials
-   1 x NTAG5 (Link or Boost)
-   2 x TMP117
-   3 x Tuning Cap (C1-3)
-   3 x Smoothing Cap (C4-C6)
-   1 x IN-S124AR LED

## Schematic
![Schematic](/IMG/SCHEMATIC.png)

## Note
This was designed as a demo project for a class that I ran. The design has not been tested and was made in a very short period of time. Whilst it should work, it is far from the ideal design for this sort of device.

## Manufacturing Info
This design was created with the PCBWay 2 layer flex PCB manufacturing specifications in mind. If you order this using the CAM files provided, you need to order with 2oz copper.