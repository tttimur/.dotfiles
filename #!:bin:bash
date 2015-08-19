#!/bin/bash

files=(~/Pictures/*)
ranImg="${files[RANDOM % ${#files[@]}]}"
sqlite3 ~/Library/Application\ Support/Dock/desktoppicture.db "update data set value = '$ranImg'" && killall Dock 