# stress-mouse
A cli autoclicker, an application for automating the mouse clicking process. <br> 
Written in pytohn, looked for adding a GUI but i really suck at it :sweat_smile: :sweat_smile:.

# Tools
* Language:
    * Python 3.6
* Libraries:
    * pyautogui

# Exemple
```
from autoclicker import AutoClicker

# declaring, see autoclicker.py and read the documentation
clicker = AutoClicker(time_lap=2, times=10)
clicker = AutoClicker(time_lap=10, times=None, clicks=1, button='right', pox_x=123, pox_y=444)
clicker = AutoClicker(clicks=2, button='left')

# start the autoclicker
clicker.start()
```

# What is missing
#### To be honest i am not satisfied with it
A GUI, is really missing so please add one, and notify me please, i really want use it witha GUI.<br>
Also, the hotkeys option is really awsome too.