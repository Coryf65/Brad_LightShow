# Setup Overview

PC talks to Controller then controller talks to the lights

Video Series that helps teach the basics [Learn Christmas Lighting](https://www.youtube.com/channel/UCXVmdAdDtjZrvZVEIbfaZCg)

Keith a Developer, [Youtube Tutorials](https://www.youtube.com/channel/UCVOKeP2mWsBEKqqHkT0QndQ/videos)

## Lights

- Use LED Strings - Most common:.0 WS2811 Protocol Which is based on LED type
- 12v or 5v
- try not to make the length more than 25ft or so
- Use Bungie Balls / Zip Ties to hold to house
- Plastic Strips to hold Pixels

## Controllers

Choose based on number of pixels needed. You could have voltage drop if it is around 50 feet may want to use a better controller.
choose a Long Range Controller

1. DIY
    - ESP8266 NodeMCU - small microcontroller, running WLED
    - Falcon F16V3 Pixel Controller, from PixelController.com $200

2. Turn Key (can be far easier)
    - HinksPix Pro

- Each board can communicate using *E1.31*

## Software

1. XLights 
    [Xlights Website](https://xlights.org/)
    [Xlights Source Code](https://github.com/smeighan/xLights)

### Pre-Made Kits

Store that sells Kits, [Holiday Coro](https://Holidaycoro.com)


## Terminology

**Pixel** : The Individual LED Diode
    Each LED has 3 Channels R G and B
        - Blue = Channel 3
        - Red = Channel 1
        - Green = Channel 2

**Strand** : String of LED RGB Lights
    each strand has 50 pixels which comes to be 3 E1.31 Channels

**Universe** : Contains Channels, max of ~510 Channels in one Universe

Rules:
3 Channels = 1 Pixel
170 Pixels = 1 Universe
Up to 6 Universes = 1 Output

**Relays** : Whole strands, traditonal lights

**DMX Decoders** : RGB LED's, whole strands

**Pixel Controllers** : Smart pixel light controllers
