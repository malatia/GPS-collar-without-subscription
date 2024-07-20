# GPS-collar-without-subscription
This project is about making a DIY GPS tracker for your animal. Without having to pay an additionnal subscription.


The idea is pretty simple : the reason you have to pay a subscription when you purchase a GPS collar, is that they have to send the datas from the collar to your phone/computer, and that they use 2G/3G/4G to do so.

The main idea here, is to do a basic GPS tracker with arduino, and then add a GSM module to it. That way, you can pay for a lil sim card to communicate with the arduino by SMS. It reduces the cost by a fair margin, which can be variable depending on the country you're living in.

# Hardware
Hardware you gonna need :
  - Arduino nano                           ->  https://fr.aliexpress.com/item/1005006989738984.html
  - GPS module, i like the neo 6m          ->  https://fr.aliexpress.com/item/1005006787427660.html
  - 3.7v battery                           ->  https://fr.aliexpress.com/item/1005003198563309.html
  - Charger module for the battery         ->  https://fr.aliexpress.com/item/1005006989495574.html
  - GSM module, i like the sim 800l        ->  https://fr.aliexpress.com/item/1005006140612338.html
  - A set of resistances, capacitors wiring cables, breadboard a very basic kit allowing us to make some electrical circuits. We especially need a 1000µF capacitor, and a set of resistors.

# Software
First, you need to have an arduino up and running. There is a plethora of excellent tutorials on the net to help you with that. Not gonna go in details about that. 
  - Just download the arduino IDE, eventually a driver for it if you don't have it yet.
  - Then plug your arduino in
  - Open the IDE and it should do the rest

Then, just clone or copy the sketch in the repository and you should be good to go

# Wiring
**WIP**

