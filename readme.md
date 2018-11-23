# Opti : The recursive image optimization script

A simple script that allows JPEG Optim and Opti PNG to be run in one go, recursively on your server. Based on [StephenPunwasi/jpegoptim-recursive](https://github.com/StephenPunwasi/jpegoptim-recursive).

## How To Use
Install script on your server in the directory you want, then symlink it to `/usr/bin/opti` or any other directory present in your path.

When you want to run it, simply `cd` in the directory you wish to optimize then run `opti`. This script can easily be used to create a cron tab.

## Requirements

* Linux based system
* jpegoptim installed. 
* optipng installed.
