# Latitude-E6430-MacOS-Big-Sur-OpenCore-EFI
Smart SMC ACPI Build 
added (dirt=0 keepsyms=1 debug=0x100 -no_compat_check -wegnoegpu -xcpm) to boot-args to fix lock after wake and change acpi to smart SMC ACPI 
Deleted SSDT-PLUG.aml not Need For This chipset Read on dortania Guide 
Added Apple ALC audio Because the voodoo kext is not loud 
added intel wifi support https://github.com/OpenIntelWireless/itlwm Kext 
