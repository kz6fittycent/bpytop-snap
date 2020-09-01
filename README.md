# bpytop-snap
## A snap for bpytop

[![bpytop](https://snapcraft.io//bpytop/badge.svg)](https://snapcraft.io/bpytop)

# Install the snap

`sudo snap install bpytop`

# Resource monitor that shows usage and stats for processor, memory, disks, network and processes.
## Python port of bashtop
  
    - Easy to use, with a game inspired menu system.
    - Fast and "mostly" responsive UI with UP, DOWN keys process selection.
    - Function for showing detailed stats for selected process.
    - Ability to filter processes.
    - Easy switching between sorting options.
    - Send SIGTERM, SIGKILL, SIGINT to selected process.
    - UI menu for changing all config file options.
    - Auto scaling graph for network usage.
    - Shows message in menu if new version is available
    - Shows current read and write speeds for disks
    - Multiple data collection methods which can be switched if running on Linux
  
# Once installed, run the following commands to so the snap will function as intended:
```        
    sudo snap connect bpytop:mount-observe
    sudo snap connect bpytop:network-control
    sudo snap connect bpytop:hardware-observe
    sudo snap connect bpytop:system-observe
    sudo snap connect bpytop:process-control
    sudo snap connect bpytop:physical-memory-observe
```    
## You can make changes to the configs and even add themes here:

`~/snap/bashtop/current/.config/bpytop`
