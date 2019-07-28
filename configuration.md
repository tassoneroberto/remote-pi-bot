# Raspberry PI configuration
Guide based on Raspbian Lite Buster os and a Raspberry Pi 3 connected to internet through an ethernet cable.

## Installation
Enable SSH connection:

    cd RASPBERRY_BOOT_VOLUME
    touch ssh
    
## Remote connection
Find raspberry local IP:

    ping raspberrypi.local
    
Connect to the raspberry:

    ssh pi@X.X.X.X
    
Replace X.X.X.X with raspberry local IP address. (N.B: it requires the SSH to be enabled.)

## First settings
Change password:

    passwd

Enter old password (default is ```raspberry```) and choose a new one.