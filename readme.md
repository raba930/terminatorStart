# Terminator start script

## Instalation
1. You need to install gawk:
	sudo apt-get install gawk
2. Copy terminatorStart file to `/usr/bin`
3. Make script executable (go to `/usr/bin` in your terminal and type command below)
	chmod +x terminatorStart

## Recommended tweaks
1. Create `start` layout and insert `terminatorStart && exit` in `Custom command` input field
![ss](https://github.com/raba930/terminatorStart/media/startLayout.png)
2. Create custom launcher with command `terminator -l start` and replace it with yout current terminal launcher icon