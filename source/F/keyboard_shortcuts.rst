*****************************
Appendix F Hotkeys shortcuts
*****************************

Hotkeys, also known as keyboard shortcuts, allow users to easily navigate, start applications, and change settings like resize windows. These are useful as they create a smooth and time efficient user experience. It would benefit users to take a few minutes to learn some of these shortcuts.

Lubuntu has manages the keyboard shortcuts using two layers. Namely, LXQt Global Keys and Openbox.

Global-keys
--------------

Global-keys (lxqt-globalkeysd) is a component of the LXQt environment. Global-keys takes preference over Openbox keyboard shortcuts. Global keys are viewed, (dis)enabled and managed using Shortcut keys (Chapter 3.2.14).

Openbox keyboard shortcuts
-------------------------------
Openbox keyboard shortcuts is the second layer managing keyboard shortcuts. It is preferred for windows management like resizing. To change these settings see this link on the `openbox wiki bindings <http://openbox.org/wiki/Help:Bindings>`_

.. note::   Global-keys will take preference over openbox bindings. If a key is used in Global-keys, it will not work in Openbox keyboard shortcuts. For example if the W(indows) key opens the LXQT application menu (equivilant of the windows start menu) in Global-keys, Openbox commands like window resizing (W + arrow keys) will not work correctly. Keep this in mind when using and editing keyboard shortcuts. 

The table below shows Lubuntu's default Openbox keyboard shortcuts:

**Modifier keys** 	

Key     description

====    ========================
S 	     Shift key

C 	     Control key

A 	     Alt key

W 	     Super key (Usually bound to the Windows key on keyboards which have one)

M        Meta key

H 	     Hyper key (If it is bound to something) 
====    ========================

**Keybindings for desktop switching**

============================= ========================

GoToLeftDesktop               C-A-Left

GoToRightDesktop              C-A-Right

GoToDesktop                   C-A-Up

GoToDesktop                   C-A-Down

SendToDesktoaToLeft           S-A-Left

SendToDesktopToRight          S-A-Right

SendToDesktop                 S-A-Up

SendToDesktop                 S-A-Down

GoTo first Desktop            W-F1

GoTo second Desktop           W-F2

GoTo third Desktop            W-F3

GoTo fourth Desktop           W-F4

ToggleShowDesktop             W-D

============================= ========================

**Keybindings for windows**

============================= ========================

Close                         A-F4

Lower (minimise)              A-Escape

ShowMenu                      A-space

============================= ========================

**Keybindings for window switching**

============================= ========================

NextWindow                    A-Tab

PreviousWindow                A-S-Tab

NextWindow                    C-A-Tab

============================= ========================

**Keybindings for window switching with the arrow keys**

============================= ========================

DirectionalCycleWindows       W-S-Right

DirectionalCycleWindows       W-S-Left

DirectionalCycleWindows       W-S-Up

DirectionalCycleWindows       W-S-Down

============================= ========================

**Keybindings to toggle fullscreen**

============================= ========================

ToggleFullscreen              F11

============================= ========================

============================= ========================

Pcmanfm                       W-e

============================= ========================

============================= ========================

Launch lxqt-runer             W-r

============================= ========================

**Launch task manager on Ctrl + Alt + Del**

============================= ========================

Open qps                      C-A-Delete

============================= ========================

**Launch a terminal on Ctrl + Alt + T**

============================= ========================

Open qterminal                 C-A-T
============================= ========================

============================= ========================

Launch firefox                XF86WWW

Open qterminal                XF86Terminal


============================= ========================

**Keybinding for computer button**

============================= ========================

Open pcmanfm-qt               XF86MyComputer

============================= ========================

**Keybinding for backlight**

============================= ========================

Toggle turn off monitor       C-F7

Decrease backlight brightness C-S-F6

Increase backlight brightness C-S-F7

============================= ========================

**Keybindings fo Volume**

============================= =========================

Decrease Volume               XF86VolumeLower

Increase Volume               XF86VolumeRaise

Mute Volume                   XF86AudioMute

============================= =========================


