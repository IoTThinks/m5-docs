
## Flash UIFlow 

* __Downloading the driver__

><img src="/image/base/Windows_logo.webp" width="50" height="50"> Go to [m5stack.com](http://m5stack.com/) and download Windows driver [CP210X Drivers](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_Windows.zip)

><img src="/image/base/MacOS_logo.webp" width="50" height="50"> Go to [m5stack.com](http://m5stack.com/) and download MacOS driver [CP210X Drivers](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_MacOS.zip)

><img src="/image/base/Linux_logo.webp" width="50" height="50">  Go to [m5stack.com](http://m5stack.com/) and download Linux driver [CP210X Drivers](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_Linux.zip)

* __Installing the driver__

> Extract the zip file and run the install package in the extracted folder

><img src="/image/base/CP210X_install.gif " width="50%">

>?For Mac OS, make sure System preferences - > Security & Privacy - > General before installing, and allow the apps to be installed from the App Store and ident
ified developers

><img src="/image/base/System_preferences.webp" width="50%">


* __Download M5Burner__

><img src="/image/base/Windows_logo.webp" width="50" height="50"> Go to [flow.m5stack.com](http://flow.m5stack.com/) and download the latest firmware and [M5Burner(Windows)](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/M5Burner.zip)

><img src="/image/base/MacOS_logo.webp" width="50" height="50">  Go to [flow.m5stack.com](http://flow.m5stack.com/) and download the latest firmware and [M5Burner(MacOS)](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/M5Burner_MacOS.zip)

><img src="/image/base/Linux_logo.webp" width="50" height="50">  Go to [flow.m5stack.com](http://flow.m5stack.com/) and download the latest firmware and [M5Burner(Linux)](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/M5Burner_Linux.zip)

?> Mac OS users need to put M5Burner in the Application folder

><img src="/image/base/application.webp" width="50%" height="50%"> 


* __Burning process__

> Extract the burner package and double click on the M5 Burner icon. Connect your M5Stack device and select its COM port from the list (Check Windows device manager if you are unsure of your COM port).Select the recommended baud rate 921600 and then select the firmware you wish to flash. Now press the burn button, your firmware will have flashed successfully once you see the message "leaving staying in bootloader". Reset your device to see the new firmware.

><img src="/image/base/Burner_user.gif " width="50%">


## Setup WIFI

>For version 1.4.5 and above, WiFi information can be written directly through M5Burner

><img src="/image/base/Burner_145.webp " width="50%">

* __M5GO__

>__*1.4.5 version and above can be configured directly through M5Bunner__

>1.Single press the red start button on the side of the M5GO, When the logo appears press the button-A quickly to enter the WiFi setup menu.Select change wi-fi connect and then connect to the M5GO's access point with your computer or mobile device (The access point will look something like "M5Stack-xxxx")

>2.Once you have connected to your M5GO's access point you can enter the WIFI setup page by scanning the QR code or by entering __192.168.4.1__ into your browser. Then you have arrived at the page choose your home wifi network from the list, enter your password and click configure

><img src="/image/base/1.webp" width="15%"> &nbsp;&nbsp;<img src="/image/base/2.webp" width="60%">


* __M5StickC__

>__*1.4.5 version and above can be configured directly through M5Bunner__

>1.Single press the power button,then connect to the StickC's access point with your computer or mobile device (The access point will look something like "M5Stack-xxxx")

>2.Once you have connected to your StickC's access point you can enter the WIFI setup page by entering __192.168.4.1__ into your browser. Then you have arrived at the page choose your home wifi network from the list, enter your password and click configure

><img src="/image/base/3.webp" width="10%"> &nbsp;&nbsp; <img src="/image/base/4.webp" width="12%"> 

* __Atom Matrix__ __&__ __Atom Lite__

>__*1.4.5 version and above can be configured directly through M5Bunner__

>1.After the device is powered on, press and hold the middle button, and release it when the LED turns to yellow breathing light, and the yellow light will always on,then connect to the Atom's access point with your computer or mobile device (The access point will look something like "M5Stack-xxxx")

>2.Once you have connected to your Atom's access point you can enter the WIFI setup page by entering __192.168.4.1__ into your browser. Then you have arrived at the page choose your home wifi network from the list, enter your password and click configure

<img src="/image/base/configure_wifi.webp" width="60%" height="60%"><img src="/image/base/4.webp" width="12%"> 

## API Key

#### Entering Code Upload Mode

* __M5GO__

>After turning on the M5stack, select the Upload mode by pressing the left face button. Assuming you have already setup wifi on your device, the M5stack will connect to your network and once it is connected will display a QR code and a unique API Key. We can now start to program the device by scanning the M5stack with a mobile device or entering the url displayed at the top of the screen into your browser [flow.m5stack.com](http://flow.m5stack.com). In addition, the uiflow connection server can be changed through the setting page. The website of Singapore server is [flow01.m5stack.com](http://flow01.m5stack.com)

><img src="/image/base/APIkey_user.webp"/>

* __M5StickC__

>After power on, wait for the earth indicator to turn red to green (this indicates that m5stickc has successfully connected to the network), and directly visit [flow.m5stack. com](http://flow.m5stack.com/) in the computer browser to enter the uiflow programming page

* __Atom Matrix__ __&__ __Atom Lite__

>After power on, wait for the LED indicator to turn red to green (this indicates that atom has successfully connected to the network), and directly visit [flow.m5stack. com](http://flow.m5stack.com/) in the computer browser to enter the UIFlow programming page

>The apikey of atom can be viewed through the WIFI setup page(Refer to the previous step - Setup WIFI) or through the serial terminal such as [Putty](https://www.putty.org/)(Windows) or [Serial](https://apps.apple.com/cn/app/serial/id877615577?mt=12)(Mac).

><img src="assets/img/product_pics/core/minicore/atom/apikey.webp" width="50%"><img src="assets/img/product_pics/core/minicore/atom/serialtool.webp" width="50%">

#### Connecting your device with API Key

>Once you have opened the UIflow website you can to connect to the web platform by clicking the gear icon in the top right corner, enter your API key and select your device and preferred language. Once you have entered the API Key click OK to confirm****

><img src="/image/base/APIkey_userpair1.webp" width="50%"><img src="/image/base/APIkey_userpair2.webp" width="50%">

## UIFlow-IDE

>If you want to use UIFlow offline，click **UIFlow-Desktop-IDE** for your operating system below to download.

<div class="link">
 <h4><span>Download UIFlow Desktop IDE:</span></h4>
    <p>
    <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/UIFlow-Desktop-IDE.zip" target="_blank" rel="noopener noreferrer"><img src="https://cdn.shopify.com/s/files/1/0056/7689/2250/files/windows_89cc6ea0-2a3c-4327-97e5-8f51f448c38b_icon.webp?v=1557026574" alt="">Windows</a>
    <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/UIFlow-Desktop-IDE_MacOS.zip" target="_blank" rel="noopener noreferrer"><img src="https://cdn.shopify.com/s/files/1/0056/7689/2250/files/mac_large.webp?v=1557026570" alt="">MacOS</a>
    <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/software/UIFlow-Desktop-IDE_Linux.zip" target="_blank" rel="noopener noreferrer"><img src="https://cdn.shopify.com/s/files/1/0056/7689/2250/files/linux_icon.webp?v=1557026584" alt="">Linux</a>
    </p>
</div>

#### configuration

>Unzip the downloaded UIFlow Desktop IDE archive and double-click to execute the application.

<img src="assets/img/related_documents/UIFlow_Desktop_IDE/Desktop_IDE_01.webp">

?>After the software is started, it will automatically detect whether your computer has a USB driver (CP210X) installed, click Install, and follow the prompts to install it.

<img src="assets/img/related_documents/UIFlow_Desktop_IDE/Desktop_IDE_02.webp">

>After the driver installation is complete, it will automatically enter the UIFlow Desktop IDE and automatically pop up the configuration box. At this time, connect the M5 device to the computer through the Tpye-C data cable.

<img src="assets/img/related_documents/UIFlow_Desktop_IDE/Desktop_IDE_03.webp">

* __For M5GO__

!>Using the UIFlow Desktop IDE requires the M5 device to carry the UIFlow firmware and enter the **USB mode**.

>Click the power button on the left side of the device to restart. After entering the menu, select Setup quickly to enter the configuration page and select**USB mode**.

<img src="assets/img/related_documents/UIFlow_Desktop_IDE/Desktop_IDE_04.webp">

>Select the corresponding port, and connect to the programming device, click OK.

<img src="assets/img/related_documents/UIFlow_Desktop_IDE/Desktop_IDE_05.webp">

* __For M5StickC__

!>If you are using M5StickC, please follow the instructions below

>Press and hold the power key on the left side of the fuselage for 2 seconds to start the machine. After the uiflow logo appears, quickly click the home key (center M5 key) to enter the configuration page. Press the button on the right side of the fuselage to switch the option to setting, and press home to confirm. Press the right key to switch to USB mode, press home key to confirm, enter USB programming mode, select the corresponding COM port and device in IDE, and click Connect.

<img src="assets/img/related_documents/UIFlow_Desktop_IDE/Desktop_IDE_00.webp">

* __For Atom__

!>If you are using Atom, please follow the instructions below

>When the device is powered on or restarted, press and hold the middle button until it is released when the blue-light breathing is displayed, and then enter USB mode.（For more information, refer to https://docs.m5stack.com/#/zh_CN/quick_start/atom/atom_quick_start）


><img src="/image/base/usbmode.webp" width="50%" height="50%">

## Toturial

* [M5StickC getting started with the Internet of things](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/UIFlow-StickC-Book-English.pdf)

* [M5GO getting started with programming](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/M5GO_Guide_English.pdf)

<script>

   anchor_search();
   scrollFunc();

</script>
