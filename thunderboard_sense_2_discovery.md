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
	* 4 pins :  
		* SS  
		* CLK  
		* MISO  
		* MOSI  
  
* I2C :
	* Synchrone
	* Bi directionnel Série
	* 2 pins :
		* SDA  
		* SCL  


* Energie Harvesting : Tire son énergie de son environnement  
	* Photovoltaic -> 100 m>/m2  
	* Thermic -> 10 mW/m2  
	* Vibration -> 1 mW/m2  
	* RF -> 10 uW/m2  (NFC, RFID)  
	* RF -> 0.1 uW/m2 (GSM, WIFI)  

* Edge computing :  
	* calcul sur la gateway  
	
* 4 notions de sécurité :  
	* Confidentialité  
	* Authentification
	* Intégrité : message non intercepté en cours de route par une personne non voulue    
	* Non-répudiation : Lorsque tout est ok on peut faire une MAJ  