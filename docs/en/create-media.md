# Create LiveG OS installation media
To install LiveG OS to an existing device, you will need to copy LiveG OS to a portable storage device (such as a USB memory stick) that can be connected to the target device.

Visit [liveg.tech/os/get](https://liveg.tech/os/get) to learn more about the minimum requirements that the storage device must meet.

LiveG OS cannot be copied to the storage device by simply copying the file across to the device's filesystem. Instead, the whole storage device must be erased and _flashed_, which correctly copies LiveG OS Setup so that it is bootable on the target device. This can be done with third-party software, as instructed later on in this guide.

Before starting, download LiveG OS to a computer (this can be the computer you wish to install LiveG OS onto). We will then copy the ISO file (.iso) to the storage device using one of the available programs listed below. Ensure that your storage device is connected to this computer.

> **Warning:** Copying LiveG OS Setup requires all data on the storage device to be erased beforehand. Ensure that you backup the storage device to somewhere else before you copy LiveG OS to it.

## Using balenaEtcher
balenaEtcher is compatible with devices running Windows, macOS or Linux.

Download balenaEtcher from [balena.io/etcher](https://www.balena.io/etcher/) and install it to a computer (this can be the computer you wish to install LiveG OS onto).

Open balenaEtcher and press **flash from file**. Select the LiveG OS ISO file from the file picker. Once the file is chosen, select the storage device to copy the ISO file to by pressing **change** if it isn't selected already. Finally, press **flash!** and wait for copying to complete. Once complete, eject the storage device, from which it will be ready for use.

For more help and support with using balenaEtcher, visit [balena.io/etcher](https://www.balena.io/etcher/).

## Using Rufus
Rufus is compatible with devices running Windows only.

Download Rufus from [rufus.ie](https://rufus.ie/) and install it to a computer (this can be the computer you wish to install LiveG OS onto).

Open Rufus and select the storage device from the **device** list. Under **boot selection**, select **disk or ISO image (please select)**, then press the **select** button. Select the LiveG OS ISO file from the file picker. Once the file is chosen, press **start** and wait for copying to complete. Once complete, eject the storage device, from which it will be ready for use.

For more help and support with using Rufus, visit [rufus.ie](https://rufus.ie/).

## Using UNetbootin
UNetbootin is compatible with devices running Windows, macOS or Linux.

Download UNetbootin from [unetbootin.org](https://unetbootin.org/) and install it to a computer (this can be the computer you wish to install LiveG OS onto).

Open UNetbootin and select **diskimage**. Press **...** and select the LiveG OS file from the file picker. Select the storage device from the **drive** list. Press **OK** and wait for copying to complete. Once complete, eject the storage device, from which it will be ready for use.

For more help and support with using UNetbootin, visit [unetbootin.org](https://unetbootin.org/).