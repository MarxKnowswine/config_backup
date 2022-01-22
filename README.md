# config_backup
This project aims to backup running configuration from a series of Dell Switches. It may work for other vendors as well.

# Prerequisites
- Python3
- Paramiko for SSH

# Usage
The script takes the output of "show running configuration" command on the switches listed in the "switches_inventory" file.</br> The output is saved on a file named after the hostname or IP address, as specified in "switches_inventory" file</br>
<strong>It is needed to modify:</br>- the destination folder in line 23</br>- credentials in lines 14, 15 and 16</strong>

