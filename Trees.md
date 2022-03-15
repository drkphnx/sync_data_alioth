**Device Tree**

	git clone git@github.com:drkphnx/device_xiaomi_sm8250-common.git -b 12.1 device/xiaomi/sm8250-common 
	git clone git@github.com:drkphnx/device_xiaomi_alioth.git -b 12  device/xiaomi/alioth

**vendor tree**
 	
	git clone git@github.com:drkphnx/vendor_xiaomi.git -b 12.1  vendor/xiaomi
	
**Kernels**

    --------------------InfiniR------------
    
	git clone git@github.com:raystef66/InfiniR_kernel_alioth.git -b 12.0 kernel/xiaomi/alioth 
	
    --------------------arrow---------------- 	
    
	git clone https://github.com/ArrowOS-Devices/android_kernel_xiaomi_alioth.git -b arrow-12.0 kernel/xiaomi/alioth  
	
    -----------------------Quantic-----------------
    
	git clone https://github.com/Official-Ayrton990/android_kernel_xiaomi_sm8250.git -b upstreamed-common kernel/xiaomi/alioth 
	
    -----------------------immensity fork by ppui-----------------	
    
    git clone git@github.com:PixelPlusUI-Devices/alioth_kernel_xiaomi_sm8250.git -b snowcone kernel/xiaomi/alioth
	
    -----------------------N0 kernel-----------------	
        
    git clone git@github.com:EmanuelCN/kernel_xiaomi_sm8250.git -b staging2 kernel/xiaomi/alioth
    
    -----------------------Next Kernel-------------------------------------------
    git clone git@github.com:NextWork123/kernel_xiaomi_sm8250.git -b S kernel/xiaomi/alioth
    
    
 **clang**
 
 	--------------Proton Clang-----------------------------------
    
    git clone --depth=1 https://github.com/kdrag0n/proton-clang.git prebuilts/clang/host/linux-x86/proton-clang
    
 	---------------AOSP clang 14-----------------------------
    
    git clone git@github.com:drkphnx/android_prebuilts_clang_host_linux-x86_clang-r437112.git -b master prebuilts/clang/host/linux-x86/clang-r437112 
    
    
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

**Lawnchair (optional)**
	
	rm -rf vendor/lawnchair
	git clone git@github.com:drkphnx/vendor_lawnchair.git -b 12  vendor/lawnchair
	

**ant-wireless**
	
	rm -rf external/ant-wireless/antradio-library
	git clone git@github.com:drkphnx/external_ant-wireless_antradio-library.git -b snowcone external/ant-wireless/antradio-library
	
**NFC (for some roms that doeesn't have kryo 785 support in source nfc package)**

	rm -rf vendor/nxp/opensource/commonsys/packages/apps/Nfc
	git clone git@github.com:drkphnx/vendor_nxp_opensource_commonsys_packages_apps_Nfc.git -b snowcone vendor/nxp/opensource/commonsys/packages/apps/Nfc
