The X11 window manager for the tiger desktop environment.

Dependencies:
* The same as tinywm - which is what this is based on.

Install instructions:
* Install the dependencies
* Run the following commands:
`git clone https://github.com/Tiger-Desktop-Environment/Tiger-Window-Manager`
`cd Tiger-Window-Manager/src`
`make`
`sudo make install`

Lastly, open up your ~/.xinitrc file, and add this line to the top:
`exec Tiger-Window-Manager`

You will then be able to run the window manager using `startx`.
