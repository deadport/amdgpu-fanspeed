# amdgpu-fanspeed
Tiny bash script to regulate AMDGPU Linux driver fanspeed. Nothing special but practical.

Dependencies: 

- amdgpu driver 
- zenity for -g (graphical mode)
- bash

Insall: 

cd ~ && git clone https://github.com/deadport/amdgpu_fanspeed && cd amdgpu_fanspeed && sudo mv fanspeed /bin/fanspeed && sudo chmod +x /bin/fanspeed && sudo rm -r ~/amdgpu_fanspeed

Usage: 

Just type "sudo fanspeed" for interactive mode.
Use "sudo fanspeed [num 1-255]" to set the fan speed directly. 

-g  = graphical mode using zenity
-G  = continous graphical mode using zenity
-s  = Output current speed
-S  = Output just the current speed (for further processing)

For more sophisticated control try this repo: https://github.com/grmat/amdgpu-fancontrol
