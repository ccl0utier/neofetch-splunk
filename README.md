# neofetch-splunk

## Overview

A set of configuration for [neofetch](https://github.com/dylanaraps/neofetch) around Splunk products, intended to spruce up the home lab instances!

Some quick examples:

![image](https://user-images.githubusercontent.com/58239192/191533878-a3be40a7-171c-4065-99d7-6d8ce516bd78.png)

![image](https://user-images.githubusercontent.com/58239192/191534203-74902949-429f-4668-abd1-bf6220af03a6.png)

Of course these can be configured to your liking, simply have a look at the neofetch project [Wiki](https://github.com/dylanaraps/neofetch/wiki) for details.

## Installation

- Install neofetch by following the instructions [here](https://github.com/dylanaraps/neofetch/wiki/Installation)
- Replace/amend your neofetch `config.conf` which is normally under `$HOME/.config/neofetch` with the one provided here
- Review/adapt the settings in the `config.conf` file according to taste or to use the SOAR banner instead of the default Splunk one (look for `image_source` around line 646)
- Call neofetch at login using your terminal/OS favorite method.  For example, by adding a shell script to `/etc/profile.d` that contains the following single line:
```
neofetch
```
