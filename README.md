# P4wnP1-The-Bee-Movie
Example of moving the entire bee movie script from a pre-saved file on the Pi

Using GenImage you are able to create files that are stored on the Pi from the moment you boot. Being able to movie large amounts of text could be useful in scripts such as the "Wifi Covert Channel" where there is a long string that the P4wnP1 has to type out. This hid script opens a target window (command prompt, Powershell, notepad, ect...) as well as the file location containing the text you stored on the pi, it then opens, copy, and then pastes the text into the target window. Though slow I could see some uses for this type of script. This example contains the entire bee movie script and copies the text from the pi into a new notepad document. (windows only)

For setup, place the .Bin file into /usr/local/P4wnP1/ums/flashdrive. Save the script to the hid script section, enable Usb Mass Storage and select the image you just uploaded. Then create a trigger action that runs the script on connection to a device. Create a master template with the usb and trigger action settings and reboot.
