#### Test 721454319a152ff_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
,07-05 15:08:34.068   754   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 15:08:34.078   754   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 15:08:34.078   754   768 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-05 15:08:34.088   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:08:34.109   754   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
07-05 15:08:34.109   754   768 D BatteryService: stay LED for fully charged
--------- beginning of main
07-05 15:08:34.119  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:08:34.129  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:08:34.129  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 15:08:34.129   754   754 I MotionRecognitionService: Plugged
07-05 15:08:34.138   754   754 D MotionRecognitionService:   cableConnection= 1
07-05 15:08:34.138   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:08:34.138   754   754 D MotionRecognitionService: skip setTransmitPower. 
07-05 15:08:34.178  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:08:34.178  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:08:34.178  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:08:34.178  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:08:34.188  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 15:08:35.018  2430  2430 E audit   : type=1400 msg=audit(1467724115.018:285): avc:  denied  { execmod } for  pid=7242 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:08:35.018  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:08:35.018  2430  2430 E audit   : type=1300 msg=audit(1467724115.018:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4009000 a1=51000 a2=5 a3=4 items=0 ppid=3631 ppcomm=adbd pid=7242 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:08:35.018  2430  2430 E audit   : type=1327 msg=audit(1467724115.018:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 15:08:35.028  2430  2430 E audit   : type=1320 msg=audit(1467724115.018:285): 
07-05 15:08:35.078  2430  2430 E audit   : type=1400 msg=audit(1467724115.078:286): avc:  denied  { execmod } for  pid=7242 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:08:35.078  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:08:35.078  2430  2430 E audit   : type=1300 msg=audit(1467724115.078:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fcc000 a1=51000 a2=5 a3=4 items=0 ppid=3631 ppcomm=adbd pid=7242 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:08:35.078  2430  2430 E audit   : type=1327 msg=audit(1467724115.078:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 15:08:35.078  2430  2430 E audit   : type=1320 msg=audit(1467724115.078:286): 
07-05 15:08:35.128  2430  2430 E audit   : type=1400 msg=audit(1467724115.128:287): avc:  denied  { execmod } for  pid=7242 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:08:35.128  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:08:35.128  7242  7242 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 15:08:35.128  2430  2430 E audit   : type=1300 msg=audit(1467724115.128:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fc8000 a1=51000 a2=5 a3=4 items=0 ppid=3631 ppcomm=adbd pid=7242 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:08:35.128  2430  2430 E audit   : type=1327 msg=audit(1467724115.128:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 15:08:35.128  2430  2430 E audit   : type=1320 msg=audit(1467724115.128:287): 
07-05 15:08:35.138  7242  7242 D AndroidRuntime: CheckJNI is OFF
07-05 15:08:35.138  7242  7242 D AndroidRuntime: readGMSProperty: start
07-05 15:08:35.138  7242  7242 D AndroidRuntime: readGMSProperty: already setted!!
07-05 15:08:35.138  7242  7242 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 15:08:35.138  7242  7242 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 15:08:35.138  7242  7242 D AndroidRuntime: readGMSProperty: end
07-05 15:08:35.138  7242  7242 D AndroidRuntime: addProductProperty: start
07-05 15:08:35.148  7242  7242 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 15:08:35.148  7242  7242 W art     : aee30000-b1d56000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:08:35.148  7242  7242 W art     : b1d56000-b3fc5000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:08:35.148  7242  7242 W art     : b3fc5000-b3fc6000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:08:35.148  7242  7242 W art     : b3fc6000-b3fc7000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.148  7242  7242 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 15:08:35.148  7242  7242 W art     : b4323000-b4771000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-05 15:08:35.148  7242  7242 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
07-05 15:08:35.148  7242  7242 W art     : b4772000-b477c000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-05 15:08:35.148  7242  7242 W art     : b477c000-b477d000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-05 15:08:35.148  7242  7242 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
07-05 15:08:35.148  7242  7242 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
07-05 15:08:35.148  7242  7242 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-05 15:08:35.148  7242  7242 W art     : b4898000-b489b000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:08:35.148  7242  7242 W art     : b489b000-b489c000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:08:35.148  7242  7242 W art     : b489c000-b489d000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:08:35.148  7242  7242 W art     : b489d000-b489e000 r--p 00000000 00:00 0 
07-05 15:08:35.148  7242  7242 W art     : b489e000-b48be000 r--s 00000000 00:0b 6710       /dev/__properties__
07-05 15:08:35.148  7242  7242 W art     : b48be000-b52cf000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:08:35.158  7242  7242 W art     : b52cf000-b52d0000 ---p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b52d0000-b5319000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:08:35.158  7242  7242 W art     : b5319000-b531a000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:08:35.158  7242  7242 W art     : b531a000-b5322000 rw-p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b5322000-b5323000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.158  7242  7242 W art     : b5323000-b5358000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:08:35.158  7242  7242 W art     : b5358000-b5359000 ---p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b5359000-b535a000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:08:35.158  7242  7242 W art     : b535a000-b535b000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:08:35.158  7242  7242 W art     : b535b000-b53b3000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-05 15:08:35.158  7242  7242 W art     : b53b3000-b53b4000 ---p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b53b4000-b53b5000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-05 15:08:35.158  7242  7242 W art     : b53b5000-b53b6000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-05 15:08:35.158  7242  7242 W art     : b53b7000-b53bd000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:08:35.158  7242  7242 W art     : b53bd000-b53be000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:08:35.158  7242  7242 W art     : b53be000-b53bf000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:08:35.158  7242  7242 W art     : b53bf000-b53c1000 rw-p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b53c2000-b53cc000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:08:35.158  7242  7242 W art     : b53cc000-b53cf000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:08:35.158  7242  7242 W art     : b53cf000-b53d0000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:08:35.158  7242  7242 W art     : b53d1000-b53e8000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:08:35.158  7242  7242 W art     : b53e8000-b53e9000 ---p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b53e9000-b53ea000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:08:35.158  7242  7242 W art     : b53ea000-b53eb000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:08:35.158  7242  7242 W art     : b53ec000-b53f6000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:08:35.158  7242  7242 W art     : b53f6000-b53f7000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:08:35.158  7242  7242 W art     : b53f7000-b53f8000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:08:35.158  7242  7242 W art     : b53f8000-b53fc000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:08:35.158  7242  7242 W art     : b53fc000-b53fd000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:08:35.158  7242  7242 W art     : b53fd000-b53fe000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:08:35.158  7242  7242 W art     : b53fe000-b5414000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-05 15:08:35.158  7242  7242 W art     : b5414000-b5415000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-05 15:08:35.158  7242  7242 W art     : b5415000-b5416000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-05 15:08:35.158  7242  7242 W art     : b5416000-b5423000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:08:35.158  7242  7242 W art     : b5423000-b5424000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:08:35.158  7242  7242 W art     : b5424000-b5425000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:08:35.158  7242  7242 W art     : b5425000-b5485000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-05 15:08:35.158  7242  7242 W art     : b5485000-b5488000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-05 15:08:35.158  7242  7242 W art     : b5488000-b548c000 rw-p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b548c000-b54ed000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-05 15:08:35.158  7242  7242 W art     : b54ed000-b54ee000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-05 15:08:35.158  7242  7242 W art     : b54ee000-b553d000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:08:35.158  7242  7242 W art     : b553d000-b553f000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:08:35.158  7242  7242 W art     : b553f000-b5540000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:08:35.158  7242  7242 W art     : b5540000-b5541000 rw-p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b5541000-b5548000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:08:35.158  7242  7242 W art     : b5548000-b5549000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:08:35.158  7242  7242 W art     : b5549000-b554a000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:08:35.158  7242  7242 W art     : b554b000-b554e000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:08:35.158  7242  7242 W art     : b554e000-b554f000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:08:35.158  7242  7242 W art     : b554f000-b5550000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:08:35.158  7242  7242 W art     : b5551000-b5555000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:08:35.158  7242  7242 W art     : b5555000-b5556000 ---p 00000000 00:00 0 
07-05 15:08:35.158  7242  7242 W art     : b5556000-b5557000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:08:35.158  7242  7242 W art     : b5557000-b5558000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:08:35.158  7242  7242 W art     : b5559000-b5576000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:08:35.158  7242  7242 W art     : b5576000-b5577000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:08:35.158  7242  7242 W art     : b5577000-b5578000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:08:35.158  7242  7242 W art     : b5579000-b557e000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:08:35.158  7242  7242 W art     : b557e000-b557f000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:08:35.158  7242  7242 W art     : b557f000-b5580000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:08:35.158  7242  7242 W art     : b5581000-b55b2000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:08:35.158  7242  7242 W art     : b55b2000-b55b5000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:08:35.158  7242  7242 W art     : b55b5000-b55b6000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:08:35.158  7242  7242 W art     : b55b7000-b55f2000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-05 15:08:35.158  7242  7242 W art     : b55f2000-b55f3000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-05 15:08:35.168  7242  7242 W art     : b55f3000-b55f4000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-05 15:08:35.168  7242  7242 W art     : b55f5000-b55fc000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:08:35.168  7242  7242 W art     : b55fc000-b55fd000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b55fd000-b55fe000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:08:35.168  7242  7242 W art     : b55fe000-b55ff000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:08:35.168  7242  7242 W art     : b55ff000-b5600000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.168  7242  7242 W art     : b5600000-b5617000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:08:35.168  7242  7242 W art     : b5617000-b5618000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b5618000-b561b000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:08:35.168  7242  7242 W art     : b561b000-b561c000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:08:35.168  7242  7242 W art     : b561c000-b563b000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:08:35.168  7242  7242 W art     : b563b000-b563c000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:08:35.168  7242  7242 W art     : b563c000-b563d000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:08:35.168  7242  7242 W art     : b563d000-b567b000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-05 15:08:35.168  7242  7242 W art     : b567b000-b567c000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b567c000-b567e000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-05 15:08:35.168  7242  7242 W art     : b567e000-b567f000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-05 15:08:35.168  7242  7242 W art     : b5680000-b5687000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:08:35.168  7242  7242 W art     : b5687000-b5688000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:08:35.168  7242  7242 W art     : b5688000-b5689000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:08:35.168  7242  7242 W art     : b568a000-b568d000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:08:35.168  7242  7242 W art     : b568d000-b568e000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:08:35.168  7242  7242 W art     : b568e000-b568f000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:08:35.168  7242  7242 W art     : b568f000-b5695000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:08:35.168  7242  7242 W art     : b5695000-b5696000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b5696000-b5697000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:08:35.168  7242  7242 W art     : b5697000-b5698000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:08:35.168  7242  7242 W art     : b5698000-b56a1000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:08:35.168  7242  7242 W art     : b56a1000-b56a2000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:08:35.168  7242  7242 W art     : b56a2000-b56a3000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:08:35.168  7242  7242 W art     : b56a3000-b5734000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:08:35.168  7242  7242 W art     : b5734000-b5735000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b5735000-b5740000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:08:35.168  7242  7242 W art     : b5740000-b5741000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:08:35.168  7242  7242 W art     : b5742000-b5754000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-05 15:08:35.168  7242  7242 W art     : b5754000-b5755000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-05 15:08:35.168  7242  7242 W art     : b5755000-b5756000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-05 15:08:35.168  7242  7242 W art     : b5757000-b575c000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:08:35.168  7242  7242 W art     : b575c000-b575d000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:08:35.168  7242  7242 W art     : b575d000-b575e000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:08:35.168  7242  7242 W art     : b575f000-b57cc000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:08:35.168  7242  7242 W art     : b57cc000-b57cd000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b57cd000-b57cf000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:08:35.168  7242  7242 W art     : b57cf000-b57d0000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:08:35.168  7242  7242 W art     : b57d0000-b57d1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.168  7242  7242 W art     : b57d1000-b57d8000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:08:35.168  7242  7242 W art     : b57d8000-b57d9000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:08:35.168  7242  7242 W art     : b57d9000-b57da000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:08:35.168  7242  7242 W art     : b57db000-b585b000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:08:35.168  7242  7242 W art     : b585b000-b585c000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b585c000-b585d000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:08:35.168  7242  7242 W art     : b585d000-b585e000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:08:35.168  7242  7242 W art     : b585e000-b5875000 rw-p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b5875000-b58ac000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-05 15:08:35.168  7242  7242 W art     : ib/libqc-opt.so
07-05 15:08:35.168  7242  7242 W art     : b58ac000-b58ad000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 15:08:35.168  7242  7242 W art     : b58ad000-b58ae000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 15:08:35.168  7242  7242 W art     : b58ae000-b58ca000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:08:35.168  7242  7242 W art     : b58ca000-b58cb000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:08:35.168  7242  7242 W art     : b58cb000-b58cc000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:08:35.168  7242  7242 W art     : b58cd000-b592e000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-05 15:08:35.168  7242  7242 W art     : b592e000-b5930000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-05 15:08:35.168  7242  7242 W art     : b5930000-b5931000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-05 15:08:35.168  7242  7242 W art     : b5932000-b5959000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-05 15:08:35.168  7242  7242 W art     : b5959000-b595a000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b595a000-b595b000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-05 15:08:35.168  7242  7242 W art     : b595b000-b595c000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-05 15:08:35.168  7242  7242 W art     : b595d000-b5965000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:08:35.168  7242  7242 W art     : b5965000-b5967000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:08:35.168  7242  7242 W art     : b5967000-b5968000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:08:35.168  7242  7242 W art     : b5969000-b596c000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-05 15:08:35.168  7242  7242 W art     : b596c000-b596d000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-05 15:08:35.168  7242  7242 W art     : b596d000-b596e000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-05 15:08:35.168  7242  7242 W art     : b596e000-b5972000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:08:35.168  7242  7242 W art     : b5972000-b5973000 ---p 00000000 00:00 0 
07-05 15:08:35.168  7242  7242 W art     : b5973000-b5974000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:08:35.168  7242  7242 W art     : b5974000-b5975000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:08:35.168  7242  7242 W art     : b5975000-b5985000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-05 15:08:35.178  7242  7242 W art     : b5985000-b5986000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-05 15:08:35.178  7242  7242 W art     : b5986000-b5987000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-05 15:08:35.178  7242  7242 W art     : b5987000-b59cd000 rw-p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b59cd000-b59d6000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-05 15:08:35.178  7242  7242 W art     : b59d6000-b59d7000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-05 15:08:35.178  7242  7242 W art     : b59d7000-b59d8000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-05 15:08:35.178  7242  7242 W art     : b59d9000-b59de000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-05 15:08:35.178  7242  7242 W art     : b59de000-b59df000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-05 15:08:35.178  7242  7242 W art     : b59df000-b59e0000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-05 15:08:35.178  7242  7242 W art     : b59e0000-b59e3000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:08:35.178  7242  7242 W art     : b59e3000-b59e4000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b59e4000-b59e5000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:08:35.178  7242  7242 W art     : b59e5000-b59e6000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:08:35.178  7242  7242 W art     : b59e7000-b59ff000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:08:35.178  7242  7242 W art     : b59ff000-b5a00000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5a00000-b5a01000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:08:35.178  7242  7242 W art     : b5a01000-b5a02000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:08:35.178  7242  7242 W art     : b5a03000-b5b9d000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:08:35.178  7242  7242 W art     : b5b9d000-b5b9e000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5b9e000-b5bab000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:08:35.178  7242  7242 W art     : b5bab000-b5bac000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:08:35.178  7242  7242 W art     : b5bac000-b5bb0000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-05 15:08:35.178  7242  7242 W art     : b5bb0000-b5bb1000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5bb1000-b5bb2000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-05 15:08:35.178  7242  7242 W art     : b5bb2000-b5bb3000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-05 15:08:35.178  7242  7242 W art     : b5bb3000-b5bc6000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:08:35.178  7242  7242 W art     : b5bc6000-b5bc7000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:08:35.178  7242  7242 W art     : b5bc7000-b5bc8000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:08:35.178  7242  7242 W art     : b5bc9000-b5c14000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:08:35.178  7242  7242 W art     : b5c14000-b5c15000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:08:35.178  7242  7242 W art     : b5c15000-b5c16000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:08:35.178  7242  7242 W art     : b5c16000-b5c18000 rw-p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5c18000-b5c19000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:08:35.178  7242  7242 W art     : b5c19000-b5c2a000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:08:35.178  7242  7242 W art     : b5c2a000-b5c2b000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5c2b000-b5c2c000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:08:35.178  7242  7242 W art     : b5c2c000-b5c2d000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:08:35.178  7242  7242 W art     : b5c2e000-b5c38000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:08:35.178  7242  7242 W art     : b5c38000-b5c3a000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:08:35.178  7242  7242 W art     : b5c3a000-b5c3b000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:08:35.178  7242  7242 W art     : b5c3b000-b5c54000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:08:35.178  7242  7242 W art     : b5c54000-b5c55000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:08:35.178  7242  7242 W art     : b5c55000-b5c58000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:08:35.178  7242  7242 W art     : b5c58000-b5c5c000 rw-p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5c5c000-b5cd0000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-05 15:08:35.178  7242  7242 W art     : b5cd0000-b5cd1000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5cd1000-b5cd4000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-05 15:08:35.178  7242  7242 W art     : b5cd4000-b5cd5000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-05 15:08:35.178  7242  7242 W art     : b5cd6000-b5cd9000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:08:35.178  7242  7242 W art     : b5cd9000-b5cda000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:08:35.178  7242  7242 W art     : b5cda000-b5cdb000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:08:35.178  7242  7242 W art     : b5cdb000-b5cdc000 r--p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5cdc000-b5ce1000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:08:35.178  7242  7242 W art     : b5ce1000-b5ce2000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:08:35.178  7242  7242 W art     : b5ce2000-b5ce3000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:08:35.178  7242  7242 W art     : b5ce3000-b5ce4000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.178  7242  7242 W art     : b5ce4000-b5ce7000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:08:35.178  7242  7242 W art     : b5ce7000-b5ce8000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:08:35.178  7242  7242 W art     : b5ce8000-b5ce9000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:08:35.178  7242  7242 W art     : b5ce9000-b5cea000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.178  7242  7242 W art     : b5cea000-b5cee000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:08:35.178  7242  7242 W art     : b5cee000-b5cef000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:08:35.178  7242  7242 W art     : b5cef000-b5cf0000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:08:35.178  7242  7242 W art     : b5cf0000-b5cf1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:08:35.178  7242  7242 W art     : b5cf1000-b5cf5000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:08:35.178  7242  7242 W art     : b5cf5000-b5cf6000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:08:35.178  7242  7242 W art     : b5cf6000-b5cf7000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:08:35.178  7242  7242 W art     : b5cf7000-b5cf8000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.178  7242  7242 W art     : b5cf8000-b5d06000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-05 15:08:35.178  7242  7242 W art     : b5d06000-b5d07000 ---p 00000000 00:00 0 
07-05 15:08:35.178  7242  7242 W art     : b5d07000-b5d08000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-05 15:08:35.178  7242  7242 W art     : b5d08000-b5d09000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-05 15:08:35.178  7242  7242 W art     : b5d09000-b5d13000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:08:35.178  7242  7242 W art     : b5d13000-b5d16000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:08:35.178  7242  7242 W art     : b5d16000-b5d17000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:08:35.178  7242  7242 W art     : b5d17000-b5d18000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.178  7242  7242 W art     : b5d18000-b5d22000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-05 15:08:35.188  7242  7242 W art     : b5d22000-b5d25000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-05 15:08:35.188  7242  7242 W art     : b5d25000-b5d26000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-05 15:08:35.188  7242  7242 W art     : b5d26000-b5d2a000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:08:35.188  7242  7242 W art     : b5d2a000-b5d2b000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:08:35.188  7242  7242 W art     : b5d2b000-b5d2c000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:08:35.188  7242  7242 W art     : b5d2c000-b5d2d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b5d2d000-b5d3a000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:08:35.188  7242  7242 W art     : b5d3a000-b5d3c000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:08:35.188  7242  7242 W art     : b5d3c000-b5d3d000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:08:35.188  7242  7242 W art     : b5d3d000-b614f000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-05 15:08:35.188  7242  7242 W art     : b614f000-b6150000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6150000-b6159000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-05 15:08:35.188  7242  7242 W art     : b6159000-b615d000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-05 15:08:35.188  7242  7242 W art     : b615d000-b615e000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b615e000-b6165000 r-xp 00000000 b3:17 2571       /system/lib/libaud
07-05 15:08:35.188  7242  7242 W art     : ioutils.so
07-05 15:08:35.188  7242  7242 W art     : b6165000-b6166000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:08:35.188  7242  7242 W art     : b6166000-b6167000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:08:35.188  7242  7242 W art     : b6167000-b6168000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6168000-b6183000 r-xp 00000000
07-05 15:08:35.188  7242  7242 W art     :  b3:17 1184       /system/lib/libz.so
07-05 15:08:35.188  7242  7242 W art     : b6183000-b6184000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-05 15:08:35.188  7242  7242 W art     : b6184000-b6185000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-05 15:08:35.188  7242  7242 W art     : b6185000-b6186000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6186000-b61d2000 r-xp 00000000 b3:17 994        
07-05 15:08:35.188  7242  7242 W art     : /system/lib/libharfbuzz_ng.so
07-05 15:08:35.188  7242  7242 W art     : b61d2000-b61d3000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b61d3000-b61d4000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:08:35.188  7242  7242 W art     : b61d4000-b61d5000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:08:35.188  7242  7242 W art     : b61d5000-b61d6000 r--p 00000000 00:00 0          [anon:li
07-05 15:08:35.188  7242  7242 W art     : nker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b61d6000-b61da000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:08:35.188  7242  7242 W art     : b61da000-b61db000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b61db000-b61dc000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:08:35.188  7242  7242 W art     : b61dc000-b61dd000 rw-p 00005000 b3:17 2681       /system/lib/libu
07-05 15:08:35.188  7242  7242 W art     : sbhost.so
07-05 15:08:35.188  7242  7242 W art     : b61dd000-b6215000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:08:35.188  7242  7242 W art     : b6215000-b6216000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:08:35.188  7242  7242 W art     : b6216000-b6217000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:08:35.188  7242  7242 W art     : b6217000-b6218000 r--p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     :          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6218000-b62b6000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-05 15:08:35.188  7242  7242 W art     : b62b6000-b62b7000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b62b7000-b62d5000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-05 15:08:35.188  7242  7242 W art     : b62d5000-b62d6000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
07-05 15:08:35.188  7242  7242 W art     : .so
07-05 15:08:35.188  7242  7242 W art     : b62d6000-b6449000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:08:35.188  7242  7242 W art     : b6449000-b6454000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:08:35.188  7242  7242 W art     : b6454000-b6455000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:08:35.188  7242  7242 W art     : b6455000-b656c000 r-xp 00000000
07-05 15:08:35.188  7242  7242 W art     :  b3:17 2041       /system/lib/libicuuc.so
07-05 15:08:35.188  7242  7242 W art     : b656c000-b6577000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:08:35.188  7242  7242 W art     : b6577000-b6578000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:08:35.188  7242  7242 W art     : b6578000-b657c000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b657c000-b65a0000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
07-05 15:08:35.188  7242  7242 W art     : o
07-05 15:08:35.188  7242  7242 W art     : b65a0000-b65a2000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-05 15:08:35.188  7242  7242 W art     : b65a2000-b65a3000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-05 15:08:35.188  7242  7242 W art     : b65a3000-b6649000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-05 15:08:35.188  7242  7242 W art     : b6649000-b6656000 r--p 000a5000 b3:17 13
07-05 15:08:35.188  7242  7242 W art     : 2        /system/lib/libcrypto.so
07-05 15:08:35.188  7242  7242 W art     : b6656000-b6657000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-05 15:08:35.188  7242  7242 W art     : b6657000-b6658000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6658000-b66ab000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:08:35.188  7242  7242 W art     : b66ab000-b66ac000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b66ac000-b66ad000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:08:35.188  7242  7242 W art     : b66ad000-b66ae000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:08:35.188  7242  7242 W art     : b66ae000-b66b3000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b66b3000-b66c5000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-05 15:08:35.188  7242  7242 W art     : b66c5000-b66c6000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b66c6000-b66c7000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-05 15:08:35.188  7242  7242 W art     : b66c7000-b66c8000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-05 15:08:35.188  7242  7242 W art     : b66c8000-b66cf000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:08:35.188  7242  7242 W art     : b66cf000-b66d0000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:08:35.188  7242  7242 W art     : b66d0000-b66d1000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:08:35.188  7242  7242 W art     : b66d1000-b66d2000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b66d2000-b66d5000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-05 15:08:35.188  7242  7242 W art     : b66d5000-b66d6000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-05 15:08:35.188  7242  7242 W art     : b66d6000-b66d7000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-05 15:08:35.188  7242  7242 W art     : b66d7000-b66db000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-05 15:08:35.188  7242  7242 W art     : b66db000-b66dc000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-05 15:08:35.188  7242  7242 W art     : b66dc000-b66dd000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-05 15:08:35.188  7242  7242 W art     : b66dd000-b66eb000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:08:35.188  7242  7242 W art     : b66eb000-b66ec000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b66ec000-b66ed000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:08:35.188  7242  7242 W art     : b66ed000-b66ee000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:08:35.188  7242  7242 W art     : b66ee000-b66f7000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:08:35.188  7242  7242 W art     : b66f7000-b66f8000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:08:35.188  7242  7242 W art     : b66f8000-b66f9000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:08:35.188  7242  7242 W art     : b66f9000-b675f000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-05 15:08:35.188  7242  7242 W art     : b675f000-b6760000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6760000-b6762000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-05 15:08:35.188  7242  7242 W art     : b6762000-b676b000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-05 15:08:35.188  7242  7242 W art     : b676b000-b676e000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b676e000-b6805000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-05 15:08:35.188  7242  7242 W art     : b6805000-b6807000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-05 15:08:35.188  7242  7242 W art     : b6807000-b6808000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-05 15:08:35.188  7242  7242 W art     : b6808000-b6809000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6809000-b6b2a000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-05 15:08:35.188  7242  7242 W art     : b6b2a000-b6b2b000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6b2b000-b6b46000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-05 15:08:35.188  7242  7242 W art     : b6b46000-b6b4a000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-05 15:08:35.188  7242  7242 W art     : b6b4a000-b6b4f000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6b4f000-b6b57000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:08:35.188  7242  7242 W art     : b6b57000-b6b58000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:08:35.188  7242  7242 W art     : b6b58000-b6b59000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:08:35.188  7242  7242 W art     : b6b59000-b6b87000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:08:35.188  7242  7242 W art     : b6b87000-b6b88000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6b88000-b6b8f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:08:35.188  7242  7242 W art     : b6b8f000-b6b90000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:08:35.188  7242  7242 W art     : b6b90000-b6bd6000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:08:35.188  7242  7242 W art     : b6bd6000-b6bd7000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6bd7000-b6bda000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:08:35.188  7242  7242 W art     : b6bda000-b6bdb000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:08:35.188  7242  7242 W art     : b6bdb000-b6bf6000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-05 15:08:35.188  7242  7242 W art     : b6bf6000-b6bfa000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-05 15:08:35.188  7242  7242 W art     : b6bfa000-b6bfb000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-05 15:08:35.188  7242  7242 W art     : b6bfb000-b6c48000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-05 15:08:35.188  7242  7242 W art     : b6c48000-b6c49000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6c49000-b6c55000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-05 15:08:35.188  7242  7242 W art     : b6c55000-b6c56000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-05 15:08:35.188  7242  7242 W art     : b6c56000-b6c63000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-05 15:08:35.188  7242  7242 W art     : b6c63000-b6c64000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6c64000-b6c65000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-05 15:08:35.188  7242  7242 W art     : b6c65000-b6c66000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-05 15:08:35.188  7242  7242 W art     : b6c66000-b6c6e000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:08:35.188  7242  7242 W art     : b6c6e000-b6c6f000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6c6f000-b6c70000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:08:35.188  7242  7242 W art     : b6c70000-b6c71000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:08:35.188  7242  7242 W art     : b6c71000-b6c78000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:08:35.188  7242  7242 W art     : b6c78000-b6c79000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:08:35.188  7242  7242 W art     : b6c79000-b6c7a000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:08:35.188  7242  7242 W art     : b6c7a000-b6c8e000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-05 15:08:35.188  7242  7242 W art     : b6c8e000-b6c90000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-05 15:08:35.188  7242  7242 W art     : b6c90000-b6c91000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-05 15:08:35.188  7242  7242 W art     : b6c91000-b6cb9000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:08:35.188  7242  7242 W art     : b6cb9000-b6cbb000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:08:35.188  7242  7242 W art     : b6cbb000-b6cbc000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:08:35.188  7242  7242 W art     : b6cbc000-b6cbf000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:08:35.188  7242  7242 W art     : b6cbf000-b6cc0000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:08:35.188  7242  7242 W art     : b6cc0000-b6cc1000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:08:35.188  7242  7242 W art     : b6cc1000-b6cca000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:08:35.188  7242  7242 W art     : b6cca000-b6ccb000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:08:35.188  7242  7242 W art     : b6ccb000-b6ccc000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:08:35.188  7242  7242 W art     : b6ccc000-b6cec000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-05 15:08:35.188  7242  7242 W art     : b6cec000-b6ced000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-05 15:08:35.188  7242  7242 W art     : b6ced000-b6cee000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-05 15:08:35.188  7242  7242 W art     : b6cee000-b6d61000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-05 15:08:35.188  7242  7242 W art     : b6d61000-b6d65000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-05 15:08:35.188  7242  7242 W art     : b6d65000-b6d68000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-05 15:08:35.188  7242  7242 W art     : b6d68000-b6d72000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6d72000-b6dfa000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-05 15:08:35.188  7242  7242 W art     : b6dfa000-b6dfb000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6dfb000-b6dff000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-05 15:08:35.188  7242  7242 W art     : b6dff000-b6e00000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-05 15:08:35.188  7242  7242 W art     : b6e00000-b6e01000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6e01000-b6e2a000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:08:35.188  7242  7242 W art     : b6e2a000-b6e2b000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6e2b000-b6e2e000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:08:35.188  7242  7242 W art     : b6e2e000-b6e2f000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:08:35.188  7242  7242 W art     : b6e2f000-b6f09000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:08:35.188  7242  7242 W art     : b6f09000-b6f10000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:08:35.188  7242  7242 W art     : b6f10000-b6f18000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:08:35.188  7242  7242 W art     : b6f18000-b6f19000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6f19000-b6f1a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:08:35.188  7242  7242 W art     : b6f1a000-b6f1b000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-05 15:08:35.188  7242  7242 W art     : b6f1b000-b6f1c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6f1c000-b6f1f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6f1f000-b6f44000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-05 15:08:35.188  7242  7242 W art     : b6f44000-b6f45000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6f45000-b6f4c000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-05 15:08:35.188  7242  7242 W art     : b6f4c000-b6f4d000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-05 15:08:35.188  7242  7242 W art     : b6f4d000-b6f54000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-05 15:08:35.188  7242  7242 W art     : b6f54000-b6f55000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-05 15:08:35.188  7242  7242 W art     : b6f55000-b6f56000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-05 15:08:35.188  7242  7242 W art     : b6f56000-b6f57000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6f57000-b6f6f000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-05 15:08:35.188  7242  7242 W art     : b6f6f000-b6f70000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6f70000-b6f71000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-05 15:08:35.188  7242  7242 W art     : b6f71000-b6f72000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-05 15:08:35.188  7242  7242 W art     : b6f72000-b6f80000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-05 15:08:35.188  7242  7242 W art     : b6f80000-b6f81000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6f81000-b6f82000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-05 15:08:35.188  7242  7242 W art     : b6f82000-b6f83000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-05 15:08:35.188  7242  7242 W art     : b6f83000-b6f84000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:08:35.188  7242  7242 W art     : b6f84000-b6f86000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6f86000-b6f87000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6f87000-b6f88000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:08:35.188  7242  7242 W art     : b6f88000-b6f89000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-05 15:08:35.188  7242  7242 W art     : b6f89000-b6f8a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:08:35.188  7242  7242 W art     : b6f8a000-b6faa000 r--s 00000000 00:0b 6710       /dev/__properties__
07-05 15:08:35.188  7242  7242 W art     : b6faa000-b6fab000 r--p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6fab000-b6fac000 ---p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6fac000-b6fae000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-05 15:08:35.188  7242  7242 W art     : b6fae000-b6faf000 r-xp 00000000 00:00 0          [sigpage]
07-05 15:08:35.188  7242  7242 W art     : b6faf000-b6fca000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-05 15:08:35.188  7242  7242 W art     : b6fca000-b6fcb000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-05 15:08:35.188  7242  7242 W art     : b6fcb000-b6fcd000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-05 15:08:35.188  7242  7242 W art     : b6fcd000-b6fcf000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : b6fcf000-b6fd4000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-05 15:08:35.188  7242  7242 W art     : b6fd4000-b6fd5000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-05 15:08:35.188  7242  7242 W art     : b6fd5000-b6fd6000 rw-p 00000000 00:00 0 
07-05 15:08:35.188  7242  7242 W art     : beab8000-bead9000 rw-p 00000000 00:00 0          [stack]
07-05 15:08:35.188  7242  7242 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-05 15:08:35.238  7242  7242 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 15:08:35.288  7242  7242 I Radio-JNI: register_android_hardware_Radio DONE
07-05 15:08:35.298  7242  7242 E AffinityControl: AffinityControl: registerfunction enter
07-05 15:08:35.318  7242  7242 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 15:08:35.328   754  1566 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-05 15:08:35.338   754  1566 D ActivityManager: mDVFSHelper.acquire()
07-05 15:08:35.338   754  1566 V WindowManager: addAppToken: AppWindowToken{42820e8 token=Token{e299a0b ActivityRecord{f3c85da u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
07-05 15:08:35.348   754   887 D SecWifiDisplayUtil: Metadata value : none
07-05 15:08:35.348   754   887 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b3c2500 V.E...... R.....ID 0,0-0,0}
07-05 15:08:35.348   754   887 D ISSUE_DEBUG: InputChannelName : 7c9437e Starting com.test.thalitest
07-05 15:08:35.368   754  1566 I ActivityManager: Start proc 7257:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 15:08:35.368  7257  7257 E Zygote  : v2
07-05 15:08:35.368  7257  7257 I libpersona: KNOX_SDCARD checking this for 10004
07-05 15:08:35.368  7257  7257 I libpersona: KNOX_SDCARD not a persona
07-05 15:08:35.368  7257  7257 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:08:35.368  7257  7257 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 15:08:35.368   293   293 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
07-05 15:08:35.368  7257  7257 E Zygote  : accessInfo : 0
07-05 15:08:35.368  7257  7257 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 15:08:35.398   754  1566 D InputDispatcher: Focused application set to: xxxx
07-05 15:08:35.398  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:08:35.398  7257  7257 D ActivityThread: Added TimaKeyStore provider
07-05 15:08:35.398   754  1566 D InputDispatcher: Focus left window: 3551
07-05 15:08:35.398   754   829 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a95d8ab u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-05 15:08:35.398  7242  7242 D AndroidRuntime: Shutting down VM
07-05 15:08:35.398   754  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-05 15:08:35.408  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-05 15:08:35.408   754   887 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-05 15:08:35.408   754   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
07-05 15:08:35.408   754   887 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 15:08:35.408   754   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
07-05 15:08:35.408   754   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 15:08:35.408   754  1778 V WindowOrientationListener: setCurrentAppOrientation :-1
07-05 15:08:35.408   754  1778 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 15:08:35.418   754   829 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{7c9437e u0 d0 Starting com.test.thalitest}
07-05 15:08:35.418  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-05 15:08:35.438   754   887 V WindowStateAnimator: Finishing drawing window Window{7c9437e u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-05 15:08:35.438   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
07-05 15:08:35.438   754  1778 D ActivityManager:  Launching com.test.thalitest, updated priority
07-05 15:08:35.448   293  4870 D libEGL  : eglTerminate EGLDisplay = 0xb470b64c
07-05 15:08:35.448   293   357 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
07-05 15:08:35.448   293   903 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
07-05 15:08:35.448  3551  3551 V ActivityThread: updateVisibility : ActivityRecord{468a122 token=android.os.BinderProxy@312086c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-05 15:08:35.458   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbefeb3a4
,07-05 15:08:35.458   754   827 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-05 15:08:35.468   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450, LCD = 0
07-05 15:08:35.468  1750  1979 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-05 15:08:35.468  1750  1750 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-05 15:08:35.478   293   357 I SurfaceFlinger: id=20 Removed VSBConnecti (5/10)
07-05 15:08:35.478   293  4870 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/10)
07-05 15:08:35.478   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
07-05 15:08:35.478   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb673f64c
07-05 15:08:35.488   293  4870 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
07-05 15:08:35.488   293   353 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-05 15:08:35.488   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbefeb3a4
07-05 15:08:35.488   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbefeb3a4
07-05 15:08:35.498  1750  1750 V ActivityThread: updateVisibility : ActivityRecord{f873ae2 token=android.os.BinderProxy@53c48de {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 15:08:35.498  2251  2263 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-05 15:08:35.498  1750  1750 D Launcher: onTrimMemory. Level: 20
07-05 15:08:35.578   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 15:08:35.618   754  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-05 15:08:35.628  7257  7257 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-05 15:08:35.648   754  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:08:35.658  7257  7257 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-05 15:08:35.658  7257  7257 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-05 15:08:35.678  7257  7257 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,07-05 15:08:35.698  7257  7257 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,07-05 15:08:35.708  7257  7257 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-05 15:08:35.718  7257  7257 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1210-1213)
07-05 15:08:35.718  7257  7257 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-05 15:08:35.738  7257  7257 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8de57ee}
,07-05 15:08:35.738  7257  7257 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,07-05 15:08:35.738  7257  7276 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-05 15:08:35.738  7257  7257 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 15:08:35.748  7257  7257 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-05 15:08:35.758   754   764 I art     : Background partial concurrent mark sweep GC freed 47557(3MB) AllocSpace objects, 93(1860KB) LOS objects, 27% free, 42MB/58MB, paused 2.165ms total 166.815ms
,07-05 15:08:35.768  7257  7257 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-05 15:08:35.768  7257  7257 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-05 15:08:35.768  7257  7257 I Adreno-EGL: Build Date: 01/28/16 Thu
07-05 15:08:35.768  7257  7257 I Adreno-EGL: Local Branch: ss
07-05 15:08:35.768  7257  7257 I Adreno-EGL: Remote Branch: 
07-05 15:08:35.768  7257  7257 I Adreno-EGL: Local Patches: 
07-05 15:08:35.768  7257  7257 I Adreno-EGL: Reconstruct Branch: 
,07-05 15:08:35.778  7257  7257 D libEGL  : eglInitialize EGLDisplay = 0xbecccdac
,07-05 15:08:35.808   754  1778 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
07-05 15:08:35.808   754  1778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,07-05 15:08:35.858  7257  7257 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,07-05 15:08:35.868  7257  7257 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 15:08:35.868  7257  7257 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,07-05 15:08:35.868  7257  7257 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,07-05 15:08:35.868  7257  7257 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,07-05 15:08:35.888  7257  7257 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,07-05 15:08:35.898  7257  7257 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-05 15:08:35.998  7257  7257 D SecWifiDisplayUtil: Metadata value : none
,07-05 15:08:35.998  7257  7257 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9ea8f7c I.E...... R.....ID 0,0-0,0}
,07-05 15:08:36.008  7257  7300 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 15:08:36.008   754  1778 D ISSUE_DEBUG: InputChannelName : a74bb63 com.test.thalitest/com.test.thalitest.MainActivity
,07-05 15:08:36.018   754  1777 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 15:08:36.018   754  1777 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:08:36.018   754   754 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:08:36.018   754   754 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-05 15:08:36.038  7257  7257 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7257
,07-05 15:08:36.038   754  1779 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7257 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 15:08:36.038   754  1327 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-05 15:08:36.048   754  1327 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 15:08:36.048   754  1327 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:08:36.048   754  1327 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,07-05 15:08:36.048   754  1327 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-05 15:08:36.058  7257  7257 D SecWifiDisplayUtil: Metadata value : none
,07-05 15:08:36.058  7257  7276 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,07-05 15:08:36.078   293   293 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
,07-05 15:08:36.088   754  2551 D InputDispatcher: Focus entered window: 7257
,07-05 15:08:36.088   754   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
,07-05 15:08:36.088   754   887 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 15:08:36.088   754   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
07-05 15:08:36.088  7257  7300 D libEGL  : eglInitialize EGLDisplay = 0x9d7ff7c4
07-05 15:08:36.088  7257  7300 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 15:08:36.088   754   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-05 15:08:36.158  7257  7257 V ActivityThread: updateVisibility : ActivityRecord{5736467 token=android.os.BinderProxy@55166f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 15:08:36.158  7257  7257 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-05 15:08:36.168  7257  7257 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-05 15:08:36.178   754  2553 V WindowStateAnimator: Finishing drawing window Window{a74bb63 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,07-05 15:08:36.178  7257  7257 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 15:08:36.178   754  2551 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 15:08:36.188   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
,07-05 15:08:36.188   754   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:08:36.188   754   754 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:08:36.188   754   887 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +576ms (total +834ms)
,07-05 15:08:36.188   754   754 I KnoxTimeoutHandler: SD activityfalse
,07-05 15:08:36.188   754   887 D ActivityManager: mDVFSHelper.release()
07-05 15:08:36.188   754   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f3c85da u0 com.test.thalitest/.MainActivity t64} time:311688
,07-05 15:08:36.198   754   887 D ViewRootImpl: #3 mView = null
,07-05 15:08:36.198  7257  7257 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 15:08:36.198   293  4870 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
,07-05 15:08:36.198   293   357 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
,07-05 15:08:36.198   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbefeb3a4
,07-05 15:08:36.208  7257  7257 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@55166f time:311708
,07-05 15:08:36.258  7257  7309 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-05 15:08:36.258  7257  7309 D libEGL  : eglInitialize EGLDisplay = 0x9c1ec3ec
,07-05 15:08:36.308  7257  7257 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7257
,07-05 15:08:36.548  7257  7257 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 15:08:36.618   754  3487 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-05 15:08:36.718  7257  7318 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1683490512
,07-05 15:08:36.718  7257  7318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 15:08:36.718  7257  7318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 15:08:36.718  7257  7318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 15:08:36.718  7257  7318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 15:08:36.718  7257  7318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 15:08:36.718  7257  7318 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebd0475 added. We now have 1 listener(s)
,07-05 15:08:36.728  7257  7318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,07-05 15:08:36.728  7257  7318 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
07-05 15:08:36.728  7257  7318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 15:08:36.728  7257  7318 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 15:08:36.728  7257  7318 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0f3a98 added. We now have 1 listener(s)
,07-05 15:08:36.728  7257  7318 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 15:08:36.738  7257  7318 D BluetoothAdapter: STATE_ON
,07-05 15:08:36.738  7257  7318 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 15:08:36.738  7257  7318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 15:08:36.738  7257  7318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 15:08:36.738  7257  7318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 15:08:36.738  7257  7318 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 15:08:36.748  7257  7318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 15:08:36.748  7257  7318 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,07-05 15:08:36.748  7257  7318 D BluetoothAdapter: STATE_ON
,07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:08:36.758  7257  7318 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 15:08:36.758  7257  7318 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 15:08:36.758  7257  7318 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 15:08:36.758  7257  7257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 15:08:36.758  7257  7318 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 15:08:36.758  7257  7257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 15:08:36.788  7257  7257 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 15:08:37.018  1445  1445 D Recents : onTaskStackChanged
,07-05 15:08:37.028  1445  1445 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-05 15:08:37.798  7257  7266 I art     : Background partial concurrent mark sweep GC freed 52521(5MB) AllocSpace objects, 10(1444KB) LOS objects, 45% free, 19MB/35MB, paused 415us total 124.150ms
,07-05 15:08:37.838  7257  7319 W jxcore-log: Initializing JXcore engine
,07-05 15:08:37.838  7257  7319 W jxcore-log: JXcore engine is ready
,07-05 15:08:37.888  2430  2430 E audit   : type=1400 msg=audit(1467724117.888:288): avc:  denied  { ioctl } for  pid=7319 comm="Thread-979" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 15:08:37.888  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-05 15:08:37.888  2430  2430 E audit   : type=1300 msg=audit(1467724117.888:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9b17f3c8 items=0 ppid=364 ppcomm=main pid=7319 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-979" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 15:08:37.888  2430  2430 E audit   : type=1327 msg=audit(1467724117.888:288): proctitle="com.test.thalitest"
07-05 15:08:37.888  2430  2430 E audit   : type=1320 msg=audit(1467724117.888:288): 
,07-05 15:08:37.888  2430  2430 E audit   : type=1400 msg=audit(1467724117.888:289): avc:  denied  { ioctl } for  pid=7319 comm="Thread-979" path="socket:[45235]" dev="sockfs" ino=45235 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 15:08:37.888  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:08:37.888  2430  2430 E audit   : type=1300 msg=audit(1467724117.888:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=1 a3=9b17f3c8 items=0 ppid=364 ppcomm=main pid=7319 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-979" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,07-05 15:08:37.888  2430  2430 E audit   : type=1327 msg=audit(1467724117.888:289): proctitle="com.test.thalitest"
07-05 15:08:37.888  2430  2430 E audit   : type=1320 msg=audit(1467724117.888:289): 
,07-05 15:08:37.898  7257  7319 W jxcore-log: Starting JXcore engine
,07-05 15:08:37.978  7257  7319 W jxcore-log: Platform android
07-05 15:08:37.978  7257  7319 W jxcore-log: 
07-05 15:08:37.978  7257  7319 W jxcore-log: Process ARCH arm
07-05 15:08:37.978  7257  7319 W jxcore-log: 
,07-05 15:08:38.168  7257  7319 I jxcore-log: JXcore Cordova bridge is ready!
07-05 15:08:38.168  7257  7319 I jxcore-log: 
,07-05 15:08:38.168  7257  7319 W jxcore-log: JXcore engine is started
,07-05 15:08:38.168  7257  7318 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 15:08:38.168  7257  7257 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 15:08:38.378   754  1360 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,07-05 15:08:40.188   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:08:40.188   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:08:40.188   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:08:40.288   754  1228 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:08:40.288   754  1228 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:08:40.288   754  1227 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:08:40.288   754  1228 I TLC_TIMA_PKM_initialize: initializing...
07-05 15:08:40.288   754  1228 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-05 15:08:40.288   754  1228 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-05 15:08:40.288   754  1228 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-05 15:08:40.288   754  1228 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-05 15:08:40.288   754  1228 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
07-05 15:08:40.288   754  1228 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-05 15:08:40.288   754  1228 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-05 15:08:40.288   754  1228 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 15:08:40.288   754  1228 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 15:08:40.328   754  1228 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 15:08:40.328   754  1228 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 15:08:40.338   754  1228 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 15:08:41.658   754  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:08:42.518   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-05 15:08:42.518   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:08:42.528   754  1228 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:08:42.528   754  1228 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:08:45.398   754   916 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 15:08:45.428   754   916 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-05 15:08:45.648   754  3486 D SSRM:n  : SIOP:: AP = 350, PST = 315, CUR = 450, LCD = 0
,07-05 15:08:48.318  7257  7319 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 15:08:48.318  7257  7319 I jxcore-log: 
,07-05 15:08:48.318  7257  7319 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 15:08:48.318  7257  7319 I jxcore-log: 
,07-05 15:08:48.328  7257  7319 D BluetoothAdapter: STATE_ON
,07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:08:48.328  7257  7319 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 15:08:48.328  7257  7319 D BluetoothAdapter: STATE_ON
,07-05 15:08:48.328  7257  7319 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 15:08:48.338  7257  7319 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 15:08:48.338  7257  7319 I jxcore-log: 
,07-05 15:08:48.338  7257  7319 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 15:08:48.338  7257  7319 I jxcore-log: 
,07-05 15:08:48.718  7257  7319 I jxcore-log: Unit Test app is loaded
07-05 15:08:48.718  7257  7319 I jxcore-log: 
,07-05 15:08:48.718  7257  7319 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 15:08:48.718  7257  7319 I jxcore-log: 
,07-05 15:08:48.728  7257  7319 I jxcore-log: My device name is: samsung-SM-G900F
07-05 15:08:48.728  7257  7319 I jxcore-log: 
,07-05 15:08:48.728  7257  7257 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 15:08:48.728  7257  7319 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 15:08:48.728  7257  7319 I jxcore-log: 
,07-05 15:08:52.608  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 15:08:52.608  7257  7319 I jxcore-log: 
,07-05 15:08:53.018  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 15:08:53.018  7257  7319 I jxcore-log: 
,07-05 15:08:53.048  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 15:08:53.048  7257  7319 I jxcore-log: 
,07-05 15:08:53.048  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 15:08:53.048  7257  7319 I jxcore-log: 
,07-05 15:08:53.068  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 15:08:53.068  7257  7319 I jxcore-log: 
,07-05 15:08:53.068  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 15:08:53.068  7257  7319 I jxcore-log: 
,07-05 15:08:55.068  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 15:08:55.068  7257  7319 I jxcore-log: 
,07-05 15:08:55.078  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 15:08:55.078  7257  7319 I jxcore-log: 
,07-05 15:08:55.088  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 15:08:55.088  7257  7319 I jxcore-log: 
,07-05 15:08:55.238  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 15:08:55.238  7257  7319 I jxcore-log: 
,07-05 15:08:55.328  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 15:08:55.328  7257  7319 I jxcore-log: 
,07-05 15:08:55.378  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 15:08:55.378  7257  7319 I jxcore-log: 
,07-05 15:08:55.388  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 15:08:55.388  7257  7319 I jxcore-log: 
,07-05 15:08:55.578  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 15:08:55.578  7257  7319 I jxcore-log: 
,07-05 15:08:55.598  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 15:08:55.598  7257  7319 I jxcore-log: 
,07-05 15:08:55.608  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 15:08:55.608  7257  7319 I jxcore-log: 
,07-05 15:08:55.608  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 15:08:55.608  7257  7319 I jxcore-log: 
,07-05 15:08:55.618   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:08:55.628  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 15:08:55.628  7257  7319 I jxcore-log: 
,07-05 15:08:55.648  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 15:08:55.648  7257  7319 I jxcore-log: 
,07-05 15:08:55.698   754  3486 D SSRM:n  : SIOP:: AP = 370, PST = 320, CUR = 450, LCD = 0
,07-05 15:08:55.738  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 15:08:55.738  7257  7319 I jxcore-log: 
,07-05 15:08:55.738  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 15:08:55.738  7257  7319 I jxcore-log: 
,07-05 15:08:55.768  7257  7319 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 15:08:55.768  7257  7319 I jxcore-log: 
,07-05 15:08:55.778  7257  7319 D BluetoothAdapter: STATE_ON
,07-05 15:08:55.778  7257  7319 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-05 15:08:55.778  7257  7319 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-05 15:08:55.778  7257  7319 I jxcore-log: 
,07-05 15:08:55.848   754  1614 E Watchdog: !@Sync 10 [07-05 15:08:55.867]
,07-05 15:08:56.618   754  1234 V AlarmManager: Expired Alarm result :4
,07-05 15:08:56.648  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:08:56.658  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 15:08:56.658  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:08:56.698  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:08:56.708  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:08:56.728  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.728  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.728  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.738  1553  1553 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 15:08:56.738  1553  1553 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 15:08:56.758  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.768  1553  1553 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-05 15:08:56.768  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.768  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.778  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:56.828  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:08:57.018  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:08:58.078   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:08:58.078   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:08:58.078   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:08:59.988   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:09:00.638  1553  1553 I wpa_supplicant: nl80211: Received scan results (11 BSSes)
,07-05 15:09:00.648   317  1145 D Netd    : Iface wlan0 link up
,07-05 15:09:00.648  1553  1553 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-05 15:09:00.658   754   833 D Tethering: interfaceLinkStateChanged wlan0, true
,07-05 15:09:00.678   754   833 D Tethering: interfaceStatusChanged wlan0, true
,07-05 15:09:00.688   754  1319 D WifiP2pService: InactiveState{ what=147461 }
,07-05 15:09:00.688   754  1319 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-05 15:09:00.688   754  1319 D WifiP2pService: DefaultState{ what=147461 }
,07-05 15:09:00.738   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9bb4353 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{74b67de 1376:com.android.systemui/u0a58}
,07-05 15:09:04.198   754  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:09:04.198   754  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:09:04.198   754  1649 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-05 15:09:04.198   754  1649 D BatteryService: stay LED for fully charged
,07-05 15:09:04.198   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:09:04.198   754   754 I MotionRecognitionService: Plugged
,07-05 15:09:04.198   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:09:04.198   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:09:04.208   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:09:04.208  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:09:04.208  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:09:04.208  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:09:04.218  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:09:04.218  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:09:04.228  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:09:04.238  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:09:04.238  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:09:05.748   754  3486 D SSRM:n  : SIOP:: AP = 330, PST = 322, CUR = 450, LCD = 0
,07-05 15:09:15.618   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:09:15.808   754  3486 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450, LCD = 0
,07-05 15:09:16.308   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:09:16.308   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:09:16.308   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:09:16.808   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:09:16.808   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:09:16.808   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:09:25.858   754  1614 E Watchdog: !@Sync 11 [07-05 15:09:25.870]
,07-05 15:09:25.888   754  3486 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450, LCD = 0
,07-05 15:09:31.868   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:09:31.868   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:09:31.868   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:09:32.658  1967  1967 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:09:32.698  1967  1967 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:09:32.698  1967  1967 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:09:32.768  5973  6015 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 15:09:32.768  5973  6015 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 15:09:32.768   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:09:32.768   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:09:32.768   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:09:32.788   317  1148 D EnterpriseController: netId is 0
07-05 15:09:32.788   317  1148 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-05 15:09:34.218   754  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:09:34.218   754  1778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:09:34.218   754  1778 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:09:34.228   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:09:34.238   754   754 I MotionRecognitionService: Plugged
,07-05 15:09:34.238   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:09:34.248   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:09:34.248   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:09:34.248   754  1778 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:09:34.248   754  1778 D BatteryService: stay LED for fully charged
,07-05 15:09:34.258  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:09:34.258  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:09:34.268  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:09:34.298  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:09:34.298  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:09:34.298  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:09:34.298  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:09:34.298  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:09:35.618   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:09:35.948   754  3486 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450, LCD = 0
,07-05 15:09:46.008   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450, LCD = 0
,07-05 15:09:55.268   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:09:55.268   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:09:55.268   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:09:55.638   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:09:55.858   754  1614 E Watchdog: !@Sync 12 [07-05 15:09:55.874]
,07-05 15:09:56.058   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450, LCD = 0
,07-05 15:09:57.128  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:10:04.288   754  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:10:04.298   754  1778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:10:04.298   754  1778 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:10:04.298   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:10:04.308   754   754 I MotionRecognitionService: Plugged
,07-05 15:10:04.318   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:10:04.318   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:10:04.318   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:10:04.328   754  1778 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:10:04.328   754  1778 D BatteryService: stay LED for fully charged
,07-05 15:10:04.348  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:10:04.348  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:10:04.348  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:10:04.358  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:10:04.358  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:10:04.368  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:10:04.368  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:10:04.368  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:10:06.118   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450, LCD = 0
,07-05 15:10:15.628   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:10:16.178   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450, LCD = 0
,07-05 15:10:25.868   754  1614 E Watchdog: !@Sync 13 [07-05 15:10:25.878]
,07-05 15:10:26.228   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 321, CUR = 450, LCD = 0
,07-05 15:10:34.368   754  2553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:10:34.368   754  2553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:10:34.368   754  2553 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:10:34.378   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:10:34.388   754   754 I MotionRecognitionService: Plugged
,07-05 15:10:34.388   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:10:34.388   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:10:34.398   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:10:34.398   754  2553 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:10:34.398   754  2553 D BatteryService: stay LED for fully charged
,07-05 15:10:34.408  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:10:34.418  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:10:34.418  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:10:34.448  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:10:34.448  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:10:34.448  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:10:34.448  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:10:34.448  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:10:35.638   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:10:35.988   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:10:35.988   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:10:35.988   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:10:36.298   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450, LCD = 0
,07-05 15:10:46.358   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450, LCD = 0
,07-05 15:10:55.648   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:10:55.868   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:10:55.868   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:10:55.868   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:10:55.868   754  1614 E Watchdog: !@Sync 14 [07-05 15:10:55.886]
,07-05 15:10:56.418   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450, LCD = 0
,07-05 15:10:57.158  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:10:57.298  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 130ms lastUpdatedAfter : 180378ms
,07-05 15:11:04.438   754  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:11:06.488   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450, LCD = 0
,07-05 15:11:15.638   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:11:16.548   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:11:25.888   754  1614 E Watchdog: !@Sync 15 [07-05 15:11:25.890]
,07-05 15:11:26.608   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:11:30.168   373   373 I bootchecker: bootchecker wake up!!
,07-05 15:11:34.508   754  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:11:34.518   754  1778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:11:34.518   754  1778 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:11:34.518   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:11:34.538   754   754 I MotionRecognitionService: Plugged
,07-05 15:11:34.538   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:11:34.538   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:11:34.538   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:11:34.548   754  1778 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
07-05 15:11:34.548   754  1778 D BatteryService: stay LED for fully charged
,07-05 15:11:34.548  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:11:34.548  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:11:34.548  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:11:34.568  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:11:34.568  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:11:34.578  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:11:34.578  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:11:34.578  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:11:35.648   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:11:36.658   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:11:46.718   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:11:55.658   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:11:55.878   754  1614 E Watchdog: !@Sync 16 [07-05 15:11:55.894]
,07-05 15:11:56.778   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:11:57.408  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:11:59.988   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:11:59.988   754  1234 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=515480 batch.start=679264
,07-05 15:12:00.008  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:12:00.008  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 15:12:00.028  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:12:00.068  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:12:00.078  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:12:00.078  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.088  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.088  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.088  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.088  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.088  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.088  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:00.148  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:12:04.588   754  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:12:06.838   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:12:15.658   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:12:16.888   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450, LCD = 0
,07-05 15:12:25.888   754  1614 E Watchdog: !@Sync 17 [07-05 15:12:25.900]
,07-05 15:12:26.948   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450, LCD = 0
,07-05 15:12:34.668   754  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:12:34.668   754  1407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:12:34.678   754  1407 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:12:34.678   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:12:34.688   754   754 I MotionRecognitionService: Plugged
,07-05 15:12:34.688   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:12:34.698   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:12:34.698   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:12:34.698   754  1407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:12:34.698   754  1407 D BatteryService: stay LED for fully charged
,07-05 15:12:34.718  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:12:34.718  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:12:34.718  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:12:34.748  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:12:34.748  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:12:34.748  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:12:34.748  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:12:34.748  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:12:35.668   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:12:37.018   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-05 15:12:47.078   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450, LCD = 0
,07-05 15:12:55.678   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:12:55.888   754  1614 E Watchdog: !@Sync 18 [07-05 15:12:55.905]
,07-05 15:12:57.138   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-05 15:12:57.508  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:12:59.988   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:13:04.748   754  2551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:13:04.758   754  2551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:13:04.758   754  2551 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:13:04.758   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:13:04.778   754   754 I MotionRecognitionService: Plugged
,07-05 15:13:04.778   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:13:04.778   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:13:04.788   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:13:04.788   754  2551 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,07-05 15:13:04.798   754  2551 D BatteryService: stay LED for fully charged
,07-05 15:13:04.798  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:13:04.798  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:13:04.798  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:13:04.808  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:13:04.818  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:13:04.818  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:13:04.828  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:13:04.828  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:13:07.188   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,07-05 15:13:15.668   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:13:17.248   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,07-05 15:13:25.898   754  1614 E Watchdog: !@Sync 19 [07-05 15:13:25.909]
,07-05 15:13:27.308   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:13:33.468   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:13:33.468   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:13:33.468   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:13:34.828   754  1566 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:13:34.838   754  1566 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:13:34.838   754  1566 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:13:34.838   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:13:34.858   754   754 I MotionRecognitionService: Plugged
,07-05 15:13:34.858   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:13:34.858   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:13:34.868   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:13:34.868   754  1566 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 15:13:34.868   754  1566 D BatteryService: stay LED for fully charged
,07-05 15:13:34.888  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:13:34.888  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:13:34.898  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:13:34.908  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:13:34.908  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:13:34.918  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:13:34.918  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:13:34.918  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:13:35.688   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:13:37.368   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:13:40.288   754  1228 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:13:40.288   754  1228 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:13:40.288   754  1227 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:13:41.768   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:13:41.768   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:13:41.778   754  1228 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:13:41.778   754  1228 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:13:47.428   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:13:48.508   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:13:48.508   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:13:48.508   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:13:55.688   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:13:55.908   754  1614 E Watchdog: !@Sync 20 [07-05 15:13:55.913]
,07-05 15:13:57.478   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:13:57.538  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:13:57.658  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 112ms lastUpdatedAfter : 180361ms
,07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.498   754   821 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.508   754   821 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.518   754   821 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:14:00.528   754   821 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:14:00.628   754   887 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-05 15:14:00.628   754   887 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-05 15:14:04.918   754  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:14:04.928   754  1406 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:14:04.928   754  1406 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:14:04.928   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:14:04.938   754   754 I MotionRecognitionService: Plugged
,07-05 15:14:04.948   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:14:04.948   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:14:04.948   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:14:04.958   754  1406 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 15:14:04.958   754  1406 D BatteryService: stay LED for fully charged
,07-05 15:14:04.968  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:14:04.968  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:14:04.968  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:14:04.998  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:14:04.998  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:14:04.998  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:14:04.998  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:14:04.998  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:14:07.528   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:14:15.688   754  3515 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:14:17.588   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:14:25.908   754  1614 E Watchdog: !@Sync 21 [07-05 15:14:25.917]
,07-05 15:14:27.638   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:14:33.018   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:14:33.018   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:14:33.018   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:14:33.038   754  2553 I ActivityManager: Killing 4656:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 615s, lastActivityTime 615s
,07-05 15:14:33.048   754  2553 I ActivityManager: Killing 3914:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 620s
,07-05 15:14:33.118   292   292 I ServiceManager: service 'AtCmdFwd' died
,07-05 15:14:33.118   378  4861 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-05 15:14:33.128   378  4861 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 15:14:33.128   754  1649 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-05 15:14:33.128   754  1649 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-05 15:14:33.128   754  1649 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-05 15:14:33.158   754  1778 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-05 15:14:33.158   754  1778 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-05 15:14:33.158   754  1778 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10968ms
,07-05 15:14:34.128   378  4861 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 15:14:34.168   754   827 I ActivityManager: Start proc 7391:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-05 15:14:34.178  7391  7391 E Zygote  : v2
,07-05 15:14:34.178  7391  7391 I libpersona: KNOX_SDCARD checking this for 1000
07-05 15:14:34.178  7391  7391 I libpersona: KNOX_SDCARD not a persona
,07-05 15:14:34.188  7391  7391 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:14:34.188  7391  7391 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:14:34.188  7391  7391 E Zygote  : accessInfo : 0
,07-05 15:14:34.228  7391  7391 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:14:34.228  7391  7391 D ActivityThread: Added TimaKeyStore provider
,07-05 15:14:34.248  7391  7391 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-05 15:14:34.268  7391  7391 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-05 15:14:34.268  7391  7391 D AtFwdService: onCreate method
,07-05 15:14:34.268  7391  7391 I AtFwdService: Instantiate AtCmdFwd Service
,07-05 15:14:34.288  7391  7403 D AtCkpdCmdHandler: De-queing command
,07-05 15:14:34.988   754  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:14:34.998   754  1407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:14:34.998   754  1407 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:14:34.998   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:14:35.008   754   754 I MotionRecognitionService: Plugged
,07-05 15:14:35.018   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:14:35.018   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:14:35.018   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:14:35.018   754  1407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:14:35.028   754  1407 D BatteryService: stay LED for fully charged
,07-05 15:14:35.038  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:14:35.048  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:14:35.048  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:14:35.058  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:14:35.058  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:14:35.068  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:14:35.068  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:14:35.068  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:14:37.698   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:14:43.778   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:14:44.198  7405  7405 E Zygote  : v2
,07-05 15:14:44.198  7405  7405 I libpersona: KNOX_SDCARD checking this for 10026
07-05 15:14:44.198  7405  7405 I libpersona: KNOX_SDCARD not a persona
,07-05 15:14:44.208   754   827 I ActivityManager: Start proc 7405:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-05 15:14:44.208  7405  7405 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:14:44.208  7405  7405 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:14:44.208  7405  7405 E Zygote  : accessInfo : 0
,07-05 15:14:44.208  7405  7405 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-05 15:14:44.248  7405  7405 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:14:44.248  7405  7405 D ActivityThread: Added TimaKeyStore provider
,07-05 15:14:44.258   754  2553 I ActivityManager: Killing 1518:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 600s, lastActivityTime 600s
,07-05 15:14:44.268   754  2553 I ActivityManager: Killing 3820:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 631s, lastActivityTime 601s
,07-05 15:14:44.298   754  1777 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
07-05 15:14:44.298   754  1777 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-05 15:14:44.298  7405  7405 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-05 15:14:44.308   754  2553 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
,07-05 15:14:44.308   754  2553 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-05 15:14:44.308   754  2553 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-05 15:14:44.318  7405  7405 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-05 15:14:44.328  7405  7405 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-05 15:14:44.328  7405  7405 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-05 15:14:45.388   754   827 I ActivityManager: Start proc 7435:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
,07-05 15:14:45.388   754  1318 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-05 15:14:45.398  7435  7435 E Zygote  : v2
,07-05 15:14:45.398  7435  7435 I libpersona: KNOX_SDCARD checking this for 10181
07-05 15:14:45.398  7435  7435 I libpersona: KNOX_SDCARD not a persona
,07-05 15:14:45.398  7435  7435 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:14:45.398  7435  7435 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:14:45.398  7435  7435 E Zygote  : accessInfo : 0
,07-05 15:14:45.398  7435  7435 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-05 15:14:45.448  7435  7435 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:14:45.448  7435  7435 D ActivityThread: Added TimaKeyStore provider
,07-05 15:14:45.468   754  1318 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 15:14:45.468  7435  7435 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-05 15:14:45.498  7435  7435 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-05 15:14:45.528  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-05 15:14:45.538  7435  7435 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:14:45.538   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6e624f2 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{46ba743 7435:com.sec.android.daemonapp/u0a181}
,07-05 15:14:45.548  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-05 15:14:45.548  7435  7435 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:14:45.548  7435  7435 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-05 15:14:45.548  7435  7435 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:14:45.548  7435  7435 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-05 15:14:45.558  7435  7435 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:14:45.568  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:14:45.568  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 15:14:45.568  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-05 15:14:45.578  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:14:45.578  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:14:45.578  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-05 15:14:45.578  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 15:14:45.598  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-05 15:14:45.608  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:14:45.608  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:14:45.608  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-05 15:14:45.608  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 15:14:45.618  7435  7435 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:14:45.618  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:14:45.618  7435  7435 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 15:14:45.618  7435  7435 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:14:45.618  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:14:45.618  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 15:14:45.618  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-05 15:14:45.618  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 15:14:45.618  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-05 15:14:45.618  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-05 15:14:45.618  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.628  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:14:45.628   754  1762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f17749f u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{46ba743 7435:com.sec.android.daemonapp/u0a181}
,07-05 15:14:45.638  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:14:45.638  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:14:45.638  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:14:45.638  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:14:45.648  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:14:45.648  7435  7435 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:14:45.648  7435  7435 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:14:45.648  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.648  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:14:45.658   754  2551 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{47f49ec u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{46ba743 7435:com.sec.android.daemonapp/u0a181}
,07-05 15:14:45.658  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:14:45.658  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:14:45.658  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:14:45.668  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:14:45.668  7435  7435 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:14:45.668  7435  7435 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:14:45.668  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:14:45.668  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:14:45.678  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.678  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:14:45.678   754   768 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4091b5 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{46ba743 7435:com.sec.android.daemonapp/u0a181}
,07-05 15:14:45.688  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:14:45.688  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:14:45.688  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:14:45.688  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.688  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:14:45.688  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:14:45.688  7435  7435 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 15:14:45.688  7435  7435 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:14:45.688  7435  7435 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:14:45.688  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:14:45.698  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:14:45.698  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 15:14:45.698  7435  7435 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:14:45.698  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:14:45.698  7435  7435 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:14:45.698  7435  7435 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:14:47.758   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:14:48.188   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:14:48.188   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:14:48.188   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:14:55.908   754  1614 E Watchdog: !@Sync 22 [07-05 15:14:55.924]
,07-05 15:14:57.668  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:14:57.808   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:15:05.068   754  2551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:15:07.858   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:15:17.918   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:15:25.918   754  1614 E Watchdog: !@Sync 23 [07-05 15:15:25.928]
,07-05 15:15:27.968   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:15:35.138   754  2551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:15:35.148   754  2551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:15:35.148   754  2551 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:15:35.158   754  2551 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 12ms
,07-05 15:15:35.158   754  2551 D BatteryService: stay LED for fully charged
,07-05 15:15:35.168   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:15:35.188   754   754 I MotionRecognitionService: Plugged
,07-05 15:15:35.188   754   754 D MotionRecognitionService:   cableConnection= 1
07-05 15:15:35.188   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:15:35.188  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:15:35.188  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:15:35.188  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 15:15:35.188   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:15:35.208  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:15:35.208  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:15:35.218  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:15:35.218  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:15:35.218  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:15:38.018   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:15:48.078   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:15:55.098   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:15:55.928   754  1614 E Watchdog: !@Sync 24 [07-05 15:15:55.932]
,07-05 15:15:57.758  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:15:58.128   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:16:05.218   754  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:16:05.228   754  1407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:16:05.228   754  1407 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:16:05.228   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:16:05.248   754   754 I MotionRecognitionService: Plugged
,07-05 15:16:05.248   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:16:05.248   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:16:05.248   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:16:05.258   754  1407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 15:16:05.258   754  1407 D BatteryService: stay LED for fully charged
,07-05 15:16:05.278  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:16:05.278  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:16:05.288  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:16:05.298  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:16:05.298  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:16:05.308  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:16:05.308  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:16:05.308  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:16:08.188   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:16:18.238   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:16:25.928   754  1614 E Watchdog: !@Sync 25 [07-05 15:16:25.936]
,07-05 15:16:28.288   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:16:35.288   754  1779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:16:35.288   754  1779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:16:35.288   754  1779 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:16:35.298   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:16:35.308   754   754 I MotionRecognitionService: Plugged
,07-05 15:16:35.308   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:16:35.308   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:16:35.318   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:16:35.318   754  1779 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:16:35.328   754  1779 D BatteryService: stay LED for fully charged
,07-05 15:16:35.338  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:16:35.338  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:16:35.338  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:16:35.348  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:16:35.348  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:16:35.358  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:16:35.358  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:16:35.358  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:16:38.338   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:16:48.398   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:16:55.938   754  1614 E Watchdog: !@Sync 26 [07-05 15:16:55.942]
,07-05 15:16:57.808  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:16:57.938  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 118ms lastUpdatedAfter : 180276ms
,07-05 15:16:58.448   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:17:00.668   754  2509 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 15:17:00.668   754  2509 V MARsPolicyManager: updateSMDBValues
,07-05 15:17:00.668   754   885 E MARsDBManager: updateDBAll : begin --size 1
,07-05 15:17:00.698   754   885 I ActivityManager: Killing 1891:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 783s, lastActivityTime 701s
,07-05 15:17:00.748   754   885 E MARsDBManager: updateDBAll : end
,07-05 15:17:00.758   754   885 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-05 15:17:00.788   754  1291 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-05 15:17:00.788   754  1291 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 15:17:00.788   754  1291 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
07-05 15:17:00.788   754  1291 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,07-05 15:17:00.788   754  1291 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 11000ms
,07-05 15:17:00.798  7000  7000 D HealthConsole: Service for HealthDataStore is disconnected
,07-05 15:17:00.828  7462  7462 E Zygote  : v2
,07-05 15:17:00.828  7462  7462 I libpersona: KNOX_SDCARD checking this for 10034
07-05 15:17:00.828  7462  7462 I libpersona: KNOX_SDCARD not a persona
,07-05 15:17:00.828  7462  7462 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:17:00.828  7462  7462 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:17:00.828  7462  7462 E Zygote  : accessInfo : 0
,07-05 15:17:00.828  7462  7462 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-05 15:17:00.828   754  1407 I ActivityManager: Start proc 7462:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,07-05 15:17:00.868  7462  7462 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:17:00.868  7462  7462 D ActivityThread: Added TimaKeyStore provider
,07-05 15:17:00.888  7462  7462 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-05 15:17:00.908  7462  7462 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-05 15:17:00.918  7462  7462 I MultiDex: VM with version 2.1.0 has multidex support
07-05 15:17:00.918  7462  7462 I MultiDex: install
07-05 15:17:00.918  7462  7462 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 15:17:00.918  7462  7462 I MultiDex: install
07-05 15:17:00.918  7462  7462 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 15:17:01.008   754  2553 I ActivityManager: Start proc 7485:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,07-05 15:17:01.008  7485  7485 E Zygote  : v2
,07-05 15:17:01.008  7485  7485 I libpersona: KNOX_SDCARD checking this for 10016
07-05 15:17:01.008  7485  7485 I libpersona: KNOX_SDCARD not a persona
,07-05 15:17:01.008  7485  7485 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:17:01.008  7485  7485 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:17:01.018  7485  7485 E Zygote  : accessInfo : 0
,07-05 15:17:01.018  7485  7485 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-05 15:17:01.038  7485  7485 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:17:01.038  7485  7485 D ActivityThread: Added TimaKeyStore provider
,07-05 15:17:01.058  7485  7485 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-05 15:17:01.098  7462  7462 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
07-05 15:17:01.098  7462  7462 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 15:17:01.118  1376  1376 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-05 15:17:01.118   754  2551 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-05 15:17:01.128   754  1291 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-05 15:17:01.128   754  1406 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-05 15:17:01.128   754  1649 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-05 15:17:01.148  1376  1376 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{a62ac60 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
07-05 15:17:01.148  1376  1376 D AdaptiveEventManager: M updateContainers()
07-05 15:17:01.148  1376  1376 D AdaptiveEventContainerSmall: C updatePedoContainer()
07-05 15:17:01.148  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-05 15:17:01.148  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-05 15:17:01.168  7462  7462 I Health.HealthService: HealthService: onCreate() start (7462)
,07-05 15:17:01.268  7000  7000 D HealthDataStore: Service for HealthDataStore is connected
,07-05 15:17:01.268  7000  7000 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 15:17:01.278   754  1778 I ActivityManager: Killing 6290:com.android.email/u0a162 (adj 15): DHA:empty #37
,07-05 15:17:01.308  7000  7000 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 15:17:01.308  7000  7000 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 15:17:01.368   754  1407 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,07-05 15:17:01.378  7462  7462 D HealthDataStore: Service for HealthDataStore is connected
,07-05 15:17:01.378  7462  7462 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 15:17:01.378  7462  7462 D HealthConsole: Service for HealthDataConsole is connected
,07-05 15:17:01.378  7462  7462 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 15:17:01.388  7462  7462 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 15:17:01.518  7462  7505 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-05 15:17:01.548  7462  7523 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-05 15:17:01.598  7485  7496 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-05 15:17:01.618   395   395 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7485
07-05 15:17:01.618   395   395 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-05 15:17:01.798  7485  7496 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-05 15:17:01.838  7462  7523 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-05 15:17:01.948  7462  7523 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-05 15:17:01.948  7462  7523 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 15:17:02.118   395   395 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-05 15:17:02.158  7485  7496 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-05 15:17:02.158  7485  7496 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-05 15:17:02.158  7485  7496 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-05 15:17:05.358   754  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:17:08.508   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450, LCD = 0
,07-05 15:17:18.568   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:17:25.928   754  1614 E Watchdog: !@Sync 27 [07-05 15:17:25.946]
,07-05 15:17:28.618   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:17:35.428   754  2553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:17:38.678   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:17:48.738   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:17:55.948   754  1614 E Watchdog: !@Sync 28 [07-05 15:17:55.951]
,07-05 15:17:57.948  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:17:58.788   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:18:05.498   754  2553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:18:05.508   754  2553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:18:05.508   754  2553 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:18:05.508   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:18:05.528   754   754 I MotionRecognitionService: Plugged
,07-05 15:18:05.528   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:18:05.528   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:18:05.538   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:18:05.538   754  2553 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 40ms
,07-05 15:18:05.548   754  2553 D BatteryService: stay LED for fully charged
,07-05 15:18:05.558  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:18:05.568  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:18:05.568  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:18:05.578  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:18:05.578  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:18:05.588  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:18:05.588  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:18:05.588  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:18:08.848   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:18:18.898   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:18:25.948   754  1614 E Watchdog: !@Sync 29 [07-05 15:18:25.956]
,07-05 15:18:28.958   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:18:35.568   754  1779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:18:35.578   754  1779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:18:35.578   754  1779 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:18:35.578   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:18:35.588   754   754 I MotionRecognitionService: Plugged
,07-05 15:18:35.598   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:18:35.598   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:18:35.598   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:18:35.608   754  1779 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-05 15:18:35.608   754  1779 D BatteryService: stay LED for fully charged
,07-05 15:18:35.618  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:18:35.618  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:18:35.618  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:18:35.628  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:18:35.628  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:18:35.638  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:18:35.638  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:18:35.648  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:18:39.018   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:18:40.278   754  1228 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:18:40.288   754  1227 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:18:40.288   754  1228 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:18:43.698   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:18:43.698   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:18:43.708   754  1228 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:18:43.718   754  1228 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:18:49.068   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:18:55.958   754  1614 E Watchdog: !@Sync 30 [07-05 15:18:55.962]
,07-05 15:18:57.988  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:18:59.128   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:02.678   754  1234 V AlarmManager: Expired Alarm result :4
,07-05 15:19:02.718  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:19:02.718  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 15:19:02.718  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:19:02.748  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:19:02.758  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:19:02.778  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.778  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.778   754   827 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-05 15:19:02.798  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.798  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.818  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.818  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.818  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.828   754   754 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-05 15:19:02.828   754   754 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:19:02.838   754   754 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 15:19:02.878  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:19:02.898   754   754 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-05 15:19:02.908  2418  2571 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-05 15:19:02.908  2418  2571 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 15:19:02.908  2418  2571 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-05 15:19:02.908  2418  2571 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-05 15:19:02.918  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.918  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:19:02.918  2418  2602 D bt_upio : upio_start_stop_timer : timer_settime success
07-05 15:19:02.918  2418  2602 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.928  2418  2602 D bt_vendor: op for 7
,07-05 15:19:02.928  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.928  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.938  1376  1393 I art     : Background sticky concurrent mark sweep GC freed 30605(1855KB) AllocSpace objects, 0(0B) LOS objects, 4% free, 39MB/41MB, paused 529us total 120.627ms
07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938   754  1649 V AlarmManager:  remove PendingIntent] PendingIntent{1e2ee77: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938   754  2553 V AlarmManager:  remove PendingIntent] PendingIntent{951fae4: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.938  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.938  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.938  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.948  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.948  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.948  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.948  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.948  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.948  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.948  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.948  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.948  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.948   754  2551 V AlarmManager:  remove PendingIntent] PendingIntent{2b17b4d: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
07-05 15:19:02.948  2418  2602 D bt_vendor: op for 7
07-05 15:19:02.948  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:19:02.948  2418  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:19:02.948   754  1291 V AlarmManager:  remove PendingIntent] PendingIntent{3b12602: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.948   754   768 V AlarmManager:  remove PendingIntent] PendingIntent{38dfb13: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.958   754   767 V AlarmManager:  remove PendingIntent] PendingIntent{9a5e150: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.958   754  2553 V AlarmManager:  remove PendingIntent] PendingIntent{a277f49: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.958   754   768 V AlarmManager:  remove PendingIntent] PendingIntent{70fa04e: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.958   754  1762 V AlarmManager:  remove PendingIntent] PendingIntent{ed3356f: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.968   754  1566 V AlarmManager:  remove PendingIntent] PendingIntent{d0fc27c: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.968   754  1407 V AlarmManager:  remove PendingIntent] PendingIntent{4dfc705: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.968   754  1649 V AlarmManager:  remove PendingIntent] PendingIntent{4c9735a: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.968   754  1777 V AlarmManager:  remove PendingIntent] PendingIntent{c87b98b: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.978   754  1406 V AlarmManager:  remove PendingIntent] PendingIntent{cd48a68: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.978   754  1778 V AlarmManager:  remove PendingIntent] PendingIntent{d1ace81: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.978   754  2551 V AlarmManager:  remove PendingIntent] PendingIntent{81b6b26: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.978   754  1291 V AlarmManager:  remove PendingIntent] PendingIntent{3b66367: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.988   754  1779 V AlarmManager:  remove PendingIntent] PendingIntent{f9be514: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.988   754   767 V AlarmManager:  remove PendingIntent] PendingIntent{6a4d1bd: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.988   754  2553 V AlarmManager:  remove PendingIntent] PendingIntent{14313b2: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.988   754   768 V AlarmManager:  remove PendingIntent] PendingIntent{73bcf03: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.998   754  1762 V AlarmManager:  remove PendingIntent] PendingIntent{cdc3e80: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.998   754  1566 V AlarmManager:  remove PendingIntent] PendingIntent{bd1ccb9: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.998   754  1406 V AlarmManager:  remove PendingIntent] PendingIntent{4cab8fe: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.998   754  1779 V AlarmManager:  remove PendingIntent] PendingIntent{122585f: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:02.998   754  1762 V AlarmManager:  remove PendingIntent] PendingIntent{b06c2ac: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}},
07-05 15:19:03.008   754  1777 V AlarmManager:  remove PendingIntent] PendingIntent{e397b75: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.008   754  1291 V AlarmManager:  remove PendingIntent] PendingIntent{395670a: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.008   754   768 V AlarmManager:  remove PendingIntent] PendingIntent{7be1b7b: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.008   754  1649 V AlarmManager:  remove PendingIntent] PendingIntent{4735d98: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.018   754  2551 V AlarmManager:  remove PendingIntent] PendingIntent{73359f1: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.018   754  2553 V AlarmManager:  remove PendingIntent] PendingIntent{7aae9d6: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.018   754  1407 V AlarmManager:  remove PendingIntent] PendingIntent{888f457: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.018   754  1778 V AlarmManager:  remove PendingIntent] PendingIntent{f0cbb44: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.018   754   767 V AlarmManager:  remove PendingIntent] PendingIntent{412a42d: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.028   754  1566 V AlarmManager:  remove PendingIntent] PendingIntent{1c3cd62: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.028   754  1406 V AlarmManager:  remove PendingIntent] PendingIntent{4be7ef3: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.028   754  1779 V AlarmManager:  remove PendingIntent] PendingIntent{2bc47b0: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.028   754  1762 V AlarmManager:  remove PendingIntent] PendingIntent{a225629: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.028   754  1777 V AlarmManager:  remove PendingIntent] PendingIntent{3955dae: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:19:03.258   754  1217 E LightSensor: RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,07-05 15:19:03.258   754   897 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-05 15:19:03.258   754   897 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 15:19:03.268   754   897 D SensorManager: unregisterListener ::   
,07-05 15:19:03.268   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=6) maintains its priority right
,07-05 15:19:03.268   754   897 V AlarmManager:  remove PendingIntent] PendingIntent{7b06ee9: PendingIntentRecord{920676e android broadcastIntent}}
,07-05 15:19:03.728  2418  2800 D bt_upio : ..proc_btwrite_timeout..
,07-05 15:19:03.728  2418  2800 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 15:19:05.648   754  1779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:19:09.178   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:19.228   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:25.958   754  1614 E Watchdog: !@Sync 31 [07-05 15:19:25.967]
,07-05 15:19:29.288   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:35.708   754  1779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:19:35.718   754  1779 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:19:35.718   754  1779 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:19:35.718   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:19:35.728   754   754 I MotionRecognitionService: Plugged
,07-05 15:19:35.738   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:19:35.738   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:19:35.738   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:19:35.748   754  1779 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 15:19:35.748   754  1779 D BatteryService: stay LED for fully charged
,07-05 15:19:35.768  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:19:35.768  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:19:35.768  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:19:35.778  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:19:35.778  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:19:35.788  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:19:35.788  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:19:35.788  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:19:39.338   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:49.398   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:55.958   754  1614 E Watchdog: !@Sync 32 [07-05 15:19:55.972]
,07-05 15:19:58.078  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:19:58.218  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 122ms lastUpdatedAfter : 180278ms
,07-05 15:19:59.448   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:19:59.998   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:20:05.788   754  1777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:20:05.788   754  1777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:20:05.788   754  1777 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:20:05.798   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:20:05.808   754   754 I MotionRecognitionService: Plugged
,07-05 15:20:05.808   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:20:05.808   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:20:05.808   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:20:05.818   754  1777 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:20:05.818   754  1777 D BatteryService: stay LED for fully charged
,07-05 15:20:05.818  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:20:05.818  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:20:05.818  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:20:05.838  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:20:05.838  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:20:05.848  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:20:05.848  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:20:05.848  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:20:09.518   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:20:19.578   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:20:25.958   754  1614 E Watchdog: !@Sync 33 [07-05 15:20:25.976]
,07-05 15:20:29.638   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:20:35.848   754  1407 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:20:35.848   754  1407 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:20:35.848   754  1407 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:20:35.858   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:20:35.868   754   754 I MotionRecognitionService: Plugged
,07-05 15:20:35.868   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:20:35.868   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:20:35.878   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:20:35.878   754  1407 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 15:20:35.878   754  1407 D BatteryService: stay LED for fully charged
,07-05 15:20:35.898  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:20:35.898  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:20:35.898  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:20:35.928  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:20:35.928  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:20:35.938  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:20:35.938  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:20:35.938  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:20:39.728   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:20:39.808   754   764 I art     : Background sticky concurrent mark sweep GC freed 67864(8MB) AllocSpace objects, 365(7MB) LOS objects, 26% free, 43MB/58MB, paused 2.730ms total 147.272ms
,07-05 15:20:49.778   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:20:55.968   754  1614 E Watchdog: !@Sync 34 [07-05 15:20:55.980]
,07-05 15:20:58.298  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:20:59.838   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:21:05.908   754  1762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:21:05.918   754  1762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:21:05.918   754  1762 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:21:05.918   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:21:05.938   754   754 I MotionRecognitionService: Plugged
,07-05 15:21:05.938   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:21:05.938   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:21:05.938   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:21:05.948   754  1762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 15:21:05.948   754  1762 D BatteryService: stay LED for fully charged
,07-05 15:21:05.968  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:21:05.968  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:21:05.968  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:21:05.988  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:21:05.988  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:21:05.998  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:21:05.998  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:21:05.998  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:21:09.898   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:21:19.948   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:21:25.968   754  1614 E Watchdog: !@Sync 35 [07-05 15:21:25.985]
,07-05 15:21:30.008   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:21:35.978   754  1566 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:21:35.978   754  1566 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:21:35.988   754  1566 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:21:35.988   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:21:35.998   754   754 I MotionRecognitionService: Plugged
,07-05 15:21:35.998   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:21:36.008   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:21:36.008   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:21:36.008   754  1566 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:21:36.018   754  1566 D BatteryService: stay LED for fully charged
,07-05 15:21:36.018  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:21:36.018  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:21:36.018  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:21:36.028  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:21:36.038  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:21:36.048  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:21:36.048  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:21:36.048  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:21:40.058   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:21:50.118   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:21:55.978   754  1614 E Watchdog: !@Sync 36 [07-05 15:21:55.991]
,07-05 15:21:58.358  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:22:00.178   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:22:06.038   754   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:22:10.238   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:22:20.288   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:22:25.978   754  1614 E Watchdog: !@Sync 37 [07-05 15:22:25.995]
,07-05 15:22:30.348   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:22:36.108   754   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:22:40.418   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:22:50.478   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:22:55.988   754  1614 E Watchdog: !@Sync 38 [07-05 15:22:56.001]
,07-05 15:22:58.458  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:22:58.598  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 125ms lastUpdatedAfter : 180381ms
,07-05 15:23:00.528   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:23:06.178   754   768 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:23:06.178   754   768 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:23:06.188   754   768 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:23:06.188   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:23:06.198   754   754 I MotionRecognitionService: Plugged
,07-05 15:23:06.198   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:23:06.208   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:23:06.208   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:23:06.208   754   768 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:23:06.218   754   768 D BatteryService: stay LED for fully charged
,07-05 15:23:06.218  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:23:06.218  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:23:06.218  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:23:06.228  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:23:06.238  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:23:06.238  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:23:06.248  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:23:06.248  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:23:10.588   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:23:20.648   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:23:25.988   754  1614 E Watchdog: !@Sync 39 [07-05 15:23:26.005]
,07-05 15:23:30.708   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:23:36.238   754   767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:23:36.248   754   767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:23:36.248   754   767 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:23:36.258   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:23:36.268   754   754 I MotionRecognitionService: Plugged
,07-05 15:23:36.268   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:23:36.268   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:23:36.278   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:23:36.278   754   767 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-05 15:23:36.278   754   767 D BatteryService: stay LED for fully charged
,07-05 15:23:36.298  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:23:36.298  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:23:36.298  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:23:36.318  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:23:36.318  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:23:36.328  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:23:36.328  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:23:36.328  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:23:40.278   754  1228 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:23:40.288   754  1228 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:23:40.288   754  1227 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:23:40.768   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:23:41.788   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:23:41.788   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:23:41.798   754  1228 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:23:41.808   754  1228 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:23:50.818   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:23:52.338   754   821 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 15:23:55.998   754  1614 E Watchdog: !@Sync 40 [07-05 15:23:56.011]
,07-05 15:23:58.668  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:24:00.878   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:24:06.308   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:24:06.308   754  1291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:24:06.318   754  1291 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:24:06.318   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:24:06.328   754   754 I MotionRecognitionService: Plugged
,07-05 15:24:06.338   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:24:06.338   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:24:06.348   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:24:06.348   754  1291 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,07-05 15:24:06.348   754  1291 D BatteryService: stay LED for fully charged
,07-05 15:24:06.368  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:24:06.368  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:24:06.368  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:24:06.378  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:24:06.378  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:24:06.388  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:24:06.388  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:24:06.388  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:24:10.938   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:24:20.998   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:24:25.998   754  1614 E Watchdog: !@Sync 41 [07-05 15:24:26.015]
,07-05 15:24:31.048   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:24:36.378   754  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:24:41.108   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:24:51.158   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:24:56.008   754  1614 E Watchdog: !@Sync 42 [07-05 15:24:56.020]
,07-05 15:24:58.728  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:25:01.218   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:25:06.438   754  1778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:25:06.448   754  1778 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:25:06.448   754  1778 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:25:06.458   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:25:06.468   754   754 I MotionRecognitionService: Plugged
,07-05 15:25:06.468   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:25:06.468   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:25:06.478   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:25:06.478   754  1778 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:25:06.478   754  1778 D BatteryService: stay LED for fully charged
,07-05 15:25:06.488  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:25:06.488  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:25:06.488  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:25:06.518  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:25:06.518  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:25:06.528  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:25:06.528  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:25:06.528  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:25:11.268   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:25:21.328   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:25:26.018   754  1614 E Watchdog: !@Sync 43 [07-05 15:25:26.024]
,07-05 15:25:31.378   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:25:36.508   754  1566 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:25:36.518   754  1566 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:25:36.518   754  1566 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:25:36.528   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:25:36.538   754   754 I MotionRecognitionService: Plugged
,07-05 15:25:36.538   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:25:36.538   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:25:36.538   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:25:36.548   754  1566 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 15:25:36.548   754  1566 D BatteryService: stay LED for fully charged
,07-05 15:25:36.568  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:25:36.568  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:25:36.568  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:25:36.578  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:25:36.578  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:25:36.588  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:25:36.588  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:25:36.588  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:25:41.438   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:25:51.488   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:25:56.018   754  1614 E Watchdog: !@Sync 44 [07-05 15:25:56.029]
,07-05 15:25:58.748  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:25:58.878  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 116ms lastUpdatedAfter : 180280ms
,07-05 15:26:01.548   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:26:06.558   754  1406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:26:06.558   754  1406 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:26:06.558   754  1406 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:26:06.558   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:26:06.568   754   754 I MotionRecognitionService: Plugged
,07-05 15:26:06.568   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:26:06.568   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:26:06.578   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:26:06.578   754  1406 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 15ms
,07-05 15:26:06.578   754  1406 D BatteryService: stay LED for fully charged
,07-05 15:26:06.588  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:26:06.588  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:26:06.588  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:26:06.618  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:26:06.618  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:26:06.618  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:26:06.618  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:26:06.618  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:26:11.598   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:26:21.648   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,07-05 15:26:26.018   754  1614 E Watchdog: !@Sync 45 [07-05 15:26:26.033]
,07-05 15:26:31.708   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-05 15:26:36.628   754  1777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:26:36.638   754  1777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:26:36.638   754  1777 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:26:36.638   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:26:36.648   754   754 I MotionRecognitionService: Plugged
,07-05 15:26:36.648   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:26:36.648   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:26:36.658   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:26:36.658   754  1777 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,07-05 15:26:36.658   754  1777 D BatteryService: stay LED for fully charged
,07-05 15:26:36.668  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:26:36.668  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:26:36.668  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:26:36.688  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:26:36.698  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:26:36.698  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:26:36.698  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:26:36.698  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:26:41.768   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,07-05 15:26:51.828   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-05 15:26:56.028   754  1614 E Watchdog: !@Sync 46 [07-05 15:26:56.037]
,07-05 15:26:58.888  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:27:01.888   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-05 15:27:06.708   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:27:06.708   754  1291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 15:27:06.708   754  1291 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:27:06.708   754  1291 D BatteryService: stay LED for fully charged
07-05 15:27:06.708   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:27:06.708   754   754 I MotionRecognitionService: Plugged
,07-05 15:27:06.718  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:27:06.718  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:27:06.718  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:27:06.718   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:27:06.718   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:27:06.718   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:27:06.738  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:27:06.738  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:27:06.738  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:27:06.748  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:27:06.748  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:27:11.948   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-05 15:27:22.008   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-05 15:27:26.038   754  1614 E Watchdog: !@Sync 47 [07-05 15:27:26.042]
,07-05 15:27:32.068   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-05 15:27:36.778   754  1762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:27:36.788   754  1762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 15:27:36.788   754  1762 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:27:36.788   754  1762 D BatteryService: stay LED for fully charged
07-05 15:27:36.788   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:27:36.788  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:27:36.788  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:27:36.788  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:27:36.798   754   754 I MotionRecognitionService: Plugged
,07-05 15:27:36.798   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:27:36.798   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:27:36.798   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:27:36.808  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:27:36.808  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:27:36.818  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:27:36.818  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:27:36.818  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:27:42.118   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 15:27:52.178   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:27:56.028   754  1614 E Watchdog: !@Sync 48 [07-05 15:27:56.046]
,07-05 15:27:58.918  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:28:02.238   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:28:06.878   754  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:28:12.298   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:28:22.348   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:28:26.048   754  1614 E Watchdog: !@Sync 49 [07-05 15:28:26.051]
,07-05 15:28:32.408   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:28:36.938   754  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:28:36.948   754  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 15:28:36.948   754  1649 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:28:36.948   754  1649 D BatteryService: stay LED for fully charged
07-05 15:28:36.948   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:28:36.948   754   754 I MotionRecognitionService: Plugged
,07-05 15:28:36.948   754   754 D MotionRecognitionService:   cableConnection= 1
07-05 15:28:36.948   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:28:36.948   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:28:36.948  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:28:36.958  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:28:36.958  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:28:36.968  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:28:36.968  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:28:36.978  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:28:36.978  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:28:36.978  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:28:40.278   754  1228 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:28:40.288   754  1228 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:28:40.288   754  1227 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:28:42.468   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 450, LCD = 0
,07-05 15:28:43.708   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:28:43.708   754  1228 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:28:43.718   754  1228 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:28:43.728   754  1228 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:28:52.528   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 292, CUR = 450, LCD = 0
,07-05 15:28:56.038   754  1614 E Watchdog: !@Sync 50 [07-05 15:28:56.055]
,07-05 15:28:59.038  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:28:59.178  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 127ms lastUpdatedAfter : 180296ms
,07-05 15:29:00.668   754  2509 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 15:29:00.678   754  2509 V MARsPolicyManager: updateSMDBValues
,07-05 15:29:00.678   754   885 E MARsDBManager: updateDBAll : begin --size 0
,07-05 15:29:00.678   754   885 E MARsDBManager: updateDBAll : end
,07-05 15:29:02.588   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 293, CUR = 450, LCD = 0
,07-05 15:29:04.128   754  1294 D InputReader: Input event(7): value=1 when=1539621081000
,07-05 15:29:04.128   754  1294 D InputReader: !@notifyKey(172), action=0
,07-05 15:29:04.128   754  1294 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,07-05 15:29:04.138   754  1294 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  pkgName : WAKEUP_BOOSTER@35
,07-05 15:29:04.138   754  1294 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 15:29:04.138   754  1294 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 754) eventTime = 1539621 event = 1
,07-05 15:29:04.138   754  1294 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 754) (1)
07-05 15:29:04.148   754  1294 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 15:29:04.148   754  1294 D InputManager-JNI: setInteractive(true)
07-05 15:29:04.148   754  1355 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
,07-05 15:29:04.148   754  1294 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 15:29:04.148   754  1294 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-05 15:29:04.148   754  1294 D PowerManagerService: mDisplayReady: false
07-05 15:29:04.148   754  1294 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-05 15:29:04.148   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:04.148   754  1294 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-05 15:29:04.148   754   891 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
07-05 15:29:04.148   754  1294 D InputManager-JNI: Disable repeat for home key when device wake up
,07-05 15:29:04.148   754   891 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 15:29:04.148   754  1355 V KeyguardServiceDelegate: onStartedWakingUp()
,07-05 15:29:04.148   754   891 I ActivityManager: Killing 7462:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 723s, lastActivityTime 723s
07-05 15:29:04.148   754   891 I ActivityManager: Killing 7435:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 858s, lastActivityTime 858s
,07-05 15:29:04.158   754   891 I ActivityManager: Killing 7405:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 859s, lastActivityTime 859s
,07-05 15:29:04.158   754   891 I ActivityManager: Killing 7391:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 869s, lastActivityTime 869s
07-05 15:29:04.158  1376  3071 I PERF    : KeyguardViewMediator - onStartedWakingUp() start
,07-05 15:29:04.158   754   827 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,07-05 15:29:04.178   754   891 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@bb8174f)
07-05 15:29:04.178   754   891 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
07-05 15:29:04.178   754   891 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-05 15:29:04.178   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.178   754  1357 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
07-05 15:29:04.178   754  1357 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:29:04.178   754  1357 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 15:29:04.178   754   891 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-05 15:29:04.178   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:04.178   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 15:29:04.178   754   900 I libsuspend: !@autosuspend_wakeup_count_disable
07-05 15:29:04.178   754   900 I libsuspend: !@autosuspend_wakeup_count_disable done
07-05 15:29:04.178   754   900 D DisplayManagerService: !@display_state: OFF -> ON brightness: 0 -> 0
,07-05 15:29:04.178   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6ae4000
07-05 15:29:04.178   754   887 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-05 15:29:04.178   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,07-05 15:29:04.198   754  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 2, mProxSensorScreenOff: false
,07-05 15:29:04.198  1376  3071 D KeyguardViewMediator: onStartedWakingUp, seq = 2
07-05 15:29:04.198  1376  3071 D KeyguardViewMediator: notifyStartedWakingUp
,07-05 15:29:04.208  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() start
07-05 15:29:04.208  1376  1376 D KeyguardViewMediator: handleNotifyWakingUp
07-05 15:29:04.208  1376  1376 D PanelView: onScreenTurnedOn 0,1
07-05 15:29:04.208  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() end
,07-05 15:29:04.208   754  1357 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 250000, 0,  
,07-05 15:29:04.208   754  1357 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:29:04.208   754  1357 E Sensors : Acc old sensor_state 512, new sensor_state : 513 en : 1
,07-05 15:29:04.218   754  1357 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 250000, 0,  
,07-05 15:29:04.218   754  1357 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::registerListener done: 42ms
,07-05 15:29:04.218  7257  7257 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-05 15:29:04.218  7257  7257 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-05 15:29:04.218  1376  3071 I PERF    : KeyguardViewMediator - onStartedWakingUp() end
,07-05 15:29:04.218  1376  3071 D KeyguardViewMediator: notifyScreenOn
07-05 15:29:04.228  7257  7257 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-05 15:29:04.228  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() start
,07-05 15:29:04.228  1376  1376 D KeyguardViewMediator: handleNotifyScreenTurningOn
07-05 15:29:04.228  1376  1376 D KeyguardViewMediator: onScreenTurnedOn()
,07-05 15:29:04.228   754  1406 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-05 15:29:04.228  1376  1376 D KeyguardViewMediator: callback.onShown()
07-05 15:29:04.228  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() end
,07-05 15:29:04.228  7257  7257 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 15:29:04.228  1735  1913 I System.out: Broadcasting: Intent { act=com.sec.android.LTE_WIDEBAND_INFO flg=0x10000000 (has extras) }
,07-05 15:29:04.238  1376  1376 D BatteryMeterView: onDraw batteryColor : -1107296257
,07-05 15:29:04.238  1376  1376 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() start
,07-05 15:29:04.238  2088  2088 D SamsungIME: showDlgMsgBox : false true true
,07-05 15:29:04.238   754  1762 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,07-05 15:29:04.248   754   829 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-05 15:29:04.248  3551  3551 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
07-05 15:29:04.248  3551  3551 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,07-05 15:29:04.248   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:29:04.248   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:29:04.248   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:29:04.248  1725  1870 D NfcService: call the applyRouting
,07-05 15:29:04.248  1376  1376 D SecKeyguardClockSingleView: onScreenTurnedOn
,07-05 15:29:04.248  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:29:04.248  1376  1376 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() end
,07-05 15:29:04.258   292   292 I ServiceManager: service 'AtCmdFwd' died
07-05 15:29:04.258   378  4862 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-05 15:29:04.258   378  4862 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 15:29:04.258  2418  2418 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-05 15:29:04.258   754   829 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-05 15:29:04.258   754   829 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
,07-05 15:29:04.258   754   827 I ActivityManager: Start proc 7613:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.ui.applocking.AppLockingUserReceiver
,07-05 15:29:04.258   754   829 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,07-05 15:29:04.258   754  1778 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 15:29:04.258   754  1778 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:29:04.258   754   829 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-05 15:29:04.268   754  1294 D InputReader: Input event(7): value=0 when=1539760106000
07-05 15:29:04.268   754  1294 D InputReader: !@notifyKey(172), action=1
07-05 15:29:04.268   754  1294 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
,07-05 15:29:04.268   754   829 V CAE     : start(ContextProvider.java:128)
,07-05 15:29:04.268   754   829 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 15:29:04.268   754   829 V CAE     : enable(AutoRotationRunner.java:158)
,07-05 15:29:04.268   754   829 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
07-05 15:29:04.268   754   829 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-05 15:29:04.268  7613  7613 E Zygote  : v2
07-05 15:29:04.268  7613  7613 I libpersona: KNOX_SDCARD checking this for 1000
07-05 15:29:04.268  7613  7613 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:29:04.268  7613  7613 I libpersona: KNOX_SDCARD not a persona
07-05 15:29:04.268  7613  7613 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 15:29:04.268   337   337 D Sensorhubs: sendContextData: -79, 7, 0, 0
07-05 15:29:04.278  7613  7613 E Zygote  : accessInfo : 0
,07-05 15:29:04.278   754  1294 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-05 15:29:04.278  1376  1376 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 15:29:04.278  1376  1376 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-05 15:29:04.278   754  1649 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
07-05 15:29:04.278   754  1649 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-05 15:29:04.278   754  1649 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-05 15:29:04.278  1376  1376 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-05 15:29:04.278   754  1293 D VoIPInterfaceManager: isVoIPRinging()...
07-05 15:29:04.278   754  1293 I WindowManager: Ignoring HOME; down is not pressed.
07-05 15:29:04.278   754  1293 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-05 15:29:04.278   754  1293 D VoIPInterfaceManager: Not exist call session
,07-05 15:29:04.278   754   829 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 15:29:04.278   754   829 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 15:29:04.298   754   829 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 15:29:04.298  2418  2418 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-05 15:29:04.298   754   829 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-05 15:29:04.298  1376  1376 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,07-05 15:29:04.298   754   829 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 15:29:04.298   754   829 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d47c2f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 15:29:04.298   754   829 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@e612be5, Service : AUTO_ROTATION(1)
07-05 15:29:04.298   754   829 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 15:29:04.298   754   829 D SContextService: 	.registerCallback : 1, client=
07-05 15:29:04.298   754   829 D SContextService: ===== SContext Service List =====
07-05 15:29:04.298   754   829 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2dda6ba, Service : Auto Rotation
07-05 15:29:04.298   754   829 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 15:29:04.298   754   829 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@211f722, service=Auto Rotation
,07-05 15:29:04.308  1376  1376 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-05 15:29:04.308  1376  1376 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-05 15:29:04.308   754   891 I DisplayPowerController: Unblocked screen on after 160 ms
07-05 15:29:04.308   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:04.308   754   891 D ColorFade: prepare: mode=2
07-05 15:29:04.308   754   891 D ColorFade: ColorFade is already prepared
07-05 15:29:04.308   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.308   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:04.308   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 15:29:04.308   754   754 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,07-05 15:29:04.308   754   754 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 15:29:04.318   314   314 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6d0a030
07-05 15:29:04.318   314   314 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
07-05 15:29:04.318   314   314 I rmt_storage: wakelock acquired: 1, error no: 42
07-05 15:29:04.318   314   617 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228146384)
,07-05 15:29:04.318   754  2553 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-05 15:29:04.328   754   754 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 15:29:04.328   754   754 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 15:29:04.328   754  2553 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 15:29:04.328   754  2553 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10950ms
,07-05 15:29:04.328   754   754 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 15:29:04.328   754   754 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
,07-05 15:29:04.328   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 754) 
,07-05 15:29:04.328   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=6) set Off
,07-05 15:29:04.328   754   754 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:29:04.338   754   897 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-05 15:29:04.338   754   754 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-05 15:29:04.338   754   897 D SensorManager: unregisterListener ::   
,07-05 15:29:04.338   754   897 D lights  : led_pattern : 5 +
,07-05 15:29:04.338   754   754 D UsbDeviceManager: Keyguard Lock/Unlock
,07-05 15:29:04.338   754   754 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
,07-05 15:29:04.348   754   754 D UsbDeviceManager: mps exists
,07-05 15:29:04.348   754  1566 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-05 15:29:04.348   754  1566 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-05 15:29:04.348   754  1566 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 20927ms
,07-05 15:29:04.358   754   897 D lights  : led_pattern : 5 -
07-05 15:29:04.358   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=6) OUT; SvcLED(id=5) IN
,07-05 15:29:04.358   754   897 V AlarmManager:  remove PendingIntent] PendingIntent{7b06ee9: PendingIntentRecord{920676e android broadcastIntent}}
07-05 15:29:04.358   754   754 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
,07-05 15:29:04.358   754  1778 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-05 15:29:04.358   754  1778 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-05 15:29:04.358   754  1778 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 30915ms
,07-05 15:29:04.368   754   754 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0210
,07-05 15:29:04.368  7613  7613 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:29:04.368   754   754 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Transferring media files via USB
,07-05 15:29:04.368  7613  7613 D ActivityThread: Added TimaKeyStore provider
,07-05 15:29:04.368   754   754 D UsbDeviceManager: updateUsbNotification : isKeyguardShowingAndNotOccluded = false, isKeyguardSecure = false, mBootCompleted = true
,07-05 15:29:04.378   754  1778 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cfda161 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12f7486 7613:com.samsung.android.sm/1000}
,07-05 15:29:04.378   314   617 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
07-05 15:29:04.378   314   617 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,07-05 15:29:04.378   314   617 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228146384) wakelock released: 1, error no: 22
07-05 15:29:04.378   314   617 I rmt_storage: 
,07-05 15:29:04.378   754   754 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
07-05 15:29:04.378   754   754 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Transferring media files via USB
,07-05 15:29:04.388   754   754 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
07-05 15:29:04.388   754   754 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
07-05 15:29:04.388   754   754 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
07-05 15:29:04.388   754   754 D PalmMotion: [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,07-05 15:29:04.388   314   314 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6d0a030
,07-05 15:29:04.388   754   754 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 15:29:04.388   754   754 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-05 15:29:04.398  7613  7613 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,07-05 15:29:04.398   754   754 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
07-05 15:29:04.398   754   754 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 15:29:04.398   754   754 D UcmService: notifyChangeToPlugin event 16
07-05 15:29:04.398   754   754 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 15:29:04.398   754   754 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 15:29:04.398   754   754 D UcmService: notifying to unmanaged plugin
,07-05 15:29:04.398  1782  1792 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-05 15:29:04.398   754   754 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 15:29:04.398   754   754 D UcmService: agentService status-0
07-05 15:29:04.398   754   754 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 15:29:04.398   754   754 D UcmService: notifying to unmanaged plugin
,07-05 15:29:04.398  1795  1805 D BootAgentService: notifyChange eventId-16
07-05 15:29:04.398   754   754 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 15:29:04.398   754   754 D UcmService: agentService status--1
07-05 15:29:04.398   754   754 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 15:29:04.398  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:29:04.398  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 15:29:04.408  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:29:04.418  7257  7257 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@55166f time:1539911
,07-05 15:29:04.418   754   754 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
07-05 15:29:04.418   754   754 D LightsService: [api] [SvcLED] setFlashing :: id = 6, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 754) 
,07-05 15:29:04.418   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=6) set On
,07-05 15:29:04.418   754   754 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:29:04.418   754   897 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-05 15:29:04.418   754   754 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-05 15:29:04.428   754   754 D EdgeLight: Turning on edge light for notification (NotificationRecord(0x01d1c2a2: pkg=com.google.android.gms user=UserHandle{0} id=1000 tag=ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227 score=10 key=0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10011: Notification(pri=1 contentView=null vibrate=null sound=null tick defaults=0x4 flags=0x1 color=0x00000000 vis=PRIVATE publicVersion=Notification(pri=0 contentView=com.google.android.gms/0x10900a4 vibrate=null sound=null defaults=0x0 flags=0x0 color=0x00000000 vis=PRIVATE secFlags=0x0 secPriority=0) secFlags=0x0 secPriority=0))) with color=ffffffff
,07-05 15:29:04.428   754   897 D SensorManager: unregisterListener ::   
07-05 15:29:04.428   754   897 D lights  : led_pattern : 3 +
,07-05 15:29:04.428  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:29:04.428  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:29:04.438  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.438  1376  1376 D PanelView: screenCapture for lockscreen preview
07-05 15:29:04.438  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:04.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:04.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:04.438   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 754) 
,07-05 15:29:04.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:04.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:04.448   754   897 D lights  : led_pattern : 3 -
07-05 15:29:04.448   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=5) OUT; SvcLED(id=6) IN
,07-05 15:29:04.448   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x2 | SvcLED(id=5) set Off
,07-05 15:29:04.448   754   754 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:29:04.448   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
07-05 15:29:04.448   293   546 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 15:29:04.448   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
,07-05 15:29:04.448   754   900 D SurfaceControl: Excessive delay in setPowerMode(): 266ms
07-05 15:29:04.448   754   900 D PowerManagerUtil: Excessive delay in !@display_state: ON: 268ms
,07-05 15:29:04.448   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:04.448   754   891 D ColorFade: prepare: mode=2
07-05 15:29:04.448   754   891 D ColorFade: ColorFade is already prepared
,07-05 15:29:04.448   754   891 D DisplayPowerState: !@ [0] ColorFade exit
07-05 15:29:04.448   754   891 D PowerManagerService: [input device light] onColorFadeExit(true)
,07-05 15:29:04.448   754   891 D DisplayPowerController: ColorFade: onAnimationStart
07-05 15:29:04.448   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.448   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:04.448   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 15:29:04.458   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.458   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:04.458   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 15:29:04.458   754  7630 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,07-05 15:29:04.458   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
,07-05 15:29:04.458   754   754 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-05 15:29:04.458   754   754 D BatteryService: turn off LED
,07-05 15:29:04.458   754  1356 D lights  : button : 0 +
07-05 15:29:04.458   754  1356 D lights  : button : 0 -
07-05 15:29:04.458   754   897 V AlarmManager:  remove PendingIntent] PendingIntent{7b06ee9: PendingIntentRecord{920676e android broadcastIntent}}
,07-05 15:29:04.458   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.458   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:04.458   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 15:29:04.468   754   897 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-05 15:29:04.468   754   897 D SensorManager: unregisterListener ::   
07-05 15:29:04.468   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=6) maintains its priority right
,07-05 15:29:04.468   754   897 V AlarmManager:  remove PendingIntent] PendingIntent{7b06ee9: PendingIntentRecord{920676e android broadcastIntent}}
,07-05 15:29:04.478   754   754 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
,07-05 15:29:04.478   754   754 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package null
,07-05 15:29:04.478   754   754 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,07-05 15:29:04.478  1376  1376 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 15:29:04.488   754  7629 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 1
,07-05 15:29:04.488  1376  1376 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 15:29:04.498   754   754 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-05 15:29:04.498   754   754 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
07-05 15:29:04.498   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
07-05 15:29:04.498   754   754 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-05 15:29:04.498   337   561 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-05 15:29:04.508   754   754 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-05 15:29:04.518   754  1240 E MotionRecognitionService:  handler : SCREEN_ON end
,07-05 15:29:04.518   754   754 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
,07-05 15:29:04.528   754   754 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-05 15:29:04.528   754   754 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 15:29:04.528   754   754 D UcmService: notifyChangeToPlugin event 16
07-05 15:29:04.528   754   754 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
,07-05 15:29:04.528   754   754 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 15:29:04.528   754   754 D UcmService: notifying to unmanaged plugin
,07-05 15:29:04.528  1782  1794 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-05 15:29:04.528   754   754 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 15:29:04.528   754   754 D UcmService: agentService status-0
07-05 15:29:04.528   754   754 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 15:29:04.528   754   754 D UcmService: notifying to unmanaged plugin
07-05 15:29:04.528  1795  1806 D BootAgentService: notifyChange eventId-16
,07-05 15:29:04.528   754   754 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 15:29:04.528   754   754 D UcmService: agentService status--1
07-05 15:29:04.528   754   754 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 15:29:04.538  1376  1376 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,07-05 15:29:04.548  1376  1376 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,07-05 15:29:04.548   754  1320 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
07-05 15:29:04.548   754  1320 D WifiNative-wlan0: callSECApiBoolean - ID [11]
07-05 15:29:04.548  1553  1553 I wpa_supplicant: STOP_PERIODIC_SCAN command
,07-05 15:29:04.558   754   754 D NotificationService: ACTION_SCREEN_ON
07-05 15:29:04.558   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 754) 
,07-05 15:29:04.558   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x2 -> 0x0 | SvcLED(id=6) set Off
07-05 15:29:04.558   754   897 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-05 15:29:04.558   754   897 D lights  : led_pattern : 0 +
,07-05 15:29:04.558  1376  1376 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 15:29:04.558   754   754 D EdgeLight: Turning on edge light for notification (NotificationRecord(0x01d1c2a2: pkg=com.google.android.gms user=UserHandle{0} id=1000 tag=ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227 score=10 key=0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10011: Notification(pri=1 contentView=null vibrate=null sound=null tick defaults=0x4 flags=0x1 color=0x00000000 vis=PRIVATE publicVersion=Notification(pri=0 contentView=com.google.android.gms/0x10900a4 vibrate=null sound=null defaults=0x0 flags=0x0 color=0x00000000 vis=PRIVATE secFlags=0x0 secPriority=0) secFlags=0x0 secPriority=0))) with color=ffffffff
,07-05 15:29:04.558   754   897 D lights  : led_pattern : 0 -
07-05 15:29:04.558   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=6) maintains its priority right
,07-05 15:29:04.558  1376  1376 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 15:29:04.558   754  1320 E WifiNative-wlan0: do suspend false
,07-05 15:29:04.568   329   329 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 15:29:04.568   329   329 V voice   : voice_set_parameters: enter: screen_state=on
07-05 15:29:04.568   329   329 V voice   : voice_set_parameters: exit with code(-2)
07-05 15:29:04.568   329   329 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 15:29:04.568   329   329 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 15:29:04.568   329   329 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 15:29:04.568   329   329 V audio_hw_primary: adev_set_parameters: exit
,07-05 15:29:04.568   754  1357 D AutomaticBrightnessController: [DAB] onSensorChanged : 1st lux : 26.0
,07-05 15:29:04.568   754  1357 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 43(43.0)    0.0 < 26.0 < 69.0 (0.0)
,07-05 15:29:04.568   754  1357 D AutomaticBrightnessController: mCallbacks.updateBrightness()
,07-05 15:29:04.568   754  1357 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
,07-05 15:29:04.568   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.568   754   891 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 26
,07-05 15:29:04.578   754  1357 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
,07-05 15:29:04.578   754   891 D DisplayPowerController: getFinalBrightness : Summary is 43 -> 43
07-05 15:29:04.578   754   891 D DisplayPowerController: Animating brightness: target=43, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:04.578   754   891 D DisplayPowerState: Requesting new screen state: [0] state=ON, backlight (By colorFade)=43
,07-05 15:29:04.578   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.578   754  1358 D DisplayPowerState: Updating screen state [0]: state=ON, backlight (by ColorFade)=43
07-05 15:29:04.578   754  1358 D lights  : lcd : 43 +
07-05 15:29:04.578   754   891 D DisplayPowerController: getFinalBrightness : Summary is 43 -> 43
07-05 15:29:04.578   754  1358 D lights  : lcd : 43 -
,07-05 15:29:04.578   754   891 D DisplayPowerController: Animating brightness: target=43, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 15:29:04.578   754  1320 D WifiStateMachine: analyze kernel wifi wakelock 
,07-05 15:29:04.578   754  1320 D WifiStateMachine: file not found /proc/wakelocks
,07-05 15:29:04.578   754   754 V AlarmManager:  remove PendingIntent] PendingIntent{6dc5fd1: PendingIntentRecord{dacaa36 android broadcastIntent}}
,07-05 15:29:04.598   754  7629 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-05 15:29:04.598   754  1357 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
,07-05 15:29:04.608  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:29:04.618   754  1321 V AlarmManager:  remove PendingIntent] PendingIntent{b76280d: PendingIntentRecord{da455d3 android broadcastIntent}}
,07-05 15:29:04.628   754   754 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
07-05 15:29:04.628   754   754 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-05 15:29:04.638   754   754 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-05 15:29:04.638   754   754 V CAE     : start(ContextProvider.java:128)
,07-05 15:29:04.638   754   754 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-05 15:29:04.638   754   754 V CAE     : enable(ActivityTrackerRunner.java:84)
,07-05 15:29:04.638   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 13, 29, 4,
07-05 15:29:04.638   754   754 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 13, 29, 4
,07-05 15:29:04.638   337   337 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 13, 29, 4
,07-05 15:29:04.648   754  2551 I ActivityManager: Killing 6323:com.android.exchange/u0a163 (adj 15): DHA:empty #37
,07-05 15:29:04.648   754   754 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-05 15:29:04.648   754   754 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 15:29:04.648   754  2551 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cfda161 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1296cbc 1967:com.google.android.gms.persistent/u0a11}
,07-05 15:29:04.658   754   754 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 15:29:04.658   754   754 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-05 15:29:04.658   754   754 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 15:29:04.658   754   754 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d47c2f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 15:29:04.658   754   754 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d47c2f, Service : ACTIVITY_TRACKER(1)
07-05 15:29:04.658   754   754 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@e612be5, Service : AUTO_ROTATION(1)
,07-05 15:29:04.668   337   560 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, -28, -70, 43, 0, 0
,07-05 15:29:04.668   754  1237 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, -28, -70, 43, 0, 0
,07-05 15:29:04.668   754  1236 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-05 15:29:04.668   754  1236 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,07-05 15:29:04.668   754  1236 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, -28, -70, 43, 0, 0,
07-05 15:29:04.668   754  1291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cfda161 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1296cbc 1967:com.google.android.gms.persistent/u0a11}
07-05 15:29:04.668   754  1236 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-05 15:29:04.668   754   754 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-05 15:29:04.668   754   754 D SContextService: 	.registerCallback : 2, client=
,07-05 15:29:04.668   754  1236 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467725344299]
,07-05 15:29:04.668   754   754 D SContextService: ===== SContext Service List =====
07-05 15:29:04.668   754  1239 D SContextService: updateSContext() : event = Activity Tracker
07-05 15:29:04.668   754   754 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@2dda6ba, Service : Auto Rotation
,07-05 15:29:04.668   754   754 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@c91f29d, Service : Activity Tracker
07-05 15:29:04.668   754   754 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@5377d74, service=Activity Tracker
,07-05 15:29:04.668   754   754 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,07-05 15:29:04.678   754   754 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
,07-05 15:29:04.678   754   754 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
,07-05 15:29:04.678   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
,07-05 15:29:04.678   754   754 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
,07-05 15:29:04.678   337   561 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-05 15:29:04.688   337   560 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 2, -28, -70, 62, 0, 0
,07-05 15:29:04.688   754  1237 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 2, -28, -70, 62, 0, 0
07-05 15:29:04.688   754  1236 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
,07-05 15:29:04.688   754  1236 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
07-05 15:29:04.688   754  1236 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 2, -28, -70, 62, 0, 0,
,07-05 15:29:04.688   754  1236 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-05 15:29:04.688   754  1236 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467725344318]
,07-05 15:29:04.688   754  1239 D SContextService: updateSContext() : event = Activity Tracker
,07-05 15:29:04.688   754   754 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-05 15:29:04.688   754   754 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 15:29:04.688   754  1291 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{9050ae3 u-1 android.intent.action.TIME_TICK qIdx=2}, state= (IDLE) to ReceiverList{507fef9 7435 com.sec.android.daemonapp/10181/u0 remote:f9ed1c0}: filter unregistered
,07-05 15:29:04.698   754   754 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
07-05 15:29:04.698   754   754 D SContextService: requestToUpdate() : service = Activity Tracker
07-05 15:29:04.698   754   754 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@5377d74, service=Activity Tracker
,07-05 15:29:04.698   754  1406 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,07-05 15:29:04.708   754  7630 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
,07-05 15:29:04.708   754   900 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-05 15:29:04.708   754   900 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-05 15:29:04.708   754   900 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 254ms
,07-05 15:29:04.708   754   900 I QCOM PowerHAL: Got set_interactive hint
,07-05 15:29:04.708   754   900 D PowerManagerUtil: Excessive delay in nativeSetInteractive(true): 257ms
07-05 15:29:04.708   754  1356 D lights  : button : 1 +
07-05 15:29:04.708   754   900 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 525ms
,07-05 15:29:04.708   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:04.708   754   891 D DisplayPowerController: getFinalBrightness : Summary is 43 -> 43
07-05 15:29:04.708   754   891 D DisplayPowerController: Animating brightness: target=43, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:04.708   754  1291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cfda161 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1296cbc 1967:com.google.android.gms.persistent/u0a11}
,07-05 15:29:04.718  1967  1967 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver bqHint=4 }.
,07-05 15:29:04.718   754   754 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 15:29:04.718   754   754 D WifiStateMachine: setWifiScanMove bMove = 0
07-05 15:29:04.718   754   754 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-05 15:29:04.718   754   754 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
07-05 15:29:04.718   754   754 D WifiService: setWifiScanWithSensor bMove = 0
,07-05 15:29:04.718   754   754 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 15:29:04.718   754   754 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,07-05 15:29:04.718   754  1320 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
07-05 15:29:04.718  1553  1553 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,07-05 15:29:04.728  1376  1376 D StatusBar.NetworkController: LTE WIDEBAND with extra : false
,07-05 15:29:04.728  1735  1748 I System.out: Broadcast completed: result=0
,07-05 15:29:04.728   754   887 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-05 15:29:04.728   754   887 D IpRemoteDisplayController: Bridge Server is not available
,07-05 15:29:04.738   754  1318 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
,07-05 15:29:04.738   754  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,07-05 15:29:04.738   754  1318 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,07-05 15:29:04.748   754  1356 D lights  : button : 1 -
,07-05 15:29:05.068   337   560 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, -28, -69, -71, 1, 2
,07-05 15:29:05.068   754  1237 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, -28, -69, -71, 1, 2
07-05 15:29:05.068   754  1236 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-05 15:29:05.068   754  1236 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
07-05 15:29:05.068   754  1236 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, -28, -69, -71, 1, 2,
,07-05 15:29:05.068   754  1236 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-05 15:29:05.068   754  1236 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[1], TimeStamp=[1467725344697]
,07-05 15:29:05.068   754  1239 D SContextService: updateSContext() : event = Activity Tracker
07-05 15:29:05.068   754   754 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 15:29:05.068   754   754 D WifiService: ACTIVITY_STATUS_STATIONARY 
,07-05 15:29:05.138   754   754 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 754  tag : WAKEUP_BOOSTER@35
,07-05 15:29:05.258   378  4862 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 15:29:05.258   754   891 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 15:29:05.258   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 15:29:05.288   293  4870 D libEGL  : eglTerminate EGLDisplay = 0xb470b64c
,07-05 15:29:05.288   293  4870 D libEGL  : eglTerminate EGLDisplay = 0xb470b64c
,07-05 15:29:05.288   754   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-05 15:29:05.288   293   357 I SurfaceFlinger: id=18 Removed DolorFade (8/8)
,07-05 15:29:05.288   293   903 I SurfaceFlinger: id=18 Removed DolorFade (-2/8)
07-05 15:29:05.288   754   891 D PowerManagerUtil: Excessive delay in ColorFade : dismiss: 31ms
07-05 15:29:05.288   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 15:29:05.298   754   891 D DisplayPowerController: getFinalBrightness : Summary is 43 -> 43
07-05 15:29:05.298   754   891 D DisplayPowerController: Animating brightness: target=43, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 15:29:05.298   754   891 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
,07-05 15:29:05.298   754   891 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
07-05 15:29:05.298   754   891 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-05 15:29:05.298   754   827 I ActivityManager: Start proc 7641:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
07-05 15:29:05.298   754   891 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-05 15:29:05.298  1376  1395 D KeyguardViewMediator: notifyScreenTurnedOn
,07-05 15:29:05.298  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() start
,07-05 15:29:05.298  1376  1376 D KeyguardViewMediator: handleNotifyScreenTurnedOn
07-05 15:29:05.298  7641  7641 E Zygote  : v2
07-05 15:29:05.298  7641  7641 I libpersona: KNOX_SDCARD checking this for 1000
07-05 15:29:05.298  7641  7641 I libpersona: KNOX_SDCARD not a persona
07-05 15:29:05.298  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() end
,07-05 15:29:05.298   754   891 D PowerManagerService: mDisplayReady: true
07-05 15:29:05.298  7641  7641 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:29:05.298  7641  7641 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:29:05.298   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbefeb3a4
,07-05 15:29:05.298  7641  7641 E Zygote  : accessInfo : 0
,07-05 15:29:05.328  7641  7641 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:29:05.328  7641  7641 D ActivityThread: Added TimaKeyStore provider
,07-05 15:29:05.348  7641  7641 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-05 15:29:05.348  7641  7641 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-05 15:29:05.358  7641  7641 D AtFwdService: onCreate method
07-05 15:29:05.358  7641  7641 I AtFwdService: Instantiate AtCmdFwd Service
,07-05 15:29:05.358  7641  7653 D AtCkpdCmdHandler: De-queing command
,07-05 15:29:06.208   754  1356 D lights  : button : 0 +
,07-05 15:29:06.248   754  1356 D lights  : button : 0 -
,07-05 15:29:06.998   754  1777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:29:07.198   754   821 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-05 15:29:07.198   754   754 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-05 15:29:07.198   754   926 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-05 15:29:07.198   754  1407 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,07-05 15:29:07.198  1725  1725 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-05 15:29:07.208  1725  2159 D NfcService: call the applyRouting
,07-05 15:29:07.218  1376  1376 D StatusBar.NetworkController: onDataActivity: direction=0
,07-05 15:29:07.218  1376  1376 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-05 15:29:07.228  2088  2088 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-05 15:29:07.238   754   754 V AlarmManager:  remove PendingIntent] PendingIntent{c6a8e5e: PendingIntentRecord{19e1221 android broadcastIntent}}
,07-05 15:29:07.238   754   754 V AlarmManager:  remove PendingIntent] PendingIntent{b73723f: PendingIntentRecord{88cff11 android broadcastIntent}}
,07-05 15:29:07.248  2418  2418 D BtGatt.GattService: LCD turned on
,07-05 15:29:07.248  2418  2583 D BtGatt.ScanManager: handleLcdOnIntent
07-05 15:29:07.248  2418  2583 D BtGatt.ScanManager: handleLcdOnIntent
07-05 15:29:07.248  2418  2583 D BtGatt.ScanManager: ClientIf = 0
,07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> SM:1417 [0:0] setClockLayoutContent
,07-05 15:29:07.258  2251  2251 D accuweather: [KK AccuPhone]>>> U:850 [0:0] Locale format : MMM d, y
,07-05 15:29:07.298   754  1407 W BroadcastQueue: Skipping deliver [sec] BroadcastRecord{2cdd855 u-1 android.intent.action.SCREEN_ON qIdx=1}, state= (IDLE) to ReceiverList{507fef9 7435 com.sec.android.daemonapp/10181/u0 remote:f9ed1c0}: filter unregistered
,07-05 15:29:07.298   754  1355 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 15:29:07.308   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 295, CUR = 450, LCD = 43
,07-05 15:29:07.318   754  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:29:07.338  7657  7657 E Zygote  : v2
,07-05 15:29:07.338   754   827 I ActivityManager: Start proc 7657:com.sec.android.daemonapp/u0a181 for broadcast-3 com.sec.android.daemonapp/.ap.accuweather.AccuWeatherDaemonService
07-05 15:29:07.338   754  1318 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: true, uidstate: -1, mProxSensorScreenOff: false
,07-05 15:29:07.338  7657  7657 I libpersona: KNOX_SDCARD checking this for 10181
07-05 15:29:07.338  7657  7657 I libpersona: KNOX_SDCARD not a persona
,07-05 15:29:07.338  7657  7657 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:29:07.338  7657  7657 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:29:07.338  7657  7657 E Zygote  : accessInfo : 0
,07-05 15:29:07.338  7657  7657 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-05 15:29:07.368  7657  7657 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:29:07.368  7657  7657 D ActivityThread: Added TimaKeyStore provider
,07-05 15:29:07.368   754  2551 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d326a u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e36f35b 7657:com.sec.android.daemonapp/u0a181}
,07-05 15:29:07.378   754  1318 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: true, uidstate: 10, mProxSensorScreenOff: false
,07-05 15:29:07.378  7657  7657 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-05 15:29:07.388   754  7673 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 15:29:07.388   754  7673 D BluetoothAdapter: STATE_ON
,07-05 15:29:07.388  2418  2602 D bt_vendor: op for 7
07-05 15:29:07.388  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:29:07.388  2418  2602 D bt_upio : upio_start_stop_timer : timer_settime success
07-05 15:29:07.388  2418  2602 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-05 15:29:07.398   754  2553 V AlarmManager:  remove PendingIntent] PendingIntent{eed87f8: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:29:07.398  7657  7657 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-05 15:29:07.408  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-05 15:29:07.418  7657  7657 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:29:07.418  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:07.418  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:07.418  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-05 15:29:07.428  7657  7657 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:29:07.428  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:07.428  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:07.428  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:07.428  7657  7657 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
07-05 15:29:07.428  7657  7657 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:29:07.428  7657  7657 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-05 15:29:07.428  7657  7657 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:29:07.428   754  7673 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 15:29:07.438  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.438  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 15:29:07.448  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.448  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 15:29:07.448  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-05 15:29:07.458  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 15:29:07.458  7657  7657 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:false
,07-05 15:29:07.458  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:29:07.468  7657  7657 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:29:07.468  7657  7657 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:29:07.468  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:45 [0:0] WeatherClockService start : 
,07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:419 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][NUT] = 1467745440000
07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:424 [0:0] [ASO][CT] = 1467725347486
,07-05 15:29:07.468  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 15:29:07.478  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1609 [0:0] PakNme size = 5
,07-05 15:29:07.478  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.478  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:29:07.478  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1613 [0:0] CP Name cp_eng
,07-05 15:29:07.478  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 15:29:07.478  7657  7657 E daemonapp: [MSC_Daemon]>>> WU:1593 [0:0] [NameNotFoundException] !!
,07-05 15:29:07.488   754  1566 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c60a4d1 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e36f35b 7657:com.sec.android.daemonapp/u0a181}
,07-05 15:29:07.488  7657  7657 D daemonapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-05 15:29:07.488  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.488  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:29:07.488  7657  7657 D daemonapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-05 15:29:07.498  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.508  7657  7657 D daemonapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-05 15:29:07.508  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.508  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 15:29:07.508  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:29:07.508  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.518   754  7673 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
07-05 15:29:07.518  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:29:07.518  7657  7657 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 15:29:07.518  7657  7657 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:29:07.518  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.518  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:29:07.528   754  1406 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{17da4c2 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e36f35b 7657:com.sec.android.daemonapp/u0a181}
,07-05 15:29:07.528   754  7673 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 15:29:07.528  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.528  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:29:07.528  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:29:07.528  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.528  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:29:07.538  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:29:07.538  7657  7657 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 15:29:07.538  7657  7657 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:29:07.538  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.538  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:29:07.538   754  1777 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{abe72d3 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e36f35b 7657:com.sec.android.daemonapp/u0a181}
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:29:07.548  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:29:07.548  7657  7657 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:29:07.548  7657  7657 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:29:07.548  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:29:07.548  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.558  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:29:07.558   754  1762 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c455e10 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e36f35b 7657:com.sec.android.daemonapp/u0a181}
,07-05 15:29:07.558  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:29:07.558  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:29:07.558  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:29:07.568  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:29:07.568  7657  7657 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:29:07.568  7657  7657 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:29:07.568  7657  7657 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:29:07.568  7657  7657 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:29:07.698   754  7673 I BatteryStatsDumper: Writing to database completed
,07-05 15:29:08.188  2418  2800 D bt_upio : ..proc_btwrite_timeout..
,07-05 15:29:08.198  2418  2800 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 15:29:08.428  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:08.428  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:08.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:08.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:08.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:08.898  2418  2602 D bt_vendor: op for 7
07-05 15:29:08.898  2418  2602 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-05 15:29:08.898  2418  2602 D bt_upio : BT_WAKE is de-asserted already
07-05 15:29:08.898   754  1762 V AlarmManager:  remove PendingIntent] PendingIntent{c921d09: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:29:10.438  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:10.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:10.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:10.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:10.438  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:12.458  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:12.458  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:12.458  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:12.458  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:12.458  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:14.488  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:14.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:14.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:14.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:14.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:15.328   754   827 I ActivityManager: Start proc 7688:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService
,07-05 15:29:15.338  7688  7688 E Zygote  : v2
07-05 15:29:15.338  7688  7688 I libpersona: KNOX_SDCARD checking this for 10034
07-05 15:29:15.338  7688  7688 I libpersona: KNOX_SDCARD not a persona
,07-05 15:29:15.338  7688  7688 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:29:15.348  7688  7688 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:29:15.348  7688  7688 E Zygote  : accessInfo : 0
,07-05 15:29:15.348  7688  7688 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-05 15:29:15.398  7688  7688 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:29:15.398  7688  7688 D ActivityThread: Added TimaKeyStore provider
,07-05 15:29:15.428  7688  7688 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-05 15:29:15.478  7688  7688 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-05 15:29:15.488  7688  7688 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 15:29:15.488  7688  7688 I MultiDex: install
07-05 15:29:15.488  7688  7688 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 15:29:15.488  7688  7688 I MultiDex: install
07-05 15:29:15.488  7688  7688 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 15:29:15.488  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:15.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:15.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:15.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:15.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:15.558  7688  7688 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-05 15:29:15.558  7688  7688 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 15:29:15.578  1376  1376 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-05 15:29:15.588   754   768 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-05 15:29:15.588  1376  1376 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{154b6cb VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,07-05 15:29:15.588  1376  1376 D AdaptiveEventManager: M updateContainers()
07-05 15:29:15.588  1376  1376 D AdaptiveEventContainerSmall: C updatePedoContainer()
07-05 15:29:15.588  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-05 15:29:15.588  1376  1376 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-05 15:29:15.588   754  1291 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-05 15:29:15.598   754  2551 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-05 15:29:15.598   754  1779 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-05 15:29:15.628  7688  7688 I Health.HealthService: HealthService: onCreate() start (7688)
,07-05 15:29:15.848  7688  7688 D HealthDataStore: Service for HealthDataStore is connected
,07-05 15:29:15.848  7688  7688 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 15:29:15.848  7688  7688 D HealthConsole: Service for HealthDataConsole is connected
,07-05 15:29:15.858  7688  7688 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 15:29:15.858  7688  7688 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 15:29:15.988  7688  7706 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-05 15:29:16.028  7688  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-05 15:29:16.028  7485  7532 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-05 15:29:16.258  7688  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-05 15:29:16.348  7688  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
07-05 15:29:16.348  7688  7714 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 15:29:16.488  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:16.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:16.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:16.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:16.488  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:17.368   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 297, CUR = 450, LCD = 43
,07-05 15:29:18.508  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:18.508  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:18.508  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:18.508  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:18.518  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:19.528  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:19.528  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:19.528  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:19.528  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:19.528  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:20.528  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:20.528  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:20.538  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:20.538  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:20.538  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:22.538  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:22.548  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:22.548  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:22.548  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:22.548  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:24.568  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:24.568  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:24.568  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:24.568  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:24.578  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:25.328   754   827 I ActivityManager: Start proc 7717:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-05 15:29:25.338  7717  7717 E Zygote  : v2
,07-05 15:29:25.338  7717  7717 I libpersona: KNOX_SDCARD checking this for 10026
,07-05 15:29:25.348  7717  7717 I libpersona: KNOX_SDCARD not a persona
,07-05 15:29:25.348  7717  7717 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:29:25.348  7717  7717 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:29:25.348  7717  7717 E Zygote  : accessInfo : 0
,07-05 15:29:25.358  7717  7717 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-05 15:29:25.398  7717  7717 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:29:25.398  7717  7717 D ActivityThread: Added TimaKeyStore provider
,07-05 15:29:25.428  7717  7717 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-05 15:29:25.438  7717  7717 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-05 15:29:25.448  7717  7717 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-05 15:29:25.468  7717  7717 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-05 15:29:25.568  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:25.568  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:25.568  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:25.578  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:25.578  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:26.048   754  1614 E Watchdog: !@Sync 51 [07-05 15:29:26.060]
,07-05 15:29:27.428   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 299, CUR = 450, LCD = 43
,07-05 15:29:27.578  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:27.578  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:27.588  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:27.588  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:27.588  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:28.268   754   891 D PowerManagerService: [s] UserActivityState : 1 -> 2
,07-05 15:29:28.268   754   891 D PowerManagerService: mDisplayReady: false
,07-05 15:29:28.268   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:28.268   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.268   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 15:29:28.268   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:28.278   754   891 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 15:29:28.278   754   891 D PowerManagerService: mDisplayReady: true
,07-05 15:29:28.278   754  1358 D lights  : lcd : 39 +
,07-05 15:29:28.298   754  1358 D lights  : lcd : 39 -
,07-05 15:29:28.298   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 15:29:28.298   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.298   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-05 15:29:28.298   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:28.298   754  1358 D lights  : lcd : 30 +
,07-05 15:29:28.308   754  1358 D lights  : lcd : 30 -
,07-05 15:29:28.318   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:28.318   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.318   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 15:29:28.318   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 15:29:28.318   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:28.318   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.318   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 15:29:28.318   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 15:29:28.318   754  1358 D lights  : lcd : 22 +
,07-05 15:29:28.328   754  1358 D lights  : lcd : 22 -
,07-05 15:29:28.328   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:28.328   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.328   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 15:29:28.328   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:28.328   754  1358 D lights  : lcd : 15 +
07-05 15:29:28.328   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:28.328   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.328   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 15:29:28.328   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:28.338   754  1358 D lights  : lcd : 15 -
,07-05 15:29:28.348   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 15:29:28.348   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:28.348   754   891 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 15:29:28.348   754   891 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:28.598  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:28.598  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:28.598  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:28.598  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:28.608  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:30.608  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 15:29:30.608  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:30.618  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:30.618  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:30.618  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:31.618  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:31.618  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:31.628  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:31.628  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:31.628  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:33.638  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:33.638  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:33.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:33.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:33.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:34.458   754   891 D PowerManagerService: [s] UserActivityState : 2 -> 4
,07-05 15:29:34.458   754   891 I PowerManagerService: Nap time (uid 1000)...
07-05 15:29:34.458   754   891 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
,07-05 15:29:34.458   754   891 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
07-05 15:29:34.458   754   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 15:29:34.458   754   891 D InputManager-JNI: setInteractive(false)
07-05 15:29:34.458   754  1355 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,07-05 15:29:34.468   754   891 D PowerManagerService: mDisplayReady: false
,07-05 15:29:34.468  1376  3071 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() start
07-05 15:29:34.468  1376  3071 D KeyguardViewMediator: onStartedGoingToSleep(3)
07-05 15:29:34.468   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 15:29:34.468   754   891 D ColorFade: prepare: mode=4
,07-05 15:29:34.468   293   293 I SurfaceFlinger: id=23 createSurf (1080x1920),2 flag=404, DolorFade
,07-05 15:29:34.468  7257  7257 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 15:29:34.478  1376  3071 D KeyguardViewMediator: timeout : 5000
,07-05 15:29:34.478   754   891 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 13ms
,07-05 15:29:34.498  1376  3071 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,07-05 15:29:34.498  1376  3071 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() end
,07-05 15:29:34.498   754   891 D libEGL  : eglInitialize EGLDisplay = 0x9a8a00cc
,07-05 15:29:34.498   754   891 D libEGL  : eglTerminate EGLDisplay = 0x9a8a01d4
,07-05 15:29:34.518   754   891 D ColorFade: ColorFade is ready
,07-05 15:29:34.518   754   891 D DisplayPowerController: ColorFade: onAnimationStart
07-05 15:29:34.518   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 15:29:34.518   754   891 D DisplayPowerController: getFinalBrightness : Summary is 43 -> 43
,07-05 15:29:34.538   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
,07-05 15:29:34.558   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
,07-05 15:29:34.648  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:34.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:34.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:34.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:34.648  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:34.658   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
,07-05 15:29:34.808   754   891 D DisplayPowerState: !@ [0] ColorFade entry
07-05 15:29:34.808   754   891 D PowerManagerService: [input device light] onColorFadeExit(false)
,07-05 15:29:34.808   754   891 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 15:29:34.818   754  1358 D lights  : lcd : 0 +
,07-05 15:29:34.818   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 15:29:34.818   754   891 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,07-05 15:29:34.828   754  1358 D lights  : lcd : 0 -
,07-05 15:29:34.888  7257  7257 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 15:29:34.888  7257  7257 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 15:29:34.968   754   891 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2dda6ba, Service = Auto Rotation, used = 0
,07-05 15:29:34.978   754  1318 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
,07-05 15:29:34.978   754   891 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-05 15:29:34.978  7257  7257 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e34a44d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@328b517, 16908290=android.view.AbsSavedState$1@328b517}, android:focusedViewId=100}]}]
07-05 15:29:34.978  7257  7257 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 15:29:34.978  7257  7257 V ActivityThread: updateVisibility : ActivityRecord{5736467 token=android.os.BinderProxy@55166f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 15:29:34.978  7257  7257 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 15:29:34.978  7257  7257 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 15:29:34.978   754   891 V CAE     : stop(ContextProvider.java:155)
,07-05 15:29:34.978   754   891 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 15:29:34.978   754   891 V CAE     : disable(AutoRotationRunner.java:171)
,07-05 15:29:34.978   754   891 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
07-05 15:29:34.978   754   891 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,07-05 15:29:34.978   337   337 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-05 15:29:34.998   754   891 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 15:29:34.998   754   891 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 15:29:35.008   754   891 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 15:29:35.008   754   891 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-05 15:29:35.008   754   891 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
,07-05 15:29:35.008   754   891 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d47c2f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 15:29:35.008   754   891 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d47c2f, Service : ACTIVITY_TRACKER(1)
,07-05 15:29:35.018   754   891 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-05 15:29:35.018   754   891 D SContextService: 	.unregisterCallback : 2, client=
07-05 15:29:35.018   754   891 D SContextService: ===== SContext Service List =====
07-05 15:29:35.018   754   891 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@c91f29d, Service : Activity Tracker
,07-05 15:29:35.018   754   891 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@211f722, service=Auto Rotation
07-05 15:29:35.018   754   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-05 15:29:35.018  1376  3071 D KeyguardViewMediator: notifyScreenTurnedOff
07-05 15:29:35.018  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() start
07-05 15:29:35.018  1376  1376 D KeyguardViewMediator: handleNotifyScreenTurnedOff
07-05 15:29:35.018  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() end
,07-05 15:29:35.018   754   891 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
,07-05 15:29:35.018   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 15:29:35.018   754  1357 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
07-05 15:29:35.018   754  1357 E LightSensor: Light old sensor_state 513, new sensor_state : 1 en : 0
,07-05 15:29:35.018   754   891 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
,07-05 15:29:35.018   754   891 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
,07-05 15:29:35.028   754  1357 D SensorManager: unregisterListener ::   
07-05 15:29:35.028   754  1357 E Sensors : Acc old sensor_state 1, new sensor_state : 0 en : 0
,07-05 15:29:35.028   754  1357 D SensorManager: unregisterListener ::   
,07-05 15:29:35.028   754  1357 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::unregisterListener done: 14ms
,07-05 15:29:35.038   754   891 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
,07-05 15:29:35.038   754   891 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-05 15:29:35.038   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:35.038   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 15:29:35.038   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 15:29:35.038   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 15:29:35.038   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:35.038   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:35.038   754  7732 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 0
,07-05 15:29:35.038   754  7732 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-05 15:29:35.038   754  7733 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
,07-05 15:29:35.048   754  7733 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,07-05 15:29:35.048   754   900 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,07-05 15:29:35.048   754   900 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 15:29:35.048   754   900 I QCOM PowerHAL: Got set_interactive hint
,07-05 15:29:35.048   754   900 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
,07-05 15:29:35.048   754   887 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 15:29:35.048   293   293 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,07-05 15:29:35.048   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-05 15:29:35.088   754   764 I art     : Background partial concurrent mark sweep GC freed 44232(2MB) AllocSpace objects, 12(240KB) LOS objects, 27% free, 42MB/58MB, paused 1.516ms total 229.397ms
,07-05 15:29:35.308   293   546 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 15:29:35.308   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-05 15:29:35.308   754   900 D SurfaceControl: Excessive delay in setPowerMode(): 260ms
07-05 15:29:35.308   754   900 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 264ms
07-05 15:29:35.308   754   900 I libsuspend: !@autosuspend_wakeup_count_enable
07-05 15:29:35.308   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 15:29:35.308   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 15:29:35.308   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:35.308   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 15:29:35.308   754   891 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 15:29:35.308   754   891 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 15:29:35.308   754   891 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 15:29:35.308   754   891 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 15:29:35.308   754   900 I libsuspend: !@autosuspend_wakeup_count_enable done
07-05 15:29:35.308   754   891 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 15:29:35.308   754   891 D PowerManagerService: mDisplayReady: true
07-05 15:29:35.308   754   891 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-05 15:29:35.318   754   891 I PowerManagerService: [PWL] Off : 0s ago
07-05 15:29:35.318   754   891 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
07-05 15:29:35.318   754   891 D PowerManagerService: handleSandman : startDream(true)
07-05 15:29:35.318   754   900 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 277ms
07-05 15:29:35.318   754   891 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-05 15:29:35.318   754   891 I PowerManagerService: Sleeping (uid 1000)...
07-05 15:29:35.318   754   891 D PowerManagerService: [s] UserActivityState : 4 -> 0
07-05 15:29:35.318   754   891 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 15:29:35.318   754  1355 D PersonaManagerService: onfinishedGoingToSleep why = 3
,07-05 15:29:35.318  1376  1400 D KeyguardViewMediator: onFinishedGoingToSleep(3)
07-05 15:29:35.318  1376  1400 D KeyguardViewMediator: onFinishedGoingToSleep: mPendingLock false
07-05 15:29:35.318  1376  1400 D KeyguardViewMediator: notifyFinishedGoingToSleep
07-05 15:29:35.318  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() start
07-05 15:29:35.318  1376  1376 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
07-05 15:29:35.318  1376  1376 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() end
,07-05 15:29:35.318   754   926 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-05 15:29:35.318  1376  1376 D SecKeyguardClockSingleView: onScreenTurnedOff
,07-05 15:29:35.318  1376  1376 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOff() end
,07-05 15:29:35.328   754   754 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 754) 
,07-05 15:29:35.328   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
07-05 15:29:35.328   754   754 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:29:35.328   754   754 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 15:29:35.328   754   754 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-05 15:29:35.328   754   754 D BatteryService: turn on LED for fully charged
,07-05 15:29:35.348   754   754 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-05 15:29:35.348   754   754 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
07-05 15:29:35.348   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
07-05 15:29:35.348   754   754 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
,07-05 15:29:35.348   337   561 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-05 15:29:35.358   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 13, 29, 35,
07-05 15:29:35.358   754   754 D SensorHubManager: SendSensorHubData: send data = -63, 14, 13, 29, 35
07-05 15:29:35.358   337   337 D Sensorhubs: sendContextData: -63, 14, 13, 29, 35
,07-05 15:29:35.358   754   754 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 15:29:35.368   754  1240 D MotionRecognitionService: Screen off setAccIntStatus 
,07-05 15:29:35.368   754  1240 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-05 15:29:35.378   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1759d7a u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f78a4c 2855:com.android.settings/1000}
,07-05 15:29:35.378   754   754 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,07-05 15:29:35.388   754   754 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-05 15:29:35.388   754   754 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 15:29:35.388   754   754 D UcmService: notifyChangeToPlugin event 16
07-05 15:29:35.388   754   754 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 15:29:35.388   754   754 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 15:29:35.388   754   754 D UcmService: notifying to unmanaged plugin
07-05 15:29:35.388  1782  1794 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-05 15:29:35.388   754   754 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 15:29:35.388   754   754 D UcmService: agentService status-0
07-05 15:29:35.388   754   754 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 15:29:35.388   754   754 D UcmService: notifying to unmanaged plugin
07-05 15:29:35.388  1795  1806 D BootAgentService: notifyChange eventId-16
07-05 15:29:35.388   754   754 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 15:29:35.388   754   754 D UcmService: agentService status--1
07-05 15:29:35.388   754   754 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 15:29:35.398   754  1320 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
07-05 15:29:35.398   754  1320 D WifiNative-wlan0: callSECApiVoid - ID [19]
07-05 15:29:35.398  1553  1553 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,07-05 15:29:35.398   754   754 D NotificationService: ACTION_SCREEN_OFF
,07-05 15:29:35.408   754  1320 E WifiNative-wlan0: do suspend true
,07-05 15:29:35.408   754   754 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
07-05 15:29:35.408   754   754 D LightsService: [api] [SvcLED] setFlashing :: id = 6, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 754) 
07-05 15:29:35.408   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=6) set On
,07-05 15:29:35.408   754   754 D EdgeLight: Turning on edge light for notification (NotificationRecord(0x01d1c2a2: pkg=com.google.android.gms user=UserHandle{0} id=1000 tag=ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227 score=10 key=0|com.google.android.gms|1000|ChBhY2NvdW50X25vdGlmaWVyGhVBSF9SRUNPVkVSWV9PUFRJT05TOjA:105256135866144380227|10011: Notification(pri=1 contentView=null vibrate=null sound=null tick defaults=0x4 flags=0x1 color=0x00000000 vis=PRIVATE publicVersion=Notification(pri=0 contentView=com.google.android.gms/0x10900a4 vibrate=null sound=null defaults=0x0 flags=0x0 color=0x00000000 vis=PRIVATE secFlags=0x0 secPriority=0) secFlags=0x0 secPriority=0))) with color=ffffffff
07-05 15:29:35.408   329   968 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 15:29:35.408   329   968 V voice   : voice_set_parameters: enter: screen_state=off
07-05 15:29:35.408   329   968 V voice   : voice_set_parameters: exit with code(-2)
07-05 15:29:35.408   329   968 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 15:29:35.408   329   968 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 15:29:35.408   329   968 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 15:29:35.408   329   968 V audio_hw_primary: adev_set_parameters: exit
,07-05 15:29:35.428   754   754 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,07-05 15:29:35.428   754   754 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 15:29:35.428   754   754 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
07-05 15:29:35.428   754   754 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@c91f29d, Service = Activity Tracker, used = 0
,07-05 15:29:35.428   754   754 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
,07-05 15:29:35.438   754   754 V CAE     : stop(ContextProvider.java:155)
,07-05 15:29:35.438   754   754 V CAE     : clear(ActivityTrackerRunner.java:108)
07-05 15:29:35.438   754   754 V CAE     : disable(ActivityTrackerRunner.java:96)
,07-05 15:29:35.438   754   754 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
07-05 15:29:35.438   754   754 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-05 15:29:35.438   337   561 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-05 15:29:35.438   754   754 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-05 15:29:35.448   754   754 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 15:29:35.458   754   754 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 15:29:35.458   754   754 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-05 15:29:35.458   754   754 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 15:29:35.458   754   754 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@1d47c2f, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 15:29:35.458   754   754 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-05 15:29:35.458   754   754 D SContextService: 	.unregisterCallback : 1, client=
07-05 15:29:35.458   754   754 D SContextService: ===== SContext Service List =====
07-05 15:29:35.458   754   754 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$12@5377d74, service=Activity Tracker
,07-05 15:29:35.458   754   887 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
07-05 15:29:35.458   754   887 D IpRemoteDisplayController: Bridge Server is not available
,07-05 15:29:35.468  1376  1376 D vol.SecVolumeDialog: dismissH : false
,07-05 15:29:35.478   754   754 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,07-05 15:29:35.478   754  1318 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
07-05 15:29:35.478   754  1318 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-05 15:29:35.708   754   897 D LightsService: [SvcLED]  onSensorChanged::light value = 32
,07-05 15:29:35.708   754   897 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 15:29:35.718   754   897 D SensorManager: unregisterListener ::   
,07-05 15:29:35.718   754   897 I LightsService: fileWriteInt : /sys/class/sec/led/led_lowpower  value : 0
,07-05 15:29:35.718   754   897 D lights  : led_pattern : 3 +
,07-05 15:29:35.728   754   897 D lights  : led_pattern : 3 -
,07-05 15:29:35.728   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=6) maintains its priority right
07-05 15:29:35.728   754   897 V AlarmManager:  remove PendingIntent] PendingIntent{7b06ee9: PendingIntentRecord{920676e android broadcastIntent}}
,07-05 15:29:35.978  1445  1445 D Recents : onTaskStackChanged
,07-05 15:29:36.438   754   821 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 15:29:36.448  1725  3423 D NfcService: call the applyRouting
,07-05 15:29:36.448  1376  1376 D StatusBar.NetworkController: onDataActivity: direction=0
,07-05 15:29:36.458  1376  1376 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-05 15:29:36.488  2418  2418 D BtGatt.GattService: LCD turned off
07-05 15:29:36.488  2418  2583 D BtGatt.ScanManager: handleLcdOffIntent
07-05 15:29:36.488  2418  2583 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,07-05 15:29:36.498  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,07-05 15:29:36.498  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,07-05 15:29:36.498  2251  2251 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,07-05 15:29:36.538   754  1355 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 15:29:36.548   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450, LCD = 0
,07-05 15:29:36.558  1376  1376 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 15:29:36.558  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:36.558  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:36.558  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 15:29:36.558  1376  1376 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 15:29:36.558   754  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:29:36.618   754  7751 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 15:29:36.618   754  7751 D BluetoothAdapter: STATE_ON
,07-05 15:29:36.618  2418  2602 D bt_vendor: op for 7
,07-05 15:29:36.618  2418  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:29:36.628  2418  2602 D bt_upio : upio_start_stop_timer : timer_settime success
,07-05 15:29:36.628  2418  2602 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
07-05 15:29:36.628   754  2551 V AlarmManager:  remove PendingIntent] PendingIntent{9091188: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:29:36.658   754  7751 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 15:29:36.758   754  7751 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 15:29:36.768   754  7751 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 15:29:36.928   754  7751 I BatteryStatsDumper: Writing to database completed
,07-05 15:29:37.438  2418  2800 D bt_upio : ..proc_btwrite_timeout..
,07-05 15:29:37.438  2418  2800 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 15:29:37.638   754  3487 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-05 15:29:37.648   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3641721 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba021c1 6642:com.samsung.android.sm.provider/1000}
,07-05 15:29:38.128  2418  2602 D bt_vendor: op for 7
,07-05 15:29:38.128  2418  2602 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-05 15:29:38.128  2418  2602 D bt_upio : BT_WAKE is de-asserted already
,07-05 15:29:38.128   754  1762 V AlarmManager:  remove PendingIntent] PendingIntent{2b56d07: PendingIntentRecord{1e5f876 com.android.bluetooth broadcastIntent}}
,07-05 15:29:39.498   754  1234 V AlarmManager: Expired Alarm result :4
,07-05 15:29:39.508  1376  1376 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-05 15:29:39.518  1376  1376 D KeyguardViewMediator: doKeyguardLocked: started
,07-05 15:29:39.558  1376  1376 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 15:29:39.578  1376  1376 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,07-05 15:29:39.588   754  1291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:29:39.588   754  1291 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:29:39.588   754  1291 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-05 15:29:39.588   754  1291 D BatteryService: stay LED for fully charged
07-05 15:29:39.588   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:29:39.588   754   754 I MotionRecognitionService: Plugged
,07-05 15:29:39.598   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:29:39.598   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:29:39.598   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:29:39.598  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:29:39.598  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:29:39.598  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:29:39.608  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:29:39.618  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:29:39.628  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:29:39.628  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:29:39.628  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:29:46.608   754  3486 D SSRM:n  : SIOP:: AP = 310, PST = 303, CUR = 450, LCD = 0
,07-05 15:29:47.788   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:29:47.788   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:29:47.788   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:29:48.428   754  1234 V AlarmManager: Expired Alarm result :4
,07-05 15:29:48.488   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5b1d2a3 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a245884 4265:com.google.android.gms/u0a11}
,07-05 15:29:48.588   754   754 I BackgroundCompactionService: onStart. jobID=801
,07-05 15:29:48.588   754   754 I BackgroundCompactionService: onStart done. jobID=801
,07-05 15:29:48.588   754  7773 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-05 15:29:48.598   754  7773 I BackgroundCompactionService: compact_memory command done
,07-05 15:29:48.658  1834  7772 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
,07-05 15:29:48.698  4265  7787 I EventLogChimeraService: Aggregate from 1467722646977 (log), 1467722646977 (data)
,07-05 15:29:48.728  1834  7771 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,07-05 15:29:48.808  1834  7771 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,07-05 15:29:48.808  1834  7771 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,07-05 15:29:48.818  1834  7771 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
,07-05 15:29:48.818  1834  7771 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,07-05 15:29:48.838  1834  7771 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-05 15:29:48.838  1834  7771 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,07-05 15:29:48.848   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6ada5f7 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12f7486 7613:com.samsung.android.sm/1000}
,07-05 15:29:48.858   754  1406 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6ada5f7 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a245884 4265:com.google.android.gms/u0a11}
,07-05 15:29:48.868   754  1779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b39becd u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12f7486 7613:com.samsung.android.sm/1000}
,07-05 15:29:48.888   754  1779 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b39becd u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a245884 4265:com.google.android.gms/u0a11}
,07-05 15:29:48.888  1834  7771 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,07-05 15:29:48.928   754  1406 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
,07-05 15:29:49.008  4265  7800 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 15:29:49.048  4265  7798 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 15:29:49.058  4265  5272 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,07-05 15:29:49.068  4265  7798 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 15:29:49.278  1834  7771 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-05 15:29:49.278  1834  7771 E native  : request_context {
07-05 15:29:49.278  1834  7771 E native  :   type: DYNAMIC_CLASS
07-05 15:29:49.278  1834  7771 E native  :   dynamic_class_context {
07-05 15:29:49.278  1834  7771 E native  :     class_type: APP_NAME
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Maps"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Settings"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Gmail"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "YouTube"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Hangouts"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Google+"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Play Store"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Chrome"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Play Books"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Play Music"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Dropbox"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Play Movies & TV"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Contacts"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Phone"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Flipboard"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Play Newsstand"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Drive"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Player"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "ThaliTest"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "S Health"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Peel Smart Remote"
07-05 15:29:49.278  1834  7771 E n,ative  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Photos"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Music"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Calculator"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Messages"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "S Planner"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Camera"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Clock"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "My Files"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Email"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Smart Manager"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Video"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Memo"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Gallery"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Voice Recorder"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Galaxy Apps"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Play Games"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "S Voice"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Docs"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :     instance {
07-05 15:29:49.278  1834  7771 E native  :       value: "Internet"
07-05 15:29:49.278  1834  7771 E native  :     }
07-05 15:29:49.278  1834  7771 E native  :   }
07-05 15:29:49.278  1834  7771 E native  : }
07-05 15:29:49.278  1834  7771 E native  : 
,07-05 15:29:49.288  1834  7771 E ContextCompilationHandl: Compiling recognition context failed for APP_NAMES en-US
07-05 15:29:49.288  1834  7771 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,07-05 15:29:49.358  4265  5263 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,07-05 15:29:49.418  4265  5263 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-05 15:29:49.478  4265  5263 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-05 15:29:49.528  4265  5095 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,07-05 15:29:49.568  1834  7771 E native  : :0 Recognition context compiler error: RecognitionContext not supported:
07-05 15:29:49.568  1834  7771 E native  : request_context {
07-05 15:29:49.568  1834  7771 E native  :   type: DYNAMIC_CLASS
07-05 15:29:49.568  1834  7771 E native  :   dynamic_class_context {
07-05 15:29:49.568  1834  7771 E native  :     class_type: SONG_NAME
07-05 15:29:49.568  1834  7771 E native  :     instance {
07-05 15:29:49.568  1834  7771 E native  :       value: "Over the Horizon"
07-05 15:29:49.568  1834  7771 E native  :     }
07-05 15:29:49.568  1834  7771 E native  :   }
07-05 15:29:49.568  1834  7771 E native  : }
07-05 15:29:49.568  1834  7771 E native  : request_context {
07-05 15:29:49.568  1834  7771 E native  :   type: DYNAMIC_CLASS
07-05 15:29:49.568  1834  7771 E native  :   dynamic_class_context {
07-05 15:29:49.568  1834  7771 E native  :     class_type: UNKNOWN_DYNAMIC_CLASS
07-05 15:29:49.568  1834  7771 E native  :     instance {
07-05 15:29:49.568  1834  7771 E native  :       value: "Brand Music"
07-05 15:29:49.568  1834  7771 E native  :     }
07-05 15:29:49.568  1834  7771 E native  :   }
07-05 15:29:49.568  1834  7771 E native  : }
07-05 15:29:49.568  1834  7771 E native  : request_context {
07-05 15:29:49.568  1834  7771 E native  :   type: DYNAMIC_CLASS
07-05 15:29:49.568  1834  7771 E native  :   dynamic_class_context {
07-05 15:29:49.568  1834  7771 E native  :     class_type: ARTIST_NAME
07-05 15:29:49.568  1834  7771 E native  :     instance {
07-05 15:29:49.568  1834  7771 E native  :       value: "Samsung"
07-05 15:29:49.568  1834  7771 E native  :     }
07-05 15:29:49.568  1834  7771 E native  :   }
07-05 15:29:49.568  1834  7771 E native  : }
07-05 15:29:49.568  1834  7771 E native  : 
,07-05 15:29:49.568  1834  7771 E ContextCompilationHandl: Compiling recognition context failed for MUSIC_NAMES en-US
,07-05 15:29:56.048   754  1614 E Watchdog: !@Sync 52 [07-05 15:29:56.062]
,07-05 15:29:56.678   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,07-05 15:29:59.268  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:29:59.988   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:30:06.508   754  1234 V AlarmManager: Expired Alarm result :4
,07-05 15:30:06.528   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:30:06.528   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:30:06.528   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:30:06.538   754  1407 V AlarmManager:  remove PendingIntent] PendingIntent{ba1afb: PendingIntentRecord{b343534 com.google.android.gms broadcastIntent}}
,07-05 15:30:06.558   754  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 15:30:06.558   754  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 15:30:06.558  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:30:06.558  1376  1376 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 15:30:06.558  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:30:06.598  1376  1376 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:30:06.598  1376  1376 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:30:06.608  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.608  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.608  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.608  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.608  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.618  1376  1376 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:30:06.618  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.668  1376  1376 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:30:06.738   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-05 15:30:09.648   754  1649 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:30:09.648   754  1649 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:30:09.658   754  1649 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:30:09.658   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:30:09.668   754   754 I MotionRecognitionService: Plugged
,07-05 15:30:09.668   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:30:09.678   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:30:09.678   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:30:09.678   754  1649 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:30:09.688   754  1649 D BatteryService: stay LED for fully charged
,07-05 15:30:09.698  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:30:09.708  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:30:09.708  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:30:09.718  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:30:09.718  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:30:09.728  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:30:09.728  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:30:09.728  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:30:13.238   754  1407 V AlarmManager:  remove PendingIntent] PendingIntent{c982718: PendingIntentRecord{da0fec4 com.google.android.gms broadcastIntent}}
,07-05 15:30:13.278   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d422571 u0 com.google.android.c2dm.intent.RECEIVE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a245884 4265:com.google.android.gms/u0a11}
,07-05 15:30:13.278  4265  4265 I GCM     : Message from 745476177629 null
,07-05 15:30:13.298   754  1291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d422571 u0 com.google.android.c2dm.intent.RECEIVE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a245884 4265:com.google.android.gms/u0a11}
,07-05 15:30:13.318   754  1407 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2f88f56 u0 com.google.android.c2dm.intent.RECEIVE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1296cbc 1967:com.google.android.gms.persistent/u0a11}
,07-05 15:30:13.348  1967  1967 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:30:13.348  1967  1967 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:30:13.398   754   754 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 754) 
,07-05 15:30:13.398   754   754 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=6) set Off
,07-05 15:30:13.408   754   754 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 15:30:13.408   754   754 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 15:30:13.418   754   754 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,07-05 15:30:13.418   754   754 D EdgeLight: Turning off
,07-05 15:30:13.418  1967  7824 W WakefulBroadcastReceiver: No active wake lock id #2
,07-05 15:30:13.418  1376  1376 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 15:30:13.428  1376  1376 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 15:30:13.778   754   897 D LightsService: [SvcLED]  onSensorChanged::light value = 28
,07-05 15:30:13.778   754   897 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 15:30:13.798   754   897 D SensorManager: unregisterListener ::   
,07-05 15:30:13.798   754   897 D lights  : led_pattern : 5 +
,07-05 15:30:13.818   754   897 D lights  : led_pattern : 5 -
,07-05 15:30:13.818   754   897 D LightsService: [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=6) OUT; SvcLED(id=5) IN
,07-05 15:30:13.818   754   897 V AlarmManager:  remove PendingIntent] PendingIntent{7b06ee9: PendingIntentRecord{920676e android broadcastIntent}}
,07-05 15:30:16.528   754  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 15:30:16.528   754  1318 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 15:30:16.808   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-05 15:30:26.058   754  1614 E Watchdog: !@Sync 53 [07-05 15:30:26.068]
,07-05 15:30:26.858   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-05 15:30:28.228   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:30:28.228   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:30:28.228   317  1144 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:30:36.918   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-05 15:30:39.718   754  1777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:30:46.978   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,07-05 15:30:56.058   754  1614 E Watchdog: !@Sync 54 [07-05 15:30:56.073]
,07-05 15:30:57.028   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,07-05 15:30:59.338  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:30:59.988   754  1234 V AlarmManager: Expired Alarm result :8
,07-05 15:31:04.758  1967  3359 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 15:31:07.088   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:31:09.788   754  1762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:31:09.788   754  1762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:31:09.788   754  1762 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:31:09.788   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:31:09.808   754   754 I MotionRecognitionService: Plugged
,07-05 15:31:09.808   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:31:09.808   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:31:09.808   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:31:09.818   754  1762 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:31:09.818   754  1762 D BatteryService: stay LED for fully charged
,07-05 15:31:09.838  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:31:09.838  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:31:09.838  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:31:09.848  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:31:09.848  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:31:09.858  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:31:09.858  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:31:09.858  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:31:17.148   754  3486 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:31:26.068   754  1614 E Watchdog: !@Sync 55 [07-05 15:31:26.077]
,07-05 15:31:27.208   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,07-05 15:31:37.268   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-05 15:31:39.848   754  2553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:31:39.858   754  2553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:31:39.858   754  2553 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:31:39.858   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:31:39.878   754   754 I MotionRecognitionService: Plugged
,07-05 15:31:39.878   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:31:39.878   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:31:39.878   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:31:39.888   754  2553 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:31:39.888   754  2553 D BatteryService: stay LED for fully charged
,07-05 15:31:39.888  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:31:39.888  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:31:39.888  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:31:39.908  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:31:39.908  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:31:39.918  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:31:39.918  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:31:39.918  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:31:47.328   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,07-05 15:31:56.068   754  1614 E Watchdog: !@Sync 56 [07-05 15:31:56.082]
,07-05 15:31:57.378   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-05 15:31:59.408  1661  1709 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:31:59.558  1661  1709 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 125ms lastUpdatedAfter : 130561ms
,07-05 15:32:07.488   754  3486 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-05 15:32:09.918   754  1777 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:32:09.928   754  1777 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:32:09.928   754  1777 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:32:09.928   754   754 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:32:09.938   754   754 I MotionRecognitionService: Plugged
,07-05 15:32:09.948   754   754 D MotionRecognitionService:   cableConnection= 1
,07-05 15:32:09.948   754   754 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:32:09.948   754   754 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:32:09.958   754  1777 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:32:09.958   754  1777 D BatteryService: stay LED for fully charged
,07-05 15:32:09.978  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:32:09.978  1376  1376 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:32:09.978  1376  1376 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:32:09.998  2418  2418 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:32:09.998  2418  2811 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:32:10.008  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:32:10.008  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:32:10.008  1376  1376 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),07-05 15:32:11.188  2430  2430 E audit   : type=1400 msg=audit(1467725531.188:294): avc:  denied  { execmod } for  pid=7846 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:32:11.188  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:32:11.188  2430  2430 E audit   : type=1300 msg=audit(1467725531.188:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f9b000 a1=51000 a2=5 a3=4 items=0 ppid=3631 ppcomm=adbd pid=7846 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:32:11.188  2430  2430 E audit   : type=1327 msg=audit(1467725531.188:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 15:32:11.188  2430  2430 E audit   : type=1320 msg=audit(1467725531.188:294): 
07-05 15:32:11.248  2430  2430 E audit   : type=1400 msg=audit(1467725531.248:295): avc:  denied  { execmod } for  pid=7846 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:32:11.248  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:32:11.248  2430  2430 E audit   : type=1300 msg=audit(1467725531.248:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f5b000 a1=51000 a2=5 a3=4 items=0 ppid=3631 ppcomm=adbd pid=7846 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:32:11.248  2430  2430 E audit   : type=1327 msg=audit(1467725531.248:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 15:32:11.248  2430  2430 E audit   : type=1320 msg=audit(1467725531.248:295): 
07-05 15:32:11.288  2430  2430 E audit   : type=1400 msg=audit(1467725531.288:296): avc:  denied  { execmod } for  pid=7846 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:32:11.288  7846  7846 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 15:32:11.288  2430  2430 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:32:11.298  2430  2430 E audit   : type=1300 msg=audit(1467725531.288:296): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f5b000 a1=51000 a2=5 a3=4 items=0 ppid=3631 ppcomm=adbd pid=7846 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:32:11.298  2430  2430 E audit   : type=1327 msg=audit(1467725531.288:296): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 15:32:11.298  2430  2430 E audit   : type=1320 msg=audit(1467725531.288:296): 
07-05 15:32:11.298  7846  7846 D AndroidRuntime: CheckJNI is OFF
07-05 15:32:11.298  7846  7846 D AndroidRuntime: readGMSProperty: start
07-05 15:32:11.298  7846  7846 D AndroidRuntime: readGMSProperty: already setted!!
07-05 15:32:11.298  7846  7846 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 15:32:11.298  7846  7846 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 15:32:11.298  7846  7846 D AndroidRuntime: readGMSProperty: end
07-05 15:32:11.298  7846  7846 D AndroidRuntime: addProductProperty: start
07-05 15:32:11.308  7846  7846 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 15:32:11.308  7846  7846 W art     : af10d000-b2033000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:32:11.308  7846  7846 W art     : b2033000-b42a2000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:32:11.308  7846  7846 W art     : b42a2000-b42a3000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:32:11.308  7846  7846 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-05 15:32:11.308  7846  7846 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-05 15:32:11.308  7846  7846 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-05 15:32:11.308  7846  7846 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-05 15:32:11.308  7846  7846 W art     : b4800000-b4829000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 15:32:11.308  7846  7846 W art     : b4829000-b482c000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:32:11.308  7846  7846 W art     : b482c000-b482d000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:32:11.308  7846  7846 W art     : b482d000-b482e000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:32:11.308  7846  7846 W art     : b482e000-b482f000 r--p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b482f000-b484f000 r--s 00000000 00:0b 6710       /dev/__properties__
07-05 15:32:11.308  7846  7846 W art     : b484f000-b5260000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:32:11.308  7846  7846 W art     : b5260000-b5261000 ---p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b5261000-b52aa000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:32:11.308  7846  7846 W art     : b52aa000-b52ab000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:32:11.308  7846  7846 W art     : b52ab000-b52b3000 rw-p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b52b3000-b52b4000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.308  7846  7846 W art     : b52b4000-b52e9000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:32:11.308  7846  7846 W art     : b52e9000-b52ea000 ---p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b52ea000-b52eb000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:32:11.308  7846  7846 W art     : b52eb000-b52ec000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:32:11.308  7846  7846 W art     : b52ec000-b5344000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-05 15:32:11.308  7846  7846 W art     : b5344000-b5345000 ---p 00000000 00:00 0 
07-05 15:32:11.308  7846  7846 W art     : b5345000-b5346000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-05 15:32:11.308  7846  7846 W art     : b5346000-b5347000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-05 15:32:11.308  7846  7846 W art     : b5348000-b534e000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:32:11.308  7846  7846 W art     : b534e000-b534f000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:32:11.308  7846  7846 W art     : b534f000-b5350000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:32:11.308  7846  7846 W art     : b5350000-b5352000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5353000-b535d000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:32:11.318  7846  7846 W art     : b535d000-b5360000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:32:11.318  7846  7846 W art     : b5360000-b5361000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:32:11.318  7846  7846 W art     : b5362000-b5379000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:32:11.318  7846  7846 W art     : b5379000-b537a000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b537a000-b537b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:32:11.318  7846  7846 W art     : b537b000-b537c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:32:11.318  7846  7846 W art     : b537d000-b5387000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:32:11.318  7846  7846 W art     : b5387000-b5388000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:32:11.318  7846  7846 W art     : b5388000-b5389000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:32:11.318  7846  7846 W art     : b5389000-b538d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:32:11.318  7846  7846 W art     : b538d000-b538e000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:32:11.318  7846  7846 W art     : b538e000-b538f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:32:11.318  7846  7846 W art     : b538f000-b53a5000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-05 15:32:11.318  7846  7846 W art     : b53a5000-b53a6000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-05 15:32:11.318  7846  7846 W art     : b53a6000-b53a7000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-05 15:32:11.318  7846  7846 W art     : b53a7000-b53b4000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:32:11.318  7846  7846 W art     : b53b4000-b53b5000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:32:11.318  7846  7846 W art     : b53b5000-b53b6000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:32:11.318  7846  7846 W art     : b53b6000-b5416000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-05 15:32:11.318  7846  7846 W art     : b5416000-b5419000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-05 15:32:11.318  7846  7846 W art     : b5419000-b541d000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b541d000-b547e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-05 15:32:11.318  7846  7846 W art     : b547e000-b547f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-05 15:32:11.318  7846  7846 W art     : b547f000-b54ce000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:32:11.318  7846  7846 W art     : b54ce000-b54d0000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:32:11.318  7846  7846 W art     : b54d0000-b54d1000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:32:11.318  7846  7846 W art     : b54d1000-b54d2000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b54d2000-b54d9000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:32:11.318  7846  7846 W art     : b54d9000-b54da000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:32:11.318  7846  7846 W art     : b54da000-b54db000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:32:11.318  7846  7846 W art     : b54dc000-b54df000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:32:11.318  7846  7846 W art     : b54df000-b54e0000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:32:11.318  7846  7846 W art     : b54e0000-b54e1000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:32:11.318  7846  7846 W art     : b54e2000-b54e6000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:32:11.318  7846  7846 W art     : b54e6000-b54e7000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b54e7000-b54e8000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:32:11.318  7846  7846 W art     : b54e8000-b54e9000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:32:11.318  7846  7846 W art     : b54ea000-b5507000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:32:11.318  7846  7846 W art     : b5507000-b5508000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:32:11.318  7846  7846 W art     : b5508000-b5509000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:32:11.318  7846  7846 W art     : b550a000-b550f000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:32:11.318  7846  7846 W art     : b550f000-b5510000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:32:11.318  7846  7846 W art     : b5510000-b5511000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:32:11.318  7846  7846 W art     : b5512000-b5543000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:32:11.318  7846  7846 W art     : b5543000-b5546000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:32:11.318  7846  7846 W art     : b5546000-b5547000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:32:11.318  7846  7846 W art     : b5548000-b5583000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-05 15:32:11.318  7846  7846 W art     : b5583000-b5584000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-05 15:32:11.318  7846  7846 W art     : b5584000-b5585000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-05 15:32:11.318  7846  7846 W art     : b5586000-b558d000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:32:11.318  7846  7846 W art     : b558d000-b558e000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b558e000-b558f000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:32:11.318  7846  7846 W art     : b558f000-b5590000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:32:11.318  7846  7846 W art     : b5590000-b5591000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5591000-b55a8000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:32:11.318  7846  7846 W art     : b55a8000-b55a9000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b55a9000-b55ac000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:32:11.318  7846  7846 W art     : b55ac000-b55ad000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:32:11.318  7846  7846 W art     : b55ad000-b55cc000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:32:11.318  7846  7846 W art     : b55cc000-b55cd000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:32:11.318  7846  7846 W art     : b55cd000-b55ce000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:32:11.318  7846  7846 W art     : b55ce000-b560c000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-05 15:32:11.318  7846  7846 W art     : b560c000-b560d000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b560d000-b560f000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-05 15:32:11.318  7846  7846 W art     : b560f000-b5610000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-05 15:32:11.318  7846  7846 W art     : b5611000-b5618000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:32:11.318  7846  7846 W art     : b5618000-b5619000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:32:11.318  7846  7846 W art     : b5619000-b561a000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:32:11.318  7846  7846 W art     : b561b000-b561e000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:32:11.318  7846  7846 W art     : b561e000-b561f000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:32:11.318  7846  7846 W art     : b561f000-b5620000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:32:11.318  7846  7846 W art     : b5620000-b5626000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:32:11.318  7846  7846 W art     : b5626000-b5627000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5627000-b5628000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:32:11.318  7846  7846 W art     : b5628000-b5629000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:32:11.318  7846  7846 W art     : b5629000-b5632000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:32:11.318  7846  7846 W art     : b5632000-b5633000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:32:11.318  7846  7846 W art     : b5633000-b5634000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:32:11.318  7846  7846 W art     : b5634000-b56c5000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:32:11.318  7846  7846 W art     : b56c5000-b56c6000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b56c6000-b56d1000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:32:11.318  7846  7846 W art     : b56d1000-b56d2000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:32:11.318  7846  7846 W art     : b56d3000-b56e5000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-05 15:32:11.318  7846  7846 W art     : b56e5000-b56e6000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-05 15:32:11.318  7846  7846 W art     : b56e6000-b56e7000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-05 15:32:11.318  7846  7846 W art     : b56e8000-b56ed000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:32:11.318  7846  7846 W art     : b56ed000-b56ee000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:32:11.318  7846  7846 W art     : b56ee000-b56ef000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:32:11.318  7846  7846 W art     : b56f0000-b575d000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:32:11.318  7846  7846 W art     : b575d000-b575e000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b575e000-b5760000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:32:11.318  7846  7846 W art     : b5760000-b5761000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:32:11.318  7846  7846 W art     : b5761000-b5762000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5762000-b5769000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:32:11.318  7846  7846 W art     : b5769000-b576a000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:32:11.318  7846  7846 W art     : b576a000-b576b000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:32:11.318  7846  7846 W art     : b576c000-b57ec000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:32:11.318  7846  7846 W art     : b57ec000-b57ed000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b57ed000-b57ee000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:32:11.318  7846  7846 W art     : b57ee000-b57ef000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:32:11.318  7846  7846 W art     : b57ef000-b5806000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5806000-b583d000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-05 15:32:11.318  7846  7846 W art     : ib/libqc-opt.so
07-05 15:32:11.318  7846  7846 W art     : b583d000-b583e000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 15:32:11.318  7846  7846 W art     : b583e000-b583f000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 15:32:11.318  7846  7846 W art     : b583f000-b585b000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:32:11.318  7846  7846 W art     : b585b000-b585c000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:32:11.318  7846  7846 W art     : b585c000-b585d000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:32:11.318  7846  7846 W art     : b585e000-b58bf000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-05 15:32:11.318  7846  7846 W art     : b58bf000-b58c1000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-05 15:32:11.318  7846  7846 W art     : b58c1000-b58c2000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-05 15:32:11.318  7846  7846 W art     : b58c3000-b58ea000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-05 15:32:11.318  7846  7846 W art     : b58ea000-b58eb000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b58eb000-b58ec000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-05 15:32:11.318  7846  7846 W art     : b58ec000-b58ed000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-05 15:32:11.318  7846  7846 W art     : b58ee000-b58f6000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:32:11.318  7846  7846 W art     : b58f6000-b58f8000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:32:11.318  7846  7846 W art     : b58f8000-b58f9000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:32:11.318  7846  7846 W art     : b58fa000-b58fd000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-05 15:32:11.318  7846  7846 W art     : b58fd000-b58fe000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-05 15:32:11.318  7846  7846 W art     : b58fe000-b58ff000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-05 15:32:11.318  7846  7846 W art     : b58ff000-b5903000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:32:11.318  7846  7846 W art     : b5903000-b5904000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5904000-b5905000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:32:11.318  7846  7846 W art     : b5905000-b5906000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:32:11.318  7846  7846 W art     : b5906000-b5916000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-05 15:32:11.318  7846  7846 W art     : b5916000-b5917000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-05 15:32:11.318  7846  7846 W art     : b5917000-b5918000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-05 15:32:11.318  7846  7846 W art     : b5918000-b595e000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b595e000-b5967000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-05 15:32:11.318  7846  7846 W art     : b5967000-b5968000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-05 15:32:11.318  7846  7846 W art     : b5968000-b5969000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-05 15:32:11.318  7846  7846 W art     : b596a000-b596f000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-05 15:32:11.318  7846  7846 W art     : b596f000-b5970000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-05 15:32:11.318  7846  7846 W art     : b5970000-b5971000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-05 15:32:11.318  7846  7846 W art     : b5971000-b5974000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:32:11.318  7846  7846 W art     : b5974000-b5975000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5975000-b5976000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:32:11.318  7846  7846 W art     : b5976000-b5977000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:32:11.318  7846  7846 W art     : b5978000-b5990000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:32:11.318  7846  7846 W art     : b5990000-b5991000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5991000-b5992000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:32:11.318  7846  7846 W art     : b5992000-b5993000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:32:11.318  7846  7846 W art     : b5993000-b5994000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:32:11.318  7846  7846 W art     : b5994000-b5b2e000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:32:11.318  7846  7846 W art     : b5b2e000-b5b2f000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5b2f000-b5b3c000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:32:11.318  7846  7846 W art     : b5b3c000-b5b3d000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:32:11.318  7846  7846 W art     : b5b3d000-b5b41000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-05 15:32:11.318  7846  7846 W art     : b5b41000-b5b42000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5b42000-b5b43000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-05 15:32:11.318  7846  7846 W art     : b5b43000-b5b44000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-05 15:32:11.318  7846  7846 W art     : b5b44000-b5b57000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:32:11.318  7846  7846 W art     : b5b57000-b5b58000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:32:11.318  7846  7846 W art     : b5b58000-b5b59000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:32:11.318  7846  7846 W art     : b5b5a000-b5ba5000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:32:11.318  7846  7846 W art     : b5ba5000-b5ba6000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:32:11.318  7846  7846 W art     : b5ba6000-b5ba7000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:32:11.318  7846  7846 W art     : b5ba7000-b5ba9000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5baa000-b5bbb000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:32:11.318  7846  7846 W art     : b5bbb000-b5bbc000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5bbc000-b5bbd000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:32:11.318  7846  7846 W art     : b5bbd000-b5bbe000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:32:11.318  7846  7846 W art     : b5bbe000-b5bbf000 r--p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5bbf000-b5bc9000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:32:11.318  7846  7846 W art     : b5bc9000-b5bcb000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:32:11.318  7846  7846 W art     : b5bcb000-b5bcc000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:32:11.318  7846  7846 W art     : b5bcc000-b5be5000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:32:11.318  7846  7846 W art     : b5be5000-b5be6000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:32:11.318  7846  7846 W art     : b5be6000-b5be9000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:32:11.318  7846  7846 W art     : b5be9000-b5bed000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5bed000-b5c61000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-05 15:32:11.318  7846  7846 W art     : b5c61000-b5c62000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5c62000-b5c65000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-05 15:32:11.318  7846  7846 W art     : b5c65000-b5c66000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-05 15:32:11.318  7846  7846 W art     : b5c66000-b5c67000 r--p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5c67000-b5c6a000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:32:11.318  7846  7846 W art     : b5c6a000-b5c6b000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:32:11.318  7846  7846 W art     : b5c6b000-b5c6c000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:32:11.318  7846  7846 W art     : b5c6c000-b5c6d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5c6d000-b5c72000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:32:11.318  7846  7846 W art     : b5c72000-b5c73000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:32:11.318  7846  7846 W art     : b5c73000-b5c74000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:32:11.318  7846  7846 W art     : b5c74000-b5c75000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5c75000-b5c78000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:32:11.318  7846  7846 W art     : b5c78000-b5c79000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:32:11.318  7846  7846 W art     : b5c79000-b5c7a000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:32:11.318  7846  7846 W art     : b5c7a000-b5c7b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5c7b000-b5c7f000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:32:11.318  7846  7846 W art     : b5c7f000-b5c80000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:32:11.318  7846  7846 W art     : b5c80000-b5c81000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:32:11.318  7846  7846 W art     : b5c81000-b5c82000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:32:11.318  7846  7846 W art     : b5c82000-b5c86000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:32:11.318  7846  7846 W art     : b5c86000-b5c87000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:32:11.318  7846  7846 W art     : b5c87000-b5c88000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:32:11.318  7846  7846 W art     : b5c88000-b5c89000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5c89000-b5c97000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-05 15:32:11.318  7846  7846 W art     : b5c97000-b5c98000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b5c98000-b5c99000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-05 15:32:11.318  7846  7846 W art     : b5c99000-b5c9a000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-05 15:32:11.318  7846  7846 W art     : b5c9a000-b5ca4000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:32:11.318  7846  7846 W art     : b5ca4000-b5ca7000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:32:11.318  7846  7846 W art     : b5ca7000-b5ca8000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:32:11.318  7846  7846 W art     : b5ca8000-b5ca9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5ca9000-b5cb3000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-05 15:32:11.318  7846  7846 W art     : b5cb3000-b5cb6000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-05 15:32:11.318  7846  7846 W art     : b5cb6000-b5cb7000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-05 15:32:11.318  7846  7846 W art     : b5cb7000-b5cbb000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:32:11.318  7846  7846 W art     : b5cbb000-b5cbc000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:32:11.318  7846  7846 W art     : b5cbc000-b5cbd000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:32:11.318  7846  7846 W art     : b5cbd000-b5cbe000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b5cbe000-b5ccb000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:32:11.318  7846  7846 W art     : b5ccb000-b5ccd000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:32:11.318  7846  7846 W art     : b5ccd000-b5cce000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:32:11.318  7846  7846 W art     : b5cce000-b60e0000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-05 15:32:11.318  7846  7846 W art     : b60e0000-b60e1000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b60e1000-b60ea000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-05 15:32:11.318  7846  7846 W art     : b60ea000-b60ee000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-05 15:32:11.318  7846  7846 W art     : b60ee000-b60ef000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b60ef000-b60f6000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:32:11.318  7846  7846 W art     : b60f6000-b60f7000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:32:11.318  7846  7846 W art     : b60f7000-b60f8000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:32:11.318  7846  7846 W art     : b60f8000-b60f9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b60f9000-b6114000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-05 15:32:11.318  7846  7846 W art     : b6114000-b6115000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-05 15:32:11.318  7846  7846 W art     : b6115000-b6116000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-05 15:32:11.318  7846  7846 W art     : b6116000-b6117000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6117000-b6163000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:32:11.318  7846  7846 W art     : b6163000-b6164000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6164000-b6165000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:32:11.318  7846  7846 W art     : b6165000-b6166000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:32:11.318  7846  7846 W art     : b6166000-b6167000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6167000-b616b000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:32:11.318  7846  7846 W art     : b616b000-b616c000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b616c000-b616d000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:32:11.318  7846  7846 W art     : b616d000-b616e000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:32:11.318  7846  7846 W art     : b616e000-b61a6000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:32:11.318  7846  7846 W art     : b61a6000-b61a7000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:32:11.318  7846  7846 W art     : b61a7000-b61a8000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:32:11.318  7846  7846 W art     : b61a8000-b61a9000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b61a9000-b6247000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-05 15:32:11.318  7846  7846 W art     : b6247000-b6248000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6248000-b6266000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-05 15:32:11.318  7846  7846 W art     : b6266000-b6267000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-05 15:32:11.318  7846  7846 W art     : b6267000-b63da000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:32:11.318  7846  7846 W art     : b63da000-b63e5000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:32:11.318  7846  7846 W art     : b63e5000-b63e6000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:32:11.318  7846  7846 W art     : b63e6000-b64fd000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:32:11.318  7846  7846 W art     : b64fd000-b6508000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:32:11.318  7846  7846 W art     : b6508000-b6509000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:32:11.318  7846  7846 W art     : b6509000-b650d000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b650d000-b6531000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-05 15:32:11.318  7846  7846 W art     : b6531000-b6533000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-05 15:32:11.318  7846  7846 W art     : b6533000-b6534000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-05 15:32:11.318  7846  7846 W art     : b6534000-b65da000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-05 15:32:11.318  7846  7846 W art     : b65da000-b65e7000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-05 15:32:11.318  7846  7846 W art     : b65e7000-b65e8000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-05 15:32:11.318  7846  7846 W art     : b65e8000-b65e9000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b65e9000-b663c000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:32:11.318  7846  7846 W art     : b663c000-b663d000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b663d000-b663e000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:32:11.318  7846  7846 W art     : b663e000-b663f000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:32:11.318  7846  7846 W art     : b663f000-b6644000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6644000-b6656000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-05 15:32:11.318  7846  7846 W art     : b6656000-b6657000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6657000-b6658000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-05 15:32:11.318  7846  7846 W art     : b6658000-b6659000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-05 15:32:11.318  7846  7846 W art     : b6659000-b6660000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:32:11.318  7846  7846 W art     : b6660000-b6661000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:32:11.318  7846  7846 W art     : b6661000-b6662000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:32:11.318  7846  7846 W art     : b6662000-b6663000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6663000-b6666000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-05 15:32:11.318  7846  7846 W art     : b6666000-b6667000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-05 15:32:11.318  7846  7846 W art     : b6667000-b6668000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-05 15:32:11.318  7846  7846 W art     : b6668000-b666c000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-05 15:32:11.318  7846  7846 W art     : b666c000-b666d000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-05 15:32:11.318  7846  7846 W art     : b666d000-b666e000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-05 15:32:11.318  7846  7846 W art     : b666e000-b667c000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:32:11.318  7846  7846 W art     : b667c000-b667d000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b667d000-b667e000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:32:11.318  7846  7846 W art     : b667e000-b667f000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:32:11.318  7846  7846 W art     : b667f000-b6688000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:32:11.318  7846  7846 W art     : b6688000-b6689000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:32:11.318  7846  7846 W art     : b6689000-b668a000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:32:11.318  7846  7846 W art     : b668a000-b66f0000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-05 15:32:11.318  7846  7846 W art     : b66f0000-b66f1000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b66f1000-b66f3000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-05 15:32:11.318  7846  7846 W art     : b66f3000-b66fc000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-05 15:32:11.318  7846  7846 W art     : b66fc000-b66ff000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b66ff000-b6796000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-05 15:32:11.318  7846  7846 W art     : b6796000-b6798000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-05 15:32:11.318  7846  7846 W art     : b6798000-b6799000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-05 15:32:11.318  7846  7846 W art     : b6799000-b679a000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b679a000-b6abb000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-05 15:32:11.318  7846  7846 W art     : b6abb000-b6abc000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6abc000-b6ad7000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-05 15:32:11.318  7846  7846 W art     : b6ad7000-b6adb000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-05 15:32:11.318  7846  7846 W art     : b6adb000-b6ae0000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6ae0000-b6ae8000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:32:11.318  7846  7846 W art     : b6ae8000-b6ae9000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:32:11.318  7846  7846 W art     : b6ae9000-b6aea000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:32:11.318  7846  7846 W art     : b6aea000-b6b18000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:32:11.318  7846  7846 W art     : b6b18000-b6b19000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6b19000-b6b20000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:32:11.318  7846  7846 W art     : b6b20000-b6b21000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:32:11.318  7846  7846 W art     : b6b21000-b6b67000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:32:11.318  7846  7846 W art     : b6b67000-b6b68000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6b68000-b6b6b000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:32:11.318  7846  7846 W art     : b6b6b000-b6b6c000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:32:11.318  7846  7846 W art     : b6b6c000-b6b87000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-05 15:32:11.318  7846  7846 W art     : b6b87000-b6b8b000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-05 15:32:11.318  7846  7846 W art     : b6b8b000-b6b8c000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-05 15:32:11.318  7846  7846 W art     : b6b8c000-b6bd9000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-05 15:32:11.318  7846  7846 W art     : b6bd9000-b6bda000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6bda000-b6be6000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-05 15:32:11.318  7846  7846 W art     : b6be6000-b6be7000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-05 15:32:11.318  7846  7846 W art     : b6be7000-b6bf4000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-05 15:32:11.318  7846  7846 W art     : b6bf4000-b6bf5000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6bf5000-b6bf6000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-05 15:32:11.318  7846  7846 W art     : b6bf6000-b6bf7000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-05 15:32:11.318  7846  7846 W art     : b6bf7000-b6bff000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:32:11.318  7846  7846 W art     : b6bff000-b6c00000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6c00000-b6c01000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:32:11.318  7846  7846 W art     : b6c01000-b6c02000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:32:11.318  7846  7846 W art     : b6c02000-b6c09000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:32:11.318  7846  7846 W art     : b6c09000-b6c0a000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:32:11.318  7846  7846 W art     : b6c0a000-b6c0b000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:32:11.318  7846  7846 W art     : b6c0b000-b6c1f000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-05 15:32:11.318  7846  7846 W art     : b6c1f000-b6c21000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-05 15:32:11.318  7846  7846 W art     : b6c21000-b6c22000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-05 15:32:11.318  7846  7846 W art     : b6c22000-b6c4a000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:32:11.318  7846  7846 W art     : b6c4a000-b6c4c000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:32:11.318  7846  7846 W art     : b6c4c000-b6c4d000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:32:11.318  7846  7846 W art     : b6c4d000-b6c50000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:32:11.318  7846  7846 W art     : b6c50000-b6c51000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:32:11.318  7846  7846 W art     : b6c51000-b6c52000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:32:11.318  7846  7846 W art     : b6c52000-b6c5b000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:32:11.318  7846  7846 W art     : b6c5b000-b6c5c000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:32:11.318  7846  7846 W art     : b6c5c000-b6c5d000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:32:11.318  7846  7846 W art     : b6c5d000-b6c7d000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-05 15:32:11.318  7846  7846 W art     : b6c7d000-b6c7e000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-05 15:32:11.318  7846  7846 W art     : b6c7e000-b6c7f000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-05 15:32:11.318  7846  7846 W art     : b6c7f000-b6cf2000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-05 15:32:11.318  7846  7846 W art     : b6cf2000-b6cf6000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-05 15:32:11.318  7846  7846 W art     : b6cf6000-b6cf9000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-05 15:32:11.318  7846  7846 W art     : b6cf9000-b6d03000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6d03000-b6d8b000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-05 15:32:11.318  7846  7846 W art     : b6d8b000-b6d8c000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6d8c000-b6d90000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-05 15:32:11.318  7846  7846 W art     : b6d90000-b6d91000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-05 15:32:11.318  7846  7846 W art     : b6d91000-b6d92000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6d92000-b6dbb000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:32:11.318  7846  7846 W art     : b6dbb000-b6dbc000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6dbc000-b6dbf000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:32:11.318  7846  7846 W art     : b6dbf000-b6dc0000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:32:11.318  7846  7846 W art     : b6dc0000-b6e9a000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:32:11.318  7846  7846 W art     : b6e9a000-b6ea1000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:32:11.318  7846  7846 W art     : b6ea1000-b6ea9000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:32:11.318  7846  7846 W art     : b6ea9000-b6eaa000 rw-p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6eaa000-b6eab000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:32:11.318  7846  7846 W art     : b6eab000-b6eac000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-05 15:32:11.318  7846  7846 W art     : b6eac000-b6ead000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6ead000-b6eb0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6eb0000-b6ed5000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-05 15:32:11.318  7846  7846 W art     : b6ed5000-b6ed6000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6ed6000-b6edd000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-05 15:32:11.318  7846  7846 W art     : b6edd000-b6ede000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-05 15:32:11.318  7846  7846 W art     : b6ede000-b6ee5000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-05 15:32:11.318  7846  7846 W art     : b6ee5000-b6ee6000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-05 15:32:11.318  7846  7846 W art     : b6ee6000-b6ee7000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-05 15:32:11.318  7846  7846 W art     : b6ee7000-b6ee8000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6ee8000-b6f00000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-05 15:32:11.318  7846  7846 W art     : b6f00000-b6f01000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6f01000-b6f02000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-05 15:32:11.318  7846  7846 W art     : b6f02000-b6f03000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-05 15:32:11.318  7846  7846 W art     : b6f03000-b6f11000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-05 15:32:11.318  7846  7846 W art     : b6f11000-b6f12000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6f12000-b6f13000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-05 15:32:11.318  7846  7846 W art     : b6f13000-b6f14000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-05 15:32:11.318  7846  7846 W art     : b6f14000-b6f15000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:32:11.318  7846  7846 W art     : b6f15000-b6f17000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6f17000-b6f18000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6f18000-b6f19000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:32:11.318  7846  7846 W art     : b6f19000-b6f1a000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-05 15:32:11.318  7846  7846 W art     : b6f1a000-b6f1b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:32:11.318  7846  7846 W art     : b6f1b000-b6f3b000 r--s 00000000 00:0b 6710       /dev/__properties__
07-05 15:32:11.318  7846  7846 W art     : b6f3b000-b6f3c000 r--p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6f3c000-b6f3d000 ---p 00000000 00:00 0 
07-05 15:32:11.318  7846  7846 W art     : b6f3d000-b6f3f000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-05 15:32:11.328  7846  7846 W art     : b6f3f000-b6f40000 r-xp 00000000 00:00 0          [sigpage]
07-05 15:32:11.328  7846  7846 W art     : b6f40000-b6f5b000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-05 15:32:11.328  7846  7846 W art     : b6f5b000-b6f5c000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-05 15:32:11.328  7846  7846 W art     : b6f5c000-b6f5e000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-05 15:32:11.328  7846  7846 W art     : b6f5e000-b6f60000 rw-p 00000000 00:00 0 
07-05 15:32:11.328  7846  7846 W art     : b6f60000-b6f65000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-05 15:32:11.328  7846  7846 W art     : b6f65000-b6f66000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-05 15:32:11.328  7846  7846 W art     : b6f66000-b6f67000 rw-p 00000000 00:00 0 
07-05 15:32:11.328  7846  7846 W art     : bea05000-bea26000 rw-p 00000000 00:00 0          [stack]
07-05 15:32:11.328  7846  7846 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-05 15:32:11.408  7846  7846 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 15:32:11.458  7846  7846 I Radio-JNI: register_android_hardware_Radio DONE
07-05 15:32:11.468  7846  7846 E AffinityControl: AffinityControl: registerfunction enter
07-05 15:32:11.478  7846  7846 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 15:32:11.498   754  1406 D PackageManager: START PACKAGE DELETE: observer{188887854}
07-05 15:32:11.498   754  1406 D PackageManager: pkg{<packageName>}
07-05 15:32:11.498   754  1406 D PackageManager: user{0}
07-05 15:32:11.498   754  1406 D PackageManager: caller{2000}
07-05 15:32:11.498   754  1406 D PackageManager: flags{2}
07-05 15:32:11.498   754  1406 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 15:32:11.498   754  1406 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 15:32:11.498   754  1406 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 15:32:11.498   754  1406 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 15:32:11.498   754  1406 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 15:32:11.498   754   916 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 15:32:11.498   754   916 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 15:32:11.498   754   916 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 15:32:11.498   754   916 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 15:32:11.498   754   916 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 15:32:11.498   754   916 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 15:32:11.498   754   916 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 15:32:11.498   754   916 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-05 15:32:11.498   754   916 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 15:32:11.498   754   827 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-05 15:32:11.498   754   916 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 15:32:11.498   754   827 I ActivityManager: Killing 7257:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 15:32:11.508   754   827 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 15:32:11.508   754   827 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-05 15:32:11.518   754   916 D AASAinstall: there is not AASApackages.xml file
07-05 15:32:11.518   754   827 D ActivityManager: mDVFSHelper.acquire()
07-05 15:32:11.558   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
07-05 15:32:11.558   293   357 D libEGL  : eglTerminate EGLDisplay = 0xb673f6fc
07-05 15:32:11.558   754  1407 D GraphicsStats: Buffer count: 4
07-05 15:32:11.568   754  1406 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a5bfecf)
07-05 15:32:11.568   754   768 I WindowState: WIN DEATH: Window{a74bb63 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 15:32:11.568   293   357 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
07-05 15:32:11.568   754  1327 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 15:32:11.568   293   903 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
07-05 15:32:11.568   754  1327 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 15:32:11.568   293   903 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
07-05 15:32:11.568   754  1327 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 15:32:11.568   754   768 D InputDispatcher: Focus left window: 7257
07-05 15:32:11.578   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbefeb3a4
07-05 15:32:11.778   754   916 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-05 15:32:11.798   754   916 W PackageSettings: Skipping PackageSetting{ca43a30 com.example.hello/10192} due to missing metadata
07-05 15:32:11.858   754   916 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-05 15:32:11.858   754   827 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-05 15:32:11.858   754   827 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-05 15:32:11.868   754   827 E ActivityManager: Failure starting process com.test.thalitest
07-05 15:32:11.868   754   827 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5273)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5190)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5028)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4999)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4960)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7375)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9142)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8765)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8920)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2597)
07-05 15:32:11.868   754   827 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 15:32:11.868   754   827 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
07-05 15:32:11.868   754   827 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 15:32:11.868   754   827 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-05 15:32:11.868   336   336 W keystore: ENTER clear_uid from uid 1000 for 10004
07-05 15:32:11.868   754   916 I art     : Starting a blocking GC Explicit
07-05 15:32:11.878   754   827 I ActivityManager:   Force finishing activity ActivityRecord{f3c85da u0 com.test.thalitest/.MainActivity t64}
07-05 15:32:11.908   754   827 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
07-05 15:32:11.918   293   293 I SurfaceFlinger: id=24 createSurf (1146x1876),1 flag=4, VSBConnecti
07-05 15:32:11.918   754   887 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 15:32:11.918   754   887 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-05 15:32:11.918   754   887 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
07-05 15:32:11.918   754   887 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
07-05 15:32:11.918   754   887 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
07-05 15:32:11.918   754   887 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
07-05 15:32:11.918   754   887 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 15:32:11.918   754   887 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-05 15:32:11.918   754   887 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 15:32:11.918   754   887 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-05 15:32:11.918   754   827 D InputDispatcher: Focus entered window: 3551
07-05 15:32:11.918   754   887 D SecWifiDisplayUtil: Metadata value : none
07-05 15:32:11.918   754   829 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{270db30 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
07-05 15:32:11.918   754   887 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{fa2f8c7 V.E...... R.....ID 0,0-0,0}
07-05 15:32:11.918  1376  1376 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
07-05 15:32:11.918   754   827 D InputDispatcher: Focused application released
07-05 15:32:11.918   754   887 W WindowManager: Attempted to add application window with unknown token Token{e299a0b ActivityRecord{f3c85da u0 com.test.thalitest/.MainActivity t64 f}}.  Aborting.
07-05 15:32:11.918   754   887 D ViewRootImpl: #3 mView = null
07-05 15:32:11.918   754   887 W WindowManager: Token{e299a0b ActivityRecord{f3c85da u0 com.test.thalitest/.MainActivity t64 f}} already running, starting window not displayed. Unable to add window -- token Token{e299a0b ActivityRecord{f3c85da u0 com.test.thalitest/.MainActivity t64 f}} is not valid; is your activity running?
07-05 15:32:11.918   754   887 W WindowManager: view not successfully added to wm, removing view
07-05 15:32:11.928   754   887 W WindowManager: Exception when adding starting window
07-05 15:32:11.928   754   887 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{fa2f8c7 V.E...... R.....ID 0,0-0,0} not attached to window manager
07-05 15:32:11.928   754   887 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:451)
07-05 15:32:11.928   754   887 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:377)
07-05 15:32:11.928   754   887 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmed,iate(WindowManagerImpl.java:122)
07-05 15:32:11.928   754   887 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4399)
07-05 15:32:11.928   754   887 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
07-05 15:32:11.928   754   887 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 15:32:11.928   754   887 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
07-05 15:32:11.928   754   887 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 15:32:11.928   754   887 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-05 15:32:11.928   754   887 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:754 uid:1000
07-05 15:32:11.928   754   887 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 15:32:11.928   754   887 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:754 uid:1000
07-05 15:32:11.928   754   887 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 15:32:11.938   754  1566 V WindowOrientationListener: setCurrentAppOrientation :1
07-05 15:32:11.938   754  1566 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 15:32:11.938  1750  1750 D Launcher: onRestart, Launcher: 12588266
07-05 15:32:11.948  1750  1750 D Launcher: onStart, Launcher: 12588266
07-05 15:32:11.948   754   768 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-05 15:32:11.948   754   768 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 15:32:11.948   754   754 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 15:32:11.948   754   754 I KnoxTimeoutHandler: Shared devices show user statefalse
07-05 15:32:11.948   754   754 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
07-05 15:32:11.948  1750  1750 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
07-05 15:32:11.948  1750  1750 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-05 15:32:11.948  1750  1750 D Launcher.HomeView: onStart
07-05 15:32:11.948  1750  1750 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
07-05 15:32:11.958  1750  1750 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
07-05 15:32:11.958  2251  2263 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
07-05 15:32:11.958  1750  1750 V ActivityThread: updateVisibility : ActivityRecord{f873ae2 token=android.os.BinderProxy@53c48de {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 15:32:11.958   754  3486 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-05 15:32:11.968   754  1762 V WindowStateAnimator: Finishing drawing window Window{270db30 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-05 15:32:11.968   754   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 15:32:11.968   754   754 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 15:32:11.968   293   293 I SurfaceFlinger: id=25 createSurf (1194x288),1 flag=4, VSBConnecti
07-05 15:32:11.968   754   754 I KnoxTimeoutHandler: SD activityfalse
07-05 15:32:11.978   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
07-05 15:32:11.978   293   293 I SurfaceFlinger: id=26 createSurf (1080x1920),1 flag=4, Mauncher
07-05 15:32:11.978  3551  3551 V ActivityThread: updateVisibility : ActivityRecord{468a122 token=android.os.BinderProxy@312086c {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
07-05 15:32:11.978   754   887 D ActivityManager: mDVFSHelper.release()
07-05 15:32:11.988   754   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a706094 u0 com.samsung.android.MtpApplication/.USBConnection t63} time:1727480
07-05 15:32:11.998   754  1779 V WindowStateAnimator: Finishing drawing window Window{508e048 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-05 15:32:11.998  3551  3551 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@312086c time:1727499
07-05 15:32:12.008   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
07-05 15:32:12.008  1750  1750 D Launcher.HomeView: onStop
07-05 15:32:12.018   754   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 15:32:12.018   754   754 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 15:32:12.018   754   754 I KnoxTimeoutHandler: SD activityfalse
07-05 15:32:12.088   754   916 I art     : Explicit concurrent mark sweep GC freed 153955(9MB) AllocSpace objects, 90(2MB) LOS objects, 27% free, 43MB/59MB, paused 1.679ms total 212.495ms
07-05 15:32:12.108   754   916 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-05 15:32:12.108   754   916 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
07-05 15:32:12.108   754   916 D AASAinstall: there is not AASApackages.xml file
07-05 15:32:12.108   754   916 D PackageManager: result of delete: 1{188887854}
07-05 15:32:12.108  7846  7846 I art     : System.exit called, status: 0
07-05 15:32:12.108  7846  7846 I AndroidRuntime: VM exiting with result code 0.
07-05 15:32:12.118   754   916 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 15:32:12.118   754   916 D PackageManager: userId{-1}
07-05 15:32:12.118   754   916 D PackageManager: andCode{true}
07-05 15:32:12.128   754   916 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
07-05 15:32:12.148  6567  7877 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
07-05 15:32:12.148  6567  7877 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
07-05 15:32:12.148   754  1762 V WindowStateAnimator: Finishing drawing window Window{a95d8ab u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
07-05 15:32:12.158  6567  7877 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
07-05 15:32:12.158   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbefeb364
07-05 15:32:12.178   754   827 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-05 15:32:12.178   754   827 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 15:32:12.178   754   827 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-05 15:32:12.188   754   887 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:32:12.188   754   754 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:32:12.188   754   887 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9d1a038 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t61} time:1727683
07-05 15:32:12.188   754   754 I KnoxTimeoutHandler: SD activityfalse
07-05 15:32:12.188   754   754 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.198  1376  1376 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
07-05 15:32:12.198  1376  1376 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
07-05 15:32:12.198   754   887 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.198   754   754 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-1/base.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.208   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.208  2088  2088 E SamsungIME: mOCRHelper is null
07-05 15:32:12.208   754   887 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.208  1967  2218 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 15:32:12.218   754   827 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b7c3de u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{567a85c 4410:com.samsung.klmsagent/u0a18}
07-05 15:32:12.218   754  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 15:32:12.238  1735  1735 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-05 15:32:12.238   754  1318 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
07-05 15:32:12.238   754  1318 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-05 15:32:12.238   754  1360 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/64_task.xml
07-05 15:32:12.238   754  1317 V NetworkStats: removeUidsLocked() for UIDs [10004]
07-05 15:32:12.238   754  1317 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 15:32:12.238   754  1317 V NetworkStats: performPollLocked(flags=0x3)
07-05 15:32:12.238   754  1360 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_images/64_task_thumbnail.png
07-05 15:32:12.248   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.248   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.248  4410  4410 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Jul 05 15:32:12 GMT+02:00 2016
07-05 15:32:12.248   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.248   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258  4410  4410 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
07-05 15:32:12.258   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258   754   754 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258   754   754 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
07-05 15:32:12.258  3236  3268 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 15:32:12.258   754  1291 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1b7c3de u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b58166c 754:system/1000}
07-05 15:32:12.258  3236  3268 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 15:32:12.258   754  1317 V NetworkStats: performPollLocked() took 18ms
07-05 15:32:12.258   754  1317 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 15:32:12.268   754  1318 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 15:32:12.268   754  1318 D NtpTrustedTime: currentTimeMillis() cache hit

```
