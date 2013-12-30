Dual_Probe_Thermocouple_Temperature_Monitor_Project
===================================================

This project builds a dual probe temperature monitor powered by an Electric Imp. Any K-type thermocouple can used. I recommend Thermoworks.com for high quality probes. This project has been through several prototypes and is currrently under redesign. I will post all new code and information as I get it, and eventually post an Instructible as a full tutorial.

Features:

 * Dual Probes with K-type jacks
 * LiPo battery and charging circuit for approx 18 hr runtime
 * LCD display
 * WiFi via Electric Imp for sending data to any web service.
 * Agent served HTML page
 * Ability to set triggers and send SMS or other alerts
 * Data graphing via Xively

<img src="http://media-cache-ec0.pinimg.com/originals/6f/64/15/6f6415441c0feac76d538bdcf4146304.jpg" width=60%; height=60%; />


New version proposed hardware list:

Enclosure: https://www.sparkfun.com/products/11797
  Notes: Adafruit has similar enclusures in other colors, but fewer endcaps. Those could be mixed in and/or painted.
  I have created these two endcaps for this enclosure, but I have NOT yet received the first copies yet, so I would not recommend ordering them until I can verify they they have been created properly.
  https://www.shapeways.com/model/1595632?materialId=6&li=ostatus
  https://www.shapeways.com/model/1595441?materialId=6&li=ostatus
  
Charging circuit: https://www.sparkfun.com/products/11231
  Notes: This charger is ideal with 5V output and undervoltage lockout.
  
Electric Imp: http://www.digikey.com/product-detail/en/IMP001-US-R-ENG/1413-1003-ND/3979638
  Notes: Imp module would be preferable, but not commonly available. Digikey has the best price for the Imp card.
  
Electric Imp breakout: http://www.digikey.com/product-search/en?vendor=0&keywords=april
  Notes: Digikey has the best prices for this board, and Sparkfun boards have been questionable in the past.
  
Thermocouple Amplifier(x2): http://www.adafruit.com/products/269
  Notes: Maxxim has a test board as well with jacks included, but these are preferable.
  
LCD Display: http://www.adafruit.com/products/784
  Notes: You can use any 16x2 display as long as it has a serial backpack. The Sparkfun versions will have slightly     different code, but can easily be used.
  
Battery: http://www.adafruit.com/products/328
  Notes: This battery has quite a bit of capacity for long usage and fits nicely in the enclosure. It should provide about 18 hours of runtime with the current code, and the LCD constantly on with 30 second udpates.
  
Power Switch: http://www.digikey.com/product-detail/en/PRK22J5DBBNN/CH865-ND/1083858
  Notes: These are the smallest rocker switches I could find. Keep a few around.
  
Power Connector: http://www.digikey.com/product-detail/en/PJ-033A/CP-033A-ND/1644529
  Notes: This is a nice small barrel connector that will be mounted on the top of the enclosure. 
  
Thermocouple Jacks and plugs: Still sourcing, as I am not satisfied with the current ones.
