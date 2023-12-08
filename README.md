# DSO-138

Latest Jyetech update version 113-13801-066 for DSO-138. This version fixes triggering at 50ms and below, trigger LED, and removed fake product warning.

![dso138-066-1](https://github.com/kittenarmy/DSO-138/assets/9025713/5cb8baa6-32a2-449d-817b-ca4eebaf2304)
![ds0138-066-2](https://github.com/kittenarmy/DSO-138/assets/9025713/3a7959fe-5246-4c8c-bcd6-2761b3403707)

Forum thread:
https://forum.jyetech.com/viewtopic.php?f=18&t=1101

Flash instructions via UART pins (requires soldering/desoldering JP1 and JP2 jumpers):
https://jyetech.com/wp-content/uploads/2018/07/dso138-firmware-upgrade.pdf

Alternate flashing using SWD pins via ST Link type adapter: 

Install [drivers](https://www.st.com/en/development-tools/stsw-link009.html#get-software) and [STM32 Link Utility](https://www.st.com/en/development-tools/stsw-link004.html#get-software) (you may need to reboot after for the adapter to be visible)

* Connect ST Link adapter to SWD pins
* Connect ST Link software to DSO-138 (Target>Connect in menu) 
* Open hex file File>Open 
* Select Target>Program & Verify

![stlink1](https://github.com/kittenarmy/DSO-138/assets/9025713/2a6d48bc-b591-47fa-bd5e-5a4c7bed08e8)

