<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="logo.png">
  <img alt="Logo" src="logo.png" height="150px">
</picture>
<br>
Asus® Battery Health Switcher
</div>
<br>

# Asus® Battery Health Switcher
KDE Plasma widget to configure the Battery Health Charging feature in compatible Asus® laptops.  
For more information see [ASUS Battery Health Charging](https://www.asus.com/us/support/FAQ/1032726/)

Keep in mind that according to some reports of users on the Internet this mode is automatically disabled after rebooting. 
To make it permanent you can do it for example with a cronjob or with Systemd **(with either of these two ways you would not need this widget)**. See [Battery Charging limiter Linux (ASUS Laptops)](https://github.com/sreejithag/battery-charging-limiter-linux) or [Enable Asus Battery Health Charging (Charging Threshold) in Linux](https://www.youtube.com/watch?v=BacV_hvaXfU).

## Install

### Dependencies

- One of the following tools is required for notifications to work. Note that in many distros at least one of the two is installed by default, check it out.
  - [notify-send](https://www.commandlinux.com/man-page/man1/notify-send.1.html) - a program to send desktop notifications.
  - [zenity](https://www.commandlinux.com/man-page/man1/zenity.1.html) - display GTK+ dialogs.

### From KDE Store
You can find it in your software center, in the subcategories `Plasma Addons > Plasma Widgets`.  
Or you can download or install it directly from the [KDE Store](https://store.kde.org/p/2075212/) website.

Note that there are two versions:
- Version `0.0.1` only gives two possible modes, `on` (60%) or `off` (100%).
- The other version gives three possible modes, `maximum` (60%), `balanced` (80%) and `full` (100%).

### Manually
- Download/clone this repo.
- Run from a terminal the command `kpackagetool6 -t Plasma/Applet -i [widget folder name]`.

## Disclaimer
I'm not a widget or KDE developer, I did this by looking at other widgets, using AI chatbots, consulting documentation, etc. So use it at your own risk.
Any recommendations and contributions are welcome.

## Screenshots

![Screenshot_20240804_163702](https://github.com/user-attachments/assets/1d725319-f59c-4ce7-9e8a-23c2d5f53074)

