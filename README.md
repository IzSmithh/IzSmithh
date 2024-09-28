Follow mkaisers guide to install "https://github.com/mkaiser/Sungrow-SHx-Inverter-Modbus-Home-Assistant". 
  Do not worry about having the modbus port part in installation process. SG series do not come with it. 
Instead of his modbus_sungrow.yaml, download and use this one. 
Additional steps i took was (not knowing if needed or not)
- Connecting through ethernet cable (to dongle)
- logging into my winet S dongle through its IP Address
- Giving it a static IP 
- while in there, Under System>forwarding Configuration >Modbus,
Port 502 should be switched on by default. 
and i just added my Home Assistants IP to whitelist too.

Hope this saves some new beginner the stress i went through trying to find something that works.
