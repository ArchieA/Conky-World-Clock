# README

![](conky/screenshot.webp)

## Overview

**Conky World Clock** initially started from a post on a [**PCLinuxOS Support Forum**](https://www.pclinuxos.com/forum/index.php/topic,162134.msg1402984.html#msg1402984).

Frankly, I would consider this a personal project. It still has ways to go to becoming available to GUI users.
***

## Quickstart
#### Download
```Plain&#x20;Text
git clone https://github.com/ArchieA/Conky-World-Clock
```
You will need to move and rename the folder Conky-World-Clock/conky to ~/.conky
and the file Conky-World-Clock/conky-worldclock to ~/.conky-worldclock .

You will also need to install Conky-World-Clock/fonts/{clockfaces.ttf, zoraclockH.ttf and zoraclockM.ttf

You should also modify ~/.conky-worldclock line #39 to your geolocation. If you don't know your geolocation, there are several ways to find out.

#### Running the widgets

In your terminal of choice:

```Plain&#x20;Text
conky -c ~/.conky-worldclock
```
The above command should work on any desktop environment, and should launch the widget on the top left corner of your display.

