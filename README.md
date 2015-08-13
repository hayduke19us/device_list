## device_list

---

####To Use Device List

**clone the report some where special**

			git clone https://github.com/hayduke19us/device_list.git

**Adding the command to PATH**

Create a symlink to use it as an executable from the directory where the
executable *note_device* is.

				ln -s $PWD/note_device /usr/local/bin 

In a project parents directory like *Paradigm/field_journal* you might clone the
repo in the */Paradigm* directory


**Options**

				device_list list

Will list the devices in the formatted text file *device_list.txt*


				device_list push

Will push the repo up and update the device list


				device_list 

Will give you two fields, a Device UID and a Device name.

This is used to register devices
[Here](https://developer.apple.com/account/ios/device/deviceCreate.action)
