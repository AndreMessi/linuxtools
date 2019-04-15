# Raspberry pi default configuration and troubleshooting: 

default configuration (`nano /boot/config.txt`):


```
# Force the monitor to HDMI mode so that sound will be sent over HDMI cable
hdmi_drive=2
# Set monitor mode to DMT
hdmi_group=2
# Set monitor resolution to 1024x768 XGA 60Hz (HDMI_DMT_XGA_60)
hdmi_mode=16
# Make display smaller to stop text spilling off the screen
overscan_left=20
overscan_right=12
overscan_top=10
overscan_bottom=10
#audio
dtparam=audio=on
```


audio:
amixer command `amixer cset numid=3 2`


start:

setting time and date
`date --set="2 OCT 2006 18:00:00"`

setting source
`apt update && apt upgrade`



