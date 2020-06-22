# SLiM FreeBSD dark theme 

### What is SLiM?
[SLiM](https://sourceforge.net/projects/slim.berlios/) is an acronym for "Simple Login Manager". Lightweight and easily configurable, SLiM requires minimal dependencies, and none from the *GNOME* or *KDE* desktop environments. It therefore contributes towards a lightweight system for users that also like to use lightweight desktops such as *Xfce*, *Openbox*, and *Fluxbox*. 

### FreeBSD Installation

```sh
$ pkg install slim
```
For the file */etc/rc.conf.local*, add the following:

```
slim_enable="YES"
```

### How to use

Clone this repository and, then copy this directory (slim-freebsd-theme) into the */usr/local/share/slim/themes/* path. 
Modify the slim configuration at ***/usr/local/etc/slim.conf*** with the following:

```sh
#current_theme      default
current_theme       slim-freebsd-dark-theme
```
### Preview

![img](https://raw.githubusercontent.com/gocobachi/slim-freebsd-theme/master/screenshot.png)


### Support
<p align="left">
<a href="https://www.paypal.me/gocobachi" target="_blank"><img alt="undefined" src="https://img.shields.io/badge/paypal-gocobachi-red?style=for-the-badge&logo=paypal"></a>
</p>

