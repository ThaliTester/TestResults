#### Test 72145431fdae11f_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
06-30 10:38:14.080   779  1617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:14.090   779  1617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
06-30 10:38:14.090   779  1617 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
06-30 10:38:14.090   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 10:38:14.109   779   779 I MotionRecognitionService: Plugged
06-30 10:38:14.109   779   779 D MotionRecognitionService:   cableConnection= 1
06-30 10:38:14.109   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
06-30 10:38:14.109   779   779 D MotionRecognitionService: skip setTransmitPower. 
06-30 10:38:14.119   779  1617 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
06-30 10:38:14.119   779  1617 D BatteryService: stay LED for fully charged
--------- beginning of main
06-30 10:38:14.129  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:14.129  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:38:14.139  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 10:38:14.169  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:14.169  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:14.169  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:38:14.999  2031  2031 E audit   : type=1400 msg=audit(1467275894.989:275): avc:  denied  { execmod } for  pid=6456 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:38:14.999  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:14.999  2031  2031 E audit   : type=1300 msg=audit(1467275894.989:275): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fdb000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=6456 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:38:14.999  2031  2031 E audit   : type=1327 msg=audit(1467275894.989:275): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 10:38:14.999  2031  2031 E audit   : type=1320 msg=audit(1467275894.989:275): 
06-30 10:38:15.049  2031  2031 E audit   : type=1400 msg=audit(1467275895.049:276): avc:  denied  { execmod } for  pid=6456 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:38:15.049  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:15.059  2031  2031 E audit   : type=1300 msg=audit(1467275895.049:276): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f9b000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=6456 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:38:15.059  2031  2031 E audit   : type=1327 msg=audit(1467275895.049:276): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 10:38:15.059  2031  2031 E audit   : type=1320 msg=audit(1467275895.049:276): 
06-30 10:38:15.099  6456  6456 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:38:15.099  2031  2031 E audit   : type=1400 msg=audit(1467275895.099:277): avc:  denied  { execmod } for  pid=6456 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 10:38:15.099  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:15.099  2031  2031 E audit   : type=1300 msg=audit(1467275895.099:277): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f9b000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=6456 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 10:38:15.109  6456  6456 D AndroidRuntime: CheckJNI is OFF
06-30 10:38:15.109  2031  2031 E audit   : type=1327 msg=audit(1467275895.099:277): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
06-30 10:38:15.109  6456  6456 D AndroidRuntime: readGMSProperty: start
06-30 10:38:15.109  6456  6456 D AndroidRuntime: readGMSProperty: already setted!!
06-30 10:38:15.109  6456  6456 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 10:38:15.109  6456  6456 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 10:38:15.109  6456  6456 D AndroidRuntime: readGMSProperty: end
06-30 10:38:15.109  6456  6456 D AndroidRuntime: addProductProperty: start
06-30 10:38:15.109  2031  2031 E audit   : type=1320 msg=audit(1467275895.099:277): 
06-30 10:38:15.119  6456  6456 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 10:38:15.119  6456  6456 W art     : af14d000-b2073000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:38:15.119  6456  6456 W art     : b2073000-b42e2000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:38:15.119  6456  6456 W art     : b42e2000-b42e3000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 10:38:15.119  6456  6456 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
06-30 10:38:15.119  6456  6456 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
06-30 10:38:15.119  6456  6456 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
06-30 10:38:15.119  6456  6456 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 10:38:15.119  6456  6456 W art     : b4840000-b4869000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 10:38:15.119  6456  6456 W art     : b4869000-b486c000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
06-30 10:38:15.119  6456  6456 W art     : b486c000-b486d000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
06-30 10:38:15.119  6456  6456 W art     : b486d000-b486e000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
06-30 10:38:15.119  6456  6456 W art     : b486e000-b486f000 r--p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b486f000-b488f000 r--s 00000000 00:0b 7188       /dev/__properties__
06-30 10:38:15.119  6456  6456 W art     : b488f000-b52a0000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
06-30 10:38:15.119  6456  6456 W art     : b52a0000-b52a1000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b52a1000-b52ea000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
06-30 10:38:15.119  6456  6456 W art     : b52ea000-b52eb000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
06-30 10:38:15.119  6456  6456 W art     : b52eb000-b52f3000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b52f3000-b52f4000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b52f4000-b5329000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
06-30 10:38:15.119  6456  6456 W art     : b5329000-b532a000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b532a000-b532b000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
06-30 10:38:15.119  6456  6456 W art     : b532b000-b532c000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
06-30 10:38:15.119  6456  6456 W art     : b532c000-b5384000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
06-30 10:38:15.119  6456  6456 W art     : b5384000-b5385000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5385000-b5386000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
06-30 10:38:15.119  6456  6456 W art     : b5386000-b5387000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
06-30 10:38:15.119  6456  6456 W art     : b5388000-b538e000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:38:15.119  6456  6456 W art     : b538e000-b538f000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:38:15.119  6456  6456 W art     : b538f000-b5390000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 10:38:15.119  6456  6456 W art     : b5390000-b5392000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5393000-b539d000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 10:38:15.119  6456  6456 W art     : b539d000-b53a0000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 10:38:15.119  6456  6456 W art     : b53a0000-b53a1000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 10:38:15.119  6456  6456 W art     : b53a2000-b53b9000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 10:38:15.119  6456  6456 W art     : b53b9000-b53ba000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b53ba000-b53bb000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 10:38:15.119  6456  6456 W art     : b53bb000-b53bc000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 10:38:15.119  6456  6456 W art     : b53bd000-b53c7000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
06-30 10:38:15.119  6456  6456 W art     : b53c7000-b53c8000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
06-30 10:38:15.119  6456  6456 W art     : b53c8000-b53c9000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
06-30 10:38:15.119  6456  6456 W art     : b53c9000-b53cd000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 10:38:15.119  6456  6456 W art     : b53cd000-b53ce000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 10:38:15.119  6456  6456 W art     : b53ce000-b53cf000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 10:38:15.119  6456  6456 W art     : b53cf000-b53e5000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
06-30 10:38:15.119  6456  6456 W art     : b53e5000-b53e6000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
06-30 10:38:15.119  6456  6456 W art     : b53e6000-b53e7000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
06-30 10:38:15.119  6456  6456 W art     : b53e7000-b53f4000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
06-30 10:38:15.119  6456  6456 W art     : b53f4000-b53f5000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
06-30 10:38:15.119  6456  6456 W art     : b53f5000-b53f6000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
06-30 10:38:15.119  6456  6456 W art     : b53f6000-b5456000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
06-30 10:38:15.119  6456  6456 W art     : b5456000-b5459000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
06-30 10:38:15.119  6456  6456 W art     : b5459000-b545d000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b545d000-b54be000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
06-30 10:38:15.119  6456  6456 W art     : b54be000-b54bf000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
06-30 10:38:15.119  6456  6456 W art     : b54bf000-b550e000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
06-30 10:38:15.119  6456  6456 W art     : b550e000-b5510000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
06-30 10:38:15.119  6456  6456 W art     : b5510000-b5511000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
06-30 10:38:15.119  6456  6456 W art     : b5511000-b5512000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5512000-b5519000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 10:38:15.119  6456  6456 W art     : b5519000-b551a000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 10:38:15.119  6456  6456 W art     : b551a000-b551b000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 10:38:15.119  6456  6456 W art     : b551c000-b551f000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 10:38:15.119  6456  6456 W art     : b551f000-b5520000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 10:38:15.119  6456  6456 W art     : b5520000-b5521000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 10:38:15.119  6456  6456 W art     : b5522000-b5526000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
06-30 10:38:15.119  6456  6456 W art     : b5526000-b5527000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5527000-b5528000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
06-30 10:38:15.119  6456  6456 W art     : b5528000-b5529000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
06-30 10:38:15.119  6456  6456 W art     : b552a000-b5547000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 10:38:15.119  6456  6456 W art     : b5547000-b5548000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 10:38:15.119  6456  6456 W art     : b5548000-b5549000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 10:38:15.119  6456  6456 W art     : b554a000-b554f000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 10:38:15.119  6456  6456 W art     : b554f000-b5550000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 10:38:15.119  6456  6456 W art     : b5550000-b5551000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 10:38:15.119  6456  6456 W art     : b5552000-b5583000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 10:38:15.119  6456  6456 W art     : b5583000-b5586000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 10:38:15.119  6456  6456 W art     : b5586000-b5587000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 10:38:15.119  6456  6456 W art     : b5588000-b55c3000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
06-30 10:38:15.119  6456  6456 W art     : b55c3000-b55c4000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
06-30 10:38:15.119  6456  6456 W art     : b55c4000-b55c5000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
06-30 10:38:15.119  6456  6456 W art     : b55c6000-b55cd000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
06-30 10:38:15.119  6456  6456 W art     : b55cd000-b55ce000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b55ce000-b55cf000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
06-30 10:38:15.119  6456  6456 W art     : b55cf000-b55d0000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
06-30 10:38:15.119  6456  6456 W art     : b55d0000-b55d1000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b55d1000-b55e8000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
06-30 10:38:15.119  6456  6456 W art     : b55e8000-b55e9000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b55e9000-b55ec000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
06-30 10:38:15.119  6456  6456 W art     : b55ec000-b55ed000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
06-30 10:38:15.119  6456  6456 W art     : b55ed000-b560c000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
06-30 10:38:15.119  6456  6456 W art     : b560c000-b560d000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
06-30 10:38:15.119  6456  6456 W art     : b560d000-b560e000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
06-30 10:38:15.119  6456  6456 W art     : b560e000-b564c000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 10:38:15.119  6456  6456 W art     : b564c000-b564d000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b564d000-b564f000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 10:38:15.119  6456  6456 W art     : b564f000-b5650000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 10:38:15.119  6456  6456 W art     : b5651000-b5658000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 10:38:15.119  6456  6456 W art     : b5658000-b5659000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 10:38:15.119  6456  6456 W art     : b5659000-b565a000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 10:38:15.119  6456  6456 W art     : b565b000-b565e000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 10:38:15.119  6456  6456 W art     : b565e000-b565f000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 10:38:15.119  6456  6456 W art     : b565f000-b5660000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 10:38:15.119  6456  6456 W art     : b5660000-b5666000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:38:15.119  6456  6456 W art     : b5666000-b5667000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5667000-b5668000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:38:15.119  6456  6456 W art     : b5668000-b5669000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 10:38:15.119  6456  6456 W art     : b5669000-b5672000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
06-30 10:38:15.119  6456  6456 W art     : b5672000-b5673000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
06-30 10:38:15.119  6456  6456 W art     : b5673000-b5674000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
06-30 10:38:15.119  6456  6456 W art     : b5674000-b5705000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 10:38:15.119  6456  6456 W art     : b5705000-b5706000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5706000-b5711000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 10:38:15.119  6456  6456 W art     : b5711000-b5712000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 10:38:15.119  6456  6456 W art     : b5713000-b5725000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
06-30 10:38:15.119  6456  6456 W art     : b5725000-b5726000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
06-30 10:38:15.119  6456  6456 W art     : b5726000-b5727000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
06-30 10:38:15.119  6456  6456 W art     : b5728000-b572d000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
06-30 10:38:15.119  6456  6456 W art     : b572d000-b572e000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
06-30 10:38:15.119  6456  6456 W art     : b572e000-b572f000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
06-30 10:38:15.119  6456  6456 W art     : b5730000-b579d000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
06-30 10:38:15.119  6456  6456 W art     : b579d000-b579e000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b579e000-b57a0000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
06-30 10:38:15.119  6456  6456 W art     : b57a0000-b57a1000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
06-30 10:38:15.119  6456  6456 W art     : b57a1000-b57a2000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b57a2000-b57a9000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:38:15.119  6456  6456 W art     : b57a9000-b57aa000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:38:15.119  6456  6456 W art     : b57aa000-b57ab000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 10:38:15.119  6456  6456 W art     : b57ac000-b582c000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 10:38:15.119  6456  6456 W art     : b582c000-b582d000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b582d000-b582e000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 10:38:15.119  6456  6456 W art     : b582e000-b582f000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 10:38:15.119  6456  6456 W art     : b582f000-b5846000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5846000-b587d000 r-xp 00000000 b3:17 3244       /system/vendor/l
06-30 10:38:15.119  6456  6456 W art     : ib/libqc-opt.so
06-30 10:38:15.119  6456  6456 W art     : b587d000-b587e000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 10:38:15.119  6456  6456 W art     : b587e000-b587f000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 10:38:15.119  6456  6456 W art     : b587f000-b589b000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 10:38:15.119  6456  6456 W art     : b589b000-b589c000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 10:38:15.119  6456  6456 W art     : b589c000-b589d000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 10:38:15.119  6456  6456 W art     : b589e000-b58ff000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 10:38:15.119  6456  6456 W art     : b58ff000-b5901000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 10:38:15.119  6456  6456 W art     : b5901000-b5902000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 10:38:15.119  6456  6456 W art     : b5903000-b592a000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
06-30 10:38:15.119  6456  6456 W art     : b592a000-b592b000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b592b000-b592c000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
06-30 10:38:15.119  6456  6456 W art     : b592c000-b592d000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
06-30 10:38:15.119  6456  6456 W art     : b592e000-b5936000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 10:38:15.119  6456  6456 W art     : b5936000-b5938000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 10:38:15.119  6456  6456 W art     : b5938000-b5939000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 10:38:15.119  6456  6456 W art     : b593a000-b593d000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
06-30 10:38:15.119  6456  6456 W art     : b593d000-b593e000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
06-30 10:38:15.119  6456  6456 W art     : b593e000-b593f000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
06-30 10:38:15.119  6456  6456 W art     : b593f000-b5943000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
06-30 10:38:15.119  6456  6456 W art     : b5943000-b5944000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5944000-b5945000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
06-30 10:38:15.119  6456  6456 W art     : b5945000-b5946000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
06-30 10:38:15.119  6456  6456 W art     : b5946000-b5956000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
06-30 10:38:15.119  6456  6456 W art     : b5956000-b5957000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
06-30 10:38:15.119  6456  6456 W art     : b5957000-b5958000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
06-30 10:38:15.119  6456  6456 W art     : b5958000-b599e000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b599e000-b59a7000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
06-30 10:38:15.119  6456  6456 W art     : b59a7000-b59a8000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
06-30 10:38:15.119  6456  6456 W art     : b59a8000-b59a9000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
06-30 10:38:15.119  6456  6456 W art     : b59aa000-b59af000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
06-30 10:38:15.119  6456  6456 W art     : b59af000-b59b0000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
06-30 10:38:15.119  6456  6456 W art     : b59b0000-b59b1000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
06-30 10:38:15.119  6456  6456 W art     : b59b1000-b59b4000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 10:38:15.119  6456  6456 W art     : b59b4000-b59b5000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b59b5000-b59b6000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 10:38:15.119  6456  6456 W art     : b59b6000-b59b7000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 10:38:15.119  6456  6456 W art     : b59b8000-b59d0000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:38:15.119  6456  6456 W art     : b59d0000-b59d1000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b59d1000-b59d2000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:38:15.119  6456  6456 W art     : b59d2000-b59d3000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 10:38:15.119  6456  6456 W art     : b59d3000-b59d4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:38:15.119  6456  6456 W art     : b59d4000-b5b6e000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
06-30 10:38:15.119  6456  6456 W art     : b5b6e000-b5b6f000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5b6f000-b5b7c000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
06-30 10:38:15.119  6456  6456 W art     : b5b7c000-b5b7d000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
06-30 10:38:15.119  6456  6456 W art     : b5b7d000-b5b81000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
06-30 10:38:15.119  6456  6456 W art     : b5b81000-b5b82000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5b82000-b5b83000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
06-30 10:38:15.119  6456  6456 W art     : b5b83000-b5b84000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
06-30 10:38:15.119  6456  6456 W art     : b5b84000-b5b97000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
06-30 10:38:15.119  6456  6456 W art     : b5b97000-b5b98000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
06-30 10:38:15.119  6456  6456 W art     : b5b98000-b5b99000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
06-30 10:38:15.119  6456  6456 W art     : b5b9a000-b5be5000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
06-30 10:38:15.119  6456  6456 W art     : b5be5000-b5be6000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
06-30 10:38:15.119  6456  6456 W art     : b5be6000-b5be7000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
06-30 10:38:15.119  6456  6456 W art     : b5be7000-b5be9000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5bea000-b5bfb000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 10:38:15.119  6456  6456 W art     : b5bfb000-b5bfc000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5bfc000-b5bfd000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 10:38:15.119  6456  6456 W art     : b5bfd000-b5bfe000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 10:38:15.119  6456  6456 W art     : b5bfe000-b5bff000 r--p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5bff000-b5c09000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
06-30 10:38:15.119  6456  6456 W art     : b5c09000-b5c0b000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
06-30 10:38:15.119  6456  6456 W art     : b5c0b000-b5c0c000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
06-30 10:38:15.119  6456  6456 W art     : b5c0c000-b5c25000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
06-30 10:38:15.119  6456  6456 W art     : b5c25000-b5c26000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
06-30 10:38:15.119  6456  6456 W art     : b5c26000-b5c29000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
06-30 10:38:15.119  6456  6456 W art     : b5c29000-b5c2d000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5c2d000-b5ca1000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
06-30 10:38:15.119  6456  6456 W art     : b5ca1000-b5ca2000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5ca2000-b5ca5000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
06-30 10:38:15.119  6456  6456 W art     : b5ca5000-b5ca6000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
06-30 10:38:15.119  6456  6456 W art     : b5ca6000-b5ca7000 r--p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5ca7000-b5caa000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
06-30 10:38:15.119  6456  6456 W art     : b5caa000-b5cab000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
06-30 10:38:15.119  6456  6456 W art     : b5cab000-b5cac000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
06-30 10:38:15.119  6456  6456 W art     : b5cac000-b5cad000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b5cad000-b5cb2000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 10:38:15.119  6456  6456 W art     : b5cb2000-b5cb3000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 10:38:15.119  6456  6456 W art     : b5cb3000-b5cb4000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 10:38:15.119  6456  6456 W art     : b5cb4000-b5cb5000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b5cb5000-b5cb8000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 10:38:15.119  6456  6456 W art     : b5cb8000-b5cb9000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 10:38:15.119  6456  6456 W art     : b5cb9000-b5cba000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 10:38:15.119  6456  6456 W art     : b5cba000-b5cbb000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b5cbb000-b5cbf000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
06-30 10:38:15.119  6456  6456 W art     : b5cbf000-b5cc0000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
06-30 10:38:15.119  6456  6456 W art     : b5cc0000-b5cc1000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
06-30 10:38:15.119  6456  6456 W art     : b5cc1000-b5cc2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:38:15.119  6456  6456 W art     : b5cc2000-b5cc6000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 10:38:15.119  6456  6456 W art     : b5cc6000-b5cc7000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 10:38:15.119  6456  6456 W art     : b5cc7000-b5cc8000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 10:38:15.119  6456  6456 W art     : b5cc8000-b5cc9000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b5cc9000-b5cd7000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 10:38:15.119  6456  6456 W art     : b5cd7000-b5cd8000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b5cd8000-b5cd9000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 10:38:15.119  6456  6456 W art     : b5cd9000-b5cda000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 10:38:15.119  6456  6456 W art     : b5cda000-b5ce4000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 10:38:15.119  6456  6456 W art     : b5ce4000-b5ce7000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 10:38:15.119  6456  6456 W art     : b5ce7000-b5ce8000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 10:38:15.119  6456  6456 W art     : b5ce8000-b5ce9000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b5ce9000-b5cf3000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
06-30 10:38:15.119  6456  6456 W art     : b5cf3000-b5cf6000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
06-30 10:38:15.119  6456  6456 W art     : b5cf6000-b5cf7000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
06-30 10:38:15.119  6456  6456 W art     : b5cf7000-b5cfb000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
06-30 10:38:15.119  6456  6456 W art     : b5cfb000-b5cfc000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
06-30 10:38:15.119  6456  6456 W art     : b5cfc000-b5cfd000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
06-30 10:38:15.119  6456  6456 W art     : b5cfd000-b5cfe000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b5cfe000-b5d0b000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:38:15.119  6456  6456 W art     : b5d0b000-b5d0d000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:38:15.119  6456  6456 W art     : b5d0d000-b5d0e000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 10:38:15.119  6456  6456 W art     : b5d0e000-b6120000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
06-30 10:38:15.119  6456  6456 W art     : b6120000-b6121000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6121000-b612a000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
06-30 10:38:15.119  6456  6456 W art     : b612a000-b612e000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
06-30 10:38:15.119  6456  6456 W art     : b612e000-b612f000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b612f000-b6136000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:38:15.119  6456  6456 W art     : b6136000-b6137000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:38:15.119  6456  6456 W art     : b6137000-b6138000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 10:38:15.119  6456  6456 W art     : b6138000-b6139000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b6139000-b6154000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
06-30 10:38:15.119  6456  6456 W art     : b6154000-b6155000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 10:38:15.119  6456  6456 W art     : b6155000-b6156000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 10:38:15.119  6456  6456 W art     : b6156000-b6157000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b6157000-b61a3000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 10:38:15.119  6456  6456 W art     : b61a3000-b61a4000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b61a4000-b61a5000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 10:38:15.119  6456  6456 W art     : b61a5000-b61a6000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 10:38:15.119  6456  6456 W art     : b61a6000-b61a7000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b61a7000-b61ab000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
06-30 10:38:15.119  6456  6456 W art     : b61ab000-b61ac000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b61ac000-b61ad000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
06-30 10:38:15.119  6456  6456 W art     : b61ad000-b61ae000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
06-30 10:38:15.119  6456  6456 W art     : b61ae000-b61e6000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
06-30 10:38:15.119  6456  6456 W art     : b61e6000-b61e7000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
06-30 10:38:15.119  6456  6456 W art     : b61e7000-b61e8000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
06-30 10:38:15.119  6456  6456 W art     : b61e8000-b61e9000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.119  6456  6456 W art     : b61e9000-b6287000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
06-30 10:38:15.119  6456  6456 W art     : b6287000-b6288000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6288000-b62a6000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
06-30 10:38:15.119  6456  6456 W art     : b62a6000-b62a7000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
06-30 10:38:15.119  6456  6456 W art     : b62a7000-b641a000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
06-30 10:38:15.119  6456  6456 W art     : b641a000-b6425000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
06-30 10:38:15.119  6456  6456 W art     : b6425000-b6426000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
06-30 10:38:15.119  6456  6456 W art     : b6426000-b653d000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:38:15.119  6456  6456 W art     : b653d000-b6548000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:38:15.119  6456  6456 W art     : b6548000-b6549000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 10:38:15.119  6456  6456 W art     : b6549000-b654d000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b654d000-b6571000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
06-30 10:38:15.119  6456  6456 W art     : b6571000-b6573000 r--p 00023000 b3:17 400        /system/lib/libssl.so
06-30 10:38:15.119  6456  6456 W art     : b6573000-b6574000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
06-30 10:38:15.119  6456  6456 W art     : b6574000-b661a000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
06-30 10:38:15.119  6456  6456 W art     : b661a000-b6627000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
06-30 10:38:15.119  6456  6456 W art     : b6627000-b6628000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
06-30 10:38:15.119  6456  6456 W art     : b6628000-b6629000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6629000-b667c000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
06-30 10:38:15.119  6456  6456 W art     : b667c000-b667d000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b667d000-b667e000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
06-30 10:38:15.119  6456  6456 W art     : b667e000-b667f000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
06-30 10:38:15.119  6456  6456 W art     : b667f000-b6684000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6684000-b6696000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
06-30 10:38:15.119  6456  6456 W art     : b6696000-b6697000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6697000-b6698000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
06-30 10:38:15.119  6456  6456 W art     : b6698000-b6699000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
06-30 10:38:15.119  6456  6456 W art     : b6699000-b66a0000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 10:38:15.119  6456  6456 W art     : b66a0000-b66a1000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 10:38:15.119  6456  6456 W art     : b66a1000-b66a2000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 10:38:15.119  6456  6456 W art     : b66a2000-b66a3000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b66a3000-b66a6000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
06-30 10:38:15.119  6456  6456 W art     : b66a6000-b66a7000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
06-30 10:38:15.119  6456  6456 W art     : b66a7000-b66a8000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
06-30 10:38:15.119  6456  6456 W art     : b66a8000-b66ac000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
06-30 10:38:15.119  6456  6456 W art     : b66ac000-b66ad000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
06-30 10:38:15.119  6456  6456 W art     : b66ad000-b66ae000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
06-30 10:38:15.119  6456  6456 W art     : b66ae000-b66bc000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
06-30 10:38:15.119  6456  6456 W art     : b66bc000-b66bd000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b66bd000-b66be000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
06-30 10:38:15.119  6456  6456 W art     : b66be000-b66bf000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
06-30 10:38:15.119  6456  6456 W art     : b66bf000-b66c8000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 10:38:15.119  6456  6456 W art     : b66c8000-b66c9000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 10:38:15.119  6456  6456 W art     : b66c9000-b66ca000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 10:38:15.119  6456  6456 W art     : b66ca000-b6730000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
06-30 10:38:15.119  6456  6456 W art     : b6730000-b6731000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6731000-b6733000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
06-30 10:38:15.119  6456  6456 W art     : b6733000-b673c000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
06-30 10:38:15.119  6456  6456 W art     : b673c000-b673f000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b673f000-b67d6000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 10:38:15.119  6456  6456 W art     : b67d6000-b67d8000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 10:38:15.119  6456  6456 W art     : b67d8000-b67d9000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 10:38:15.119  6456  6456 W art     : b67d9000-b67da000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b67da000-b6afb000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
06-30 10:38:15.119  6456  6456 W art     : b6afb000-b6afc000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6afc000-b6b17000 r--p 00321000 b3:17 377        /system/lib/libskia.so
06-30 10:38:15.119  6456  6456 W art     : b6b17000-b6b1b000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
06-30 10:38:15.119  6456  6456 W art     : b6b1b000-b6b20000 rw-p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6b20000-b6b28000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 10:38:15.119  6456  6456 W art     : b6b28000-b6b29000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 10:38:15.119  6456  6456 W art     : b6b29000-b6b2a000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 10:38:15.119  6456  6456 W art     : b6b2a000-b6b58000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:38:15.119  6456  6456 W art     : b6b58000-b6b59000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6b59000-b6b60000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:38:15.119  6456  6456 W art     : b6b60000-b6b61000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 10:38:15.119  6456  6456 W art     : b6b61000-b6ba7000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:38:15.119  6456  6456 W art     : b6ba7000-b6ba8000 ---p 00000000 00:00 0 
06-30 10:38:15.119  6456  6456 W art     : b6ba8000-b6bab000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:38:15.119  6456  6456 W art     : b6bab000-b6bac000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 10:38:15.129  6456  6456 W art     : b6bac000-b6bc7000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
06-30 10:38:15.129  6456  6456 W art     : b6bc7000-b6bcb000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
06-30 10:38:15.129  6456  6456 W art     : b6bcb000-b6bcc000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
06-30 10:38:15.129  6456  6456 W art     : b6bcc000-b6c19000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
06-30 10:38:15.129  6456  6456 W art     : b6c19000-b6c1a000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6c1a000-b6c26000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
06-30 10:38:15.129  6456  6456 W art     : b6c26000-b6c27000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
06-30 10:38:15.129  6456  6456 W art     : b6c27000-b6c34000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
06-30 10:38:15.129  6456  6456 W art     : b6c34000-b6c35000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6c35000-b6c36000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
06-30 10:38:15.129  6456  6456 W art     : b6c36000-b6c37000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
06-30 10:38:15.129  6456  6456 W art     : b6c37000-b6c3f000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
06-30 10:38:15.129  6456  6456 W art     : b6c3f000-b6c40000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6c40000-b6c41000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
06-30 10:38:15.129  6456  6456 W art     : b6c41000-b6c42000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
06-30 10:38:15.129  6456  6456 W art     : b6c42000-b6c49000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:38:15.129  6456  6456 W art     : b6c49000-b6c4a000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:38:15.129  6456  6456 W art     : b6c4a000-b6c4b000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 10:38:15.129  6456  6456 W art     : b6c4b000-b6c5f000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
06-30 10:38:15.129  6456  6456 W art     : b6c5f000-b6c61000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
06-30 10:38:15.129  6456  6456 W art     : b6c61000-b6c62000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
06-30 10:38:15.129  6456  6456 W art     : b6c62000-b6c8a000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
06-30 10:38:15.129  6456  6456 W art     : b6c8a000-b6c8c000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
06-30 10:38:15.129  6456  6456 W art     : b6c8c000-b6c8d000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
06-30 10:38:15.129  6456  6456 W art     : b6c8d000-b6c90000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
06-30 10:38:15.129  6456  6456 W art     : b6c90000-b6c91000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
06-30 10:38:15.129  6456  6456 W art     : b6c91000-b6c92000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
06-30 10:38:15.129  6456  6456 W art     : b6c92000-b6c9b000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:38:15.129  6456  6456 W art     : b6c9b000-b6c9c000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:38:15.129  6456  6456 W art     : b6c9c000-b6c9d000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 10:38:15.129  6456  6456 W art     : b6c9d000-b6cbd000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 10:38:15.129  6456  6456 W art     : b6cbd000-b6cbe000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 10:38:15.129  6456  6456 W art     : b6cbe000-b6cbf000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 10:38:15.129  6456  6456 W art     : b6cbf000-b6d32000 r-xp 00000000 b3:17 860        /system/lib/libc.so
06-30 10:38:15.129  6456  6456 W art     : b6d32000-b6d36000 r--p 00072000 b3:17 860        /system/lib/libc.so
06-30 10:38:15.129  6456  6456 W art     : b6d36000-b6d39000 rw-p 00076000 b3:17 860        /system/lib/libc.so
06-30 10:38:15.129  6456  6456 W art     : b6d39000-b6d43000 rw-p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6d43000-b6dcb000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 10:38:15.129  6456  6456 W art     : b6dcb000-b6dcc000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6dcc000-b6dd0000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 10:38:15.129  6456  6456 W art     : b6dd0000-b6dd1000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 10:38:15.129  6456  6456 W art     : b6dd1000-b6dd2000 rw-p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6dd2000-b6dfb000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:38:15.129  6456  6456 W art     : b6dfb000-b6dfc000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6dfc000-b6dff000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:38:15.129  6456  6456 W art     : b6dff000-b6e00000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 10:38:15.129  6456  6456 W art     : b6e00000-b6eda000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 10:38:15.129  6456  6456 W art     : b6eda000-b6ee1000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 10:38:15.129  6456  6456 W art     : b6ee1000-b6ee9000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 10:38:15.129  6456  6456 W art     : b6ee9000-b6eea000 rw-p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6eea000-b6eeb000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:38:15.129  6456  6456 W art     : b6eeb000-b6eec000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 10:38:15.129  6456  6456 W art     : b6eec000-b6eed000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.129  6456  6456 W art     : b6eed000-b6ef0000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.129  6456  6456 W art     : b6ef0000-b6f15000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
06-30 10:38:15.129  6456  6456 W art     : b6f15000-b6f16000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6f16000-b6f1d000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
06-30 10:38:15.129  6456  6456 W art     : b6f1d000-b6f1e000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
06-30 10:38:15.129  6456  6456 W art     : b6f1e000-b6f25000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 10:38:15.129  6456  6456 W art     : b6f25000-b6f26000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 10:38:15.129  6456  6456 W art     : b6f26000-b6f27000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 10:38:15.129  6456  6456 W art     : b6f27000-b6f28000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.129  6456  6456 W art     : b6f28000-b6f40000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
06-30 10:38:15.129  6456  6456 W art     : b6f40000-b6f41000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6f41000-b6f42000 r--p 00018000 b3:17 918        /system/lib/libutils.so
06-30 10:38:15.129  6456  6456 W art     : b6f42000-b6f43000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
06-30 10:38:15.129  6456  6456 W art     : b6f43000-b6f51000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
06-30 10:38:15.129  6456  6456 W art     : b6f51000-b6f52000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6f52000-b6f53000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
06-30 10:38:15.129  6456  6456 W art     : b6f53000-b6f54000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
06-30 10:38:15.129  6456  6456 W art     : b6f54000-b6f55000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:38:15.129  6456  6456 W art     : b6f55000-b6f57000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.129  6456  6456 W art     : b6f57000-b6f58000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.129  6456  6456 W art     : b6f58000-b6f59000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 10:38:15.129  6456  6456 W art     : b6f59000-b6f5a000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 10:38:15.129  6456  6456 W art     : b6f5a000-b6f5b000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 10:38:15.129  6456  6456 W art     : b6f5b000-b6f7b000 r--s 00000000 00:0b 7188       /dev/__properties__
06-30 10:38:15.129  6456  6456 W art     : b6f7b000-b6f7c000 r--p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6f7c000-b6f7d000 ---p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6f7d000-b6f7f000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 10:38:15.129  6456  6456 W art     : b6f7f000-b6f80000 r-xp 00000000 00:00 0          [sigpage]
06-30 10:38:15.129  6456  6456 W art     : b6f80000-b6f9b000 r-xp 00000000 b3:17 2770       /system/bin/linker
06-30 10:38:15.129  6456  6456 W art     : b6f9b000-b6f9c000 r--p 0001a000 b3:17 2770       /system/bin/linker
06-30 10:38:15.129  6456  6456 W art     : b6f9c000-b6f9e000 rw-p 0001b000 b3:17 2770       /system/bin/linker
06-30 10:38:15.129  6456  6456 W art     : b6f9e000-b6fa0000 rw-p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : b6fa0000-b6fa5000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 10:38:15.129  6456  6456 W art     : b6fa5000-b6fa6000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 10:38:15.129  6456  6456 W art     : b6fa6000-b6fa7000 rw-p 00000000 00:00 0 
06-30 10:38:15.129  6456  6456 W art     : bedc7000-bede8000 rw-p 00000000 00:00 0          [stack]
06-30 10:38:15.129  6456  6456 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 10:38:15.189  6456  6456 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:38:15.239  6456  6456 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:38:15.249  6456  6456 E AffinityControl: AffinityControl: registerfunction enter
06-30 10:38:15.269  6456  6456 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:38:15.279   779  2252 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
06-30 10:38:15.289   779  2252 D ActivityManager: mDVFSHelper.acquire()
06-30 10:38:15.289   779  2252 V WindowManager: addAppToken: AppWindowToken{98cd6e7 token=Token{93d7ca6 ActivityRecord{b1c3601 u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
06-30 10:38:15.299   779   932 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5e3bbdf V.E...... R.....ID 0,0-0,0}
06-30 10:38:15.299   779   932 D SecWifiDisplayUtil: Metadata value : none
06-30 10:38:15.299   779   932 D ISSUE_DEBUG: InputChannelName : e664af5 Starting com.test.thalitest
06-30 10:38:15.309   779  2252 I ActivityManager: Start proc 6471:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 10:38:15.309  6471  6471 E Zygote  : v2
06-30 10:38:15.309  6471  6471 I libpersona: KNOX_SDCARD checking this for 10004
06-30 10:38:15.309  6471  6471 I libpersona: KNOX_SDCARD not a persona
06-30 10:38:15.309   779  2252 D InputDispatcher: Focused application set to: xxxx
06-30 10:38:15.309  6471  6471 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:38:15.309  6471  6471 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:15.309   779  2252 D InputDispatcher: Focus left window: 3395
06-30 10:38:15.319   779  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
06-30 10:38:15.319   779   888 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9d5ebfe u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
06-30 10:38:15.319  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
06-30 10:38:15.319  6471  6471 E Zygote  : accessInfo : 0
06-30 10:38:15.319  6471  6471 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 10:38:15.319  6456  6456 D AndroidRuntime: Shutting down VM
06-30 10:38:15.319   295   295 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
06-30 10:38:15.339   779   932 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
06-30 10:38:15.339   779   932 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:15.339   779   932 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
06-30 10:38:15.339   779   932 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 10:38:15.339   779   932 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 10:38:15.349  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:38:15.349  6471  6471 D ActivityThread: Added TimaKeyStore provider
06-30 10:38:15.349   779  1693 V WindowOrientationListener: setCurrentAppOrientation :-1
06-30 10:38:15.349   779  1693 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 10:38:15.349   779   888 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{e664af5 u0 d0 Starting com.test.thalitest}
06-30 10:38:15.349  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
06-30 10:38:15.359   779  1693 D ActivityManager:  Launching com.test.thalitest, updated priority
06-30 10:38:15.369   779   886 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
06-30 10:38:15.379  1695  1855 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
06-30 10:38:15.379  1695  1695 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
06-30 10:38:15.389   295  1294 D libEGL  : eglTerminate EGLDisplay = 0xb46ff64c
06-30 10:38:15.389   295   329 I SurfaceFlinger: id=13 Removed VSBConnecti (7/11)
06-30 10:38:15.399   295  1294 I SurfaceFlinger: id=13 Removed VSBConnecti (-2/11)
06-30 10:38:15.399   779   932 V WindowStateAnimator: Finishing drawing window Window{e664af5 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
06-30 10:38:15.399  3395  3395 V ActivityThread: updateVisibility : ActivityRecord{cf92765 token=android.os.BinderProxy@34633d7 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
06-30 10:38:15.399   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbea403a4
06-30 10:38:15.399   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbea40364
06-30 10:38:15.409   295  1295 D libEGL  : eglTerminate EGLDisplay = 0xb1eec64c
06-30 10:38:15.409   295  1295 D libEGL  : eglTerminate EGLDisplay = 0xb1eec64c
06-30 10:38:15.409   295   342 I SurfaceFlinger: id=7 Removed Mauncher (4/10)
06-30 10:38:15.409   295  1295 I SurfaceFlinger: id=7 Removed Mauncher (-2/10)
06-30 10:38:15.409  2398  2413 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
06-30 10:38:15.419  1695  1695 V ActivityThread: updateVisibility : ActivityRecord{15169f4 token=android.os.BinderProxy@93f9e11 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 10:38:15.419  1695  1695 D Launcher: onTrimMemory. Level: 20
06-30 10:38:15.419   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbea403a4
06-30 10:38:15.429   295   329 I SurfaceFlinger: id=14 Removed VSBConnecti (4/9)
06-30 10:38:15.429   295  1295 I SurfaceFlinger: id=14 Removed VSBConnecti (-2/9)
06-30 10:38:15.439   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbea403a4
06-30 10:38:15.509   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,06-30 10:38:15.679   779  1693 I WindowManager: Screenshot max retries 4 of Token{93d7ca6 ActivityRecord{b1c3601 u0 com.test.thalitest/.MainActivity t64}} appWin=Window{e664af5 u0 d0 Starting com.test.thalitest} drawState=4
06-30 10:38:15.679   779  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
06-30 10:38:15.689  6471  6471 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 10:38:15.689   779  3333 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
06-30 10:38:15.709  6471  6471 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 10:38:15.709  6471  6471 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 10:38:15.729  6471  6471 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
06-30 10:38:15.759  6471  6471 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
06-30 10:38:15.759  6471  6471 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 10:38:15.769  6471  6471 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 6525-6528)
06-30 10:38:15.769  6471  6471 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 10:38:15.799  6471  6471 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f312961}
06-30 10:38:15.799  6471  6471 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
06-30 10:38:15.799  6471  6471 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:38:15.799  6471  6500 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
06-30 10:38:15.809  6471  6471 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 10:38:15.829  6471  6501 W chromium: [WARNING:dns_config_service_posix.cc(302)] Failed to read DnsConfig.
06-30 10:38:15.839  6471  6471 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 10:38:15.839  6471  6471 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 10:38:15.839  6471  6471 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 10:38:15.839  6471  6471 I Adreno-EGL: Local Branch: ss
06-30 10:38:15.839  6471  6471 I Adreno-EGL: Remote Branch: 
06-30 10:38:15.839  6471  6471 I Adreno-EGL: Local Patches: 
06-30 10:38:15.839  6471  6471 I Adreno-EGL: Reconstruct Branch: 
06-30 10:38:15.849  6471  6471 D libEGL  : eglInitialize EGLDisplay = 0xbee08dac
06-30 10:38:15.919   779  2257 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
06-30 10:38:15.929   779  2257 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
06-30 10:38:15.989  6471  6471 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
06-30 10:38:16.009  6471  6471 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 10:38:16.009  6471  6471 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
06-30 10:38:16.009  6471  6471 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
06-30 10:38:16.009  6471  6471 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
06-30 10:38:16.029  6471  6471 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
06-30 10:38:16.029  6471  6471 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 10:38:16.119  6471  6471 D SecWifiDisplayUtil: Metadata value : none
06-30 10:38:16.129  6471  6471 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{da81727 I.E...... R.....ID 0,0-0,0}
06-30 10:38:16.129  6471  6525 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 10:38:16.139   779   794 D ISSUE_DEBUG: InputChannelName : 80c0fde com.test.thalitest/com.test.thalitest.MainActivity
06-30 10:38:16.139   779   793 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
06-30 10:38:16.139   779   793 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:38:16.139   779   779 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:38:16.139   779   779 I KnoxTimeoutHandler: Shared devices show user statefalse
06-30 10:38:16.149  6471  6471 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6471
06-30 10:38:16.159   779  1708 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6471 for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:38:16.169  6471  6500 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
06-30 10:38:16.169  6471  6471 D SecWifiDisplayUtil: Metadata value : none
06-30 10:38:16.179   295   295 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
06-30 10:38:16.199   779  1489 D InputDispatcher: Focus entered window: 6471
06-30 10:38:16.199   779   932 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
06-30 10:38:16.199   779   932 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:16.199   779   932 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
06-30 10:38:16.199   779   932 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 10:38:16.199  6471  6525 D libEGL  : eglInitialize EGLDisplay = 0x9d5ff7c4
06-30 10:38:16.199  6471  6525 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 10:38:16.239  6471  6471 V ActivityThread: updateVisibility : ActivityRecord{1c21340 token=android.os.BinderProxy@a3895e6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 10:38:16.239  6471  6471 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
06-30 10:38:16.269   779  2252 V WindowStateAnimator: Finishing drawing window Window{80c0fde u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
06-30 10:38:16.269  6471  6471 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
06-30 10:38:16.279  6471  6471 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 10:38:16.279   779  4283 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 10:38:16.279   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbea40364
06-30 10:38:16.289   779   932 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:38:16.289   779   779 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
06-30 10:38:16.299   779   932 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +621ms (total +999ms)
06-30 10:38:16.299   779   779 I KnoxTimeoutHandler: SD activityfalse
06-30 10:38:16.299   779   932 D ActivityManager: mDVFSHelper.release()
06-30 10:38:16.299   779   932 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b1c3601 u0 com.test.thalitest/.MainActivity t64} time:287056
06-30 10:38:16.309   779   932 D ViewRootImpl: #3 mView = null
06-30 10:38:16.309   295  1294 I SurfaceFlinger: id=15 Removed uhalitest (7/9)
06-30 10:38:16.309   295   342 I SurfaceFlinger: id=15 Removed uhalitest (-2/9)
06-30 10:38:16.309   779  2252 V WindowStateAnimator: Finishing drawing window Window{80c0fde u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
06-30 10:38:16.309  6471  6471 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
06-30 10:38:16.309  6471  6471 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a3895e6 time:287066
06-30 10:38:16.309   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbea403a4
06-30 10:38:16.319   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbea40364
06-30 10:38:16.349  6471  6533 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:38:16.349  6471  6533 D libEGL  : eglInitialize EGLDisplay = 0x9b77f3ec
06-30 10:38:16.389  6471  6471 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6471
06-30 10:38:16.679   779  3334 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,06-30 10:38:16.769  6471  6471 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:38:16.899  6471  6541 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1693198032
,06-30 10:38:16.909  6471  6541 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:38:16.909  6471  6541 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:38:16.909  6471  6541 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:38:16.909  6471  6541 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:38:16.909  6471  6541 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 10:38:16.909  6471  6541 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc84496 added. We now have 1 listener(s)
,06-30 10:38:16.909  6471  6541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,06-30 10:38:16.909  6471  6541 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,06-30 10:38:16.909  6471  6541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 10:38:16.909  6471  6541 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 10:38:16.919  6471  6541 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38cded added. We now have 1 listener(s)
06-30 10:38:16.919  6471  6541 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:38:16.919  6471  6541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:38:16.919  6471  6541 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:38:16.929  6471  6541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-30 10:38:16.929  6471  6541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:38:16.929  6471  6541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:38:16.929  6471  6541 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 10:38:16.929  6471  6541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 10:38:16.929  6471  6541 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,06-30 10:38:16.929  6471  6541 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:38:16.929  6471  6541 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 10:38:16.929  6471  6541 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-30 10:38:16.939  6471  6541 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-30 10:38:16.939  6471  6541 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:38:16.999  6471  6471 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:38:17.139  1451  1451 D Recents : onTaskStackChanged
,06-30 10:38:17.149  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,06-30 10:38:17.959  6471  6542 W jxcore-log: Initializing JXcore engine
,06-30 10:38:17.959  6471  6542 W jxcore-log: JXcore engine is ready
,06-30 10:38:18.019  2031  2031 E audit   : type=1400 msg=audit(1467275898.019:278): avc:  denied  { ioctl } for  pid=6542 comm="Thread-907" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:38:18.019  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,06-30 10:38:18.019  2031  2031 E audit   : type=1300 msg=audit(1467275898.019:278): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9b0353c8 items=0 ppid=356 ppcomm=main pid=6542 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-907" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:38:18.019  2031  2031 E audit   : type=1327 msg=audit(1467275898.019:278): proctitle="com.test.thalitest"
06-30 10:38:18.019  2031  2031 E audit   : type=1320 msg=audit(1467275898.019:278): 
,06-30 10:38:18.019  2031  2031 E audit   : type=1400 msg=audit(1467275898.019:279): avc:  denied  { ioctl } for  pid=6542 comm="Thread-907" path="socket:[41990]" dev="sockfs" ino=41990 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 10:38:18.019  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:18.019  2031  2031 E audit   : type=1300 msg=audit(1467275898.019:279): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=1 a3=9b0353c8 items=0 ppid=356 ppcomm=main pid=6542 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-907" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
06-30 10:38:18.019  2031  2031 E audit   : type=1327 msg=audit(1467275898.019:279): proctitle="com.test.thalitest"
06-30 10:38:18.019  2031  2031 E audit   : type=1320 msg=audit(1467275898.019:279): 
,06-30 10:38:18.039  6471  6542 W jxcore-log: Starting JXcore engine
,06-30 10:38:18.049   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:18.149  6471  6542 W jxcore-log: Platform android
06-30 10:38:18.149  6471  6542 W jxcore-log: 
06-30 10:38:18.149  6471  6542 W jxcore-log: Process ARCH arm
06-30 10:38:18.149  6471  6542 W jxcore-log: 
,06-30 10:38:18.329   779  1364 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,06-30 10:38:18.349  6471  6542 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:38:18.349  6471  6542 I jxcore-log: 
06-30 10:38:18.349  6471  6542 W jxcore-log: JXcore engine is started
,06-30 10:38:18.359  6471  6541 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:38:18.369   779  2257 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in null rsrc of package null
,06-30 10:38:18.389   779  2257 D ActivityManager: mDVFSHelper.acquire()
,06-30 10:38:18.389   779  2257 V WindowManager: addAppToken: AppWindowToken{2ca2c8e token=Token{3bf9489 ActivityRecord{9680390 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}}} to stack=1 task=64 at 1
,06-30 10:38:18.409  6543  6543 E Zygote  : v2
,06-30 10:38:18.409  6543  6543 I libpersona: KNOX_SDCARD checking this for 10129
06-30 10:38:18.409  6543  6543 I libpersona: KNOX_SDCARD not a persona
06-30 10:38:18.409  6543  6543 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:38:18.409  6543  6543 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 10:38:18.409  6543  6543 E Zygote  : accessInfo : 0
,06-30 10:38:18.409  6543  6543 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.android.packageinstaller 
,06-30 10:38:18.419   779  2257 I ActivityManager: Start proc 6543:com.android.packageinstaller/u0a129 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 10:38:18.419   779  2257 D InputDispatcher: Focused application set to: xxxx
,06-30 10:38:18.429   779  2257 D InputDispatcher: Focus left window: 6471
,06-30 10:38:18.429  6471  6541 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 69ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:38:18.429   779   932 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
06-30 10:38:18.429   779   932 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:18.429   779   932 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
06-30 10:38:18.429   779   932 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:38:18.439  6543  6543 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:38:18.439  6543  6543 D ActivityThread: Added TimaKeyStore provider
,06-30 10:38:18.449   779  1708 D ActivityManager:  Launching com.android.packageinstaller, updated priority
,06-30 10:38:18.449   779   886 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.android.packageinstaller
,06-30 10:38:18.769   779  1708 I WindowManager: Screenshot max retries 4 of Token{3bf9489 ActivityRecord{9680390 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}} appWin=Window{80c0fde u0 d0 com.test.thalitest/com.test.thalitest.MainActivity} drawState=4
,06-30 10:38:18.879  6543  6543 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:18.919  6543  6543 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 10:38:18.939  6543  6543 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:18.939  6543  6543 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePackageInstaller/GooglePackageInstaller.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:18.979  6543  6543 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.009  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.009  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.019  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.019  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.019  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.029  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.099  6543  6543 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in com.android.packageinstaller rsrc of package null
,06-30 10:38:19.109  6543  6543 D SecWifiDisplayUtil: Metadata value : none
,06-30 10:38:19.109  6543  6543 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7c702c9 I.E...... R.....I. 0,0-0,0}
,06-30 10:38:19.119  6543  6558 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:38:19.119   779  1319 D ISSUE_DEBUG: InputChannelName : 3ad24cb com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity
,06-30 10:38:19.119   779  1694 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,06-30 10:38:19.119   779  1694 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:38:19.129   779   779 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:38:19.129   779   779 I KnoxTimeoutHandler: Shared devices show user statefalse
,06-30 10:38:19.129   779   779 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,06-30 10:38:19.159   295   295 I SurfaceFlinger: id=17 createSurf (145x145),1 flag=4, HrantPermis
,06-30 10:38:19.159   779   888 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{3ad24cb u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}
,06-30 10:38:19.159  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,06-30 10:38:19.179   779  1693 D InputDispatcher: Focus entered window: 6543
,06-30 10:38:19.179   779   932 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
,06-30 10:38:19.179   779   932 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 10:38:19.179   779   932 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
,06-30 10:38:19.179   779   932 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 10:38:19.189  6543  6558 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
06-30 10:38:19.189  6543  6558 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
06-30 10:38:19.189  6543  6558 I Adreno-EGL: Build Date: 01/28/16 Thu
06-30 10:38:19.189  6543  6558 I Adreno-EGL: Local Branch: ss
06-30 10:38:19.189  6543  6558 I Adreno-EGL: Remote Branch: 
06-30 10:38:19.189  6543  6558 I Adreno-EGL: Local Patches: 
06-30 10:38:19.189  6543  6558 I Adreno-EGL: Reconstruct Branch: 
,06-30 10:38:19.189  6543  6558 D libEGL  : eglInitialize EGLDisplay = 0xae2147c4
,06-30 10:38:19.189  6543  6558 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:38:19.239  6543  6543 V ActivityThread: updateVisibility : ActivityRecord{2149be8 token=android.os.BinderProxy@ecb42d0 {com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}} show : true
,06-30 10:38:19.249  6543  6543 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,06-30 10:38:19.249   779  1319 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 10:38:19.269  1942  1942 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 10:38:19.269  6543  6543 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,06-30 10:38:19.399   779  2251 V WindowStateAnimator: Finishing drawing window Window{3ad24cb u0 d0 com.android.packageinstaller/com.android.packageinstaller.permission.ui.GrantPermissionsActivity}: mDrawState=DRAW_PENDING
,06-30 10:38:19.409   295   295 D libEGL  : eglInitialize EGLDisplay = 0xbea40364
,06-30 10:38:19.419  6543  6543 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@ecb42d0 time:290169
,06-30 10:38:19.429   779   932 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:38:19.429   779   779 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,06-30 10:38:19.429   779   779 I KnoxTimeoutHandler: SD activityfalse
,06-30 10:38:19.429   779   932 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +641ms (total +1s33ms)
,06-30 10:38:19.449   779   932 D ActivityManager: mDVFSHelper.release()
,06-30 10:38:19.449   779   932 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9680390 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64} time:290203
,06-30 10:38:20.139  1451  1451 D Recents : onTaskStackChanged
,06-30 10:38:24.869   779  3333 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true]
,06-30 10:38:25.309   779   968 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 10:38:25.339   779   968 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,06-30 10:38:25.729   779  3333 D SSRM:n  : SIOP:: AP = 310, PST = 304, CUR = 450, LCD = 0
,06-30 10:38:30.129   779  1570 E Watchdog: !@Sync 9 [06-30 10:38:30.135]
,06-30 10:38:35.779   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,06-30 10:38:38.049   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:38:44.159   779  1726 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:38:44.159   779  1726 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:38:44.169   779  1726 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:38:44.169   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:38:44.179   779   779 I MotionRecognitionService: Plugged
,06-30 10:38:44.189   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:38:44.189   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:38:44.189   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:38:44.189   779  1726 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,06-30 10:38:44.199   779  1726 D BatteryService: stay LED for fully charged
,06-30 10:38:44.209  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:44.209  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:38:44.209  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:38:44.249  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:44.249  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:44.249  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:38:44.969   779  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:38:44.969   779  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:38:44.969   779  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:38:44.989   779  1230 I TLC_TIMA_PKM_initialize: initializing...
,06-30 10:38:44.989   779  1230 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 10:38:44.989   779  1230 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
06-30 10:38:44.989   779  1230 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 10:38:44.989   779  1230 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,06-30 10:38:44.999   779  1230 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,06-30 10:38:44.999   779  1230 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,06-30 10:38:44.999   779  1230 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 10:38:44.999   779  1230 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,06-30 10:38:45.009   779  1230 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 10:38:45.059   779  1230 D QSEECOMAPI: : Loaded image: APP id = 2
,06-30 10:38:45.079   779  1230 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 10:38:45.089   779  1230 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 10:38:45.849   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,06-30 10:38:48.119   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:38:48.119   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:38:48.129   779  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:48.139   779  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:38:55.919   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:38:58.059   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:00.129   779  1570 E Watchdog: !@Sync 10 [06-30 10:39:00.139]
,06-30 10:39:01.669  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:39:05.989   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:39:14.239   779   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:14.249   779   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:39:14.249   779   794 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:39:14.249   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:14.259   779   779 I MotionRecognitionService: Plugged
,06-30 10:39:14.269   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:39:14.269   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:39:14.269   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:39:14.269   779   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:39:14.279   779   794 D BatteryService: stay LED for fully charged
,06-30 10:39:14.289  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:14.289  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:39:14.289  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:14.309  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:14.309  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:39:14.309  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:16.039   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:39:18.059   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:22.059  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:22.079  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:22.079  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:22.149  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 10:39:22.149  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:39:22.149   317  1197 D EnterpriseController: netId is 0
06-30 10:39:22.159   317  1197 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 10:39:22.279   779   789 I art     : Background partial concurrent mark sweep GC freed 51660(4MB) AllocSpace objects, 122(2MB) LOS objects, 27% free, 42MB/58MB, paused 2.140ms total 259.478ms
,06-30 10:39:26.099   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:39:30.139   779  1570 E Watchdog: !@Sync 11 [06-30 10:39:30.144]
,06-30 10:39:33.379   779  1236 V AlarmManager: Expired Alarm result :4
,06-30 10:39:33.399  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 10:39:33.399  1377  1377 I PERF    : received broadcast android.intent.action.TIME_TICK
,06-30 10:39:33.399  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 10:39:33.459  1377  1377 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 10:39:33.469  1377  1377 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 10:39:33.479  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.489  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.489  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.489  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.489  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.489  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.499  1377  1377 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:33.549  1377  1377 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 10:39:36.159   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:39:38.069   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:44.319   779  1617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:39:44.329   779  1617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:39:44.329   779  1617 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:39:44.329   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:39:44.339   779   779 I MotionRecognitionService: Plugged
,06-30 10:39:44.339   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:39:44.349   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:39:44.349   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:39:44.349   779  1617 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:39:44.359   779  1617 D BatteryService: stay LED for fully charged
,06-30 10:39:44.369  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:44.369  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:39:44.369  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:39:44.409  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:44.409  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:44.409  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:39:46.219   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:39:56.269   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,06-30 10:39:58.069   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:39:59.989   779  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:40:00.149   779  1570 E Watchdog: !@Sync 12 [06-30 10:40:00.151]
,06-30 10:40:01.689  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:40:06.339   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 10:40:14.399   779   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:14.399   779   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:40:14.409   779   794 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:40:14.409   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:14.419   779   779 I MotionRecognitionService: Plugged
,06-30 10:40:14.419   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:40:14.419   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:40:14.429   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:14.429   779   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:40:14.429   779   794 D BatteryService: stay LED for fully charged
,06-30 10:40:14.439  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:14.439  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:40:14.439  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:14.459  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:14.469  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:40:14.469  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:16.389   779  3333 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,06-30 10:40:18.079   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:26.489   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,06-30 10:40:30.149   779  1570 E Watchdog: !@Sync 13 [06-30 10:40:30.155]
,06-30 10:40:36.549   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,06-30 10:40:38.079   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:40:44.479   779  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:40:44.479   779  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:40:44.479   779  1489 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:40:44.479   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:40:44.499   779   779 I MotionRecognitionService: Plugged
,06-30 10:40:44.499   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:40:44.499   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:40:44.499   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:40:44.499   779  1489 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:40:44.509   779  1489 D BatteryService: stay LED for fully charged
,06-30 10:40:44.519  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:44.519  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:40:44.529  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:40:44.559  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:44.559  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:40:44.559  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:40:46.609   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,06-30 10:40:56.659   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,06-30 10:40:58.079   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:00.149   779  1570 E Watchdog: !@Sync 14 [06-30 10:41:00.160]
,06-30 10:41:01.719  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:41:01.909  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 178ms lastUpdatedAfter : 180251ms
,06-30 10:41:06.719   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,06-30 10:41:14.559   779  2251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:16.779   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,06-30 10:41:18.089   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:26.829   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,06-30 10:41:30.149   779  1570 E Watchdog: !@Sync 15 [06-30 10:41:30.164]
,06-30 10:41:34.569   369   369 I bootchecker: bootchecker wake up!!
,06-30 10:41:36.889   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,06-30 10:41:38.089   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:41:44.639   779  1250 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:41:44.639   779  1250 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:41:44.649   779  1250 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:41:44.649   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:41:44.659   779   779 I MotionRecognitionService: Plugged
,06-30 10:41:44.659   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:41:44.669   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:41:44.669   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:41:44.669   779  1250 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:41:44.679   779  1250 D BatteryService: stay LED for fully charged
,06-30 10:41:44.689  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:41:44.689  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:41:44.689  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:41:44.709  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:44.709  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:44.709  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:41:46.949   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,06-30 10:41:56.999   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:41:58.099   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:00.159   779  1570 E Watchdog: !@Sync 16 [06-30 10:42:00.168]
,06-30 10:42:01.919  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:42:07.059   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:42:14.719   779  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:17.109   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:42:18.099   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:27.169   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:42:30.169   779  1570 E Watchdog: !@Sync 17 [06-30 10:42:30.173]
,06-30 10:42:37.219   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:42:38.099   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:42:44.799   779   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:42:44.799   779   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:42:44.809   779   794 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:42:44.809   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:42:44.819   779   779 I MotionRecognitionService: Plugged
,06-30 10:42:44.819   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:42:44.829   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:42:44.829   779   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:42:44.829   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:42:44.829   779   794 D BatteryService: stay LED for fully charged
,06-30 10:42:44.839  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:42:44.839  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:42:44.839  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:42:44.859  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:44.869  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:42:44.869  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:42:47.279   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:42:57.329   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:42:58.109   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:00.159   779  1570 E Watchdog: !@Sync 18 [06-30 10:43:00.177]
,06-30 10:43:01.939  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:43:07.389   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:43:14.879   779  1250 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:14.879   779  1250 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:43:14.879   779  1250 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:43:14.889   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:43:14.899   779   779 I MotionRecognitionService: Plugged
,06-30 10:43:14.899   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:43:14.899   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:43:14.909   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:43:14.909   779  1250 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:43:14.909   779  1250 D BatteryService: stay LED for fully charged
,06-30 10:43:14.929  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:14.929  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:14.929  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:14.969  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:14.969  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:43:14.969  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:17.439   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:43:18.109   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:27.499   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:43:30.179   779  1570 E Watchdog: !@Sync 19 [06-30 10:43:30.181]
,06-30 10:43:37.599   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:43:38.109   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:43:44.959   779  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:43:44.959   779  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:43:44.959   779  1694 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:43:44.969   779  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:43:44.969   779  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:43:44.969   779  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:43:44.969   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:43:44.979   779   779 I MotionRecognitionService: Plugged
,06-30 10:43:44.989   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:43:44.989   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:43:44.989   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:43:44.989   779  1694 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,06-30 10:43:44.999   779  1694 D BatteryService: stay LED for fully charged
,06-30 10:43:45.009  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:45.009  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:43:45.009  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:43:45.049  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:45.049  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:45.049  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:43:46.349   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:43:46.349   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:43:46.359   779  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:46.359   779  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:43:47.659   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:43:57.709   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:43:58.119   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:44:00.179   779  1570 E Watchdog: !@Sync 20 [06-30 10:44:00.185]
,06-30 10:44:01.969  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:44:02.139  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 162ms lastUpdatedAfter : 180235ms
,06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.589   779   879 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.599   779   879 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
,06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.609   779   879 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
06-30 10:44:02.619   779   879 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,06-30 10:44:02.709   779   932 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,06-30 10:44:02.709   779   932 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,06-30 10:44:07.769   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:44:15.039   779   793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:15.039   779   793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:44:15.039   779   793 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:44:15.049   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:15.059   779   779 I MotionRecognitionService: Plugged
,06-30 10:44:15.059   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:44:15.059   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:44:15.069   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:44:15.069   779   793 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:44:15.069   779   793 D BatteryService: stay LED for fully charged
,06-30 10:44:15.089  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:15.089  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:44:15.089  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:15.109  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:15.109  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:15.109  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:17.819   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:44:18.119   779  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 10:44:22.219   779  1617 I ActivityManager: Killing 4468:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 603s, lastActivityTime 603s
,06-30 10:44:22.219   779  1617 I ActivityManager: Killing 3796:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 606s, lastActivityTime 606s
,06-30 10:44:22.249  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:22.269   294   294 I ServiceManager: service 'AtCmdFwd' died
,06-30 10:44:22.269   376  4933 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,06-30 10:44:22.269   376  4933 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:44:22.279   779  1489 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 10:44:22.279   779  1489 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 10:44:22.279   779  1489 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 10:44:22.309  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:22.309  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:22.359   779  1725 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,06-30 10:44:22.359   779  1725 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 10:44:22.359   779  1725 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10923ms
,06-30 10:44:22.389  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:44:22.389  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:44:22.389   317  1197 D EnterpriseController: netId is 0
06-30 10:44:22.389   317  1197 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 10:44:23.279   376  4933 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:44:23.349   779   886 I ActivityManager: Start proc 6664:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 10:44:23.359  6664  6664 E Zygote  : v2
,06-30 10:44:23.359  6664  6664 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:44:23.359  6664  6664 I libpersona: KNOX_SDCARD not a persona
,06-30 10:44:23.359  6664  6664 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:44:23.359  6664  6664 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:44:23.369  6664  6664 E Zygote  : accessInfo : 0
,06-30 10:44:23.409  6664  6664 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:44:23.409  6664  6664 D ActivityThread: Added TimaKeyStore provider
,06-30 10:44:23.429  6664  6664 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 10:44:23.449  6664  6664 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 10:44:23.449  6664  6664 D AtFwdService: onCreate method
,06-30 10:44:23.449  6664  6664 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 10:44:23.459  6664  6676 D AtCkpdCmdHandler: De-queing command
,06-30 10:44:27.869   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:44:30.179   779  1570 E Watchdog: !@Sync 21 [06-30 10:44:30.190]
,06-30 10:44:33.349   779   886 I ActivityManager: Start proc 6678:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 10:44:33.359  6678  6678 E Zygote  : v2
,06-30 10:44:33.359  6678  6678 I libpersona: KNOX_SDCARD checking this for 10026
06-30 10:44:33.359  6678  6678 I libpersona: KNOX_SDCARD not a persona
,06-30 10:44:33.359  6678  6678 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:44:33.359  6678  6678 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:44:33.359  6678  6678 E Zygote  : accessInfo : 0
,06-30 10:44:33.359  6678  6678 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 10:44:33.409  6678  6678 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:44:33.409  6678  6678 D ActivityThread: Added TimaKeyStore provider
,06-30 10:44:33.419   779  2255 I ActivityManager: Killing 3717:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 618s, lastActivityTime 607s
,06-30 10:44:33.449  6678  6678 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 10:44:33.449   779  1489 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,06-30 10:44:33.449   779  1489 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,06-30 10:44:33.469  6678  6678 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 10:44:33.489  6678  6678 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 10:44:33.489  6678  6678 D ContextualPageNotification: resetAllNotification : all clear!!!
,06-30 10:44:33.699   779  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:44:37.929   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:44:45.119   779  2255 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:44:45.129   779  2255 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:44:45.129   779  2255 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:44:45.129   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:44:45.139   779   779 I MotionRecognitionService: Plugged
,06-30 10:44:45.139   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:44:45.149   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:44:45.149   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:44:45.149   779  2255 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:44:45.149   779  2255 D BatteryService: stay LED for fully charged
,06-30 10:44:45.159  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:45.159  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:44:45.169  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:44:45.199  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:45.199  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:44:45.199  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:44:47.979   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:44:58.039   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:45:00.189   779  1570 E Watchdog: !@Sync 22 [06-30 10:45:00.196]
,06-30 10:45:02.149  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:45:08.089   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:45:15.199   779  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:15.199   779  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:45:15.199   779  1694 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:45:15.209   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:15.219   779   779 I MotionRecognitionService: Plugged
,06-30 10:45:15.219   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:45:15.219   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:45:15.229   779  1694 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,06-30 10:45:15.229   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:45:15.229   779  1694 D BatteryService: stay LED for fully charged
,06-30 10:45:15.249  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:15.249  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:45:15.249  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:15.269  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:15.269  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:15.269  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:18.149   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:45:28.199   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:45:30.189   779  1570 E Watchdog: !@Sync 23 [06-30 10:45:30.202]
,06-30 10:45:38.249   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:45:45.279   779  1617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:45:45.289   779  1617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:45:45.289   779  1617 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:45:45.289   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:45:45.299   779   779 I MotionRecognitionService: Plugged
,06-30 10:45:45.299   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:45:45.309   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:45:45.309   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:45:45.309   779  1617 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:45:45.309   779  1617 D BatteryService: stay LED for fully charged
,06-30 10:45:45.329  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:45.329  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:45:45.339  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:45:45.369  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:45.369  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:45:45.369  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:45:48.309   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:45:58.369   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:46:00.199   779  1570 E Watchdog: !@Sync 24 [06-30 10:46:00.206]
,06-30 10:46:02.319  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:46:08.449   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:46:15.359   779  1708 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:15.359   779  1708 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:46:15.369   779  1708 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:46:15.369   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:15.379   779   779 I MotionRecognitionService: Plugged
,06-30 10:46:15.379   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:46:15.379   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:46:15.389   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:15.389   779  1708 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:46:15.389   779  1708 D BatteryService: stay LED for fully charged
,06-30 10:46:15.399  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:15.399  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:46:15.399  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:15.419  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:15.419  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:15.429  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:18.509   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:46:28.559   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:46:30.209   779  1570 E Watchdog: !@Sync 25 [06-30 10:46:30.211]
,06-30 10:46:38.609   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:46:45.439   779  2251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:46:45.439   779  2251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:46:45.439   779  2251 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:46:45.449   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:46:45.459   779   779 I MotionRecognitionService: Plugged
,06-30 10:46:45.459   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:46:45.459   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:46:45.459   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:46:45.469   779  2251 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:46:45.469   779  2251 D BatteryService: stay LED for fully charged
,06-30 10:46:45.489  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:45.489  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:46:45.489  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:46:45.519  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:45.519  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:46:45.519  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:46:48.659   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:46:58.719   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:47:00.209   779  1570 E Watchdog: !@Sync 26 [06-30 10:47:00.215]
,06-30 10:47:02.339  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:47:02.529  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 172ms lastUpdatedAfter : 180384ms
,06-30 10:47:08.769   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:47:15.519   779  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:18.829   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:47:28.879   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:47:30.209   779  1570 E Watchdog: !@Sync 27 [06-30 10:47:30.219]
,06-30 10:47:38.939   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:47:45.599   779   793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:47:45.599   779   793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:47:45.609   779   793 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:47:45.609   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:47:45.619   779   779 I MotionRecognitionService: Plugged
,06-30 10:47:45.619   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:47:45.619   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:47:45.629   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:47:45.629   779   793 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:47:45.629   779   793 D BatteryService: stay LED for fully charged
,06-30 10:47:45.649  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:47:45.649  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:47:45.649  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:47:45.669  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:45.669  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:45.669  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:47:48.989   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:47:59.039   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:48:00.219   779  1570 E Watchdog: !@Sync 28 [06-30 10:48:00.223]
,06-30 10:48:02.569  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:48:02.859   779  2152 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 10:48:02.859   779  2152 V MARsPolicyManager: updateSMDBValues
,06-30 10:48:02.859   779   930 E MARsDBManager: updateDBAll : begin --size 1
,06-30 10:48:02.869   779   930 I ActivityManager: Killing 1866:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 840s, lastActivityTime 766s,
,06-30 10:48:02.879   779   930 I ActivityManager: Killing 1514:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 818s, lastActivityTime 808s
,06-30 10:48:02.949   779   930 E MARsDBManager: updateDBAll : end
,06-30 10:48:02.949   779   930 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,06-30 10:48:02.999   779  1726 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,06-30 10:48:02.999   779  1726 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 10:48:02.999   779  1726 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,06-30 10:48:03.019   779  1319 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,06-30 10:48:03.019   779  1319 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 10:48:03.019   779  1319 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10980ms
06-30 10:48:03.019   779  1319 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 10:48:03.019   779  1319 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 20979ms
,06-30 10:48:03.019  5642  5642 D HealthConsole: Service for HealthDataStore is disconnected
,06-30 10:48:03.049  6706  6706 E Zygote  : v2
,06-30 10:48:03.049  6706  6706 I libpersona: KNOX_SDCARD checking this for 10034
,06-30 10:48:03.049  6706  6706 I libpersona: KNOX_SDCARD not a persona
06-30 10:48:03.049  6706  6706 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:48:03.059  6706  6706 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:48:03.059   779  4283 I ActivityManager: Start proc 6706:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,06-30 10:48:03.069  6706  6706 E Zygote  : accessInfo : 0
,06-30 10:48:03.069  6706  6706 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,06-30 10:48:03.099  6706  6706 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:48:03.099  6706  6706 D ActivityThread: Added TimaKeyStore provider
,06-30 10:48:03.119  6706  6706 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,06-30 10:48:03.149  6706  6706 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,06-30 10:48:03.149  6706  6706 I MultiDex: VM with version 2.1.0 has multidex support
06-30 10:48:03.149  6706  6706 I MultiDex: install
06-30 10:48:03.149  6706  6706 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 10:48:03.149  6706  6706 I MultiDex: install
06-30 10:48:03.149  6706  6706 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:48:03.249  6737  6737 E Zygote  : v2
06-30 10:48:03.249  6737  6737 I libpersona: KNOX_SDCARD checking this for 10016
06-30 10:48:03.249  6737  6737 I libpersona: KNOX_SDCARD not a persona
06-30 10:48:03.249  6737  6737 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 10:48:03.249  6737  6737 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:48:03.259   779  1694 I ActivityManager: Start proc 6737:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider,
06-30 10:48:03.259  6737  6737 E Zygote  : accessInfo : 0
,06-30 10:48:03.259  6737  6737 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,06-30 10:48:03.319  6737  6737 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 10:48:03.319  6737  6737 D ActivityThread: Added TimaKeyStore provider
,06-30 10:48:03.349  6737  6737 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,06-30 10:48:03.419  6706  6706 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 10:48:03.419  6706  6706 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 10:48:03.539  1377  1377 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,06-30 10:48:03.579   779  4283 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,06-30 10:48:03.599  1377  1377 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{ff8331d VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,06-30 10:48:03.599  1377  1377 D AdaptiveEventManager: M updateContainers()
,06-30 10:48:03.599  1377  1377 D AdaptiveEventContainerSmall: C updatePedoContainer()
,06-30 10:48:03.599  1377  1377 D AdaptiveEventContainerSmall: handlePedoUpdate()
,06-30 10:48:03.609   779  1489 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,06-30 10:48:03.619  1377  1377 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,06-30 10:48:03.619   779  2252 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,06-30 10:48:03.629   779  2255 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,06-30 10:48:03.659  6706  6706 I Health.HealthService: HealthService: onCreate() start (6706)
,06-30 10:48:03.759  5642  5642 D HealthDataStore: Service for HealthDataStore is connected
,06-30 10:48:03.769  5642  5642 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 10:48:03.789   779  2252 I ActivityManager: Killing 4994:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,06-30 10:48:03.809  5642  5642 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 10:48:03.809  5642  5642 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 10:48:03.829   779  1725 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,06-30 10:48:03.839  6706  6706 D HealthDataStore: Service for HealthDataStore is connected
,06-30 10:48:03.849  6706  6706 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 10:48:03.849  6706  6706 D HealthConsole: Service for HealthDataConsole is connected
,06-30 10:48:03.869  6706  6706 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 10:48:03.869  6706  6706 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 10:48:04.019   779   886 I ActivityManager: Start proc 6781:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
06-30 10:48:04.019   779  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 10:48:04.019  6781  6781 E Zygote  : v2
,06-30 10:48:04.019  6781  6781 I libpersona: KNOX_SDCARD checking this for 10181
,06-30 10:48:04.029  6781  6781 I libpersona: KNOX_SDCARD not a persona
,06-30 10:48:04.029  6781  6781 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:48:04.029  6781  6781 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:48:04.039  6781  6781 E Zygote  : accessInfo : 0
,06-30 10:48:04.039  6781  6781 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,06-30 10:48:04.049  6706  6762 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,06-30 10:48:04.079  6781  6781 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:48:04.079  6781  6781 D ActivityThread: Added TimaKeyStore provider
,06-30 10:48:04.089   779  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:48:04.089  6781  6781 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,06-30 10:48:04.109  6781  6781 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,06-30 10:48:04.119  6706  6793 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,06-30 10:48:04.139  6737  6747 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,06-30 10:48:04.139  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,06-30 10:48:04.139   394   394 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 6737
06-30 10:48:04.139   394   394 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,06-30 10:48:04.149  6781  6781 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:48:04.159   779   886 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d773977 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84fe9e4 6781:com.sec.android.daemonapp/u0a181}
,06-30 10:48:04.159  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,06-30 10:48:04.159  6781  6781 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:48:04.159  6781  6781 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,06-30 10:48:04.159  6781  6781 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:48:04.169  6781  6781 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,06-30 10:48:04.169  6781  6781 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:48:04.189  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:48:04.189  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 10:48:04.189  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,06-30 10:48:04.189  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:48:04.189  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:48:04.189  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,06-30 10:48:04.199  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 10:48:04.229  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,06-30 10:48:04.229  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:48:04.229  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:48:04.229  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,06-30 10:48:04.239  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 10:48:04.239  6781  6781 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:48:04.239  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.239  6781  6781 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:48:04.249  6781  6781 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:48:04.249  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.249  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:48:04.259   779  1708 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c13c050 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84fe9e4 6781:com.sec.android.daemonapp/u0a181}
,06-30 10:48:04.269  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:48:04.269  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:48:04.269  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:48:04.269  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.269  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:48:04.279  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.279  6781  6781 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 10:48:04.279  6781  6781 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:48:04.279  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.279  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:48:04.289   779  1250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e17249 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84fe9e4 6781:com.sec.android.daemonapp/u0a181}
,06-30 10:48:04.289  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:48:04.289  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:48:04.289  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:48:04.299  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.299  6781  6781 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:48:04.299  6781  6781 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:48:04.299  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 10:48:04.299  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.309  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:48:04.309   779  1708 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c46174e u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84fe9e4 6781:com.sec.android.daemonapp/u0a181}
,06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:48:04.329  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.329  6781  6781 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:48:04.329  6781  6781 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:48:04.329  6781  6781 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:48:04.329  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:48:04.339  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,06-30 10:48:04.339  6781  6781 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 10:48:04.339  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 10:48:04.339  6781  6781 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:48:04.339  6737  6747 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,06-30 10:48:04.339  6781  6781 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:48:04.369  6706  6793 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,06-30 10:48:04.489  6706  6793 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
06-30 10:48:04.489  6706  6793 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 10:48:04.789   394   394 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,06-30 10:48:04.849  6737  6747 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,06-30 10:48:04.849  6737  6747 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,06-30 10:48:04.859  6737  6747 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,06-30 10:48:09.099   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:48:15.679   779  4283 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:15.679   779  4283 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:48:15.689   779  4283 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:48:15.689   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:48:15.699   779   779 I MotionRecognitionService: Plugged
,06-30 10:48:15.699   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:48:15.699   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:48:15.709   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:48:15.709   779  4283 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:48:15.709   779  4283 D BatteryService: stay LED for fully charged
,06-30 10:48:15.719  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:48:15.719  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:48:15.719  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:48:15.749  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:15.749  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:15.749  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:48:19.149   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:48:29.209   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:48:30.209   779  1570 E Watchdog: !@Sync 29 [06-30 10:48:30.227]
,06-30 10:48:39.259   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:48:44.979   779  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:48:44.979   779  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:48:44.979   779  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:48:45.759   779  2255 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:48:48.039   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:48:48.049   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:48:48.059   779  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:48:48.059   779  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:48:49.309   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:48:59.369   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:49:00.219   779  1570 E Watchdog: !@Sync 30 [06-30 10:49:00.232]
,06-30 10:49:02.599  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:49:09.419   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:49:15.829   779  2252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:15.829   779  2252 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:49:15.829   779  2252 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:49:15.829   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:15.849   779   779 I MotionRecognitionService: Plugged
,06-30 10:49:15.849   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:49:15.849   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:49:15.849   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:49:15.859   779  2252 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:49:15.859   779  2252 D BatteryService: stay LED for fully charged
,06-30 10:49:15.869  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:15.869  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:49:15.869  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:15.889  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:15.889  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:15.889  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:19.469   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:49:20.199   779  1236 V AlarmManager: Expired Alarm result :8
,06-30 10:49:22.519  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:22.539  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:22.539  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:22.609  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:22.609  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:49:22.609   317  1197 D EnterpriseController: netId is 0
06-30 10:49:22.609   317  1197 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 10:49:29.529   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:49:30.229   779  1570 E Watchdog: !@Sync 31 [06-30 10:49:30.236]
,06-30 10:49:39.589   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0,
,06-30 10:49:45.909   779  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:49:45.909   779  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:49:45.919   779  1489 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:49:45.919   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:49:45.929   779   779 I MotionRecognitionService: Plugged
,06-30 10:49:45.929   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:49:45.929   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:49:45.939   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:49:45.939   779  1489 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:49:45.939   779  1489 D BatteryService: stay LED for fully charged
,06-30 10:49:45.959  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:49:45.959  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:49:45.959  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:49:45.979  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:45.979  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:49:45.989  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:49:49.649   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:49:59.699   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:50:00.239   779  1570 E Watchdog: !@Sync 32 [06-30 10:50:00.242]
,06-30 10:50:02.629  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:50:02.809  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 169ms lastUpdatedAfter : 180279ms
,06-30 10:50:09.759   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:50:15.989   779  2255 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:15.989   779  2255 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:50:15.999   779  2255 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:50:15.999   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:16.009   779   779 I MotionRecognitionService: Plugged
,06-30 10:50:16.009   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:50:16.009   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:50:16.019   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:16.019   779  2255 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:50:16.019   779  2255 D BatteryService: stay LED for fully charged
,06-30 10:50:16.039  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:16.039  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:16.039  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:16.079  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:16.079  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:16.079  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:19.809   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:50:29.899   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:50:30.239   779  1570 E Watchdog: !@Sync 33 [06-30 10:50:30.246]
,06-30 10:50:39.959   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:50:46.069   779  1617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:50:46.069   779  1617 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:50:46.079   779  1617 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:50:46.079   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:50:46.089   779   779 I MotionRecognitionService: Plugged
,06-30 10:50:46.089   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:50:46.089   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:50:46.099   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:50:46.099   779  1617 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:50:46.099   779  1617 D BatteryService: stay LED for fully charged
,06-30 10:50:46.109  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:50:46.109  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:50:46.109  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:50:46.129  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:46.129  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:46.139  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:50:50.009   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:51:00.059   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:51:00.239   779  1570 E Watchdog: !@Sync 34 [06-30 10:51:00.251]
,06-30 10:51:02.879  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:51:10.119   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:51:16.149   779  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:16.149   779  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:51:16.159   779  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:51:16.159   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:16.169   779   779 I MotionRecognitionService: Plugged
,06-30 10:51:16.169   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:51:16.169   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:51:16.179   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:51:16.179   779  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:51:16.189   779  1693 D BatteryService: stay LED for fully charged
,06-30 10:51:16.199  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:16.199  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:16.199  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:16.229  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:16.229  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:16.229  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:20.169   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:51:30.219   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:51:30.249   779  1570 E Watchdog: !@Sync 35 [06-30 10:51:30.255]
,06-30 10:51:40.279   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:51:46.229   779   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:51:46.229   779   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:51:46.229   779   794 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:51:46.239   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:51:46.249   779   779 I MotionRecognitionService: Plugged
,06-30 10:51:46.249   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:51:46.249   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:51:46.249   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:51:46.259   779   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:51:46.259   779   794 D BatteryService: stay LED for fully charged
,06-30 10:51:46.269  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:46.269  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:51:46.269  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:51:46.299  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:46.309  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:51:46.309  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:51:50.329   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:00.259   779  1570 E Watchdog: !@Sync 36 [06-30 10:52:00.260]
,06-30 10:52:00.389   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:02.899  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:52:10.439   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:16.309   779  4283 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:16.309   779  4283 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:52:16.309   779  4283 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:52:16.319   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:52:16.329   779   779 I MotionRecognitionService: Plugged
,06-30 10:52:16.329   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:52:16.329   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:52:16.329   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:52:16.339   779  4283 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:52:16.339   779  4283 D BatteryService: stay LED for fully charged
,06-30 10:52:16.359  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:16.359  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:52:16.359  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:16.379  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:16.379  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:52:16.379  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:20.499   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:30.259   779  1570 E Watchdog: !@Sync 37 [06-30 10:52:30.265]
,06-30 10:52:30.549   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:40.599   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:46.389   779  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:52:46.389   779  1725 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:52:46.399   779  1725 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:52:46.399   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:52:46.409   779   779 I MotionRecognitionService: Plugged
,06-30 10:52:46.409   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:52:46.409   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:52:46.419   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:52:46.419   779  1725 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 10:52:46.419   779  1725 D BatteryService: stay LED for fully charged
,06-30 10:52:46.439  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:46.439  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:52:46.439  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:52:46.479  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:46.479  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:46.479  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:52:50.659   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:52:50.779   779   789 I art     : Background sticky concurrent mark sweep GC freed 45846(7MB) AllocSpace objects, 405(7MB) LOS objects, 27% free, 42MB/58MB, paused 3.277ms total 113.837ms
,06-30 10:53:00.259   779  1570 E Watchdog: !@Sync 38 [06-30 10:53:00.269]
,06-30 10:53:00.739   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:53:02.929  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:53:03.149  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 211ms lastUpdatedAfter : 180342ms
,06-30 10:53:10.789   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:53:16.469   779  1250 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:16.469   779  1250 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:53:16.479   779  1250 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:53:16.479   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:53:16.489   779   779 I MotionRecognitionService: Plugged
,06-30 10:53:16.489   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:53:16.489   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:53:16.499   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:53:16.499   779  1250 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,06-30 10:53:16.499   779  1250 D BatteryService: stay LED for fully charged
,06-30 10:53:16.509  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:16.509  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:53:16.509  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:53:16.529  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:16.539  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:16.539  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:53:20.849   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:53:30.259   779  1570 E Watchdog: !@Sync 39 [06-30 10:53:30.276]
,06-30 10:53:30.899   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:53:40.959   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:53:44.969   779  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:53:44.969   779  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:53:44.969   779  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:53:46.309   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:53:46.309   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:53:46.319   779  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:46.319   779  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:53:46.549   779  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:53:51.009   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:53:56.999   779   879 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:54:00.279   779  1570 E Watchdog: !@Sync 40 [06-30 10:54:00.281]
,06-30 10:54:01.069   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:54:03.159  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:54:11.169   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:54:16.629   779  2251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:21.219   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:54:22.709  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:22.729  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:22.739  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:22.799  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:54:22.799  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:54:22.799   317  1197 D EnterpriseController: netId is 0
06-30 10:54:22.799   317  1197 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 10:54:30.269   779  1570 E Watchdog: !@Sync 41 [06-30 10:54:30.285]
,06-30 10:54:31.279   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:54:41.339   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:54:46.709   779  2252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:54:46.709   779  2252 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:54:46.719   779  2252 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:54:46.719   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:54:46.729   779   779 I MotionRecognitionService: Plugged
,06-30 10:54:46.729   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:54:46.729   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:54:46.739   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:54:46.739   779  2252 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:54:46.739   779  2252 D BatteryService: stay LED for fully charged
,06-30 10:54:46.759  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:46.759  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:54:46.759  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:54:46.799  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:46.799  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:54:46.799  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:54:51.389   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:55:00.289   779  1570 E Watchdog: !@Sync 42 [06-30 10:55:00.291]
,06-30 10:55:01.439   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:55:03.189  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:55:11.499   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:55:16.789   779  4283 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:21.549   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:55:30.279   779  1570 E Watchdog: !@Sync 43 [06-30 10:55:30.296]
,06-30 10:55:31.599   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:55:41.659   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:55:46.869   779  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:55:46.869   779  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:55:46.879   779  1319 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:55:46.879   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:55:46.889   779   779 I MotionRecognitionService: Plugged
,06-30 10:55:46.889   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:55:46.889   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:55:46.899   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:55:46.899   779  1319 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:55:46.909   779  1319 D BatteryService: stay LED for fully charged
,06-30 10:55:46.919  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:46.919  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:55:46.919  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:55:46.939  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:46.939  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:46.939  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:55:51.709   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:56:00.299   779  1570 E Watchdog: !@Sync 44 [06-30 10:56:00.302]
,06-30 10:56:01.769   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:56:03.209  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:56:03.399  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 176ms lastUpdatedAfter : 180247ms
,06-30 10:56:11.819   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:56:16.949   779  2252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:21.879   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:56:30.289   779  1570 E Watchdog: !@Sync 45 [06-30 10:56:30.306]
,06-30 10:56:31.929   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:56:41.989   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:56:47.029   779  1693 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:56:47.029   779  1693 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:56:47.029   779  1693 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:56:47.039   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:56:47.049   779   779 I MotionRecognitionService: Plugged
,06-30 10:56:47.049   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:56:47.049   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:56:47.049   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:56:47.059   779  1693 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:56:47.059   779  1693 D BatteryService: stay LED for fully charged
,06-30 10:56:47.069  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:56:47.069  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:56:47.069  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:56:47.089  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:47.089  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:47.089  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:56:52.039   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:57:00.309   779  1570 E Watchdog: !@Sync 46 [06-30 10:57:00.312]
,06-30 10:57:02.099   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:57:03.489  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:57:12.149   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:57:17.109   779  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:17.109   779  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:57:17.109   779  1319 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:57:17.119   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:57:17.129   779   779 I MotionRecognitionService: Plugged
,06-30 10:57:17.129   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:57:17.129   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:57:17.129   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:57:17.139   779  1319 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,06-30 10:57:17.139   779  1319 D BatteryService: stay LED for fully charged
,06-30 10:57:17.159  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:17.159  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:57:17.159  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:57:17.199  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:17.199  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:57:17.199  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:57:22.209   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:57:30.309   779  1570 E Watchdog: !@Sync 47 [06-30 10:57:30.316]
,06-30 10:57:32.259   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:57:42.309   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:57:47.189   779  1250 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:57:52.369   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:58:00.319   779  1570 E Watchdog: !@Sync 48 [06-30 10:58:00.320]
,06-30 10:58:02.419   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:58:03.579  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:58:12.499   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:58:17.269   779  1708 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:17.269   779  1708 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:58:17.269   779  1708 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:58:17.279   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:58:17.289   779   779 I MotionRecognitionService: Plugged
,06-30 10:58:17.289   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:58:17.289   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:58:17.289   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:58:17.299   779  1708 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,06-30 10:58:17.299   779  1708 D BatteryService: stay LED for fully charged
,06-30 10:58:17.319  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:17.319  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:58:17.319  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:17.339  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:17.339  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:58:17.339  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:22.549   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:58:30.319   779  1570 E Watchdog: !@Sync 49 [06-30 10:58:30.324]
,06-30 10:58:32.639   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:58:42.689   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:58:44.969   779  1230 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 10:58:44.969   779  1230 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 10:58:44.969   779  1229 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 10:58:47.359   779  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:58:47.359   779  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:58:47.359   779  1319 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:58:47.369   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:58:47.369   779   779 I MotionRecognitionService: Plugged
,06-30 10:58:47.379   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:58:47.379   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:58:47.379   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:58:47.389   779  1319 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:58:47.389   779  1319 D BatteryService: stay LED for fully charged
,06-30 10:58:47.409  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:47.409  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:58:47.409  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:58:47.439  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:47.439  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:47.439  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:58:48.069   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 10:58:48.069   779  1230 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 10:58:48.079   779  1230 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:58:48.079   779  1230 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 10:58:52.749   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:00.319   779  1570 E Watchdog: !@Sync 50 [06-30 10:59:00.328]
,06-30 10:59:02.799   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:03.609  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 10:59:03.789  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 175ms lastUpdatedAfter : 180389ms
,06-30 10:59:12.869   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:17.419   779  2251 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:59:17.429   779  2251 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:59:17.429   779  2251 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:59:17.429   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:59:17.439   779   779 I MotionRecognitionService: Plugged
,06-30 10:59:17.439   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:59:17.449   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:59:17.449   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:59:17.449   779  2251 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 10:59:17.459   779  2251 D BatteryService: stay LED for fully charged
,06-30 10:59:17.469  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:59:17.469  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
06-30 10:59:17.469  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:59:17.489  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:59:17.489  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:59:17.489  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:59:22.929   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:22.949   779   794 I ActivityManager: Killing 6781:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 678s, lastActivityTime 678s
,06-30 10:59:22.959   779   794 I ActivityManager: Killing 6706:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 679s, lastActivityTime 679s
,06-30 10:59:22.959   779   794 I ActivityManager: Killing 6678:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 889s, lastActivityTime 889s
,06-30 10:59:22.969   779   794 I ActivityManager: Killing 6664:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 899s, lastActivityTime 899s
,06-30 10:59:22.979  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:59:22.999  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:59:22.999  2012  2012 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:59:23.089  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:59:23.089  4761  4795 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 10:59:23.089   317  1197 D EnterpriseController: netId is 0
06-30 10:59:23.089   317  1197 D Netd    : getNetworkForDns: using netid 0 for uid 10029
,06-30 10:59:23.089   294   294 I ServiceManager: service 'AtCmdFwd' died
06-30 10:59:23.089   376  4934 I Atfwd_Sendcmd: AtCmdFwd : binderDied
06-30 10:59:23.099   376  4934 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:59:23.099   779  1725 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,06-30 10:59:23.099   779  1725 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
06-30 10:59:23.099   779  1725 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,06-30 10:59:23.109   779  1726 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
06-30 10:59:23.109   779  1726 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
06-30 10:59:23.109   779  1726 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 10986ms
,06-30 10:59:23.119   779  2257 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,06-30 10:59:23.119   779  2257 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
06-30 10:59:23.119   779  2257 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 20976ms
,06-30 10:59:23.129   779  1319 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
06-30 10:59:23.129   779  1319 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
06-30 10:59:23.129   779  1319 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 30970ms
,06-30 10:59:24.099   376  4934 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 10:59:24.159   779   886 I ActivityManager: Start proc 6909:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,06-30 10:59:24.169  6909  6909 E Zygote  : v2
,06-30 10:59:24.169  6909  6909 I libpersona: KNOX_SDCARD checking this for 1000
06-30 10:59:24.169  6909  6909 I libpersona: KNOX_SDCARD not a persona
,06-30 10:59:24.169  6909  6909 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:59:24.179  6909  6909 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:59:24.179  6909  6909 E Zygote  : accessInfo : 0
,06-30 10:59:24.219  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:59:24.219  6909  6909 D ActivityThread: Added TimaKeyStore provider
,06-30 10:59:24.249  6909  6909 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,06-30 10:59:24.259  6909  6909 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,06-30 10:59:24.259  6909  6909 D AtFwdService: onCreate method
,06-30 10:59:24.259  6909  6909 I AtFwdService: Instantiate AtCmdFwd Service
,06-30 10:59:24.279  6909  6921 D AtCkpdCmdHandler: De-queing command
,06-30 10:59:30.329   779  1570 E Watchdog: !@Sync 51 [06-30 10:59:30.333]
,06-30 10:59:32.989   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:34.159   779   886 I ActivityManager: Start proc 6923:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
06-30 10:59:34.159   779  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,06-30 10:59:34.159  6923  6923 E Zygote  : v2
,06-30 10:59:34.169  6923  6923 I libpersona: KNOX_SDCARD checking this for 10181
06-30 10:59:34.169  6923  6923 I libpersona: KNOX_SDCARD not a persona
,06-30 10:59:34.169  6923  6923 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:59:34.169  6923  6923 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:59:34.169  6923  6923 E Zygote  : accessInfo : 0
,06-30 10:59:34.169  6923  6923 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,06-30 10:59:34.219  6923  6923 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:59:34.219  6923  6923 D ActivityThread: Added TimaKeyStore provider
,06-30 10:59:34.239   779  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,06-30 10:59:34.239  6923  6923 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,06-30 10:59:34.259  6923  6923 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,06-30 10:59:34.279  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,06-30 10:59:34.289  6923  6923 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:59:34.289   779   886 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d1c929 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75354ae 6923:com.sec.android.daemonapp/u0a181}
,06-30 10:59:34.299  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,06-30 10:59:34.299  6923  6923 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:59:34.299  6923  6923 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,06-30 10:59:34.309  6923  6923 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:59:34.309  6923  6923 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,06-30 10:59:34.309  6923  6923 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,06-30 10:59:34.319  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:59:34.329  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 10:59:34.329  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,06-30 10:59:34.329  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:59:34.329  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:59:34.329  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,06-30 10:59:34.339  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 10:59:34.349  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,06-30 10:59:34.359  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:59:34.359  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:59:34.359  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,06-30 10:59:34.369  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,06-30 10:59:34.369  6923  6923 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:59:34.379  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:59:34.379  6923  6923 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 10:59:34.379  6923  6923 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,06-30 10:59:34.379  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:59:34.379  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:59:34.379  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 10:59:34.379  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:59:34.379  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 10:59:34.379  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:59:34.379  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.389  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:59:34.389   779  1250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a040dba u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75354ae 6923:com.sec.android.daemonapp/u0a181}
,06-30 10:59:34.399  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:59:34.399  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:59:34.399  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:59:34.399  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:59:34.409  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:59:34.409  6923  6923 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:59:34.409  6923  6923 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:59:34.409  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.409  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:59:34.419   779   794 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{7c4b46b u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75354ae 6923:com.sec.android.daemonapp/u0a181}
,06-30 10:59:34.429  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:59:34.429  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
06-30 10:59:34.429  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:59:34.429  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.429  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:59:34.439  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:59:34.439  6923  6923 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,06-30 10:59:34.439  6923  6923 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:59:34.439  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.439  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:59:34.449   779  1250 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{37b9bc8 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{75354ae 6923:com.sec.android.daemonapp/u0a181}
,06-30 10:59:34.459  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,06-30 10:59:34.469  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,06-30 10:59:34.469  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,06-30 10:59:34.469  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.469  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,06-30 10:59:34.469  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:59:34.469  6923  6923 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
06-30 10:59:34.469  6923  6923 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
06-30 10:59:34.479  6923  6923 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,06-30 10:59:34.479  6923  6923 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,06-30 10:59:43.039   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:44.159   779   886 I ActivityManager: Start proc 6946:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService
,06-30 10:59:44.159  6946  6946 E Zygote  : v2
,06-30 10:59:44.159  6946  6946 I libpersona: KNOX_SDCARD checking this for 10034
06-30 10:59:44.169  6946  6946 I libpersona: KNOX_SDCARD not a persona
,06-30 10:59:44.169  6946  6946 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:59:44.169  6946  6946 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:59:44.169  6946  6946 E Zygote  : accessInfo : 0
,06-30 10:59:44.179  6946  6946 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,06-30 10:59:44.219  6946  6946 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:59:44.219  6946  6946 D ActivityThread: Added TimaKeyStore provider
,06-30 10:59:44.239  6946  6946 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,06-30 10:59:44.259  6946  6946 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,06-30 10:59:44.269  6946  6946 I MultiDex: VM with version 2.1.0 has multidex support
,06-30 10:59:44.269  6946  6946 I MultiDex: install
06-30 10:59:44.269  6946  6946 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 10:59:44.269  6946  6946 I MultiDex: install
06-30 10:59:44.269  6946  6946 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 10:59:44.339  6946  6946 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 10:59:44.339  6946  6946 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 10:59:44.359  1377  1377 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,06-30 10:59:44.369  1377  1377 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{1aec992 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,06-30 10:59:44.369  1377  1377 D AdaptiveEventManager: M updateContainers()
06-30 10:59:44.369  1377  1377 D AdaptiveEventContainerSmall: C updatePedoContainer()
06-30 10:59:44.369  1377  1377 D AdaptiveEventContainerSmall: handlePedoUpdate()
,06-30 10:59:44.369  1377  1377 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,06-30 10:59:44.369   779  2251 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,06-30 10:59:44.379   779  1693 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,06-30 10:59:44.379   779  1726 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,06-30 10:59:44.379   779  2257 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,06-30 10:59:44.409  6946  6946 I Health.HealthService: HealthService: onCreate() start (6946)
,06-30 10:59:44.529  6946  6946 D HealthDataStore: Service for HealthDataStore is connected
,06-30 10:59:44.529  6946  6946 D HealthDataStore: HealthConnectionErrorResult code : 9
,06-30 10:59:44.539  6946  6946 D HealthConsole: Service for HealthDataConsole is connected
,06-30 10:59:44.539  6946  6946 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,06-30 10:59:44.539  6946  6946 E HealthDataStore: disconnectService: Context instance is invalid
,06-30 10:59:44.699  6946  6968 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,06-30 10:59:44.739  6946  6977 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,06-30 10:59:44.749  6737  6748 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,06-30 10:59:44.939  6946  6977 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,06-30 10:59:45.099  6946  6977 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,06-30 10:59:45.109  6946  6977 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,06-30 10:59:47.499   779  1725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 10:59:47.499   779  1725 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 10:59:47.499   779  1725 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 10:59:47.509   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 10:59:47.519   779   779 I MotionRecognitionService: Plugged
,06-30 10:59:47.519   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 10:59:47.519   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 10:59:47.529   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 10:59:47.529   779  1725 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 10:59:47.529   779  1725 D BatteryService: stay LED for fully charged
,06-30 10:59:47.549  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:59:47.549  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 10:59:47.549  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 10:59:47.579  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:59:47.579  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 10:59:47.579  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 10:59:53.099   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 10:59:54.159   779   886 I ActivityManager: Start proc 6983:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,06-30 10:59:54.169  6983  6983 E Zygote  : v2
,06-30 10:59:54.169  6983  6983 I libpersona: KNOX_SDCARD checking this for 10026
06-30 10:59:54.169  6983  6983 I libpersona: KNOX_SDCARD not a persona
,06-30 10:59:54.169  6983  6983 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,06-30 10:59:54.169  6983  6983 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,06-30 10:59:54.169  6983  6983 E Zygote  : accessInfo : 0
,06-30 10:59:54.179  6983  6983 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,06-30 10:59:54.219  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 10:59:54.219  6983  6983 D ActivityThread: Added TimaKeyStore provider
,06-30 10:59:54.239  6983  6983 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,06-30 10:59:54.259  6983  6983 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,06-30 10:59:54.259  6983  6983 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,06-30 10:59:54.269  6983  6983 D ContextualPageNotification: resetAllNotification : all clear!!!
,06-30 11:00:00.329   779  1570 E Watchdog: !@Sync 52 [06-30 11:00:00.338]
,06-30 11:00:02.879   779  2152 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,06-30 11:00:02.879   779  2152 V MARsPolicyManager: updateSMDBValues
,06-30 11:00:02.879   779   930 E MARsDBManager: updateDBAll : begin --size 0
,06-30 11:00:02.879   779   930 E MARsDBManager: updateDBAll : end
,06-30 11:00:03.149   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:00:03.799  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 11:00:13.209   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:00:17.579   779   793 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:00:17.579   779   793 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 11:00:17.589   779   793 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 11:00:17.589   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 11:00:17.599   779   779 I MotionRecognitionService: Plugged
,06-30 11:00:17.599   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 11:00:17.609   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 11:00:17.609   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 11:00:17.609   779   793 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,06-30 11:00:17.609   779   793 D BatteryService: stay LED for fully charged
,06-30 11:00:17.619  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:00:17.619  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:00:17.629  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 11:00:17.659  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:00:17.659  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:00:17.659  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:00:23.259   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:00:30.339   779  1570 E Watchdog: !@Sync 53 [06-30 11:00:30.345]
,06-30 11:00:33.309   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:00:43.369   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:00:47.659   779  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:00:47.659   779  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 11:00:47.669   779  1489 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 11:00:47.669   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 11:00:47.679   779   779 I MotionRecognitionService: Plugged
,06-30 11:00:47.679   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 11:00:47.679   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 11:00:47.689   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 11:00:47.689   779  1489 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 11:00:47.689   779  1489 D BatteryService: stay LED for fully charged
,06-30 11:00:47.709  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:00:47.709  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:00:47.709  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 11:00:47.729  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:00:47.729  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:00:47.729  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:00:53.419   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:01:00.339   779  1570 E Watchdog: !@Sync 54 [06-30 11:01:00.350]
,06-30 11:01:03.479   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:01:03.879  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 11:01:13.529   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:01:17.739   779  1617 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:01:23.589   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:01:30.349   779  1570 E Watchdog: !@Sync 55 [06-30 11:01:30.354]
,06-30 11:01:33.639   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:01:43.689   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:01:47.819   779  2252 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:01:53.749   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:00.349   779  1570 E Watchdog: !@Sync 56 [06-30 11:02:00.358]
,06-30 11:02:03.799   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:03.899  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 11:02:04.089  1727  1784 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 171ms lastUpdatedAfter : 180295ms
,06-30 11:02:13.849   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:17.899   779  1708 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:02:17.899   779  1708 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 11:02:17.899   779  1708 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 11:02:17.909   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 11:02:17.919   779   779 I MotionRecognitionService: Plugged
,06-30 11:02:17.919   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 11:02:17.919   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 11:02:17.929   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 11:02:17.929   779  1708 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,06-30 11:02:17.929   779  1708 D BatteryService: stay LED for fully charged
,06-30 11:02:17.949  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:02:17.949  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:02:17.949  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 11:02:17.989  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:02:17.989  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 11:02:17.989  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:02:23.899   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:29.999   779  1236 V AlarmManager: Expired Alarm result :8
,06-30 11:02:29.999   779  1236 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=1740734 batch.start=2233201
,06-30 11:02:30.059  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 11:02:30.059  1377  1377 I PERF    : received broadcast android.intent.action.TIME_TICK
06-30 11:02:30.059  1377  1377 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 11:02:30.079  1377  1377 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,06-30 11:02:30.079  1377  1377 D SecKeyguardClockView: HomeTimezone(): 1
,06-30 11:02:30.089   779   886 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,06-30 11:02:30.099  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.109   779   779 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 11:02:30.109  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.109  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.119   779   779 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,06-30 11:02:30.119  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.119   779   779 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
06-30 11:02:30.119  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.119  1377  1377 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.119  1377  1377 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.139   779   779 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,06-30 11:02:30.179  1799  7019 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,06-30 11:02:30.189  1377  1377 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,06-30 11:02:30.209  1799  7009 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 11:02:30.269  1799  7009 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,06-30 11:02:30.269  1799  7009 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 11:02:30.279  1799  7009 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 11:02:30.279  1799  7009 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 11:02:30.329  1799  7009 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
06-30 11:02:30.329  1799  7009 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 11:02:30.349   779  1570 E Watchdog: !@Sync 57 [06-30 11:02:30.365]
,06-30 11:02:30.389   779  2255 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,06-30 11:02:30.399  1799  7009 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,06-30 11:02:30.469  4053  7034 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 11:02:30.509   779  1218 E LightSensor: RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
,06-30 11:02:30.509   779   947 D LightsService: [SvcLED]  onSensorChanged::light value = 0
06-30 11:02:30.509   779   947 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 11:02:30.519   779   947 D SensorManager: unregisterListener ::   
06-30 11:02:30.519   779   947 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,06-30 11:02:30.519   779   947 V AlarmManager:  remove PendingIntent] PendingIntent{f11f324: PendingIntentRecord{491ae8d android broadcastIntent}}
,06-30 11:02:30.589  4053  5654 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-30 11:02:30.999  1799  7009 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
06-30 11:02:30.999  1799  7009 E native  : request_context {
06-30 11:02:30.999  1799  7009 E native  :   type: DYNAMIC_CLASS
06-30 11:02:30.999  1799  7009 E native  :   dynamic_class_context {
06-30 11:02:30.999  1799  7009 E native  :     class_type: APP_NAME
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Maps"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Settings"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Gmail"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "YouTube"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Hangouts"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Google+"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Play Store"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Chrome"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Play Books"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Play Music"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Dropbox"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Play Movies & TV"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Contacts"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Phone"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Flipboard"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Play Newsstand"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Drive"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Player"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "ThaliTest"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "S Health"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Peel Smart Remote"
06-30 11:02:30.999  1799  7009 E n,ative  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Photos"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Music"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Calculator"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Messages"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "S Planner"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Camera"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Clock"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "My Files"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Email"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Smart Manager"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Video"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Memo"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Gallery"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Voice Recorder"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Galaxy Apps"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Play Games"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "S Voice"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Docs"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :     instance {
06-30 11:02:30.999  1799  7009 E native  :       value: "Internet"
06-30 11:02:30.999  1799  7009 E native  :     }
06-30 11:02:30.999  1799  7009 E native  :   }
06-30 11:02:30.999  1799  7009 E native  : }
06-30 11:02:30.999  1799  7009 E native  : 
,06-30 11:02:31.009  1799  7009 E ContextCompilationHandl: Compiling recognition context failed for APP_NAMES en-US
06-30 11:02:31.009  1799  7009 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 11:02:31.069  4053  5654 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 11:02:31.149  4053  5661 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 11:02:31.219  4053  4866 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 11:02:31.299  4053  5661 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 11:02:31.359  1799  7009 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
06-30 11:02:31.359  1799  7009 E native  : request_context {
06-30 11:02:31.359  1799  7009 E native  :   type: DYNAMIC_CLASS
06-30 11:02:31.359  1799  7009 E native  :   dynamic_class_context {
06-30 11:02:31.359  1799  7009 E native  :     class_type: SONG_NAME
06-30 11:02:31.359  1799  7009 E native  :     instance {
06-30 11:02:31.359  1799  7009 E native  :       value: "Over the Horizon"
06-30 11:02:31.359  1799  7009 E native  :     }
06-30 11:02:31.359  1799  7009 E native  :   }
06-30 11:02:31.359  1799  7009 E native  : }
06-30 11:02:31.359  1799  7009 E native  : request_context {
06-30 11:02:31.359  1799  7009 E native  :   type: DYNAMIC_CLASS
06-30 11:02:31.359  1799  7009 E native  :   dynamic_class_context {
06-30 11:02:31.359  1799  7009 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
06-30 11:02:31.359  1799  7009 E native  :     instance {
06-30 11:02:31.359  1799  7009 E native  :       value: "Brand Music"
06-30 11:02:31.359  1799  7009 E native  :     }
06-30 11:02:31.359  1799  7009 E native  :   }
06-30 11:02:31.359  1799  7009 E native  : }
06-30 11:02:31.359  1799  7009 E native  : request_context {
06-30 11:02:31.359  1799  7009 E native  :   type: DYNAMIC_CLASS
06-30 11:02:31.359  1799  7009 E native  :   dynamic_class_context {
06-30 11:02:31.359  1799  7009 E native  :     class_type: ARTIST_NAME
06-30 11:02:31.359  1799  7009 E native  :     instance {
06-30 11:02:31.359  1799  7009 E native  :       value: "Samsung"
06-30 11:02:31.359  1799  7009 E native  :     }
06-30 11:02:31.359  1799  7009 E native  :   }
06-30 11:02:31.359  1799  7009 E native  : }
06-30 11:02:31.359  1799  7009 E native  : 
,06-30 11:02:31.359  1799  7009 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
,06-30 11:02:33.969   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:44.019   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:47.979   779  1694 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 11:02:47.979   779  1694 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,06-30 11:02:47.979   779  1694 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,06-30 11:02:47.989   779   779 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 11:02:47.999   779   779 I MotionRecognitionService: Plugged
,06-30 11:02:47.999   779   779 D MotionRecognitionService:   cableConnection= 1
,06-30 11:02:47.999   779   779 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,06-30 11:02:47.999   779   779 D MotionRecognitionService: skip setTransmitPower. 
,06-30 11:02:48.009   779  1694 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,06-30 11:02:48.009   779  1694 D BatteryService: stay LED for fully charged
,06-30 11:02:48.029  1377  1377 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:02:48.029  1377  1377 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,06-30 11:02:48.029  1377  1377 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 11:02:48.059  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:02:48.059  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 11:02:48.059  1377  1377 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 11:02:54.069   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,06-30 11:02:59.999   779  1236 V AlarmManager: Expired Alarm result :8
,06-30 11:03:00.359   779  1570 E Watchdog: !@Sync 58 [06-30 11:03:00.367]
,06-30 11:03:04.119  1727  1784 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,06-30 11:03:04.129   779  3333 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,TIME-OUT KILL (timeout was 1400000ms),06-30 11:03:12.339  2031  2031 E audit   : type=1400 msg=audit(1467277392.339:284): avc:  denied  { execmod } for  pid=7065 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 11:03:12.339  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 11:03:12.339  2031  2031 E audit   : type=1300 msg=audit(1467277392.339:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f3d000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=7065 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 11:03:12.339  2031  2031 E audit   : type=1327 msg=audit(1467277392.339:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 11:03:12.349  2031  2031 E audit   : type=1320 msg=audit(1467277392.339:284): 
06-30 11:03:12.409  2031  2031 E audit   : type=1400 msg=audit(1467277392.409:285): avc:  denied  { execmod } for  pid=7065 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 11:03:12.409  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 11:03:12.409  2031  2031 E audit   : type=1300 msg=audit(1467277392.409:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f00000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=7065 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 11:03:12.409  2031  2031 E audit   : type=1327 msg=audit(1467277392.409:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 11:03:12.409  2031  2031 E audit   : type=1320 msg=audit(1467277392.409:285): 
06-30 11:03:12.449  2031  2031 E audit   : type=1400 msg=audit(1467277392.449:286): avc:  denied  { execmod } for  pid=7065 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
06-30 11:03:12.449  2031  2031 E audit   :  SEPF_SECMOBILE_6.0.1_0011
06-30 11:03:12.459  2031  2031 E audit   : type=1300 msg=audit(1467277392.449:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f00000 a1=51000 a2=5 a3=4 items=0 ppid=3468 ppcomm=adbd pid=7065 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
06-30 11:03:12.459  2031  2031 E audit   : type=1327 msg=audit(1467277392.449:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
06-30 11:03:12.459  2031  2031 E audit   : type=1320 msg=audit(1467277392.449:286): 
06-30 11:03:12.459  7065  7065 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 11:03:12.459  7065  7065 D AndroidRuntime: CheckJNI is OFF
06-30 11:03:12.459  7065  7065 D AndroidRuntime: readGMSProperty: start
06-30 11:03:12.459  7065  7065 D AndroidRuntime: readGMSProperty: already setted!!
06-30 11:03:12.459  7065  7065 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 11:03:12.459  7065  7065 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 11:03:12.459  7065  7065 D AndroidRuntime: readGMSProperty: end
06-30 11:03:12.459  7065  7065 D AndroidRuntime: addProductProperty: start
06-30 11:03:12.469  7065  7065 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 11:03:12.469  7065  7065 W art     : aed64000-b1c8a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
06-30 11:03:12.469  7065  7065 W art     : b1c8a000-b3ef9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
06-30 11:03:12.469  7065  7065 W art     : b3ef9000-b3efa000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
06-30 11:03:12.469  7065  7065 W art     : b3efa000-b3efb000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.469  7065  7065 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
06-30 11:03:12.469  7065  7065 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
06-30 11:03:12.469  7065  7065 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
06-30 11:03:12.469  7065  7065 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
06-30 11:03:12.469  7065  7065 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
06-30 11:03:12.469  7065  7065 W art     : b47ce000-b47d1000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
06-30 11:03:12.469  7065  7065 W art     : b47d1000-b47d2000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
06-30 11:03:12.469  7065  7065 W art     : b47d2000-b47d3000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
06-30 11:03:12.469  7065  7065 W art     : b47d3000-b47d4000 r--p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b47d4000-b47f4000 r--s 00000000 00:0b 7188       /dev/__properties__
06-30 11:03:12.469  7065  7065 W art     : b47f4000-b5205000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
06-30 11:03:12.469  7065  7065 W art     : b5205000-b5206000 ---p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b5206000-b524f000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
06-30 11:03:12.469  7065  7065 W art     : b524f000-b5250000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
06-30 11:03:12.469  7065  7065 W art     : b5250000-b5258000 rw-p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b5258000-b5259000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.469  7065  7065 W art     : b5259000-b528e000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
06-30 11:03:12.469  7065  7065 W art     : b528e000-b528f000 ---p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b528f000-b5290000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
06-30 11:03:12.469  7065  7065 W art     : b5290000-b5291000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
06-30 11:03:12.469  7065  7065 W art     : b5291000-b52e9000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
06-30 11:03:12.469  7065  7065 W art     : b52e9000-b52ea000 ---p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b52ea000-b52eb000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
06-30 11:03:12.469  7065  7065 W art     : b52eb000-b52ec000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
06-30 11:03:12.469  7065  7065 W art     : b52ed000-b52f3000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 11:03:12.469  7065  7065 W art     : b52f3000-b52f4000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 11:03:12.469  7065  7065 W art     : b52f4000-b52f5000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
06-30 11:03:12.469  7065  7065 W art     : b52f5000-b52f7000 rw-p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b52f8000-b5302000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 11:03:12.469  7065  7065 W art     : b5302000-b5305000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 11:03:12.469  7065  7065 W art     : b5305000-b5306000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
06-30 11:03:12.469  7065  7065 W art     : b5307000-b531e000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 11:03:12.469  7065  7065 W art     : b531e000-b531f000 ---p 00000000 00:00 0 
06-30 11:03:12.469  7065  7065 W art     : b531f000-b5320000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 11:03:12.469  7065  7065 W art     : b5320000-b5321000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
06-30 11:03:12.469  7065  7065 W art     : b5322000-b532c000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
06-30 11:03:12.469  7065  7065 W art     : b532c000-b532d000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
06-30 11:03:12.469  7065  7065 W art     : b532d000-b532e000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
06-30 11:03:12.469  7065  7065 W art     : b532e000-b5332000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 11:03:12.469  7065  7065 W art     : b5332000-b5333000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 11:03:12.469  7065  7065 W art     : b5333000-b5334000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
06-30 11:03:12.469  7065  7065 W art     : b5334000-b534a000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
06-30 11:03:12.469  7065  7065 W art     : b534a000-b534b000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
06-30 11:03:12.469  7065  7065 W art     : b534b000-b534c000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
06-30 11:03:12.469  7065  7065 W art     : b534c000-b5359000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
06-30 11:03:12.469  7065  7065 W art     : b5359000-b535a000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
06-30 11:03:12.469  7065  7065 W art     : b535a000-b535b000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
06-30 11:03:12.469  7065  7065 W art     : b535b000-b53bb000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
06-30 11:03:12.469  7065  7065 W art     : b53bb000-b53be000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
06-30 11:03:12.479  7065  7065 W art     : b53be000-b53c2000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b53c2000-b5423000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
06-30 11:03:12.479  7065  7065 W art     : b5423000-b5424000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
06-30 11:03:12.479  7065  7065 W art     : b5424000-b5473000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
06-30 11:03:12.479  7065  7065 W art     : b5473000-b5475000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
06-30 11:03:12.479  7065  7065 W art     : b5475000-b5476000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
06-30 11:03:12.479  7065  7065 W art     : b5476000-b5477000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5477000-b547e000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 11:03:12.479  7065  7065 W art     : b547e000-b547f000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 11:03:12.479  7065  7065 W art     : b547f000-b5480000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
06-30 11:03:12.479  7065  7065 W art     : b5481000-b5484000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 11:03:12.479  7065  7065 W art     : b5484000-b5485000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 11:03:12.479  7065  7065 W art     : b5485000-b5486000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
06-30 11:03:12.479  7065  7065 W art     : b5487000-b548b000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
06-30 11:03:12.479  7065  7065 W art     : b548b000-b548c000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b548c000-b548d000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
06-30 11:03:12.479  7065  7065 W art     : b548d000-b548e000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
06-30 11:03:12.479  7065  7065 W art     : b548f000-b54ac000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 11:03:12.479  7065  7065 W art     : b54ac000-b54ad000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 11:03:12.479  7065  7065 W art     : b54ad000-b54ae000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
06-30 11:03:12.479  7065  7065 W art     : b54af000-b54b4000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 11:03:12.479  7065  7065 W art     : b54b4000-b54b5000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 11:03:12.479  7065  7065 W art     : b54b5000-b54b6000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
06-30 11:03:12.479  7065  7065 W art     : b54b7000-b54e8000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 11:03:12.479  7065  7065 W art     : b54e8000-b54eb000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 11:03:12.479  7065  7065 W art     : b54eb000-b54ec000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
06-30 11:03:12.479  7065  7065 W art     : b54ed000-b5528000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
06-30 11:03:12.479  7065  7065 W art     : b5528000-b5529000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
06-30 11:03:12.479  7065  7065 W art     : b5529000-b552a000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
06-30 11:03:12.479  7065  7065 W art     : b552b000-b5532000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
06-30 11:03:12.479  7065  7065 W art     : b5532000-b5533000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5533000-b5534000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
06-30 11:03:12.479  7065  7065 W art     : b5534000-b5535000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
06-30 11:03:12.479  7065  7065 W art     : b5535000-b5536000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5536000-b554d000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
06-30 11:03:12.479  7065  7065 W art     : b554d000-b554e000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b554e000-b5551000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
06-30 11:03:12.479  7065  7065 W art     : b5551000-b5552000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
06-30 11:03:12.479  7065  7065 W art     : b5552000-b5571000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
06-30 11:03:12.479  7065  7065 W art     : b5571000-b5572000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
06-30 11:03:12.479  7065  7065 W art     : b5572000-b5573000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
06-30 11:03:12.479  7065  7065 W art     : b5573000-b55b1000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
06-30 11:03:12.479  7065  7065 W art     : b55b1000-b55b2000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b55b2000-b55b4000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
06-30 11:03:12.479  7065  7065 W art     : b55b4000-b55b5000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
06-30 11:03:12.479  7065  7065 W art     : b55b6000-b55bd000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 11:03:12.479  7065  7065 W art     : b55bd000-b55be000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 11:03:12.479  7065  7065 W art     : b55be000-b55bf000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
06-30 11:03:12.479  7065  7065 W art     : b55c0000-b55c3000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 11:03:12.479  7065  7065 W art     : b55c3000-b55c4000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 11:03:12.479  7065  7065 W art     : b55c4000-b55c5000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
06-30 11:03:12.479  7065  7065 W art     : b55c5000-b55cb000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 11:03:12.479  7065  7065 W art     : b55cb000-b55cc000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b55cc000-b55cd000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 11:03:12.479  7065  7065 W art     : b55cd000-b55ce000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
06-30 11:03:12.479  7065  7065 W art     : b55ce000-b55d7000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
06-30 11:03:12.479  7065  7065 W art     : b55d7000-b55d8000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
06-30 11:03:12.479  7065  7065 W art     : b55d8000-b55d9000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
06-30 11:03:12.479  7065  7065 W art     : b55d9000-b566a000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 11:03:12.479  7065  7065 W art     : b566a000-b566b000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b566b000-b5676000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 11:03:12.479  7065  7065 W art     : b5676000-b5677000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
06-30 11:03:12.479  7065  7065 W art     : b5678000-b568a000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
06-30 11:03:12.479  7065  7065 W art     : b568a000-b568b000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
06-30 11:03:12.479  7065  7065 W art     : b568b000-b568c000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
06-30 11:03:12.479  7065  7065 W art     : b568d000-b5692000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
06-30 11:03:12.479  7065  7065 W art     : b5692000-b5693000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
06-30 11:03:12.479  7065  7065 W art     : b5693000-b5694000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
06-30 11:03:12.479  7065  7065 W art     : b5695000-b5702000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
06-30 11:03:12.479  7065  7065 W art     : b5702000-b5703000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5703000-b5705000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
06-30 11:03:12.479  7065  7065 W art     : b5705000-b5706000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
06-30 11:03:12.479  7065  7065 W art     : b5706000-b5707000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5707000-b570e000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 11:03:12.479  7065  7065 W art     : b570e000-b570f000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 11:03:12.479  7065  7065 W art     : b570f000-b5710000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
06-30 11:03:12.479  7065  7065 W art     : b5711000-b5791000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 11:03:12.479  7065  7065 W art     : b5791000-b5792000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5792000-b5793000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 11:03:12.479  7065  7065 W art     : b5793000-b5794000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
06-30 11:03:12.479  7065  7065 W art     : b5794000-b57ab000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b57ab000-b57e2000 r-xp 00000000 b3:17 3244       /system/vendor/l
06-30 11:03:12.479  7065  7065 W art     : ib/libqc-opt.so
06-30 11:03:12.479  7065  7065 W art     : b57e2000-b57e3000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 11:03:12.479  7065  7065 W art     : b57e3000-b57e4000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
06-30 11:03:12.479  7065  7065 W art     : b57e4000-b5800000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 11:03:12.479  7065  7065 W art     : b5800000-b5801000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 11:03:12.479  7065  7065 W art     : b5801000-b5802000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
06-30 11:03:12.479  7065  7065 W art     : b5803000-b5864000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
06-30 11:03:12.479  7065  7065 W art     : b5864000-b5866000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
06-30 11:03:12.479  7065  7065 W art     : b5866000-b5867000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
06-30 11:03:12.479  7065  7065 W art     : b5868000-b588f000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
06-30 11:03:12.479  7065  7065 W art     : b588f000-b5890000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5890000-b5891000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
06-30 11:03:12.479  7065  7065 W art     : b5891000-b5892000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
06-30 11:03:12.479  7065  7065 W art     : b5893000-b589b000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 11:03:12.479  7065  7065 W art     : b589b000-b589d000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 11:03:12.479  7065  7065 W art     : b589d000-b589e000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
06-30 11:03:12.479  7065  7065 W art     : b589f000-b58a2000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
06-30 11:03:12.479  7065  7065 W art     : b58a2000-b58a3000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
06-30 11:03:12.479  7065  7065 W art     : b58a3000-b58a4000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
06-30 11:03:12.479  7065  7065 W art     : b58a4000-b58a8000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
06-30 11:03:12.479  7065  7065 W art     : b58a8000-b58a9000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b58a9000-b58aa000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
06-30 11:03:12.479  7065  7065 W art     : b58aa000-b58ab000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
06-30 11:03:12.479  7065  7065 W art     : b58ab000-b58bb000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
06-30 11:03:12.479  7065  7065 W art     : b58bb000-b58bc000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
06-30 11:03:12.479  7065  7065 W art     : b58bc000-b58bd000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
06-30 11:03:12.479  7065  7065 W art     : b58bd000-b5903000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5903000-b590c000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
06-30 11:03:12.479  7065  7065 W art     : b590c000-b590d000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
06-30 11:03:12.479  7065  7065 W art     : b590d000-b590e000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
06-30 11:03:12.479  7065  7065 W art     : b590f000-b5914000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
06-30 11:03:12.479  7065  7065 W art     : b5914000-b5915000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
06-30 11:03:12.479  7065  7065 W art     : b5915000-b5916000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
06-30 11:03:12.479  7065  7065 W art     : b5916000-b5919000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 11:03:12.479  7065  7065 W art     : b5919000-b591a000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b591a000-b591b000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 11:03:12.479  7065  7065 W art     : b591b000-b591c000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
06-30 11:03:12.479  7065  7065 W art     : b591d000-b5935000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 11:03:12.479  7065  7065 W art     : b5935000-b5936000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5936000-b5937000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 11:03:12.479  7065  7065 W art     : b5937000-b5938000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
06-30 11:03:12.479  7065  7065 W art     : b5939000-b5ad3000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
06-30 11:03:12.479  7065  7065 W art     : b5ad3000-b5ad4000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5ad4000-b5ae1000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
06-30 11:03:12.479  7065  7065 W art     : b5ae1000-b5ae2000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
06-30 11:03:12.479  7065  7065 W art     : b5ae2000-b5ae6000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
06-30 11:03:12.479  7065  7065 W art     : b5ae6000-b5ae7000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5ae7000-b5ae8000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
06-30 11:03:12.479  7065  7065 W art     : b5ae8000-b5ae9000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
06-30 11:03:12.479  7065  7065 W art     : b5ae9000-b5afc000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
06-30 11:03:12.479  7065  7065 W art     : b5afc000-b5afd000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
06-30 11:03:12.479  7065  7065 W art     : b5afd000-b5afe000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
06-30 11:03:12.479  7065  7065 W art     : b5aff000-b5b4a000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
06-30 11:03:12.479  7065  7065 W art     : b5b4a000-b5b4b000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
06-30 11:03:12.479  7065  7065 W art     : b5b4b000-b5b4c000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
06-30 11:03:12.479  7065  7065 W art     : b5b4c000-b5b4e000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5b4e000-b5b4f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 11:03:12.479  7065  7065 W art     : b5b4f000-b5b60000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 11:03:12.479  7065  7065 W art     : b5b60000-b5b61000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5b61000-b5b62000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 11:03:12.479  7065  7065 W art     : b5b62000-b5b63000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
06-30 11:03:12.479  7065  7065 W art     : b5b64000-b5b6e000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
06-30 11:03:12.479  7065  7065 W art     : b5b6e000-b5b70000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
06-30 11:03:12.479  7065  7065 W art     : b5b70000-b5b71000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
06-30 11:03:12.479  7065  7065 W art     : b5b71000-b5b8a000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
06-30 11:03:12.479  7065  7065 W art     : b5b8a000-b5b8b000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
06-30 11:03:12.479  7065  7065 W art     : b5b8b000-b5b8e000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
06-30 11:03:12.479  7065  7065 W art     : b5b8e000-b5b92000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5b92000-b5c06000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
06-30 11:03:12.479  7065  7065 W art     : b5c06000-b5c07000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5c07000-b5c0a000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
06-30 11:03:12.479  7065  7065 W art     : b5c0a000-b5c0b000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
06-30 11:03:12.479  7065  7065 W art     : b5c0c000-b5c0f000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
06-30 11:03:12.479  7065  7065 W art     : b5c0f000-b5c10000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
06-30 11:03:12.479  7065  7065 W art     : b5c10000-b5c11000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
06-30 11:03:12.479  7065  7065 W art     : b5c11000-b5c12000 r--p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5c12000-b5c17000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 11:03:12.479  7065  7065 W art     : b5c17000-b5c18000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 11:03:12.479  7065  7065 W art     : b5c18000-b5c19000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
06-30 11:03:12.479  7065  7065 W art     : b5c19000-b5c1a000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5c1a000-b5c1d000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 11:03:12.479  7065  7065 W art     : b5c1d000-b5c1e000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 11:03:12.479  7065  7065 W art     : b5c1e000-b5c1f000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
06-30 11:03:12.479  7065  7065 W art     : b5c1f000-b5c20000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5c20000-b5c24000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
06-30 11:03:12.479  7065  7065 W art     : b5c24000-b5c25000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
06-30 11:03:12.479  7065  7065 W art     : b5c25000-b5c26000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
06-30 11:03:12.479  7065  7065 W art     : b5c26000-b5c27000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 11:03:12.479  7065  7065 W art     : b5c27000-b5c2b000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 11:03:12.479  7065  7065 W art     : b5c2b000-b5c2c000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 11:03:12.479  7065  7065 W art     : b5c2c000-b5c2d000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
06-30 11:03:12.479  7065  7065 W art     : b5c2d000-b5c2e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5c2e000-b5c3c000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
06-30 11:03:12.479  7065  7065 W art     : b5c3c000-b5c3d000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b5c3d000-b5c3e000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
06-30 11:03:12.479  7065  7065 W art     : b5c3e000-b5c3f000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
06-30 11:03:12.479  7065  7065 W art     : b5c3f000-b5c49000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 11:03:12.479  7065  7065 W art     : b5c49000-b5c4c000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 11:03:12.479  7065  7065 W art     : b5c4c000-b5c4d000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
06-30 11:03:12.479  7065  7065 W art     : b5c4d000-b5c4e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5c4e000-b5c58000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
06-30 11:03:12.479  7065  7065 W art     : b5c58000-b5c5b000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
06-30 11:03:12.479  7065  7065 W art     : b5c5b000-b5c5c000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
06-30 11:03:12.479  7065  7065 W art     : b5c5c000-b5c60000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
06-30 11:03:12.479  7065  7065 W art     : b5c60000-b5c61000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
06-30 11:03:12.479  7065  7065 W art     : b5c61000-b5c62000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
06-30 11:03:12.479  7065  7065 W art     : b5c62000-b5c63000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b5c63000-b5c70000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
06-30 11:03:12.479  7065  7065 W art     : b5c70000-b5c72000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
06-30 11:03:12.479  7065  7065 W art     : b5c72000-b5c73000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
06-30 11:03:12.479  7065  7065 W art     : b5c73000-b6085000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
06-30 11:03:12.479  7065  7065 W art     : b6085000-b6086000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6086000-b608f000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
06-30 11:03:12.479  7065  7065 W art     : b608f000-b6093000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
06-30 11:03:12.479  7065  7065 W art     : b6093000-b6094000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6094000-b609b000 r-xp 00000000 b3:17 2571       /system/lib/libaud
06-30 11:03:12.479  7065  7065 W art     : ioutils.so
06-30 11:03:12.479  7065  7065 W art     : b609b000-b609c000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
06-30 11:03:12.479  7065  7065 W art     : b609c000-b609d000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
06-30 11:03:12.479  7065  7065 W art     : b609d000-b609e000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b609e000-b60b9000 r-xp 00000000
06-30 11:03:12.479  7065  7065 W art     :  b3:17 1184       /system/lib/libz.so
06-30 11:03:12.479  7065  7065 W art     : b60b9000-b60ba000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
06-30 11:03:12.479  7065  7065 W art     : b60ba000-b60bb000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
06-30 11:03:12.479  7065  7065 W art     : b60bb000-b60bc000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b60bc000-b6108000 r-xp 00000000 b3:17 994        
06-30 11:03:12.479  7065  7065 W art     : /system/lib/libharfbuzz_ng.so
06-30 11:03:12.479  7065  7065 W art     : b6108000-b6109000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6109000-b610a000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 11:03:12.479  7065  7065 W art     : b610a000-b610b000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
06-30 11:03:12.479  7065  7065 W art     : b610b000-b610c000 r--p 00000000 00:00 0          [anon:li
06-30 11:03:12.479  7065  7065 W art     : nker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b610c000-b6110000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
06-30 11:03:12.479  7065  7065 W art     : b6110000-b6111000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6111000-b6112000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
06-30 11:03:12.479  7065  7065 W art     : b6112000-b6113000 rw-p 00005000 b3:17 2681       /system/lib/libu
06-30 11:03:12.479  7065  7065 W art     : sbhost.so
06-30 11:03:12.479  7065  7065 W art     : b6113000-b614b000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
06-30 11:03:12.479  7065  7065 W art     : b614b000-b614c000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
06-30 11:03:12.479  7065  7065 W art     : b614c000-b614d000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
06-30 11:03:12.479  7065  7065 W art     : b614d000-b614e000 r--p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     :          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b614e000-b61ec000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
06-30 11:03:12.479  7065  7065 W art     : b61ec000-b61ed000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b61ed000-b620b000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
06-30 11:03:12.479  7065  7065 W art     : b620b000-b620c000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
06-30 11:03:12.479  7065  7065 W art     : .so
06-30 11:03:12.479  7065  7065 W art     : b620c000-b637f000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
06-30 11:03:12.479  7065  7065 W art     : b637f000-b638a000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
06-30 11:03:12.479  7065  7065 W art     : b638a000-b638b000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
06-30 11:03:12.479  7065  7065 W art     : b638b000-b64a2000 r-xp 00000000
06-30 11:03:12.479  7065  7065 W art     :  b3:17 2041       /system/lib/libicuuc.so
06-30 11:03:12.479  7065  7065 W art     : b64a2000-b64ad000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
06-30 11:03:12.479  7065  7065 W art     : b64ad000-b64ae000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
06-30 11:03:12.479  7065  7065 W art     : b64ae000-b64b2000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b64b2000-b64d6000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
06-30 11:03:12.479  7065  7065 W art     : o
06-30 11:03:12.479  7065  7065 W art     : b64d6000-b64d8000 r--p 00023000 b3:17 400        /system/lib/libssl.so
06-30 11:03:12.479  7065  7065 W art     : b64d8000-b64d9000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
06-30 11:03:12.479  7065  7065 W art     : b64d9000-b657f000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
06-30 11:03:12.479  7065  7065 W art     : b657f000-b658c000 r--p 000a5000 b3:17 13
06-30 11:03:12.479  7065  7065 W art     : 2        /system/lib/libcrypto.so
06-30 11:03:12.479  7065  7065 W art     : b658c000-b658d000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
06-30 11:03:12.479  7065  7065 W art     : b658d000-b658e000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b658e000-b65e1000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
06-30 11:03:12.479  7065  7065 W art     : b65e1000-b65e2000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b65e2000-b65e3000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
06-30 11:03:12.479  7065  7065 W art     : b65e3000-b65e4000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
06-30 11:03:12.479  7065  7065 W art     : b65e4000-b65e9000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b65e9000-b65fb000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
06-30 11:03:12.479  7065  7065 W art     : b65fb000-b65fc000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b65fc000-b65fd000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
06-30 11:03:12.479  7065  7065 W art     : b65fd000-b65fe000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
06-30 11:03:12.479  7065  7065 W art     : b65fe000-b6605000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 11:03:12.479  7065  7065 W art     : b6605000-b6606000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 11:03:12.479  7065  7065 W art     : b6606000-b6607000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
06-30 11:03:12.479  7065  7065 W art     : b6607000-b6608000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6608000-b660b000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
06-30 11:03:12.479  7065  7065 W art     : b660b000-b660c000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
06-30 11:03:12.479  7065  7065 W art     : b660c000-b660d000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
06-30 11:03:12.479  7065  7065 W art     : b660d000-b6611000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
06-30 11:03:12.479  7065  7065 W art     : b6611000-b6612000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
06-30 11:03:12.479  7065  7065 W art     : b6612000-b6613000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
06-30 11:03:12.479  7065  7065 W art     : b6613000-b6621000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
06-30 11:03:12.479  7065  7065 W art     : b6621000-b6622000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6622000-b6623000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
06-30 11:03:12.479  7065  7065 W art     : b6623000-b6624000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
06-30 11:03:12.479  7065  7065 W art     : b6624000-b662d000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 11:03:12.479  7065  7065 W art     : b662d000-b662e000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 11:03:12.479  7065  7065 W art     : b662e000-b662f000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
06-30 11:03:12.479  7065  7065 W art     : b662f000-b6695000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
06-30 11:03:12.479  7065  7065 W art     : b6695000-b6696000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6696000-b6698000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
06-30 11:03:12.479  7065  7065 W art     : b6698000-b66a1000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
06-30 11:03:12.479  7065  7065 W art     : b66a1000-b66a4000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b66a4000-b673b000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
06-30 11:03:12.479  7065  7065 W art     : b673b000-b673d000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
06-30 11:03:12.479  7065  7065 W art     : b673d000-b673e000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
06-30 11:03:12.479  7065  7065 W art     : b673e000-b673f000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b673f000-b6a60000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
06-30 11:03:12.479  7065  7065 W art     : b6a60000-b6a61000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6a61000-b6a7c000 r--p 00321000 b3:17 377        /system/lib/libskia.so
06-30 11:03:12.479  7065  7065 W art     : b6a7c000-b6a80000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
06-30 11:03:12.479  7065  7065 W art     : b6a80000-b6a85000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6a85000-b6a8d000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 11:03:12.479  7065  7065 W art     : b6a8d000-b6a8e000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 11:03:12.479  7065  7065 W art     : b6a8e000-b6a8f000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
06-30 11:03:12.479  7065  7065 W art     : b6a8f000-b6abd000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
06-30 11:03:12.479  7065  7065 W art     : b6abd000-b6abe000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6abe000-b6ac5000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
06-30 11:03:12.479  7065  7065 W art     : b6ac5000-b6ac6000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
06-30 11:03:12.479  7065  7065 W art     : b6ac6000-b6b0c000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
06-30 11:03:12.479  7065  7065 W art     : b6b0c000-b6b0d000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6b0d000-b6b10000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
06-30 11:03:12.479  7065  7065 W art     : b6b10000-b6b11000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
06-30 11:03:12.479  7065  7065 W art     : b6b11000-b6b2c000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
06-30 11:03:12.479  7065  7065 W art     : b6b2c000-b6b30000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
06-30 11:03:12.479  7065  7065 W art     : b6b30000-b6b31000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
06-30 11:03:12.479  7065  7065 W art     : b6b31000-b6b7e000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
06-30 11:03:12.479  7065  7065 W art     : b6b7e000-b6b7f000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6b7f000-b6b8b000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
06-30 11:03:12.479  7065  7065 W art     : b6b8b000-b6b8c000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
06-30 11:03:12.479  7065  7065 W art     : b6b8c000-b6b99000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
06-30 11:03:12.479  7065  7065 W art     : b6b99000-b6b9a000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6b9a000-b6b9b000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
06-30 11:03:12.479  7065  7065 W art     : b6b9b000-b6b9c000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
06-30 11:03:12.479  7065  7065 W art     : b6b9c000-b6ba4000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
06-30 11:03:12.479  7065  7065 W art     : b6ba4000-b6ba5000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6ba5000-b6ba6000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
06-30 11:03:12.479  7065  7065 W art     : b6ba6000-b6ba7000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
06-30 11:03:12.479  7065  7065 W art     : b6ba7000-b6bae000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
06-30 11:03:12.479  7065  7065 W art     : b6bae000-b6baf000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
06-30 11:03:12.479  7065  7065 W art     : b6baf000-b6bb0000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
06-30 11:03:12.479  7065  7065 W art     : b6bb0000-b6bc4000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
06-30 11:03:12.479  7065  7065 W art     : b6bc4000-b6bc6000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
06-30 11:03:12.479  7065  7065 W art     : b6bc6000-b6bc7000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
06-30 11:03:12.479  7065  7065 W art     : b6bc7000-b6bef000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
06-30 11:03:12.479  7065  7065 W art     : b6bef000-b6bf1000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
06-30 11:03:12.479  7065  7065 W art     : b6bf1000-b6bf2000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
06-30 11:03:12.479  7065  7065 W art     : b6bf2000-b6bf5000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
06-30 11:03:12.479  7065  7065 W art     : b6bf5000-b6bf6000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
06-30 11:03:12.479  7065  7065 W art     : b6bf6000-b6bf7000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
06-30 11:03:12.479  7065  7065 W art     : b6bf7000-b6c00000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
06-30 11:03:12.479  7065  7065 W art     : b6c00000-b6c01000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
06-30 11:03:12.479  7065  7065 W art     : b6c01000-b6c02000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
06-30 11:03:12.479  7065  7065 W art     : b6c02000-b6c22000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
06-30 11:03:12.479  7065  7065 W art     : b6c22000-b6c23000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
06-30 11:03:12.479  7065  7065 W art     : b6c23000-b6c24000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
06-30 11:03:12.479  7065  7065 W art     : b6c24000-b6c97000 r-xp 00000000 b3:17 860        /system/lib/libc.so
06-30 11:03:12.479  7065  7065 W art     : b6c97000-b6c9b000 r--p 00072000 b3:17 860        /system/lib/libc.so
06-30 11:03:12.479  7065  7065 W art     : b6c9b000-b6c9e000 rw-p 00076000 b3:17 860        /system/lib/libc.so
06-30 11:03:12.479  7065  7065 W art     : b6c9e000-b6ca8000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6ca8000-b6d30000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
06-30 11:03:12.479  7065  7065 W art     : b6d30000-b6d31000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6d31000-b6d35000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
06-30 11:03:12.479  7065  7065 W art     : b6d35000-b6d36000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
06-30 11:03:12.479  7065  7065 W art     : b6d36000-b6d37000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6d37000-b6d60000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
06-30 11:03:12.479  7065  7065 W art     : b6d60000-b6d61000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6d61000-b6d64000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
06-30 11:03:12.479  7065  7065 W art     : b6d64000-b6d65000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
06-30 11:03:12.479  7065  7065 W art     : b6d65000-b6e3f000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 11:03:12.479  7065  7065 W art     : b6e3f000-b6e46000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 11:03:12.479  7065  7065 W art     : b6e46000-b6e4e000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
06-30 11:03:12.479  7065  7065 W art     : b6e4e000-b6e4f000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6e4f000-b6e50000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 11:03:12.479  7065  7065 W art     : b6e50000-b6e51000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
06-30 11:03:12.479  7065  7065 W art     : b6e51000-b6e52000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b6e52000-b6e55000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b6e55000-b6e7a000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
06-30 11:03:12.479  7065  7065 W art     : b6e7a000-b6e7b000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6e7b000-b6e82000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
06-30 11:03:12.479  7065  7065 W art     : b6e82000-b6e83000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
06-30 11:03:12.479  7065  7065 W art     : b6e83000-b6e8a000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
06-30 11:03:12.479  7065  7065 W art     : b6e8a000-b6e8b000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
06-30 11:03:12.479  7065  7065 W art     : b6e8b000-b6e8c000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
06-30 11:03:12.479  7065  7065 W art     : b6e8c000-b6e8d000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b6e8d000-b6ea5000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
06-30 11:03:12.479  7065  7065 W art     : b6ea5000-b6ea6000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6ea6000-b6ea7000 r--p 00018000 b3:17 918        /system/lib/libutils.so
06-30 11:03:12.479  7065  7065 W art     : b6ea7000-b6ea8000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
06-30 11:03:12.479  7065  7065 W art     : b6ea8000-b6eb6000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
06-30 11:03:12.479  7065  7065 W art     : b6eb6000-b6eb7000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6eb7000-b6eb8000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
06-30 11:03:12.479  7065  7065 W art     : b6eb8000-b6eb9000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
06-30 11:03:12.479  7065  7065 W art     : b6eb9000-b6eba000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 11:03:12.479  7065  7065 W art     : b6eba000-b6ebc000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b6ebc000-b6ebd000 rw-p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b6ebd000-b6ebe000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
06-30 11:03:12.479  7065  7065 W art     : b6ebe000-b6ebf000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
06-30 11:03:12.479  7065  7065 W art     : b6ebf000-b6ec0000 r--p 00000000 00:00 0          [anon:linker_alloc]
06-30 11:03:12.479  7065  7065 W art     : b6ec0000-b6ee0000 r--s 00000000 00:0b 7188       /dev/__properties__
06-30 11:03:12.479  7065  7065 W art     : b6ee0000-b6ee1000 r--p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6ee1000-b6ee2000 ---p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6ee2000-b6ee4000 rw-p 00000000 00:00 0          [anon:thread signal stack]
06-30 11:03:12.479  7065  7065 W art     : b6ee4000-b6ee5000 r-xp 00000000 00:00 0          [sigpage]
06-30 11:03:12.479  7065  7065 W art     : b6ee5000-b6f00000 r-xp 00000000 b3:17 2770       /system/bin/linker
06-30 11:03:12.479  7065  7065 W art     : b6f00000-b6f01000 r--p 0001a000 b3:17 2770       /system/bin/linker
06-30 11:03:12.479  7065  7065 W art     : b6f01000-b6f03000 rw-p 0001b000 b3:17 2770       /system/bin/linker
06-30 11:03:12.479  7065  7065 W art     : b6f03000-b6f05000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : b6f05000-b6f0a000 r-xp 00000000 b3:17 978        /system/bin/app_process32
06-30 11:03:12.479  7065  7065 W art     : b6f0a000-b6f0b000 r--p 00004000 b3:17 978        /system/bin/app_process32
06-30 11:03:12.479  7065  7065 W art     : b6f0b000-b6f0c000 rw-p 00000000 00:00 0 
06-30 11:03:12.479  7065  7065 W art     : bed64000-bed85000 rw-p 00000000 00:00 0          [stack]
06-30 11:03:12.479  7065  7065 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
06-30 11:03:12.549  7065  7065 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 11:03:12.599  7065  7065 I Radio-JNI: register_android_hardware_Radio DONE
06-30 11:03:12.609  7065  7065 E AffinityControl: AffinityControl: registerfunction enter
06-30 11:03:12.629  7065  7065 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 11:03:12.639   779   794 D PackageManager: START PACKAGE DELETE: observer{231676695}
06-30 11:03:12.639   779   794 D PackageManager: pkg{<packageName>}
06-30 11:03:12.639   779   794 D PackageManager: user{0}
06-30 11:03:12.639   779   794 D PackageManager: caller{2000}
06-30 11:03:12.639   779   794 D PackageManager: flags{2}
06-30 11:03:12.639   779   794 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 11:03:12.639   779   794 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 11:03:12.639   779   794 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 11:03:12.639   779   794 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 11:03:12.639   779   794 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 11:03:12.639   779   968 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 11:03:12.639   779   968 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 11:03:12.639   779   968 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 11:03:12.639   779   968 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 11:03:12.639   779   968 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 11:03:12.639   779   968 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 11:03:12.639   779   968 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 11:03:12.639   779   968 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
06-30 11:03:12.639   779   886 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
06-30 11:03:12.639   779   886 I ActivityManager: Killing 6471:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
06-30 11:03:12.639   779   886 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
06-30 11:03:12.649   779   968 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
06-30 11:03:12.649   779   968 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
06-30 11:03:12.659   779   886 I ActivityManager: Start proc 7080:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
06-30 11:03:12.659  7080  7080 E Zygote  : v2
06-30 11:03:12.659  7080  7080 I libpersona: KNOX_SDCARD checking this for 10004
06-30 11:03:12.659  7080  7080 I libpersona: KNOX_SDCARD not a persona
06-30 11:03:12.659  7080  7080 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
06-30 11:03:12.659  7080  7080 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
06-30 11:03:12.659  7080  7080 E Zygote  : accessInfo : 0
06-30 11:03:12.659   779   886 I ActivityManager:   Force finishing activity ActivityRecord{b1c3601 u0 com.test.thalitest/.MainActivity t64}
06-30 11:03:12.659  7080  7080 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
06-30 11:03:12.659   779   886 I ActivityManager:   Force finishing activity ActivityRecord{9680390 u0 com.android.packageinstaller/.permission.ui.GrantPermissionsActivity t64}
06-30 11:03:12.669   779   886 D InputDispatcher: Focused application set to: xxxx
06-30 11:03:12.679   779   886 I ActivityManager: Killing 5310:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
06-30 11:03:12.689   779   886 D ActivityManager: mDVFSHelper.acquire()
06-30 11:03:12.689  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 11:03:12.689  7080  7080 D ActivityThread: Added TimaKeyStore provider
06-30 11:03:12.699  6543  6543 D ViewRootImpl: #3 mView = null
06-30 11:03:12.699   295   329 I SurfaceFlinger: id=17 Removed HrantPermis (7/9)
06-30 11:03:12.709   295  1294 I SurfaceFlinger: id=17 Removed HrantPermis (-2/9)
06-30 11:03:12.709   779  1617 D InputDispatcher: Focus left window: 6543
06-30 11:03:12.709   779  1617 D InputDispatcher: Focus entered window: 6471
06-30 11:03:12.709   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbea403a4
06-30 11:03:12.729   779   968 D AASAinstall: there is not AASApackages.xml file
06-30 11:03:12.739   295  1294 D libEGL  : eglTerminate EGLDisplay = 0xb46ff6fc
06-30 11:03:12.739   779  1726 D GraphicsStats: Buffer count: 5
06-30 11:03:12.749   779  1250 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@639bb04)
06-30 11:03:12.749   779  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 11:03:12.749   779  1489 I WindowState: WIN DEATH: Window{80c0fde u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 11:03:12.749   295   342 I SurfaceFlinger: id=16 Removed NainActivit (4/8)
06-30 11:03:12.749   295   329 I SurfaceFlinger: id=16 Removed NainActivit (-2/8)
06-30 11:03:12.749   779  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 11:03:12.749   295   329 I SurfaceFlinger: id=16 Removed NainActivit (-2/8)
06-30 11:03:12.749   779  1489 D InputDispatcher: Focus left window: 6471
06-30 11:03:12.749   779  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 11:03:12.759   295   295 D libEGL  : eglTerminate EGLDisplay = 0xbea403a4
06-30 11:03:13.019   779   968 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
06-30 11:03:13.039   779   968 W PackageSettings: Skipping PackageSetting{46afcab com.example.hello/10192} due to missing metadata
06-30 11:03:13.159   779   968 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
06-30 11:03:13.169   338   338 W keystore: ENTER clear_uid from uid 1000 for 10004
06-30 11:03:13.169   779   968 I art     : Starting a blocking GC Explicit
06-30 11:03:13.189   295   295 I SurfaceFlinger: id=18 createSurf (1146x1876),1 flag=4, VSBConnecti
06-30 11:03:13.189   779  1726 V WindowOrientationListener: setCurrentAppOrientation :1
06-30 11:03:13.189   779  1726 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
06-30 11:03:13.199   779  1726 D InputDispatcher: Focus entered window: 3395
06-30 11:03:13.199  1695  1695 D Launcher: onRestart, Launcher: 17152786
06-30 11:03:13.199   779   886 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
06-30 11:03:13.209   779  1617 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
06-30 11:03:13.219   779   888 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{80c0fde u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 11:03:13.219  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
06-30 11:03:13.219   779  2255 I ActivityManager: Killing 4886:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
06-30 11:03:13.229   779   932 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:779 uid:1000
06-30 11:03:13.229   779   932 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 11:03:13.229   779   932 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:779 uid:1000
06-30 11:03:13.229   779   932 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 11:03:13.229  1695  1695 D Launcher: onStart, Launcher: 17152786
06-30 11:03:13.229  1695  1695 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
06-30 11:03:13.229  1695  1695 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
06-30 11:03:13.229  1695  1695 D Launcher.HomeView: onStart
06-30 11:03:13.229   779   888 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{bb2ca95 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
06-30 11:03:13.229   779  1725 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
06-30 11:03:13.229   779  1725 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
06-30 11:03:13.229  1377  1377 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600

```
