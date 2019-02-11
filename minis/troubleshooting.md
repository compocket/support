# Troubleshooting

### There is no scope view.

If you can't see the scope screen like the below image, your graphics card's driver may not be up to date. You need to download and install the latest version of the graphics card driver to fix the problem. 

![](../.gitbook/assets/image%20%283%29.png)

### I connected the device, but I cannot communicate with it.

#### For Windows:

* Open the **Device Manager.**
* Under the **View** Menu, click **Show hidden devices.**
* Expand Universal Serial Bus devices.
* Normally, you should see **"Minis"** and **"Minis v1.0"** under the Universal Serial Bus devices.
* If you cannot find them there, you need to install the drivers manually.
* Go to the installation folder of the Minis. If you did not change the default location, it is **"C:\Program Files \(x86\)\Compocket\Minis"**. 
* Open **Drivers** folder.
* If you do not have **Minis.cat** and **MinisBootloader.cat** files, **Run dpscat.exe** first. This creates the necessary .cat files.
* **Run dpinst32.exe or dpinst64.exe** according to your OS. This will install the drivers.

#### **For Linux:**

* You need to make sure that you have the permission to access the USB as the current user.

#### For Mac OS:

* You need to make sure that you have the **Minis.kext** file to communicate with the device.
* The .kext file should be located at **/System/Library/Extensions.** 

