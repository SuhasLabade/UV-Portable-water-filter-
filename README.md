# UV Portable water filter 
### Project objective : 
To design and fabricate UV Light based portable water filter that works in batch process and opeartes on solar energy.   

### Project description and Need : 

In India about 160 million (more than the population of Russia ) of India's 1.3 billion people don't have access to clean water. Most of them drinking untreated contaminated  surface water that causes deseases such as diarrhoea, cholera, dysentery, typhoid, and polio.

![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/1.jpg)   

https://timesofindia.indiatimes.com/india/polluted-water-killed-7-every-day-in-2018/articleshow/69996658.cms  
This report says in 2018 , 2,439 people died because of four major water-diseases — cholera, acute diarrhoeal diseases (ADD), typhoid and viral hepatitis. In all, more than 1.3 crore people were diagnosed with these diseases . In the past five years, 11,768 people have died of these diseases — one every four hours on average.


To overcome this problem in some amount we can try to purify water - atleast baterial content that mainly majorly affects on human health and sperads water deseases. This project aims  that to develope simple, affordable , poratable water filter that works on solar energy. Its already proven that UV C light kills bacterias effectivily . In normal water filter usually UV candles are used to remove bactrial content, but in that case it needs  another water source / tank to pass water continousaly through UV candle - its a contineous filtering process and its difficult to make portable version of this. Also in continous process we need to keep filter ON for long time that increases electricity consumptions. 

Considering all above issues  and limitations , if we develope filter that uses UV C light and filters water in batch process , also if it opeartes on Solar energy that will good for tribal communities and in rural area. 



### System sketch and initial trials:

To start with , its decided to have temporary setup to check concept validity and to calculate required retention time to get one batch of water purified. As per below sketch we designed initial setup.  

![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/1-1.jpg)  
 




My collegue Miss. Priyanka Gharat worked on this initial setup. Detailed documenation of this is available on her blog. Here is the link :  
http://vadic.vigyanashram.blog/2020/10/06/solar-water-filter-2/  
In first trial, to know retention time of UV C light in continous filtering process , we passed xxx water for xxx time thorugh UV C quartz glass tube, After  water testing (H2S test) we got negative results , so ist concluded that it needs around 10 sec time to purify xxx amount of water.  

Temperature sensors comparision            |  Comparision graph
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/2.jpg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/3.jpg)


Taking in count this result we dsigned another setup to test retention time required for batch process. This setup mainly includes 

11 watt UV C light tube 
Choke to control supply 
20 lit container 

So we tried with different quantity and UV C projection timings-. 
Initially  we kept 3 min projection for 5 liter of water - results are negative. so we kept reducing projectioin time and finally we found for 5 liter quantity it needs to have 5 min projection time . 





   



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
