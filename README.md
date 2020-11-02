# Add this after create machine
`` VBoxManage.exe modifyvm “Vm name” –-cpuidset 00000001 000106e5 00100800 0098e3fd bfebfbff
VBoxManage setextradata "Vm name" VBoxInternal/Devices/efi/0/Config/DmiSystemProduct “MacBookPro15,1”
VBoxManage setextradata "Vm name" "VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "Mac-551B86E5744E2388"
VBoxManage setextradata "Vm name" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedpleasedontsteal(c)AppleComputerInc"
VBoxManage setextradata "Vm name" "VBoxInternal/Devices/smc/0/Config/GetKeyFromRealSMC" 1 ``
