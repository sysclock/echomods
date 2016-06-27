# Module: Croaker

![](/croaker/viewme.png)

## Name

[`MDL-probe_echomods_controler_croaker`]()

## Title

The controler heart of the echOmods

## Description

* A Pi/BBB/STM32...
* version: V0.1
* date: 27/06/2016
* technology: n/a
* language: n/a
* author: Kelu124

## IOs

### Inputs

* `ITF-A_gnd`
* `ITF-B_5v`
* `ITF-mEG_SPI` : signal from the ADC

### Outputs

* `Screen`
* `WiFi`

## Key Components

* `BBB` : see notes
* `Pi Zero` : see notes

## Information

### What is it supposed to do?


The aim of this echOmod is to receive the signal and process it.


### How does it work: block diagram

![Block schema](source/blocks.png)

* `ITF-mEG_SPI`->`Pi Zero`->`WiFi`
* `Pi Zero`->`Screen`


## About the module

### Pros

* Building on existing techs and communities

### Cons

* Need to find a real-time solution

### Constraint and limits

* A series of work has been done on ![EMW3165](notes_EMW3165.md),  ![ESP8266](notes_ESP8266.md), ![Raspberry Pi Zero](notes_RPi0.md), ![feather WICED](notes_feather_WICED.md), 

* A recap of microcontrolers has been added [here](notes_uC.md)

## Discussions


### TODO

* Choose the platform (BBB, RPi0, STM32, ... ?)
* Getting some codes
* Getting some images
* Getting images onto a screen

### DONE

* Nothing

### People

* ??

## License

### Croaker 

The [echOmods project](https://github.com/kelu124/echomods) and its prototypes (amongst which we find the [croaker](/croaker/) module) are open hardware, and working with open-hardware components.

Licensed under TAPR Open Hardware License (www.tapr.org/OHL)

Copyright Kelu124 (luc@echopen.org / kelu124@gmail.com ) 2015-2018

### Based on 

The following work is base on a previous TAPR project, [Murgen](https://github.com/kelu124/murgen-dev-kit) - and respects its TAPR license.

Copyright Murgen and Kelu124 (murgen@echopen.org , luc@echopen.org / kelu124@gmail.com ) 2015-2018
