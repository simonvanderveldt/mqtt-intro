![MQTT](img/mqtt-logo.png)

# Why I like MQTT
a quick MQTT intro


!SLIDE
![MQTT](img/mqtt-logo.png)
# MQTT
“_MQTT is a machine-to-machine/Internet of Things connectivity protocol_”

[MQTT.org](http://mqtt.org)


!SUB
### My one line description
A lightweight, scalable and portable pub/sub based message protocol that's very easy to implement


!SLIDE

## Lightweight & Portable


!SUB <!-- .element: data-transition="none" -->

## Microcontrollers
![ESP8266](img/ESP8266-ESP01.png) <!-- .element: class="round" -->

!NOTE
The basic implementations are in C, just like any other piece of software this will run no problem on a Raspberry Pi.
But because it's so lightweight it's possible to run it on memory and CPU limited devices as well. It basically runs anywhere.

!SUB <!-- .element: data-transition="none" -->

## Microcontrollers
![Arduino](img/Arduino.png) <!-- .element: class="round" -->

!SUB <!-- .element: data-transition="none" -->

## Single board computers
![Raspberry](img/Raspberry-pi.png) <!-- .element: class="round" -->

!SUB <!-- .element: data-transition="none" -->

## Mobile
![Mobile](img/nexus5.png) <!-- .element: class="round" -->

!SUB <!-- .element: data-transition="none" -->

## Computer
![Laptop](img/laptop.png) <!-- .element: class="round" -->

!SUB <!-- .element: data-transition="none" -->

## Server
![Server](img/server.png) <!-- .element: class="round" -->


!SLIDE
## Scalable


!SLIDE
## Easy to implement


!SLIDE
## Why it's a perfect match for IoT

!SUB
Born from a realistic view at the IoT landscape:

- IoT currently vendor controller
- Many individually connected things that don't work together

!SUB
MQTT is the perfect "glue" to wire all these disconnected things together 


!SLIDE
### Fragmentation
We commit to a common way of communication between components vs commit to the extension mechanism one application offers (or even worse, commit to a monolith)

!SLIDE
### Polyglot!
