#### Test 794266509fa1f7f_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
08-05 02:13:17.105   765  1583 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 02:13:17.125   765  1583 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-05 02:13:17.125   765  1583 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-05 02:13:17.125   765  1583 D BatteryService: stay LED for fully charged
08-05 02:13:17.135   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-05 02:13:17.145   765   765 I MotionRecognitionService: Plugged
08-05 02:13:17.145   765   765 D MotionRecognitionService:   cableConnection= 1
--------- beginning of main
08-05 02:13:17.155  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 02:13:17.155  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-05 02:13:17.155  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 02:13:17.165   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-05 02:13:17.165   765   765 D MotionRecognitionService: skip setTransmitPower. 
08-05 02:13:17.195  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:13:17.205  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:13:17.205  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:13:17.205  2299  2299 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 02:13:17.215  2299  2722 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 02:13:18.055  2304  2304 E audit   : type=1400 msg=audit(1470355998.055:284): avc:  denied  { execmod } for  pid=7046 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 02:13:18.055  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:18.055  2304  2304 E audit   : type=1300 msg=audit(1470355998.055:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b400f000 a1=51000 a2=5 a3=4 items=0 ppid=3563 ppcomm=adbd pid=7046 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 02:13:18.055  2304  2304 E audit   : type=1327 msg=audit(1470355998.055:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-05 02:13:18.055  2304  2304 E audit   : type=1320 msg=audit(1470355998.055:284): 
08-05 02:13:18.115  2304  2304 E audit   : type=1400 msg=audit(1470355998.115:285): avc:  denied  { execmod } for  pid=7046 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 02:13:18.115  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:18.115  2304  2304 E audit   : type=1300 msg=audit(1470355998.115:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcf000 a1=51000 a2=5 a3=4 items=0 ppid=3563 ppcomm=adbd pid=7046 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 02:13:18.115  2304  2304 E audit   : type=1327 msg=audit(1470355998.115:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-05 02:13:18.115  2304  2304 E audit   : type=1320 msg=audit(1470355998.115:285): 
08-05 02:13:18.155  2304  2304 E audit   : type=1400 msg=audit(1470355998.155:286): avc:  denied  { execmod } for  pid=7046 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 02:13:18.155  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:18.155  7046  7046 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 02:13:18.155  2304  2304 E audit   : type=1300 msg=audit(1470355998.155:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcf000 a1=51000 a2=5 a3=4 items=0 ppid=3563 ppcomm=adbd pid=7046 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 02:13:18.155  2304  2304 E audit   : type=1327 msg=audit(1470355998.155:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-05 02:13:18.155  2304  2304 E audit   : type=1320 msg=audit(1470355998.155:286): 
08-05 02:13:18.165  7046  7046 D AndroidRuntime: CheckJNI is OFF
08-05 02:13:18.165  7046  7046 D AndroidRuntime: readGMSProperty: start
08-05 02:13:18.165  7046  7046 D AndroidRuntime: readGMSProperty: already setted!!
08-05 02:13:18.165  7046  7046 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 02:13:18.165  7046  7046 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 02:13:18.165  7046  7046 D AndroidRuntime: readGMSProperty: end
08-05 02:13:18.165  7046  7046 D AndroidRuntime: addProductProperty: start
08-05 02:13:18.175  7046  7046 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-05 02:13:18.175  7046  7046 W art     : af165000-b208b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-05 02:13:18.175  7046  7046 W art     : b208b000-b42fa000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-05 02:13:18.175  7046  7046 W art     : b42fa000-b42fb000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-05 02:13:18.175  7046  7046 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-05 02:13:18.175  7046  7046 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-05 02:13:18.175  7046  7046 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-05 02:13:18.175  7046  7046 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-05 02:13:18.175  7046  7046 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-05 02:13:18.175  7046  7046 W art     : b489d000-b48a0000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-05 02:13:18.175  7046  7046 W art     : b48a0000-b48a1000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-05 02:13:18.175  7046  7046 W art     : b48a1000-b48a2000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-05 02:13:18.175  7046  7046 W art     : b48a2000-b48a3000 r--p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b48a3000-b48c3000 r--s 00000000 00:0b 7179       /dev/__properties__
08-05 02:13:18.175  7046  7046 W art     : b48c3000-b52d4000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-05 02:13:18.175  7046  7046 W art     : b52d4000-b52d5000 ---p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b52d5000-b531e000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-05 02:13:18.175  7046  7046 W art     : b531e000-b531f000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-05 02:13:18.175  7046  7046 W art     : b531f000-b5327000 rw-p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b5327000-b5328000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.175  7046  7046 W art     : b5328000-b535d000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-05 02:13:18.175  7046  7046 W art     : b535d000-b535e000 ---p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b535e000-b535f000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-05 02:13:18.175  7046  7046 W art     : b535f000-b5360000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-05 02:13:18.175  7046  7046 W art     : b5360000-b53b8000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-05 02:13:18.175  7046  7046 W art     : b53b8000-b53b9000 ---p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b53b9000-b53ba000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-05 02:13:18.175  7046  7046 W art     : b53ba000-b53bb000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-05 02:13:18.175  7046  7046 W art     : b53bc000-b53c2000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 02:13:18.175  7046  7046 W art     : b53c2000-b53c3000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 02:13:18.175  7046  7046 W art     : b53c3000-b53c4000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 02:13:18.175  7046  7046 W art     : b53c4000-b53c6000 rw-p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b53c7000-b53d1000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 02:13:18.175  7046  7046 W art     : b53d1000-b53d4000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 02:13:18.175  7046  7046 W art     : b53d4000-b53d5000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 02:13:18.175  7046  7046 W art     : b53d6000-b53ed000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 02:13:18.175  7046  7046 W art     : b53ed000-b53ee000 ---p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b53ee000-b53ef000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 02:13:18.175  7046  7046 W art     : b53ef000-b53f0000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 02:13:18.175  7046  7046 W art     : b53f1000-b53fb000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-05 02:13:18.175  7046  7046 W art     : b53fb000-b53fc000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-05 02:13:18.175  7046  7046 W art     : b53fc000-b53fd000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-05 02:13:18.175  7046  7046 W art     : b53fd000-b5401000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 02:13:18.175  7046  7046 W art     : b5401000-b5402000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 02:13:18.175  7046  7046 W art     : b5402000-b5403000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 02:13:18.175  7046  7046 W art     : b5403000-b5419000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-05 02:13:18.175  7046  7046 W art     : b5419000-b541a000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-05 02:13:18.175  7046  7046 W art     : b541a000-b541b000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-05 02:13:18.175  7046  7046 W art     : b541b000-b5428000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-05 02:13:18.175  7046  7046 W art     : b5428000-b5429000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-05 02:13:18.175  7046  7046 W art     : b5429000-b542a000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-05 02:13:18.175  7046  7046 W art     : b542a000-b548a000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-05 02:13:18.175  7046  7046 W art     : b548a000-b548d000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-05 02:13:18.175  7046  7046 W art     : b548d000-b5491000 rw-p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b5491000-b54f2000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-05 02:13:18.175  7046  7046 W art     : b54f2000-b54f3000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-05 02:13:18.175  7046  7046 W art     : b54f3000-b5542000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-05 02:13:18.175  7046  7046 W art     : b5542000-b5544000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-05 02:13:18.175  7046  7046 W art     : b5544000-b5545000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-05 02:13:18.175  7046  7046 W art     : b5545000-b5546000 rw-p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b5546000-b554d000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 02:13:18.175  7046  7046 W art     : b554d000-b554e000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 02:13:18.175  7046  7046 W art     : b554e000-b554f000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 02:13:18.175  7046  7046 W art     : b5550000-b5553000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 02:13:18.175  7046  7046 W art     : b5553000-b5554000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 02:13:18.175  7046  7046 W art     : b5554000-b5555000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 02:13:18.175  7046  7046 W art     : b5556000-b555a000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-05 02:13:18.175  7046  7046 W art     : b555a000-b555b000 ---p 00000000 00:00 0 
08-05 02:13:18.175  7046  7046 W art     : b555b000-b555c000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-05 02:13:18.175  7046  7046 W art     : b555c000-b555d000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-05 02:13:18.175  7046  7046 W art     : b555e000-b557b000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 02:13:18.175  7046  7046 W art     : b557b000-b557c000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 02:13:18.175  7046  7046 W art     : b557c000-b557d000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 02:13:18.175  7046  7046 W art     : b557e000-b5583000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 02:13:18.175  7046  7046 W art     : b5583000-b5584000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 02:13:18.175  7046  7046 W art     : b5584000-b5585000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 02:13:18.175  7046  7046 W art     : b5586000-b55b7000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 02:13:18.175  7046  7046 W art     : b55b7000-b55ba000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 02:13:18.175  7046  7046 W art     : b55ba000-b55bb000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 02:13:18.175  7046  7046 W art     : b55bc000-b55f7000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-05 02:13:18.175  7046  7046 W art     : b55f7000-b55f8000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-05 02:13:18.175  7046  7046 W art     : b55f8000-b55f9000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-05 02:13:18.185  7046  7046 W art     : b55fa000-b5601000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-05 02:13:18.185  7046  7046 W art     : b5601000-b5602000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5602000-b5603000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-05 02:13:18.185  7046  7046 W art     : b5603000-b5604000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-05 02:13:18.185  7046  7046 W art     : b5604000-b5605000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5605000-b561c000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-05 02:13:18.185  7046  7046 W art     : b561c000-b561d000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b561d000-b5620000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-05 02:13:18.185  7046  7046 W art     : b5620000-b5621000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-05 02:13:18.185  7046  7046 W art     : b5621000-b5640000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-05 02:13:18.185  7046  7046 W art     : b5640000-b5641000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-05 02:13:18.185  7046  7046 W art     : b5641000-b5642000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-05 02:13:18.185  7046  7046 W art     : b5642000-b5680000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-05 02:13:18.185  7046  7046 W art     : b5680000-b5681000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5681000-b5683000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-05 02:13:18.185  7046  7046 W art     : b5683000-b5684000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-05 02:13:18.185  7046  7046 W art     : b5685000-b568c000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 02:13:18.185  7046  7046 W art     : b568c000-b568d000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 02:13:18.185  7046  7046 W art     : b568d000-b568e000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 02:13:18.185  7046  7046 W art     : b568f000-b5692000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 02:13:18.185  7046  7046 W art     : b5692000-b5693000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 02:13:18.185  7046  7046 W art     : b5693000-b5694000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 02:13:18.185  7046  7046 W art     : b5694000-b569a000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 02:13:18.185  7046  7046 W art     : b569a000-b569b000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b569b000-b569c000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 02:13:18.185  7046  7046 W art     : b569c000-b569d000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 02:13:18.185  7046  7046 W art     : b569d000-b56a6000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-05 02:13:18.185  7046  7046 W art     : b56a6000-b56a7000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-05 02:13:18.185  7046  7046 W art     : b56a7000-b56a8000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-05 02:13:18.185  7046  7046 W art     : b56a8000-b5739000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 02:13:18.185  7046  7046 W art     : b5739000-b573a000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b573a000-b5745000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 02:13:18.185  7046  7046 W art     : b5745000-b5746000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 02:13:18.185  7046  7046 W art     : b5747000-b5759000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-05 02:13:18.185  7046  7046 W art     : b5759000-b575a000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-05 02:13:18.185  7046  7046 W art     : b575a000-b575b000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-05 02:13:18.185  7046  7046 W art     : b575c000-b5761000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-05 02:13:18.185  7046  7046 W art     : b5761000-b5762000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-05 02:13:18.185  7046  7046 W art     : b5762000-b5763000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-05 02:13:18.185  7046  7046 W art     : b5764000-b57d1000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-05 02:13:18.185  7046  7046 W art     : b57d1000-b57d2000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b57d2000-b57d4000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-05 02:13:18.185  7046  7046 W art     : b57d4000-b57d5000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-05 02:13:18.185  7046  7046 W art     : b57d5000-b57d6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b57d6000-b57dd000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 02:13:18.185  7046  7046 W art     : b57dd000-b57de000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 02:13:18.185  7046  7046 W art     : b57de000-b57df000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 02:13:18.185  7046  7046 W art     : b57e0000-b5860000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 02:13:18.185  7046  7046 W art     : b5860000-b5861000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5861000-b5862000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 02:13:18.185  7046  7046 W art     : b5862000-b5863000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 02:13:18.185  7046  7046 W art     : b5863000-b587a000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b587a000-b58b1000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-05 02:13:18.185  7046  7046 W art     : ib/libqc-opt.so
08-05 02:13:18.185  7046  7046 W art     : b58b1000-b58b2000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 02:13:18.185  7046  7046 W art     : b58b2000-b58b3000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 02:13:18.185  7046  7046 W art     : b58b3000-b58cf000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 02:13:18.185  7046  7046 W art     : b58cf000-b58d0000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 02:13:18.185  7046  7046 W art     : b58d0000-b58d1000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 02:13:18.185  7046  7046 W art     : b58d2000-b5933000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-05 02:13:18.185  7046  7046 W art     : b5933000-b5935000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-05 02:13:18.185  7046  7046 W art     : b5935000-b5936000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-05 02:13:18.185  7046  7046 W art     : b5937000-b595e000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-05 02:13:18.185  7046  7046 W art     : b595e000-b595f000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b595f000-b5960000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-05 02:13:18.185  7046  7046 W art     : b5960000-b5961000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-05 02:13:18.185  7046  7046 W art     : b5962000-b596a000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 02:13:18.185  7046  7046 W art     : b596a000-b596c000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 02:13:18.185  7046  7046 W art     : b596c000-b596d000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 02:13:18.185  7046  7046 W art     : b596e000-b5971000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-05 02:13:18.185  7046  7046 W art     : b5971000-b5972000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-05 02:13:18.185  7046  7046 W art     : b5972000-b5973000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-05 02:13:18.185  7046  7046 W art     : b5973000-b5977000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-05 02:13:18.185  7046  7046 W art     : b5977000-b5978000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5978000-b5979000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-05 02:13:18.185  7046  7046 W art     : b5979000-b597a000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-05 02:13:18.185  7046  7046 W art     : b597a000-b598a000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-05 02:13:18.185  7046  7046 W art     : b598a000-b598b000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-05 02:13:18.185  7046  7046 W art     : b598b000-b598c000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-05 02:13:18.185  7046  7046 W art     : b598c000-b59d2000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b59d2000-b59db000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-05 02:13:18.185  7046  7046 W art     : b59db000-b59dc000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-05 02:13:18.185  7046  7046 W art     : b59dc000-b59dd000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-05 02:13:18.185  7046  7046 W art     : b59de000-b59e3000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-05 02:13:18.185  7046  7046 W art     : b59e3000-b59e4000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-05 02:13:18.185  7046  7046 W art     : b59e4000-b59e5000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-05 02:13:18.185  7046  7046 W art     : b59e5000-b59e8000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 02:13:18.185  7046  7046 W art     : b59e8000-b59e9000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b59e9000-b59ea000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 02:13:18.185  7046  7046 W art     : b59ea000-b59eb000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 02:13:18.185  7046  7046 W art     : b59ec000-b5a04000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 02:13:18.185  7046  7046 W art     : b5a04000-b5a05000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5a05000-b5a06000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 02:13:18.185  7046  7046 W art     : b5a06000-b5a07000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 02:13:18.185  7046  7046 W art     : b5a07000-b5a08000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:18.185  7046  7046 W art     : b5a08000-b5ba2000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-05 02:13:18.185  7046  7046 W art     : b5ba2000-b5ba3000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5ba3000-b5bb0000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-05 02:13:18.185  7046  7046 W art     : b5bb0000-b5bb1000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-05 02:13:18.185  7046  7046 W art     : b5bb1000-b5bb5000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-05 02:13:18.185  7046  7046 W art     : b5bb5000-b5bb6000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5bb6000-b5bb7000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-05 02:13:18.185  7046  7046 W art     : b5bb7000-b5bb8000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-05 02:13:18.185  7046  7046 W art     : b5bb8000-b5bcb000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-05 02:13:18.185  7046  7046 W art     : b5bcb000-b5bcc000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-05 02:13:18.185  7046  7046 W art     : b5bcc000-b5bcd000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-05 02:13:18.185  7046  7046 W art     : b5bce000-b5c19000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-05 02:13:18.185  7046  7046 W art     : b5c19000-b5c1a000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-05 02:13:18.185  7046  7046 W art     : b5c1a000-b5c1b000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-05 02:13:18.185  7046  7046 W art     : b5c1b000-b5c1d000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5c1e000-b5c2f000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 02:13:18.185  7046  7046 W art     : b5c2f000-b5c30000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5c30000-b5c31000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 02:13:18.185  7046  7046 W art     : b5c31000-b5c32000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 02:13:18.185  7046  7046 W art     : b5c32000-b5c33000 r--p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5c33000-b5c3d000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-05 02:13:18.185  7046  7046 W art     : b5c3d000-b5c3f000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-05 02:13:18.185  7046  7046 W art     : b5c3f000-b5c40000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-05 02:13:18.185  7046  7046 W art     : b5c40000-b5c59000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-05 02:13:18.185  7046  7046 W art     : b5c59000-b5c5a000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-05 02:13:18.185  7046  7046 W art     : b5c5a000-b5c5d000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-05 02:13:18.185  7046  7046 W art     : b5c5d000-b5c61000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5c61000-b5cd5000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-05 02:13:18.185  7046  7046 W art     : b5cd5000-b5cd6000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5cd6000-b5cd9000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-05 02:13:18.185  7046  7046 W art     : b5cd9000-b5cda000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-05 02:13:18.185  7046  7046 W art     : b5cda000-b5cdb000 r--p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5cdb000-b5cde000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-05 02:13:18.185  7046  7046 W art     : b5cde000-b5cdf000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-05 02:13:18.185  7046  7046 W art     : b5cdf000-b5ce0000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-05 02:13:18.185  7046  7046 W art     : b5ce0000-b5ce1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5ce1000-b5ce6000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 02:13:18.185  7046  7046 W art     : b5ce6000-b5ce7000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 02:13:18.185  7046  7046 W art     : b5ce7000-b5ce8000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 02:13:18.185  7046  7046 W art     : b5ce8000-b5ce9000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5ce9000-b5cec000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 02:13:18.185  7046  7046 W art     : b5cec000-b5ced000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 02:13:18.185  7046  7046 W art     : b5ced000-b5cee000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 02:13:18.185  7046  7046 W art     : b5cee000-b5cef000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5cef000-b5cf3000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-05 02:13:18.185  7046  7046 W art     : b5cf3000-b5cf4000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-05 02:13:18.185  7046  7046 W art     : b5cf4000-b5cf5000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-05 02:13:18.185  7046  7046 W art     : b5cf5000-b5cf6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:18.185  7046  7046 W art     : b5cf6000-b5cfa000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 02:13:18.185  7046  7046 W art     : b5cfa000-b5cfb000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 02:13:18.185  7046  7046 W art     : b5cfb000-b5cfc000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 02:13:18.185  7046  7046 W art     : b5cfc000-b5cfd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5cfd000-b5d0b000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-05 02:13:18.185  7046  7046 W art     : b5d0b000-b5d0c000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b5d0c000-b5d0d000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-05 02:13:18.185  7046  7046 W art     : b5d0d000-b5d0e000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-05 02:13:18.185  7046  7046 W art     : b5d0e000-b5d18000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 02:13:18.185  7046  7046 W art     : b5d18000-b5d1b000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 02:13:18.185  7046  7046 W art     : b5d1b000-b5d1c000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 02:13:18.185  7046  7046 W art     : b5d1c000-b5d1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5d1d000-b5d27000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-05 02:13:18.185  7046  7046 W art     : b5d27000-b5d2a000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-05 02:13:18.185  7046  7046 W art     : b5d2a000-b5d2b000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-05 02:13:18.185  7046  7046 W art     : b5d2b000-b5d2f000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-05 02:13:18.185  7046  7046 W art     : b5d2f000-b5d30000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-05 02:13:18.185  7046  7046 W art     : b5d30000-b5d31000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-05 02:13:18.185  7046  7046 W art     : b5d31000-b5d32000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b5d32000-b5d3f000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-05 02:13:18.185  7046  7046 W art     : b5d3f000-b5d41000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-05 02:13:18.185  7046  7046 W art     : b5d41000-b5d42000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-05 02:13:18.185  7046  7046 W art     : b5d42000-b6154000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-05 02:13:18.185  7046  7046 W art     : b6154000-b6155000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6155000-b615e000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-05 02:13:18.185  7046  7046 W art     : b615e000-b6162000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-05 02:13:18.185  7046  7046 W art     : b6162000-b6163000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6163000-b616a000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-05 02:13:18.185  7046  7046 W art     : b616a000-b616b000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-05 02:13:18.185  7046  7046 W art     : b616b000-b616c000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-05 02:13:18.185  7046  7046 W art     : b616c000-b616d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b616d000-b6188000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-05 02:13:18.185  7046  7046 W art     : b6188000-b6189000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-05 02:13:18.185  7046  7046 W art     : b6189000-b618a000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-05 02:13:18.185  7046  7046 W art     : b618a000-b618b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b618b000-b61d7000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 02:13:18.185  7046  7046 W art     : b61d7000-b61d8000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b61d8000-b61d9000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 02:13:18.185  7046  7046 W art     : b61d9000-b61da000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 02:13:18.185  7046  7046 W art     : b61da000-b61db000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b61db000-b61df000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-05 02:13:18.185  7046  7046 W art     : b61df000-b61e0000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b61e0000-b61e1000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-05 02:13:18.185  7046  7046 W art     : b61e1000-b61e2000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-05 02:13:18.185  7046  7046 W art     : b61e2000-b621a000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-05 02:13:18.185  7046  7046 W art     : b621a000-b621b000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-05 02:13:18.185  7046  7046 W art     : b621b000-b621c000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-05 02:13:18.185  7046  7046 W art     : b621c000-b621d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b621d000-b62bb000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-05 02:13:18.185  7046  7046 W art     : b62bb000-b62bc000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b62bc000-b62da000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-05 02:13:18.185  7046  7046 W art     : b62da000-b62db000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-05 02:13:18.185  7046  7046 W art     : b62db000-b644e000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-05 02:13:18.185  7046  7046 W art     : b644e000-b6459000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-05 02:13:18.185  7046  7046 W art     : b6459000-b645a000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-05 02:13:18.185  7046  7046 W art     : b645a000-b6571000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-05 02:13:18.185  7046  7046 W art     : b6571000-b657c000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-05 02:13:18.185  7046  7046 W art     : b657c000-b657d000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-05 02:13:18.185  7046  7046 W art     : b657d000-b6581000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6581000-b65a5000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-05 02:13:18.185  7046  7046 W art     : b65a5000-b65a7000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-05 02:13:18.185  7046  7046 W art     : b65a7000-b65a8000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-05 02:13:18.185  7046  7046 W art     : b65a8000-b664e000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-05 02:13:18.185  7046  7046 W art     : b664e000-b665b000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-05 02:13:18.185  7046  7046 W art     : b665b000-b665c000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-05 02:13:18.185  7046  7046 W art     : b665c000-b665d000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b665d000-b66b0000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-05 02:13:18.185  7046  7046 W art     : b66b0000-b66b1000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b66b1000-b66b2000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-05 02:13:18.185  7046  7046 W art     : b66b2000-b66b3000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-05 02:13:18.185  7046  7046 W art     : b66b3000-b66b8000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b66b8000-b66ca000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-05 02:13:18.185  7046  7046 W art     : b66ca000-b66cb000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b66cb000-b66cc000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-05 02:13:18.185  7046  7046 W art     : b66cc000-b66cd000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-05 02:13:18.185  7046  7046 W art     : b66cd000-b66d4000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 02:13:18.185  7046  7046 W art     : b66d4000-b66d5000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 02:13:18.185  7046  7046 W art     : b66d5000-b66d6000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 02:13:18.185  7046  7046 W art     : b66d6000-b66d7000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b66d7000-b66da000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-05 02:13:18.185  7046  7046 W art     : b66da000-b66db000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-05 02:13:18.185  7046  7046 W art     : b66db000-b66dc000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-05 02:13:18.185  7046  7046 W art     : b66dc000-b66e0000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-05 02:13:18.185  7046  7046 W art     : b66e0000-b66e1000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-05 02:13:18.185  7046  7046 W art     : b66e1000-b66e2000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-05 02:13:18.185  7046  7046 W art     : b66e2000-b66f0000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-05 02:13:18.185  7046  7046 W art     : b66f0000-b66f1000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b66f1000-b66f2000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-05 02:13:18.185  7046  7046 W art     : b66f2000-b66f3000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-05 02:13:18.185  7046  7046 W art     : b66f3000-b66fc000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 02:13:18.185  7046  7046 W art     : b66fc000-b66fd000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 02:13:18.185  7046  7046 W art     : b66fd000-b66fe000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 02:13:18.185  7046  7046 W art     : b66fe000-b6764000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-05 02:13:18.185  7046  7046 W art     : b6764000-b6765000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6765000-b6767000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-05 02:13:18.185  7046  7046 W art     : b6767000-b6770000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-05 02:13:18.185  7046  7046 W art     : b6770000-b6773000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6773000-b680a000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-05 02:13:18.185  7046  7046 W art     : b680a000-b680c000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-05 02:13:18.185  7046  7046 W art     : b680c000-b680d000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-05 02:13:18.185  7046  7046 W art     : b680d000-b680e000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b680e000-b6b2f000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-05 02:13:18.185  7046  7046 W art     : b6b2f000-b6b30000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6b30000-b6b4b000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-05 02:13:18.185  7046  7046 W art     : b6b4b000-b6b4f000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-05 02:13:18.185  7046  7046 W art     : b6b4f000-b6b54000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6b54000-b6b5c000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 02:13:18.185  7046  7046 W art     : b6b5c000-b6b5d000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 02:13:18.185  7046  7046 W art     : b6b5d000-b6b5e000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 02:13:18.185  7046  7046 W art     : b6b5e000-b6b8c000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-05 02:13:18.185  7046  7046 W art     : b6b8c000-b6b8d000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6b8d000-b6b94000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-05 02:13:18.185  7046  7046 W art     : b6b94000-b6b95000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-05 02:13:18.185  7046  7046 W art     : b6b95000-b6bdb000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-05 02:13:18.185  7046  7046 W art     : b6bdb000-b6bdc000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6bdc000-b6bdf000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-05 02:13:18.185  7046  7046 W art     : b6bdf000-b6be0000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-05 02:13:18.185  7046  7046 W art     : b6be0000-b6bfb000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-05 02:13:18.185  7046  7046 W art     : b6bfb000-b6bff000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-05 02:13:18.185  7046  7046 W art     : b6bff000-b6c00000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-05 02:13:18.185  7046  7046 W art     : b6c00000-b6c4d000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-05 02:13:18.185  7046  7046 W art     : b6c4d000-b6c4e000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6c4e000-b6c5a000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-05 02:13:18.185  7046  7046 W art     : b6c5a000-b6c5b000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-05 02:13:18.185  7046  7046 W art     : b6c5b000-b6c68000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-05 02:13:18.185  7046  7046 W art     : b6c68000-b6c69000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6c69000-b6c6a000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-05 02:13:18.185  7046  7046 W art     : b6c6a000-b6c6b000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-05 02:13:18.185  7046  7046 W art     : b6c6b000-b6c73000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-05 02:13:18.185  7046  7046 W art     : b6c73000-b6c74000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6c74000-b6c75000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-05 02:13:18.185  7046  7046 W art     : b6c75000-b6c76000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-05 02:13:18.185  7046  7046 W art     : b6c76000-b6c7d000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-05 02:13:18.185  7046  7046 W art     : b6c7d000-b6c7e000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-05 02:13:18.185  7046  7046 W art     : b6c7e000-b6c7f000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-05 02:13:18.185  7046  7046 W art     : b6c7f000-b6c93000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-05 02:13:18.185  7046  7046 W art     : b6c93000-b6c95000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-05 02:13:18.185  7046  7046 W art     : b6c95000-b6c96000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-05 02:13:18.185  7046  7046 W art     : b6c96000-b6cbe000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-05 02:13:18.185  7046  7046 W art     : b6cbe000-b6cc0000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-05 02:13:18.185  7046  7046 W art     : b6cc0000-b6cc1000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-05 02:13:18.185  7046  7046 W art     : b6cc1000-b6cc4000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-05 02:13:18.185  7046  7046 W art     : b6cc4000-b6cc5000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-05 02:13:18.185  7046  7046 W art     : b6cc5000-b6cc6000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-05 02:13:18.185  7046  7046 W art     : b6cc6000-b6ccf000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-05 02:13:18.185  7046  7046 W art     : b6ccf000-b6cd0000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-05 02:13:18.185  7046  7046 W art     : b6cd0000-b6cd1000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-05 02:13:18.185  7046  7046 W art     : b6cd1000-b6cf1000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-05 02:13:18.185  7046  7046 W art     : b6cf1000-b6cf2000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-05 02:13:18.185  7046  7046 W art     : b6cf2000-b6cf3000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-05 02:13:18.185  7046  7046 W art     : b6cf3000-b6d66000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-05 02:13:18.185  7046  7046 W art     : b6d66000-b6d6a000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-05 02:13:18.185  7046  7046 W art     : b6d6a000-b6d6d000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-05 02:13:18.185  7046  7046 W art     : b6d6d000-b6d77000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6d77000-b6dff000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-05 02:13:18.185  7046  7046 W art     : b6dff000-b6e00000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6e00000-b6e04000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-05 02:13:18.185  7046  7046 W art     : b6e04000-b6e05000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-05 02:13:18.185  7046  7046 W art     : b6e05000-b6e06000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6e06000-b6e2f000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-05 02:13:18.185  7046  7046 W art     : b6e2f000-b6e30000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6e30000-b6e33000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-05 02:13:18.185  7046  7046 W art     : b6e33000-b6e34000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-05 02:13:18.185  7046  7046 W art     : b6e34000-b6f0e000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 02:13:18.185  7046  7046 W art     : b6f0e000-b6f15000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 02:13:18.185  7046  7046 W art     : b6f15000-b6f1d000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 02:13:18.185  7046  7046 W art     : b6f1d000-b6f1e000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6f1e000-b6f1f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:18.185  7046  7046 W art     : b6f1f000-b6f20000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-05 02:13:18.185  7046  7046 W art     : b6f20000-b6f21000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b6f21000-b6f24000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b6f24000-b6f49000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-05 02:13:18.185  7046  7046 W art     : b6f49000-b6f4a000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6f4a000-b6f51000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-05 02:13:18.185  7046  7046 W art     : b6f51000-b6f52000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-05 02:13:18.185  7046  7046 W art     : b6f52000-b6f59000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-05 02:13:18.185  7046  7046 W art     : b6f59000-b6f5a000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-05 02:13:18.185  7046  7046 W art     : b6f5a000-b6f5b000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-05 02:13:18.185  7046  7046 W art     : b6f5b000-b6f5c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b6f5c000-b6f74000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-05 02:13:18.185  7046  7046 W art     : b6f74000-b6f75000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6f75000-b6f76000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-05 02:13:18.185  7046  7046 W art     : b6f76000-b6f77000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-05 02:13:18.185  7046  7046 W art     : b6f77000-b6f85000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-05 02:13:18.185  7046  7046 W art     : b6f85000-b6f86000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6f86000-b6f87000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-05 02:13:18.185  7046  7046 W art     : b6f87000-b6f88000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-05 02:13:18.185  7046  7046 W art     : b6f88000-b6f89000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:18.185  7046  7046 W art     : b6f89000-b6f8b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b6f8b000-b6f8c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b6f8c000-b6f8d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:18.185  7046  7046 W art     : b6f8d000-b6f8e000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-05 02:13:18.185  7046  7046 W art     : b6f8e000-b6f8f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:18.185  7046  7046 W art     : b6f8f000-b6faf000 r--s 00000000 00:0b 7179       /dev/__properties__
08-05 02:13:18.185  7046  7046 W art     : b6faf000-b6fb0000 r--p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6fb0000-b6fb1000 ---p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6fb1000-b6fb3000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-05 02:13:18.185  7046  7046 W art     : b6fb3000-b6fb4000 r-xp 00000000 00:00 0          [sigpage]
08-05 02:13:18.185  7046  7046 W art     : b6fb4000-b6fcf000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-05 02:13:18.185  7046  7046 W art     : b6fcf000-b6fd0000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-05 02:13:18.185  7046  7046 W art     : b6fd0000-b6fd2000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-05 02:13:18.185  7046  7046 W art     : b6fd2000-b6fd4000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : b6fd4000-b6fd9000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-05 02:13:18.185  7046  7046 W art     : b6fd9000-b6fda000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-05 02:13:18.185  7046  7046 W art     : b6fda000-b6fdb000 rw-p 00000000 00:00 0 
08-05 02:13:18.185  7046  7046 W art     : beccf000-becf0000 rw-p 00000000 00:00 0          [stack]
08-05 02:13:18.185  7046  7046 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-05 02:13:18.225  7046  7046 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 02:13:18.275  7046  7046 I Radio-JNI: register_android_hardware_Radio DONE
08-05 02:13:18.285  7046  7046 E AffinityControl: AffinityControl: registerfunction enter
08-05 02:13:18.305  7046  7046 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 02:13:18.315   765  1474 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-05 02:13:18.325   765  1474 D ActivityManager: mDVFSHelper.acquire()
08-05 02:13:18.335   765  1474 V WindowManager: addAppToken: AppWindowToken{42a2e53 token=Token{d9d1e42 ActivityRecord{fed2c8d u0 com.test.thalitest/.MainActivity t115}}} to stack=1 task=115 at 0
08-05 02:13:18.345   765   901 D SecWifiDisplayUtil: Metadata value : none
08-05 02:13:18.345   765   901 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f8f14cb V.E...... R.....ID 0,0-0,0}
08-05 02:13:18.345   765   901 D ISSUE_DEBUG: InputChannelName : 683bbc1 Starting com.test.thalitest
08-05 02:13:18.355  7061  7061 E Zygote  : v2
08-05 02:13:18.355  7061  7061 I libpersona: KNOX_SDCARD checking this for 10004
08-05 02:13:18.355  7061  7061 I libpersona: KNOX_SDCARD not a persona
08-05 02:13:18.365   765  1474 I ActivityManager: Start proc 7061:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-05 02:13:18.365  7061  7061 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-05 02:13:18.365   292   292 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
08-05 02:13:18.365  7061  7061 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:18.365  7061  7061 E Zygote  : accessInfo : 0
08-05 02:13:18.365  7061  7061 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-05 02:13:18.375   765   901 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-05 02:13:18.375   765  1474 D InputDispatcher: Focused application set to: xxxx
08-05 02:13:18.375   765  1474 D InputDispatcher: Focus left window: 3487
08-05 02:13:18.375  7046  7046 D AndroidRuntime: Shutting down VM
08-05 02:13:18.375   765   854 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ef44029 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-05 02:13:18.385   765  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-05 02:13:18.385  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-05 02:13:18.405   765   901 V WindowStateAnimator: Finishing drawing window Window{683bbc1 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-05 02:13:18.415  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 02:13:18.415  7061  7061 D ActivityThread: Added TimaKeyStore provider
08-05 02:13:18.415   765   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
08-05 02:13:18.415   765   901 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:13:18.415   765   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
,08-05 02:13:18.415   765   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:13:18.415   765  2371 V WindowOrientationListener: setCurrentAppOrientation :-1
08-05 02:13:18.415   765  2371 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-05 02:13:18.425   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe893364
08-05 02:13:18.425   765   854 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{683bbc1 u0 d0 Starting com.test.thalitest}
08-05 02:13:18.425  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-05 02:13:18.435   765  2371 D ActivityManager:  Launching com.test.thalitest, updated priority
08-05 02:13:18.435   765   851 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-05 02:13:18.455  1718  1849 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-05 02:13:18.455  1718  1718 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-05 02:13:18.455   292  1296 D libEGL  : eglTerminate EGLDisplay = 0xb47bd64c
08-05 02:13:18.465   292   375 D libEGL  : eglTerminate EGLDisplay = 0xb67bf64c
08-05 02:13:18.465   292  1297 I SurfaceFlinger: id=14 Removed VSBConnecti (7/11)
08-05 02:13:18.465   292   375 D libEGL  : eglTerminate EGLDisplay = 0xb67bf64c
08-05 02:13:18.465   292   369 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/11)
08-05 02:13:18.465   292   369 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
08-05 02:13:18.465   292   375 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
08-05 02:13:18.475   292   369 I SurfaceFlinger: id=15 Removed VSBConnecti (4/9)
08-05 02:13:18.475   292  1297 I SurfaceFlinger: id=15 Removed VSBConnecti (-2/9)
08-05 02:13:18.475   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
08-05 02:13:18.475   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
08-05 02:13:18.475   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
08-05 02:13:18.475  3487  3487 V ActivityThread: updateVisibility : ActivityRecord{ea49cf token=android.os.BinderProxy@8f35871 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-05 02:13:18.475  2140  2152 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-05 02:13:18.475  1718  1718 V ActivityThread: updateVisibility : ActivityRecord{93272eb token=android.os.BinderProxy@f89ed9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 02:13:18.475  1718  1718 D Launcher: onTrimMemory. Level: 20
08-05 02:13:18.495   765  3410 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
08-05 02:13:18.575   765  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-05 02:13:18.585  7061  7061 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-05 02:13:18.595   765  3410 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 02:13:18.605  7061  7061 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 02:13:18.605  7061  7061 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 02:13:18.625  7061  7061 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-05 02:13:18.645  7061  7061 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 02:13:18.645  7061  7061 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-05 02:13:18.655  7061  7061 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 624-627)
08-05 02:13:18.655  7061  7061 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-05 02:13:18.675  7061  7061 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ccad46b}
08-05 02:13:18.675  7061  7061 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-05 02:13:18.675  7061  7061 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 02:13:18.685   765   775 I art     : Background partial concurrent mark sweep GC freed 38775(3MB) AllocSpace objects, 86(1720KB) LOS objects, 27% free, 42MB/58MB, paused 1.519ms total 124.317ms
,08-05 02:13:18.685  7061  7061 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-05 02:13:18.685  7061  7081 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-05 02:13:18.705  7061  7061 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-05 02:13:18.705  7061  7061 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-05 02:13:18.705  7061  7061 I Adreno-EGL: Build Date: 01/28/16 Thu
08-05 02:13:18.705  7061  7061 I Adreno-EGL: Local Branch: ss
08-05 02:13:18.705  7061  7061 I Adreno-EGL: Remote Branch: 
08-05 02:13:18.705  7061  7061 I Adreno-EGL: Local Patches: 
08-05 02:13:18.705  7061  7061 I Adreno-EGL: Reconstruct Branch: 
,08-05 02:13:18.715  7061  7061 D libEGL  : eglInitialize EGLDisplay = 0xbeaf5dac
,08-05 02:13:18.745   765  2385 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-05 02:13:18.745   765  2385 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-05 02:13:18.785  7061  7061 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-05 02:13:18.795  7061  7061 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 02:13:18.795  7061  7061 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-05 02:13:18.795  7061  7061 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-05 02:13:18.795  7061  7061 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-05 02:13:18.815  7061  7061 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-05 02:13:18.815  7061  7061 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-05 02:13:18.915  7061  7061 D SecWifiDisplayUtil: Metadata value : none
,08-05 02:13:18.925  7061  7061 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{e86d741 I.E...... R.....ID 0,0-0,0}
,08-05 02:13:18.925  7061  7105 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 02:13:18.925   765  2392 D ISSUE_DEBUG: InputChannelName : ead86fa com.test.thalitest/com.test.thalitest.MainActivity
,08-05 02:13:18.925   765  2371 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-05 02:13:18.925   765  2371 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-05 02:13:18.925   765   765 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 02:13:18.935   765   765 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-05 02:13:18.945  7061  7061 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7061
,08-05 02:13:18.945   765  2371 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7061 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:18.945   765  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-05 02:13:18.945   765  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-05 02:13:18.945   765  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-05 02:13:18.945   765  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:18.945   765  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:18.945   765  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:18.945   765  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-05 02:13:18.945   765  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-05 02:13:18.945   765  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-05 02:13:18.945   765  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:18.955  7061  7081 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-05 02:13:18.965  7061  7061 D SecWifiDisplayUtil: Metadata value : none
,08-05 02:13:18.965   292   292 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-05 02:13:18.985   765   781 D InputDispatcher: Focus entered window: 7061
,08-05 02:13:18.985   765   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
,08-05 02:13:18.985   765   901 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:13:18.985   765   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-05 02:13:18.985   765   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:13:18.985  7061  7105 D libEGL  : eglInitialize EGLDisplay = 0x9d67f7c4
08-05 02:13:18.985  7061  7105 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 02:13:19.025  7061  7061 V ActivityThread: updateVisibility : ActivityRecord{a8eaa40 token=android.os.BinderProxy@b3c3e28 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 02:13:19.035  7061  7061 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-05 02:13:19.035  7061  7061 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-05 02:13:19.055   765  1272 V WindowStateAnimator: Finishing drawing window Window{ead86fa u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-05 02:13:19.055  7061  7061 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 02:13:19.055   765  1731 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 02:13:19.065   765   901 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 02:13:19.065   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbe893364
,08-05 02:13:19.065   765   901 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +495ms (total +734ms)
,08-05 02:13:19.065   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-05 02:13:19.065   765   765 I KnoxTimeoutHandler: SD activityfalse
,08-05 02:13:19.085  7061  7061 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b3c3e28 time:301052
,08-05 02:13:19.085   765   901 D ActivityManager: mDVFSHelper.release()
,08-05 02:13:19.085   765   901 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fed2c8d u0 com.test.thalitest/.MainActivity t115} time:301054
,08-05 02:13:19.085   765   901 D ViewRootImpl: #3 mView = null
,08-05 02:13:19.085   292  1297 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
,08-05 02:13:19.085   292   375 I SurfaceFlinger: id=16 Removed uhalitest (-2/9)
,08-05 02:13:19.095  7061  7061 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-05 02:13:19.095   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
,08-05 02:13:19.145  7061  7124 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 02:13:19.145  7061  7124 D libEGL  : eglInitialize EGLDisplay = 0x9c22f3ec
,08-05 02:13:19.165   765  1587 E Watchdog: !@Sync 9 [08-05 02:13:19.178]
,08-05 02:13:19.185  7061  7061 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7061
,08-05 02:13:19.355  7061  7061 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 02:13:19.455  7061  7135 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1683490512
,08-05 02:13:19.455  7061  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 02:13:19.455  7061  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 02:13:19.455  7061  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 02:13:19.455  7061  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 02:13:19.455  7061  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 02:13:19.455  7061  7135 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b71396 added. We now have 1 listener(s)
,08-05 02:13:19.455  7061  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-05 02:13:19.465  7061  7135 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-05 02:13:19.465  7061  7135 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 02:13:19.465  7061  7135 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 02:13:19.465  7061  7135 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31528ed added. We now have 1 listener(s)
08-05 02:13:19.465  7061  7135 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 02:13:19.465  7061  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 02:13:19.465  7061  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 02:13:19.465  7061  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 02:13:19.465  7061  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 02:13:19.465  7061  7135 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 02:13:19.475  7061  7135 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 02:13:19.475  7061  7135 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-05 02:13:19.475  7061  7135 D BluetoothAdapter: STATE_ON
,08-05 02:13:19.475  7061  7135 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:13:19.475  7061  7135 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:13:19.475  7061  7135 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-05 02:13:19.475  7061  7135 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 02:13:19.475  7061  7135 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 02:13:19.475  7061  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 02:13:19.485  7061  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 02:13:19.505  7061  7061 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 02:13:19.575   765  3411 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-05 02:13:19.935  1455  1455 D Recents : onTaskStackChanged
,08-05 02:13:19.945  1455  1455 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-05 02:13:20.545  7061  7139 W jxcore-log: Initializing JXcore engine
,08-05 02:13:20.545  7061  7139 W jxcore-log: JXcore engine is ready
,08-05 02:13:20.595  2304  2304 E audit   : type=1400 msg=audit(1470356000.585:287): avc:  denied  { ioctl } for  pid=7139 comm="Thread-972" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-05 02:13:20.595  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 02:13:20.595  2304  2304 E audit   : type=1300 msg=audit(1470356000.585:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9b97a3c8 items=0 ppid=340 ppcomm=main pid=7139 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-972" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 02:13:20.595  2304  2304 E audit   : type=1327 msg=audit(1470356000.585:287): proctitle="com.test.thalitest"
08-05 02:13:20.595  2304  2304 E audit   : type=1320 msg=audit(1470356000.585:287): 
08-05 02:13:20.595  2304  2304 E audit   : type=1400 msg=audit(1470356000.595:288): avc:  denied  { ioctl } for  pid=7139 comm="Thread-972" path="socket:[43498]" dev="sockfs" ino=43498 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-05 02:13:20.595  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 02:13:20.595  2304  2304 E audit   : type=1300 msg=audit(1470356000.595:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=1 a3=9b97a3c8 items=0 ppid=340 ppcomm=main pid=7139 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-972" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-05 02:13:20.595  2304  2304 E audit   : type=1327 msg=audit(1470356000.595:288): proctitle="com.test.thalitest"
08-05 02:13:20.595  2304  2304 E audit   : type=1320 msg=audit(1470356000.595:288): 
,08-05 02:13:20.605  7061  7139 W jxcore-log: Starting JXcore engine
,08-05 02:13:20.675  7061  7139 W jxcore-log: Platform android
08-05 02:13:20.675  7061  7139 W jxcore-log: 
,08-05 02:13:20.675  7061  7139 W jxcore-log: Process ARCH arm
08-05 02:13:20.675  7061  7139 W jxcore-log: 
,08-05 02:13:20.885  7061  7139 I jxcore-log: JXcore Cordova bridge is ready!
08-05 02:13:20.885  7061  7139 I jxcore-log: 
,08-05 02:13:20.885  7061  7139 W jxcore-log: JXcore engine is started
,08-05 02:13:20.885  7061  7135 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 02:13:20.885  7061  7061 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 02:13:21.385   765  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/115_task.xml.bak
,08-05 02:13:24.605   765  3410 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-05 02:13:28.365   765   925 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 02:13:28.405   765   925 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 02:13:28.625   765  3410 D SSRM:n  : SIOP:: AP = 340, PST = 308, CUR = 450, LCD = 0
,08-05 02:13:28.825   765  3455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 02:13:33.935   765  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-05 02:13:33.945   765  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-05 02:13:33.945   765  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-05 02:13:33.955   765  1229 I TLC_TIMA_PKM_initialize: initializing...
08-05 02:13:33.955   765  1229 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-05 02:13:33.955   765  1229 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-05 02:13:33.955   765  1229 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-05 02:13:33.955   765  1229 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-05 02:13:33.955   765  1229 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
08-05 02:13:33.955   765  1229 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-05 02:13:33.955   765  1229 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-05 02:13:33.955   765  1229 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-05 02:13:33.955   765  1229 D QSEECOMAPI: : App is not loaded in QSEE
,08-05 02:13:33.975   765  1229 D QSEECOMAPI: : Loaded image: APP id = 4
,08-05 02:13:33.975   765  1229 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-05 02:13:33.985   765  1229 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-05 02:13:36.665   765  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
08-05 02:13:36.665   765  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-05 02:13:36.675   765  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-05 02:13:36.685   765  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-05 02:13:36.835  7061  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 02:13:36.835  7061  7139 I jxcore-log: 
,08-05 02:13:36.835  7061  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 02:13:36.835  7061  7139 I jxcore-log: 
,08-05 02:13:36.845  7061  7139 D BluetoothAdapter: STATE_ON
,08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:13:36.845  7061  7139 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 02:13:36.845  7061  7139 D BluetoothAdapter: STATE_ON
,08-05 02:13:36.845  7061  7139 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 02:13:36.845  7061  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 02:13:36.845  7061  7139 I jxcore-log: 
,08-05 02:13:36.855  7061  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 02:13:36.855  7061  7139 I jxcore-log: 
,08-05 02:13:37.195  7061  7139 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-05 02:13:37.195  7061  7139 I jxcore-log: Failed to execute UT.
08-05 02:13:37.195  7061  7139 I jxcore-log: 
08-05 02:13:37.195  7061  7139 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-05 02:13:37.195  7061  7139 I jxcore-log: 
,08-05 02:13:37.205  7061  7139 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 02:13:37.205  7061  7139 I jxcore-log: 
08-05 02:13:37.205  7061  7061 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 02:13:38.065  2304  2304 E audit   : type=1400 msg=audit(1470356018.065:289): avc:  denied  { execmod } for  pid=7157 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 02:13:38.065  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-05 02:13:38.075  2304  2304 E audit   : type=1300 msg=audit(1470356018.065:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f43000 a1=51000 a2=5 a3=4 items=0 ppid=3563 ppcomm=adbd pid=7157 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 02:13:38.075  2304  2304 E audit   : type=1327 msg=audit(1470356018.065:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-05 02:13:38.075  2304  2304 E audit   : type=1320 msg=audit(1470356018.065:289): 
,08-05 02:13:38.125  2304  2304 E audit   : type=1400 msg=audit(1470356018.125:290): avc:  denied  { execmod } for  pid=7157 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 02:13:38.125  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:38.125  2304  2304 E audit   : type=1300 msg=audit(1470356018.125:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f02000 a1=51000 a2=5 a3=4 items=0 ppid=3563 ppcomm=adbd pid=7157 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 02:13:38.125  2304  2304 E audit   : type=1327 msg=audit(1470356018.125:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-05 02:13:38.125  2304  2304 E audit   : type=1320 msg=audit(1470356018.125:290): 
,08-05 02:13:38.165  2304  2304 E audit   : type=1400 msg=audit(1470356018.165:291): avc:  denied  { execmod } for  pid=7157 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-05 02:13:38.165  7157  7157 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 02:13:38.165  2304  2304 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:38.165  2304  2304 E audit   : type=1300 msg=audit(1470356018.165:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f03000 a1=51000 a2=5 a3=4 items=0 ppid=3563 ppcomm=adbd pid=7157 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-05 02:13:38.165  2304  2304 E audit   : type=1327 msg=audit(1470356018.165:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-05 02:13:38.165  2304  2304 E audit   : type=1320 msg=audit(1470356018.165:291): 
08-05 02:13:38.175  7157  7157 D AndroidRuntime: CheckJNI is OFF
08-05 02:13:38.175  7157  7157 D AndroidRuntime: readGMSProperty: start
08-05 02:13:38.175  7157  7157 D AndroidRuntime: readGMSProperty: already setted!!
08-05 02:13:38.175  7157  7157 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-05 02:13:38.175  7157  7157 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-05 02:13:38.175  7157  7157 D AndroidRuntime: readGMSProperty: end
08-05 02:13:38.175  7157  7157 D AndroidRuntime: addProductProperty: start
,08-05 02:13:38.175  7157  7157 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art,
08-05 02:13:38.175  7157  7157 W art     : af0a4000-b1fca000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
,08-05 02:13:38.175  7157  7157 W art     : b1fca000-b4239000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
,08-05 02:13:38.175  7157  7157 W art     : b4239000-b423a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-05 02:13:38.175  7157  7157 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-05 02:13:38.175  7157  7157 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-05 02:13:38.175  7157  7157 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
,08-05 02:13:38.175  7157  7157 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-05 02:13:38.175  7157  7157 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so,
08-05 02:13:38.175  7157  7157 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
,08-05 02:13:38.175  7157  7157 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-05 02:13:38.175  7157  7157 W art     : b47d1000-b47d4000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-05 02:13:38.175  7157  7157 W art     : b47d4000-b47d5000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
,08-05 02:13:38.175  7157  7157 W art     : b47d5000-b47d6000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
,08-05 02:13:38.175  7157  7157 W art     : b47d6000-b47d7000 r--p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b47d7000-b47f7000 r--s 00000000 00:0b 7179       /dev/__properties__
,08-05 02:13:38.175  7157  7157 W art     : b47f7000-b5208000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-05 02:13:38.175  7157  7157 W art     : b5208000-b5209000 ---p 00000000 00:00 0 ,
08-05 02:13:38.175  7157  7157 W art     : b5209000-b5252000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
,08-05 02:13:38.175  7157  7157 W art     : b5252000-b5253000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-05 02:13:38.175  7157  7157 W art     : b5253000-b525b000 rw-p 00000000 00:00 0 
,08-05 02:13:38.175  7157  7157 W art     : b525b000-b525c000 r--p 00000000 00:00 0          [anon:linker_alloc],
08-05 02:13:38.175  7157  7157 W art     : b525c000-b5291000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
,08-05 02:13:38.175  7157  7157 W art     : b5291000-b5292000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b5292000-b5293000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-05 02:13:38.175  7157  7157 W art     : b5293000-b5294000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-05 02:13:38.175  7157  7157 W art     : b5294000-b52ec000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-05 02:13:38.175  7157  7157 W art     : b52ec000-b52ed000 ---p 00000000 00:00 0 
,08-05 02:13:38.175  7157  7157 W art     : b52ed000-b52ee000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-05 02:13:38.175  7157  7157 W art     : b52ee000-b52ef000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-05 02:13:38.175  7157  7157 W art     : b52f0000-b52f6000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 02:13:38.175  7157  7157 W art     : b52f6000-b52f7000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so,
08-05 02:13:38.175  7157  7157 W art     : b52f7000-b52f8000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-05 02:13:38.175  7157  7157 W art     : b52f8000-b52fa000 rw-p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b52fb000-b5305000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 02:13:38.175  7157  7157 W art     : b5305000-b5308000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 02:13:38.175  7157  7157 W art     : b5308000-b5309000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-05 02:13:38.175  7157  7157 W art     : b530a000-b5321000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 02:13:38.175  7157  7157 W art     : b5321000-b5322000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b5322000-b5323000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 02:13:38.175  7157  7157 W art     : b5323000-b5324000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-05 02:13:38.175  7157  7157 W art     : b5325000-b532f000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
,08-05 02:13:38.175  7157  7157 W art     : b532f000-b5330000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
,08-05 02:13:38.175  7157  7157 W art     : b5330000-b5331000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-05 02:13:38.175  7157  7157 W art     : b5331000-b5335000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 02:13:38.175  7157  7157 W art     : b5335000-b5336000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 02:13:38.175  7157  7157 W art     : b5336000-b5337000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-05 02:13:38.175  7157  7157 W art     : b5337000-b534d000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-05 02:13:38.175  7157  7157 W art     : b534d000-b534e000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-05 02:13:38.175  7157  7157 W art     : b534e000-b534f000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-05 02:13:38.175  7157  7157 W art     : b534f000-b535c000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-05 02:13:38.175  7157  7157 W art     : b535c000-b535d000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-05 02:13:38.175  7157  7157 W art     : b535d000-b535e000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-05 02:13:38.175  7157  7157 W art     : b535e000-b53be000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-05 02:13:38.175  7157  7157 W art     : b53be000-b53c1000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-05 02:13:38.175  7157  7157 W art     : b53c1000-b53c5000 rw-p 00000000 00:00 0 
,08-05 02:13:38.175  7157  7157 W art     : b53c5000-b5426000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-05 02:13:38.175  7157  7157 W art     : b5426000-b5427000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-05 02:13:38.175  7157  7157 W art     : b5427000-b5476000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-05 02:13:38.175  7157  7157 W art     : b5476000-b5478000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-05 02:13:38.175  7157  7157 W art     : b5478000-b5479000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-05 02:13:38.175  7157  7157 W art     : b5479000-b547a000 rw-p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b547a000-b5481000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
,08-05 02:13:38.175  7157  7157 W art     : b5481000-b5482000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-05 02:13:38.175  7157  7157 W art     : b5482000-b5483000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-05 02:13:38.175  7157  7157 W art     : avc_common.so
08-05 02:13:38.175  7157  7157 W art     : b5484000-b5487000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 02:13:38.175  7157  7157 W art     : b5487000-b5488000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-05 02:13:38.175  7157  7157 W art     : b5488000-b5489000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-05 02:13:38.175  7157  7157 W art     : enc_common.so
08-05 02:13:38.175  7157  7157 W art     : b548a000-b548e000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-05 02:13:38.175  7157  7157 W art     : b548e000-b548f000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b548f000-b5490000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-05 02:13:38.175  7157  7157 W art     : b5490000-b5491000 rw-p 00005000 b3:17 2510       /syste
08-05 02:13:38.175  7157  7157 W art     : m/lib/libpowermanager.so
08-05 02:13:38.175  7157  7157 W art     : b5492000-b54af000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 02:13:38.175  7157  7157 W art     : b54af000-b54b0000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-05 02:13:38.175  7157  7157 W art     : b54b0000-b54b1000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
,08-05 02:13:38.175  7157  7157 W art     : b54b2000-b54b7000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 02:13:38.175  7157  7157 W art     : b54b7000-b54b8000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 02:13:38.175  7157  7157 W art     : b54b8000-b54b9000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-05 02:13:38.175  7157  7157 W art     : b54ba000-b54eb000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 02:13:38.175  7157  7157 W art     : b54eb000-b54ee000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 02:13:38.175  7157  7157 W art     : b54ee000-b54ef000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-05 02:13:38.175  7157  7157 W art     : b54f0000-b552b000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-05 02:13:38.175  7157  7157 W art     : b552b000-b552c000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-05 02:13:38.175  7157  7157 W art     : b552c000-b552d000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-05 02:13:38.175  7157  7157 W art     : b552e000-b5535000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-05 02:13:38.175  7157  7157 W art     : b5535000-b5536000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b5536000-b5537000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-05 02:13:38.175  7157  7157 W art     : b5537000-b5538000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-05 02:13:38.175  7157  7157 W art     : b5538000-b5539000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.175  7157  7157 W art     : b5539000-b5550000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-05 02:13:38.175  7157  7157 W art     : b5550000-b5551000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b5551000-b5554000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-05 02:13:38.175  7157  7157 W art     : b5554000-b5555000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-05 02:13:38.175  7157  7157 W art     : b5555000-b5574000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-05 02:13:38.175  7157  7157 W art     : b5574000-b5575000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-05 02:13:38.175  7157  7157 W art     : b5575000-b5576000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-05 02:13:38.175  7157  7157 W art     : b5576000-b55b4000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-05 02:13:38.175  7157  7157 W art     : b55b4000-b55b5000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b55b5000-b55b7000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
,08-05 02:13:38.175  7157  7157 W art     : b55b7000-b55b8000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-05 02:13:38.175  7157  7157 W art     : b55b9000-b55c0000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 02:13:38.175  7157  7157 W art     : b55c0000-b55c1000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 02:13:38.175  7157  7157 W art     : b55c1000-b55c2000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-05 02:13:38.175  7157  7157 W art     : b55c3000-b55c6000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 02:13:38.175  7157  7157 W art     : b55c6000-b55c7000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 02:13:38.175  7157  7157 W art     : b55c7000-b55c8000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-05 02:13:38.175  7157  7157 W art     : b55c8000-b55ce000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 02:13:38.175  7157  7157 W art     : b55ce000-b55cf000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b55cf000-b55d0000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 02:13:38.175  7157  7157 W art     : b55d0000-b55d1000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-05 02:13:38.175  7157  7157 W art     : b55d1000-b55da000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-05 02:13:38.175  7157  7157 W art     : b55da000-b55db000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-05 02:13:38.175  7157  7157 W art     : b55db000-b55dc000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-05 02:13:38.175  7157  7157 W art     : b55dc000-b566d000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 02:13:38.175  7157  7157 W art     : b566d000-b566e000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b566e000-b5679000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 02:13:38.175  7157  7157 W art     : b5679000-b567a000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-05 02:13:38.175  7157  7157 W art     : b567b000-b568d000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-05 02:13:38.175  7157  7157 W art     : b568d000-b568e000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-05 02:13:38.175  7157  7157 W art     : b568e000-b568f000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-05 02:13:38.175  7157  7157 W art     : b5690000-b5695000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-05 02:13:38.175  7157  7157 W art     : b5695000-b5696000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-05 02:13:38.175  7157  7157 W art     : b5696000-b5697000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-05 02:13:38.175  7157  7157 W art     : b5698000-b5705000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-05 02:13:38.175  7157  7157 W art     : b5705000-b5706000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b5706000-b5708000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-05 02:13:38.175  7157  7157 W art     : b5708000-b5709000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-05 02:13:38.175  7157  7157 W art     : b5709000-b570a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.175  7157  7157 W art     : b570a000-b5711000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
,08-05 02:13:38.175  7157  7157 W art     : b5711000-b5712000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 02:13:38.175  7157  7157 W art     : b5712000-b5713000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-05 02:13:38.175  7157  7157 W art     : b5714000-b5794000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 02:13:38.175  7157  7157 W art     : b5794000-b5795000 ---p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b5795000-b5796000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-05 02:13:38.175  7157  7157 W art     : b5796000-b5797000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
,08-05 02:13:38.175  7157  7157 W art     : b5797000-b57ae000 rw-p 00000000 00:00 0 
08-05 02:13:38.175  7157  7157 W art     : b57ae000-b57e5000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-05 02:13:38.175  7157  7157 W art     : ib/libqc-opt.so
08-05 02:13:38.185  7157  7157 W art     : b57e5000-b57e6000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 02:13:38.185  7157  7157 W art     : b57e6000-b57e7000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-05 02:13:38.185  7157  7157 W art     : b57e7000-b5803000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 02:13:38.185  7157  7157 W art     : b5803000-b5804000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 02:13:38.185  7157  7157 W art     : b5804000-b5805000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-05 02:13:38.185  7157  7157 W art     : b5806000-b5867000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-05 02:13:38.185  7157  7157 W art     : b5867000-b5869000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-05 02:13:38.185  7157  7157 W art     : b5869000-b586a000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-05 02:13:38.185  7157  7157 W art     : b586b000-b5892000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-05 02:13:38.185  7157  7157 W art     : b5892000-b5893000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5893000-b5894000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-05 02:13:38.185  7157  7157 W art     : b5894000-b5895000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-05 02:13:38.185  7157  7157 W art     : b5896000-b589e000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 02:13:38.185  7157  7157 W art     : b589e000-b58a0000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 02:13:38.185  7157  7157 W art     : b58a0000-b58a1000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-05 02:13:38.185  7157  7157 W art     : b58a2000-b58a5000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-05 02:13:38.185  7157  7157 W art     : b58a5000-b58a6000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-05 02:13:38.185  7157  7157 W art     : b58a6000-b58a7000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-05 02:13:38.185  7157  7157 W art     : b58a7000-b58ab000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-05 02:13:38.185  7157  7157 W art     : b58ab000-b58ac000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b58ac000-b58ad000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-05 02:13:38.185  7157  7157 W art     : b58ad000-b58ae000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-05 02:13:38.185  7157  7157 W art     : b58ae000-b58be000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-05 02:13:38.185  7157  7157 W art     : b58be000-b58bf000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-05 02:13:38.185  7157  7157 W art     : b58bf000-b58c0000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-05 02:13:38.185  7157  7157 W art     : b58c0000-b5906000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5906000-b590f000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-05 02:13:38.185  7157  7157 W art     : b590f000-b5910000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-05 02:13:38.185  7157  7157 W art     : b5910000-b5911000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-05 02:13:38.185  7157  7157 W art     : b5912000-b5917000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-05 02:13:38.185  7157  7157 W art     : b5917000-b5918000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-05 02:13:38.185  7157  7157 W art     : b5918000-b5919000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-05 02:13:38.185  7157  7157 W art     : b5919000-b591c000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 02:13:38.185  7157  7157 W art     : b591c000-b591d000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b591d000-b591e000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 02:13:38.185  7157  7157 W art     : b591e000-b591f000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-05 02:13:38.185  7157  7157 W art     : b5920000-b5938000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 02:13:38.185  7157  7157 W art     : b5938000-b5939000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5939000-b593a000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 02:13:38.185  7157  7157 W art     : b593a000-b593b000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-05 02:13:38.185  7157  7157 W art     : b593c000-b5ad6000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-05 02:13:38.185  7157  7157 W art     : b5ad6000-b5ad7000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5ad7000-b5ae4000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-05 02:13:38.185  7157  7157 W art     : b5ae4000-b5ae5000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-05 02:13:38.185  7157  7157 W art     : b5ae5000-b5ae9000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-05 02:13:38.185  7157  7157 W art     : b5ae9000-b5aea000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5aea000-b5aeb000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-05 02:13:38.185  7157  7157 W art     : b5aeb000-b5aec000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-05 02:13:38.185  7157  7157 W art     : b5aec000-b5aff000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-05 02:13:38.185  7157  7157 W art     : b5aff000-b5b00000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-05 02:13:38.185  7157  7157 W art     : b5b00000-b5b01000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-05 02:13:38.185  7157  7157 W art     : b5b01000-b5b02000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:38.185  7157  7157 W art     : b5b02000-b5b4d000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-05 02:13:38.185  7157  7157 W art     : b5b4d000-b5b4e000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-05 02:13:38.185  7157  7157 W art     : b5b4e000-b5b4f000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-05 02:13:38.185  7157  7157 W art     : b5b4f000-b5b51000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5b52000-b5b63000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 02:13:38.185  7157  7157 W art     : b5b63000-b5b64000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5b64000-b5b65000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 02:13:38.185  7157  7157 W art     : b5b65000-b5b66000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-05 02:13:38.185  7157  7157 W art     : b5b67000-b5b71000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-05 02:13:38.185  7157  7157 W art     : b5b71000-b5b73000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-05 02:13:38.185  7157  7157 W art     : b5b73000-b5b74000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-05 02:13:38.185  7157  7157 W art     : b5b74000-b5b8d000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-05 02:13:38.185  7157  7157 W art     : b5b8d000-b5b8e000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-05 02:13:38.185  7157  7157 W art     : b5b8e000-b5b91000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-05 02:13:38.185  7157  7157 W art     : b5b91000-b5b95000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5b95000-b5c09000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-05 02:13:38.185  7157  7157 W art     : b5c09000-b5c0a000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5c0a000-b5c0d000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-05 02:13:38.185  7157  7157 W art     : b5c0d000-b5c0e000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-05 02:13:38.185  7157  7157 W art     : b5c0e000-b5c0f000 r--p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5c0f000-b5c12000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-05 02:13:38.185  7157  7157 W art     : b5c12000-b5c13000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-05 02:13:38.185  7157  7157 W art     : b5c13000-b5c14000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-05 02:13:38.185  7157  7157 W art     : b5c14000-b5c15000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b5c15000-b5c1a000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 02:13:38.185  7157  7157 W art     : b5c1a000-b5c1b000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 02:13:38.185  7157  7157 W art     : b5c1b000-b5c1c000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-05 02:13:38.185  7157  7157 W art     : b5c1c000-b5c1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b5c1d000-b5c20000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 02:13:38.185  7157  7157 W art     : b5c20000-b5c21000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 02:13:38.185  7157  7157 W art     : b5c21000-b5c22000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-05 02:13:38.185  7157  7157 W art     : b5c22000-b5c23000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b5c23000-b5c27000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-05 02:13:38.185  7157  7157 W art     : b5c27000-b5c28000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-05 02:13:38.185  7157  7157 W art     : b5c28000-b5c29000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-05 02:13:38.185  7157  7157 W art     : b5c29000-b5c2a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:38.185  7157  7157 W art     : b5c2a000-b5c2e000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 02:13:38.185  7157  7157 W art     : b5c2e000-b5c2f000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 02:13:38.185  7157  7157 W art     : b5c2f000-b5c30000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-05 02:13:38.185  7157  7157 W art     : b5c30000-b5c31000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b5c31000-b5c3f000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-05 02:13:38.185  7157  7157 W art     : b5c3f000-b5c40000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b5c40000-b5c41000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-05 02:13:38.185  7157  7157 W art     : b5c41000-b5c42000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-05 02:13:38.185  7157  7157 W art     : b5c42000-b5c4c000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 02:13:38.185  7157  7157 W art     : b5c4c000-b5c4f000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 02:13:38.185  7157  7157 W art     : b5c4f000-b5c50000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-05 02:13:38.185  7157  7157 W art     : b5c50000-b5c51000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b5c51000-b5c5b000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-05 02:13:38.185  7157  7157 W art     : b5c5b000-b5c5e000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-05 02:13:38.185  7157  7157 W art     : b5c5e000-b5c5f000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-05 02:13:38.185  7157  7157 W art     : b5c5f000-b5c63000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-05 02:13:38.185  7157  7157 W art     : b5c63000-b5c64000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-05 02:13:38.185  7157  7157 W art     : b5c64000-b5c65000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-05 02:13:38.185  7157  7157 W art     : b5c65000-b5c66000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b5c66000-b5c73000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-05 02:13:38.185  7157  7157 W art     : b5c73000-b5c75000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-05 02:13:38.185  7157  7157 W art     : b5c75000-b5c76000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-05 02:13:38.185  7157  7157 W art     : b5c76000-b6088000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-05 02:13:38.185  7157  7157 W art     : b6088000-b6089000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6089000-b6092000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-05 02:13:38.185  7157  7157 W art     : b6092000-b6096000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-05 02:13:38.185  7157  7157 W art     : b6096000-b6097000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6097000-b609e000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-05 02:13:38.185  7157  7157 W art     : b609e000-b609f000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-05 02:13:38.185  7157  7157 W art     : b609f000-b60a0000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-05 02:13:38.185  7157  7157 W art     : b60a0000-b60a1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b60a1000-b60bc000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-05 02:13:38.185  7157  7157 W art     : b60bc000-b60bd000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-05 02:13:38.185  7157  7157 W art     : b60bd000-b60be000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-05 02:13:38.185  7157  7157 W art     : b60be000-b60bf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b60bf000-b610b000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 02:13:38.185  7157  7157 W art     : b610b000-b610c000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b610c000-b610d000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 02:13:38.185  7157  7157 W art     : b610d000-b610e000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-05 02:13:38.185  7157  7157 W art     : b610e000-b610f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b610f000-b6113000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-05 02:13:38.185  7157  7157 W art     : b6113000-b6114000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6114000-b6115000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-05 02:13:38.185  7157  7157 W art     : b6115000-b6116000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-05 02:13:38.185  7157  7157 W art     : b6116000-b614e000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-05 02:13:38.185  7157  7157 W art     : b614e000-b614f000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-05 02:13:38.185  7157  7157 W art     : b614f000-b6150000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-05 02:13:38.185  7157  7157 W art     : b6150000-b6151000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6151000-b61ef000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-05 02:13:38.185  7157  7157 W art     : b61ef000-b61f0000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b61f0000-b620e000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-05 02:13:38.185  7157  7157 W art     : b620e000-b620f000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-05 02:13:38.185  7157  7157 W art     : b620f000-b6382000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-05 02:13:38.185  7157  7157 W art     : b6382000-b638d000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-05 02:13:38.185  7157  7157 W art     : b638d000-b638e000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-05 02:13:38.185  7157  7157 W art     : b638e000-b64a5000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-05 02:13:38.185  7157  7157 W art     : b64a5000-b64b0000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-05 02:13:38.185  7157  7157 W art     : b64b0000-b64b1000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-05 02:13:38.185  7157  7157 W art     : b64b1000-b64b5000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b64b5000-b64d9000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-05 02:13:38.185  7157  7157 W art     : b64d9000-b64db000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-05 02:13:38.185  7157  7157 W art     : b64db000-b64dc000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-05 02:13:38.185  7157  7157 W art     : b64dc000-b6582000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-05 02:13:38.185  7157  7157 W art     : b6582000-b658f000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-05 02:13:38.185  7157  7157 W art     : b658f000-b6590000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-05 02:13:38.185  7157  7157 W art     : b6590000-b6591000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6591000-b65e4000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-05 02:13:38.185  7157  7157 W art     : b65e4000-b65e5000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b65e5000-b65e6000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-05 02:13:38.185  7157  7157 W art     : b65e6000-b65e7000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-05 02:13:38.185  7157  7157 W art     : b65e7000-b65ec000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b65ec000-b65fe000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-05 02:13:38.185  7157  7157 W art     : b65fe000-b65ff000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b65ff000-b6600000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-05 02:13:38.185  7157  7157 W art     : b6600000-b6601000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-05 02:13:38.185  7157  7157 W art     : b6601000-b6608000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 02:13:38.185  7157  7157 W art     : b6608000-b6609000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 02:13:38.185  7157  7157 W art     : b6609000-b660a000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-05 02:13:38.185  7157  7157 W art     : b660a000-b660b000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b660b000-b660e000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-05 02:13:38.185  7157  7157 W art     : b660e000-b660f000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-05 02:13:38.185  7157  7157 W art     : b660f000-b6610000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-05 02:13:38.185  7157  7157 W art     : b6610000-b6614000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-05 02:13:38.185  7157  7157 W art     : b6614000-b6615000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-05 02:13:38.185  7157  7157 W art     : b6615000-b6616000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-05 02:13:38.185  7157  7157 W art     : b6616000-b6624000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-05 02:13:38.185  7157  7157 W art     : b6624000-b6625000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6625000-b6626000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-05 02:13:38.185  7157  7157 W art     : b6626000-b6627000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-05 02:13:38.185  7157  7157 W art     : b6627000-b6630000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 02:13:38.185  7157  7157 W art     : b6630000-b6631000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 02:13:38.185  7157  7157 W art     : b6631000-b6632000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-05 02:13:38.185  7157  7157 W art     : b6632000-b6698000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-05 02:13:38.185  7157  7157 W art     : b6698000-b6699000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6699000-b669b000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-05 02:13:38.185  7157  7157 W art     : b669b000-b66a4000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-05 02:13:38.185  7157  7157 W art     : b66a4000-b66a7000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b66a7000-b673e000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-05 02:13:38.185  7157  7157 W art     : b673e000-b6740000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-05 02:13:38.185  7157  7157 W art     : b6740000-b6741000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-05 02:13:38.185  7157  7157 W art     : b6741000-b6742000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6742000-b6a63000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-05 02:13:38.185  7157  7157 W art     : b6a63000-b6a64000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6a64000-b6a7f000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-05 02:13:38.185  7157  7157 W art     : b6a7f000-b6a83000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-05 02:13:38.185  7157  7157 W art     : b6a83000-b6a88000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6a88000-b6a90000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 02:13:38.185  7157  7157 W art     : b6a90000-b6a91000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 02:13:38.185  7157  7157 W art     : b6a91000-b6a92000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-05 02:13:38.185  7157  7157 W art     : b6a92000-b6ac0000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-05 02:13:38.185  7157  7157 W art     : b6ac0000-b6ac1000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6ac1000-b6ac8000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-05 02:13:38.185  7157  7157 W art     : b6ac8000-b6ac9000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-05 02:13:38.185  7157  7157 W art     : b6ac9000-b6b0f000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-05 02:13:38.185  7157  7157 W art     : b6b0f000-b6b10000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6b10000-b6b13000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-05 02:13:38.185  7157  7157 W art     : b6b13000-b6b14000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-05 02:13:38.185  7157  7157 W art     : b6b14000-b6b2f000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-05 02:13:38.185  7157  7157 W art     : b6b2f000-b6b33000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-05 02:13:38.185  7157  7157 W art     : b6b33000-b6b34000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-05 02:13:38.185  7157  7157 W art     : b6b34000-b6b81000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-05 02:13:38.185  7157  7157 W art     : b6b81000-b6b82000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6b82000-b6b8e000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-05 02:13:38.185  7157  7157 W art     : b6b8e000-b6b8f000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-05 02:13:38.185  7157  7157 W art     : b6b8f000-b6b9c000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-05 02:13:38.185  7157  7157 W art     : b6b9c000-b6b9d000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6b9d000-b6b9e000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-05 02:13:38.185  7157  7157 W art     : b6b9e000-b6b9f000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-05 02:13:38.185  7157  7157 W art     : b6b9f000-b6ba7000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-05 02:13:38.185  7157  7157 W art     : b6ba7000-b6ba8000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6ba8000-b6ba9000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-05 02:13:38.185  7157  7157 W art     : b6ba9000-b6baa000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-05 02:13:38.185  7157  7157 W art     : b6baa000-b6bb1000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-05 02:13:38.185  7157  7157 W art     : b6bb1000-b6bb2000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-05 02:13:38.185  7157  7157 W art     : b6bb2000-b6bb3000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-05 02:13:38.185  7157  7157 W art     : b6bb3000-b6bc7000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-05 02:13:38.185  7157  7157 W art     : b6bc7000-b6bc9000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-05 02:13:38.185  7157  7157 W art     : b6bc9000-b6bca000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-05 02:13:38.185  7157  7157 W art     : b6bca000-b6bf2000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-05 02:13:38.185  7157  7157 W art     : b6bf2000-b6bf4000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-05 02:13:38.185  7157  7157 W art     : b6bf4000-b6bf5000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-05 02:13:38.185  7157  7157 W art     : b6bf5000-b6bf8000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-05 02:13:38.185  7157  7157 W art     : b6bf8000-b6bf9000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-05 02:13:38.185  7157  7157 W art     : b6bf9000-b6bfa000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-05 02:13:38.185  7157  7157 W art     : b6bfa000-b6c03000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-05 02:13:38.185  7157  7157 W art     : b6c03000-b6c04000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-05 02:13:38.185  7157  7157 W art     : b6c04000-b6c05000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-05 02:13:38.185  7157  7157 W art     : b6c05000-b6c25000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-05 02:13:38.185  7157  7157 W art     : b6c25000-b6c26000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-05 02:13:38.185  7157  7157 W art     : b6c26000-b6c27000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-05 02:13:38.185  7157  7157 W art     : b6c27000-b6c9a000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-05 02:13:38.185  7157  7157 W art     : b6c9a000-b6c9e000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-05 02:13:38.185  7157  7157 W art     : b6c9e000-b6ca1000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-05 02:13:38.185  7157  7157 W art     : b6ca1000-b6cab000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6cab000-b6d33000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-05 02:13:38.185  7157  7157 W art     : b6d33000-b6d34000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6d34000-b6d38000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-05 02:13:38.185  7157  7157 W art     : b6d38000-b6d39000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-05 02:13:38.185  7157  7157 W art     : b6d39000-b6d3a000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6d3a000-b6d63000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-05 02:13:38.185  7157  7157 W art     : b6d63000-b6d64000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6d64000-b6d67000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-05 02:13:38.185  7157  7157 W art     : b6d67000-b6d68000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-05 02:13:38.185  7157  7157 W art     : b6d68000-b6e42000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 02:13:38.185  7157  7157 W art     : b6e42000-b6e49000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 02:13:38.185  7157  7157 W art     : b6e49000-b6e51000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-05 02:13:38.185  7157  7157 W art     : b6e51000-b6e52000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6e52000-b6e53000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:38.185  7157  7157 W art     : b6e53000-b6e54000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-05 02:13:38.185  7157  7157 W art     : b6e54000-b6e55000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6e55000-b6e58000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6e58000-b6e7d000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-05 02:13:38.185  7157  7157 W art     : b6e7d000-b6e7e000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6e7e000-b6e85000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-05 02:13:38.185  7157  7157 W art     : b6e85000-b6e86000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-05 02:13:38.185  7157  7157 W art     : b6e86000-b6e8d000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-05 02:13:38.185  7157  7157 W art     : b6e8d000-b6e8e000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-05 02:13:38.185  7157  7157 W art     : b6e8e000-b6e8f000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-05 02:13:38.185  7157  7157 W art     : b6e8f000-b6e90000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6e90000-b6ea8000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-05 02:13:38.185  7157  7157 W art     : b6ea8000-b6ea9000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6ea9000-b6eaa000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-05 02:13:38.185  7157  7157 W art     : b6eaa000-b6eab000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-05 02:13:38.185  7157  7157 W art     : b6eab000-b6eb9000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-05 02:13:38.185  7157  7157 W art     : b6eb9000-b6eba000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6eba000-b6ebb000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-05 02:13:38.185  7157  7157 W art     : b6ebb000-b6ebc000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-05 02:13:38.185  7157  7157 W art     : b6ebc000-b6ebd000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:38.185  7157  7157 W art     : b6ebd000-b6ebf000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6ebf000-b6ec0000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6ec0000-b6ec1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-05 02:13:38.185  7157  7157 W art     : b6ec1000-b6ec2000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-05 02:13:38.185  7157  7157 W art     : b6ec2000-b6ec3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-05 02:13:38.185  7157  7157 W art     : b6ec3000-b6ee3000 r--s 00000000 00:0b 7179       /dev/__properties__
08-05 02:13:38.185  7157  7157 W art     : b6ee3000-b6ee4000 r--p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6ee4000-b6ee5000 ---p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6ee5000-b6ee7000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-05 02:13:38.185  7157  7157 W art     : b6ee7000-b6ee8000 r-xp 00000000 00:00 0          [sigpage]
08-05 02:13:38.185  7157  7157 W art     : b6ee8000-b6f03000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-05 02:13:38.185  7157  7157 W art     : b6f03000-b6f04000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-05 02:13:38.185  7157  7157 W art     : b6f04000-b6f06000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-05 02:13:38.185  7157  7157 W art     : b6f06000-b6f08000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : b6f08000-b6f0d000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-05 02:13:38.185  7157  7157 W art     : b6f0d000-b6f0e000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-05 02:13:38.185  7157  7157 W art     : b6f0e000-b6f0f000 rw-p 00000000 00:00 0 
08-05 02:13:38.185  7157  7157 W art     : be9e7000-bea08000 rw-p 00000000 00:00 0          [stack]
08-05 02:13:38.185  7157  7157 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-05 02:13:38.245  7157  7157 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-05 02:13:38.285  7157  7157 I Radio-JNI: register_android_hardware_Radio DONE
,08-05 02:13:38.295  7157  7157 E AffinityControl: AffinityControl: registerfunction enter
,08-05 02:13:38.315  7157  7157 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 02:13:38.325   765  2385 D PackageManager: START PACKAGE DELETE: observer{130903372}
08-05 02:13:38.325   765  2385 D PackageManager: pkg{<packageName>}
08-05 02:13:38.325   765  2385 D PackageManager: user{0}
08-05 02:13:38.325   765  2385 D PackageManager: caller{2000}
08-05 02:13:38.325   765  2385 D PackageManager: flags{2}
,08-05 02:13:38.325   765  2385 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 02:13:38.325   765  2385 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-05 02:13:38.325   765  2385 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-05 02:13:38.325   765  2385 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 02:13:38.325   765  2385 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-05 02:13:38.325   765   925 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-05 02:13:38.325   765   925 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-05 02:13:38.325   765   925 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-05 02:13:38.325   765   925 D ApplicationPolicy: getApplicationUninstallationEnabled
08-05 02:13:38.325   765   925 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 02:13:38.325   765   925 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-05 02:13:38.325   765   925 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-05 02:13:38.325   765   925 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-05 02:13:38.325   765   925 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-05 02:13:38.325   765   851 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-05 02:13:38.325   765   925 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-05 02:13:38.325   765   851 I ActivityManager: Killing 7061:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-05 02:13:38.345   765   851 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 02:13:38.345   765   851 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-05 02:13:38.345   765   851 D ActivityManager: mDVFSHelper.acquire()
,08-05 02:13:38.355   765   901 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-05 02:13:38.365  7166  7166 E Zygote  : v2
,08-05 02:13:38.365  7166  7166 I libpersona: KNOX_SDCARD checking this for 10004
08-05 02:13:38.365  7166  7166 I libpersona: KNOX_SDCARD not a persona
,08-05 02:13:38.365  7166  7166 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-05 02:13:38.365  7166  7166 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-05 02:13:38.365   765   851 I ActivityManager: Start proc 7166:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,08-05 02:13:38.365  7166  7166 E Zygote  : accessInfo : 0
08-05 02:13:38.365  7166  7166 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-05 02:13:38.365   765   901 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-05 02:13:38.365   765   901 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-05 02:13:38.365   765   901 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-05 02:13:38.365   765   901 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
08-05 02:13:38.365   765   901 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-05 02:13:38.365   765   901 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:38.365   765   901 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-05 02:13:38.365   765   901 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:38.365   765   901 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-05 02:13:38.375   765   851 I ActivityManager:   Force finishing activity ActivityRecord{fed2c8d u0 com.test.thalitest/.MainActivity t115}
,08-05 02:13:38.385   765  1717 D GraphicsStats: Buffer count: 4
08-05 02:13:38.385   765  2385 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a633f76)
,08-05 02:13:38.385   765  1717 I WindowState: WIN DEATH: Window{ead86fa u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:13:38.385   765  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 02:13:38.385   292   375 I SurfaceFlinger: id=17 Removed NainActivit (6/8)
08-05 02:13:38.385   765  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 02:13:38.385   765  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 02:13:38.385   292  1296 I SurfaceFlinger: id=17 Removed NainActivit (-2/8)
08-05 02:13:38.385   765  1717 D InputDispatcher: Focus left window: 7061
08-05 02:13:38.395   292  1296 I SurfaceFlinger: id=17 Removed NainActivit (-2/8)
08-05 02:13:38.395   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
08-05 02:13:38.405   765   925 D AASAinstall: there is not AASApackages.xml file
08-05 02:13:38.405  7166  7166 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 02:13:38.405  7166  7166 D ActivityThread: Added TimaKeyStore provider
,08-05 02:13:38.655   765  3410 D SSRM:n  : SIOP:: AP = 360, PST = 313, CUR = 450, LCD = 0
,08-05 02:13:38.695   765   925 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-05 02:13:38.715   765   925 W PackageSettings: Skipping PackageSetting{2ea098f com.example.hello/10192} due to missing metadata
,08-05 02:13:38.775   765   925 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-05 02:13:38.775   765   901 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{4dc2977 V.E...... R.....ID 0,0-0,0}
08-05 02:13:38.775   765   901 D SecWifiDisplayUtil: Metadata value : none
08-05 02:13:38.775   765   901 D ISSUE_DEBUG: InputChannelName : e68ae4d Starting com.test.thalitest
,08-05 02:13:38.785   320   320 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-05 02:13:38.785   765   925 I art     : Starting a blocking GC Explicit
,08-05 02:13:38.805   292   292 I SurfaceFlinger: id=18 createSurf (1146x1876),1 flag=4, VSBConnecti
,08-05 02:13:38.825  1718  1718 D Launcher: onRestart, Launcher: 62934087
,08-05 02:13:38.885   765   925 I art     : Explicit concurrent mark sweep GC freed 84736(4MB) AllocSpace objects, 19(380KB) LOS objects, 27% free, 41MB/57MB, paused 1.453ms total 104.041ms
,08-05 02:13:38.905   765   925 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-05 02:13:38.905   765   925 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-05 02:13:38.905   765   925 D AASAinstall: there is not AASApackages.xml file
08-05 02:13:38.905   765   925 D PackageManager: result of delete: 1{130903372}
,08-05 02:13:38.915  7157  7157 I art     : System.exit called, status: 0
08-05 02:13:38.915  7157  7157 I AndroidRuntime: VM exiting with result code 0.
,08-05 02:13:38.915   765   925 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 02:13:38.915   765   925 D PackageManager: userId{-1}
08-05 02:13:38.915   765   925 D PackageManager: andCode{true}
,08-05 02:13:39.015   765   839 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml -> /data/system/users/0/runtime-permissions.xml.bak
,08-05 02:13:39.015   765   839 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-05 02:13:39.115   765   851 I WindowManager: Screenshot max retries 4 of Token{a8c805b ActivityRecord{b7cd36a u0 com.samsung.android.MtpApplication/.USBConnection t114}} appWin=Window{1e08710 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=1
,08-05 02:13:39.125   765  1299 I EventHub: Removing device '/dev/input/event4' due to inotify event
,08-05 02:13:39.125   765  1731 I ActivityManager: Killing 6040:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-05 02:13:39.135   765   901 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
,08-05 02:13:39.135   765   851 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-05 02:13:39.135  1718  1718 D Launcher: onStart, Launcher: 62934087
,08-05 02:13:39.135   765   901 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-05 02:13:39.135   765   901 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
08-05 02:13:39.135   765   901 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 02:13:39.145   292   292 I SurfaceFlinger: id=19 createSurf (1080x1920),1 flag=404, uhalitest
,08-05 02:13:39.145  1718  1718 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,08-05 02:13:39.145   765   851 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9cc7e14c in tid 851 (ActivityManager)
,08-05 02:13:39.145  2304  2304 E audit_log: File locking failed. error= Bad file descriptor
,08-05 02:13:39.145  2304  2304 E audit_log: File locking failed. error= Bad file descriptor
,08-05 02:13:39.145  1718  1718 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-05 02:13:39.155  1718  1718 D Launcher.HomeView: onStart
,08-05 02:13:39.155  1718  1718 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f085056 in tid 1718 (id.app.launcher)
,08-05 02:13:39.155  1718  1718 F libc    : Unable to open connection to debuggerd: Connection refused
,08-05 02:13:39.155  2304  2304 E audit_log: File locking failed. error= Bad file descriptor
,08-05 02:13:39.255   340   340 I Zygote  : Process 1718 exited due to signal (7)
,08-05 02:13:39.265   318   318 E installd: eof
08-05 02:13:39.265   318   318 E installd: failed to read size
08-05 02:13:39.265   318   318 I installd: closing connection
,08-05 02:13:39.265   315  2100 W AudioFlinger: power manager service died !!!
08-05 02:13:39.265   315  2100 W AudioFlinger: power manager service died !!!
08-05 02:13:39.265  2825  2835 W Sensors : sensorservice died [0xad6b8b00]
,08-05 02:13:39.265   292  1296 D libEGL  : eglTerminate EGLDisplay = 0xb47bd6fc
08-05 02:13:39.265   292  1296 D libEGL  : eglTerminate EGLDisplay = 0xb47bd6fc
,08-05 02:13:39.265   292   292 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
08-05 02:13:39.265   292   292 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-05 02:13:39.275   292  1296 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-05 02:13:39.275  1967  1979 W Sensors : sensorservice died [0xb28aa940]
,08-05 02:13:39.275  1702  1702 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-05 02:13:39.275  1967  2264 E WifiManager: Channel connection lost
,08-05 02:13:39.275  2825  3158 E WifiManager: Channel connection lost
,08-05 02:13:39.285  1813  2015 E WifiManager: Channel connection lost
08-05 02:13:39.285  1383  1645 E WifiManager: Channel connection lost
,08-05 02:13:39.285  5586  5664 E WifiManager: Channel connection lost
,08-05 02:13:39.285   291   291 I ServiceManager: service 'telecom' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'user' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'procstats' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'meminfo' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'gfxinfo' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'dbinfo' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'cpuinfo' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'permission' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'processinfo' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'sensorservice' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'mdm.remotedesktop' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'notification' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'battery' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'usagestats' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'webviewupdate' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'devicestoragemonitor' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'scheduling_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'telephony.registry' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'persona' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'enterprise_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'statusbar' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'clipboard' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'clipboardEx' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'network_management' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'ABTPersistenceService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'textservices' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'network_score' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'netstats' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'netpolicy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'wifip2p' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'wifi' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'wifihs20' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'wifiscanner' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'rttmanager' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'ethernet' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'connectivity' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'sb_service' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'servicediscovery' died
08-05 02:13:39.285  2304  2304 E audit_log: File locking failed. error= Bad file descriptor
08-05 02:13:39.285   291   291 I ServiceManager: service 'updatelock' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'location' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'country_detector' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'sec_location' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'search' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'execute' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'dropbox' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'wallpaper' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'audio' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'DockObserver' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'midi' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'usb' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'serial' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'kiesusb' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'jobscheduler' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'backup' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'appwidget' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'voiceinteraction' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'SecExternalDisplayService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'diskstats' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'mDNIe' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'AAS' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'MSCS' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'spengestureservice' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'quickconnect' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'samplingprofiler' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'commontime_management' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'dreams' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'graphicsstats' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'print' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'restrictions' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'media_session' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'media_router' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'trust' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'fingerprint' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'launcherapps' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'voip' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'media_projection' died
08-05 02:13:39.285  2299  2299 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9edf130a in tid 2299 (droid.bluetooth),
08-05 02:13:39.285   291   291 I ServiceManager: service 'lpnet' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'sec_analytics' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'knox_ccm_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'enterprise_license_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'application_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'wifi_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'phone_restriction_policy' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'remoteinjection' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'knox_ucsm_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'edm_proxy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'mum_container_policy' died
08-05 02:13:39.285  1866  1882 W Sensors : sensorservice died [0xb3f1acc0]
08-05 02:13:39.285   291   291 I ServiceManager: service 'enterprise_billing_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'otp_service' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'enterprise_shared_device_policy' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'knox_timakeystore_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'edmnativehelper' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'SEAMService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'media.camera.proxy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'account' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'content' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'DirEncryptService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'LSManager' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'ReactiveService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'DeviceRootKeyService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'EngineeringModeService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'SatsService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'sedenial' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'vibrator' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'tw_toolbox' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'tima' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'iccc' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'cepproxyks' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'emailksproxy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'CustomFrequencyManagerService' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'consumer_ir' died
08-05 02:13:39.285  2299  2299 F libc    : Unable to open connection to debuggerd: Connection refused
,08-05 02:13:39.285   291   291 I ServiceManager: service 'alarm' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'context_aware' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'scontext' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'barbeam' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'multiwindow_facade' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'window' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'input' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'imms' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'bluetooth_manager' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'rcp' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'input_method' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'accessibility' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'persona_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'cover' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'mount' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'lock_settings' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'deviceidle' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'device_policy' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'harmony_eas_service' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'sdp' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'sdp_log' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'dlp' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'log_manager_service' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'uimode' died
,08-05 02:13:39.285   291   291 I ServiceManager: service 'batterystats' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'appops' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'power' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'display' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'package' died
08-05 02:13:39.285   291   291 I ServiceManager: service 'activity' died
08-05 02:13:39.285   292  1297 I SurfaceFlinger: id=2 Removed GocusedStac (6/9)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=9 Removed EimLayer(Di (2/6)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=10 Removed EimLayer(An (0/5)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
,08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=19 Removed uhalitest (2/4)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=19 Removed uhalitest (-2/4)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=5 Removed TtatusBar (2/3)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=5 Removed TtatusBar (-2/3),
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=6 Removed JmageWallpa (0/2)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/2)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=18 Removed VSBConnecti (0/1)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/1)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=13 Removed DolorFade (0/0)
,08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=13 Removed DolorFade (-2/0)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=9 Removed EimLayer(Di (-2/0)
08-05 02:13:39.295   292  1297 I SurfaceFlinger: id=10 Removed EimLayer(An (-2/0)
08-05 02:13:39.295  1702  2171 E WifiManager: Channel connection lost
,08-05 02:13:39.295  2358  2370 W Sensors : sensorservice died [0xb3a72a80]
,08-05 02:13:39.295  1383  3726 W Sensors : sensorservice died [0xad69ec80]
,08-05 02:13:39.305  7166  7166 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-05 02:13:39.305  7166  7166 W asset   : Asset path /data/app/com.test.thalitest-1/base.apk is neither a directory nor file (type=1).
,08-05 02:13:39.305  7166  7166 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-05 02:13:39.305  7166  7166 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-05 02:13:39.305  7166  7166 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-05 02:13:39.305  7166  7166 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-05 02:13:39.315  7166  7166 W System  : ClassLoader referenced unknown path: /data/app/com.test.thalitest-1/base.apk
,08-05 02:13:39.315  7166  7166 W System  : ClassLoader referenced unknown path: /data/app/com.test.thalitest-1/lib/arm
,08-05 02:13:39.315  7166  7166 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x732ffe68 in tid 7166 (.test.thalitest)
,08-05 02:13:39.315  7166  7166 F libc    : Unable to open connection to debuggerd: Connection refused
08-05 02:13:39.315  2304  2304 E audit_log: File locking failed. error= Bad file descriptor
,08-05 02:13:39.315  2345  2345 D BluetoothA2dp: Proxy object disconnected
,08-05 02:13:39.315  2825  2825 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 02:13:39.315  3487  3487 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8f35871 time:321287
08-05 02:13:39.315  2825  2825 D PanProfile: Bluetooth service disconnected
08-05 02:13:39.315  2825  2825 D BluetoothMap: Proxy object disconnected
08-05 02:13:39.315  2825  2825 D MapProfile: Bluetooth service disconnected
,08-05 02:13:39.315  2825  2825 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b9242bd in tid 2825 (ndroid.settings)
,08-05 02:13:39.315  2825  2825 F libc    : Unable to open connection to debuggerd: Connection refused
08-05 02:13:39.315  2304  2304 E audit_log: File locking failed. error= Bad file descriptor
,08-05 02:13:39.355   340   340 I Zygote  : Process 2825 exited due to signal (7)
,08-05 02:13:39.365   340   340 I Zygote  : Process 2299 exited due to signal (7)
08-05 02:13:39.365   340   340 I Zygote  : Process 7166 exited due to signal (7)
,08-05 02:13:39.455   290   290 I lowmemorykiller: ActivityManager disconnected
08-05 02:13:39.455   290   290 I lowmemorykiller: Closing Activity Manager data connection
,08-05 02:13:39.515   292   552 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-05 02:13:39.515   292   292 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-05 02:13:39.765   292   292 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-05 02:13:39.765   292   552 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-05 02:13:39.765   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
,08-05 02:13:39.765   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe89338c
,08-05 02:13:39.775   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe89338c
08-05 02:13:39.775   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe89338c
,08-05 02:13:39.775   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4
,08-05 02:13:39.775   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbe8933a4

```
