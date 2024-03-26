# ArchISO OBL (Obviously Basic Linux)

A custom Arch Linux ISO Maker based off archiso's releng profile with personal addition.

## Instructions

* Clone this repo.

## Introduction

This contains script to build arch linux based isos. Slightly personalized as per my needs.

## How to build ISO

You need to use an arch based system.

General information: 

https://wiki.archlinux.org/title/archiso

### Install build dependencies

```
sudo pacman -S archiso git squashfs-tools --needed
```
It is recommended to reboot after these changes.

### Build

* Run `$ sudo ./build.sh -v`
* This will run the mkarchiso command to build the iso, iso will be generated in the current directory.

## Customizing your ISO

The iso can be changed as per your configuration.

## Installing your system

Burn the generated ISO to a DVD or an USB stick.
