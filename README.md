# Gnome-Sound
# Volume: above 100%
https://www.google.com/search?q=gnome+volume+above+100 https://www.reddit.com/r/Fedora/comments/qec6hn/how_can_i_turn_the_volume_above_100/

## dconf
Just an update for anyone else ending up here. Gnome Tweaks no longer does this for Fedora Workstation 39. You'll want to install dconf-editor , navigate to org.gnome.desktop.sound and set allow-volume-above-100-percent to true.

## gsettings
`gsettings set org.gnome.desktop.sound allow-volume-above-100-percent true`
