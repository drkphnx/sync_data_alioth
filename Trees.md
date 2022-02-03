****----------Device Tree--------****

	git clone https://github.com/drkphnx/device_xiaomi_sm8250-common.git -b 12  device/xiaomi/sm8250-common 
	git clone https://github.com/drkphnx/device_xiaomi_alioth.git -b 12  device/xiaomi/alioth
	
	git clone git@github.com:drkphnx/device_xiaomi_sm8250-common.git -b 12 device/xiaomi/sm8250-common 
	git clone git@github.com:drkphnx/device_xiaomi_alioth.git -b 12  device/xiaomi/alioth

**------vendor tree--------------**
	
	git clone git@github.com:drkphnx/vendor_xiaomi.git -b 12  vendor/xiaomi

**---------Kernels ----------------** </br>

    --------------------OD------------
	git clone https://github.com/GZR-Kernels/Optimus_Drunk_Alioth.git -b 11.0 kernel/xiaomi/alioth 
	
    --------------------arrow---------------- 	
	git clone https://github.com/ArrowOS-Devices/android_kernel_xiaomi_alioth.git -b arrow-12.0 kernel/xiaomi/alioth  
	
    -----------------------Quantic-----------------
	git clone https://github.com/Official-Ayrton990/android_kernel_xiaomi_sm8250.git -b twelve kernel/xiaomi/alioth 
	
    -----------------------Next kernel-----------------	
    git clone https://github.com/NextWork123/kernel_xiaomi_sm8250.git -b android11-stable kernel/xiaomi/alioth
	
**------------Xiaomi Harware required to build xiaomi Parts---------------** </br>

	rm -rf hardware/xiaomi
	git clone https://github.com/ProjectRadiant/hardware_xiaomi.git -b twelve hardware/xiaomi

**----------------HALS--------------------------------------** </br>

	rm -rf hardware/qcom-caf/sm8250/display 
	
	git clone https://github.com/ArrowOS/android_hardware_qcom_display.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/display 
	
	rm -rf hardware/qcom-caf/sm8250/media 
	
	git clone https://github.com/ArrowOS/android_hardware_qcom_media.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/media 
	
	rm -rf hardware/qcom-caf/sm8250/audio 
	
	git clone https://github.com/ArrowOS/android_hardware_qcom_audio.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/audio 

**----------------Lawnchair---------------------------------** </br>

	git clone git@github.com:drkphnx/vendor_lawnchair.git -b 12  vendor/lawnchair
	
**..................Packages Device settings.................** <br>
	
	rm -rf packages/resources/devicesettings 
	git clone https://github.com/drkphnx/packages_resources_devicesettings.git -b snow packages/resources/devicesettings 
	
