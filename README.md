****----------Device Tree--------****

	git clone https://github.com/drkphnx/device_xiaomi_sm8250-common.git -b 12  device/xiaomi/sm8250-common </br>
	git clone https://github.com/drkphnx/device_xiaomi_alioth.git -b 12  device/xiaomi/alioth

**------vendor tree--------------**

	git clone https://github.com/drkphnx/vendor_xiaomi_alioth.git -b 12 vendor/xiaomi/alioth </br>
	git clone https://github.com/drkphnx/vendor_xiaomi_sm8250-common.git -b 12 vendor/xiaomi/sm8250-common </br>

**-------IFFA-------------------** </br>

	git clone https://github.com/drkphnx/device_xiaomi_extras.git -b 12 device/xiaomi/extras </br>

**---------Kernel ----------------** </br>

	git clone https://github.com/Official-Ayrton990/android_kernel_xiaomi_sm8250.git -b twelve kernel/xiaomi/alioth </br>

**------------Xiaomi Harware required to build xiaomi Parts---------------** </br>

	rm -rf hardware/xiaomi </br>
	git clone https://github.com/ProjectRadiant/hardware_xiaomi.git -b twelve hardware/xiaomi </br>

**----------------HALS--------------------------------------** </br>

	git clone https://github.com/ArrowOS/android_hardware_qcom_display.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/display </br>
	git clone https://github.com/ArrowOS/android_hardware_qcom_media.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/media </br>
	git clone https://github.com/ArrowOS/android_hardware_qcom_audio.git -b arrow-12.0-caf-sm8250 hardware/qcom-caf/sm8250/audio </br>

**-----------------untill i adapt parts to S style completly--------------** </br>

	git clone https://github.com/drkphnx/packages_resources_devicesettings.git -b snow packages/resources/devicesettings </br>

