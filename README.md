# amdgpu_fanspeed
Tiny bash script to regulate AMDGPU Linux driver fanspeed. Nothing special but practical.

Insall: 

cd ~ && git clone https://github.com/deadport/amdgpu_fanspeed && cd amdgpu_fanspeed && sudo mv fanspeed /bin/fanspeed && sudo chmod +x /bin/fanspeed

Usage: 

Just type "sudo fanspeed" for interactive mode.
Use "sudo fanspeed [num 1-255]" to set the fan speed directly. 
