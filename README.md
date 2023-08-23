# Supervisor UI Bootstrap Theme
Clone git repo

```
root@srv:~# git clone git@github.com:blackbunny/supervisor-theme.git
root@srv:~# cd supervisor-theme
```

find your supervisor system directory

```root@srv:~# dpkg -L supervisor|grep ui/
/usr/lib/python3/dist-packages/supervisor/ui/images
/usr/lib/python3/dist-packages/supervisor/ui/images/button_refresh.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/button_restart.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/button_stop.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/icon.png
/usr/lib/python3/dist-packages/supervisor/ui/images/rule.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/state0.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/state1.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/state2.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/state3.gif
/usr/lib/python3/dist-packages/supervisor/ui/images/supervisor.gif
/usr/lib/python3/dist-packages/supervisor/ui/status.html
/usr/lib/python3/dist-packages/supervisor/ui/stylesheets
/usr/lib/python3/dist-packages/supervisor/ui/stylesheets/supervisor.css
/usr/lib/python3/dist-packages/supervisor/ui/tail.html
```

copy your pulled directory content to  `/usr/lib/python3/dist-packages/supervisor/ui/`
