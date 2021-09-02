# Lenovo Thinkpad W540 hackintosh

## Clover Bootloader

### Tested system
- Thinkpad W540
- CPU: i7-4900MQ (Haswell)
- iGPU: Intel HD Graphichs 4600
- dGPU: Nvidia Quadro K2100M (can't be used to drive display for internal monitor)
- LAN: Intel I217-LM
- Wireless: Intel Wireless 7260
- Sound: Realtek ALC292

### Lasted support version: MacOS BigSur 11.2.3 (later version not compatible with this hardware)


### Issue
- Sleep
- Strong white noise from audio jack when waking up from sleep (reboot solves)
- If you use Catalina or earlier, wifi will not work. Use https://github.com/win1010525/Airportitlwm-kext instead Airportitlwm.kext
