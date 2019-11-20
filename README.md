Collection of configuration files for linux to save (battery) power.
To install, run:

    $ sudo make install

And reboot the computer. This should make powertop happy - showing most tunables as good.

Some of the powersave tunables would still shows as bad:

- "Autosuspend for USB device ..."
  I found it annoying to have usb mouse shut down after some time of inactivity.
- "Enable SATA link power management for ..."
  Powertop wants this setting to be 'min_power', 
  but it is recommended to have it on 'med_power_with_dipm'.

Note this does not enable/disable power saving when on battery/AC power. 
There are other projects to do that.
