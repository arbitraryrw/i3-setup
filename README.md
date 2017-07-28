# i3-setup
My i3-wm config files, using i3-gaps.

### Requirements
- Running a few Gnome3 utilities
... Working with debian system myself, not mandatory..
- Requires I3
- Works with I3-gaps also

### usage
install window manager
sudo apt-get install i3

show current window managers
ls /usr/share/xsessions/

set the window manager in linux
sudo update-alternatives --install "/usr/bin/x-session-manager" "x-session-manager" "/usr/bin/i3" 1


check window manager then choose the number
update-alternatives --config x-session-manager

edit config:
/etc/i3/config

for my config I need to change things from ~/.i3 to ~/.config/i3
and install
compton
fonts awesome
rofi
