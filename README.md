# Dual-Monitor-Dashboards / Kiosk

Raspberry pi dual monitor dashboards rotating browser tabs in kiosk mode. Booting directly into kiosk mode chrmium. Perfect for dashboards and build monitors.

<br>

### Features
___

* Selectable Browser (Firefox,Chromium)
* Configurable refresh of the browser (every 5 minutes by default)
* Configurable browser kiosk mode (default off)
* Configurable webpages to be displayed
* Optionally disables browser alert flags for easier monitoring

<br>

### Installation Notes
___

It is easier to setup raspberry pi if you do the following:

```

1.  Manually configure the Wifi
2.  Install openssh-server on the Pi
3.  Enable auto-login on pi configuration
4.  Setup TightVNC for remote graphical interface

```
### Systemd notes
---

Systemd timers are used to schedule the page switch so the resolution can be specified in seconds Systemd has support for integration with the graphical user session (see systemd.special(7), target graphical-session.target) but this integration is not implemented by any of the session managers yet. Instead
