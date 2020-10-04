# Xdotool

> xdotool lets you programmatically (or manually) simulate keyboard input and mouse activity, move and resize windows, etc
> https://github.com/jordansissel/xdotool
- Click 10 times with a delay of 1 second:

`xdotool click --repeat 10 --delay 100 1`

- Send Ctrl-s to active window:

  `xdotool key ctrl+s`

- Move mouse to center (1920x1080):

  `xdotool mousemove 960 540`
  
- Send Ctrl-q to all windows with the name "firefox":

  `xdotool search --name firefox key ctrl+q`
  
- Send Ctrl+d to the first clicked window:
  
  `xdotool selectwindow key ctrl+s`
