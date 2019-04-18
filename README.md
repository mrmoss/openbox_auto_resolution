# Openbox Auto Resolution

Terrible openbox auto resolution configuration thingy.

I've been feeling way too spoiled with budgie and gnome...

What's the point of all this computer stuff if it magically fixes my screen for me...

Made for a laptop for when you are plugging into/out of a screen...pretty hacky...

## Dependencies

	sudo package-manager install feh xrandr
	sudo pip3 install parse

## Usage

Usually add a line like this into ~/.config/openbox/autostart:

	openbox_auto_resolution eDP1 DP1 /home/mittens/Pictures/catbox.png

`eDP1` is the "internal" display (laptop screen) and `DP1` is the external display.

Obviously you'd need to put this script in your path and put in the right args...
