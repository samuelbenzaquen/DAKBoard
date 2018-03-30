# DAKBoard
https://blog.dakboard.com/diy-wall-display/
 - sudo apt-get install unclutter
 - if it does not work you may need to uncomment the source by 'sudo nano /etc/apt/sources.list'
 - sudo nano ~/.config/lxsession/LXDE-pi/autostart
 - Change the content with:
@xset s off
@xset -dpms
@xset s noblank
@chromium-browser --noerrdialogs --incognito --kiosk http://dakboard.com/app/?p=
