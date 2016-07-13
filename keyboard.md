# My keyboard is outputting the wrong characters!

Unlike American software, Raspbian (and NOOBS) defaults to UK keyboard settings. You were given the opportunity to change location settings the first time you started Raspbian, with the `raspi-config` menu.

1. To get the menu back in Raspbian OS, open a terminal window and type `sudo raspi-config`
1. Select **Internationalization** menu
1. Then **keyboard setup** menu.
1. If your exact keyboard is not on the list then choose one of the generic 101, 102, or 104 keyboards. 

If you have a US Keyboard, then you should choose US.

1. The default keyboard layout is English (UK)
1. You will need to scroll down and select **Other** to get back to the **Country of Origin** menu
1. From Country of Origin menu, select **English (US)**
1. From Keyboard Layout menu, scroll to top of list and select **English (US)**. 
1. Complete the other menus then reboot.
