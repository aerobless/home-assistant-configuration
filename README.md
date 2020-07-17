# home-assistant-configuration

This repo contains the raw configuration of my personal [Home Assistant](https://home-assistant.io/) instance.
See http://aerobless.github.io/SmartHome for more details on my setup.

## Structure
+ configuration.yaml: Is the main entry point for home assistant
    + config/*: contains sub configurations for various indvidual components such as cameras, lights, plants etc.
    + node-red/*: contains node-red flows, is probably not very useful for sharing since it's not made to be human readable

## What's missing:
These files are not checked into version control on purpose.

+ secrets.yaml: contains all the tokens, ips & passwords referenced by !secret xyz
+ various .dot files
+ known_devices.yaml: list of devices that could be tracked via router
+ custom components
+ themes
+ www: various picture resources