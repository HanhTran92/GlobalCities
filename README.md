# Global Cities

## Mapping Air Connections

Inspired by global cities network as depicted in "Global Cities: a, ß and γ tiers" map (Carta & González 2010), in this project, we set out to visualise air connectivity to illustrate the interconnectedness element which characterises global cities.

### Data Source

Using data from open source: openflights.org (https://openflights.org/data.html), we extracted two datasets through Excel: airports.csv,and routes.csv. This database consists of over 7000 airports, and 655536 flight records. 

### Method

We used Stata to eliminate missing observations and duplicated locations in nodes if required, in which the number reduced to approximately 5000.

In preparation for data visualisation in Gephi, we divided the data into two files: nodes, which contained airport coordinates, and linkages, which had source and target airport. 

We set longitude and latitude in double format, then proceeded to apply Geolayout and set different colors to encapsulate distinctive elements. We then modify the nodes depending on the degree centrality, which means how well-connected with other cities, and ranked the linkages in accordance with airline frequency. 

### Discussion

The graph connotes two implications. First, European airports tended to have higher connectivity in comparison with other continents’ counterparts. Second, there was high air connectivity between US and Europe, as well as China and Europe.

We took further step by investigating which city had the highest global connectivity. As such, we created a new dataset attaching each airport with their city location.

As discovered from the data networks, 4 out of 5 cities which ranked first in the global interconnectedness list belonged to European continent, with London possessing the highest international connectivity degree (338 flight-out links and 341 flight-in links). The remaining list respectively came Paris, Frankfurt and Moscow. Istanbul, the city straddling between Asia and Europe, ranked 5th with 229 out flights and 232 in-flights. Chicago, and Beijing appeared to rank 7th and 8th as top world interconnected cities. 

As we explored further, the precursory outcome partially implies why some cities had higher connectivity than the others. (1) ideal geographical location, where the airport can easily and conveniently serve as a vital transit node that connects one city to another. (2) the presence of strong airlines,  London (British Airways), France (Air France), Frankfurt (Lufthansa), Moscow (Aeroflot) Istabul (Turkish Airline). (3) vibrant economic activities between these cities with the world that shape their frequent transportation. 




### Acknowledgement

Special credits go to Young Joon Oh with his tutorial video.
https://www.youtube.com/watch?v=DvSJQRx9Jss&list=LLqsMN_VaDEEWWB18BrZv5vw&index=4&t=747s

![Air connections between cities around the world](map002.png)

### References

Belderbos, R., Du, H.S. and Goerzen, A., 2017. Global cities, connectivity, and the location choice of MNC regional headquarters. Journal of Management Studies, 54(8), pp.1271-1302.

Carta, S. and Gonzalez, M., 2013. Mapping Connectedness of Global Cities: a, ß and γ tiers.

Goerzen, A., Asmussen, C.G. and Nielsen, B.B., 2013. Global cities and multinational enterprise location strategy. Journal of international business studies, 44(5), pp.427-450

Sassen, S., 2016. Global networks, linked cities. Routledge.


