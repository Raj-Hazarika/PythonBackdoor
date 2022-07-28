# PythonBackdoor
- All the scripts are programmed using python3.
- The LinuxListener.py file is responsible to send commands from the hacker (source) device and is ran in kali linux.
- The Backdoor.py file is executed in the target device. 
- ***FOR EDUCATIONAL PURPOSES ONLY***

### LinuxListener.py
- This scripts looks for connections to take place. It is to be executed in the hacker device.
- The ip address of the hacker device and the port number through which you want the connection needs to be mentioned.
- Make sure to install all the required modules before running the script.

### Backdoor.py
- This scripts is required to be executed in the target device. This could be achieved in various way and depends fully upon ones social engineering skills.
- The ip address of the hacker device and the same port number is required to be entered in this script to initialize the connection.
- This script isn't persistent but can be easily done by adding a function to do so.

### What can this backdoor do?
- The backdoor can execute system commands in the target device remotely.
- It can also be used to download files from the target device remotely.
- This script can also upload files to the target device which opens up the possibilty of various other exploits and attacks.
