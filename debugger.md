# Debugger

#### Simple 

- `Step over` F8
- `Step into` F7
- `Droop frame` - return to previous step. (don't cahnge global state) 

## Expert debugger 

#### Filters
You can use 'Alt + Enter' on debug line to open popup window with a lot of choises.  
![frame-window](https://github.com/DGarbar/intelij-idea/blob/main/quick-debug-actions.jpg)

- `Caller filter` to fitler which metod needed to be executed before
- `Class filter` to fitler which in wich class executed

#### Non suspending breakpoint

- Use for logging
- Use to change variable (through evaluate). (you can do this manualy in debugger window)


#### Frame window

You can manualy throw/return to emulate behavior

![frame-window](https://github.com/DGarbar/intelij-idea/blob/main/frame-window.jpg)

## Interesting stuff

#### Method breakpoint

You can set breakpoint on method in interface. So we will stop at any call. (Emulated to imrpove speed)
