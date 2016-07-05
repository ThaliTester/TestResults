#### Test 757892685fc4836_thali08_samsung-SM-G900F Logs


```
--------- beginning of system
07-05 15:39:18.717   770  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:39:18.727   770  1618 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 15:39:18.727   770  1618 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-05 15:39:18.727   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 15:39:18.747   770   770 I MotionRecognitionService: Plugged
07-05 15:39:18.747   770   770 D MotionRecognitionService:   cableConnection= 1
07-05 15:39:18.747   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:39:18.747   770   770 D MotionRecognitionService: skip setTransmitPower. 
07-05 15:39:18.756   770  1618 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
07-05 15:39:18.756   770  1618 D BatteryService: stay LED for fully charged
--------- beginning of main
07-05 15:39:18.766  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:18.766  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:18.776  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 15:39:18.806  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:18.806  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:18.806  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:18.806  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:39:18.806  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 15:39:19.366   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450, LCD = 0
07-05 15:39:19.666  2410  2410 E audit   : type=1400 msg=audit(1467725959.666:284): avc:  denied  { execmod } for  pid=7214 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:39:19.666  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:19.666  2410  2410 E audit   : type=1300 msg=audit(1467725959.666:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f43000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7214 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:39:19.666  2410  2410 E audit   : type=1327 msg=audit(1467725959.666:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 15:39:19.666  2410  2410 E audit   : type=1320 msg=audit(1467725959.666:284): 
07-05 15:39:19.726  2410  2410 E audit   : type=1400 msg=audit(1467725959.716:285): avc:  denied  { execmod } for  pid=7214 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:39:19.726  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:19.726  2410  2410 E audit   : type=1300 msg=audit(1467725959.716:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f02000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7214 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:39:19.726  2410  2410 E audit   : type=1327 msg=audit(1467725959.716:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 15:39:19.736  2410  2410 E audit   : type=1320 msg=audit(1467725959.716:285): 
07-05 15:39:19.766  7214  7214 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 15:39:19.766  2410  2410 E audit   : type=1400 msg=audit(1467725959.766:286): avc:  denied  { execmod } for  pid=7214 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 15:39:19.766  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:19.776   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 15:39:19.776  7214  7214 D AndroidRuntime: CheckJNI is OFF
07-05 15:39:19.776  7214  7214 D AndroidRuntime: readGMSProperty: start
07-05 15:39:19.776  7214  7214 D AndroidRuntime: readGMSProperty: already setted!!
07-05 15:39:19.776  7214  7214 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 15:39:19.776  7214  7214 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 15:39:19.776  7214  7214 D AndroidRuntime: readGMSProperty: end
07-05 15:39:19.776  7214  7214 D AndroidRuntime: addProductProperty: start
07-05 15:39:19.776  2410  2410 E audit   : type=1300 msg=audit(1467725959.766:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f03000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7214 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 15:39:19.776  2410  2410 E audit   : type=1327 msg=audit(1467725959.766:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 15:39:19.776  2410  2410 E audit   : type=1320 msg=audit(1467725959.766:286): 
07-05 15:39:19.786  7214  7214 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 15:39:19.786  7214  7214 W art     : af0a4000-b1fca000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:39:19.786  7214  7214 W art     : b1fca000-b4239000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:39:19.786  7214  7214 W art     : b4239000-b423a000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-05 15:39:19.786  7214  7214 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 15:39:19.786  7214  7214 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-05 15:39:19.786  7214  7214 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-05 15:39:19.786  7214  7214 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-05 15:39:19.786  7214  7214 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-05 15:39:19.786  7214  7214 W art     : b47d2000-b47d5000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:39:19.786  7214  7214 W art     : b47d5000-b47d6000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:39:19.786  7214  7214 W art     : b47d6000-b47d7000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-05 15:39:19.786  7214  7214 W art     : b47d7000-b47d8000 r--p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b47d8000-b47f8000 r--s 00000000 00:0b 7184       /dev/__properties__
07-05 15:39:19.786  7214  7214 W art     : b47f8000-b5209000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:39:19.786  7214  7214 W art     : b5209000-b520a000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b520a000-b5253000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:39:19.786  7214  7214 W art     : b5253000-b5254000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-05 15:39:19.786  7214  7214 W art     : b5254000-b525c000 rw-p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b525c000-b525d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.786  7214  7214 W art     : b525d000-b5292000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:39:19.786  7214  7214 W art     : b5292000-b5293000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b5293000-b5294000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:39:19.786  7214  7214 W art     : b5294000-b5295000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-05 15:39:19.786  7214  7214 W art     : b5295000-b52ed000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-05 15:39:19.786  7214  7214 W art     : b52ed000-b52ee000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b52ee000-b52ef000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-05 15:39:19.786  7214  7214 W art     : b52ef000-b52f0000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-05 15:39:19.786  7214  7214 W art     : b52f1000-b52f7000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:39:19.786  7214  7214 W art     : b52f7000-b52f8000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:39:19.786  7214  7214 W art     : b52f8000-b52f9000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 15:39:19.786  7214  7214 W art     : b52f9000-b52fb000 rw-p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b52fc000-b5306000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:39:19.786  7214  7214 W art     : b5306000-b5309000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:39:19.786  7214  7214 W art     : b5309000-b530a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 15:39:19.786  7214  7214 W art     : b530b000-b5322000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:39:19.786  7214  7214 W art     : b5322000-b5323000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b5323000-b5324000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:39:19.786  7214  7214 W art     : b5324000-b5325000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 15:39:19.786  7214  7214 W art     : b5326000-b5330000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:39:19.786  7214  7214 W art     : b5330000-b5331000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:39:19.786  7214  7214 W art     : b5331000-b5332000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-05 15:39:19.786  7214  7214 W art     : b5332000-b5336000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:39:19.786  7214  7214 W art     : b5336000-b5337000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:39:19.786  7214  7214 W art     : b5337000-b5338000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 15:39:19.786  7214  7214 W art     : b5338000-b534e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-05 15:39:19.786  7214  7214 W art     : b534e000-b534f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-05 15:39:19.786  7214  7214 W art     : b534f000-b5350000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-05 15:39:19.786  7214  7214 W art     : b5350000-b535d000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:39:19.786  7214  7214 W art     : b535d000-b535e000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:39:19.786  7214  7214 W art     : b535e000-b535f000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-05 15:39:19.786  7214  7214 W art     : b535f000-b53bf000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-05 15:39:19.786  7214  7214 W art     : b53bf000-b53c2000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-05 15:39:19.786  7214  7214 W art     : b53c2000-b53c6000 rw-p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b53c6000-b5427000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-05 15:39:19.786  7214  7214 W art     : b5427000-b5428000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-05 15:39:19.786  7214  7214 W art     : b5428000-b5477000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:39:19.786  7214  7214 W art     : b5477000-b5479000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:39:19.786  7214  7214 W art     : b5479000-b547a000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-05 15:39:19.786  7214  7214 W art     : b547a000-b547b000 rw-p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b547b000-b5482000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:39:19.786  7214  7214 W art     : b5482000-b5483000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 15:39:19.786  7214  7214 W art     : b5483000-b5484000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
07-05 15:39:19.786  7214  7214 W art     : avc_common.so
07-05 15:39:19.786  7214  7214 W art     : b5485000-b5488000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:39:19.786  7214  7214 W art     : b5488000-b5489000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 15:39:19.786  7214  7214 W art     : b5489000-b548a000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
07-05 15:39:19.786  7214  7214 W art     : enc_common.so
07-05 15:39:19.786  7214  7214 W art     : b548b000-b548f000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:39:19.786  7214  7214 W art     : b548f000-b5490000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b5490000-b5491000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-05 15:39:19.786  7214  7214 W art     : b5491000-b5492000 rw-p 00005000 b3:17 2510       /syste
07-05 15:39:19.786  7214  7214 W art     : m/lib/libpowermanager.so
07-05 15:39:19.786  7214  7214 W art     : b5493000-b54b0000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:39:19.786  7214  7214 W art     : b54b0000-b54b1000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:39:19.786  7214  7214 W art     : b54b1000-b54b2000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 15:39:19.786  7214  7214 W art     : b54b3000-b54b8000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:39:19.786  7214  7214 W art     : b54b8000-b54b9000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:39:19.786  7214  7214 W art     : b54b9000-b54ba000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 15:39:19.786  7214  7214 W art     : b54bb000-b54ec000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:39:19.786  7214  7214 W art     : b54ec000-b54ef000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:39:19.786  7214  7214 W art     : b54ef000-b54f0000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 15:39:19.786  7214  7214 W art     : b54f1000-b552c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-05 15:39:19.786  7214  7214 W art     : b552c000-b552d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-05 15:39:19.786  7214  7214 W art     : b552d000-b552e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-05 15:39:19.786  7214  7214 W art     : b552f000-b5536000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:39:19.786  7214  7214 W art     : b5536000-b5537000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b5537000-b5538000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:39:19.786  7214  7214 W art     : b5538000-b5539000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-05 15:39:19.786  7214  7214 W art     : b5539000-b553a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.786  7214  7214 W art     : b553a000-b5551000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:39:19.786  7214  7214 W art     : b5551000-b5552000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b5552000-b5555000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:39:19.786  7214  7214 W art     : b5555000-b5556000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-05 15:39:19.786  7214  7214 W art     : b5556000-b5575000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:39:19.786  7214  7214 W art     : b5575000-b5576000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:39:19.786  7214  7214 W art     : b5576000-b5577000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-05 15:39:19.786  7214  7214 W art     : b5577000-b55b5000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-05 15:39:19.786  7214  7214 W art     : b55b5000-b55b6000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b55b6000-b55b8000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-05 15:39:19.786  7214  7214 W art     : b55b8000-b55b9000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-05 15:39:19.786  7214  7214 W art     : b55ba000-b55c1000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:39:19.786  7214  7214 W art     : b55c1000-b55c2000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:39:19.786  7214  7214 W art     : b55c2000-b55c3000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 15:39:19.786  7214  7214 W art     : b55c4000-b55c7000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:39:19.786  7214  7214 W art     : b55c7000-b55c8000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:39:19.786  7214  7214 W art     : b55c8000-b55c9000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 15:39:19.786  7214  7214 W art     : b55c9000-b55cf000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:39:19.786  7214  7214 W art     : b55cf000-b55d0000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b55d0000-b55d1000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:39:19.786  7214  7214 W art     : b55d1000-b55d2000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 15:39:19.786  7214  7214 W art     : b55d2000-b55db000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:39:19.786  7214  7214 W art     : b55db000-b55dc000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:39:19.786  7214  7214 W art     : b55dc000-b55dd000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-05 15:39:19.786  7214  7214 W art     : b55dd000-b566e000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:39:19.786  7214  7214 W art     : b566e000-b566f000 ---p 00000000 00:00 0 
07-05 15:39:19.786  7214  7214 W art     : b566f000-b567a000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:39:19.786  7214  7214 W art     : b567a000-b567b000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 15:39:19.786  7214  7214 W art     : b567c000-b568e000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-05 15:39:19.786  7214  7214 W art     : b568e000-b568f000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-05 15:39:19.786  7214  7214 W art     : b568f000-b5690000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-05 15:39:19.786  7214  7214 W art     : b5691000-b5696000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:39:19.786  7214  7214 W art     : b5696000-b5697000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:39:19.786  7214  7214 W art     : b5697000-b5698000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-05 15:39:19.786  7214  7214 W art     : b5699000-b5706000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:39:19.786  7214  7214 W art     : b5706000-b5707000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5707000-b5709000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:39:19.796  7214  7214 W art     : b5709000-b570a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-05 15:39:19.796  7214  7214 W art     : b570a000-b570b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b570b000-b5712000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:39:19.796  7214  7214 W art     : b5712000-b5713000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:39:19.796  7214  7214 W art     : b5713000-b5714000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 15:39:19.796  7214  7214 W art     : b5715000-b5795000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:39:19.796  7214  7214 W art     : b5795000-b5796000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5796000-b5797000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:39:19.796  7214  7214 W art     : b5797000-b5798000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 15:39:19.796  7214  7214 W art     : b5798000-b57af000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b57af000-b57e6000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-05 15:39:19.796  7214  7214 W art     : ib/libqc-opt.so
07-05 15:39:19.796  7214  7214 W art     : b57e6000-b57e7000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 15:39:19.796  7214  7214 W art     : b57e7000-b57e8000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 15:39:19.796  7214  7214 W art     : b57e8000-b5804000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:39:19.796  7214  7214 W art     : b5804000-b5805000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:39:19.796  7214  7214 W art     : b5805000-b5806000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 15:39:19.796  7214  7214 W art     : b5807000-b5868000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-05 15:39:19.796  7214  7214 W art     : b5868000-b586a000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-05 15:39:19.796  7214  7214 W art     : b586a000-b586b000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-05 15:39:19.796  7214  7214 W art     : b586c000-b5893000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-05 15:39:19.796  7214  7214 W art     : b5893000-b5894000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5894000-b5895000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-05 15:39:19.796  7214  7214 W art     : b5895000-b5896000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-05 15:39:19.796  7214  7214 W art     : b5897000-b589f000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:39:19.796  7214  7214 W art     : b589f000-b58a1000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:39:19.796  7214  7214 W art     : b58a1000-b58a2000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 15:39:19.796  7214  7214 W art     : b58a3000-b58a6000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-05 15:39:19.796  7214  7214 W art     : b58a6000-b58a7000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-05 15:39:19.796  7214  7214 W art     : b58a7000-b58a8000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-05 15:39:19.796  7214  7214 W art     : b58a8000-b58ac000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:39:19.796  7214  7214 W art     : b58ac000-b58ad000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b58ad000-b58ae000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:39:19.796  7214  7214 W art     : b58ae000-b58af000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-05 15:39:19.796  7214  7214 W art     : b58af000-b58bf000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-05 15:39:19.796  7214  7214 W art     : b58bf000-b58c0000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-05 15:39:19.796  7214  7214 W art     : b58c0000-b58c1000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-05 15:39:19.796  7214  7214 W art     : b58c1000-b5907000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5907000-b5910000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-05 15:39:19.796  7214  7214 W art     : b5910000-b5911000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-05 15:39:19.796  7214  7214 W art     : b5911000-b5912000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-05 15:39:19.796  7214  7214 W art     : b5913000-b5918000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-05 15:39:19.796  7214  7214 W art     : b5918000-b5919000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-05 15:39:19.796  7214  7214 W art     : b5919000-b591a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-05 15:39:19.796  7214  7214 W art     : b591a000-b591d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:39:19.796  7214  7214 W art     : b591d000-b591e000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b591e000-b591f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:39:19.796  7214  7214 W art     : b591f000-b5920000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 15:39:19.796  7214  7214 W art     : b5921000-b5939000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:39:19.796  7214  7214 W art     : b5939000-b593a000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b593a000-b593b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:39:19.796  7214  7214 W art     : b593b000-b593c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 15:39:19.796  7214  7214 W art     : b593d000-b5ad7000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:39:19.796  7214  7214 W art     : b5ad7000-b5ad8000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5ad8000-b5ae5000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:39:19.796  7214  7214 W art     : b5ae5000-b5ae6000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-05 15:39:19.796  7214  7214 W art     : b5ae6000-b5aea000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-05 15:39:19.796  7214  7214 W art     : b5aea000-b5aeb000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5aeb000-b5aec000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-05 15:39:19.796  7214  7214 W art     : b5aec000-b5aed000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-05 15:39:19.796  7214  7214 W art     : b5aed000-b5b00000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:39:19.796  7214  7214 W art     : b5b00000-b5b01000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:39:19.796  7214  7214 W art     : b5b01000-b5b02000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-05 15:39:19.796  7214  7214 W art     : b5b02000-b5b03000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:39:19.796  7214  7214 W art     : b5b03000-b5b4e000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:39:19.796  7214  7214 W art     : b5b4e000-b5b4f000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:39:19.796  7214  7214 W art     : b5b4f000-b5b50000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-05 15:39:19.796  7214  7214 W art     : b5b50000-b5b52000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5b53000-b5b64000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:39:19.796  7214  7214 W art     : b5b64000-b5b65000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5b65000-b5b66000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:39:19.796  7214  7214 W art     : b5b66000-b5b67000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 15:39:19.796  7214  7214 W art     : b5b68000-b5b72000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:39:19.796  7214  7214 W art     : b5b72000-b5b74000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:39:19.796  7214  7214 W art     : b5b74000-b5b75000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-05 15:39:19.796  7214  7214 W art     : b5b75000-b5b8e000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:39:19.796  7214  7214 W art     : b5b8e000-b5b8f000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:39:19.796  7214  7214 W art     : b5b8f000-b5b92000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-05 15:39:19.796  7214  7214 W art     : b5b92000-b5b96000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5b96000-b5c0a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-05 15:39:19.796  7214  7214 W art     : b5c0a000-b5c0b000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5c0b000-b5c0e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-05 15:39:19.796  7214  7214 W art     : b5c0e000-b5c0f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-05 15:39:19.796  7214  7214 W art     : b5c0f000-b5c10000 r--p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5c10000-b5c13000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:39:19.796  7214  7214 W art     : b5c13000-b5c14000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:39:19.796  7214  7214 W art     : b5c14000-b5c15000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-05 15:39:19.796  7214  7214 W art     : b5c15000-b5c16000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b5c16000-b5c1b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:39:19.796  7214  7214 W art     : b5c1b000-b5c1c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:39:19.796  7214  7214 W art     : b5c1c000-b5c1d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 15:39:19.796  7214  7214 W art     : b5c1d000-b5c1e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b5c1e000-b5c21000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:39:19.796  7214  7214 W art     : b5c21000-b5c22000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:39:19.796  7214  7214 W art     : b5c22000-b5c23000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 15:39:19.796  7214  7214 W art     : b5c23000-b5c24000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b5c24000-b5c28000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:39:19.796  7214  7214 W art     : b5c28000-b5c29000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:39:19.796  7214  7214 W art     : b5c29000-b5c2a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-05 15:39:19.796  7214  7214 W art     : b5c2a000-b5c2b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:39:19.796  7214  7214 W art     : b5c2b000-b5c2f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:39:19.796  7214  7214 W art     : b5c2f000-b5c30000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:39:19.796  7214  7214 W art     : b5c30000-b5c31000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 15:39:19.796  7214  7214 W art     : b5c31000-b5c32000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b5c32000-b5c40000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-05 15:39:19.796  7214  7214 W art     : b5c40000-b5c41000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b5c41000-b5c42000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-05 15:39:19.796  7214  7214 W art     : b5c42000-b5c43000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-05 15:39:19.796  7214  7214 W art     : b5c43000-b5c4d000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:39:19.796  7214  7214 W art     : b5c4d000-b5c50000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:39:19.796  7214  7214 W art     : b5c50000-b5c51000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 15:39:19.796  7214  7214 W art     : b5c51000-b5c52000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b5c52000-b5c5c000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-05 15:39:19.796  7214  7214 W art     : b5c5c000-b5c5f000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-05 15:39:19.796  7214  7214 W art     : b5c5f000-b5c60000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-05 15:39:19.796  7214  7214 W art     : b5c60000-b5c64000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:39:19.796  7214  7214 W art     : b5c64000-b5c65000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:39:19.796  7214  7214 W art     : b5c65000-b5c66000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-05 15:39:19.796  7214  7214 W art     : b5c66000-b5c67000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b5c67000-b5c74000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:39:19.796  7214  7214 W art     : b5c74000-b5c76000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:39:19.796  7214  7214 W art     : b5c76000-b5c77000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-05 15:39:19.796  7214  7214 W art     : b5c77000-b6089000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-05 15:39:19.796  7214  7214 W art     : b6089000-b608a000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b608a000-b6093000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-05 15:39:19.796  7214  7214 W art     : b6093000-b6097000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-05 15:39:19.796  7214  7214 W art     : b6097000-b6098000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6098000-b609f000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:39:19.796  7214  7214 W art     : b609f000-b60a0000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:39:19.796  7214  7214 W art     : b60a0000-b60a1000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-05 15:39:19.796  7214  7214 W art     : b60a1000-b60a2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b60a2000-b60bd000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-05 15:39:19.796  7214  7214 W art     : b60bd000-b60be000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-05 15:39:19.796  7214  7214 W art     : b60be000-b60bf000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-05 15:39:19.796  7214  7214 W art     : b60bf000-b60c0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b60c0000-b610c000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:39:19.796  7214  7214 W art     : b610c000-b610d000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b610d000-b610e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:39:19.796  7214  7214 W art     : b610e000-b610f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 15:39:19.796  7214  7214 W art     : b610f000-b6110000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6110000-b6114000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:39:19.796  7214  7214 W art     : b6114000-b6115000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6115000-b6116000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:39:19.796  7214  7214 W art     : b6116000-b6117000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-05 15:39:19.796  7214  7214 W art     : b6117000-b614f000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:39:19.796  7214  7214 W art     : b614f000-b6150000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:39:19.796  7214  7214 W art     : b6150000-b6151000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-05 15:39:19.796  7214  7214 W art     : b6151000-b6152000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6152000-b61f0000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-05 15:39:19.796  7214  7214 W art     : b61f0000-b61f1000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b61f1000-b620f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-05 15:39:19.796  7214  7214 W art     : b620f000-b6210000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-05 15:39:19.796  7214  7214 W art     : b6210000-b6383000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:39:19.796  7214  7214 W art     : b6383000-b638e000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:39:19.796  7214  7214 W art     : b638e000-b638f000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-05 15:39:19.796  7214  7214 W art     : b638f000-b64a6000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:39:19.796  7214  7214 W art     : b64a6000-b64b1000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:39:19.796  7214  7214 W art     : b64b1000-b64b2000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-05 15:39:19.796  7214  7214 W art     : b64b2000-b64b6000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b64b6000-b64da000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-05 15:39:19.796  7214  7214 W art     : b64da000-b64dc000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-05 15:39:19.796  7214  7214 W art     : b64dc000-b64dd000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-05 15:39:19.796  7214  7214 W art     : b64dd000-b6583000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-05 15:39:19.796  7214  7214 W art     : b6583000-b6590000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-05 15:39:19.796  7214  7214 W art     : b6590000-b6591000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-05 15:39:19.796  7214  7214 W art     : b6591000-b6592000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6592000-b65e5000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:39:19.796  7214  7214 W art     : b65e5000-b65e6000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b65e6000-b65e7000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:39:19.796  7214  7214 W art     : b65e7000-b65e8000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-05 15:39:19.796  7214  7214 W art     : b65e8000-b65ed000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b65ed000-b65ff000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-05 15:39:19.796  7214  7214 W art     : b65ff000-b6600000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6600000-b6601000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-05 15:39:19.796  7214  7214 W art     : b6601000-b6602000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-05 15:39:19.796  7214  7214 W art     : b6602000-b6609000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:39:19.796  7214  7214 W art     : b6609000-b660a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:39:19.796  7214  7214 W art     : b660a000-b660b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 15:39:19.796  7214  7214 W art     : b660b000-b660c000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b660c000-b660f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-05 15:39:19.796  7214  7214 W art     : b660f000-b6610000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-05 15:39:19.796  7214  7214 W art     : b6610000-b6611000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-05 15:39:19.796  7214  7214 W art     : b6611000-b6615000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-05 15:39:19.796  7214  7214 W art     : b6615000-b6616000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-05 15:39:19.796  7214  7214 W art     : b6616000-b6617000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-05 15:39:19.796  7214  7214 W art     : b6617000-b6625000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:39:19.796  7214  7214 W art     : b6625000-b6626000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6626000-b6627000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:39:19.796  7214  7214 W art     : b6627000-b6628000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-05 15:39:19.796  7214  7214 W art     : b6628000-b6631000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:39:19.796  7214  7214 W art     : b6631000-b6632000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:39:19.796  7214  7214 W art     : b6632000-b6633000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 15:39:19.796  7214  7214 W art     : b6633000-b6699000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-05 15:39:19.796  7214  7214 W art     : b6699000-b669a000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b669a000-b669c000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-05 15:39:19.796  7214  7214 W art     : b669c000-b66a5000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-05 15:39:19.796  7214  7214 W art     : b66a5000-b66a8000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b66a8000-b673f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-05 15:39:19.796  7214  7214 W art     : b673f000-b6741000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-05 15:39:19.796  7214  7214 W art     : b6741000-b6742000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-05 15:39:19.796  7214  7214 W art     : b6742000-b6743000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6743000-b6a64000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-05 15:39:19.796  7214  7214 W art     : b6a64000-b6a65000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6a65000-b6a80000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-05 15:39:19.796  7214  7214 W art     : b6a80000-b6a84000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-05 15:39:19.796  7214  7214 W art     : b6a84000-b6a89000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6a89000-b6a91000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:39:19.796  7214  7214 W art     : b6a91000-b6a92000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:39:19.796  7214  7214 W art     : b6a92000-b6a93000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 15:39:19.796  7214  7214 W art     : b6a93000-b6ac1000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:39:19.796  7214  7214 W art     : b6ac1000-b6ac2000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6ac2000-b6ac9000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:39:19.796  7214  7214 W art     : b6ac9000-b6aca000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-05 15:39:19.796  7214  7214 W art     : b6aca000-b6b10000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:39:19.796  7214  7214 W art     : b6b10000-b6b11000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6b11000-b6b14000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:39:19.796  7214  7214 W art     : b6b14000-b6b15000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-05 15:39:19.796  7214  7214 W art     : b6b15000-b6b30000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-05 15:39:19.796  7214  7214 W art     : b6b30000-b6b34000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-05 15:39:19.796  7214  7214 W art     : b6b34000-b6b35000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-05 15:39:19.796  7214  7214 W art     : b6b35000-b6b82000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-05 15:39:19.796  7214  7214 W art     : b6b82000-b6b83000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6b83000-b6b8f000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-05 15:39:19.796  7214  7214 W art     : b6b8f000-b6b90000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-05 15:39:19.796  7214  7214 W art     : b6b90000-b6b9d000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-05 15:39:19.796  7214  7214 W art     : b6b9d000-b6b9e000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6b9e000-b6b9f000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-05 15:39:19.796  7214  7214 W art     : b6b9f000-b6ba0000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-05 15:39:19.796  7214  7214 W art     : b6ba0000-b6ba8000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:39:19.796  7214  7214 W art     : b6ba8000-b6ba9000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6ba9000-b6baa000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:39:19.796  7214  7214 W art     : b6baa000-b6bab000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-05 15:39:19.796  7214  7214 W art     : b6bab000-b6bb2000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:39:19.796  7214  7214 W art     : b6bb2000-b6bb3000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:39:19.796  7214  7214 W art     : b6bb3000-b6bb4000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-05 15:39:19.796  7214  7214 W art     : b6bb4000-b6bc8000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-05 15:39:19.796  7214  7214 W art     : b6bc8000-b6bca000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-05 15:39:19.796  7214  7214 W art     : b6bca000-b6bcb000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-05 15:39:19.796  7214  7214 W art     : b6bcb000-b6bf3000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:39:19.796  7214  7214 W art     : b6bf3000-b6bf5000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:39:19.796  7214  7214 W art     : b6bf5000-b6bf6000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-05 15:39:19.796  7214  7214 W art     : b6bf6000-b6bf9000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:39:19.796  7214  7214 W art     : b6bf9000-b6bfa000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:39:19.796  7214  7214 W art     : b6bfa000-b6bfb000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-05 15:39:19.796  7214  7214 W art     : b6bfb000-b6c04000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:39:19.796  7214  7214 W art     : b6c04000-b6c05000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:39:19.796  7214  7214 W art     : b6c05000-b6c06000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-05 15:39:19.796  7214  7214 W art     : b6c06000-b6c26000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-05 15:39:19.796  7214  7214 W art     : b6c26000-b6c27000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-05 15:39:19.796  7214  7214 W art     : b6c27000-b6c28000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-05 15:39:19.796  7214  7214 W art     : b6c28000-b6c9b000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-05 15:39:19.796  7214  7214 W art     : b6c9b000-b6c9f000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-05 15:39:19.796  7214  7214 W art     : b6c9f000-b6ca2000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-05 15:39:19.796  7214  7214 W art     : b6ca2000-b6cac000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6cac000-b6d34000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-05 15:39:19.796  7214  7214 W art     : b6d34000-b6d35000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6d35000-b6d39000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-05 15:39:19.796  7214  7214 W art     : b6d39000-b6d3a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-05 15:39:19.796  7214  7214 W art     : b6d3a000-b6d3b000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6d3b000-b6d64000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:39:19.796  7214  7214 W art     : b6d64000-b6d65000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6d65000-b6d68000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:39:19.796  7214  7214 W art     : b6d68000-b6d69000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-05 15:39:19.796  7214  7214 W art     : b6d69000-b6e43000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:39:19.796  7214  7214 W art     : b6e43000-b6e4a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:39:19.796  7214  7214 W art     : b6e4a000-b6e52000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 15:39:19.796  7214  7214 W art     : b6e52000-b6e53000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6e53000-b6e54000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:39:19.796  7214  7214 W art     : b6e54000-b6e55000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-05 15:39:19.796  7214  7214 W art     : b6e55000-b6e56000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6e56000-b6e59000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6e59000-b6e7e000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-05 15:39:19.796  7214  7214 W art     : b6e7e000-b6e7f000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6e7f000-b6e86000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-05 15:39:19.796  7214  7214 W art     : b6e86000-b6e87000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-05 15:39:19.796  7214  7214 W art     : b6e87000-b6e8e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-05 15:39:19.796  7214  7214 W art     : b6e8e000-b6e8f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-05 15:39:19.796  7214  7214 W art     : b6e8f000-b6e90000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-05 15:39:19.796  7214  7214 W art     : b6e90000-b6e91000 r--p 00000000 00:00 0          [anon:linker_alloc],
07-05 15:39:19.796  7214  7214 W art     : b6e91000-b6ea9000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-05 15:39:19.796  7214  7214 W art     : b6ea9000-b6eaa000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6eaa000-b6eab000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-05 15:39:19.796  7214  7214 W art     : b6eab000-b6eac000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-05 15:39:19.796  7214  7214 W art     : b6eac000-b6eba000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-05 15:39:19.796  7214  7214 W art     : b6eba000-b6ebb000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6ebb000-b6ebc000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-05 15:39:19.796  7214  7214 W art     : b6ebc000-b6ebd000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-05 15:39:19.796  7214  7214 W art     : b6ebd000-b6ebe000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:39:19.796  7214  7214 W art     : b6ebe000-b6ec0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6ec0000-b6ec1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6ec1000-b6ec2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 15:39:19.796  7214  7214 W art     : b6ec2000-b6ec3000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-05 15:39:19.796  7214  7214 W art     : b6ec3000-b6ec4000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 15:39:19.796  7214  7214 W art     : b6ec4000-b6ee4000 r--s 00000000 00:0b 7184       /dev/__properties__
07-05 15:39:19.796  7214  7214 W art     : b6ee4000-b6ee5000 r--p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6ee5000-b6ee6000 ---p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6ee6000-b6ee8000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-05 15:39:19.796  7214  7214 W art     : b6ee8000-b6ee9000 r-xp 00000000 00:00 0          [sigpage]
07-05 15:39:19.796  7214  7214 W art     : b6ee9000-b6f04000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-05 15:39:19.796  7214  7214 W art     : b6f04000-b6f05000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-05 15:39:19.796  7214  7214 W art     : b6f05000-b6f07000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-05 15:39:19.796  7214  7214 W art     : b6f07000-b6f09000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : b6f09000-b6f0e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-05 15:39:19.796  7214  7214 W art     : b6f0e000-b6f0f000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-05 15:39:19.796  7214  7214 W art     : b6f0f000-b6f10000 rw-p 00000000 00:00 0 
07-05 15:39:19.796  7214  7214 W art     : bec30000-bec51000 rw-p 00000000 00:00 0          [stack]
07-05 15:39:19.796  7214  7214 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-05 15:39:19.836  7214  7214 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 15:39:19.886  7214  7214 I Radio-JNI: register_android_hardware_Radio DONE
07-05 15:39:19.896  7214  7214 E AffinityControl: AffinityControl: registerfunction enter
07-05 15:39:19.916  7214  7214 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 15:39:19.936   770  1731 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-05 15:39:19.946   770  1731 D ActivityManager: mDVFSHelper.acquire()
07-05 15:39:19.946   770  1731 V WindowManager: addAppToken: AppWindowToken{2385ea7 token=Token{4474b66 ActivityRecord{f8507c1 u0 com.test.thalitest/.MainActivity t64}}} to stack=1 task=64 at 0
07-05 15:39:19.956   770   916 D SecWifiDisplayUtil: Metadata value : none
07-05 15:39:19.956   770   916 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7b9f V.E...... R.....ID 0,0-0,0}
07-05 15:39:19.956   770   916 D ISSUE_DEBUG: InputChannelName : 70a70b5 Starting com.test.thalitest
07-05 15:39:19.966  7235  7235 E Zygote  : v2
07-05 15:39:19.966  7235  7235 I libpersona: KNOX_SDCARD checking this for 10004
07-05 15:39:19.966  7235  7235 I libpersona: KNOX_SDCARD not a persona
07-05 15:39:19.966   770  1731 I ActivityManager: Start proc 7235:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 15:39:19.966   770  1731 D InputDispatcher: Focused application set to: xxxx
07-05 15:39:19.966  7235  7235 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:39:19.966   770  1731 D InputDispatcher: Focus left window: 3584
07-05 15:39:19.966  7235  7235 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 15:39:19.966   770   879 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{27ddb6f u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-05 15:39:19.966  7235  7235 E Zygote  : accessInfo : 0
07-05 15:39:19.966   770  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-05 15:39:19.966  7235  7235 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 15:39:19.966  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
07-05 15:39:19.966  7214  7214 D AndroidRuntime: Shutting down VM
07-05 15:39:19.976   294   294 I SurfaceFlinger: id=21 createSurf (1x1),1 flag=404, uhalitest
07-05 15:39:19.986   770   916 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
07-05 15:39:19.986   770   916 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 15:39:19.986   770   916 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-05 15:39:19.986   770   916 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 15:39:19.986   770   916 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-05 15:39:19.996  7235  7235 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:39:19.996  7235  7235 D ActivityThread: Added TimaKeyStore provider
07-05 15:39:19.996   770   787 V WindowOrientationListener: setCurrentAppOrientation :-1
07-05 15:39:19.996   770   787 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 15:39:19.996   770   879 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{70a70b5 u0 d0 Starting com.test.thalitest}
07-05 15:39:19.996  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-05 15:39:20.006   770   787 D ActivityManager:  Launching com.test.thalitest, updated priority
07-05 15:39:20.016   770   876 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-05 15:39:20.026  1732  1876 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-05 15:39:20.026  1732  1732 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-05 15:39:20.036   294   348 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
07-05 15:39:20.036   294  1282 I SurfaceFlinger: id=19 Removed VSBConnecti (7/11)
07-05 15:39:20.046   294   348 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/11)
07-05 15:39:20.046   770   916 V WindowStateAnimator: Finishing drawing window Window{70a70b5 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-05 15:39:20.046   294   348 I SurfaceFlinger: id=20 Removed VSBConnecti (5/10)
07-05 15:39:20.046   294  1283 I SurfaceFlinger: id=20 Removed VSBConnecti (-2/10)
07-05 15:39:20.046   294   358 D libEGL  : eglTerminate EGLDisplay = 0xb65bf64c
07-05 15:39:20.056   294   358 D libEGL  : eglTerminate EGLDisplay = 0xb65bf64c
07-05 15:39:20.056   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec863a4
07-05 15:39:20.056   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec863a4
07-05 15:39:20.056   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec86364
07-05 15:39:20.056  3584  3584 V ActivityThread: updateVisibility : ActivityRecord{b9d2aa1 token=android.os.BinderProxy@4556e33 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
07-05 15:39:20.066   294  1283 I SurfaceFlinger: id=8 Removed Mauncher (4/9)
07-05 15:39:20.066   294   358 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-05 15:39:20.066  2282  2300 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-05 15:39:20.066  1732  1732 V ActivityThread: updateVisibility : ActivityRecord{4e52c5e token=android.os.BinderProxy@f1d76a4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 15:39:20.066  1732  1732 D Launcher: onTrimMemory. Level: 20
07-05 15:39:20.066   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec863a4
07-05 15:39:20.326   770   787 I WindowManager: Screenshot max retries 4 of Token{4474b66 ActivityRecord{f8507c1 u0 com.test.thalitest/.MainActivity t64}} appWin=Window{70a70b5 u0 d0 Starting com.test.thalitest} drawState=4
07-05 15:39:20.336   770  1323 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-05 15:39:20.336  7235  7235 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 15:39:20.346   770  3509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-05 15:39:20.366  7235  7235 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 15:39:20.366  7235  7235 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 15:39:20.386  7235  7235 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
07-05 15:39:20.406  7235  7235 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 15:39:20.416  7235  7235 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-05 15:39:20.426  7235  7235 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 1861-1864)
07-05 15:39:20.426  7235  7235 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-05 15:39:20.446  7235  7235 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3696c5d}
07-05 15:39:20.446  7235  7235 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-05 15:39:20.446  7235  7235 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 15:39:20.446  7235  7252 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-05 15:39:20.456  7235  7235 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-05 15:39:20.486  7235  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-05 15:39:20.486  7235  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-05 15:39:20.486  7235  7235 I Adreno-EGL: Build Date: 01/28/16 Thu
07-05 15:39:20.486  7235  7235 I Adreno-EGL: Local Branch: ss
07-05 15:39:20.486  7235  7235 I Adreno-EGL: Remote Branch: 
07-05 15:39:20.486  7235  7235 I Adreno-EGL: Local Patches: 
07-05 15:39:20.486  7235  7235 I Adreno-EGL: Reconstruct Branch: 
07-05 15:39:20.486  7235  7235 D libEGL  : eglInitialize EGLDisplay = 0xbea91dac
07-05 15:39:20.526   770  1744 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
07-05 15:39:20.526   770  1744 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
07-05 15:39:20.576  7235  7235 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
07-05 15:39:20.586  7235  7235 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 15:39:20.586  7235  7235 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-05 15:39:20.586  7235  7235 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
07-05 15:39:20.586  7235  7235 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
07-05 15:39:20.606  7235  7235 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
07-05 15:39:20.616  7235  7235 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-05 15:39:20.736  7235  7235 D SecWifiDisplayUtil: Metadata value : none
07-05 15:39:20.736  7235  7235 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7eb0683 I.E...... R.....ID 0,0-0,0}
07-05 15:39:20.746  7235  7287 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-05 15:39:20.746   770  1744 D ISSUE_DEBUG: InputChannelName : 223569e com.test.thalitest/com.test.thalitest.MainActivity
07-05 15:39:20.746   770  2433 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 15:39:20.746   770  2433 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:39:20.746   770   770 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:39:20.746   770   770 I KnoxTimeoutHandler: Shared devices show user statefalse
07-05 15:39:20.766  7235  7235 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 7235
07-05 15:39:20.766   770  1744 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/7235 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 15:39:20.766   770  1332 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-05 15:39:20.776   770  1332 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 15:39:20.776   770  1332 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-05 15:39:20.776   770  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:20.776   770  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:20.776   770  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:20.776   770  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-05 15:39:20.776   770  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 15:39:20.776   770  1332 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-05 15:39:20.776   770  1332 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 15:39:20.776  7235  7252 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
07-05 15:39:20.786  7235  7235 D SecWifiDisplayUtil: Metadata value : none
07-05 15:39:20.796   294   294 I SurfaceFlinger: id=22 createSurf (1x1),1 flag=404, NainActivit
07-05 15:39:20.796   770   786 D InputDispatcher: Focus entered window: 7235
07-05 15:39:20.806   770   916 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:770 uid:1000
07-05 15:39:20.806   770   916 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 15:39:20.806   770   916 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:770 uid:1000
07-05 15:39:20.806   770   916 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 15:39:20.806  7235  7287 D libEGL  : eglInitialize EGLDisplay = 0x9c77f7c4
07-05 15:39:20.806  7235  7287 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 15:39:20.846  7235  7235 V ActivityThread: updateVisibility : ActivityRecord{37ffc8a token=android.os.BinderProxy@9d67932 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 15:39:20.856  7235  7235 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-05 15:39:20.856  7235  7235 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-05 15:39:20.856   770  1744 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 15:39:20.866  7235  7235 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-05 15:39:20.876   770  2468 V WindowStateAnimator: Finishing drawing window Window{223569e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-05 15:39:20.886   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbec86364
07-05 15:39:20.886  7235  7235 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-05 15:39:20.886  7235  7235 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9d67932 time:312324
07-05 15:39:20.886   770   916 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:39:20.886   770   770 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 15:39:20.886   770   916 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +563ms (total +939ms)
07-05 15:39:20.886   770   916 D ActivityManager: mDVFSHelper.release()
07-05 15:39:20.886   770   916 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f8507c1 u0 com.test.thalitest/.MainActivity t64} time:312326
07-05 15:39:20.886   770   916 D ViewRootImpl: #3 mView = null
07-05 15:39:20.886   770   770 I KnoxTimeoutHandler: SD activityfalse
07-05 15:39:20.896   294   358 I SurfaceFlinger: id=21 Removed uhalitest (7/9)
07-05 15:39:20.896   294  1283 I SurfaceFlinger: id=21 Removed uhalitest (-2/9)
07-05 15:39:20.896   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec863a4
07-05 15:39:20.936  7235  7299 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 15:39:20.936  7235  7299 D libEGL  : eglInitialize EGLDisplay = 0x9a1d03ec
07-05 15:39:20.986  7235  7235 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7235
07-05 15:39:21.136  7235  7235 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-05 15:39:21.166  7235  7235 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
07-05 15:39:21.236  7235  7309 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1716258512
07-05 15:39:21.246  7235  7309 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 15:39:21.246  7235  7309 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 15:39:21.246  7235  7309 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 15:39:21.246  7235  7309 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 15:39:21.246  7235  7309 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 15:39:21.246  7235  7309 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42b4930 added. We now have 1 listener(s)
07-05 15:39:21.246  7235  7309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
07-05 15:39:21.246  7235  7309 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
07-05 15:39:21.246  7235  7309 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 15:39:21.246  7235  7309 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fce26cf added. We now have 1 listener(s)
07-05 15:39:21.256  7235  7309 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 15:39:21.256  7235  7309 D BluetoothAdapter: STATE_ON
07-05 15:39:21.256  7235  7309 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 15:39:21.256  7235  7309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 15:39:21.256  7235  7309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 15:39:21.256  7235  7309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 15:39:21.256  7235  7309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-05 15:39:21.266  7235  7309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 15:39:21.266  7235  7309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
07-05 15:39:21.266  7235  7309 D BluetoothAdapter: STATE_ON
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 15:39:21.266  7235  7309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 15:39:21.266  7235  7309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 15:39:21.266  7235  7309 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 15:39:21.266  7235  7309 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 15:39:21.276  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 15:39:21.276  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 15:39:21.286  7235  7235 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 15:39:21.336   770  3510 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-05 15:39:21.756  1446  1446 D Recents : onTaskStackChanged
,07-05 15:39:21.766  1446  1446 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-05 15:39:22.016  7235  7316 W jxcore-log: Initializing JXcore engine
07-05 15:39:22.016  7235  7316 W jxcore-log: JXcore engine is ready
,07-05 15:39:22.056  2410  2410 E audit   : type=1400 msg=audit(1467725962.056:287): avc:  denied  { ioctl } for  pid=7316 comm="Thread-979" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 15:39:22.056  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-05 15:39:22.056  2410  2410 E audit   : type=1300 msg=audit(1467725962.056:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=1 a3=99a103c8 items=0 ppid=355 ppcomm=main pid=7316 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-979" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 15:39:22.056  2410  2410 E audit   : type=1327 msg=audit(1467725962.056:287): proctitle="com.test.thalitest"
07-05 15:39:22.056  2410  2410 E audit   : type=1320 msg=audit(1467725962.056:287): 
07-05 15:39:22.056  2410  2410 E audit   : type=1400 msg=audit(1467725962.056:288): avc:  denied  { ioctl } for  pid=7316 comm="Thread-979" path="socket:[46862]" dev="sockfs" ino=46862 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 15:39:22.056  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-05 15:39:22.066  2410  2410 E audit   : type=1300 msg=audit(1467725962.056:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=1 a3=99a103c8 items=0 ppid=355 ppcomm=main pid=7316 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-979" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 15:39:22.066  2410  2410 E audit   : type=1327 msg=audit(1467725962.056:288): proctitle="com.test.thalitest"
07-05 15:39:22.066  2410  2410 E audit   : type=1320 msg=audit(1467725962.056:288): 
,07-05 15:39:22.076  7235  7316 W jxcore-log: Starting JXcore engine
,07-05 15:39:22.146  7235  7316 W jxcore-log: Platform android
07-05 15:39:22.146  7235  7316 W jxcore-log: 
07-05 15:39:22.146  7235  7316 W jxcore-log: Process ARCH arm
07-05 15:39:22.146  7235  7316 W jxcore-log: 
,07-05 15:39:22.336  7235  7316 I jxcore-log: JXcore Cordova bridge is ready!
07-05 15:39:22.336  7235  7316 I jxcore-log: 
,07-05 15:39:22.336  7235  7316 W jxcore-log: JXcore engine is started
,07-05 15:39:22.976   770  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/64_task.xml.bak
,07-05 15:39:24.516   770  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:39:24.526   770  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:39:24.526   770  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:39:24.546   770  1231 I TLC_TIMA_PKM_initialize: initializing...
,07-05 15:39:24.546   770  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-05 15:39:24.546   770  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 15:39:24.556   770  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-05 15:39:24.556   770  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 15:39:24.556   770  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 15:39:24.556   770  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-05 15:39:24.556   770  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-05 15:39:24.566   770  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 15:39:24.566   770  1231 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 15:39:24.606   770  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 15:39:24.616   770  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 15:39:24.616   770  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 15:39:26.406   770  3509 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 15:39:27.396   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:39:27.396   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:39:27.416   770  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:39:27.416   770  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:39:28.806   770  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:39:28.806   770  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:39:28.816   770  1320 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:39:28.816   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:39:28.826   770   770 I MotionRecognitionService: Plugged
,07-05 15:39:28.826   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:39:28.826   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:39:28.826   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:39:28.836   770  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 15:39:28.836   770  1320 D BatteryService: stay LED for fully charged
,07-05 15:39:28.846  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:39:28.846  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:39:28.846  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:39:28.876  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:39:28.876  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:39:28.876  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:28.876  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:28.876  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:39:29.426   770  3509 D SSRM:n  : SIOP:: AP = 330, PST = 324, CUR = 450, LCD = 0
,07-05 15:39:29.946   770   957 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 15:39:29.996   770   957 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-05 15:39:39.486   770  3509 D SSRM:n  : SIOP:: AP = 330, PST = 324, CUR = 450, LCD = 0
,07-05 15:39:39.706   770  1585 E Watchdog: !@Sync 10 [07-05 15:39:39.707]
,07-05 15:39:39.776   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:39:40.806   770  1237 V AlarmManager: Expired Alarm result :4
,07-05 15:39:40.886   770   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:39:40.886   770   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:39:40.886   770   787 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-05 15:39:40.886   770   787 D BatteryService: stay LED for fully charged
,07-05 15:39:40.896   770  1237 I ActivityManager: Start proc 7335:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-05 15:39:40.906  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:39:40.906  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 15:39:40.906  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:39:40.916  7335  7335 E Zygote  : v2
,07-05 15:39:40.916  7335  7335 I libpersona: KNOX_SDCARD checking this for 1000
07-05 15:39:40.916  7335  7335 I libpersona: KNOX_SDCARD not a persona
,07-05 15:39:40.926  7335  7335 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:39:40.926  7335  7335 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:39:40.926  7335  7335 E Zygote  : accessInfo : 0
,07-05 15:39:40.946  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:39:40.946  1550  1550 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 15:39:40.946  1550  1550 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 15:39:40.966  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:39:40.966  1550  1550 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-05 15:39:40.986   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:39:40.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:40.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:39:40.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:40.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:39:40.996   770   770 I MotionRecognitionService: Plugged
07-05 15:39:40.996   770   770 D MotionRecognitionService:   cableConnection= 1
07-05 15:39:40.996   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:39:40.996   770   770 D MotionRecognitionService: skip setTransmitPower. 
07-05 15:39:40.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:40.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:39:40.996  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:39:40.996  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:39:40.996  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:39:41.006  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:39:41.006  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:39:41.006  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:41.006  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:41.006  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:39:41.006  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:39:41.036  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 15:39:41.036  7335  7335 D ActivityThread: Added TimaKeyStore provider
,07-05 15:39:41.056  7335  7335 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-05 15:39:41.066  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:39:41.076  7335  7335 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-05 15:39:41.086  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:39:41.096   770  5181 I ActivityManager: Killing 6214:com.android.email/u0a162 (adj 15): DHA:empty #37
,07-05 15:39:41.116   770  1728 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,07-05 15:39:43.596   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:39:43.596   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:39:43.596   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:39:44.846  1550  1550 I wpa_supplicant: nl80211: Received scan results (9 BSSes)
,07-05 15:39:44.856   319  1123 D Netd    : Iface wlan0 link up
,07-05 15:39:44.866  1550  1550 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-05 15:39:44.876   770   882 D Tethering: interfaceLinkStateChanged wlan0, true
,07-05 15:39:44.886   770   882 D Tethering: interfaceStatusChanged wlan0, true
,07-05 15:39:44.896   770  1324 D WifiP2pService: InactiveState{ what=147461 }
,07-05 15:39:44.896   770  1324 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-05 15:39:44.896   770  1324 D WifiP2pService: DefaultState{ what=147461 }
,07-05 15:39:44.956   770   876 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{657fd7c u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b42f70d 1380:com.android.systemui/u0a58}
,07-05 15:39:49.546   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450, LCD = 0
,07-05 15:39:50.976   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:39:59.606   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:39:59.786   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:39:59.966   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:39:59.966   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:39:59.966   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:39:59.996   770  1237 V AlarmManager: Expired Alarm result :8
,07-05 15:40:01.066   770  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:40:09.666   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:40:09.706   770  1585 E Watchdog: !@Sync 11 [07-05 15:40:09.713]
,07-05 15:40:11.136   770  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:40:11.146   770  1618 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:40:11.146   770  1618 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:40:11.146   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:11.156   770   770 I MotionRecognitionService: Plugged
,07-05 15:40:11.166   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:40:11.166   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:40:11.176   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:11.176   770  1618 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 15:40:11.176   770  1618 D BatteryService: stay LED for fully charged
,07-05 15:40:11.186  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:11.186  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:11.186  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:11.196  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:40:11.196  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:11.216  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:11.216  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:11.216  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:16.856  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:40:16.896  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:40:16.896  2075  2075 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 15:40:16.966  5948  5986 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 15:40:16.966  5948  5986 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 15:40:16.966   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:40:16.966   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:40:16.966   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:40:16.986   319  1126 D EnterpriseController: netId is 0
07-05 15:40:16.986   319  1126 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,07-05 15:40:19.726   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:40:19.786   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:40:21.226   770  2433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:40:21.236   770  2433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:40:21.236   770  2433 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:40:21.236   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:21.246   770   770 I MotionRecognitionService: Plugged
,07-05 15:40:21.256   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:40:21.256   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:40:21.256   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:21.256   770  2433 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:40:21.266   770  2433 D BatteryService: stay LED for fully charged
,07-05 15:40:21.276  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:21.276  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:21.286  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:21.296  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:40:21.296  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:21.306  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:21.306  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:21.306  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:29.776   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:40:31.316   770  2468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:40:31.326   770  2468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:40:31.326   770  2468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:40:31.326   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:31.336   770   770 I MotionRecognitionService: Plugged
,07-05 15:40:31.336   770   770 D MotionRecognitionService:   cableConnection= 1
07-05 15:40:31.346   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:40:31.346   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:31.346   770  2468 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 15:40:31.356   770  2468 D BatteryService: stay LED for fully charged
,07-05 15:40:31.356  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:31.356  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:31.366  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:31.386  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:40:31.386  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:31.396  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-05 15:40:31.406  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:31.406  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,07-05 15:40:39.716   770  1585 E Watchdog: !@Sync 12 [07-05 15:40:39.721]
,07-05 15:40:39.786   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:40:39.836   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:40:41.096  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:40:41.396   770  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:40:41.396   770  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:40:41.396   770  1220 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:40:41.406   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:41.416   770   770 I MotionRecognitionService: Plugged
,07-05 15:40:41.416   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:40:41.416   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:40:41.416   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:41.426   770  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 15:40:41.426   770  1220 D BatteryService: stay LED for fully charged
,07-05 15:40:41.436  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:41.436  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:40:41.436  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:41.446  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:40:41.446  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:41.456  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:41.456  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:41.456  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:48.486   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:40:48.486   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:40:48.486   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:40:49.896   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:40:51.486   770  5181 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:40:51.486   770  5181 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:40:51.486   770  5181 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:40:51.486   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:40:51.506   770   770 I MotionRecognitionService: Plugged
,07-05 15:40:51.506   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:40:51.506   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:40:51.506   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:40:51.506   770  5181 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 15:40:51.516   770  5181 D BatteryService: stay LED for fully charged
,07-05 15:40:51.526  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:51.536  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:40:51.536  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:40:51.546  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:40:51.546  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:40:51.556  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:51.556  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:40:51.556  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:40:59.796   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:40:59.946   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450, LCD = 0
,07-05 15:41:01.566   770  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:41:01.566   770  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:41:01.566   770  1320 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:41:01.566   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:41:01.586   770   770 I MotionRecognitionService: Plugged
,07-05 15:41:01.586   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:41:01.586   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:41:01.586   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:01.586   770  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 15:41:01.596   770  1320 D BatteryService: stay LED for fully charged
,07-05 15:41:01.606  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:41:01.606  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:41:01.606  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:41:01.636  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:41:01.636  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:01.636  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:01.636  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:01.636  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:09.716   770  1585 E Watchdog: !@Sync 13 [07-05 15:41:09.727]
,07-05 15:41:10.006   770  3509 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450, LCD = 0
,07-05 15:41:11.666   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:41:11.676   770  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:41:11.676   770  1731 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:41:11.676   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:41:11.686   770   770 I MotionRecognitionService: Plugged
,07-05 15:41:11.686  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:41:11.686  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:41:11.686  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 15:41:11.686   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:41:11.686   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:41:11.686   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:11.696   770  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:41:11.696   770  1731 D BatteryService: stay LED for fully charged
,07-05 15:41:11.706  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:41:11.706  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:11.716  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:11.716  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:41:11.716  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:19.796   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:41:20.066   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450, LCD = 0
,07-05 15:41:26.766   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:41:26.766   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:41:26.766   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:41:30.126   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450, LCD = 0
,07-05 15:41:39.726   770  1585 E Watchdog: !@Sync 14 [07-05 15:41:39.732]
,07-05 15:41:39.806   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:41:40.176   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450, LCD = 0
,07-05 15:41:41.116  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:41:41.246  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 117ms lastUpdatedAfter : 180264ms
,07-05 15:41:41.726   770  2468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:41:41.726   770  2468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:41:41.726   770  2468 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:41:41.736   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:41:41.746   770   770 I MotionRecognitionService: Plugged
,07-05 15:41:41.746   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:41:41.746   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:41:41.756   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:41:41.756   770  2468 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 15:41:41.756   770  2468 D BatteryService: stay LED for fully charged
,07-05 15:41:41.776  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:41:41.776  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:41:41.776  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:41:41.796  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:41:41.796  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:41:41.806  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:41.806  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:41.806  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:41:48.126   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:41:48.126   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:41:48.126   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:41:50.236   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450, LCD = 0
,07-05 15:41:59.806   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:00.296   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450, LCD = 0
,07-05 15:42:09.726   770  1585 E Watchdog: !@Sync 15 [07-05 15:42:09.736]
,07-05 15:42:10.346   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450, LCD = 0
,07-05 15:42:11.806   770  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:42:11.816   770  1422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:42:11.816   770  1422 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:42:11.816   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:42:11.826   770   770 I MotionRecognitionService: Plugged
,07-05 15:42:11.826   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:42:11.836   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:42:11.836   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:42:11.836   770  1422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:42:11.836   770  1422 D BatteryService: stay LED for fully charged
,07-05 15:42:11.846  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:42:11.856  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:42:11.856  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:42:11.886  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:11.886  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:11.886  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:11.886  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:42:11.886  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:42:14.096   362   362 I bootchecker: bootchecker wake up!!
,07-05 15:42:19.816   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:20.406   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450, LCD = 0
,07-05 15:42:30.466   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450, LCD = 0
,07-05 15:42:39.736   770  1585 E Watchdog: !@Sync 16 [07-05 15:42:39.740]
,07-05 15:42:39.816   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:40.526   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450, LCD = 0
,07-05 15:42:41.366  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:42:41.876   770  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:42:41.876   770  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:42:41.886   770  1730 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:42:41.886   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:42:41.896   770   770 I MotionRecognitionService: Plugged
,07-05 15:42:41.896   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:42:41.906   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:42:41.906   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:42:41.906   770  1730 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 15:42:41.916   770  1730 D BatteryService: stay LED for fully charged
,07-05 15:42:41.926  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:42:41.926  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:42:41.926  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:42:41.946  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:42:41.946  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:42:41.956  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:41.956  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:41.956  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:42:50.576   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:42:59.816   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:42:59.996   770  1237 V AlarmManager: Expired Alarm result :8
,07-05 15:42:59.996   770  1237 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=531427 batch.start=679215
,07-05 15:43:00.026  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
07-05 15:43:00.026  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 15:43:00.036  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:43:00.076  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:43:00.096  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:43:00.106  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.106  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.106  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.116  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.116  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.116  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.116  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.176  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:43:00.636   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:43:09.736   770  1585 E Watchdog: !@Sync 17 [07-05 15:43:09.745]
,07-05 15:43:10.696   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:43:11.956   770  1422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:43:11.956   770  1422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:43:11.966   770  1422 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:43:11.966   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:43:11.976   770   770 I MotionRecognitionService: Plugged
,07-05 15:43:11.976   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:43:11.986   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:43:11.986   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:43:11.986   770  1422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:43:11.986   770  1422 D BatteryService: stay LED for fully charged
,07-05 15:43:11.996  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:43:11.996  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:43:12.006  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:43:12.026  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,07-05 15:43:12.036  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:43:12.036  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:43:12.036  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:12.036  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:19.826   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:43:20.746   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:43:30.796   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:43:39.746   770  1585 E Watchdog: !@Sync 18 [07-05 15:43:39.749]
,07-05 15:43:39.826   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:43:40.856   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:43:41.486  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:43:42.026   770  1729 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:43:42.026   770  1729 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:43:42.026   770  1729 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:43:42.036   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:43:42.046   770   770 I MotionRecognitionService: Plugged
,07-05 15:43:42.046   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:43:42.046   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:43:42.046   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:43:42.056   770  1729 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:43:42.056   770  1729 D BatteryService: stay LED for fully charged
,07-05 15:43:42.076  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:43:42.076  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:43:42.076  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:43:42.096  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:43:42.096  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:43:42.106  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:42.106  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:42.106  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:43:50.906   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:43:59.836   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:43:59.996   770  1237 V AlarmManager: Expired Alarm result :8
,07-05 15:44:00.956   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:44:09.746   770  1585 E Watchdog: !@Sync 19 [07-05 15:44:09.753]
,07-05 15:44:11.006   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:44:12.106   770  1618 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:44:12.106   770  1618 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:44:12.116   770  1618 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:44:12.116   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:44:12.126   770   770 I MotionRecognitionService: Plugged
,07-05 15:44:12.126   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:44:12.136   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:44:12.136   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:44:12.136   770  1618 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:44:12.136   770  1618 D BatteryService: stay LED for fully charged
,07-05 15:44:12.146  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:44:12.146  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:44:12.156  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:44:12.186  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:44:12.186  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:44:12.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:44:12.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:44:12.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:44:17.306   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:44:17.306   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:44:17.306   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:44:19.836   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:44:21.066   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:44:24.516   770  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:44:24.526   770  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:44:24.526   770  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:44:25.886   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:44:25.886   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:44:25.896   770  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:44:25.896   770  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:44:31.116   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:44:32.366   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:44:32.366   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:44:32.366   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:44:39.756   770  1585 E Watchdog: !@Sync 20 [07-05 15:44:39.758]
,07-05 15:44:39.846   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:44:41.166   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:44:41.596  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:44:41.726  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 120ms lastUpdatedAfter : 180479ms
,07-05 15:44:42.176   770  1728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:44:42.176   770  1728 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:44:42.186   770  1728 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:44:42.186   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:44:42.196   770   770 I MotionRecognitionService: Plugged
,07-05 15:44:42.196   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:44:42.196   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:44:42.206   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:44:42.206   770  1728 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:44:42.216   770  1728 D BatteryService: stay LED for fully charged
,07-05 15:44:42.226  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:44:42.236  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:44:42.236  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:44:42.246  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:44:42.246  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:44:42.256  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:44:42.256  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:44:42.256  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.486   770   870 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.496   770   870 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.506   770   870 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.516   770   870 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.516   770   870 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 15:44:44.516   770   870 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 15:44:44.666   770   916 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-05 15:44:44.666   770   916 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-05 15:44:51.226   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:44:59.846   770  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 15:45:01.276   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:45:09.756   770  1585 E Watchdog: !@Sync 21 [07-05 15:45:09.765]
,07-05 15:45:11.326   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:45:12.256   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:45:12.266   770  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:45:12.266   770  1731 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:45:12.266   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:45:12.276   770   770 I MotionRecognitionService: Plugged
,07-05 15:45:12.276   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:45:12.276   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:45:12.286   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:45:12.286   770  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:45:12.286   770  1731 D BatteryService: stay LED for fully charged
,07-05 15:45:12.296  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:45:12.296  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:45:12.306  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:45:12.336  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:45:12.336  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:45:12.336  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:12.336  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:45:12.336  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:17.206   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:45:17.206   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:45:17.206   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:45:17.226   770  1618 I ActivityManager: Killing 4681:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 615s, lastActivityTime 615s
,07-05 15:45:17.226   770  1618 I ActivityManager: Killing 3925:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 620s
,07-05 15:45:17.306   293   293 I ServiceManager: service 'AtCmdFwd' died
,07-05 15:45:17.306   377  4806 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-05 15:45:17.306   377  4806 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 15:45:17.306   770   787 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-05 15:45:17.316   770   787 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-05 15:45:17.316   770   787 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-05 15:45:17.336   770  5181 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,07-05 15:45:17.336   770  5181 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-05 15:45:17.336   770  5181 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10974ms
,07-05 15:45:18.306   377  4806 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 15:45:18.356   770   876 I ActivityManager: Start proc 7405:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-05 15:45:18.356  7405  7405 E Zygote  : v2
,07-05 15:45:18.366  7405  7405 I libpersona: KNOX_SDCARD checking this for 1000
,07-05 15:45:18.366  7405  7405 I libpersona: KNOX_SDCARD not a persona
,07-05 15:45:18.366  7405  7405 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:45:18.366  7405  7405 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 15:45:18.366  7405  7405 E Zygote  : accessInfo : 0
,07-05 15:45:18.406  7405  7405 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:45:18.406  7405  7405 D ActivityThread: Added TimaKeyStore provider
,07-05 15:45:18.426  7405  7405 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-05 15:45:18.436  7405  7405 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-05 15:45:18.446  7405  7405 D AtFwdService: onCreate method
,07-05 15:45:18.446  7405  7405 I AtFwdService: Instantiate AtCmdFwd Service
,07-05 15:45:18.456  7405  7417 D AtCkpdCmdHandler: De-queing command
,07-05 15:45:21.386   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:45:27.786   770  1237 V AlarmManager: Expired Alarm result :8
,07-05 15:45:28.386   770   876 I ActivityManager: Start proc 7419:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-05 15:45:28.386  7419  7419 E Zygote  : v2
,07-05 15:45:28.386  7419  7419 I libpersona: KNOX_SDCARD checking this for 10026
07-05 15:45:28.386  7419  7419 I libpersona: KNOX_SDCARD not a persona
,07-05 15:45:28.396  7419  7419 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 15:45:28.396  7419  7419 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:45:28.396  7419  7419 E Zygote  : accessInfo : 0
,07-05 15:45:28.396  7419  7419 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-05 15:45:28.436  7419  7419 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:45:28.436  7419  7419 D ActivityThread: Added TimaKeyStore provider
,07-05 15:45:28.446   770  1674 I ActivityManager: Killing 1503:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 601s, lastActivityTime 601s
,07-05 15:45:28.446   770  1674 I ActivityManager: Killing 3889:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 631s, lastActivityTime 605s
,07-05 15:45:28.486   770  5181 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-05 15:45:28.486   770  5181 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-05 15:45:28.486   770  5181 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
,07-05 15:45:28.486  7419  7419 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-05 15:45:28.496   770  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
,07-05 15:45:28.496   770  1320 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-05 15:45:28.516  7419  7419 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-05 15:45:28.526  7419  7419 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-05 15:45:28.526  7419  7419 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-05 15:45:29.546   770   876 I ActivityManager: Start proc 7456:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
07-05 15:45:29.546   770  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-05 15:45:29.556  7456  7456 E Zygote  : v2
,07-05 15:45:29.556  7456  7456 I libpersona: KNOX_SDCARD checking this for 10181
07-05 15:45:29.556  7456  7456 I libpersona: KNOX_SDCARD not a persona
,07-05 15:45:29.556  7456  7456 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:45:29.556  7456  7456 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:45:29.556  7456  7456 E Zygote  : accessInfo : 0
,07-05 15:45:29.556  7456  7456 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-05 15:45:29.606  7456  7456 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:45:29.606  7456  7456 D ActivityThread: Added TimaKeyStore provider
,07-05 15:45:29.616   770  1323 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 15:45:29.626  7456  7456 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-05 15:45:29.646  7456  7456 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-05 15:45:29.676  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-05 15:45:29.686  7456  7456 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:45:29.686   770   876 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5ea5f5f u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53bdac 7456:com.sec.android.daemonapp/u0a181}
,07-05 15:45:29.696  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-05 15:45:29.696  7456  7456 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:45:29.696  7456  7456 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-05 15:45:29.696  7456  7456 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:45:29.706  7456  7456 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-05 15:45:29.706  7456  7456 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 15:45:29.716  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:45:29.716  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 15:45:29.716  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-05 15:45:29.726  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:45:29.726  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:45:29.726  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-05 15:45:29.726  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 15:45:29.746  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-05 15:45:29.756  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:45:29.756  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:45:29.756  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-05 15:45:29.756  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 15:45:29.756  7456  7456 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:45:29.766  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:45:29.766  7456  7456 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 15:45:29.766  7456  7456 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:45:29.766  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.766  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:45:29.776   770  1320 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1150898 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53bdac 7456:com.sec.android.daemonapp/u0a181}
,07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:45:29.786  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:45:29.786  7456  7456 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:45:29.786  7456  7456 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:45:29.786  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:45:29.786  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 15:45:29.796  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:45:29.796  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:45:29.796  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.796  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:45:29.796   770  1674 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c2328f1 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53bdac 7456:com.sec.android.daemonapp/u0a181}
,07-05 15:45:29.806  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:45:29.806  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:45:29.806  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:45:29.806  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:45:29.816  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 15:45:29.816  7456  7456 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 15:45:29.816  7456  7456 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:45:29.816  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.816  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:45:29.826   770   787 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd80cd6 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{53bdac 7456:com.sec.android.daemonapp/u0a181}
,07-05 15:45:29.826  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 15:45:29.826  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 15:45:29.826  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 15:45:29.836  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:45:29.836  7456  7456 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 15:45:29.836  7456  7456 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 15:45:29.836  7456  7456 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 15:45:29.836  7456  7456 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 15:45:29.846  7456  7456 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 15:45:31.446   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:45:32.366   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 15:45:32.366   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 15:45:32.366   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 15:45:39.766   770  1585 E Watchdog: !@Sync 22 [07-05 15:45:39.769]
,07-05 15:45:41.506   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:45:41.736  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:45:42.346   770  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:45:42.346   770  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:45:42.346   770  1320 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:45:42.356   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:45:42.366   770   770 I MotionRecognitionService: Plugged
,07-05 15:45:42.366   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:45:42.366   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:45:42.376   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:45:42.376   770  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:45:42.376   770  1320 D BatteryService: stay LED for fully charged
,07-05 15:45:42.396  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:45:42.396  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:45:42.396  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:45:42.406  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:45:42.406  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:45:42.416  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:42.416  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:42.416  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:45:51.556   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:46:01.606   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:46:09.766   770  1585 E Watchdog: !@Sync 23 [07-05 15:46:09.773]
,07-05 15:46:11.656   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450, LCD = 0
,07-05 15:46:12.416   770  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:46:12.416   770  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:46:12.426   770  1220 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:46:12.426   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:46:12.436   770   770 I MotionRecognitionService: Plugged
,07-05 15:46:12.436   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:46:12.446   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:46:12.446   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:46:12.446   770  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:46:12.446   770  1220 D BatteryService: stay LED for fully charged
,07-05 15:46:12.456  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:46:12.456  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:46:12.466  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:46:12.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:46:12.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:46:12.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:46:12.496  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:46:12.496  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:46:21.716   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450, LCD = 0,
,07-05 15:46:31.776   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450, LCD = 0
,07-05 15:46:39.776   770  1585 E Watchdog: !@Sync 24 [07-05 15:46:39.777]
,07-05 15:46:41.836   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450, LCD = 0
,07-05 15:46:41.856  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:46:42.506   770  1728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:46:42.506   770  1728 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:46:42.516   770  1728 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:46:42.516   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:46:42.526   770   770 I MotionRecognitionService: Plugged
,07-05 15:46:42.526   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:46:42.526   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:46:42.536   770  1728 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,07-05 15:46:42.536   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:46:42.536   770  1728 D BatteryService: stay LED for fully charged
,07-05 15:46:42.546  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:46:42.546  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:46:42.546  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:46:42.556  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:46:42.556  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:46:42.566  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:46:42.576  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:46:42.576  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:46:51.886   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450, LCD = 0
,07-05 15:47:01.946   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450, LCD = 0
,07-05 15:47:09.776   770  1585 E Watchdog: !@Sync 25 [07-05 15:47:09.782]
,07-05 15:47:11.996   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450, LCD = 0
,07-05 15:47:12.586   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:47:12.586   770  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:47:12.596   770  1731 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:47:12.596   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:47:12.606   770   770 I MotionRecognitionService: Plugged
,07-05 15:47:12.606   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:47:12.606   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:47:12.606   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:47:12.616   770  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:47:12.616   770  1731 D BatteryService: stay LED for fully charged
,07-05 15:47:12.636  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:47:12.636  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:47:12.646  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:47:12.656  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:47:12.656  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:47:12.666  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:12.666  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:12.666  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:22.086   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450, LCD = 0
,07-05 15:47:22.176   770   782 I art     : Background sticky concurrent mark sweep GC freed 81420(8MB) AllocSpace objects, 331(6MB) LOS objects, 26% free, 43MB/58MB, paused 2.659ms total 122.122ms
,07-05 15:47:32.146   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:47:39.786   770  1585 E Watchdog: !@Sync 26 [07-05 15:47:39.791]
,07-05 15:47:41.926  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:47:42.056  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 116ms lastUpdatedAfter : 180324ms
,07-05 15:47:42.206   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:47:42.666   770  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:47:42.676   770  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:47:42.676   770  1320 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:47:42.676   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:47:42.686   770   770 I MotionRecognitionService: Plugged
,07-05 15:47:42.686   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:47:42.696   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:47:42.696   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:47:42.696   770  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:47:42.706   770  1320 D BatteryService: stay LED for fully charged
,07-05 15:47:42.716  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:47:42.716  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:47:42.726  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:47:42.746  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:47:42.746  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:47:42.756  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:42.766  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:42.766  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:47:44.656   770  2497 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 15:47:44.656   770  2497 V MARsPolicyManager: updateSMDBValues
,07-05 15:47:44.656   770   913 E MARsDBManager: updateDBAll : begin --size 1
,07-05 15:47:44.676   770   913 I ActivityManager: Killing 1887:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 783s, lastActivityTime 694s
,07-05 15:47:44.756   770   913 E MARsDBManager: updateDBAll : end
,07-05 15:47:44.756   770   913 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,07-05 15:47:44.796   770   787 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
,07-05 15:47:44.796   770   787 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 15:47:44.796   770   787 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
07-05 15:47:44.796   770   787 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
,07-05 15:47:44.796   770   787 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 10999ms
,07-05 15:47:44.796  6998  6998 D HealthConsole: Service for HealthDataStore is disconnected
,07-05 15:47:44.816   770  2433 I ActivityManager: Start proc 7481:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,07-05 15:47:44.826  7481  7481 E Zygote  : v2
,07-05 15:47:44.836  7481  7481 I libpersona: KNOX_SDCARD checking this for 10034
,07-05 15:47:44.836  7481  7481 I libpersona: KNOX_SDCARD not a persona
,07-05 15:47:44.836  7481  7481 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:47:44.836  7481  7481 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:47:44.836  7481  7481 E Zygote  : accessInfo : 0
,07-05 15:47:44.836  7481  7481 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-05 15:47:44.866  7481  7481 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:47:44.866  7481  7481 D ActivityThread: Added TimaKeyStore provider
,07-05 15:47:44.896  7481  7481 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-05 15:47:44.906  7481  7481 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-05 15:47:44.916  7481  7481 I MultiDex: VM with version 2.1.0 has multidex support
07-05 15:47:44.916  7481  7481 I MultiDex: install
07-05 15:47:44.916  7481  7481 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 15:47:44.916  7481  7481 I MultiDex: install
07-05 15:47:44.916  7481  7481 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 15:47:45.016  7505  7505 E Zygote  : v2
07-05 15:47:45.016  7505  7505 I libpersona: KNOX_SDCARD checking this for 10016
07-05 15:47:45.016  7505  7505 I libpersona: KNOX_SDCARD not a persona
,07-05 15:47:45.016  7505  7505 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 15:47:45.016   770   787 I ActivityManager: Start proc 7505:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
07-05 15:47:45.016  7505  7505 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 15:47:45.016  7505  7505 E Zygote  : accessInfo : 0
,07-05 15:47:45.016  7505  7505 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-05 15:47:45.066  7505  7505 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 15:47:45.066  7505  7505 D ActivityThread: Added TimaKeyStore provider
,07-05 15:47:45.086  7505  7505 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-05 15:47:45.136  7481  7481 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
07-05 15:47:45.136  7481  7481 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 15:47:45.186  1380  1380 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-05 15:47:45.196   770  1744 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,07-05 15:47:45.206   770   786 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,07-05 15:47:45.216  1380  1380 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{a910162 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,07-05 15:47:45.216  1380  1380 D AdaptiveEventManager: M updateContainers()
07-05 15:47:45.216  1380  1380 D AdaptiveEventContainerSmall: C updatePedoContainer()
,07-05 15:47:45.216  1380  1380 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-05 15:47:45.216  1380  1380 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-05 15:47:45.216   770  1422 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,07-05 15:47:45.226   770  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,07-05 15:47:45.276  7481  7481 I Health.HealthService: HealthService: onCreate() start (7481)
,07-05 15:47:45.506  6998  6998 D HealthDataStore: Service for HealthDataStore is connected
,07-05 15:47:45.506  6998  6998 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 15:47:45.526   770  5181 I ActivityManager: Killing 6243:com.sec.android.provider.badge/u0a77 (adj 15): DHA:empty #37
,07-05 15:47:45.556  6998  6998 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 15:47:45.556  6998  6998 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 15:47:45.566   770  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,07-05 15:47:45.636  7481  7481 D HealthDataStore: Service for HealthDataStore is connected
,07-05 15:47:45.636  7481  7481 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 15:47:45.646  7481  7481 D HealthConsole: Service for HealthDataConsole is connected
,07-05 15:47:45.646  7481  7481 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 15:47:45.646  7481  7481 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 15:47:45.806  7481  7528 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-05 15:47:45.846  7481  7547 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-05 15:47:45.906  7505  7515 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-05 15:47:45.926   395   395 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7505
,07-05 15:47:45.926   395   395 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-05 15:47:46.146  7505  7515 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-05 15:47:46.236  7481  7547 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-05 15:47:46.356  7481  7547 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-05 15:47:46.356  7481  7547 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 15:47:46.466   395   395 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-05 15:47:46.506  7505  7515 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-05 15:47:46.506  7505  7515 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-05 15:47:46.506  7505  7515 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,07-05 15:47:52.256   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450, LCD = 0
,07-05 15:48:02.316   770  3509 D SSRM:n  : SIOP:: AP = 310, PST = 302, CUR = 450, LCD = 0
,07-05 15:48:09.786   770  1585 E Watchdog: !@Sync 27 [07-05 15:48:09.796]
,07-05 15:48:12.376   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:48:12.746   770  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:48:12.756   770  1320 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:48:12.756   770  1320 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:48:12.756   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:48:12.766   770   770 I MotionRecognitionService: Plugged
,07-05 15:48:12.766   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:48:12.776   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:48:12.776   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:48:12.776   770  1320 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:48:12.776   770  1320 D BatteryService: stay LED for fully charged
,07-05 15:48:12.786  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:48:12.786  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:48:12.786  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:48:12.806  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:48:12.806  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:48:12.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:12.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:48:12.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:22.426   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:48:32.486   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:48:39.796   770  1585 E Watchdog: !@Sync 28 [07-05 15:48:39.801]
,07-05 15:48:42.126  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:48:42.536   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:48:42.826   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:48:42.826   770   786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:48:42.836   770   786 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:48:42.836   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:48:42.846   770   770 I MotionRecognitionService: Plugged
,07-05 15:48:42.846   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:48:42.846   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:48:42.856   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:48:42.856   770   786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:48:42.856   770   786 D BatteryService: stay LED for fully charged
,07-05 15:48:42.876  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:48:42.876  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:48:42.876  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:48:42.896  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:48:42.896  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:48:42.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:42.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:42.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:48:52.586   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:49:02.646   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:49:09.796   770  1585 E Watchdog: !@Sync 29 [07-05 15:49:09.805]
,07-05 15:49:12.696   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:49:12.906   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:49:12.906   770  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:49:12.916   770  1731 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:49:12.916   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:49:12.926   770   770 I MotionRecognitionService: Plugged
,07-05 15:49:12.926   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:49:12.936   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:49:12.936   770  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 15:49:12.936   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:49:12.936   770  1731 D BatteryService: stay LED for fully charged
,07-05 15:49:12.946  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:49:12.956  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:49:12.956  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:49:12.986  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:49:12.986  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:49:12.986  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 15:49:12.986  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:49:12.986  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:49:22.746   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450, LCD = 0
,07-05 15:49:24.516   770  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:49:24.526   770  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:49:24.526   770  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:49:27.636   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:49:27.636   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:49:27.646   770  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:49:27.656   770  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:49:32.806   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450, LCD = 0
,07-05 15:49:39.806   770  1585 E Watchdog: !@Sync 30 [07-05 15:49:39.811]
,07-05 15:49:42.236  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:49:42.856   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:49:46.586   770  1237 V AlarmManager: Expired Alarm result :4
,07-05 15:49:46.636  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 15:49:46.636  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 15:49:46.636  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 15:49:46.646   770  1729 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:49:46.646   770  1729 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:49:46.646   770  1729 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
07-05 15:49:46.646   770  1729 D BatteryService: stay LED for fully charged
,07-05 15:49:46.656  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 15:49:46.656  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 15:49:46.676  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:46.676  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:46.676   770   876 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,07-05 15:49:46.686  2405  2548 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 15:49:46.686  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.686  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:49:46.686  2405  2548 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 15:49:46.686  2405  2548 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
07-05 15:49:46.686  2405  2548 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 15:49:46.696  2405  2602 D bt_upio : upio_start_stop_timer : timer_settime success
,07-05 15:49:46.696  2405  2602 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-05 15:49:46.696  2405  2602 D bt_vendor: op for 7
,07-05 15:49:46.696  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.696  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.696  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.696  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.696  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.706  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.706  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:49:46.706  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.706  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.706  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.706  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.706  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.706  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:49:46.706  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.706  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.706  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.706  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.706  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.706  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.706  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.706  2405  2602 D bt_vendor: op for 7
,07-05 15:49:46.706  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.706  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
,07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.716  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.716  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 15:49:46.716  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.726  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.726  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.726  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.726  2405  2602 D bt_vendor: op for 7
,07-05 15:49:46.726  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.726  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.736  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.736  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.736  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.736  2405  2602 D bt_vendor: op for 7
07-05 15:49:46.736  2405  2602 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 15:49:46.736  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:49:46.736  2405  2602 D bt_upio : BT_WAKE is asserted already
,07-05 15:49:46.736  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:46.736  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 15:49:46.736  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:46.736  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:46.736   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:49:46.756  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 15:49:46.756  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:49:46.756  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:49:46.756  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:49:46.756   770   770 I MotionRecognitionService: Plugged
07-05 15:49:46.756   770   770 D MotionRecognitionService:   cableConnection= 1
07-05 15:49:46.756   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 15:49:46.756   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:49:46.756  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:49:46.756  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:49:46.756  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:49:46.756  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 15:49:46.756   770  1674 V AlarmManager:  remove PendingIntent] PendingIntent{4cf49d3: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.766   770   787 V AlarmManager:  remove PendingIntent] PendingIntent{f2e910: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.776   770  1422 V AlarmManager:  remove PendingIntent] PendingIntent{cd04c09: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.776   770  1728 V AlarmManager:  remove PendingIntent] PendingIntent{3d14e0e: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.776   770  1729 V AlarmManager:  remove PendingIntent] PendingIntent{2bab02f: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.786   770  1744 V AlarmManager:  remove PendingIntent] PendingIntent{e85863c: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.786   770  1728 V AlarmManager:  remove PendingIntent] PendingIntent{c289fc5: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.806   770  1422 V AlarmManager:  remove PendingIntent] PendingIntent{5583d1a: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.806  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 15:49:46.816   770  1730 V AlarmManager:  remove PendingIntent] PendingIntent{54c204b: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.816   770  1618 V AlarmManager:  remove PendingIntent] PendingIntent{842ca28: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.826   770  5181 V AlarmManager:  remove PendingIntent] PendingIntent{f87341: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.836   770  1674 V AlarmManager:  remove PendingIntent] PendingIntent{22d10e6: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.836   770  1618 V AlarmManager:  remove PendingIntent] PendingIntent{3a7627: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.836   770  1728 V AlarmManager:  remove PendingIntent] PendingIntent{20e60d4: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.836   770  1730 V AlarmManager:  remove PendingIntent] PendingIntent{998027d: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.846   770  1744 V AlarmManager:  remove PendingIntent] PendingIntent{295572: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.846   770  2433 V AlarmManager:  remove PendingIntent] PendingIntent{1ce4dc3: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.846   770  1731 V AlarmManager:  remove PendingIntent] PendingIntent{85ab640: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.846   770   787 V AlarmManager:  remove PendingIntent] PendingIntent{7a74979: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.856   770  2468 V AlarmManager:  remove PendingIntent] PendingIntent{73356be: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.856   770   786 V AlarmManager:  remove PendingIntent] PendingIntent{a3e031f: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.856   770  1220 V AlarmManager:  remove PendingIntent] PendingIntent{a54f66c: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.856   770   787 V AlarmManager:  remove PendingIntent] PendingIntent{cca0435: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.856   770  1744 V AlarmManager:  remove PendingIntent] PendingIntent{54a20ca: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.866   770  1618 V AlarmManager:  remove PendingIntent] PendingIntent{cc9b23b: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.866   770  1729 V AlarmManager:  remove PendingIntent] PendingIntent{ad10d58: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.866   770  1220 V AlarmManager:  remove PendingIntent] PendingIntent{723aeb1: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.866   770   787 V AlarmManager:  remove PendingIntent] PendingIntent{7517f96: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.866   770  1744 V AlarmManager:  remove PendingIntent] PendingIntent{6973717: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.866   770  1618 V AlarmManager:  remove PendingIntent] PendingIntent{3f5a704: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.876   770  1729 V AlarmManager:  remove PendingIntent] PendingIntent{99384ed: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.876   770  1220 V AlarmManager:  remove PendingIntent] PendingIntent{29dff22: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.876   770   787 V AlarmManager:  remove PendingIntent] PendingIntent{74e2db3: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.876   770  1744 V AlarmManager:  remove PendingIntent] PendingIntent{9a82f70: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.876   770  1618 V AlarmManager:  remove PendingIntent] PendingIntent{bb082e9: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.876   770  1729 V AlarmManager:  remove PendingIntent] PendingIntent{b40eb6e: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.886   770  1220 V AlarmManager:  remove PendingIntent] PendingIntent{773f20f: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.886   770   787 V AlarmManager:  remove PendingIntent] PendingIntent{6b8d29c: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:46.886   770  1744 V AlarmManager:  remove PendingIntent] PendingIntent{d8564a5: PendingIntentRecord{e7f77c2 com.android.bluetooth broadcastIntent}}
,07-05 15:49:47.496  2405  2774 D bt_upio : ..proc_btwrite_timeout..
,07-05 15:49:47.496  2405  2774 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 15:49:52.916   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:49:59.996   770  1237 V AlarmManager: Expired Alarm result :8
,07-05 15:50:01.996   770  1237 V AlarmManager: Expired Alarm result :8
,07-05 15:50:02.966   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:50:09.806   770  1585 E Watchdog: !@Sync 31 [07-05 15:50:09.815]
,07-05 15:50:13.026   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:50:16.726   770  2433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:50:16.736   770  2433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:50:16.736   770  2433 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:50:16.736   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:50:16.746   770   770 I MotionRecognitionService: Plugged
,07-05 15:50:16.756   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:50:16.756   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:50:16.756   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:50:16.756   770  2433 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:50:16.766   770  2433 D BatteryService: stay LED for fully charged
,07-05 15:50:16.776  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:50:16.776  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:50:16.776  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:50:16.786  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:50:16.786  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:50:16.796  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:50:16.796  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:50:16.796  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:50:23.076   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:50:33.126   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:50:39.816   770  1585 E Watchdog: !@Sync 32 [07-05 15:50:39.820]
,07-05 15:50:42.346  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:50:42.476  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 120ms lastUpdatedAfter : 180424ms
,07-05 15:50:43.186   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:50:46.806   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:50:46.806   770  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:50:46.806   770  1731 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:50:46.816   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:50:46.826   770   770 I MotionRecognitionService: Plugged
,07-05 15:50:46.826   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:50:46.826   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:50:46.826   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:50:46.836   770  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:50:46.836   770  1731 D BatteryService: stay LED for fully charged
,07-05 15:50:46.856  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:50:46.856  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:50:46.866  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:50:46.886  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:50:46.886  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:50:46.896  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:50:46.896  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:50:46.896  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:50:53.246   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:51:03.296   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:51:09.816   770  1585 E Watchdog: !@Sync 33 [07-05 15:51:09.824]
,07-05 15:51:13.356   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:51:16.876   770  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:51:16.886   770  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:51:16.886   770  1730 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:51:16.886   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:51:16.896   770   770 I MotionRecognitionService: Plugged
,07-05 15:51:16.896   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:51:16.906   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:51:16.906   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:51:16.916   770  1730 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 15:51:16.916   770  1730 D BatteryService: stay LED for fully charged
,07-05 15:51:16.926  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:51:16.926  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:51:16.926  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:51:16.936  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:51:16.936  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:51:16.946  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:51:16.946  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:51:16.946  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:51:23.406   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:51:33.456   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:51:39.826   770  1585 E Watchdog: !@Sync 34 [07-05 15:51:39.828]
,07-05 15:51:42.546  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:51:43.516   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:51:46.946   770  1674 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:51:46.946   770  1674 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:51:46.956   770  1674 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:51:46.956   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:51:46.966   770   770 I MotionRecognitionService: Plugged
,07-05 15:51:46.966   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:51:46.966   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:51:46.976   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:51:46.976   770  1674 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:51:46.976   770  1674 D BatteryService: stay LED for fully charged
,07-05 15:51:46.986  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:51:46.986  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:51:46.996  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:51:47.026  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:51:47.026  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:51:47.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:51:47.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:51:47.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:51:53.566   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:52:03.626   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:52:09.826   770  1585 E Watchdog: !@Sync 35 [07-05 15:52:09.835]
,07-05 15:52:13.676   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:52:17.026   770  2433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:52:17.026   770  2433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:52:17.026   770  2433 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:52:17.036   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:52:17.046   770   770 I MotionRecognitionService: Plugged
,07-05 15:52:17.046   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:52:17.046   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:52:17.056   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:52:17.056   770  2433 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:52:17.056   770  2433 D BatteryService: stay LED for fully charged
,07-05 15:52:17.076  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:52:17.076  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:52:17.076  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:52:17.086  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:52:17.086  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:52:17.096  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:52:17.096  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:52:17.096  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:52:23.736   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:52:33.786   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:52:39.836   770  1585 E Watchdog: !@Sync 36 [07-05 15:52:39.840]
,07-05 15:52:42.606  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:52:43.836   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:52:47.096   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:52:53.896   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:53:03.946   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:53:09.836   770  1585 E Watchdog: !@Sync 37 [07-05 15:53:09.844]
,07-05 15:53:14.006   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:53:17.176   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:53:17.176   770   786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:53:17.176   770   786 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:53:17.186   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:53:17.196   770   770 I MotionRecognitionService: Plugged
,07-05 15:53:17.196   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:53:17.196   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:53:17.206   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:53:17.206   770   786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:53:17.206   770   786 D BatteryService: stay LED for fully charged
,07-05 15:53:17.226  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:53:17.226  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:53:17.226  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:53:17.236  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:53:17.236  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:53:17.246  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:53:17.246  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:53:17.246  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:53:24.056   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:53:34.116   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:53:39.846   770  1585 E Watchdog: !@Sync 38 [07-05 15:53:39.849]
,07-05 15:53:42.686  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:53:42.826  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 131ms lastUpdatedAfter : 180344ms
,07-05 15:53:44.166   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:53:47.256   770  5181 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:53:47.266   770  5181 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:53:47.266   770  5181 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:53:47.266   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:53:47.276   770   770 I MotionRecognitionService: Plugged
,07-05 15:53:47.286   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:53:47.286   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:53:47.286   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:53:47.286   770  5181 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 15:53:47.296   770  5181 D BatteryService: stay LED for fully charged
,07-05 15:53:47.306  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:53:47.316  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:53:47.316  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:53:47.336  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:53:47.336  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:53:47.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:53:47.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:53:47.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:53:54.226   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:54:04.286   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:54:09.846   770  1585 E Watchdog: !@Sync 39 [07-05 15:54:09.853]
,07-05 15:54:14.336   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:54:17.336   770  1729 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:54:17.346   770  1729 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:54:17.346   770  1729 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:54:17.346   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:54:17.356   770   770 I MotionRecognitionService: Plugged
,07-05 15:54:17.356   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:54:17.366   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:54:17.366   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:54:17.366   770  1729 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:54:17.376   770  1729 D BatteryService: stay LED for fully charged
,07-05 15:54:17.376  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:54:17.376  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:54:17.376  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:54:17.386  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:54:17.386  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:54:17.396  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:17.406  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:17.406  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:24.396   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:54:24.516   770  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:54:24.526   770  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:54:24.526   770  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:54:25.886   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:54:25.886   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:54:25.896   770  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:54:25.906   770  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:54:34.446   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:54:36.446   770   870 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 15:54:39.856   770  1585 E Watchdog: !@Sync 40 [07-05 15:54:39.857]
,07-05 15:54:42.876  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:54:44.506   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:54:47.416   770  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:54:47.416   770  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:54:47.416   770  1220 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:54:47.416   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:54:47.426   770   770 I MotionRecognitionService: Plugged
,07-05 15:54:47.436   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:54:47.436   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:54:47.436   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:54:47.436   770  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:54:47.446   770  1220 D BatteryService: stay LED for fully charged
,07-05 15:54:47.456  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:54:47.456  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:54:47.466  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:54:47.486  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:54:47.486  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:54:47.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:47.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:54:47.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:54:54.556   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:55:04.606   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:55:09.856   770  1585 E Watchdog: !@Sync 41 [07-05 15:55:09.865]
,07-05 15:55:14.656   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:55:17.486   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:55:24.716   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:55:34.766   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:55:39.866   770  1585 E Watchdog: !@Sync 42 [07-05 15:55:39.869]
,07-05 15:55:42.956  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:55:44.816   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:55:47.556   770  2433 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:55:47.556   770  2433 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:55:47.566   770  2433 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:55:47.566   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:55:47.576   770   770 I MotionRecognitionService: Plugged
,07-05 15:55:47.576   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:55:47.586   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:55:47.586   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:55:47.586   770  2433 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:55:47.586   770  2433 D BatteryService: stay LED for fully charged
,07-05 15:55:47.606  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:55:47.606  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:55:47.606  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:55:47.626  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:55:47.636  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:55:47.646  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:55:47.646  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:55:47.646  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:55:54.876   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:56:04.926   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:56:09.866   770  1585 E Watchdog: !@Sync 43 [07-05 15:56:09.873]
,07-05 15:56:14.986   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:56:17.626   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:56:25.036   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:56:35.086   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:56:39.876   770  1585 E Watchdog: !@Sync 44 [07-05 15:56:39.877]
,07-05 15:56:42.976  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:56:43.096  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 102ms lastUpdatedAfter : 180268ms
,07-05 15:56:45.146   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:56:47.706   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:56:55.196   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:57:05.246   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450, LCD = 0
,07-05 15:57:09.876   770  1585 E Watchdog: !@Sync 45 [07-05 15:57:09.882]
,07-05 15:57:15.306   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 450, LCD = 0
,07-05 15:57:17.776   770  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:57:17.786   770  1730 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:57:17.786   770  1730 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:57:17.786   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:57:17.806   770   770 I MotionRecognitionService: Plugged
,07-05 15:57:17.806   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:57:17.806   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:57:17.816   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:57:17.816   770  1730 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 15:57:17.816   770  1730 D BatteryService: stay LED for fully charged
,07-05 15:57:17.826  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:57:17.826  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:57:17.826  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:57:17.836  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:57:17.836  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:57:17.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:57:17.856  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 15:57:17.856  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:57:25.356   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 450, LCD = 0
,07-05 15:57:35.416   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 450, LCD = 0
,07-05 15:57:39.876   770  1585 E Watchdog: !@Sync 46 [07-05 15:57:39.886]
,07-05 15:57:43.106  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:57:45.476   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 450, LCD = 0
,07-05 15:57:47.856   770  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:57:55.536   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 450, LCD = 0
,07-05 15:58:05.586   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 450, LCD = 0
,07-05 15:58:09.886   770  1585 E Watchdog: !@Sync 47 [07-05 15:58:09.891]
,07-05 15:58:15.646   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 450, LCD = 0
,07-05 15:58:17.936   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:58:25.706   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 450, LCD = 0
,07-05 15:58:35.766   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 15:58:39.886   770  1585 E Watchdog: !@Sync 48 [07-05 15:58:39.895]
,07-05 15:58:43.156  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:58:45.816   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:58:48.006   770  1728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:58:55.876   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:59:05.936   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:59:09.896   770  1585 E Watchdog: !@Sync 49 [07-05 15:59:09.899]
,07-05 15:59:15.986   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:59:18.076   770  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:59:18.076   770  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:59:18.086   770  1220 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:59:18.086   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:59:18.096   770   770 I MotionRecognitionService: Plugged
,07-05 15:59:18.096   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:59:18.106   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:59:18.106   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:59:18.106   770  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 15:59:18.106   770  1220 D BatteryService: stay LED for fully charged
,07-05 15:59:18.126  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:59:18.126  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 15:59:18.126  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:59:18.136  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:59:18.136  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:59:18.146  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:18.146  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:18.146  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:24.526   770  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 15:59:24.526   770  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 15:59:24.526   770  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 15:59:26.046   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 15:59:27.636   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 15:59:27.636   770  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 15:59:27.646   770  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:59:27.656   770  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 15:59:36.096   770  3509 D SSRM:n  : SIOP:: AP = 300, PST = 291, CUR = 450, LCD = 0
,07-05 15:59:39.896   770  1585 E Watchdog: !@Sync 50 [07-05 15:59:39.904]
,07-05 15:59:43.276  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 15:59:43.386  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 99ms lastUpdatedAfter : 180295ms
,07-05 15:59:44.666   770  2497 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 15:59:44.666   770  2497 V MARsPolicyManager: updateSMDBValues
,07-05 15:59:44.676   770   913 E MARsDBManager: updateDBAll : begin --size 0
,07-05 15:59:44.676   770   913 E MARsDBManager: updateDBAll : end
,07-05 15:59:46.156   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 15:59:48.146   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 15:59:48.156   770   786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 15:59:48.156   770   786 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 15:59:48.156   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 15:59:48.166   770   770 I MotionRecognitionService: Plugged
,07-05 15:59:48.166   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 15:59:48.176   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 15:59:48.176   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 15:59:48.176   770   786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,07-05 15:59:48.186   770   786 D BatteryService: stay LED for fully charged
,07-05 15:59:48.196  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:59:48.196  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 15:59:48.196  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 15:59:48.226  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 15:59:48.226  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 15:59:48.236  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:48.236  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:48.236  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 15:59:56.206   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:00:06.256   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:00:09.906   770  1585 E Watchdog: !@Sync 51 [07-05 16:00:09.908]
,07-05 16:00:16.326   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:00:16.396   770   782 I art     : Background sticky concurrent mark sweep GC freed 55706(7MB) AllocSpace objects, 388(7MB) LOS objects, 26% free, 43MB/58MB, paused 2.459ms total 116.586ms
,07-05 16:00:18.226   770  1674 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:00:18.236   770  1674 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 16:00:18.236   770  1674 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 16:00:18.236   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 16:00:18.246   770   770 I MotionRecognitionService: Plugged
,07-05 16:00:18.256   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 16:00:18.256   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 16:00:18.256   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:00:18.266   770  1674 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 16:00:18.266   770  1674 D BatteryService: stay LED for fully charged
,07-05 16:00:18.276  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 16:00:18.276  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:00:18.276  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:00:18.286  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 16:00:18.286  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:00:18.296  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:18.296  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:18.296  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:26.376   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:00:36.426   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:00:39.906   770  1585 E Watchdog: !@Sync 52 [07-05 16:00:39.913]
,07-05 16:00:43.406  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 16:00:46.486   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:00:48.306   770   787 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:00:48.306   770   787 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 16:00:48.316   770   787 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 16:00:48.316   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 16:00:48.326   770   770 I MotionRecognitionService: Plugged
,07-05 16:00:48.326   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 16:00:48.326   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 16:00:48.336   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:00:48.336   770   787 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 16:00:48.346   770   787 D BatteryService: stay LED for fully charged
,07-05 16:00:48.356  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 16:00:48.356  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 16:00:48.366  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:00:48.386  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 16:00:48.386  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:00:48.396  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:48.396  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:48.396  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:00:56.546   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:01:06.596   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 450, LCD = 0
,07-05 16:01:09.916   770  1585 E Watchdog: !@Sync 53 [07-05 16:01:09.917]
,07-05 16:01:16.656   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:01:18.386   770  1220 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:01:18.386   770  1220 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 16:01:18.386   770  1220 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 16:01:18.396   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 16:01:18.406   770   770 I MotionRecognitionService: Plugged
,07-05 16:01:18.406   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 16:01:18.406   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 16:01:18.416   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:01:18.416   770  1220 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 16:01:18.416   770  1220 D BatteryService: stay LED for fully charged
,07-05 16:01:18.426  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 16:01:18.426  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 16:01:18.426  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:01:18.436  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
07-05 16:01:18.436  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:01:18.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:18.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:18.456  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:26.716   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:01:36.766   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:01:39.916   770  1585 E Watchdog: !@Sync 54 [07-05 16:01:39.924]
,07-05 16:01:43.516  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 16:01:46.816   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:01:48.466   770   786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:01:48.466   770   786 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 16:01:48.476   770   786 D BatteryService: online:4, current avg:450, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
,07-05 16:01:48.476   770   770 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 16:01:48.486   770   770 I MotionRecognitionService: Plugged
,07-05 16:01:48.486   770   770 D MotionRecognitionService:   cableConnection= 1
,07-05 16:01:48.496   770   770 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 16:01:48.496   770   770 D MotionRecognitionService: skip setTransmitPower. 
,07-05 16:01:48.496   770   786 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 16:01:48.496   770   786 D BatteryService: stay LED for fully charged
,07-05 16:01:48.516  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 16:01:48.516  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 16:01:48.526  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 16:01:48.536  2405  2405 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 16:01:48.536  2405  2793 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 16:01:48.546  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:48.546  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:48.546  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 16:01:56.876   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:02:06.926   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:02:09.926   770  1585 E Watchdog: !@Sync 55 [07-05 16:02:09.928]
,07-05 16:02:16.986   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:02:18.546   770  1674 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 16:02:27.036   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:02:37.086   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,07-05 16:02:39.926   770  1585 E Watchdog: !@Sync 56 [07-05 16:02:39.935]
,07-05 16:02:43.636  1660  1760 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 16:02:43.766  1660  1760 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 116ms lastUpdatedAfter : 180382ms
,07-05 16:02:47.136   770  3509 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 450, LCD = 0
,TIME-OUT KILL (timeout was 1401000ms),07-05 16:02:53.276   770  1237 V AlarmManager: Expired Alarm result :4
07-05 16:02:53.286   770  1237 I ActivityManager: Killing 7481:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 908s, lastActivityTime 908s
07-05 16:02:53.296   770  1237 I ActivityManager: Killing 7456:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 1043s, lastActivityTime 1043s
07-05 16:02:53.296   770  1237 I ActivityManager: Killing 7419:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 1044s, lastActivityTime 1044s
07-05 16:02:53.296   770  1237 I ActivityManager: Killing 7405:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 1054s, lastActivityTime 1054s
07-05 16:02:53.306   770   770 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
07-05 16:02:53.316   770   770 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
07-05 16:02:53.316   770   770 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
07-05 16:02:53.326   770   770 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-05 16:02:53.336   770  2468 V AlarmManager:  remove PendingIntent] PendingIntent{ade1407: PendingIntentRecord{6a7abe5 com.google.android.gms broadcastIntent}}
07-05 16:02:53.336   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 16:02:53.336   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 16:02:53.336   319  1120 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
07-05 16:02:53.336   770  1730 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 16:02:53.346   770  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 16:02:53.346   770  1323 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 16:02:53.366  2410  2410 E audit   : type=1400 msg=audit(1467727373.366:293): avc:  denied  { execmod } for  pid=7626 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 16:02:53.366  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 16:02:53.366  2410  2410 E audit   : type=1300 msg=audit(1467727373.366:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f53000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7626 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 16:02:53.366  2410  2410 E audit   : type=1327 msg=audit(1467727373.366:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 16:02:53.366  2410  2410 E audit   : type=1320 msg=audit(1467727373.366:293): 
07-05 16:02:53.366  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 16:02:53.366  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 16:02:53.366  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
07-05 16:02:53.376  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
07-05 16:02:53.376  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
07-05 16:02:53.386  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.386  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.386  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.386   293   293 I ServiceManager: service 'AtCmdFwd' died
07-05 16:02:53.386   377  4808 I Atfwd_Sendcmd: AtCmdFwd : binderDied
07-05 16:02:53.386   377  4808 I ServiceManager: Waiting for service AtCmdFwd...
07-05 16:02:53.386  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.396  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.396  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.396  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.396   770  5181 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
07-05 16:02:53.396   770  5181 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-05 16:02:53.396   770  5181 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
07-05 16:02:53.396  1831  7647 W System  : ClassLoader referenced unknown path: /system/priv-app/Velvet/lib/arm
07-05 16:02:53.416   770  1320 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
07-05 16:02:53.416   770  1320 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-05 16:02:53.416   770  1320 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10977ms
07-05 16:02:53.416  2410  2410 E audit   : type=1400 msg=audit(1467727373.416:294): avc:  denied  { execmod } for  pid=7626 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 16:02:53.416  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 16:02:53.416  2410  2410 E audit   : type=1300 msg=audit(1467727373.416:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f13000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7626 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 16:02:53.416  2410  2410 E audit   : type=1327 msg=audit(1467727373.416:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 16:02:53.426  2410  2410 E audit   : type=1320 msg=audit(1467727373.416:294): 
07-05 16:02:53.426   770   786 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-05 16:02:53.426   770   786 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 16:02:53.426   770   786 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 20969ms
07-05 16:02:53.436   770  1729 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-05 16:02:53.436   770  1729 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-05 16:02:53.436   770  1729 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 30961ms
07-05 16:02:53.456  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 16:02:53.456  1831  7633 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
07-05 16:02:53.466   770  1730 V AlarmManager:  remove PendingIntent] PendingIntent{f12d934: PendingIntentRecord{6a7abe5 com.google.android.gms broadcastIntent}}
07-05 16:02:53.466  2410  2410 E audit   : type=1400 msg=audit(1467727373.466:295): avc:  denied  { execmod } for  pid=7626 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 16:02:53.466  2410  2410 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 16:02:53.466  2410  2410 E audit   : type=1300 msg=audit(1467727373.466:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f13000 a1=51000 a2=5 a3=4 items=0 ppid=3661 ppcomm=adbd pid=7626 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 16:02:53.466  2410  2410 E audit   : type=1327 msg=audit(1467727373.466:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 16:02:53.466  2410  2410 E audit   : type=1320 msg=audit(1467727373.466:295): 
07-05 16:02:53.466  7626  7626 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 16:02:53.476   770  1422 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{b6c835d u-1 android.intent.action.TIME_TICK qIdx=2}, state= (IDLE) to ReceiverList{5265a0a 7456 com.sec.android.daemonapp/10181/u0 remote:67a5a75}: filter unregistered
07-05 16:02:53.476  7626  7626 D AndroidRuntime: CheckJNI is OFF
07-05 16:02:53.476  7626  7626 D AndroidRuntime: readGMSProperty: start
07-05 16:02:53.476  7626  7626 D AndroidRuntime: readGMSProperty: already setted!!
07-05 16:02:53.476  7626  7626 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 16:02:53.476  7626  7626 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 16:02:53.476  7626  7626 D AndroidRuntime: readGMSProperty: end
07-05 16:02:53.476  7626  7626 D AndroidRuntime: addProductProperty: start
07-05 16:02:53.476  7626  7626 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 16:02:53.476  7626  7626 W art     : af0a5000-b1fcb000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-05 16:02:53.476  7626  7626 W art     : b1fcb000-b423a000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-05 16:02:53.476  7626  7626 W art     : b423a000-b423b000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-05 16:02:53.476  7626  7626 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
07-05 16:02:53.476  7626  7626 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
07-05 16:02:53.476  7626  7626 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
07-05 16:02:53.476  7626  7626 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
07-05 16:02:53.476  7626  7626 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 332        /system/lib/libart.so
07-05 16:02:53.476  7626  7626 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
07-05 16:02:53.476  7626  7626 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-05 16:02:53.476  7626  7626 W art     : b47e2000-b47e5000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
07-05 16:02:53.486  7626  7626 W art     : b47e5000-b47e6000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
07-05 16:02:53.486  7626  7626 W art     : b47e6000-b47e7000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
07-05 16:02:53.486  7626  7626 W art     : b47e7000-b47e8000 r--p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b47e8000-b4808000 r--s 00000000 00:0b 7184       /dev/__properties__
07-05 16:02:53.486  7626  7626 W art     : b4808000-b5219000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
07-05 16:02:53.486  7626  7626 W art     : b5219000-b521a000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b521a000-b5263000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
07-05 16:02:53.486  7626  7626 W art     : b5263000-b5264000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
07-05 16:02:53.486  7626  7626 W art     : b5264000-b526c000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b526c000-b526d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b526d000-b52a2000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
07-05 16:02:53.486  7626  7626 W art     : b52a2000-b52a3000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b52a3000-b52a4000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
07-05 16:02:53.486  7626  7626 W art     : b52a4000-b52a5000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
07-05 16:02:53.486  7626  7626 W art     : b52a5000-b52fd000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
07-05 16:02:53.486  7626  7626 W art     : b52fd000-b52fe000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b52fe000-b52ff000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
07-05 16:02:53.486  7626  7626 W art     : b52ff000-b5300000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
07-05 16:02:53.486  7626  7626 W art     : b5301000-b5307000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 16:02:53.486  7626  7626 W art     : b5307000-b5308000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 16:02:53.486  7626  7626 W art     : b5308000-b5309000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 16:02:53.486  7626  7626 W art     : b5309000-b530b000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b530c000-b5316000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 16:02:53.486  7626  7626 W art     : b5316000-b5319000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 16:02:53.486  7626  7626 W art     : b5319000-b531a000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
07-05 16:02:53.486  7626  7626 W art     : b531b000-b5332000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 16:02:53.486  7626  7626 W art     : b5332000-b5333000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5333000-b5334000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 16:02:53.486  7626  7626 W art     : b5334000-b5335000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
07-05 16:02:53.486  7626  7626 W art     : b5336000-b5340000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
07-05 16:02:53.486  7626  7626 W art     : b5340000-b5341000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
07-05 16:02:53.486  7626  7626 W art     : b5341000-b5342000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
07-05 16:02:53.486  7626  7626 W art     : b5342000-b5346000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 16:02:53.486  7626  7626 W art     : b5346000-b5347000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 16:02:53.486  7626  7626 W art     : b5347000-b5348000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
07-05 16:02:53.486  7626  7626 W art     : b5348000-b535e000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
07-05 16:02:53.486  7626  7626 W art     : b535e000-b535f000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
07-05 16:02:53.486  7626  7626 W art     : b535f000-b5360000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
07-05 16:02:53.486  7626  7626 W art     : b5360000-b536d000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
07-05 16:02:53.486  7626  7626 W art     : b536d000-b536e000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
07-05 16:02:53.486  7626  7626 W art     : b536e000-b536f000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
07-05 16:02:53.486  7626  7626 W art     : b536f000-b53cf000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
07-05 16:02:53.486  7626  7626 W art     : b53cf000-b53d2000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
07-05 16:02:53.486  7626  7626 W art     : b53d2000-b53d6000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b53d6000-b5437000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
07-05 16:02:53.486  7626  7626 W art     : b5437000-b5438000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
07-05 16:02:53.486  7626  7626 W art     : b5438000-b5487000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
07-05 16:02:53.486  7626  7626 W art     : b5487000-b5489000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
07-05 16:02:53.486  7626  7626 W art     : b5489000-b548a000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
07-05 16:02:53.486  7626  7626 W art     : b548a000-b548b000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b548b000-b5492000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 16:02:53.486  7626  7626 W art     : b5492000-b5493000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 16:02:53.486  7626  7626 W art     : b5493000-b5494000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
07-05 16:02:53.486  7626  7626 W art     : b5495000-b5498000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 16:02:53.486  7626  7626 W art     : b5498000-b5499000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 16:02:53.486  7626  7626 W art     : b5499000-b549a000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
07-05 16:02:53.486  7626  7626 W art     : b549b000-b549f000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
07-05 16:02:53.486  7626  7626 W art     : b549f000-b54a0000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b54a0000-b54a1000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
07-05 16:02:53.486  7626  7626 W art     : b54a1000-b54a2000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
07-05 16:02:53.486  7626  7626 W art     : b54a3000-b54c0000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 16:02:53.486  7626  7626 W art     : b54c0000-b54c1000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 16:02:53.486  7626  7626 W art     : b54c1000-b54c2000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
07-05 16:02:53.486  7626  7626 W art     : b54c3000-b54c8000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 16:02:53.486  7626  7626 W art     : b54c8000-b54c9000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 16:02:53.486  7626  7626 W art     : b54c9000-b54ca000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
07-05 16:02:53.486  7626  7626 W art     : b54cb000-b54fc000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 16:02:53.486  7626  7626 W art     : b54fc000-b54ff000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 16:02:53.486  7626  7626 W art     : b54ff000-b5500000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
07-05 16:02:53.486  7626  7626 W art     : b5501000-b553c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
07-05 16:02:53.486  7626  7626 W art     : b553c000-b553d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
07-05 16:02:53.486  7626  7626 W art     : b553d000-b553e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
07-05 16:02:53.486  7626  7626 W art     : b553f000-b5546000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
07-05 16:02:53.486  7626  7626 W art     : b5546000-b5547000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5547000-b5548000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
07-05 16:02:53.486  7626  7626 W art     : b5548000-b5549000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
07-05 16:02:53.486  7626  7626 W art     : b5549000-b554a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b554a000-b5561000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
07-05 16:02:53.486  7626  7626 W art     : b5561000-b5562000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5562000-b5565000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
07-05 16:02:53.486  7626  7626 W art     : b5565000-b5566000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
07-05 16:02:53.486  7626  7626 W art     : b5566000-b5585000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
07-05 16:02:53.486  7626  7626 W art     : b5585000-b5586000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
07-05 16:02:53.486  7626  7626 W art     : b5586000-b5587000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
07-05 16:02:53.486  7626  7626 W art     : b5587000-b55c5000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-05 16:02:53.486  7626  7626 W art     : b55c5000-b55c6000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b55c6000-b55c8000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-05 16:02:53.486  7626  7626 W art     : b55c8000-b55c9000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-05 16:02:53.486  7626  7626 W art     : b55ca000-b55d1000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 16:02:53.486  7626  7626 W art     : b55d1000-b55d2000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 16:02:53.486  7626  7626 W art     : b55d2000-b55d3000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
07-05 16:02:53.486  7626  7626 W art     : b55d4000-b55d7000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 16:02:53.486  7626  7626 W art     : b55d7000-b55d8000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 16:02:53.486  7626  7626 W art     : b55d8000-b55d9000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
07-05 16:02:53.486  7626  7626 W art     : b55d9000-b55df000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 16:02:53.486  7626  7626 W art     : b55df000-b55e0000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b55e0000-b55e1000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 16:02:53.486  7626  7626 W art     : b55e1000-b55e2000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 16:02:53.486  7626  7626 W art     : b55e2000-b55eb000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
07-05 16:02:53.486  7626  7626 W art     : b55eb000-b55ec000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
07-05 16:02:53.486  7626  7626 W art     : b55ec000-b55ed000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
07-05 16:02:53.486  7626  7626 W art     : b55ed000-b567e000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 16:02:53.486  7626  7626 W art     : b567e000-b567f000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b567f000-b568a000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 16:02:53.486  7626  7626 W art     : b568a000-b568b000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
07-05 16:02:53.486  7626  7626 W art     : b568c000-b569e000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
07-05 16:02:53.486  7626  7626 W art     : b569e000-b569f000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
07-05 16:02:53.486  7626  7626 W art     : b569f000-b56a0000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
07-05 16:02:53.486  7626  7626 W art     : b56a1000-b56a6000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
07-05 16:02:53.486  7626  7626 W art     : b56a6000-b56a7000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
07-05 16:02:53.486  7626  7626 W art     : b56a7000-b56a8000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
07-05 16:02:53.486  7626  7626 W art     : b56a9000-b5716000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
07-05 16:02:53.486  7626  7626 W art     : b5716000-b5717000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5717000-b5719000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
07-05 16:02:53.486  7626  7626 W art     : b5719000-b571a000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
07-05 16:02:53.486  7626  7626 W art     : b571a000-b571b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b571b000-b5722000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 16:02:53.486  7626  7626 W art     : b5722000-b5723000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 16:02:53.486  7626  7626 W art     : b5723000-b5724000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 16:02:53.486  7626  7626 W art     : b5725000-b57a5000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 16:02:53.486  7626  7626 W art     : b57a5000-b57a6000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b57a6000-b57a7000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 16:02:53.486  7626  7626 W art     : b57a7000-b57a8000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
07-05 16:02:53.486  7626  7626 W art     : b57a8000-b57bf000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b57bf000-b57f6000 r-xp 00000000 b3:17 3244       /system/vendor/l
07-05 16:02:53.486  7626  7626 W art     : ib/libqc-opt.so
07-05 16:02:53.486  7626  7626 W art     : b57f6000-b57f7000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 16:02:53.486  7626  7626 W art     : b57f7000-b57f8000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
07-05 16:02:53.486  7626  7626 W art     : b57f8000-b5814000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 16:02:53.486  7626  7626 W art     : b5814000-b5815000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 16:02:53.486  7626  7626 W art     : b5815000-b5816000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
07-05 16:02:53.486  7626  7626 W art     : b5817000-b5878000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-05 16:02:53.486  7626  7626 W art     : b5878000-b587a000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-05 16:02:53.486  7626  7626 W art     : b587a000-b587b000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-05 16:02:53.486  7626  7626 W art     : b587c000-b58a3000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
07-05 16:02:53.486  7626  7626 W art     : b58a3000-b58a4000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b58a4000-b58a5000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
07-05 16:02:53.486  7626  7626 W art     : b58a5000-b58a6000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
07-05 16:02:53.486  7626  7626 W art     : b58a7000-b58af000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 16:02:53.486  7626  7626 W art     : b58af000-b58b1000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 16:02:53.486  7626  7626 W art     : b58b1000-b58b2000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
07-05 16:02:53.486  7626  7626 W art     : b58b3000-b58b6000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
07-05 16:02:53.486  7626  7626 W art     : b58b6000-b58b7000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
07-05 16:02:53.486  7626  7626 W art     : b58b7000-b58b8000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
07-05 16:02:53.486  7626  7626 W art     : b58b8000-b58bc000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
07-05 16:02:53.486  7626  7626 W art     : b58bc000-b58bd000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b58bd000-b58be000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
07-05 16:02:53.486  7626  7626 W art     : b58be000-b58bf000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
07-05 16:02:53.486  7626  7626 W art     : b58bf000-b58cf000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
07-05 16:02:53.486  7626  7626 W art     : b58cf000-b58d0000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
07-05 16:02:53.486  7626  7626 W art     : b58d0000-b58d1000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
07-05 16:02:53.486  7626  7626 W art     : b58d1000-b5917000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5917000-b5920000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
07-05 16:02:53.486  7626  7626 W art     : b5920000-b5921000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
07-05 16:02:53.486  7626  7626 W art     : b5921000-b5922000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
07-05 16:02:53.486  7626  7626 W art     : b5923000-b5928000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
07-05 16:02:53.486  7626  7626 W art     : b5928000-b5929000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
07-05 16:02:53.486  7626  7626 W art     : b5929000-b592a000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
07-05 16:02:53.486  7626  7626 W art     : b592a000-b592d000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 16:02:53.486  7626  7626 W art     : b592d000-b592e000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b592e000-b592f000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 16:02:53.486  7626  7626 W art     : b592f000-b5930000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
07-05 16:02:53.486  7626  7626 W art     : b5931000-b5949000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 16:02:53.486  7626  7626 W art     : b5949000-b594a000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b594a000-b594b000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 16:02:53.486  7626  7626 W art     : b594b000-b594c000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 16:02:53.486  7626  7626 W art     : b594c000-b594d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 16:02:53.486  7626  7626 W art     : b594d000-b5ae7000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
07-05 16:02:53.486  7626  7626 W art     : b5ae7000-b5ae8000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5ae8000-b5af5000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
07-05 16:02:53.486  7626  7626 W art     : b5af5000-b5af6000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
07-05 16:02:53.486  7626  7626 W art     : b5af6000-b5afa000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
07-05 16:02:53.486  7626  7626 W art     : b5afa000-b5afb000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5afb000-b5afc000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
07-05 16:02:53.486  7626  7626 W art     : b5afc000-b5afd000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
07-05 16:02:53.486  7626  7626 W art     : b5afd000-b5b10000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
07-05 16:02:53.486  7626  7626 W art     : b5b10000-b5b11000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
07-05 16:02:53.486  7626  7626 W art     : b5b11000-b5b12000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
07-05 16:02:53.486  7626  7626 W art     : b5b13000-b5b5e000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
07-05 16:02:53.486  7626  7626 W art     : b5b5e000-b5b5f000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
07-05 16:02:53.486  7626  7626 W art     : b5b5f000-b5b60000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
07-05 16:02:53.486  7626  7626 W art     : b5b60000-b5b62000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5b63000-b5b74000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 16:02:53.486  7626  7626 W art     : b5b74000-b5b75000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5b75000-b5b76000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 16:02:53.486  7626  7626 W art     : b5b76000-b5b77000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
07-05 16:02:53.486  7626  7626 W art     : b5b77000-b5b78000 r--p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5b78000-b5b82000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
07-05 16:02:53.486  7626  7626 W art     : b5b82000-b5b84000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
07-05 16:02:53.486  7626  7626 W art     : b5b84000-b5b85000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
07-05 16:02:53.486  7626  7626 W art     : b5b85000-b5b9e000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
07-05 16:02:53.486  7626  7626 W art     : b5b9e000-b5b9f000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
07-05 16:02:53.486  7626  7626 W art     : b5b9f000-b5ba2000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
07-05 16:02:53.486  7626  7626 W art     : b5ba2000-b5ba6000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5ba6000-b5c1a000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
07-05 16:02:53.486  7626  7626 W art     : b5c1a000-b5c1b000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5c1b000-b5c1e000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
07-05 16:02:53.486  7626  7626 W art     : b5c1e000-b5c1f000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
07-05 16:02:53.486  7626  7626 W art     : b5c1f000-b5c20000 r--p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5c20000-b5c23000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
07-05 16:02:53.486  7626  7626 W art     : b5c23000-b5c24000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
07-05 16:02:53.486  7626  7626 W art     : b5c24000-b5c25000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
07-05 16:02:53.486  7626  7626 W art     : b5c25000-b5c26000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b5c26000-b5c2b000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 16:02:53.486  7626  7626 W art     : b5c2b000-b5c2c000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 16:02:53.486  7626  7626 W art     : b5c2c000-b5c2d000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
07-05 16:02:53.486  7626  7626 W art     : b5c2d000-b5c2e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b5c2e000-b5c31000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 16:02:53.486  7626  7626 W art     : b5c31000-b5c32000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 16:02:53.486  7626  7626 W art     : b5c32000-b5c33000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
07-05 16:02:53.486  7626  7626 W art     : b5c33000-b5c34000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b5c34000-b5c38000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
07-05 16:02:53.486  7626  7626 W art     : b5c38000-b5c39000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
07-05 16:02:53.486  7626  7626 W art     : b5c39000-b5c3a000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
07-05 16:02:53.486  7626  7626 W art     : b5c3a000-b5c3b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 16:02:53.486  7626  7626 W art     : b5c3b000-b5c3f000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 16:02:53.486  7626  7626 W art     : b5c3f000-b5c40000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 16:02:53.486  7626  7626 W art     : b5c40000-b5c41000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
07-05 16:02:53.486  7626  7626 W art     : b5c41000-b5c42000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b5c42000-b5c50000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-05 16:02:53.486  7626  7626 W art     : b5c50000-b5c51000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b5c51000-b5c52000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-05 16:02:53.486  7626  7626 W art     : b5c52000-b5c53000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-05 16:02:53.486  7626  7626 W art     : b5c53000-b5c5d000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 16:02:53.486  7626  7626 W art     : b5c5d000-b5c60000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 16:02:53.486  7626  7626 W art     : b5c60000-b5c61000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
07-05 16:02:53.486  7626  7626 W art     : b5c61000-b5c62000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b5c62000-b5c6c000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
07-05 16:02:53.486  7626  7626 W art     : b5c6c000-b5c6f000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
07-05 16:02:53.486  7626  7626 W art     : b5c6f000-b5c70000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
07-05 16:02:53.486  7626  7626 W art     : b5c70000-b5c74000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
07-05 16:02:53.486  7626  7626 W art     : b5c74000-b5c75000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
07-05 16:02:53.486  7626  7626 W art     : b5c75000-b5c76000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
07-05 16:02:53.486  7626  7626 W art     : b5c76000-b5c77000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b5c77000-b5c84000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-05 16:02:53.486  7626  7626 W art     : b5c84000-b5c86000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-05 16:02:53.486  7626  7626 W art     : b5c86000-b5c87000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-05 16:02:53.486  7626  7626 W art     : b5c87000-b6099000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
07-05 16:02:53.486  7626  7626 W art     : b6099000-b609a000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b609a000-b60a3000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
07-05 16:02:53.486  7626  7626 W art     : b60a3000-b60a7000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
07-05 16:02:53.486  7626  7626 W art     : b60a7000-b60a8000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b60a8000-b60af000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-05 16:02:53.486  7626  7626 W art     : b60af000-b60b0000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-05 16:02:53.486  7626  7626 W art     : b60b0000-b60b1000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-05 16:02:53.486  7626  7626 W art     : b60b1000-b60b2000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b60b2000-b60cd000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-05 16:02:53.486  7626  7626 W art     : b60cd000-b60ce000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-05 16:02:53.486  7626  7626 W art     : b60ce000-b60cf000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-05 16:02:53.486  7626  7626 W art     : b60cf000-b60d0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b60d0000-b611c000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 16:02:53.486  7626  7626 W art     : b611c000-b611d000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b611d000-b611e000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 16:02:53.486  7626  7626 W art     : b611e000-b611f000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
07-05 16:02:53.486  7626  7626 W art     : b611f000-b6120000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6120000-b6124000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
07-05 16:02:53.486  7626  7626 W art     : b6124000-b6125000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6125000-b6126000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
07-05 16:02:53.486  7626  7626 W art     : b6126000-b6127000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
07-05 16:02:53.486  7626  7626 W art     : b6127000-b615f000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
07-05 16:02:53.486  7626  7626 W art     : b615f000-b6160000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
07-05 16:02:53.486  7626  7626 W art     : b6160000-b6161000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
07-05 16:02:53.486  7626  7626 W art     : b6161000-b6162000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6162000-b6200000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
07-05 16:02:53.486  7626  7626 W art     : b6200000-b6201000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6201000-b621f000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
07-05 16:02:53.486  7626  7626 W art     : b621f000-b6220000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
07-05 16:02:53.486  7626  7626 W art     : b6220000-b6393000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
07-05 16:02:53.486  7626  7626 W art     : b6393000-b639e000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
07-05 16:02:53.486  7626  7626 W art     : b639e000-b639f000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
07-05 16:02:53.486  7626  7626 W art     : b639f000-b64b6000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-05 16:02:53.486  7626  7626 W art     : b64b6000-b64c1000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-05 16:02:53.486  7626  7626 W art     : b64c1000-b64c2000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-05 16:02:53.486  7626  7626 W art     : b64c2000-b64c6000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b64c6000-b64ea000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
07-05 16:02:53.486  7626  7626 W art     : b64ea000-b64ec000 r--p 00023000 b3:17 400        /system/lib/libssl.so
07-05 16:02:53.486  7626  7626 W art     : b64ec000-b64ed000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
07-05 16:02:53.486  7626  7626 W art     : b64ed000-b6593000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
07-05 16:02:53.486  7626  7626 W art     : b6593000-b65a0000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
07-05 16:02:53.486  7626  7626 W art     : b65a0000-b65a1000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
07-05 16:02:53.486  7626  7626 W art     : b65a1000-b65a2000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b65a2000-b65f5000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
07-05 16:02:53.486  7626  7626 W art     : b65f5000-b65f6000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b65f6000-b65f7000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
07-05 16:02:53.486  7626  7626 W art     : b65f7000-b65f8000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
07-05 16:02:53.486  7626  7626 W art     : b65f8000-b65fd000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b65fd000-b660f000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
07-05 16:02:53.486  7626  7626 W art     : b660f000-b6610000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6610000-b6611000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
07-05 16:02:53.486  7626  7626 W art     : b6611000-b6612000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
07-05 16:02:53.486  7626  7626 W art     : b6612000-b6619000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 16:02:53.486  7626  7626 W art     : b6619000-b661a000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 16:02:53.486  7626  7626 W art     : b661a000-b661b000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
07-05 16:02:53.486  7626  7626 W art     : b661b000-b661c000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b661c000-b661f000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
07-05 16:02:53.486  7626  7626 W art     : b661f000-b6620000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
07-05 16:02:53.486  7626  7626 W art     : b6620000-b6621000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
07-05 16:02:53.486  7626  7626 W art     : b6621000-b6625000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
07-05 16:02:53.486  7626  7626 W art     : b6625000-b6626000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
07-05 16:02:53.486  7626  7626 W art     : b6626000-b6627000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
07-05 16:02:53.486  7626  7626 W art     : b6627000-b6635000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
07-05 16:02:53.486  7626  7626 W art     : b6635000-b6636000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6636000-b6637000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
07-05 16:02:53.486  7626  7626 W art     : b6637000-b6638000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
07-05 16:02:53.486  7626  7626 W art     : b6638000-b6641000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 16:02:53.486  7626  7626 W art     : b6641000-b6642000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 16:02:53.486  7626  7626 W art     : b6642000-b6643000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
07-05 16:02:53.486  7626  7626 W art     : b6643000-b66a9000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
07-05 16:02:53.486  7626  7626 W art     : b66a9000-b66aa000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b66aa000-b66ac000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
07-05 16:02:53.486  7626  7626 W art     : b66ac000-b66b5000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
07-05 16:02:53.486  7626  7626 W art     : b66b5000-b66b8000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b66b8000-b674f000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-05 16:02:53.486  7626  7626 W art     : b674f000-b6751000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-05 16:02:53.486  7626  7626 W art     : b6751000-b6752000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-05 16:02:53.486  7626  7626 W art     : b6752000-b6753000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6753000-b6a74000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
07-05 16:02:53.486  7626  7626 W art     : b6a74000-b6a75000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6a75000-b6a90000 r--p 00321000 b3:17 377        /system/lib/libskia.so
07-05 16:02:53.486  7626  7626 W art     : b6a90000-b6a94000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
07-05 16:02:53.486  7626  7626 W art     : b6a94000-b6a99000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6a99000-b6aa1000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 16:02:53.486  7626  7626 W art     : b6aa1000-b6aa2000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 16:02:53.486  7626  7626 W art     : b6aa2000-b6aa3000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
07-05 16:02:53.486  7626  7626 W art     : b6aa3000-b6ad1000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-05 16:02:53.486  7626  7626 W art     : b6ad1000-b6ad2000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6ad2000-b6ad9000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-05 16:02:53.486  7626  7626 W art     : b6ad9000-b6ada000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-05 16:02:53.486  7626  7626 W art     : b6ada000-b6b20000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-05 16:02:53.486  7626  7626 W art     : b6b20000-b6b21000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6b21000-b6b24000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-05 16:02:53.486  7626  7626 W art     : b6b24000-b6b25000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-05 16:02:53.486  7626  7626 W art     : b6b25000-b6b40000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
07-05 16:02:53.486  7626  7626 W art     : b6b40000-b6b44000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
07-05 16:02:53.486  7626  7626 W art     : b6b44000-b6b45000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
07-05 16:02:53.486  7626  7626 W art     : b6b45000-b6b92000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
07-05 16:02:53.486  7626  7626 W art     : b6b92000-b6b93000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6b93000-b6b9f000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
07-05 16:02:53.486  7626  7626 W art     : b6b9f000-b6ba0000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
07-05 16:02:53.486  7626  7626 W art     : b6ba0000-b6bad000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
07-05 16:02:53.486  7626  7626 W art     : b6bad000-b6bae000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6bae000-b6baf000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
07-05 16:02:53.486  7626  7626 W art     : b6baf000-b6bb0000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
07-05 16:02:53.486  7626  7626 W art     : b6bb0000-b6bb8000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
07-05 16:02:53.486  7626  7626 W art     : b6bb8000-b6bb9000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6bb9000-b6bba000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
07-05 16:02:53.486  7626  7626 W art     : b6bba000-b6bbb000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
07-05 16:02:53.486  7626  7626 W art     : b6bbb000-b6bc2000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-05 16:02:53.486  7626  7626 W art     : b6bc2000-b6bc3000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-05 16:02:53.486  7626  7626 W art     : b6bc3000-b6bc4000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-05 16:02:53.486  7626  7626 W art     : b6bc4000-b6bd8000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
07-05 16:02:53.486  7626  7626 W art     : b6bd8000-b6bda000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
07-05 16:02:53.486  7626  7626 W art     : b6bda000-b6bdb000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
07-05 16:02:53.486  7626  7626 W art     : b6bdb000-b6c03000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
07-05 16:02:53.486  7626  7626 W art     : b6c03000-b6c05000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
07-05 16:02:53.486  7626  7626 W art     : b6c05000-b6c06000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
07-05 16:02:53.486  7626  7626 W art     : b6c06000-b6c09000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
07-05 16:02:53.486  7626  7626 W art     : b6c09000-b6c0a000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
07-05 16:02:53.486  7626  7626 W art     : b6c0a000-b6c0b000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
07-05 16:02:53.486  7626  7626 W art     : b6c0b000-b6c14000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-05 16:02:53.486  7626  7626 W art     : b6c14000-b6c15000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-05 16:02:53.486  7626  7626 W art     : b6c15000-b6c16000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-05 16:02:53.486  7626  7626 W art     : b6c16000-b6c36000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-05 16:02:53.486  7626  7626 W art     : b6c36000-b6c37000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-05 16:02:53.486  7626  7626 W art     : b6c37000-b6c38000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-05 16:02:53.486  7626  7626 W art     : b6c38000-b6cab000 r-xp 00000000 b3:17 860        /system/lib/libc.so
07-05 16:02:53.486  7626  7626 W art     : b6cab000-b6caf000 r--p 00072000 b3:17 860        /system/lib/libc.so
07-05 16:02:53.486  7626  7626 W art     : b6caf000-b6cb2000 rw-p 00076000 b3:17 860        /system/lib/libc.so
07-05 16:02:53.486  7626  7626 W art     : b6cb2000-b6cbc000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6cbc000-b6d44000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-05 16:02:53.486  7626  7626 W art     : b6d44000-b6d45000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6d45000-b6d49000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-05 16:02:53.486  7626  7626 W art     : b6d49000-b6d4a000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-05 16:02:53.486  7626  7626 W art     : b6d4a000-b6d4b000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6d4b000-b6d74000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-05 16:02:53.486  7626  7626 W art     : b6d74000-b6d75000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6d75000-b6d78000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-05 16:02:53.486  7626  7626 W art     : b6d78000-b6d79000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-05 16:02:53.486  7626  7626 W art     : b6d79000-b6e53000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 16:02:53.486  7626  7626 W art     : b6e53000-b6e5a000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 16:02:53.486  7626  7626 W art     : b6e5a000-b6e62000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
07-05 16:02:53.486  7626  7626 W art     : b6e62000-b6e63000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6e63000-b6e64000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 16:02:53.486  7626  7626 W art     : b6e64000-b6e65000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-05 16:02:53.486  7626  7626 W art     : b6e65000-b6e66000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6e66000-b6e69000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6e69000-b6e8e000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
07-05 16:02:53.486  7626  7626 W art     : b6e8e000-b6e8f000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6e8f000-b6e96000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
07-05 16:02:53.486  7626  7626 W art     : b6e96000-b6e97000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
07-05 16:02:53.486  7626  7626 W art     : b6e97000-b6e9e000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-05 16:02:53.486  7626  7626 W art     : b6e9e000-b6e9f000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-05 16:02:53.486  7626  7626 W art     : b6e9f000-b6ea0000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-05 16:02:53.486  7626  7626 W art     : b6ea0000-b6ea1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6ea1000-b6eb9000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
07-05 16:02:53.486  7626  7626 W art     : b6eb9000-b6eba000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6eba000-b6ebb000 r--p 00018000 b3:17 918        /system/lib/libutils.so
07-05 16:02:53.486  7626  7626 W art     : b6ebb000-b6ebc000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
07-05 16:02:53.486  7626  7626 W art     : b6ebc000-b6eca000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
07-05 16:02:53.486  7626  7626 W art     : b6eca000-b6ecb000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6ecb000-b6ecc000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
07-05 16:02:53.486  7626  7626 W art     : b6ecc000-b6ecd000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
07-05 16:02:53.486  7626  7626 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 16:02:53.486  7626  7626 W art     : b6ece000-b6ed0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6ed0000-b6ed1000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6ed1000-b6ed2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 16:02:53.486  7626  7626 W art     : b6ed2000-b6ed3000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-05 16:02:53.486  7626  7626 W art     : b6ed3000-b6ed4000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 16:02:53.486  7626  7626 W art     : b6ed4000-b6ef4000 r--s 00000000 00:0b 7184       /dev/__properties__
07-05 16:02:53.486  7626  7626 W art     : b6ef4000-b6ef5000 r--p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6ef5000-b6ef6000 ---p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6ef6000-b6ef8000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-05 16:02:53.486  7626  7626 W art     : b6ef8000-b6ef9000 r-xp 00000000 00:00 0          [sigpage]
07-05 16:02:53.486  7626  7626 W art     : b6ef9000-b6f14000 r-xp 00000000 b3:17 2770       /system/bin/linker
07-05 16:02:53.486  7626  7626 W art     : b6f14000-b6f15000 r--p 0001a000 b3:17 2770       /system/bin/linker
07-05 16:02:53.486  7626  7626 W art     : b6f15000-b6f17000 rw-p 0001b000 b3:17 2770       /system/bin/linker
07-05 16:02:53.486  7626  7626 W art     : b6f17000-b6f19000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : b6f19000-b6f1e000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-05 16:02:53.486  7626  7626 W art     : b6f1e000-b6f1f000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-05 16:02:53.486  7626  7626 W art     : b6f1f000-b6f20000 rw-p 00000000 00:00 0 
07-05 16:02:53.486  7626  7626 W art     : bec9e000-becbf000 rw-p 00000000 00:00 0          [stack]
07-05 16:02:53.486  7626  7626 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-05 16:02:53.526  7626  7626 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 16:02:53.536  1831  7633 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
07-05 16:02:53.536  1831  7633 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
07-05 16:02:53.546  1831  7633 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
07-05 16:02:53.546  1831  7633 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
07-05 16:02:53.566  7626  7626 I Radio-JNI: register_android_hardware_Radio DONE
07-05 16:02:53.576  1831  7633 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
07-05 16:02:53.576  1831  7633 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
07-05 16:02:53.576  7626  7626 E AffinityControl: AffinityControl: registerfunction enter
07-05 16:02:53.596  7626  7626 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 16:02:53.606   770  1618 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
07-05 16:02:53.606  1831  7633 W ThreadPoolDumper: Queue length for executor IcingConnectionExecutor with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
07-05 16:02:53.616   770  1731 D PackageManager: START PACKAGE DELETE: observer{114409749}
07-05 16:02:53.616   770  1731 D PackageManager: pkg{<packageName>}
07-05 16:02:53.616   770  1731 D PackageManager: user{0}
07-05 16:02:53.616   770  1731 D PackageManager: caller{2000}
07-05 16:02:53.616   770  1731 D PackageManager: flags{2}
07-05 16:02:53.616   770  1731 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 16:02:53.616   770  1731 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 16:02:53.616   770  1731 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 16:02:53.616   770  1731 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 16:02:53.616   770  1731 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 16:02:53.616   770   957 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 16:02:53.616   770   957 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 16:02:53.616   770   957 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 16:02:53.616   770   957 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 16:02:53.616   770   957 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 16:02:53.616   770   957 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 16:02:53.616   770   957 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 16:02:53.616   770   957 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-05 16:02:53.616   770   957 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 16:02:53.616   770   876 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-05 16:02:53.616   770   957 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 16:02:53.616   770   876 I ActivityManager: Killing 7235:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 16:02:53.616   770   876 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 16:02:53.616   770   876 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-05 16:02:53.626   770   876 D ActivityManager: mDVFSHelper.acquire()
07-05 16:02:53.636   770   957 D AASAinstall: there is not AASApackages.xml file
07-05 16:02:53.636  7662  7662 E Zygote  : v2
07-05 16:02:53.636  7662  7662 I libpersona: KNOX_SDCARD checking this for 10004
07-05 16:02:53.636  7662  7662 I libpersona: KNOX_SDCARD not a persona
07-05 16:02:53.636   770   876 I ActivityManager: Start proc 7662:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 16:02:53.636  7662  7662 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 16:02:53.636  7662  7662 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 16:02:53.636  7662  7662 E Zygote  : accessInfo : 0
07-05 16:02:53.636  7662  7662 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 16:02:53.646   770   876 I ActivityManager:   Force finishing activity ActivityRecord{f8507c1 u0 com.test.thalitest/.MainActivity t64}
07-05 16:02:53.666  7662  7662 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 16:02:53.666  7662  7662 D ActivityThread: Added TimaKeyStore provider
07-05 16:02:53.666   770  1422 D GraphicsStats: Buffer count: 4
07-05 16:02:53.666   770  2468 I WindowState: WIN DEATH: Window{223569e u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 16:02:53.666   770  1422 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@59a5991)
07-05 16:02:53.666   294   348 I SurfaceFlinger: id=22 Removed NainActivit (6/8)
07-05 16:02:53.666   770  1332 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUST,ED&NOT_VPN] ]
07-05 16:02:53.666   294   348 I SurfaceFlinger: id=22 Removed NainActivit (-2/8)
07-05 16:02:53.666   770  1332 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 16:02:53.666   770  1332 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 16:02:53.666   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbec863a4
07-05 16:02:53.676   770  2468 D InputDispatcher: Focus left window: 7235
07-05 16:02:53.696   770  1219 E LightSensor: RED : 0, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=2, cpl=3202560
07-05 16:02:53.696   770   938 D LightsService: [SvcLED]  onSensorChanged::light value = 0
07-05 16:02:53.696   770   938 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
07-05 16:02:53.706   770   938 D SensorManager: unregisterListener ::   
07-05 16:02:53.706   770   938 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 16:02:53.706   770   938 V AlarmManager:  remove PendingIntent] PendingIntent{8772a8d: PendingIntentRecord{fc24442 android broadcastIntent}}
07-05 16:02:53.906   770   957 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-05 16:02:53.926   770   957 W PackageSettings: Skipping PackageSetting{e0c2447 com.example.hello/10192} due to missing metadata
07-05 16:02:53.986   770   957 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-05 16:02:53.996   770   916 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 16:02:53.996   770   916 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)

```
