ventilation_yùn

My little boy's room is rather wet, so I need to trigger its mechanical ventilation as soon as I can and the more automatic is the better.

On the other hand, my wife is not a connected geek as I am, so I need to let her use a simple dumb switch to put it on or off.

Here's my solution:

* Arduino Yùn next the ventilation system, with a relay and a DHT11 sensor.
* The relay will be connected in a "va et vient" with the simple swith, so my wife'll be happy
* A REST interface will be defined to trigger the relay and get the DHT11 informations
* One of my two main server will be allowed to consult and trigger the Yùn, with some rules (baby-boy not at home, parents not at home: if humidity > 55% and temp > 19°C, trigger the ventialtion and so on.

Of course, I can change my mind on my way... 
