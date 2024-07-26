## fix error (remote server display not supported e.g Wayland)

## Step 1: nano /etc/gdm3/custom.conf
## Step 2: Edit & Add the custom.conf file
    WaylandEnable=false
    AutomaticLoginEnable=true
    AutomaticLogin=$USERNAME

## Step 3: Reboot the machine
    sudo reboot
