**Device Tree**
	
	git clone git@github.com:drkphnx/android_device_xiaomi_sm8250-common.git -b twelve device/xiaomi/sm8250-common 
	git clone git@github.com:drkphnx/android_device_xiaomi_alioth.git -b twelve device/xiaomi/alioth

**vendor tree**
	
	git clone git@github.com:drkphnx/android_vendor_xiaomi_sm8250-common.git -b twelve vendor/xiaomi/sm8250-common
	git clone git@github.com:drkphnx/android_vendor_xiaomi_alioth.git -b twelve vendor/xiaomi/alioth

**Kernels**

    --------------------OD------------
    
	git clone https://github.com/GZR-Kernels/Optimus_Drunk_Alioth.git -b 11.0 kernel/xiaomi/alioth 
	
    --------------------arrow------------------
    
	git clone https://github.com/ArrowOS-Devices/android_kernel_xiaomi_alioth.git -b arrow-12.0 kernel/xiaomi/alioth  
	
    -----------------------Quantic-----------------
    
	git clone https://github.com/Official-Ayrton990/android_kernel_xiaomi_sm8250.git -b upstreamed-common kernel/xiaomi/alioth 
	
    -----------------------N0 kernel-----------------	
        
    git clone git@github.com:EmanuelCN/kernel_xiaomi_sm8250.git -b S kernel/xiaomi/alioth
    
 **proton clang**
    
    git clone --depth=1 https://github.com/kdrag0n/proton-clang.git prebuilts/clang/host/linux-x86/proton-clang
    
**Xiaomi Harware required to build xiaomi Parts**

	rm -rf hardware/xiaomi
	git clone https://github.com/ProjectRadiant/hardware_xiaomi.git -b twelve hardware/xiaomi

**HALS**

	rm -rf hardware/qcom-caf/sm8250/display 
	
	git clone git@github.com:AliothDevelopment/android_hardware_qcom-caf_sm8250_display.git -b twelve hardware/qcom-caf/sm8250/display 
	
	rm -rf hardware/qcom-caf/sm8250/media 
	
	git clone git@github.com:AliothDevelopment/android_hardware_qcom-caf_sm8250_media.git -b twelve  hardware/qcom-caf/sm8250/media 
	
	rm -rf hardware/qcom-caf/sm8250/audio 
	
	git clone git@github.com:AliothDevelopment/android_hardware_qcom-caf_sm8250_audio.git -b twelve hardware/qcom-caf/sm8250/audio 

**Lawnchair**

	git clone git@github.com:drkphnx/vendor_lawnchair.git -b 12  vendor/lawnchair
	
**Packages Device settings**
	
	rm -rf packages/resources/devicesettings 
	git clone https://github.com/drkphnx/packages_resources_devicesettings.git -b snow packages/resources/devicesettings 
	
**Google camera**

    git clone https://github.com/drkphnx/packages_apps_Gcam.git packages/apps/Gcam

**NFC (for some roms that doeesn't have kryo 785 support in source caf nfc package)**
	rm -rf vendor/nxp/opensource/commonsys/packages/apps/Nfc
	git clone git@github.com:drkphnx/vendor_nxp_opensource_commonsys_packages_apps_Nfc.git -b snowcone vendor/nxp/opensource/commonsys/packages/apps/Nfc
