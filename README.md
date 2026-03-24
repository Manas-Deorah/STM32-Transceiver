# STM32-Transceiver
The objective of this work is to design and develop a printed circuit board (PCB) for a 2.4 GHz wireless communication system using the RFX2401C RF front-end module and STM32
The microcontroller communicates with the RF transceiver through an SPI interface and provides the data to betransmitted. The RF transceiver converts this digital data into a 2.4 GHz RF signal, which is then amplified by the RF front-end module.
To check the working, S parameters for the RF paths for plotted using Ansys SIwave as shown in the above plot. S11 parameter for both antenna reaches minima at 2.4GHz showing minimal reflections. The S12 parameter is close to 0dB showing very less power loss.
Can be mounted on drones and used for video transmission and communication. Size of the PCB is only 3.5 by 4.7 mm which makes it convenient for using with drones
