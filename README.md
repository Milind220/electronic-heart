# Electronic Heart


I made this brass heart with colourful LEDs inside as a gift for my girlfriend. When switched on, it's LEDs light up in a series of 4 different patterns. The first is a shifting purple light that runs down both sides of the heart. There's also two multicoloured, rainbow style patterns, and one which is supposed to resemble the beating of a heart.

You can see videos/photos of the project [here](https://drive.google.com/drive/folders/1zQZjbOZPv8SrULSwWYCTZUva66K80eWO?usp=sharing)

## Build

The outer shell is made out of 1.0 mm diameter brass wire (non enameled wire), and the inner heart shape with the LEDs mounted on it is made out of 0.8 mm diameter brass wire (also non enameled).

I used 9 WS2812b individually addressable 'NeoPixel' LEDs, which require 3 connections: 5V, Ground, and Data. This made wiring easy as the same data line could run through all the LEDs one by one.

The heart is powered by a 750 mAh LiPo cell (which in hindsight was definitely overkill). This is wired to a TP4056 boost converter/LiPo charger module, that ensures that the output voltage is a steady 5V, while also enabling safe charging and usage of the LiPo. The entire contraption can be charged through a micro USB port.

## Credit:

Design Credit: Jiri Praus's [Beating LED Heart](https://www.youtube.com/watch?v=PCjM7lu5XMA)

The code for the heart was simple enough for me to handle with my then limited programming skills, so I wrote it myself.




If you notice, there's very few commits on the actual code here. I made this project in March 2021, before I learnt how to use Git and Github, and so when I finally made the Github repo for it, I had a completed project ready to put in it.
