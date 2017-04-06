#### Enable Nexus6 NFC-SWP
These will be replaced
```
/system/etc/libnfc-brcm-20795a10.conf
/system/etc/libnfc-brcm.conf
```
These will be created
```
/system/etc/permissions/org.simalliance.openmobileapi.xml
/system/framework/org.simalliance.openmobileapi.jar
/system/priv-app/SmartcardService/SmartcardService.apk
```

Should be working on Android 6.0+

#### Known Issues

1. If you enable Wechat NFC, System NFC Service maybe crash

#### Support

Thanks Joseph Liu

<https://paoyuan.org/2015/11/14/nexus-6-android-marshmallow-nfc-swp-sim-support>