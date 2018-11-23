# Opti : The recursive image optimization script

A simple script that allows JPEG Optim and Opti PNG to be run in one go, recursively on your server. Based on [StephenPunwasi/jpegoptim-recursive](https://github.com/StephenPunwasi/jpegoptim-recursive).

## How To Use
Install script on your server in the directory you want, then symlink it to `/usr/bin/opti` or any other directory present in your path.

When you want to run it, simply `cd` in the directory you wish to optimize then run `opti`. This script can easily be used to create a cron tab.

## Good to know
When you see any of the following output:

```
jpegoptim: skipping special file: *.jpg
jpegoptim: skipping special file: *.jpeg
jpegoptim: skipping special file: *.JPG
** Processing: *.png
Error: Can't open the input file

** Status report
1 file(s) have been processed.
1 error(s) have been encountered.
```

This simply means that either or both jpegoptim and optipng have not found files to optimized in the folder.

## Requirements

* Linux based system
* jpegoptim installed. 
* optipng installed.
