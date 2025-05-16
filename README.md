# aventadorII_jp5.1.4

JETPACK 5.1.4 build system for audio on AventadorII<br>
The <b>compile_kernel</b> script creates a dtbo loadable with <b>/opt/nvidia/jetson-io/config-by-hardware.py -n "AventadorII Stonehex NAU8822 Codec"</b><br>
This script download the compiler if not available and all the requested modules<br><br>
The devel machine must have a running http server<br>
The <b>op</b> script should be copied in devel machine's WWW_Root ( /var/www/html on Ubuntu machines )<br>
From the target issue <b>wget <your_server_ip>/op</b> <br>
On the target issue <b>./op</b><br>


