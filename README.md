# GarageControl
Particle Photon + SmartThings = TOTAL GARAGE CONTROL!!!

Voice control with Google Assistant and Alexa are easily integrated with IFTTT.

WebCoRE is used to refresh the door status in SmartThings when
it sees a Particle.publish from the Particle.

TO DO:  

        - Get SmartThings to see the g#State as open/close sensors so I can use them
          with smartapps like Notify Me When and Smart Lighting

        - Get SmartThings to see the relays as garage doors

1/1/19: Modified Jared's original .ino and .groovy for controlling a single relay/garage door, using a Particle Argon. 
        Pin D4 must be used as D3 is not an option using the Adafruit Power Relay Featherboard.
        Will be adding a second magnetic sensor to pick up a positive door open, and another picture to indicate "Intermediate" 
        if neither set of contacts are made. 
