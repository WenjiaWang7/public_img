##HW12_comparison of ADS-B transponder data on Mar.06.2015 and Nov.13.2015(Friday)

##Single day view
<img src="https://github.com/WenjiaWang7/public_img/blob/master/mar_map.png" width = "450" height = "400"/> 
<img src="https://github.com/WenjiaWang7/public_img/blob/master/nov_map.png" width = "450" height = "400" align=center />

From two geo-maps we can find that, the amount of transponder flights on Mar.06 is larger than flight on Nov.13. Besides, flights transpondered at (lon=118.44, lat=34.02) is more on Mar.06 than Nov.13

##Comparing daytime
<img src="https://github.com/WenjiaWang7/public_img/blob/master/mar.dt.png" width = "450" height = "400"/> 
<img src="https://github.com/WenjiaWang7/public_img/blob/master/nov_dt.png" width = "450" height = "400"/> 

Split the data into daytime part(6am to 7pm) and nighttime part(8pm to 5am). These are daytime transponder data. The color is based on altitude. We can see that transponder positions are more converged together on Nov.13 than Mar.06. There is roughly one cluster on Nov.13 while there are roughly three clusters on Mar.06

##Comparing nighttime
<img src="https://github.com/WenjiaWang7/public_img/blob/master/mar_nt.png" width = "450" height = "400"/> 
<img src="https://github.com/WenjiaWang7/public_img/blob/master/nov_nt.png" width = "450" height = "400"/> 

Then let's look at the plots during nighttime. On Mar.06, most thansponder positions are near (lon=118.64, lat=34.01). On Nov.13, there is no scatter point.

##Comparison by hour
<img src="https://github.com/WenjiaWang7/public_img/blob/master/mar_hour.png" width = "450" height = "400"/> 
<img src="https://github.com/WenjiaWang7/public_img/blob/master/nov_hour.png" width = "450" height = "400"/> 

So, I dig into the data and shown them by hour. Firstly we can see that there is no data from 0am to 6am and from 8pm to 12pm on Nov.13. Beside, during the night most transponder happened on the central of SMO and maybe because of less amount of transponder flights, the altitude of them don't need to be that high as the flight during daytime.


##Comparison of distant-altitude
<img src="https://github.com/WenjiaWang7/public_img/blob/master/mar.alt.png" width = "450" height = "400"/> 
<img src="https://github.com/WenjiaWang7/public_img/blob/master/nov_alt.png" width = "450" height = "400"/> 

In the end, I draw a dist-alt plot for these two days. On Mar.06, there are obviously three height layers below 10000feet, and then the more transponder position is approaching SMO, the flights with larger altitude while the flights will approach the ground if the position is far away from SMO. On Nov.13, the flights converged near SMO and have a roughly high altitude. On both day, there are several extremly high altitude flights.
