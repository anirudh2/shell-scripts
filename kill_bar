#!/bin/sh
# Kills the sleep in dwm_bar.sh to refresh the bar
# Luke Smith's refbar.sh script

kill "$(pstree -lp | grep -- -dwm_bar.sh\([0-9] | sed "s/.*sleep(\([0-9]\+\))/\1/")"
