# TWRP Device Tree for Samsung Galaxy S24 Ultra

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/Archer3770/twrp_device_samsung_e3q device/samsung/e3q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_e3q-eng
mka recoveryimage
```
