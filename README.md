## EX 6: MOVING FILES BETWEEN VIRTUAL MACHINES

### Aim:
To move the files between virtual machine.

You can move files between virtual machines in several ways:
- You can copy files using network utilities as you would between physical computers on your network. To do this between two virtual machines:
- Both virtual machines must be configured to allow access to your network.
- Any of the networking methods (host-only, bridged and NAT) are appropriate.
- With host-only networking, you copy files from the virtual machines to the host and vice-versa, since host-only networking only allows the virtual machines see your host computer.
- With bridged networking or NAT enabled, you can copy files across your network between the virtual machines.
- You can create a shared drive, either a virtual disk or a raw partition, and mount the drive in each of the virtual machines.

Procedure:  
        How to Enable File sharing in VirtualBox.

Step 1. Install Guest Additions on the Guest machine.  
Step 2. Configure File Sharing on VirtualBox.

Step 1. Install Guest Additions on the Guest machine.
1. Start the Virtuabox Guest Machine (OS).
2. From Oracle's VM VirtualBox main menu, select Devices > Install Guest Additions *

a. Open Windows Explorer  
b. Double click at the "CD Drive (X:) VirtualBox Guest additions" to explore its contents.

![image](https://github.com/user-attachments/assets/d3dbb341-38c1-4f3e-92f7-0cfe1084e679)

C. Right click at "VBoxWindowsAdditions" application and from the pop-up menu, choose "Run as administrator".

![image](https://github.com/user-attachments/assets/35be1b73-df5c-445e-bb24-94d71f7898e4)

3. Press Next and then follow the on screen instructions to complete the Guest Additions installation.

![image](https://github.com/user-attachments/assets/066c93ef-f2fa-40e8-a8f2-041ca2758db1)

4. When the setup is completed, choose Finish and restart the Virtuabox guest machine.

Step 2. Setup File Sharing on VirtualBox Guest Machine.
1. From VirtualBox menu click Devices and choose Shared Folders -> Shared Folder Settings.

![image](https://github.com/user-attachments/assets/c58d8e37-8a75-47ad-bdc8-800ff55b2ccf)

2. Click the Add new shared fol
