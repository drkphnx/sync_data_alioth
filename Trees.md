**Device Tree**

	git clone git@github.com:drkphnx/device_xiaomi_sm8250-common.git -b 12 device/xiaomi/sm8250-common 
	git clone git@github.com:drkphnx/device_xiaomi_alioth.git -b 12  device/xiaomi/alioth

**vendor tree**
	
	git clone git@github.com:drkphnx/vendor_xiaomi_alioth.git -b 12  vendor/xiaomi/alioth
	git clone git@github.com:drkphnx/vendor_xiaomi_sm8250-common.git -b 12 vendor/xiaomi/sm8250-common
	git clone git@github.com:drkphnx/vendor_xiaomi_sm8250-common-extra.git -b 12 vendor/xiaomi/sm8250-common-extra

**Kernels**

    --------------------OD------------
    
	git clone https://github.com/GZR-Kernels/Optimus_Drunk_Alioth.git -b 11.0 kernel/xiaomi/alioth 
	
    --------------------arrow---------------- 	
    
	git clone https://github.com/ArrowOS-Devices/android_kernel_xiaomi_alioth.git -b arrow-12.0 kernel/xiaomi/alioth  
	
    -----------------------Quantic-----------------
    
	git clone https://github.com/Official-Ayrton990/android_kernel_xiaomi_sm8250.git -b upstreamed-common kernel/xiaomi/alioth 
	
    -----------------------immensity fork by ppui-----------------	
    
    git clone git@github.com:PixelPlusUI-Devices/alioth_kernel_xiaomi_sm8250.git -b snowcone kernel/xiaomi/alioth
	
    -----------------------N0 kernel-----------------	
        
    git clone git@github.com:EmanuelCN/kernel_xiaomi_sm8250.git -b S kernel/xiaomi/alioth
    
 **proton clang**
    
    git clone --depth=1 https://github.com/kdrag0n/proton-clang.git prebuilts/clang/host/linux-x86/proton-clang
    
**Xiaomi Harware required to build xiaomi Parts**

	rm -rf hardware/xiaomi
	git clone git@github.com:LineageOS/android_hardware_xiaomi.git -b lineage-19.0 hardware/xiaomi

**HALS**

	rm -rf hardware/qcom-caf/sm8250/display 
	
	git clone git@github.com:PixelPlusUI-Devices/alioth_hardware_qcom-caf_sm8250_display.git -b snowcone hardware/qcom-caf/sm8250/display 
	
	rm -rf hardware/qcom-caf/sm8250/media 
	
	git clone git@github.com:PixelPlusUI-Devices/alioth_hardware_qcom-caf_sm8250_media.git -b snowcone hardware/qcom-caf/sm8250/media 
	
	rm -rf hardware/qcom-caf/sm8250/audio 
	
	git clone git@github.com:PixelPlusUI-Devices/alioth_hardware_qcom-caf_sm8250_audio.git -b snowcone hardware/qcom-caf/sm8250/audio 

**Lawnchair**

	git clone git@github.com:drkphnx/vendor_lawnchair.git -b 12  vendor/lawnchair
	
**Packages Device settings**
	
	rm -rf packages/resources/devicesettings 
	git clone https://github.com/drkphnx/packages_resources_devicesettings.git -b snow packages/resources/devicesettings 
	
