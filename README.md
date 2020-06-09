# wos-dwm
Wos's version of dwm.

Changes:
* Use Win as ModKey.
* Quiting dmw with ModKey + Shift + E (like i3wm)
* Closing a window with ModKey + Shift + Q (like i3wm)
* Running [rofi](https://github.com/davatorium/rofi) with ModKey + D 
* Decrement the number of master windows with ModKey + O
* Start [Brave](https://brave.com/) with ModKey + B
* Hide bar with ModKey + Shift + B
* Take a screenshot with [Flameshot](https://flameshot.js.org/) with ModKey + S

Applied patches:
* [Swallow](https://dwm.suckless.org/patches/swallow/) - Terminals are replaced the program launched from it. The terminal is resotred after the program is closed.
* [Systray](https://dwm.suckless.org/patches/systray/)
* [Fullgaps](https://dwm.suckless.org/patches/fullgaps/)
