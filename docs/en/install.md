# Install LiveG OS to a device
If a device you have does not run LiveG OS yet, you'll need to install LiveG OS to that device's internal storage. These steps must be followed if your device either has no operating system installed (where you get an error message when trying to turn it on), or has a different operating system installed (such as Microsoft Windows).

> **Note:** If you have purchased a new device that comes with LiveG OS, then you do not need to follow these steps. Check out [our guide on setting up a device running LiveG OS](setup.md) instead.

## Before we start
You will need a storage device handy to install LiveG OS with (such as a USB memory stick). Make sure that the storage device is compatible with the device you want to install LiveG OS on.

Once you have found a storage device, you will need to then format it and copy LiveG OS Setup onto it. This can be done by visiting [liveg.tech/os](https://liveg.tech/os) and downloading LiveG OS. Further steps on how to copy LiveG OS to your storage device are listed on that page.

> **Warning:** Copying LiveG OS Setup requires all data on the storage device to be erased beforehand. Ensure that you backup the storage device to somewhere else before you copy LiveG OS to it.

## Setup procedure
The following steps below will need to be followed to install LiveG OS.

### 1. Turn off the device if you haven't done already
Refer to your device's user guide for more help on shutting down or otherwise turning off the device.

If your device runs Microsoft Windows, hold down the <kbd>Shift</kbd> key while shutting down the system. This allows the BIOS/boot menu to be accessed when the device is turned on again.

### 2. Connect the storage device containing LiveG OS to the installation device
If you have a USB memory stick with LiveG OS installed onto it, plug the memory stick in.

### 3. Start up the device and choose options to boot to LiveG OS
When powering on the device, you will need to tell the device to boot to the connected storage device instead of internal storage. This is typically done on many device by holding down a keyboard key or by pressing a combination of volume or power buttons.

This procedure varies depending on the device and who manufactured it, so refer to your device's user guide for more help on this, or contact your supplier or manufacturer.

For the device models made by the following manufacturers, you will need to do the following when the manufacturer's logo appears on the device's screen:

* **Acer**: Hold the <kbd>F2</kbd> key (or <kbd>Del</kbd> on some models). For most models, use the arrow keys to navigate to **Boot**, then select the relevant storage device.
* **Asus**: Hold the <kbd>F2</kbd> key. When the BIOS interface appears, press <kbd>F8</kbd>, then select the relevant storage device.
* **Dell**: Hold the <kbd>F2</kbd> key. For most models, use the arrow keys to navigate to **Boot**, then select the relevant storage device.
* **HP**: Hold the <kbd>F9</kbd> key, then select the relevant storage device using the keyboard. For some models, you may need to access the BIOS menu via the <kbd>F10</kbd> or <kbd>F1</kbd> buttons.
* **Lenovo/ThinkPad**: Hold the <kbd>FN</kbd> + <kbd>F12</kbd> keys. For most models, use the arrow keys to navigate to **Startup**, then select the relevant storage device. For some models, <kbd>FN</kbd> + <kbd>F2</kbd> must be used instead.

### 4. Wait for LiveG OS to boot
This should take less than a minute. Your device will have booted when the LiveG OS Setup language selection screen appears.

### 5. Select your language
LiveG OS will show a list of languages that will be used throughout the system. From this list, select **English**.

### 6. Choose language settings
Once you have chosen your language, you will be further asked what language region/variation you wish to read text in, in addition to the keyboard layout you wish to use to input text.

For example, if you speak British English, you would select **English (United Kingdom)** for **language region/variation** and **British QWERTY** for **keyboard layout**.

Once you are happy with the chosen settings, press **next**.

### 7. Choose the option to install LiveG OS
Choose the **install LiveG OS to internal storage** option.

If you wish to try out LiveG OS before installing it, you can choose the **try out LiveG OS before installation** option, but you will need to restart these steps from step 1 when you want to install LiveG OS.

### 8. Choose the internal disk to install to
Choose the disk you wish to install LiveG OS to from the list of options, and then press **next**.

The total size of each disk is displayed under each option so that it is easier for you to match the correct disk (the disk size may also be labelled on the box your device came with).

### 9. Choose a disk partition to install to
We recommend choosing the **erase entire disk and install LiveG OS** option as this will remove any partitions that were used only for the old operating system that was previously installed on the device.

Advanced users may wish to choose another option to allow dual-booting.

Once an option has been chosen, press **next**.

### 10. Confirm installation
When you are ready to start the installation process, press **confirm**. If you wish to review the options you have chosen, press **previous**.

> **Warning:** While LiveG OS is being installed, data on the respective disk chosen previously will be erased. Ensure that you backup any important data you wish to keep to another device before beginning installation.

### 11. Wait for installation to complete
This step should take a few minutes to copy LiveG OS to internal storage and configure your device to correctly boot into LiveG OS when you turn it on.

You cannot cancel the installation while it is running.

### 12. Restart the system
Once installation is complete, the system will restart after 10 seconds so that you can continue setting up your device. You can alternatively press **restart** to immediately restart the system.

When the system restarts, we recommend configuring the boot options at startup again to ensure that LiveG OS boots from internal storage. Once restarted, the installation storage device can be removed.

When the system has finished booting, continue setting up your device by following the [setup instructions](setup.md).