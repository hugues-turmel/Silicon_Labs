# Thunderboard Sense 2 discovery
## TP2
  
* EFR32MG12 (uC):  
	* R pour radio  
	* MG : BT, Zigbee, etc...  
	* Cortex M4  
	* 1 Mega de flash  
	* Mode :  
		* EM0 : Active  
		* EM1 : Sleep  
		* EM2 : Deep Sleep  
		* EM3 : Stop  
		* EM4 : Hibernate  
		* EM4 : Shutoff  

* UART :  
	* liaison série asynchrone  
	* bit de start et bit de stop  
	* liaison Rx/Tx RS232  
	* half ou full duplex  
* SPI :  
	* liaison full duplex  
	* plus rapide que l'I2C  
	* 4 pin :  
		* SS  
		* CLK  
		* MISO  
		* MOSI  
