# Playing Podracer on PC with queenkjuul

## RadminVPN

First off you gotta install the Radmin VPN. 

[Download it from here](https://www.radmin-vpn.com/)

then install it. In the app, go to Network at the top, then Join an Existing Network.

Join a Private Network not a Gaming Network

Network name is `queenkjuul`
password is in the discord server

## download the patch

it is available [here](assets/Podracer_Patch.zip)

## run the patch

1. Copy setup.bat and SWEP1RCR.EXE.patched to your game folder (should be C:\GOG Games\STAR WARS Racer)
2. run setup.bat
3. select your monitor's resolution in the first window
4. select "Famatech RadminVPN Ethernet Adapter" at the top of the second window

## create a shortcut

the game was written in the days of dialup, so we need to give tell the game to use more bandwidth or else movement online will be all jerky

the easiest way to do this is to create a shortcut which will tell the game to run with different options. 

1. right-click SWEP1RCR.EXE and select "Create Shortcut"
2. right-click the new "SWEP1RCR.EXE - Shortcut" file and select Properties
3. in the "Target" box, add `-nut 5` to the end of the line. You need to put it at the very end, outside the quotes. Mine reads like: 
   
    ```"C:\GOG Games\STAR WARS Racer\SWEP1RCR.EXE" -nut 5 -i```

    The `-i` is to skip the cutscenes. you might want to watch the cutscenes. you're wrong. you'll thank me later. 

![](assets/shortcut.png)

4. Move that shortcut file to the desktop, stick it in your startmenu, whatever you wanna do. Make sure you use that shortcut when launching the game. 

## Tips

I have my control mapping file [here](assets/current_control.zip). Extract it and replace the `(game folder)/Data/config/current/current_control.map` file there. My controls are as follows (x360 controller)


A: Boost

B: Break

X: Slide

Y: Repair

L1: Roll Left

R1: Roll Right

L2: Brake

R2: Thrust

Dpad Up: Camera

Dpad Down: Look Back

Dpad Left: Taunt


TURN THE VOLUME DOWN IN WINDOWS MIXER FIRST it's crazy stupid loud

If your camera gets stuck looking backwards, hit Tab