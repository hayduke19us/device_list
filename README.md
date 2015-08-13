## device_list

###WORK IN PROGRESS

**We need encryption**

####To Use Device List

**clone the repo somewhere special**

			git clone https://github.com/hayduke19us/device_list.git

**Adding the command to PATH**

Create a symlink to use it as an executable from the directory where the
executable *note_device* is.

				ln -s $PWD/note_device /usr/local/bin 

In a project parents directory like *Paradigm/field_journal* you might clone the
repo in the */Paradigm* directory


**Options**

				note_device devices

Will list the local devices and their UID'

				note_device list

Will list the devices in the formatted text file *device_list.txt*

				note_device push

Will push the repo up and update the device list

				note_device

Will give you two fields, a Device UID and a Device name. These will be saved in
*device_list.txt* in the following format:

Device UID	Device Name 
888888888   Frank

This is used to register devices
[Here](https://developer.apple.com/account/ios/device/deviceCreate.action)
