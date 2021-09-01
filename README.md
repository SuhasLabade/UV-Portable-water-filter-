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

### Problems after testing :    

This first prototype is installed in Dixit sirs house for testing, after 20 days we found nutbolts to fix motor are corrodated and motor coupling is broken. 
So I taken this unit back and opened up FRP case so I found water dropletes on electronic parts. I opened up UVC tube frame to check choke circuit, most of PCB tracks gets corrodated due to water vapourization.   

 Nut and  bolts corrosion         |  Water droplets on electronics 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/filter2.jpeg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/filter1.jpeg)     

Its hazardous , eletronics needs to keep inside weather proof box to avoid this corrosion and chances of short circuit failures.Its difficult to keep same setup with UVC tube  and its holder, it needs to cover that part with transperent covering that passes UVC radiations.   


### Solutions  


I find first solution to use quartz tube setup which used for continous water filter system . but it needs again to water seal from both sides to put inside water. Here making connections and tube repalcement will be difficult.   


Qauratz glass covering in water filter         |  Aquarium submersible UVC tube 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/filter3.jpeg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/uvtube.jpg)     


So I browsed some ready to use solutions on internet and I got this submersible UVC germicidal lamp for aquarium. So placed order from two diffrent sources. First tube is with 11watt power consumption and second with 7watt power consumption .  
https://www.eassymall.com/product/uv-light-aquarium-clean-lights-submersible-waterproof-lamp-11w  

I did H2S water testing with both tubes , results are positive with both tubes in same retension time. so I fixed 11watt UV tibe in filter tank with vaccum press attachements and given this unit for testing. 

 Vaccum press UVC submersible tube (11Watt)          |  Final filter unit 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/10.jpeg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/11.jpeg)     

This unit working properly now.My collegue Prasad and Pooja preaperd design and manual of this filter in Solidworks Composer.  

http://vadic.vigyanashram.blog/2021/06/29/portable-solar-uv-water-filter/

In next spiral, we discussed about version 2 with ceramic candles for muddy water . There are filters available in market with ceramic candles so I orederd one of them and fitted 7 watt submersible tube on that. After water testing results are positive , so another unit with UVC and ceramic candles is ready in case of muddy water. 

 Vaccum press UVC submersible tube (11Watt)          |  Final filter unit 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/12.jpeg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/13.jpeg)     


### Bill of material of both units attached herewith : 
 
 https://docs.google.com/spreadsheets/d/1rSHNEuhsrDX18GmfSiTp9_UhxoSMxmUI/edit#gid=175455302
 
 
 So right now two units  are ready as below : 
 
 i) UV Water filter : which will need electric supply for min 15 min in a day , either solar power or grid connection. Its not designed for muddy water.
 
 ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/14.jpg) 

 

ii) UV+C Water filter : This filter mainly contains ceramic candles in addition with UVC tube to treat muddy water. Needs electric supply wither from solar power or grid connection.  

![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/15.jpeg) 


### How to use this filter : 

This filter unit is very handy to use, just follow below steps to start using this. 

1.	Open a filter cover and keep this aside, cover is with UVC tube (fragile material), take care during handling. 
2.	Pour tap water inside up to marking. ( Take care of this while selecting water source - This filter removing only bacterial content, it’s not reducing water hardness or filters muddy water) 
3.	Keep filter cover on tank, orient tube inside direction. 
4.	Now plug in filter connection in 230V AC socket and turn ON switch. 
5.	Keep this for next 15-20 min 
6.	Turn OFF switch and remove connection. Water is ready to drink. 
7.	Keep filter ON every day for 15-20 min. 

Cleaning: 
Clean filter tank and cover regularly.
UV C tube is fixed with vacuum press attachments, it’s removable while cleaning. Fix it properly after cleaning. 

### Advantages: 
	This filer usage UVC light radiations in bandwidth 200 to 280 nm to kill pathogens inside water in batch process. It requires around 15-20 minutes for 20 liter water.   
	No need to give continuous supply. Vey less electricity consumption, 11watt / hour.   
	Portable unit works on solar power, for remote area users, for tribal communities.   
	No need of extra tank, motor and solenoids like continuous type of filters.   
	Low cost, affordable to tribal, remote area peoples.   
	Takes very less space and handy to use and clean.   

### Disadvantages: 
	It’s only disinfecting water with killing bacteria and virus, it’s not reducing water hardness.   
	Not suitable for muddy water.    

### Specifications: 
	UVC light tube : 11Watt, bandwidth 200 to 280 nm  
	Power supply : 230 VAC / 50Hz  
	Solar Panel : 10 watt   
	Solar inverter : 45Watt   

### Features: 
	Portable water filter / Easy to handle   
	Low cost   
	Less maintenance / Easy cleaning   
	Operates on Grid and Solar Power   
	Low power consumption   


### Commissioning instructions: 

1.	Check fragile parts regularly. 
2.	Check electric connections regularly. 
3.	If tube is not operational don’t turn it ON.
4.	Check water level while filling water. 

### Operational   Instructions  
1.	Don’t open filter cover when its ON 
2.	Fit cover properly after pouring water.
3.	Fill water up to the marking only. 
4.	Fix UVC tube properly with vacuum press attachments after cleaning. 
5.	Keep it ON every day for 15 min only, Don’t leave it ON for whole day/ night. 
6.	Handle fragile parts carefully.    


 Concept note preapared to take this next level.  
 https://docs.google.com/document/d/1VB4zR3EquJS_yAA6lzgcYAixboCVVVau/edit?usp=drive_web&ouid=108225846397181625907&rtpof=true
 
 
 ### Installations and Feedback 
 
   1. Given one filter unit to Dixit sirs house at Pune , Feedback received after one week is that flow rate through ceramic candles is very less. Rest of parts working good.     


 Ladies Hostel          |  Workshop 
:---------------------------:|:-------------------------:
![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/16.jpg)  |  ![](https://github.com/SuhasLabade/UV-Portable-water-filter-/blob/main/Images/17.jpg)  

       - Replaced ceramic candles with new candles and tested it again, half of water started remaining in container .  
       - Calculated flow rate of newly received candles - its 800ml / hr , 1600ml / hr .     
   2. Second Unit installed at Ladies hostel and strated collecting feedback.  
   3. Third unit installed inside fablab with Solar Power backup - 90watt inverter with 10 watt solar panel.  
   
   
  Next action plan :  
  2 filters in Manchar city : Electrical shop (1 month trial without cost ) , Paid   
  2 filters on sugar factory : No cost ( 1 month trail )  
  2 filters : Nomadic community (10 days trial ith solar backup )  
  NBIRT model   
  Find Funding resources  
  Discuss new ways 
  
































