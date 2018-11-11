Shairplay
=========

Configures shairport-sync + HifiBerry DAC+ on a Raspbian Raspberry PI

Install procedure
-----------------

**On macOS**

1. Burn Raspbian Stretch on SD Card (using Etcher)
2. Mount the card and run `setup-boot.sh`
3. Boot the RPI and check its IP address
4. Configure `inventory`
5. Run `ansible-playbook -i inventory shairplay.yml -K -k`


Reference
---------
https://github.com/mikebrady/shairport-sync/blob/master/INSTALL.md

https://www.hifiberry.com/build/documentation/configuring-linux-3-18-x/

https://www.raspberrypi.org/forums/viewtopic.php?t=21632
