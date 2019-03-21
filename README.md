# rdp_thinbook

Heaphones working -


Download the folder bytcr-rt5651

    Copy directory to UCM location
    sudo cp -rf bytcr-rt5651 /usr/share/alsa/ucm

    Copy asound.state from bytcr-rt5651 directory to /var/lib/alsa
    sudo cp asound.state /var/lib/alsa

    Restart
    
    Connect headphones and test sound via below command :
    speaker-test -t wav -c 6
