# UV Portable water filter 
### Project objective : 
To design and fabricate UV Light based portable water filter that works in batch process and opeartes on solar energy.   

### Project description and Need : 

In India about 160 million (more than the population of Russia ) of India's 1.3 billion people don't have access to clean water. Most of them drinking untreated contaminated  surface water that causes deseases such as diarrhoea, cholera, dysentery, typhoid, and polio.

![](https://github.com/SuhasLabade/my-projects-/blob/master/Images/1.jpg) 

https://timesofindia.indiatimes.com/india/polluted-water-killed-7-every-day-in-2018/articleshow/69996658.cms  
This report says in 2018 , 2,439 people died because of four major water-diseases — cholera, acute diarrhoeal diseases (ADD), typhoid and viral hepatitis. In all, more than 1.3 crore people were diagnosed with these diseases . In the past five years, 11,768 people have died of these diseases — one every four hours on average.To overcome this problem in some amount we can try to purify water - atleast baterial content that mainly majorly affects on human health and sperads water deseases. This project aims to that to develope simple, affordable , poratable water filter unit that works on solar energy. Its proven that UV C light kills bacteria s effectivily.In normal water filter usually UV candles are used to remove bactrial content. But in that case it needs  another water source / tank to pass water continousaly from UV candle, its a contineous filtering process and its difficult to make portable version of this. Also in continous process we need to keep filter ON for long time that increases electricity consumptions. 

Considering all these things 




### System sketch and design:

This device system mainly consisiting Sensor part ,Main controller board, 
data trnsmission unit and cloud storage. Sensor part includes BOSCH make BME280 Temperature and relative humidity 
sensor, considering its best performance in this envirnoment.ESP32 controller is brain of this system,considered its latest features like onchip bluetooth ,wifi connectivity. 
Its also suitable for furure modifications at software level.GSM SIM800L module used for transmitiing data in GPRS mode on thingspeak cloud.Thingspeak
cloud storage displaying this data in graphical format and if possible, we can do mathematical analysis using thingspeak. Its also available to download 
CSV sheet format.This whole system is powered with Solar energy with battery backup considering remote farm locations without electric supply.   



### Electronic design:

Electronics design part mainly consisting four parts - 
1. Sensory system 
2. Main control unit 
3. Cloud storage 
4. Power supply 

#### Sensor selection : 
Here to measure temperature and relative humidity parameters BOSCH make BME280 sensor selected.
This module self-heats a little bit and the temperature measurements can be 1 or 2 degrees above the real temperature value.
However, the BME280 is also the temperature sensor that gave more stable temperature readings without many oscillations between readings.
 This has to do with the resolution of the sensor. It can detect changes up to 0.01ºC.  
 
On below link most commonly used temparture sensors are compared and its showing BME280 is most suitable for this type of application. 
https://randomnerdtutorials.com/dht11-vs-dht22-vs-lm35-vs-ds18b20-vs-bme280-vs-bmp180/

Refering these results to use BME280 for this project.

Temperature sensors comparision            |  Comparision graph
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/my-projects-/blob/master/Images/BME4.png)  |  ![](https://github.com/SuhasLabade/my-projects-/blob/master/Images/BME5.png)

Although temperature sensor selection is dependent on your applications. 
