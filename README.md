# virturalbox
virtural learning notes

How you can enable copy-paste between your host and VirtualBox virtual machine:

### 1. Install Guest Additions
1. **Start Your Virtual Machine**:
   - Launch your virtual machine in VirtualBox.

2. **Insert Guest Additions CD Image**:
   - In the VirtualBox window, go to the menu and click on `Devices`.
   - Select `Insert Guest Additions CD Image...`.

3. **Run the Installer**:
   - If the AutoPlay window pops up in the virtual machine, click `Run VBoxWindowsAdditions.exe`.
   - If AutoPlay doesn’t appear, open `This PC` or `My Computer`, locate the VirtualBox Guest Additions CD (it should show as a CD icon), and double-click it.
   - Find and double-click `VBoxWindowsAdditions.exe` to start the installation manually.

4. **Follow the Installation Wizard**:
   - The installer will start. Click `Next` to proceed through the steps.
   - If a security prompt appears asking if you want to install the drivers, click `Install`.

5. **Finish the Installation**:
   - Once the installation is complete, you will be prompted to reboot the virtual machine. Click `Reboot`.

### 2. Enable Shared Clipboard and Drag and Drop
1. **Shut Down the Virtual Machine**:
   - Ensure the virtual machine is turned off.

2. **Configure Settings**:
   - In the VirtualBox main window, select your virtual machine and click `Settings`.
   - Go to the `General` section and select the `Advanced` tab.
   - Set `Shared Clipboard` to `Bidirectional`.
   - Set `Drag’n’Drop` to `Bidirectional`.

### 3. Restart the Virtual Machine
- After making these changes, restart your virtual machine.

### 4. Confirm the Installation
- Once the virtual machine has restarted, you should see the VirtualBox Guest Additions icon in the system tray.
- Test the copy-paste functionality to ensure it’s working correctly.
