---
title: "Introduction"
permalink: /docs/getting-started/
excerpt: "Introduction and getting started with the SparkFun Inventor's Kit."
toc: true
toc_sticky: true
sidebar:
    nav: "docs"
---

# WELCOME TO THE SPARKFUN INVENTOR’S KIT (SIK) GUIDE

This is your map for navigating beginning embedded electronics.
This booklet contains all the information you will need to build five
projects encompassing the 16 circuits of the SIK for the SparkFun
RedBoard. At the center of this manual is one core philosophy: that
anyone can (and should) play around with electronics. When you’re
done with this guide, you will have built five great projects and
acquired the know-how to create countless more. Now enough talk
— let’s start something!

# The RedBoard Platform

**THE DIY REVOLUTION:** At SparkFun we believe that an understanding of electronics
is a core literacy that opens up a world of opportunities in the fields of robotics, Internet
of Things (IoT), engineering, fashion, medical industries, environmental sciences,
performing arts and more. This guide is designed to explore the connection between
software and hardware, introducing Arduino code and SparkFun parts as they are
used in the context of building engaging projects. The circuits in this guide progress
in difficulty as new concepts and components are introduced. Completing each circuit
means much more than just “experimenting”; you will walk away with a fun project you
can use — and a sense of accomplishment that is just the beginning of your electronics
journey. At the end of each circuit, you'll find coding challenges that extend your learning
and fuel ongoing innovation.

## A COMPUTER FOR THE PHYSICAL WORLD

The SparkFun RedBoard IoT - RP2350 is your development platform. At its roots, the
RedBoard is essentially a small, portable computer, also known as a microcontroller.
It is capable of taking inputs (such as the push of a button or a reading from a light
sensor) and interpreting that information to control various outputs (like blinking an
LED light or spinning an electric motor). That’s where the term “physical computing”
comes in; this board is capable of taking the world of electronics and relating it to the
physical world in a real and tangible way.

<figure>
  <img src="{{ '/assets/images/sik-docs-010-redboard-rp2350.jpg' | relative_url }}" alt="RedBoard IoT RP2350">
</figure>

**THE SPARKFUN REDBOARD IOT- RP2350** is one of a multitude of development boards
based on the Raspberry Pi RP2350 microprocessor. It has 14 digital input/output pins (six of which
can be PWM outputs), six analog inputs, an onboard RGB LED, qwiic connector, Wi-Fi, a USB-C connection, a
power jack, and a reset button. You’ll learn more about each of the RedBoard's features as
you progress through this guide.

**NOTE:** For the remainder of this guide, in the interest of brevity, we will refer to the RedBoard IoT - RP2350 simply as the “RedBoard.” 
{: .notice--info}

# Baseplate Assembly

Before you can build circuits, you’ll want to first assemble the breadboard baseplate. This
apparatus makes circuit building easier by keeping the RedBoard microcontroller and the
breadboard connected without the worry of disconnecting or damaging your circuit.

**TO BEGIN**, collect your parts: the RedBoard, breadboard, included screwdriver, baseplate and
two baseplate screws.

Your screwdriver has both Phillips and flatheads. If it is not already in position,
pull the shaft out and switch to the Phillips head.

## Install the Breadboard

<figure>
  <img src="{{ '/assets/images/sik-docs-010-asm-base.png' | relative_url }}" alt="Add the breadboard to the base">
</figure>

**PEEL** the adhesive backing off the breadboard.

**CAREFULLY ALIGN** the breadboard over its spot on the baseplate. The text on the
breadboard should face the same direction as the text on the baseplate. Firmly press the
breadboard to the baseplate to adhere it.

## Install the RedBoard

<figure>
  <img src="{{ '/assets/images/sik-docs-010-asm-redboard.png' | relative_url }}" alt="Add the RedBoard to the base">
</figure>

**ALIGN THE REDBOARD** with its spot on the baseplate. The text on it should
face the same direction as the text on the breadboard and the baseplate. Using
one of the two included screws, affix the RedBoard to one of the four stand-off holes
found on the baseplate. The plastic holes are not threaded, so you will need to apply
pressure as you twist the screwdriver.

Screw the second screw in the stand-off hole diagonally across from the first. With
that, your baseplate is now assembled.

# Anatomy of the SparkFun RedBoard

<figure>
  <img src="{{ '/assets/images/sik-docs-010-atom-redboard.png' | relative_url }}" alt="RedBoard IoT - Details">
</figure>

## REDBOARD HARDWARE OVERVIEW

| | | |
|--|:--:|--|
| **A** | **POWER IN (BARREL JACK)** | Can be used with either a 9V or 12V “wall-wart” or a battery pack.|
|**B** | **POWER IN (USB-C PORT)** |Provides power and communicates with your board when plugged into your computer via USB.|
|**C** | **LED<br>(RX: RECEIVING)** | Shows when the USB-to-serial chip is receiving data bits from the computer.|
| **D** | **LED<br>(TX: TRANSMITTING)** | Shows when the USB-to-serial chip is transmitting data bits to the computer.|
|**E**|**ONBOARD LED<br>PIN D13** | This LED, connected to digital pin 13, can be controlled in your program and is great for troubleshooting.|
|**F**| **PINS AREF,GROUND, DIGITAL,RX, TX, SDA, SCL**|These pins can be used for inputs, outputs, power and ground.|
|**G**|**POWER LED**|Illuminated when the board is connected to a power source.|
|**H**| **RESET BUTTON**|A manual reset switch that will restart the RedBoard and your code.|
|**I**| **ISP HEADER**|This is the In-System Programming header. It is used to program the ATMega328 directly. It will not be used in this guide.|
|**J**| **ANALOG IN, VOLTAGE IN, GROUND, 3.3 AND 5V OUT, RESET**|The power bus has pins to power your circuits with various voltages. The analog inputs allow you to read analog signals.|
|**K**|**RFU**|This stands for Reserved for Future Use.|
|**L**|**QWIIC CONNECTOR**|SparkFun Qwiic® Cable Connector for I2C Devices.|

# Anatomy of the Breadboard

A breadboard is a circuit-building platform that allows you to
connect multiple components without using a soldering iron.

<figure>
  <img src="{{ '/assets/images/sik-docs-010-atom-breadboard.png' | relative_url }}" alt="Breadboard Overview">
</figure>

# Inventory of Parts

The SparkFun Inventor’s Kit contains an extensive array of electronic components. As
you work your way through each circuit, you will learn to use new and more complicated
parts to accomplish increasingly complex tasks.

<figure>
  <img src="{{ '/assets/images/sik-docs-010-inventory.png' | relative_url }}" alt="SIK Inventory of Parts">
</figure>






