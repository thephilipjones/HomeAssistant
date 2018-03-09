# Home Assistant configuration

This is the live working configuration of my Smart Home.

## System

A Raspberry Pi server is the backbone. It runs:
* Home Assistant
* Homebridge
* Unifi Controller

## Bridges
This requires a few extra hubs/bridges:
* Philips Hue Bridge
* Linear HUSBZB-1 Z-Wave + Zigbee hub
* August Connect

## Control
Several methods of accessing these features include:
* Downstairs Echo - Alexa
* Bedroom Echo - Alexa
* Downstairs iPad Mini - Apple Home / Hue / Spotify

## Network
I'm all in on UniFi. I have:
* UniFi Security Gateway - router
* UniFi US-8-60W - core NOC switch
* UniFi US-8-60W - main floor switch
* UniFi AP-AC-Pro - main floor wifi
* Motorola MoCA adapters - connect NOC to main floor
* Apple Airport Extreme / 2TB Time Capsule - Time Machine backups
* Apple Airport Extreme / old version - NOC device switch
* ASUS RT-66U - main floor VPN client switch + wifi