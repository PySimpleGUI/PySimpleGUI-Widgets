# PySimpleGUI-Widgets
Rainmeter-like Widgets for your desktop using the easy to use PySimpleGUI package

You will need to install PySimpleGUI for any of these widgets to execute.

## List of Widgets

--------

NOTE - The COVID19 Widget has been removed.  The data sources were changed and it no longer properly worked. Sorry about that!

--------------------

## System Status Dashboard

Displays some stats found via the psutil package (required)

![System Status Dashboard](https://user-images.githubusercontent.com/46163555/83331138-38b37080-a262-11ea-83a6-3864f7b8291e.gif)

This is one of the older programs.  Hopefully the coding conventions are up to date.

It uses a class to define the individual graphs which is likely a great way to have done it.  It's worth a look to see if it gives you some ideas.  Only recently re-discovered.

---------------------


## Weather - Current Weather Conditions

You will need to obtain an API key (APPID) from https://home.openweathermap.org/ in order to run this Widget.

Change the colors to any of the PySimpleGUI Themes.

Your key and location are saved in a config file (.CFG).  Any time you change the key or the location it will be saved in your config file.

![SNAG-0649](https://user-images.githubusercontent.com/46163555/76476971-3ddaef00-63da-11ea-8e7e-3aafb1485185.jpg)


-------------------------

## CPU Core Usage

This one uses psutil to graph the CPU time used by each of your CPU's cores.

![PSG CPU Cores Scrolling](https://user-images.githubusercontent.com/46163555/72114378-52830400-3311-11ea-8584-32bde5c265db.gif)

