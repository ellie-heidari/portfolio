---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: ["embedded","firmware"]
categories: ["projects"]
summary: "One-line outcome and main challenge."
Project:
  Role: "Firmware"
  MCU: "ATmega1280"
  Toolchain: "avr-gcc, CMake"
  Interfaces: ["UART","I2C","SPI"]
  Highlights: ["XON/XOFF state machine","CRC16 integrity","EEPROM paging"]
resources:
  - name: hero
    src: "images/{{ .Name }}/hero.png"
---
## Problem
Describe system, constraints, target KPIs.

## Approach
Bullets of architecture, drivers, protocols.

## Key challenges
Latency, timing, EMI, memory, etc.

## Results
Numbers, reliability, measured data.

## Code
Link to repo.

