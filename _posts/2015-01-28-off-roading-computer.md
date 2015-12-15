---
layout: post
title: "Off roading computer"
description: "Arduino based off-roading computer"
category: 
tags: ['Arduino', 'Jeep']
---
{% include JB/setup %}

## Construction

I don't have a schematic, if you want me to make a schematic let me know.

The LCD and position sensor run data on a I2C bus. The computer is powered by a 12v to 5v power converter. I made the holes for the button and LCD switch using a Dremel Drill. I wired the power into the stereo circuit. 

[Hackaday.io project page](https://hackaday.io/project/8047-jeep-offroading-computer)

### Parts

- [Arduino Nano](http://www.amazon.com/gp/product/B00761NDHI/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&linkCode=as2)
- [4x20 Led screen](http://www.amazon.com/gp/product/B00GZ6GK7A/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&linkCode=as2)
- [Project box](http://www.amazon.com/gp/product/B0002BENMI/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&linkCode=as2)
- [Position Sensor](http://www.adafruit.com/products/1604)
- [Outside temperature sensor](http://www.amazon.com/gp/product/B008HODWBU/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&linkCode=as2)
- [Calebration switch](http://www.amazon.com/gp/product/B00M7PRTHI/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&linkCode=as2)

### Images

![overview]({{ site.url }}/assets/images/off_roading_computer_1.jpg)
![insides]({{ site.url }}/assets/images/off_roading_computer_2.jpg)

### Code

[https://github.com/CacheFactory/offroading_computer](https://github.com/CacheFactory/offroading_computer)