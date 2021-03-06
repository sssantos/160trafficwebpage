# The MacArthur Maze
<img src="images/maze.jpg" class="img-responsive" alt="" caption = "The MacArthur Maze" width = "60%">  <br />
The MacArthur Maze is an intersection of five different freeways: the I880, I980, I580, I80, SR24. It is unique because there are multiple route options to reach destinations of interest. So, if a particular freeway on the Maze is heavily congested or closed, other routes can still be utilized. 

# Question
How do freeway closures on the MacArthur Maze influence traffic behavior on the Maze and its freeways? What alternatives freeways are taken due to a closure?

# Data
Our data was collected from the State of California PeMS website. This data consists of hourly traffic flow (vehicles per hour) and delay (extra time traveled caused by traffic speed under 60mph)for sections of the freeways on and near the Maze for multiple time frames approximately a month long containing the following events: the 2007 I-580 East Connector collapse, the 2009 Emergency Bridge Closure, and the 2013 Labor Day Bridge Closure. Data was collected from previous years of the events to use for comparison. <br />
<img src="images/inventory.jpg" class="img-responsive" alt="" caption = "PeMS Freeway Sensors"  width = "70%"> 
<img src="images/data.jpg" class="img-responsive" alt="" caption = "data table"  width = "70%"> 

# Results
### 2007 I-580 Connector Collapse
On April 29th, the connecting ramp from I80 east to I580 east collapsed, landing on the I880. Focusing first on I880 north, we see that traffic flow dropped signifacantly near I880 north's section of the maze, suggesting that drivers avoided taking I880 north. However, once the connector was rebuilt, traffic flow values became consistent with values before the collapse, suggesting that for many driver's, I880 north is the freeway of choice. The graphs below depicts the traffic flow between the beginning of April to the end of May. <br />
<img src="images/20007.jpg" class="img-responsive" alt="" caption = "PeMS Freeway Sensors"  width = "70%"> 



### 2009 Emergency Bay Bridge Closure  
On Wednesday, October 27, during the evening commute, the new cross beams installed during the 2009 Labor Day Bay Bridge restoration project came crashing down and caused the bridge to remain closed until the morning of Monday, November 2. The proposed cause of this failure was likely due to the 55 mile per hour wind gusts that ensued on the night of the bridge failure. In order to see how traffic patterns diverged as a result of this incident, we decided to analyze the effects of the Bay Bridge closure on other bridges into San Francisco. The bridges we looked at are as follows: Richmond (A on map), San Mateo (C on map), Dumbarton (D on map).  <br />
<img src="images/2009map.jpg" class="img-responsive" alt="" caption = "data table"  width = "70%"> <br />

For our analysis, we looked at weekdays and weekends individually so that we could see the effects of the emergency closure on the daily work commute. From the flow plot below regarding weekdays, we can see that all three bridges in question increase abruptly in use in response to the closure of the Bay Bridge. The I92, in both directions, sees the most significant jump in average flow after the emergency closure. This is likely due to the fact that the San Mateo Bridge is the closest in proximity for commuters who normally take the Bay Bridge. The pattern for the I92 holds over the weekend, however the other two bridges do not see the same increase that they experienced during weekdays.<br />
<img src="images/2009graph.jpg" class="img-responsive" alt="" caption = "data table"  width = "70%"> 


### 2013 Labor Day Closure    
The 2013 Labor Day Bay Bridge closure was planned ahead of time, unlike the 2009 emergency closure, thus allowing local residents and commuters to strategize their travel arrangements during the closure. The closure extended from Wednesday, August 28 to Tuesday, September 3. 
<br /><br />

As seen in the following histograms, the bridge closure in 2013 certainly impacted these four freeways significantly more than the effects of just the holiday weekend, as observed in 2012. This is likely a direct result of the Bay Bridge closure, as the bridge lies on the I80. As for SR24, many people from east of the bay area may be avoiding the MacArthur Maze altogether due to the closure of the Bay Bridge. This means that fewer people will be taking this route to and from the bay area, explaining the substantial decline in use during the 2013 Labor Day Weekend. This decline in external commuters entering the Maze in the first place could part of the reason that the I880-S, in particular, sees far lower use as well. The I880-S can be used as a route towards the San Mateo Bridge as an alternative means of entrance into San Francisco, implying a potential increase in use, but, due to the lower traffic into the East Bay in general, this alternative route goes unused. 

<br />
<img src="images/2013histograms.jpg" class="img-responsive" alt="" caption = "PeMS Freeway Sensors"  width = "100%"> 

# Conclusion
As a result of our analysis we were able to diagnose and understand the flow of traffic that occurs throughout the MacArthur Maze in West Oakland. Though none of the freeways are direct substitutes for each other, there are several alternate routes that can be used within the Maze to arrive at the same location. All three of the bridges, primarily the San Mateo Bridge, that we looked at increased in traffic flow considerably after the emergency closure of the Bay Bridge, in spite of increased BART ridership. This helps cement our conclusion that most commuters are willing to drive to alternate routes in order to avoid a closure on their commutes.
	As for the 2013 closure, however, it is still unclear how alternate routes were affected by the closing of the bridge, as the holiday weekend and increase in BART ridership both decreased traffic volume considerably, confounding our analysis. As a result, no hard and fast diagnosis can be made regarding the alternate routes in the Maze during this time; rather, we can only discuss those that experienced abnormally severe shifts in traffic flow.

