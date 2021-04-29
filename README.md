# UV Portable water filter 
### Project objective : 
To design and fabricate UV Light based portable water filter that works in batch process and opeartes on solar energy.   

### Project description and Need : 

In India about 160 million (more than the population of Russia ) of India's 1.3 billion people don't have access to clean water. Most of them drinking untreated contaminated  surface water that causes deseases such as diarrhoea, cholera, dysentery, typhoid, and polio.

![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/1.jpg)    
Image source : Pinterest  


https://timesofindia.indiatimes.com/india/polluted-water-killed-7-every-day-in-2018/articleshow/69996658.cms  

This report says in 2018 , 2,439 people died because of four major water-diseases — cholera, acute diarrhoeal diseases (ADD), typhoid and viral hepatitis. In all, more than 1.3 crore people were diagnosed with these diseases . In the past five years, 11,768 people have died of these diseases — one every four hours on average.


To overcome this problem in some amount we can try to purify water - atleast bacterial content that majorly affects on human health and spreads water deseases. This project aims  that to develope simple, affordable , poratable water filter that works on solar energy. Its already proven that UV C light kills bacterias effectively . In normal water filter usually UV candles are used to remove bactrial content, but in that case it needs  another water source / tank to pass water contineously through UV candle - its a contineous filtering process and its difficult to make portable version of this. Also in continous process we need to keep filter ON for long time that increases electricity consumptions. 

Considering all above issues  and limitations , if we develope filter that uses UV C light and filters water in batch process , also if it operates on Solar energy that will good for tribal communities and in rural area. 



### System sketch and Initial trials:

To start with , its decided to have temporary setup to check concept validity and to calculate required retention time to get one batch of purified water . System sketch will look like this - 

![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/1-1.jpg)  
 


My collegue Miss. Priyanka Gharat worked on this initial setup. Detailed documenation of this is available on her blog. Here is the link :  
http://vadic.vigyanashram.blog/2020/10/06/solar-water-filter-2/    

In first trial, to know retention time of UV C light in continous filtering process , we passed 250ml water for 30 sec time thorugh UV C quartz glass tube, After  water testing (H2S test) we got negative results , so its concluded that it needs around 30 sec time to purify 250 ml amount of water in continoues process.


Trial on contineous process  |  Trail on batch process
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/1-2.jpg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/1-3.jpg)

In another trial, we taken 2 liter water and kept one UV tube on it with distance 15 cm in between, this was for 3 min retension time and result was negative. We taken successsive trails with varying quantity of water and distance between UV tube and water surface. Finally we got result for 5 liter water with 15cm distance it needs 3.75 min retension time.   

So we concluded, for 20 liter water it needs approximate 15 min retension time of UVC light exposure with 15cm gap in between and with submersible motor inside.  


Accounting these results we dsigned another setup to test above conclusions. This setup mainly included- 

11 watt UV C light tube - 2 numbers   
Choke to control supply voltage   
20 lit container    

Following images showing assembly of this setup, In this we attached two UV C light tubes parallely and equidistant, connected to 230 V AC power supply through choke. UV C light normally passes around 15cm distance inside water so accordingly we selected water container that can hold around 20 liter water.     
Initial setup         |  UV C light tubes
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/2.jpg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/3.jpg)  

with this setup we kept calculated retention time of 15 min with two UV C tubes for 20 lit of  water. After water testing( H2S test )
result was negative.So we tried again with same setup but now with one tube , result was positive . After discussion we come to know that we need to circulate water to get UV C light exposure in whole water. So we added one small 12 V DC operated submercible pump into it nad taken trial again with same setup and retentionn time, now result was negative. Thats it !! Here we saved one UV C light tube (11watt consumption) and added 12VDC submersible pump (2 watt )  into this setup. 


### First prototype design and testing : 

After successful trial of initial setup we come to know ratio of retension time , water quantity  and distnace in between.Accordingly we started working around first prototype to take multiple trails. To test functionality prepared this  with ready water container and same setup as per above. Here for saftey  purpose added case for electronics and tried to fix UV light properly.

![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/4.jpg) 

After testing this for two days its clear that it needs water proofing (especially for electronics part) as water vapours gets trapped on inside cover and affecting on attached electronics on it. So we decided to make design of this system and manufacture this water container cover in FRP.  This FRP cover will contain electronics and fit on water container properly.     

Whole setup design          |  Cover design in solidworks 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/5.png)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/6.png)  



 We outsourced FRP cover with giving mold design as per requirnments. After fixing electronics and UV tube it looks like this. 

UV tube assembly with FRP cover        |  Prototype ready for testing 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/7.jpg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/8.jpg)  




To run this whole setup on Solar energy I tested this on 45 Watt Inverter system available in market. Total consumption of this unit 
is around 15 watt so this inverter is suitable as power source. It's chaging on 20watt solar panel panel and has 2 LED lights as well. Considering tribal areas its solving both - lighting plus water filtering problem. 


Filter with solar power backup        |  On campus installation
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/9.jpg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/install.jpg) 

This first prototype is under testing for now. 

 Nut and  bolts corrosion         |  Water droplets on electyronics 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/filter2.jpeg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/filter1.jpeg)   



### Solutions  


Qauratz glass covering in water filter         |  Aquarium submersible UVC tube 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/filter3.jpeg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/uvtube.jpg)   
















