## functions and aliases 

finally have my beautiful cdf back. 

change wallpaper to random img script, using crontab to run that script every 60 minutes 
`$ crontab -e` 
`MAILCHECK=0`
`*/60 * * * * ~/.dotfiles/wallpaper.sh` Possible functionality to scan the images so that images that are bright are shown in the morning and images that are darker are shown at night. Possibly make two scripts: one script that is run from 8am-7pm that has an array of images that are _brighter_ and another script that runs from 7pm-8am that is the opposite.