#### Test 8286536244f8192_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-26 14:59:50.947  5870  5910 I Finsky  : [840] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
--------- beginning of system
08-26 14:59:50.987   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 14:59:50.987   781  2302 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4341, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-26 14:59:50.987   781  2302 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-26 14:59:50.987   781  2302 D BatteryService: stay LED for charging
08-26 14:59:50.987   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 14:59:50.987   781   781 I MotionRecognitionService: Plugged
08-26 14:59:50.987   781   781 D MotionRecognitionService:   cableConnection= 1
08-26 14:59:50.987   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-26 14:59:50.987   781   781 D MotionRecognitionService: skip setTransmitPower. 
08-26 14:59:51.007  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 14:59:51.007  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-26 14:59:51.007  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:59:51.007  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 14:59:51.017  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:59:51.017  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 14:59:51.027  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 14:59:51.027  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 14:59:51.557  5870  5910 I Finsky  : [840] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
08-26 14:59:51.567  5870  5870 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
08-26 14:59:52.147  2165  2165 E audit   : type=1400 msg=audit(1472216392.147:285): avc:  denied  { execmod } for  pid=6441 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-26 14:59:52.147  2165  2165 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:52.147  2165  2165 E audit   : type=1300 msg=audit(1472216392.147:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd8000 a1=51000 a2=5 a3=4 items=0 ppid=3570 ppcomm=adbd pid=6441 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-26 14:59:52.147  2165  2165 E audit   : type=1327 msg=audit(1472216392.147:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-26 14:59:52.147  2165  2165 E audit   : type=1320 msg=audit(1472216392.147:285): 
08-26 14:59:52.217  2165  2165 E audit   : type=1400 msg=audit(1472216392.217:286): avc:  denied  { execmod } for  pid=6441 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-26 14:59:52.217  2165  2165 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:52.217  2165  2165 E audit   : type=1300 msg=audit(1472216392.217:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f98000 a1=51000 a2=5 a3=4 items=0 ppid=3570 ppcomm=adbd pid=6441 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-26 14:59:52.217  2165  2165 E audit   : type=1327 msg=audit(1472216392.217:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-26 14:59:52.217  2165  2165 E audit   : type=1320 msg=audit(1472216392.217:286): 
08-26 14:59:52.227   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-26 14:59:52.277  2165  2165 E audit   : type=1400 msg=audit(1472216392.277:287): avc:  denied  { execmod } for  pid=6441 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-26 14:59:52.277  2165  2165 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:52.277  2165  2165 E audit   : type=1300 msg=audit(1472216392.277:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f98000 a1=51000 a2=5 a3=4 items=0 ppid=3570 ppcomm=adbd pid=6441 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-26 14:59:52.277  2165  2165 E audit   : type=1327 msg=audit(1472216392.277:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-26 14:59:52.277  2165  2165 E audit   : type=1320 msg=audit(1472216392.277:287): 
08-26 14:59:52.277  6441  6441 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 14:59:52.287  6441  6441 D AndroidRuntime: CheckJNI is OFF
08-26 14:59:52.287  6441  6441 D AndroidRuntime: readGMSProperty: start
08-26 14:59:52.287  6441  6441 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:59:52.287  6441  6441 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:59:52.287  6441  6441 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 14:59:52.287  6441  6441 D AndroidRuntime: readGMSProperty: end
08-26 14:59:52.287  6441  6441 D AndroidRuntime: addProductProperty: start
08-26 14:59:52.297  6441  6441 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-26 14:59:52.297  6441  6441 W art     : aedff000-b1d25000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-26 14:59:52.297  6441  6441 W art     : b1d25000-b3f94000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-26 14:59:52.297  6441  6441 W art     : b3f94000-b3f95000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-26 14:59:52.297  6441  6441 W art     : b3f95000-b3f96000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-26 14:59:52.297  6441  6441 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-26 14:59:52.297  6441  6441 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-26 14:59:52.297  6441  6441 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b4740000-b4840000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-26 14:59:52.297  6441  6441 W art     : b4841000-b486a000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-26 14:59:52.297  6441  6441 W art     : b486a000-b486d000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-26 14:59:52.297  6441  6441 W art     : b486d000-b486e000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-26 14:59:52.297  6441  6441 W art     : b486e000-b486f000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-26 14:59:52.297  6441  6441 W art     : b486f000-b4870000 r--p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b4870000-b4890000 r--s 00000000 00:0b 9219       /dev/__properties__
08-26 14:59:52.297  6441  6441 W art     : b4890000-b52a1000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-26 14:59:52.297  6441  6441 W art     : b52a1000-b52a2000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b52a2000-b52eb000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-26 14:59:52.297  6441  6441 W art     : b52eb000-b52ec000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-26 14:59:52.297  6441  6441 W art     : b52ec000-b52f4000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b52f4000-b52f5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b52f5000-b532a000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-26 14:59:52.297  6441  6441 W art     : b532a000-b532b000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b532b000-b532c000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-26 14:59:52.297  6441  6441 W art     : b532c000-b532d000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-26 14:59:52.297  6441  6441 W art     : b532d000-b5385000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-26 14:59:52.297  6441  6441 W art     : b5385000-b5386000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5386000-b5387000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-26 14:59:52.297  6441  6441 W art     : b5387000-b5388000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-26 14:59:52.297  6441  6441 W art     : b5389000-b538f000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-26 14:59:52.297  6441  6441 W art     : b538f000-b5390000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-26 14:59:52.297  6441  6441 W art     : b5390000-b5391000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-26 14:59:52.297  6441  6441 W art     : b5391000-b5393000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5394000-b539e000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-26 14:59:52.297  6441  6441 W art     : b539e000-b53a1000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-26 14:59:52.297  6441  6441 W art     : b53a1000-b53a2000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-26 14:59:52.297  6441  6441 W art     : b53a3000-b53ba000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-26 14:59:52.297  6441  6441 W art     : b53ba000-b53bb000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b53bb000-b53bc000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-26 14:59:52.297  6441  6441 W art     : b53bc000-b53bd000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-26 14:59:52.297  6441  6441 W art     : b53be000-b53c8000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-26 14:59:52.297  6441  6441 W art     : b53c8000-b53c9000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-26 14:59:52.297  6441  6441 W art     : b53c9000-b53ca000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-26 14:59:52.297  6441  6441 W art     : b53ca000-b53ce000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-26 14:59:52.297  6441  6441 W art     : b53ce000-b53cf000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-26 14:59:52.297  6441  6441 W art     : b53cf000-b53d0000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-26 14:59:52.297  6441  6441 W art     : b53d0000-b53e6000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-26 14:59:52.297  6441  6441 W art     : b53e6000-b53e7000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-26 14:59:52.297  6441  6441 W art     : b53e7000-b53e8000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-26 14:59:52.297  6441  6441 W art     : b53e8000-b53f5000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-26 14:59:52.297  6441  6441 W art     : b53f5000-b53f6000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-26 14:59:52.297  6441  6441 W art     : b53f6000-b53f7000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-26 14:59:52.297  6441  6441 W art     : b53f7000-b5457000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-26 14:59:52.297  6441  6441 W art     : b5457000-b545a000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-26 14:59:52.297  6441  6441 W art     : b545a000-b545e000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b545e000-b54bf000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-26 14:59:52.297  6441  6441 W art     : b54bf000-b54c0000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-26 14:59:52.297  6441  6441 W art     : b54c0000-b550f000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-26 14:59:52.297  6441  6441 W art     : b550f000-b5511000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-26 14:59:52.297  6441  6441 W art     : b5511000-b5512000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-26 14:59:52.297  6441  6441 W art     : b5512000-b5513000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5513000-b551a000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-26 14:59:52.297  6441  6441 W art     : b551a000-b551b000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-26 14:59:52.297  6441  6441 W art     : b551b000-b551c000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-26 14:59:52.297  6441  6441 W art     : avc_common.so
08-26 14:59:52.297  6441  6441 W art     : b551d000-b5520000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-26 14:59:52.297  6441  6441 W art     : b5520000-b5521000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-26 14:59:52.297  6441  6441 W art     : b5521000-b5522000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-26 14:59:52.297  6441  6441 W art     : enc_common.so
08-26 14:59:52.297  6441  6441 W art     : b5523000-b5527000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-26 14:59:52.297  6441  6441 W art     : b5527000-b5528000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5528000-b5529000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-26 14:59:52.297  6441  6441 W art     : b5529000-b552a000 rw-p 00005000 b3:17 2510       /syste
08-26 14:59:52.297  6441  6441 W art     : m/lib/libpowermanager.so
08-26 14:59:52.297  6441  6441 W art     : b552b000-b5548000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-26 14:59:52.297  6441  6441 W art     : b5548000-b5549000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-26 14:59:52.297  6441  6441 W art     : b5549000-b554a000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-26 14:59:52.297  6441  6441 W art     : b554b000-b5550000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-26 14:59:52.297  6441  6441 W art     : b5550000-b5551000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-26 14:59:52.297  6441  6441 W art     : b5551000-b5552000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-26 14:59:52.297  6441  6441 W art     : b5553000-b5584000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-26 14:59:52.297  6441  6441 W art     : b5584000-b5587000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-26 14:59:52.297  6441  6441 W art     : b5587000-b5588000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-26 14:59:52.297  6441  6441 W art     : b5589000-b55c4000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-26 14:59:52.297  6441  6441 W art     : b55c4000-b55c5000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-26 14:59:52.297  6441  6441 W art     : b55c5000-b55c6000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-26 14:59:52.297  6441  6441 W art     : b55c7000-b55ce000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-26 14:59:52.297  6441  6441 W art     : b55ce000-b55cf000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b55cf000-b55d0000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-26 14:59:52.297  6441  6441 W art     : b55d0000-b55d1000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-26 14:59:52.297  6441  6441 W art     : b55d1000-b55d2000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b55d2000-b55e9000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-26 14:59:52.297  6441  6441 W art     : b55e9000-b55ea000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b55ea000-b55ed000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-26 14:59:52.297  6441  6441 W art     : b55ed000-b55ee000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-26 14:59:52.297  6441  6441 W art     : b55ee000-b560d000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-26 14:59:52.297  6441  6441 W art     : b560d000-b560e000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-26 14:59:52.297  6441  6441 W art     : b560e000-b560f000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-26 14:59:52.297  6441  6441 W art     : b560f000-b564d000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-26 14:59:52.297  6441  6441 W art     : b564d000-b564e000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b564e000-b5650000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-26 14:59:52.297  6441  6441 W art     : b5650000-b5651000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-26 14:59:52.297  6441  6441 W art     : b5652000-b5659000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-26 14:59:52.297  6441  6441 W art     : b5659000-b565a000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-26 14:59:52.297  6441  6441 W art     : b565a000-b565b000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-26 14:59:52.297  6441  6441 W art     : b565c000-b565f000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-26 14:59:52.297  6441  6441 W art     : b565f000-b5660000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-26 14:59:52.297  6441  6441 W art     : b5660000-b5661000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-26 14:59:52.297  6441  6441 W art     : b5661000-b5667000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-26 14:59:52.297  6441  6441 W art     : b5667000-b5668000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5668000-b5669000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-26 14:59:52.297  6441  6441 W art     : b5669000-b566a000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-26 14:59:52.297  6441  6441 W art     : b566a000-b5673000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-26 14:59:52.297  6441  6441 W art     : b5673000-b5674000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-26 14:59:52.297  6441  6441 W art     : b5674000-b5675000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-26 14:59:52.297  6441  6441 W art     : b5675000-b5706000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-26 14:59:52.297  6441  6441 W art     : b5706000-b5707000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5707000-b5712000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-26 14:59:52.297  6441  6441 W art     : b5712000-b5713000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-26 14:59:52.297  6441  6441 W art     : b5714000-b5726000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-26 14:59:52.297  6441  6441 W art     : b5726000-b5727000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-26 14:59:52.297  6441  6441 W art     : b5727000-b5728000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-26 14:59:52.297  6441  6441 W art     : b5729000-b572e000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-26 14:59:52.297  6441  6441 W art     : b572e000-b572f000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-26 14:59:52.297  6441  6441 W art     : b572f000-b5730000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-26 14:59:52.297  6441  6441 W art     : b5731000-b579e000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-26 14:59:52.297  6441  6441 W art     : b579e000-b579f000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b579f000-b57a1000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-26 14:59:52.297  6441  6441 W art     : b57a1000-b57a2000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-26 14:59:52.297  6441  6441 W art     : b57a2000-b57a3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b57a3000-b57aa000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-26 14:59:52.297  6441  6441 W art     : b57aa000-b57ab000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-26 14:59:52.297  6441  6441 W art     : b57ab000-b57ac000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-26 14:59:52.297  6441  6441 W art     : b57ad000-b582d000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-26 14:59:52.297  6441  6441 W art     : b582d000-b582e000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b582e000-b582f000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-26 14:59:52.297  6441  6441 W art     : b582f000-b5830000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-26 14:59:52.297  6441  6441 W art     : b5830000-b5847000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5847000-b587e000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-26 14:59:52.297  6441  6441 W art     : ib/libqc-opt.so
08-26 14:59:52.297  6441  6441 W art     : b587e000-b587f000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-26 14:59:52.297  6441  6441 W art     : b587f000-b5880000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-26 14:59:52.297  6441  6441 W art     : b5880000-b589c000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-26 14:59:52.297  6441  6441 W art     : b589c000-b589d000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-26 14:59:52.297  6441  6441 W art     : b589d000-b589e000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-26 14:59:52.297  6441  6441 W art     : b589f000-b5900000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-26 14:59:52.297  6441  6441 W art     : b5900000-b5902000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-26 14:59:52.297  6441  6441 W art     : b5902000-b5903000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-26 14:59:52.297  6441  6441 W art     : b5904000-b592b000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-26 14:59:52.297  6441  6441 W art     : b592b000-b592c000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b592c000-b592d000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-26 14:59:52.297  6441  6441 W art     : b592d000-b592e000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-26 14:59:52.297  6441  6441 W art     : b592f000-b5937000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-26 14:59:52.297  6441  6441 W art     : b5937000-b5939000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-26 14:59:52.297  6441  6441 W art     : b5939000-b593a000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-26 14:59:52.297  6441  6441 W art     : b593b000-b593e000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-26 14:59:52.297  6441  6441 W art     : b593e000-b593f000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-26 14:59:52.297  6441  6441 W art     : b593f000-b5940000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-26 14:59:52.297  6441  6441 W art     : b5940000-b5944000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-26 14:59:52.297  6441  6441 W art     : b5944000-b5945000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5945000-b5946000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-26 14:59:52.297  6441  6441 W art     : b5946000-b5947000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-26 14:59:52.297  6441  6441 W art     : b5947000-b5957000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-26 14:59:52.297  6441  6441 W art     : b5957000-b5958000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-26 14:59:52.297  6441  6441 W art     : b5958000-b5959000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-26 14:59:52.297  6441  6441 W art     : b5959000-b599f000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b599f000-b59a8000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-26 14:59:52.297  6441  6441 W art     : b59a8000-b59a9000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-26 14:59:52.297  6441  6441 W art     : b59a9000-b59aa000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-26 14:59:52.297  6441  6441 W art     : b59ab000-b59b0000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-26 14:59:52.297  6441  6441 W art     : b59b0000-b59b1000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-26 14:59:52.297  6441  6441 W art     : b59b1000-b59b2000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-26 14:59:52.297  6441  6441 W art     : b59b2000-b59b5000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-26 14:59:52.297  6441  6441 W art     : b59b5000-b59b6000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b59b6000-b59b7000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-26 14:59:52.297  6441  6441 W art     : b59b7000-b59b8000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-26 14:59:52.297  6441  6441 W art     : b59b9000-b59d1000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-26 14:59:52.297  6441  6441 W art     : b59d1000-b59d2000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b59d2000-b59d3000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-26 14:59:52.297  6441  6441 W art     : b59d3000-b59d4000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-26 14:59:52.297  6441  6441 W art     : b59d5000-b5b6f000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-26 14:59:52.297  6441  6441 W art     : b5b6f000-b5b70000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5b70000-b5b7d000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-26 14:59:52.297  6441  6441 W art     : b5b7d000-b5b7e000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-26 14:59:52.297  6441  6441 W art     : b5b7e000-b5b82000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-26 14:59:52.297  6441  6441 W art     : b5b82000-b5b83000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5b83000-b5b84000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-26 14:59:52.297  6441  6441 W art     : b5b84000-b5b85000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-26 14:59:52.297  6441  6441 W art     : b5b85000-b5b98000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-26 14:59:52.297  6441  6441 W art     : b5b98000-b5b99000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-26 14:59:52.297  6441  6441 W art     : b5b99000-b5b9a000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-26 14:59:52.297  6441  6441 W art     : b5b9a000-b5b9b000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-26 14:59:52.297  6441  6441 W art     : b5b9b000-b5be6000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-26 14:59:52.297  6441  6441 W art     : b5be6000-b5be7000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-26 14:59:52.297  6441  6441 W art     : b5be7000-b5be8000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-26 14:59:52.297  6441  6441 W art     : b5be8000-b5bea000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5beb000-b5bfc000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-26 14:59:52.297  6441  6441 W art     : b5bfc000-b5bfd000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5bfd000-b5bfe000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-26 14:59:52.297  6441  6441 W art     : b5bfe000-b5bff000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-26 14:59:52.297  6441  6441 W art     : b5c00000-b5c0a000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-26 14:59:52.297  6441  6441 W art     : b5c0a000-b5c0c000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-26 14:59:52.297  6441  6441 W art     : b5c0c000-b5c0d000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-26 14:59:52.297  6441  6441 W art     : b5c0d000-b5c26000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-26 14:59:52.297  6441  6441 W art     : b5c26000-b5c27000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-26 14:59:52.297  6441  6441 W art     : b5c27000-b5c2a000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-26 14:59:52.297  6441  6441 W art     : b5c2a000-b5c2e000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5c2e000-b5ca2000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-26 14:59:52.297  6441  6441 W art     : b5ca2000-b5ca3000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5ca3000-b5ca6000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-26 14:59:52.297  6441  6441 W art     : b5ca6000-b5ca7000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-26 14:59:52.297  6441  6441 W art     : b5ca7000-b5ca8000 r--p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5ca8000-b5cab000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-26 14:59:52.297  6441  6441 W art     : b5cab000-b5cac000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-26 14:59:52.297  6441  6441 W art     : b5cac000-b5cad000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-26 14:59:52.297  6441  6441 W art     : b5cad000-b5cae000 r--p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5cae000-b5cb3000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-26 14:59:52.297  6441  6441 W art     : b5cb3000-b5cb4000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-26 14:59:52.297  6441  6441 W art     : b5cb4000-b5cb5000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-26 14:59:52.297  6441  6441 W art     : b5cb5000-b5cb6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b5cb6000-b5cb9000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-26 14:59:52.297  6441  6441 W art     : b5cb9000-b5cba000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-26 14:59:52.297  6441  6441 W art     : b5cba000-b5cbb000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-26 14:59:52.297  6441  6441 W art     : b5cbb000-b5cbc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b5cbc000-b5cc0000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-26 14:59:52.297  6441  6441 W art     : b5cc0000-b5cc1000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-26 14:59:52.297  6441  6441 W art     : b5cc1000-b5cc2000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-26 14:59:52.297  6441  6441 W art     : b5cc2000-b5cc3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-26 14:59:52.297  6441  6441 W art     : b5cc3000-b5cc7000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-26 14:59:52.297  6441  6441 W art     : b5cc7000-b5cc8000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-26 14:59:52.297  6441  6441 W art     : b5cc8000-b5cc9000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-26 14:59:52.297  6441  6441 W art     : b5cc9000-b5cca000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b5cca000-b5cd8000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-26 14:59:52.297  6441  6441 W art     : b5cd8000-b5cd9000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b5cd9000-b5cda000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-26 14:59:52.297  6441  6441 W art     : b5cda000-b5cdb000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-26 14:59:52.297  6441  6441 W art     : b5cdb000-b5ce5000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-26 14:59:52.297  6441  6441 W art     : b5ce5000-b5ce8000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-26 14:59:52.297  6441  6441 W art     : b5ce8000-b5ce9000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-26 14:59:52.297  6441  6441 W art     : b5ce9000-b5cea000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b5cea000-b5cf4000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-26 14:59:52.297  6441  6441 W art     : b5cf4000-b5cf7000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-26 14:59:52.297  6441  6441 W art     : b5cf7000-b5cf8000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-26 14:59:52.297  6441  6441 W art     : b5cf8000-b5cfc000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-26 14:59:52.297  6441  6441 W art     : b5cfc000-b5cfd000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-26 14:59:52.297  6441  6441 W art     : b5cfd000-b5cfe000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-26 14:59:52.297  6441  6441 W art     : b5cfe000-b5cff000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b5cff000-b5d0c000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-26 14:59:52.297  6441  6441 W art     : b5d0c000-b5d0e000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-26 14:59:52.297  6441  6441 W art     : b5d0e000-b5d0f000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-26 14:59:52.297  6441  6441 W art     : b5d0f000-b6121000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-26 14:59:52.297  6441  6441 W art     : b6121000-b6122000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b6122000-b612b000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-26 14:59:52.297  6441  6441 W art     : b612b000-b612f000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-26 14:59:52.297  6441  6441 W art     : b612f000-b6130000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b6130000-b6137000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-26 14:59:52.297  6441  6441 W art     : b6137000-b6138000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-26 14:59:52.297  6441  6441 W art     : b6138000-b6139000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-26 14:59:52.297  6441  6441 W art     : b6139000-b613a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b613a000-b6155000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-26 14:59:52.297  6441  6441 W art     : b6155000-b6156000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-26 14:59:52.297  6441  6441 W art     : b6156000-b6157000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-26 14:59:52.297  6441  6441 W art     : b6157000-b6158000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b6158000-b61a4000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-26 14:59:52.297  6441  6441 W art     : b61a4000-b61a5000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b61a5000-b61a6000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-26 14:59:52.297  6441  6441 W art     : b61a6000-b61a7000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-26 14:59:52.297  6441  6441 W art     : b61a7000-b61a8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b61a8000-b61ac000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-26 14:59:52.297  6441  6441 W art     : b61ac000-b61ad000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b61ad000-b61ae000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-26 14:59:52.297  6441  6441 W art     : b61ae000-b61af000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-26 14:59:52.297  6441  6441 W art     : b61af000-b61e7000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-26 14:59:52.297  6441  6441 W art     : b61e7000-b61e8000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-26 14:59:52.297  6441  6441 W art     : b61e8000-b61e9000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-26 14:59:52.297  6441  6441 W art     : b61e9000-b61ea000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.297  6441  6441 W art     : b61ea000-b6288000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-26 14:59:52.297  6441  6441 W art     : b6288000-b6289000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b6289000-b62a7000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-26 14:59:52.297  6441  6441 W art     : b62a7000-b62a8000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-26 14:59:52.297  6441  6441 W art     : b62a8000-b641b000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-26 14:59:52.297  6441  6441 W art     : b641b000-b6426000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-26 14:59:52.297  6441  6441 W art     : b6426000-b6427000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-26 14:59:52.297  6441  6441 W art     : b6427000-b653e000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-26 14:59:52.297  6441  6441 W art     : b653e000-b6549000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-26 14:59:52.297  6441  6441 W art     : b6549000-b654a000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-26 14:59:52.297  6441  6441 W art     : b654a000-b654e000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b654e000-b6572000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-26 14:59:52.297  6441  6441 W art     : b6572000-b6574000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-26 14:59:52.297  6441  6441 W art     : b6574000-b6575000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-26 14:59:52.297  6441  6441 W art     : b6575000-b661b000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-26 14:59:52.297  6441  6441 W art     : b661b000-b6628000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-26 14:59:52.297  6441  6441 W art     : b6628000-b6629000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-26 14:59:52.297  6441  6441 W art     : b6629000-b662a000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b662a000-b667d000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-26 14:59:52.297  6441  6441 W art     : b667d000-b667e000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b667e000-b667f000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-26 14:59:52.297  6441  6441 W art     : b667f000-b6680000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-26 14:59:52.297  6441  6441 W art     : b6680000-b6685000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b6685000-b6697000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-26 14:59:52.297  6441  6441 W art     : b6697000-b6698000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b6698000-b6699000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-26 14:59:52.297  6441  6441 W art     : b6699000-b669a000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-26 14:59:52.297  6441  6441 W art     : b669a000-b66a1000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-26 14:59:52.297  6441  6441 W art     : b66a1000-b66a2000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-26 14:59:52.297  6441  6441 W art     : b66a2000-b66a3000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-26 14:59:52.297  6441  6441 W art     : b66a3000-b66a4000 rw-p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b66a4000-b66a7000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-26 14:59:52.297  6441  6441 W art     : b66a7000-b66a8000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-26 14:59:52.297  6441  6441 W art     : b66a8000-b66a9000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-26 14:59:52.297  6441  6441 W art     : b66a9000-b66ad000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-26 14:59:52.297  6441  6441 W art     : b66ad000-b66ae000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-26 14:59:52.297  6441  6441 W art     : b66ae000-b66af000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-26 14:59:52.297  6441  6441 W art     : b66af000-b66bd000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-26 14:59:52.297  6441  6441 W art     : b66bd000-b66be000 ---p 00000000 00:00 0 
08-26 14:59:52.297  6441  6441 W art     : b66be000-b66bf000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-26 14:59:52.297  6441  6441 W art     : b66bf000-b66c0000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-26 14:59:52.297  6441  6441 W art     : b66c0000-b66c9000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-26 14:59:52.297  6441  6441 W art     : b66c9000-b66ca000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-26 14:59:52.297  6441  6441 W art     : b66ca000-b66cb000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-26 14:59:52.307  6441  6441 W art     : b66cb000-b6731000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-26 14:59:52.307  6441  6441 W art     : b6731000-b6732000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6732000-b6734000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-26 14:59:52.307  6441  6441 W art     : b6734000-b673d000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-26 14:59:52.307  6441  6441 W art     : b673d000-b6740000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6740000-b67d7000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-26 14:59:52.307  6441  6441 W art     : b67d7000-b67d9000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-26 14:59:52.307  6441  6441 W art     : b67d9000-b67da000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-26 14:59:52.307  6441  6441 W art     : b67da000-b67db000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b67db000-b6afc000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-26 14:59:52.307  6441  6441 W art     : b6afc000-b6afd000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6afd000-b6b18000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-26 14:59:52.307  6441  6441 W art     : b6b18000-b6b1c000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-26 14:59:52.307  6441  6441 W art     : b6b1c000-b6b21000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6b21000-b6b29000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-26 14:59:52.307  6441  6441 W art     : b6b29000-b6b2a000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-26 14:59:52.307  6441  6441 W art     : b6b2a000-b6b2b000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-26 14:59:52.307  6441  6441 W art     : b6b2b000-b6b59000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-26 14:59:52.307  6441  6441 W art     : b6b59000-b6b5a000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6b5a000-b6b61000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-26 14:59:52.307  6441  6441 W art     : b6b61000-b6b62000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-26 14:59:52.307  6441  6441 W art     : b6b62000-b6ba8000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-26 14:59:52.307  6441  6441 W art     : b6ba8000-b6ba9000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6ba9000-b6bac000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-26 14:59:52.307  6441  6441 W art     : b6bac000-b6bad000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-26 14:59:52.307  6441  6441 W art     : b6bad000-b6bc8000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-26 14:59:52.307  6441  6441 W art     : b6bc8000-b6bcc000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-26 14:59:52.307  6441  6441 W art     : b6bcc000-b6bcd000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-26 14:59:52.307  6441  6441 W art     : b6bcd000-b6c1a000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-26 14:59:52.307  6441  6441 W art     : b6c1a000-b6c1b000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6c1b000-b6c27000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-26 14:59:52.307  6441  6441 W art     : b6c27000-b6c28000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-26 14:59:52.307  6441  6441 W art     : b6c28000-b6c35000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-26 14:59:52.307  6441  6441 W art     : b6c35000-b6c36000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6c36000-b6c37000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-26 14:59:52.307  6441  6441 W art     : b6c37000-b6c38000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-26 14:59:52.307  6441  6441 W art     : b6c38000-b6c40000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-26 14:59:52.307  6441  6441 W art     : b6c40000-b6c41000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6c41000-b6c42000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-26 14:59:52.307  6441  6441 W art     : b6c42000-b6c43000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-26 14:59:52.307  6441  6441 W art     : b6c43000-b6c4a000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-26 14:59:52.307  6441  6441 W art     : b6c4a000-b6c4b000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-26 14:59:52.307  6441  6441 W art     : b6c4b000-b6c4c000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-26 14:59:52.307  6441  6441 W art     : b6c4c000-b6c60000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-26 14:59:52.307  6441  6441 W art     : b6c60000-b6c62000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-26 14:59:52.307  6441  6441 W art     : b6c62000-b6c63000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-26 14:59:52.307  6441  6441 W art     : b6c63000-b6c8b000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-26 14:59:52.307  6441  6441 W art     : b6c8b000-b6c8d000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-26 14:59:52.307  6441  6441 W art     : b6c8d000-b6c8e000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-26 14:59:52.307  6441  6441 W art     : b6c8e000-b6c91000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-26 14:59:52.307  6441  6441 W art     : b6c91000-b6c92000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-26 14:59:52.307  6441  6441 W art     : b6c92000-b6c93000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-26 14:59:52.307  6441  6441 W art     : b6c93000-b6c9c000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-26 14:59:52.307  6441  6441 W art     : b6c9c000-b6c9d000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-26 14:59:52.307  6441  6441 W art     : b6c9d000-b6c9e000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-26 14:59:52.307  6441  6441 W art     : b6c9e000-b6cbe000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-26 14:59:52.307  6441  6441 W art     : b6cbe000-b6cbf000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-26 14:59:52.307  6441  6441 W art     : b6cbf000-b6cc0000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-26 14:59:52.307  6441  6441 W art     : b6cc0000-b6d33000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-26 14:59:52.307  6441  6441 W art     : b6d33000-b6d37000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-26 14:59:52.307  6441  6441 W art     : b6d37000-b6d3a000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-26 14:59:52.307  6441  6441 W art     : b6d3a000-b6d44000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6d44000-b6dcc000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-26 14:59:52.307  6441  6441 W art     : b6dcc000-b6dcd000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6dcd000-b6dd1000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-26 14:59:52.307  6441  6441 W art     : b6dd1000-b6dd2000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-26 14:59:52.307  6441  6441 W art     : b6dd2000-b6dd3000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6dd3000-b6dfc000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-26 14:59:52.307  6441  6441 W art     : b6dfc000-b6dfd000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6dfd000-b6e00000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-26 14:59:52.307  6441  6441 W art     : b6e00000-b6e01000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-26 14:59:52.307  6441  6441 W art     : b6e01000-b6edb000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-26 14:59:52.307  6441  6441 W art     : b6edb000-b6ee2000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-26 14:59:52.307  6441  6441 W art     : b6ee2000-b6eea000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-26 14:59:52.307  6441  6441 W art     : b6eea000-b6eeb000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6eeb000-b6eec000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-26 14:59:52.307  6441  6441 W art     : b6eec000-b6eed000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-26 14:59:52.307  6441  6441 W art     : b6eed000-b6eee000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.307  6441  6441 W art     : b6eee000-b6ef1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.307  6441  6441 W art     : b6ef1000-b6f16000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-26 14:59:52.307  6441  6441 W art     : b6f16000-b6f17000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6f17000-b6f1e000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-26 14:59:52.307  6441  6441 W art     : b6f1e000-b6f1f000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-26 14:59:52.307  6441  6441 W art     : b6f1f000-b6f26000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-26 14:59:52.307  6441  6441 W art     : b6f26000-b6f27000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-26 14:59:52.307  6441  6441 W art     : b6f27000-b6f28000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-26 14:59:52.307  6441  6441 W art     : b6f28000-b6f29000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.307  6441  6441 W art     : b6f29000-b6f41000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-26 14:59:52.307  6441  6441 W art     : b6f41000-b6f42000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6f42000-b6f43000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-26 14:59:52.307  6441  6441 W art     : b6f43000-b6f44000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-26 14:59:52.307  6441  6441 W art     : b6f44000-b6f52000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-26 14:59:52.307  6441  6441 W art     : b6f52000-b6f53000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6f53000-b6f54000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-26 14:59:52.307  6441  6441 W art     : b6f54000-b6f55000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-26 14:59:52.307  6441  6441 W art     : b6f55000-b6f56000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-26 14:59:52.307  6441  6441 W art     : b6f56000-b6f58000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.307  6441  6441 W art     : b6f58000-b6f59000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.307  6441  6441 W art     : b6f59000-b6f5a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-26 14:59:52.307  6441  6441 W art     : b6f5a000-b6f5b000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-26 14:59:52.307  6441  6441 W art     : b6f5b000-b6f5c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-26 14:59:52.307  6441  6441 W art     : b6f5c000-b6f7c000 r--s 00000000 00:0b 9219       /dev/__properties__
08-26 14:59:52.307  6441  6441 W art     : b6f7c000-b6f7d000 r--p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6f7d000-b6f7e000 ---p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6f7e000-b6f80000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-26 14:59:52.307  6441  6441 W art     : b6f80000-b6f81000 r-xp 00000000 00:00 0          [sigpage]
08-26 14:59:52.307  6441  6441 W art     : b6f81000-b6f9c000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-26 14:59:52.307  6441  6441 W art     : b6f9c000-b6f9d000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-26 14:59:52.307  6441  6441 W art     : b6f9d000-b6f9f000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-26 14:59:52.307  6441  6441 W art     : b6f9f000-b6fa1000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : b6fa1000-b6fa6000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-26 14:59:52.307  6441  6441 W art     : b6fa6000-b6fa7000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-26 14:59:52.307  6441  6441 W art     : b6fa7000-b6fa8000 rw-p 00000000 00:00 0 
08-26 14:59:52.307  6441  6441 W art     : bedb1000-bedd2000 rw-p 00000000 00:00 0          [stack]
08-26 14:59:52.307  6441  6441 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-26 14:59:52.377  6441  6441 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 14:59:52.437  6441  6441 I Radio-JNI: register_android_hardware_Radio DONE
08-26 14:59:52.447  6441  6441 E AffinityControl: AffinityControl: registerfunction enter
08-26 14:59:52.477  6441  6441 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 14:59:52.487   781  1717 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-26 14:59:52.507   781  1717 D ActivityManager: mDVFSHelper.acquire()
08-26 14:59:52.507   781  1717 D FocusedStackFrame: Set to : 0
08-26 14:59:52.507   781  1717 V WindowManager: addAppToken: AppWindowToken{4ad5424 token=Token{71ae4b7 ActivityRecord{446dfb6 u0 com.test.thalitest/.MainActivity t167}}} to stack=1 task=167 at 0
08-26 14:59:52.517   781   902 D SecWifiDisplayUtil: Metadata value : none
08-26 14:59:52.517   781   902 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{2d503bc V.E...... R.....ID 0,0-0,0}
08-26 14:59:52.517   781   902 D ISSUE_DEBUG: InputChannelName : 671b69a Starting com.test.thalitest
08-26 14:59:52.527  6453  6453 E Zygote  : v2
08-26 14:59:52.527  6453  6453 I libpersona: KNOX_SDCARD checking this for 10004
08-26 14:59:52.527  6453  6453 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:52.527  6453  6453 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:52.527  6453  6453 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:52.527  6453  6453 E Zygote  : accessInfo : 0
08-26 14:59:52.537  6453  6453 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-26 14:59:52.537   293   293 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
08-26 14:59:52.537   781  1717 I ActivityManager: Start proc 6453:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-26 14:59:52.547   781  1717 D InputDispatcher: Focused application set to: xxxx
08-26 14:59:52.547   781   902 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-26 14:59:52.547   781  1717 D InputDispatcher: Focus left window: 1735
08-26 14:59:52.547  6441  6441 D AndroidRuntime: Shutting down VM
08-26 14:59:52.557   781  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-26 14:59:52.577   781   902 V WindowStateAnimator: Finishing drawing window Window{671b69a u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-26 14:59:52.587   781   902 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-26 14:59:52.587   781   902 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:52.587   781   902 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-26 14:59:52.587   781   902 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-26 14:59:52.587   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe9da364
08-26 14:59:52.587  6453  6453 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:52.587  6453  6453 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:52.597   781  1731 V WindowOrientationListener: setCurrentAppOrientation :-1
08-26 14:59:52.597   781  1731 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-26 14:59:52.597   781   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{671b69a u0 d0 Starting com.test.thalitest}
08-26 14:59:52.607  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-26 14:59:52.607  1735  1884 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-26 14:59:52.617  1735  1735 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-26 14:59:52.617   781  1731 D ActivityManager:  Launching com.test.thalitest, updated priority
08-26 14:59:52.637   293   370 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-26 14:59:52.637   293   370 D libEGL  : eglTerminate EGLDisplay = 0xb69c164c
08-26 14:59:52.647   293  1295 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-26 14:59:52.647   293   370 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-26 14:59:52.647  2284  2295 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-26 14:59:52.647  1735  1735 V ActivityThread: updateVisibility : ActivityRecord{dce2b40 token=android.os.BinderProxy@31b7122 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 14:59:52.647  1735  1735 D Launcher: onTrimMemory. Level: 20
08-26 14:59:52.657   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9da3a4
08-26 14:59:52.667   781   854 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-26 14:59:52.677   781  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-26 14:59:52.677  6453  6453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-26 14:59:52.687   781  3423 D M       : limitCPUFreq:: freq = -1
08-26 14:59:52.687   781  3423 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 781  tag : SIOP_ARM_MAX@25
08-26 14:59:52.687   781  3423 D M       : limitGPUFreq:: freq = -1
08-26 14:59:52.697   781  3423 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-26 14:59:52.717  6453  6453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-26 14:59:52.727  6453  6453 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-26 14:59:52.737  6453  6453 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
08-26 14:59:52.767  6453  6453 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-26 14:59:52.767  6453  6453 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 14:59:52.777  6453  6453 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 6213-6217)
,08-26 14:59:52.777  6453  6453 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-26 14:59:52.807  6453  6453 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e2094}
,08-26 14:59:52.807  6453  6453 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
08-26 14:59:52.807  6453  6453 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:59:52.817   781   791 I art     : Background partial concurrent mark sweep GC freed 146530(8MB) AllocSpace objects, 10(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.929ms total 160.604ms
,08-26 14:59:52.817  6453  6472 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-26 14:59:52.817  6453  6453 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 14:59:52.857  6453  6453 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-26 14:59:52.857  6453  6453 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-26 14:59:52.857  6453  6453 I Adreno-EGL: Build Date: 01/28/16 Thu
08-26 14:59:52.857  6453  6453 I Adreno-EGL: Local Branch: ss
08-26 14:59:52.857  6453  6453 I Adreno-EGL: Remote Branch: 
08-26 14:59:52.857  6453  6453 I Adreno-EGL: Local Patches: 
08-26 14:59:52.857  6453  6453 I Adreno-EGL: Reconstruct Branch: 
,08-26 14:59:52.857  6453  6453 D libEGL  : eglInitialize EGLDisplay = 0xbeefddac
,08-26 14:59:52.887   781  1747 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-26 14:59:52.887   781  1747 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-26 14:59:52.937  6453  6453 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-26 14:59:52.947  6453  6453 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 14:59:52.947  6453  6453 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-26 14:59:52.947  6453  6453 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-26 14:59:52.957  6453  6453 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-26 14:59:52.967  6453  6453 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-26 14:59:52.987  6453  6453 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 14:59:53.037  5472  5472 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-26 14:59:53.037  5472  5472 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-26 14:59:53.037  5472  5472 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
,08-26 14:59:53.037  5472  5472 I art     : System.exit called, status: 0
,08-26 14:59:53.037  5472  5472 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:59:53.067  6453  6453 D SecWifiDisplayUtil: Metadata value : none
,08-26 14:59:53.077  6453  6453 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{70d7a92 I.E...... R.....ID 0,0-0,0}
,08-26 14:59:53.077  6453  6500 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 14:59:53.077  5429  5429 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
,08-26 14:59:53.087   781   795 I ActivityManager: Process com.samsung.aasaservice (pid 5472)(adj 0) has died(106,754)
,08-26 14:59:53.087   781   795 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-26 14:59:53.087   781   795 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
,08-26 14:59:53.087   781   795 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,08-26 14:59:53.087   781  1319 D ISSUE_DEBUG: InputChannelName : 595101c com.test.thalitest/com.test.thalitest.MainActivity
,08-26 14:59:53.107  6501  6501 E Zygote  : v2
,08-26 14:59:53.107   781   854 I ActivityManager: Start proc 6501:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-26 14:59:53.107   781  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-26 14:59:53.107   781  1747 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-26 14:59:53.107   781  1747 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-26 14:59:53.107   781   781 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-26 14:59:53.107  6501  6501 I libpersona: KNOX_SDCARD checking this for 10014
08-26 14:59:53.107  6501  6501 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:53.107   781   781 I KnoxTimeoutHandler: Shared devices show user statefalse
08-26 14:59:53.107  6501  6501 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:53.107  6501  6501 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:53.107  6501  6501 E Zygote  : accessInfo : 0
,08-26 14:59:53.107  6501  6501 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
,08-26 14:59:53.117   781  1322 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 14:59:53.127  6453  6453 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6453
,08-26 14:59:53.137  6501  6501 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:53.137  6501  6501 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:53.137   781  1625 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6453 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 14:59:53.137   781  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-26 14:59:53.137   781  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 14:59:53.137   781  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-26 14:59:53.137   781  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,08-26 14:59:53.137   781  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 14:59:53.147   781  2274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{89bc787 6501:com.google.android.partnersetup/u0a14}
,08-26 14:59:53.147  6501  6501 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
,08-26 14:59:53.157  6453  6472 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-26 14:59:53.157  6453  6453 D SecWifiDisplayUtil: Metadata value : none
,08-26 14:59:53.157  6501  6501 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-26 14:59:53.167   293   293 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
,08-26 14:59:53.177   781  1727 D InputDispatcher: Focus entered window: 6453
,08-26 14:59:53.177   781   902 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-26 14:59:53.177   781   902 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:53.177   781   902 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-26 14:59:53.177   781   902 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-26 14:59:53.177  6453  6500 D libEGL  : eglInitialize EGLDisplay = 0x9c97f7c4
08-26 14:59:53.177  6453  6500 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 14:59:53.187   781  1810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{89bc787 6501:com.google.android.partnersetup/u0a14}
,08-26 14:59:53.207   781  1747 I ActivityManager: Start proc 6520:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-26 14:59:53.207  6520  6520 E Zygote  : v2
08-26 14:59:53.207  6520  6520 I libpersona: KNOX_SDCARD checking this for 10015
08-26 14:59:53.207  6520  6520 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:53.207  6520  6520 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:53.207  6520  6520 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:53.207  6520  6520 E Zygote  : accessInfo : 0
,08-26 14:59:53.207  6520  6520 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
,08-26 14:59:53.217   781  1489 I ActivityManager: Killing 4009:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,08-26 14:59:53.227  6453  6453 V ActivityThread: updateVisibility : ActivityRecord{6e81dd5 token=android.os.BinderProxy@3cf081d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 14:59:53.227  6453  6453 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-26 14:59:53.227  6453  6453 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-26 14:59:53.227   781  1717 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:59:53.247  6453  6453 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-26 14:59:53.247   781  1412 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-26 14:59:53.257  6520  6520 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:53.257  6520  6520 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:53.267   781  1625 V WindowStateAnimator: Finishing drawing window Window{595101c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-26 14:59:53.267  6453  6453 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
08-26 14:59:53.267  6453  6453 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3cf081d time:106703
,08-26 14:59:53.267   781  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fe35523 6520:com.samsung.groupcast/u0a15}
08-26 14:59:53.267   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe9da364
08-26 14:59:53.277   781   902 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-26 14:59:53.277   781   902 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +603ms (total +761ms)
08-26 14:59:53.277   781   781 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
08-26 14:59:53.277   781   902 D ActivityManager: mDVFSHelper.release()
08-26 14:59:53.277   781   781 I KnoxTimeoutHandler: SD activityfalse
08-26 14:59:53.277   781   902 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{446dfb6 u0 com.test.thalitest/.MainActivity t167} time:106713
08-26 14:59:53.277   781   902 D ViewRootImpl: #3 mView = null
08-26 14:59:53.277   293   370 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
08-26 14:59:53.277  6520  6520 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-26 14:59:53.277   293   378 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
,08-26 14:59:53.287   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9da3a4
,08-26 14:59:53.307  6520  6520 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
,08-26 14:59:53.317  6453  6535 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:59:53.317  6453  6535 D libEGL  : eglInitialize EGLDisplay = 0x9aeed3ec
,08-26 14:59:53.327  6520  6520 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
,08-26 14:59:53.327  6520  6520 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,08-26 14:59:53.327  6520  6520 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-26 14:59:53.327  6520  6520 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-26 14:59:53.327  6520  6520 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-26 14:59:53.327  6520  6520 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-26 14:59:53.327  6520  6520 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:59:53.327  6520  6520 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-26 14:59:53.327  6520  6520 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-26 14:59:53.337   781  2274 I ActivityManager: Killing 5664:com.sec.android.app.camera/u0a153 (adj 15): DHA:empty #37
,08-26 14:59:53.337   781  2274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1e0150 1888:com.sec.android.app.shealth:remote/u0a34}
,08-26 14:59:53.357   781  1642 I ActivityManager: Start proc 6538:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
08-26 14:59:53.357  6538  6538 E Zygote  : v2
08-26 14:59:53.357  6538  6538 I libpersona: KNOX_SDCARD checking this for 10041
08-26 14:59:53.357  6538  6538 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:53.357  6538  6538 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:53.357  6538  6538 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:53.357  6453  6453 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6453
,08-26 14:59:53.357  6538  6538 E Zygote  : accessInfo : 0
,08-26 14:59:53.357  6538  6538 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-26 14:59:53.357   781  1717 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.camera, Auto Run ON
,08-26 14:59:53.377  6538  6538 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:53.377  6538  6538 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:53.387   781   794 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3ce1a20 6538:com.samsung.android.sdk.samsunglink/u0a41}
,08-26 14:59:53.397  6538  6538 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
,08-26 14:59:53.447  6453  6453 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:59:53.477  6538  6538 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-26 14:59:53.477  6538  6538 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-26 14:59:53.527  6538  6538 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-26 14:59:53.527  6538  6538 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-26 14:59:53.537   781  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.537   781  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-26 14:59:53.547   781  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.547   781   794 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.547   781  1810 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.557   781  1791 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.557   781  1319 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.557   781  1489 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.557   781  2274 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.557   781  2302 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-26 14:59:53.627  6453  6555 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1720846032
,08-26 14:59:53.627  6453  6555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:59:53.627  6453  6555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:59:53.627  6453  6555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:59:53.627  6453  6555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:59:53.627  6453  6555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 14:59:53.627  6453  6555 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c52a453 added. We now have 1 listener(s)
,08-26 14:59:53.627  6453  6555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-26 14:59:53.627  6453  6555 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-26 14:59:53.637  6453  6555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:59:53.637  6453  6555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 14:59:53.637  6453  6555 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa64a8e added. We now have 1 listener(s)
08-26 14:59:53.637  6453  6555 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:59:53.637  6453  6555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-26 14:59:53.647  6453  6555 D BluetoothAdapter: STATE_ON
,08-26 14:59:53.647  6453  6555 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:59:53.647  6453  6555 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:59:53.647  6453  6555 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-26 14:59:53.647  6453  6555 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:59:53.647  6453  6555 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:59:53.647  6453  6453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:53.657  6453  6453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:53.677   781  3427 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-26 14:59:53.677  6453  6453 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:59:53.677  6538  6538 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-26 14:59:53.677  6538  6538 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-26 14:59:53.677  6538  6538 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-26 14:59:53.677  6538  6538 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-26 14:59:53.677  6538  6538 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-26 14:59:53.677  6538  6538 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-26 14:59:53.677  6538  6538 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-26 14:59:53.677  6538  6538 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:59:53.677  6538  6538 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-26 14:59:53.677  6538  6538 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-26 14:59:53.687   781  1791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{6fc67fa 1651:android.process.acore/u0a19}
,08-26 14:59:53.697   781   795 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{126bac8 5120:com.sec.android.gallery3d/u0a47}
,08-26 14:59:53.697  5120  5120 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-26 14:59:53.697   781  1717 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-26 14:59:53.717   781  1747 I ActivityManager: Start proc 6565:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
,08-26 14:59:53.717  6565  6565 E Zygote  : v2
08-26 14:59:53.717  6565  6565 I libpersona: KNOX_SDCARD checking this for 10050
08-26 14:59:53.717  6565  6565 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:53.717  6565  6565 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:53.717  6565  6565 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:53.717  6565  6565 E Zygote  : accessInfo : 0
,08-26 14:59:53.717  6565  6565 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-26 14:59:53.757  6565  6565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:53.757  6565  6565 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:53.767   781  1810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8c8d5a 6565:com.sec.android.app.myfiles/u0a50}
,08-26 14:59:53.777  6565  6565 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-26 14:59:53.797  6565  6565 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-26 14:59:53.847  6565  6565 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-26 14:59:53.867   781  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba50bcf 2802:com.android.settings/1000}
,08-26 14:59:53.867   321   321 E installd: system dir 0 : /system/app/
08-26 14:59:53.867   321   321 E installd: system dir 1 : /system/priv-app/
08-26 14:59:53.867   321   321 E installd: system dir 2 : /vendor/app/
08-26 14:59:53.867   321   321 E installd: system dir 3 : /oem/app/
,08-26 14:59:53.877   781   924 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-26 14:59:53.887   781  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ba50bcf 2802:com.android.settings/1000}
,08-26 14:59:53.897  6580  6580 E Zygote  : v2
08-26 14:59:53.897  6580  6580 I libpersona: KNOX_SDCARD checking this for 10169
08-26 14:59:53.897  6580  6580 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:53.897   781   794 I ActivityManager: Start proc 6580:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
08-26 14:59:53.897  6580  6580 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:53.897  6580  6580 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:53.907  6580  6580 E Zygote  : accessInfo : 0
08-26 14:59:53.907  6580  6580 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-26 14:59:53.937  6580  6580 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:53.937  6580  6580 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:53.947   781  2274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4f62526 6580:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-26 14:59:53.947  6580  6580 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-26 14:59:53.957  6580  6580 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-26 14:59:53.967  3494  3494 D FactoryTest: User mode
,08-26 14:59:53.977  3494  3494 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-26 14:59:53.977  3494  3494 D MTPRx   : still no open session command from host, so toast
,08-26 14:59:53.977   781  1747 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-26 14:59:53.977   781  1747 D ActivityManager: mDVFSHelper.acquire()
,08-26 14:59:53.987   781  1747 V WindowManager: addAppToken: AppWindowToken{fe253bd token=Token{d362f14 ActivityRecord{d839567 u0 com.samsung.android.MtpApplication/.USBConnection t168}}} to stack=1 task=168 at 0
,08-26 14:59:53.987   781  1747 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-26 14:59:53.987   781   854 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-26 14:59:53.997   781  1747 D InputDispatcher: Focused application set to: xxxx
,08-26 14:59:53.997   781  1747 D InputDispatcher: Focus left window: 6453
,08-26 14:59:54.007   781   902 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
,08-26 14:59:54.007   781   902 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:54.007   781   902 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-26 14:59:54.007   781   902 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-26 14:59:54.007  3494  3494 E MTPRx   : started activity for popup
,08-26 14:59:54.007  3494  3494 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-26 14:59:54.007  3494  3494 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-26 14:59:54.017   781  1489 I ActivityManager: Killing 5267:com.android.mms/u0a49 (adj 15): DHA:empty #37
,08-26 14:59:54.017   781  1489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bc17ff2 1718:com.android.phone/1001}
,08-26 14:59:54.027  3494  3494 D MTPUSBConnection: onCreate in USBConnection
,08-26 14:59:54.027  3494  3494 V MTPUSBConnection: Registering broadcast receiver.
,08-26 14:59:54.037   781  1489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a7539b 1829:com.google.android.googlequicksearchbox:search/u0a61}
,08-26 14:59:54.037   781  2302 D CountryDetector: No listener is left
,08-26 14:59:54.047  3494  3494 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-26 14:59:54.047   781  1319 D ActivityManager: isAutoRunBlockedApp:: com.android.mms, Auto Run ON
,08-26 14:59:54.047   781   795 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-26 14:59:54.057   781  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7a7539b 1829:com.google.android.googlequicksearchbox:search/u0a61}
,08-26 14:59:54.077   781  1791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23ca5f 6386:com.samsung.android.sm.provider/1000}
,08-26 14:59:54.097   781   854 I ActivityManager: Start proc 6593:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
,08-26 14:59:54.097  6593  6593 E Zygote  : v2
08-26 14:59:54.097  6593  6593 I libpersona: KNOX_SDCARD checking this for 10210
08-26 14:59:54.097  6593  6593 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:54.097  6593  6593 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 14:59:54.097  6593  6593 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:54.097  3494  3494 D TAG     : dev.kiessupport is : TRUE
,08-26 14:59:54.097  6593  6593 E Zygote  : accessInfo : 0
,08-26 14:59:54.097  6593  6593 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-26 14:59:54.107  1448  1448 D Recents : onTaskStackChanged
,08-26 14:59:54.117  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-26 14:59:54.127  3494  3494 D SecWifiDisplayUtil: Metadata value : none
,08-26 14:59:54.127  3494  3494 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{9d8b44d V.E...... R.....I. 0,0-0,0}
,08-26 14:59:54.137  3494  6606 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 14:59:54.147   781  1319 D ISSUE_DEBUG: InputChannelName : 764ad7b com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-26 14:59:54.147  6608  6608 E Zygote  : v2
08-26 14:59:54.147  6608  6608 I libpersona: KNOX_SDCARD checking this for 5012
08-26 14:59:54.147  6608  6608 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:54.147  6608  6608 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:54.147  6608  6608 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:54.147   781  2274 I ActivityManager: Start proc 6608:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-26 14:59:54.147   781  1319 D InputDispatcher: Focus entered window: 3494
,08-26 14:59:54.147   781   902 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-26 14:59:54.147   781   902 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:54.147   781   902 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-26 14:59:54.147   781   902 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-26 14:59:54.147  6608  6608 E Zygote  : accessInfo : 0
,08-26 14:59:54.147  6608  6608 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-26 14:59:54.147  6593  6593 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:54.147  6593  6593 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:54.157   781   858 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{764ad7b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-26 14:59:54.157  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-26 14:59:54.157  1448  1448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-26 14:59:54.157  3494  3494 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{952005 I.E...... R.....I. 0,0-0,0}
,08-26 14:59:54.167   781  1731 D ISSUE_DEBUG: InputChannelName : a593bf1 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-26 14:59:54.177   781  1319 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
,08-26 14:59:54.177   781  1319 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-26 14:59:54.177   781   781 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-26 14:59:54.177   781   781 I KnoxTimeoutHandler: Shared devices show user statefalse
08-26 14:59:54.177   781   781 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-26 14:59:54.187  1829  6592 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-26 14:59:54.197  6608  6608 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:54.197  6608  6608 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:54.207   293   293 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,08-26 14:59:54.207   781  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5a823d6 6608:com.samsung.android.sm.devicesecurity/5012}
,08-26 14:59:54.217  6593  6593 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-26 14:59:54.227  3494  6606 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-26 14:59:54.227  3494  6606 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-26 14:59:54.227  3494  6606 I Adreno-EGL: Build Date: 01/28/16 Thu
08-26 14:59:54.227  3494  6606 I Adreno-EGL: Local Branch: ss
08-26 14:59:54.227  3494  6606 I Adreno-EGL: Remote Branch: 
08-26 14:59:54.227  3494  6606 I Adreno-EGL: Local Patches: 
08-26 14:59:54.227  3494  6606 I Adreno-EGL: Reconstruct Branch: 
,08-26 14:59:54.227  3494  6606 D libEGL  : eglInitialize EGLDisplay = 0x9ef487c4
,08-26 14:59:54.227  3494  6606 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 14:59:54.227  6593  6593 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-26 14:59:54.237  6593  6593 D AASAservice: onCreate()
,08-26 14:59:54.237   781  1412 I ActivityManager: Killing 5678:com.sec.android.GeoLookout/u0a112 (adj 15): DHA:empty #37
,08-26 14:59:54.247  5429  5429 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,08-26 14:59:54.257   781  1489 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.GeoLookout, Auto Run ON
08-26 14:59:54.257  6608  6608 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
08-26 14:59:54.287   293   293 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
08-26 14:59:54.297  6608  6608 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
08-26 14:59:54.317  3494  3494 V ActivityThread: updateVisibility : ActivityRecord{6687768 token=android.os.BinderProxy@8c26b02 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
08-26 14:59:54.317  3494  3494 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-26 14:59:54.417   781  1489 I ActivityManager: Killing 5197:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
08-26 14:59:54.427   781  1489 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d16a2c1 3196:com.android.contacts/u0a19}
08-26 14:59:54.447   781   794 I ActivityManager: Start proc 6625:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
08-26 14:59:54.447  6625  6625 E Zygote  : v2
08-26 14:59:54.447  6625  6625 I libpersona: KNOX_SDCARD checking this for 10049
08-26 14:59:54.447  6625  6625 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:54.447  6625  6625 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:54.447  6625  6625 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:54.447  6625  6625 E Zygote  : accessInfo : 0
08-26 14:59:54.447  6625  6625 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
08-26 14:59:54.447   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe9da364
08-26 14:59:54.447   781  1791 V WindowStateAnimator: Finishing drawing window Window{764ad7b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-26 14:59:54.457  3494  3494 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
08-26 14:59:54.457   781  1319 V WindowStateAnimator: Finishing drawing window Window{a593bf1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
08-26 14:59:54.457  3494  3494 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-26 14:59:54.457  3494  3494 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-26 14:59:54.457  1829  6592 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-26 14:59:54.467   781   902 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-26 14:59:54.467   781   781 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-26 14:59:54.467   781   781 I KnoxTimeoutHandler: SD activityfalse
08-26 14:59:54.467   781   902 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +470ms (total +484ms)
08-26 14:59:54.467   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe9da364
08-26 14:59:54.467  1829  6592 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
08-26 14:59:54.467   781  2302 V WindowStateAnimator: Finishing drawing window Window{764ad7b u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-26 14:59:54.467   781  1412 V WindowStateAnimator: Finishing drawing window Window{a593bf1 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
08-26 14:59:54.467  3494  3494 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8c26b02 time:107909
08-26 14:59:54.477   781   902 D ActivityManager: mDVFSHelper.release()
08-26 14:59:54.477   781   902 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d839567 u0 com.samsung.android.MtpApplication/.USBConnection t168} time:107910
08-26 14:59:54.487   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe9da364
08-26 14:59:54.497   781  1731 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
08-26 14:59:54.507  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:54.507  6625  6625 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:54.517   781  1791 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{106a657 6625:com.android.mms/u0a49}
08-26 14:59:54.527  6625  6625 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-26 14:59:54.537   781  1717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.icing.proxy.SmsMonitor newState = 1 callingPackage = 10011
08-26 14:59:54.587  6625  6625 W System  : ClassLoader referenced unknown path: imsmanager.jar
08-26 14:59:54.617  6625  6625 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
08-26 14:59:54.627  4192  6637 W IcingInternalCorpora: getNumBytesRead when not calculated.
08-26 14:59:54.657  6625  6625 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-26 14:59:54.667  6625  6638 D Mms/ArtClassLoader: init before art first
08-26 14:59:54.667  6625  6625 D Mms/TelephonyPermission: start operation mode monitor
08-26 14:59:54.667  6625  6625 D Mms/TelephonyPermission: User ID is null set current User Id
08-26 14:59:54.677  6625  6639 D Mms/ArtClassLoader: init before art second
08-26 14:59:54.687  6625  6640 D Mms/ArtClassLoader: init before art third
08-26 14:59:54.697  6625  6625 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
08-26 14:59:54.697  6625  6625 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
08-26 14:59:54.697  1829  6592 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 516 ms] updated apps [took 516 ms] 
08-26 14:59:54.717  6625  6640 D Mms/ArtClassLoader: init [DONE] art
08-26 14:59:54.727  6625  6625 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-26 14:59:54.727  6625  6625 D Mms/TelephonyPermission: isDefault true
08-26 14:59:54.727  6625  6625 D Mms/MmsApp: onCreate() com.android.mms
08-26 14:59:54.727  6453  6560 W jxcore-log: Initializing JXcore engine
08-26 14:59:54.727  6453  6560 W jxcore-log: JXcore engine is ready
08-26 14:59:54.747  6625  6625 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
08-26 14:59:54.747  6625  6625 D Mms/MmsApp: [start]    initCountryIso consume time = 94.5075
08-26 14:59:54.757   781  1489 D CountryDetector: The first listener is added
08-26 14:59:54.757  6625  6625 D Mms/MmsApp: [end]    initCountryIso consume time = 7.467292
08-26 14:59:54.757  6625  6625 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.096666
08-26 14:59:54.777  2165  2165 E audit   : type=1400 msg=audit(1472216394.777:288): avc:  denied  { ioctl } for  pid=6560 comm="Thread-899" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 14:59:54.777  2165  2165 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:54.777  2165  2165 E audit   : type=1300 msg=audit(1472216394.777:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98ae53c8 items=0 ppid=348 ppcomm=main pid=6560 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-26 14:59:54.777  2165  2165 E audit   : type=1327 msg=audit(1472216394.777:288): proctitle="com.test.thalitest"
08-26 14:59:54.777  2165  2165 E audit   : type=1320 msg=audit(1472216394.777:288): 
08-26 14:59:54.777  2165  2165 E audit   : type=1400 msg=audit(1472216394.777:289): avc:  denied  { ioctl } for  pid=6560 comm="Thread-899" path="socket:[38676]" dev="sockfs" ino=38676 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-26 14:59:54.777  2165  2165 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:54.777  2165  2165 E audit   : type=1300 msg=audit(1472216394.777:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3b a1=5451 a2=3 a3=98ae53c8 items=0 ppid=348 ppcomm=main pid=6560 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-899" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-26 14:59:54.777  2165  2165 E audit   : type=1327 msg=audit(1472216394.777:289): proctitle="com.test.thalitest"
08-26 14:59:54.777  2165  2165 E audit   : type=1320 msg=audit(1472216394.777:289): 
08-26 14:59:54.777  6625  6625 D Mms/MmsConfig: before partial update
08-26 14:59:54.787  6453  6560 W jxcore-log: Starting JXcore engine
08-26 14:59:54.837  6625  6639 D Mms/ArtClassLoader: init [DONE] art
08-26 14:59:54.847  6625  6625 D Mms/MmsConfig: Load Resize quality : 80
08-26 14:59:54.847  6625  6625 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-26 14:59:54.847  6625  6625 D EasySignUpManager_1.0.5: isAuth is false
08-26 14:59:54.847  6625  6625 I EasySignUpManager_1.0.5: auth : false, join : 2
08-26 14:59:54.847  6625  6638 D Mms/ArtClassLoader: init [DONE] art
08-26 14:59:54.847  6625  6625 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
08-26 14:59:54.847  6625  6625 D EasySignUpManager_1.0.5: userSerialNumber = 0
08-26 14:59:54.847  6625  6625 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-26 14:59:54.847  6625  6625 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
08-26 14:59:54.847  6625  6625 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-26 14:59:54.847  6625  6625 D EasySignUpManager_1.0.5: isAuth is false
08-26 14:59:54.847  6625  6625 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
08-26 14:59:54.847  6625  6625 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
08-26 14:59:54.857  1718  1732 D TP/MmsSmsProvider: query, match:2117, calling pid = 6625, accessRestricted = false
08-26 14:59:54.867  1718  1732 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 1.137 ms
08-26 14:59:54.867  6625  6625 E CscParser: mps_code.dat does not exist
08-26 14:59:54.867  6625  6625 E CscParser: customer_path =/system/csc/customer.xml
08-26 14:59:54.867  6625  6625 E CscParser: fileName + /system/csc/customer.xml
08-26 14:59:54.877  6625  6625 E CscParser: mps_code.dat does not exist
08-26 14:59:54.877  6625  6625 E CscParser: customer_path =/system/csc/customer.xml
08-26 14:59:54.877  6625  6625 E CscParser: fileName + /system/csc/customer.xml
08-26 14:59:54.877  6453  6560 W jxcore-log: Platform android
08-26 14:59:54.877  6453  6560 W jxcore-log: 
08-26 14:59:54.877  6453  6560 W jxcore-log: Process ARCH arm
08-26 14:59:54.877  6453  6560 W jxcore-log: 
08-26 14:59:54.887  6625  6625 D CscParser: getInstance fileName =/system/csc/customer.xml
08-26 14:59:54.887  6625  6625 D Mms/MmsConfig:  enable multiwindow = true
08-26 14:59:54.887  6625  6625 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
08-26 14:59:54.887  6625  6625 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
08-26 14:59:54.887  6625  6625 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-26 14:59:54.887  6625  6625 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
08-26 14:59:54.887  6625  6625 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
08-26 14:59:54.887  6625  6625 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-26 14:59:54.887  6625  6625 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-26 14:59:54.897  6625  6625 D Mms/MmsConfig: [end]    init() consume time = 134.040365
08-26 14:59:54.897  6625  6625 D Mms/Contact: [start]    init() consume time = 3.265052
08-26 14:59:54.907  6625  6625 D Mms/Contact: [end]    init consume time = 8.694636
08-26 14:59:54.907  1718  1976 D TP/MmsSmsProvider: query, match:13, calling pid = 6625, accessRestricted = false
08-26 14:59:54.907  6625  6646 D Mms/DraftCache: [start]    rebuildCache consume time = 5.204322
08-26 14:59:54.917  1718  1976 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.712 ms
08-26 14:59:54.917  6625  6625 D Mms:transaction: roaming -> false (slotId = 0)
08-26 14:59:54.917  6625  6625 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 14:59:54.917  6625  6625 D Mms:transaction: auto download without roaming -> true
08-26 14:59:54.917  6625  6625 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-26 14:59:54.917  6625  6625 D Mms:transaction: roaming -> false (slotId = 1)
08-26 14:59:54.917  6625  6625 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-26 14:59:54.917  6625  6625 D Mms:transaction: auto download without roaming -> true
08-26 14:59:54.917  6625  6625 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-26 14:59:54.917  6625  6625 D Mms:transaction: auto download during roaming secondary -> false
08-26 14:59:54.917  6625  6625 D Mms:transaction: mAutoDownload ------> true
08-26 14:59:54.917  1718  1733 D TP/MmsSmsProvider: query, match:12, calling pid = 6625, accessRestricted = false
08-26 14:59:54.937  1718  1733 D TP/MmsSmsProvider: query, match 12:Elapsed time : 12.698 ms
08-26 14:59:54.937  6625  6625 D ComposerPerformance: 1472216394950 ms / [DONE] Composer constructor
08-26 14:59:54.937  6625  6646 D Mms/DraftCache: [end]    rebuildCache consume time = 26.891355
08-26 14:59:54.937  6625  6648 D Mms/Conversation: [start]    init() consume time = 1.249114
08-26 14:59:54.937  1718  1976 D TP/MmsSmsProvider: delete, match:1, calling pid = 6625
08-26 14:59:54.937  1718  1976 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-26 14:59:54.937  1718  1976 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
08-26 14:59:54.947  1718  1976 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
08-26 14:59:54.947  1718  1976 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-26 14:59:54.947  1718  1976 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-26 14:59:54.947  1718  1976 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
08-26 14:59:54.947  6625  6625 D CII     : Log Level [5]
08-26 14:59:54.957  6625  6625 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
08-26 14:59:54.957  6625  6625 I Mms/ReservationManager: ReservationManager()
08-26 14:59:54.957  6625  6625 I Mms/ReservationManager: resetAfterConnected()
08-26 14:59:54.957  1718  1976 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-26 14:59:54.957  1718  1976 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-26 14:59:54.957  1718  1976 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-26 14:59:54.957  1718  1976 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 16.873 ms
08-26 14:59:54.957  1718  1976 D TP/MmsSmsProvider: need read changed broadcast:false
08-26 14:59:54.957  6625  6648 D Mms/Conversation: [end]    init consume time = 19.068177
08-26 14:59:54.957  6625  6648 D Mms/MessagingNotification: [start]    init() consume time = 2.501406
08-26 14:59:54.957  6625  6648 D Mms/MessagingNotification: [end]    init consume time = 1.446302
08-26 14:59:54.957  1718  2557 D TP/MmsSmsProvider: query, match:7, calling pid = 6625, accessRestricted = false
08-26 14:59:54.967  1718  2557 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.629 ms
08-26 14:59:54.967  6625  6650 D Mms/Synchronizer: [start]    doSync consume time = 3.633334
08-26 14:59:54.967  1718  1732 D TP/MmsSmsProvider: update, match:300, calling pid = 6625
08-26 14:59:54.967  1718  1732 V TP/MmsSmsProvider: syncDBData start
08-26 14:59:54.967  1718  1732 V TP/MmsSmsProvider: syncDBData sms end
08-26 14:59:54.967  1718  1732 V TP/MmsSmsProvider: syncDBData mms end
08-26 14:59:54.967  1718  1732 V TP/MmsSmsProvider: syncDBData end
08-26 14:59:54.967  1718  1732 D TP/MmsSmsProvider: update, match 300:Elapsed time : 1.931 ms
08-26 14:59:54.967  6625  6650 D Mms/Synchronizer: [end]    doSync consume time = 4.619791
08-26 14:59:54.967  6625  6649 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.866927
08-26 14:59:54.967  1718  1733 D TP/MmsSmsProvider: query, match:0, calling pid = 6625, accessRestricted = false
08-26 14:59:54.967  1718  1733 V TP/MmsSmsProvider: getSimpleConversations entered.
08-26 14:59:54.977  1718  1733 D TP/MmsSmsProvider: query, match 0:Elapsed time : 1.561 ms
08-26 14:59:54.977  6625  6625 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-26 14:59:54.977  1718  1976 D TP/MmsSmsProvider: query, match:400, calling pid = 6625, accessRestricted = false
08-26 14:59:54.987  6625  6649 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 12.433959
08-26 14:59:54.987  6235  6246 D BadgeProvider: query, [selection] : package=?
08-26 14:59:54.987  6625  6625 D Mms/MmsApp: [end]    onCreate() consume time = 1.533698
08-26 14:59:54.987  6625  6625 D Mms/MmsApp: [end]    onCreate() consume time = 0.176354
08-26 14:59:54.987  6625  6648 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-26 14:59:54.997  1718  1733 D TP/SmsProvider: query,matched:26, calling pid = 6625
08-26 14:59:54.997  1718  1733 D TP/SmsProvider: query, match 26:Elapsed time : 1.205 ms
08-26 14:59:55.007   781  3427 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
08-26 14:59:55.007  1718  1976 D TP/MmsSmsProvider: query, match:6, calling pid = 6625, accessRestricted = false
08-26 14:59:55.007  1718  1976 D TP/MmsSmsProvider: query, match 6:Elapsed time : 2.306 ms
08-26 14:59:55.017  6625  6625 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
08-26 14:59:55.017  6625  6625 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-26 14:59:55.017  6625  6625 D Mms:transaction: roaming -> false (slotId = 0)
08-26 14:59:55.017  6625  6625 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 14:59:55.017  6625  6625 D Mms:transaction: auto download without roaming -> true
08-26 14:59:55.017  6625  6625 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-26 14:59:55.017  6625  6625 D Mms:transaction: mAutoDownload ------> true
08-26 14:59:55.017  6651  6651 E Zygote  : v2
08-26 14:59:55.027   781   795 I ActivityManager: Start proc 6651:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
08-26 14:59:55.027  6651  6651 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:59:55.027  6651  6651 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:55.027  6651  6651 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:55.027  6651  6651 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:55.027  6651  6651 E Zygote  : accessInfo : 0
08-26 14:59:55.057  6651  6651 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:55.057  6651  6651 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:55.067  6663  6663 E Zygote  : v2
08-26 14:59:55.067  6663  6663 I libpersona: KNOX_SDCARD checking this for 10024
08-26 14:59:55.067  6663  6663 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:55.067  6663  6663 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:55.067  6663  6663 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:55.067   781  2274 I ActivityManager: Start proc 6663:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
08-26 14:59:55.067  6663  6663 E Zygote  : accessInfo : 0
08-26 14:59:55.067  6663  6663 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
08-26 14:59:55.077   781   795 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1dfcc6a 6651:com.samsung.android.bbc.bbcagent/1000}
08-26 14:59:55.107  6663  6663 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:55.107  6663  6663 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:55.117   781  1412 I ActivityManager: Killing 5171:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
08-26 14:59:55.137  6453  6560 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:59:55.137  6453  6560 I jxcore-log: 
08-26 14:59:55.137  6453  6560 W jxcore-log: JXcore engine is started
08-26 14:59:55.137  6651  6651 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
08-26 14:59:55.137   781  1731 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
08-26 14:59:55.137  6453  6555 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 14:59:55.137  6453  6453 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-26 14:59:55.147  6663  6663 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
08-26 14:59:55.167  6663  6663 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
08-26 14:59:55.167  6651  6651 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
08-26 14:59:55.177  1448  1448 D Recents : onTaskStackChanged
08-26 14:59:55.207  6675  6675 E Zygote  : v2
08-26 14:59:55.207  6675  6675 I libpersona: KNOX_SDCARD checking this for 10097
08-26 14:59:55.207  6675  6675 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:55.207  6675  6675 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:55.207  6675  6675 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:55.217  6675  6675 E Zygote  : accessInfo : 0
08-26 14:59:55.217  6675  6675 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
08-26 14:59:55.217   781  1747 I ActivityManager: Start proc 6675:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-26 14:59:55.217   781  1747 I ActivityManager: Killing 5237:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
08-26 14:59:55.237   781  1642 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
08-26 14:59:55.247  6625  6648 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-26 14:59:55.247  6663  6663 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
08-26 14:59:55.257  6675  6675 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:55.257  6675  6675 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:55.267   781  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8e855b 6675:com.google.android.apps.docs/u0a97}
08-26 14:59:55.277  6675  6675 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
08-26 14:59:55.277  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-26 14:59:55.277  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-26 14:59:55.277  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-26 14:59:55.277  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-26 14:59:55.287  6675  6675 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
08-26 14:59:55.287  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-26 14:59:55.297  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-26 14:59:55.297  6663  6663 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-26 14:59:55.557  6675  6689 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-26 14:59:55.557  6675  6689 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 14:59:55.557  6675  6689 I GAv4    :   adb logcat -s GAv4
,08-26 14:59:55.557   781  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/167_task.xml.bak
,08-26 14:59:55.587  6675  6689 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-26 14:59:55.587   781  2274 V AlarmManager:  remove PendingIntent] PendingIntent{e261c37: PendingIntentRecord{c5cf5a4 com.google.android.apps.docs broadcastIntent}}
,08-26 14:59:55.587  6675  6689 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:59:55.587  6675  6689 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:59:55.597  6675  6695 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:59:55.687  6675  6675 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-26 14:59:55.687  6675  6675 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-26 14:59:55.697  4192  5034 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-26 14:59:55.727  6675  6689 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
,08-26 14:59:55.727  6675  6689 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-26 14:59:55.727  6675  6689 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
,08-26 14:59:55.727  6675  6689 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-26 14:59:55.747  4192  5034 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-26 14:59:55.767  6701  6701 E Zygote  : v2
08-26 14:59:55.767  6701  6701 I libpersona: KNOX_SDCARD checking this for 10098
08-26 14:59:55.767  6701  6701 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:55.767  6701  6701 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:55.767  6701  6701 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:55.767   781  1625 I ActivityManager: Start proc 6701:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
08-26 14:59:55.767  6701  6701 E Zygote  : accessInfo : 0
08-26 14:59:55.767  6701  6701 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-26 14:59:55.767   781  1625 I ActivityManager: Killing 5096:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-26 14:59:55.807  6701  6701 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:55.807  6701  6701 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:55.817   781  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{45c810 6701:com.sec.android.automotive.drivelink/u0a98}
,08-26 14:59:55.827   781  2274 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-26 14:59:55.827  6701  6701 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-26 14:59:55.857  6701  6701 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-26 14:59:55.897  6701  6701 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-26 14:59:55.907   781  1727 V AlarmManager:  remove PendingIntent] PendingIntent{d0b3f09: PendingIntentRecord{4f4c50e com.sec.android.automotive.drivelink broadcastIntent}}
,08-26 14:59:55.907  6701  6717 I GMPM    : App measurement is starting up
,08-26 14:59:55.907  6701  6701 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-26 14:59:55.917  6701  6717 E GMPM    : getGoogleAppId failed with status: 10
,08-26 14:59:55.917  6701  6717 E GMPM    : Uploading is not possible. App measurement disabled
,08-26 14:59:55.917   781  1319 V AlarmManager:  remove PendingIntent] PendingIntent{7165b2f: PendingIntentRecord{4f4c50e com.sec.android.automotive.drivelink broadcastIntent}}
,08-26 14:59:55.937  6701  6701 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-26 14:59:55.937  4192  5034 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-26 14:59:55.947  6701  6701 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-26 14:59:55.967  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:59:55.967  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:59:55.987  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:59:56.017  6723  6723 E Zygote  : v2
08-26 14:59:56.017  6723  6723 I libpersona: KNOX_SDCARD checking this for 10032
08-26 14:59:56.017  6723  6723 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:56.017  6723  6723 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:56.017  6723  6723 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:56.017  6723  6723 E Zygote  : accessInfo : 0
,08-26 14:59:56.017  6723  6723 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-26 14:59:56.017   781  1727 I ActivityManager: Start proc 6723:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
08-26 14:59:56.017   781  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-26 14:59:56.047  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:56.047  6723  6723 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:56.057   781  1322 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-26 14:59:56.067  6723  6723 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-26 14:59:56.077  6675  6690 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-26 14:59:56.087  6723  6723 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-26 14:59:56.167   781  6365 I HarmonyEASService: Updating for all 1
,08-26 14:59:56.187  6701  6701 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-26 14:59:56.197  6701  6701 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-26 14:59:56.197  6675  6684 W art     : Suspending all threads took: 6.062ms
,08-26 14:59:56.207  6701  6701 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-26 14:59:56.227  6723  6723 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-26 14:59:56.227  6675  6690 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-26 14:59:56.227  6701  6701 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDFri Aug 26 14:59:56 GMT+02:00 2016
,08-26 14:59:56.237  6701  6701 D DialogFlow: initQueue()
,08-26 14:59:56.247  6737  6737 E Zygote  : v2
08-26 14:59:56.247  6737  6737 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:59:56.247  6737  6737 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:56.247  6737  6737 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:56.247  6737  6737 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:56.247   781  1717 I ActivityManager: Start proc 6737:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
,08-26 14:59:56.247  6737  6737 E Zygote  : accessInfo : 0
,08-26 14:59:56.247   781  1717 I ActivityManager: Killing 5518:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
,08-26 14:59:56.247   781  1717 I ActivityManager: Killing 5720:com.sec.android.app.popupuireceiver/1000 (adj 15): DHA:empty #37
,08-26 14:59:56.277   781  1489 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.popupuireceiver, Auto Run ON
,08-26 14:59:56.277  6737  6737 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:56.277  6737  6737 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:56.287   781   795 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-26 14:59:56.287  6675  6690 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-26 14:59:56.287  6675  6690 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-26 14:59:56.297   781  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{204fc79 6737:com.samsung.android.app.filterinstaller/1000}
,08-26 14:59:56.297  6723  6723 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-26 14:59:56.297  6675  6690 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 14:59:56.307  6737  6737 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-26 14:59:56.317  6737  6737 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-26 14:59:56.327  6737  6737 E FilterPackageIntentReceiver: This package is not a effect filter
,08-26 14:59:56.337  6754  6754 E Zygote  : v2
08-26 14:59:56.337  6754  6754 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:59:56.337  6754  6754 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:56.337  6754  6754 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:56.337  6754  6754 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:56.337  6754  6754 E Zygote  : accessInfo : 0
,08-26 14:59:56.337   781  1625 I ActivityManager: Start proc 6754:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
,08-26 14:59:56.337   781  1625 I ActivityManager: Killing 5417:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-26 14:59:56.347  6675  6690 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 14:59:56.357   781  1412 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-26 14:59:56.367  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:56.367  6754  6754 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:56.367   781  1810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{fa28dbe 6754:com.samsung.helphub/1000}
,08-26 14:59:56.377   781  1791 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
08-26 14:59:56.377  6754  6754 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
08-26 14:59:56.387  6754  6754 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
08-26 14:59:56.397  6723  6723 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
08-26 14:59:56.397  6723  6723 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
08-26 14:59:56.397  6723  6723 D DialogFlow: initQueue()
,08-26 14:59:56.437  6766  6766 E Zygote  : v2
,08-26 14:59:56.437  6766  6766 I libpersona: KNOX_SDCARD checking this for 1000
,08-26 14:59:56.437   781  1489 I ActivityManager: Start proc 6766:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
08-26 14:59:56.437   781  1489 I ActivityManager: Killing 5429:com.policydm/1000 (adj 15): DHA:empty #37
08-26 14:59:56.437  6766  6766 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:56.437  6766  6766 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:56.437  6766  6766 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:56.447  6766  6766 E Zygote  : accessInfo : 0
,08-26 14:59:56.467  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:56.467  6766  6766 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:56.467   781  1625 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-26 14:59:56.467  6593  6593 D AASAservice: onDestroy()
,08-26 14:59:56.477  6593  6593 I art     : System.exit called, status: 80
08-26 14:59:56.477  6593  6593 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-26 14:59:56.477   781  2302 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9909696 6766:com.samsung.android.app.mirrorlink/1000}
,08-26 14:59:56.477  6766  6766 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-26 14:59:56.487   781  1810 I ActivityManager: Process com.samsung.aasaservice (pid 6593)(adj 0) has died(44,738)
,08-26 14:59:56.487   781  1810 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-26 14:59:56.497  6766  6766 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-26 14:59:56.537   348   348 I Zygote  : Process 6593 exited cleanly (80)
,08-26 14:59:56.537  6766  6766 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-26 14:59:56.537  6766  6766 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-26 14:59:56.547   781  2302 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f020854 5846:com.google.android.apps.plus/u0a134}
,08-26 14:59:56.557   781  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f020854 5846:com.google.android.apps.plus/u0a134}
,08-26 14:59:56.567   781  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f020854 5846:com.google.android.apps.plus/u0a134}
,08-26 14:59:56.607   781   794 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-26 14:59:56.617   781  1731 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-26 14:59:56.617   781  2302 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-26 14:59:56.617   781  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-26 14:59:56.617   781  1489 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-26 14:59:56.617   781  2274 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-26 14:59:56.627   781  1727 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-26 14:59:56.627   781  1747 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-26 14:59:56.637  6781  6781 E Zygote  : v2
08-26 14:59:56.637  6781  6781 I libpersona: KNOX_SDCARD checking this for 10165
08-26 14:59:56.637  6781  6781 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:56.637  6781  6781 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:56.637  6781  6781 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 14:59:56.637  6781  6781 E Zygote  : accessInfo : 0
,08-26 14:59:56.637  6781  6781 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-26 14:59:56.637   781  1810 I ActivityManager: Start proc 6781:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-26 14:59:56.667  6781  6781 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:56.667  6781  6781 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:56.677   781  2274 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12c7ed 6781:com.sec.kidsplat.installer/u0a165}
,08-26 14:59:56.697  6781  6781 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-26 14:59:56.707  6781  6781 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-26 14:59:56.717   781  2302 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12c7ed 6781:com.sec.kidsplat.installer/u0a165}
,08-26 14:59:56.727  6781  6781 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-26 14:59:56.747  6793  6793 E Zygote  : v2
08-26 14:59:56.747  6793  6793 I libpersona: KNOX_SDCARD checking this for 10142
08-26 14:59:56.747  6793  6793 E Zygote  : isSdpEnabledProcess - SDP enabled
08-26 14:59:56.747  6793  6793 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:56.747  6793  6793 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 14:59:56.747   781  1642 I ActivityManager: Start proc 6793:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
08-26 14:59:56.747  6793  6793 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-26 14:59:56.747   781  1322 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-26 14:59:56.747  6793  6793 E Zygote  : accessInfo : 64
08-26 14:59:56.747   781  1642 I ActivityManager: Killing 5777:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
08-26 14:59:56.747  6793  6793 E Zygote  : isSdpEnabledProcess - SDP enabled
08-26 14:59:56.747  6793  6793 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-26 14:59:56.747  6793  6793 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-26 14:59:56.747   781  1322 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 14:59:56.767  6793  6793 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:56.767  6793  6793 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:56.767   781  2274 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-26 14:59:56.787   781  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f378622 6793:com.sec.android.app.sbrowser/u0a142}
,08-26 14:59:56.787  6793  6793 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-26 14:59:56.807  6793  6793 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-26 14:59:56.817  6793  6793 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-26 14:59:56.817  6793  6793 D ManifestProvider: onCreate()
,08-26 14:59:56.827  6793  6793 I SBrowserUtils: getSystemProperty of sales_code : XEO
,08-26 14:59:56.827  6793  6793 I SBrowserUtils: getSystemProperty of country_code : Poland
08-26 14:59:56.827  6793  6793 I SBrowserUtils: getSystemProperty of country_code : Poland
08-26 14:59:56.827  6793  6793 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-26 14:59:56.837  6793  6793 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-26 14:59:56.837  6793  6793 D [MM]MHDataBaseProvider: onCreate()
,08-26 14:59:56.857  6793  6793 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@ae5fa39)
,08-26 14:59:56.907   781  1731 I ActivityManager: Killing 5796:com.sec.android.cloudagent/u0a2 (adj 15): DHA:empty #37
,08-26 14:59:56.907   781  1731 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b611 2102:com.google.android.gms.persistent/u0a11}
,08-26 14:59:56.937   781   794 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d567e0 4192:com.google.android.gms/u0a11}
,08-26 14:59:56.937  4192  6808 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-26 14:59:56.937   781  1625 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.cloudagent, Auto Run ON
,08-26 14:59:56.947  4192  6807 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-26 14:59:56.947  4192  6808 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-26 14:59:56.957  4192  4192 D AsyncTaskServiceImpl: Submit a task: nzm
,08-26 14:59:56.967  4192  6808 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-26 14:59:56.977  4192  6808 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-26 14:59:56.977   781  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b611 2102:com.google.android.gms.persistent/u0a11}
,08-26 14:59:56.997   781  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d567e0 4192:com.google.android.gms/u0a11}
,08-26 14:59:56.997  4192  5094 D nzm     : Processing package: com.test.thalitest
,08-26 14:59:57.007  4192  4192 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-26 14:59:57.027  6625  6625 I Mms/MmsApp:  start initViewCache mms
,08-26 14:59:57.037  4192  5094 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,08-26 14:59:57.037  4192  5094 D nzm     : Found info for package com.test.thalitest in db.
,08-26 14:59:57.097   781  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5add8d6 6339:com.sec.android.app.samsungapps/u0a39}
,08-26 14:59:57.117   781  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8414474 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2768281 5870:com.android.vending/u0a29}
,08-26 14:59:57.207  5870  5870 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-26 14:59:57.207  2102  2102 D WearableService: callingUid 10011, callindPid: 2102
,08-26 14:59:57.217  5870  5870 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,08-26 14:59:57.217   781   781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d262b59 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{52bff44 5920:com.sec.android.app.shealth/u0a34}
,08-26 14:59:57.227   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:59:57.237  5870  5870 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 14:59:57.237   781  1412 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d262b59 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1e0150 1888:com.sec.android.app.shealth:remote/u0a34}
,08-26 14:59:57.247  5870  5870 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,08-26 14:59:57.247   781   781 I BackgroundCompactionService: onStart. jobID=801
,08-26 14:59:57.257   781   781 I BackgroundCompactionService: onStart done. jobID=801
,08-26 14:59:57.257   781  6815 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-26 14:59:57.257   781  6815 I BackgroundCompactionService: compact_memory command done
,08-26 14:59:57.347  6723  6753 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-26 14:59:57.357  6723  6753 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-26 14:59:57.367   781  1810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d262b59 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b1e0150 1888:com.sec.android.app.shealth:remote/u0a34}
,08-26 14:59:57.407   781  1319 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{76851b u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b611 2102:com.google.android.gms.persistent/u0a11}
,08-26 14:59:57.417  6723  6753 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-26 14:59:57.417  6723  6753 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-26 14:59:57.417  6723  6753 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-26 14:59:57.417  6723  6753 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-26 14:59:57.417  6723  6753 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-26 14:59:57.497  6625  6625 D Mms/BubbleViewCache: fillCache bubble = 4
,08-26 14:59:58.167  4192  5034 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-26 14:59:58.277  4192  5034 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-26 14:59:58.277  4192  5034 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-26 14:59:58.287  4192  5034 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-26 14:59:58.447   781  3423 D SSRM:n  : SIOP:: AP = 480, PST = 463, CUR = 350, LCD = 0
,08-26 14:59:58.457   781  3423 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-26 14:59:59.987   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:00:00.017   781  3423 D M       : limitCPUFreq:: freq = 1728000
,08-26 15:00:00.017   781  3423 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 781  pkgName : SIOP_ARM_MAX@25
,08-26 15:00:00.017   781  3423 D M       : limitGPUFreq:: freq = 389000000
,08-26 15:00:00.017   781  3423 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-26 15:00:02.517   781   924 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 15:00:02.547   781   924 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-26 15:00:03.917   781   924 D PackageManager: [MSG] MCS_UNBIND
,08-26 15:00:03.947   781  1319 I ActivityManager: Killing 5607:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-26 15:00:03.987   781  1717 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-26 15:00:07.587   781  1574 E Watchdog: !@Sync 3 [08-26 15:00:07.595]
,08-26 15:00:08.347   781  1235 V AlarmManager: Expired Alarm result :4
,08-26 15:00:08.357   781   781 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 15:00:08.357   781  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-26 15:00:08.357   781  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-26 15:00:08.367   781   795 V AlarmManager:  remove PendingIntent] PendingIntent{2bf17f6: PendingIntentRecord{742ad25 com.google.android.gms broadcastIntent}}
,08-26 15:00:08.367   781  2302 I ActivityManager: Killing 5753:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-26 15:00:08.377   781   781 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-26 15:00:08.377   781   781 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 15:00:08.377  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-26 15:00:08.377  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
08-26 15:00:08.377  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:00:08.387  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:00:08.397  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:00:08.397  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.407  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.407   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:08.407   781  2302 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4355, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:00:08.407   781  2302 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-26 15:00:08.407   781  2302 D BatteryService: stay LED for charging
08-26 15:00:08.407   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:08.407   781   781 I MotionRecognitionService: Plugged
,08-26 15:00:08.417   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:00:08.417   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-26 15:00:08.417   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:00:08.417  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:08.417  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:00:08.427  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.427  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.427  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.427  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.427  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.427  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:08.427  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:08.437  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:08.437  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:00:08.437  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:08.437  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:08.477   781  1319 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-26 15:00:08.487  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:00:08.497   781  3423 D SSRM:n  : SIOP:: AP = 450, PST = 461, CUR = 350, LCD = 0
,08-26 15:00:08.507   781  3423 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-26 15:00:08.667   781   854 I ActivityManager: Waited long enough for: ServiceRecord{b530002 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
,08-26 15:00:12.157   781  1235 V AlarmManager: Expired Alarm result :4
,08-26 15:00:12.197   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5bcbd82 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b611 2102:com.google.android.gms.persistent/u0a11}
,08-26 15:00:12.227  6453  6560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:00:12.227  6453  6560 I jxcore-log: 
,08-26 15:00:12.227  6453  6560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:00:12.227  6453  6560 I jxcore-log: 
,08-26 15:00:12.237  5870  5910 I Finsky  : [840] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,08-26 15:00:12.237   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{91b9cc9: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:12.237  6453  6560 D BluetoothAdapter: STATE_ON
,08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:00:12.247  6453  6560 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:00:12.257  6453  6560 D BluetoothAdapter: STATE_ON
,08-26 15:00:12.257  6453  6560 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:00:12.257  6453  6560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:00:12.257  6453  6560 I jxcore-log: 
08-26 15:00:12.257  6453  6560 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:00:12.257  6453  6560 I jxcore-log: 
,08-26 15:00:12.367   781   795 V AlarmManager:  remove PendingIntent] PendingIntent{5b24eef: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:12.467  4192  6863 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-26 15:00:12.467  4192  6863 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 15:00:12.487  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:00:12.497   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{73b6aa6: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:12.517   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f2ce7 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{893b611 2102:com.google.android.gms.persistent/u0a11}
,08-26 15:00:12.557   781  1412 V AlarmManager:  remove PendingIntent] PendingIntent{26eb094: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:12.697   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{137b083: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:12.777  6453  6560 I jxcore-log: Running unit tests
08-26 15:00:12.777  6453  6560 I jxcore-log: 
,08-26 15:00:12.777  6453  6560 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-26 15:00:12.777  6453  6560 I jxcore-log: Failed to execute UT.
08-26 15:00:12.777  6453  6560 I jxcore-log: 
,08-26 15:00:12.777  6453  6560 I jxcore-log: Unit Test app is loaded
08-26 15:00:12.777  6453  6560 I jxcore-log: 
,08-26 15:00:12.787  6453  6560 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:00:12.787  6453  6560 I jxcore-log: 
,08-26 15:00:12.787  6453  6453 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 15:00:12.787  6453  6560 I jxcore-log: My device name is: samsung-SM-G900F
08-26 15:00:12.787  6453  6560 I jxcore-log: 
,08-26 15:00:12.817  5870  5910 I Finsky  : [840] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,08-26 15:00:12.817  5870  5870 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-26 15:00:12.867   781  1727 I ActivityManager: Start proc 6868:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-26 15:00:12.867  6868  6868 E Zygote  : v2
08-26 15:00:12.867  6868  6868 I libpersona: KNOX_SDCARD checking this for 10011
,08-26 15:00:12.867  6868  6868 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:12.867  6868  6868 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:00:12.877  6868  6868 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:00:12.877  6868  6868 E Zygote  : accessInfo : 0
,08-26 15:00:12.877  6868  6868 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-26 15:00:12.907  6868  6868 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:12.907  6868  6868 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:12.927  6868  6868 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-26 15:00:12.967  6868  6868 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:00:12.967  6868  6868 I MultiDex: install
08-26 15:00:12.967  6868  6868 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:00:12.997  6868  6868 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-26 15:00:13.007  6868  6868 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-26 15:00:13.007  6868  6868 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-26 15:00:13.017  6868  6868 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 15:00:13.047  6868  6868 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 15:00:13.067  6868  6868 D ChimeraCfgMgr: Reading stored module config
,08-26 15:00:13.177  6868  6882 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 15:00:13.207  2102  2102 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=f9aa4fb0-990f-4565-9a96-90fd74a27cf6
,08-26 15:00:13.217  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:00:13.217  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:00:13.247   318   966 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6868)
,08-26 15:00:13.337   781   791 I art     : Background partial concurrent mark sweep GC freed 35051(2008KB) AllocSpace objects, 17(340KB) LOS objects, 27% free, 42MB/58MB, paused 1.987ms total 130.551ms
08-26 15:00:13.337   318   966 D WVCdm   : Instantiating CDM.
,08-26 15:00:13.337   318   982 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6868)
08-26 15:00:13.337   318   982 I WVCdm   : CdmEngine::OpenSession
08-26 15:00:13.337   318   982 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-26 15:00:13.347   318   982 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 15:00:13.347   318   982 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-26 15:00:13.347   318   982 D DrmWidevineDash: Service_Initialize: starts!
08-26 15:00:13.347   318   982 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-26 15:00:13.357   318   982 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:00:13.357   318   982 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-26 15:00:13.357   318   982 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-26 15:00:13.357   318   982 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 15:00:13.357   318   982 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:00:13.357   318   982 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-26 15:00:13.357   318   982 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-26 15:00:13.357   318   982 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 15:00:13.357   318   982 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:00:13.377   318   982 D QSEECOMAPI: : Loaded image: APP id = 4
,08-26 15:00:13.377   318   982 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-26 15:00:13.377   318   982 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefdb000
08-26 15:00:13.377   318   982 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaefdb000
,08-26 15:00:13.387  6868  6879 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:13.387  6868  6879 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:13.397   318   982 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-26 15:00:13.397   318   982 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-26 15:00:13.397   318   982 D DrmWidevineDash: hlos api version =  10
08-26 15:00:13.397   318   982 D DrmWidevineDash: tz api version =  10
08-26 15:00:13.397   318   982 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-26 15:00:13.397   318   982 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-26 15:00:13.397   304  1125 D EnterpriseController: netId is 0
08-26 15:00:13.397   304  1125 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-26 15:00:13.397  6453  6560 W jxcore-log: !!! js_ReportOverRecursed called !!!
,08-26 15:00:13.427   318   982 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-26 15:00:13.427   318   982 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-26 15:00:13.427   318   982 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xaee3e924
,08-26 15:00:13.427   318   982 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,08-26 15:00:13.427   318   982 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,08-26 15:00:13.427   318   982 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1edd168, dataLength=8
,08-26 15:00:13.427   318   982 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-26 15:00:13.447   318   982 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1e4d800, wrapped_rsa_key_length=1280
,08-26 15:00:13.447   318   982 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-26 15:00:13.447   318   982 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 15:00:13.457  6868  6879 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6868, getuid(): 10011
,08-26 15:00:13.457   318   966 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-26 15:00:13.457   318   966 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,08-26 15:00:13.457   318   966 I WVCdm   : CdmEngine::GenerateKeyRequest
08-26 15:00:13.457   318   966 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xae60ad60, idLength=0xaf279f2c
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-26 15:00:13.467   318   966 D DrmWidevineDash: hlos api version =  10
08-26 15:00:13.467   318   966 D DrmWidevineDash: tz api version =  10
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-26 15:00:13.467   318   966 D WVCdm   : PrepareKeyRequest: nonce=1932160152
,08-26 15:00:13.467   318   966 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xaee47b00
08-26 15:00:13.467   318   966 D DrmWidevineDash: message_length=1631, signature=0xaeec9a80, signature_length=2938609668
,08-26 15:00:13.517  2102  2470 W GCoreFlp: No location to return for getLastLocation()
,08-26 15:00:13.577  6891  6891 F google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,08-26 15:00:13.577  6891  6891 F google-breakpad: V WebView:48.0.2564.106
08-26 15:00:13.577  6891  6891 F google-breakpad: O A arm 04 armv7l samsung/kltexx/klte:6.0.1/MMB29M/G900FXXU1CPEM:user/release-keys
08-26 15:00:13.577  6891  6891 F google-breakpad: G OpenGL ES 3.0 V@140.0 AU@  (GIT@Ia10634f51b)|Qualcomm|Adreno (TM) 330
08-26 15:00:13.587  6891  6891 F google-breakpad: S 0 98A66B18 98A66000 00008000
,08-26 15:00:13.607   318   966 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-26 15:00:13.607   318   318 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6868)
08-26 15:00:13.607   318   318 I WVCdm   : CdmEngine::CloseSession
08-26 15:00:13.607   318   318 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-26 15:00:13.607   318   318 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-26 15:00:13.607   318   318 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-26 15:00:13.617   318   318 D DrmWidevineDash: Service_Uninitialize: starts!
08-26 15:00:13.617   318   318 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-26 15:00:13.617   318   318 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 4
08-26 15:00:13.617   318   318 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-26 15:00:13.617   318   318 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-26 15:00:13.617  4192  6864 D UdcContextInitService: registered all accounts: true
,08-26 15:00:13.617  2102  2546 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:00:13.627  2102  2707 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66000 0100000088506498010000007F00000000A806AEE4975299C01E899A8EFF4137E0A806AEE497529910C06298E01E899A40B062986860A6989C60A698CE83AA1A0000000000000000588B53994C61A698E0A806AE1461A6985861A698E4975299FC60A698305509999C910299000000005861A6980000000000000000E4975299E0A806AE588B539901000000C05ECFB69C91029984910299EC60A698000000008016329788FFFFFF0000000082FFFFFFE4975299608162980000000040A66298485FA6984000000045CC9794CECC9794CECC9794F2CC9794CECC979401000000000000000C00000004CD979424CD979401000000010000000100000000000400806A52991400000005000000FFFFFFFFB864A6980000000000000000000000000000040000000000405EA69801000000885064984C61A69800000000000000001C5EA698F4FD0899000000004861A698000000000000000000000000E0A806AE080000000000000040A662988C5EA698000000004C61A698405EA698105A2A97
,08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66180 885064984C61A698000000001461A6983C5EA69858FF08993C5EA698E0A806AEE0A806AE4C61A6988C5EA698845EA6986C5EA698E80B159988506498D8975299B865A698E6FFFFFFECA806AE8C5EA6980000000000000000C05ECFB6E0A806AEFC5EA698503F159940A662987C5EA6988C5EA6988C5EA6982062A6988C5EA698D45EA6988489F998002271984CCC3D990000A69800C89794000000000400000045CC9794CECC9794CECC9794F2CC9794CECC979401000000000000000C00000004CD979424CD979401000000010000000100000000000400806A52991400000005000000FFFFFFFFB864A6980000000000000000000000000000040000000000405EA69801000000885064984C61A69800000000000000001C5EA698F4FD0899000000004861A698000000000000000000000000E0A806AE080000000000000040A662988C5EA698000000004C61A698405EA698105A2A97885064984C61A698000000001461A6983C5EA69858FF08993C5EA698E0A806AEE0A806AE4C61A698
,08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66300 8C5EA698845EA6986C5EA698E80B159988506498D8975299B865A698E6FFFFFFECA806AE8C5EA6980000000000000000C05ECFB6E0A806AEFC5EA698503F159940A662987C5EA6988C5EA6988C5EA6982062A6988C5EA698D45EA6988489F998002271984CCC3D990000A69800C8979400000000030200000100000001000000603F679800826A981D9A4898ADDBBA004466A698CE83AA1A603F67985012EE9688FFFFFF81FFFFFFB012EE9603020000603F6798010000004466A69808E6429888FFFFFFCC63A698B012EE9603020000B864A6980100000000000000B4DB4298FC63A698EC63A69808D55C9900000000000000007CDB4298C004000002000000C0D0629888FFFFFFA00F639888FFFFFFB012EE9688FFFFFF5012EE9688FFFFFFF0DA5C99C8F17198B012EE968012EE960000000087FFFFFFA00F63985012EE968012EE9680163297E0BB0F9485020000C0366498020000000000000082FFFFFFA00F639888FFFFFF5012EE9688FFFFFFA864A6985012EE96F011EE962012EE96
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66480 FCDE0F94850200000037649800000000F011EE9688FFFFFF603CEA968A00000007000000703CEA96E0A806AE40B062987041E0960037649820988F9803020000603F67980100000040B0629888FFFFFF7041E09685FFFFFF0000403F0000803E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000020BE06AEE0A806AEC05ECFB68066A6980100000081FFFFFFD865A6983C65A698480CF5980000579A000000004466A6986074F598603F67980000000000000000A865A6985C65A69838978F98588B5399E0A806AE001E899AC476A69800000000000000000000000001000000AC6DA698E0A806AE0001000000000000B0DD0F9400000000603F6798386AA698020000000100000000000000000000000E00000084FFFFFF0000000000000000106AA698F6FFFFFFECA806AE01000000E0A806AED865A698000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66600 8066A698E0A806AE78EB5C9900826A9800000000B806DF954466A698CE83AA1A00000000E0A806AE8066A6984866A698603F679800826A98CE83AA1A000000006C66A6980C141399000000000000000000000000C05ECFB601000000E0A806AE406AA6987866A698F469A6982416139952106D96FB116D96406AA69801000000E8BC52990100000000826A987866A6980000000000126D9602000000020000000100000000000000806A52995C0000000600000000000000B075A69800000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66780 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086D9600000000000000000100000002000000E015329700836A9825EBBBAD0000000000000000CE83AA1A00000000C05ECFB600000000E0A806AEC86A05991068A6988C6BA698A81613990000000000000000306CA6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66900 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CE83AA1AC05ECFB6306AA698E0A806AEE06AA698406AA698B806DF959C6AA698E41A139900000000000000000000000040B06298406AA698010000002077A698F6FFFFFFECA806AE00000000E0A806AE306AA6980300000008000000603F679888FFFFFF40B0629888FFFFFF7041E09685FFFFFF08E6339AB006DF950080879A606BA6980CE3CFB600E6339A9415CFB608E6339AB006DF95EB32CDB604000000846AA69801000000E0A806AE
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66A80 9C6AA69894B10399AC6DA698C476A698E0A806AE00000000CC6AA6985C050399B006DF95E86AA69840B0629869090000F0F6DA9A10709196F46AA69810F4E39800000000606BA6982C000000106BA698E86AA69807000000588B539974C73D99E0A806AE0000000085FFFFFF0040579A4C6BA69820F9E39800000000106BA698E0A806AE000000006CC73D99606BA69874C73D994C6BA69807000000000000000000000090B8E0E6A041E09685FFFFFFE01D7198E0A806AED06BA6987C6BA698546BA69885FFFFFF746BA69820DE029900000000E01D719822000000406CA6987C6BA698D06BA69874C73D99A041E0969C6BA69858872499DC9A4096000000000000000082FFFFFFD06BA698406CA698C06BA698E0A806AE046CA6981C1B1D99E4883D99508C3D99588B539922000000DC9A40964C42219600000000D46BA698A041E09685FFFFFFE0A806AE00000000A041E09685FFFFFF886CA698586DA69818715499506CA6980000000001000000406CA698306CA69822000000E0A806AE
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66C00 946DA698284420999806DF9500000000E0A806AE206CA69802000000686CA698E0FC5A97886CA69830FDE29688FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFFE0A806AE0000000000000000E0A806AE01000000B86DA698C86DA698010000009806DF950700000007000000010000001040E09600000000E0A806AE0000000000000000060000003C7154993C715499060000001871549900000000FFFFFFFF00000000A806DF95220000001840E096070000000000000001000000180070985098289681FFFFFFF46CA698E05A0D99070000001040E096E0A806AE0000000010007098006DA698346DA698E89C0D990000000000000000000000000CB20F94686DA6980100000000000000C011EE96E01B71981040E09600000000FFFFFFFF5098289681FFFFFFD06DA698B0B20F94286EA698446DA698906DA698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFF1040E09685FFFFFF1000709885FFFFFF000000006049669888FFFFFF88DC8D9B
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66D80 00000000FFFFFFFFC098289681FFFFFFD06DA698385F909800000000A46DA6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFF1040E09685FFFFFF2C6EA698C098289688DC8D9B010500001040E09685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C9340020000000000005000000030BD6298F0D9719885FFFFFF5C6EA698746EA69800000000506EA6988C6990988201000080866698010000000000000082FFFFFF1040E09685FFFFFFFC6EA698C0F6A8962CACF097010A00001040E09685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFF182DE6920200000000000000286FA698
08-26 15:00:13.637  6891  6891 F google-breakpad: S 98A66F00 8C69909802020000C04C669802000000A0C6659888FFFFFF1040E09685FFFFFF6016329788FFFFFF9C6FA69880673D98EC6DE69281060000F0D9719885FFFFFF1040E09685FFFFFFA0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000806FA6980000000083FFFFFF680000006081E3951840E09601000000300000006081E39500000000C06FA6988C6990988201000060241296010000000000000082FFFFFF1040E09685FFFFFF4470A69870603D982C66E692810700001040E09685FFFFFF0000000082FFFFFF6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6070A6985870A6985070A698C470A698780000006081E3950000000016AC6F96588B5399E0A806AE000000006870A6988C69909882010000A0241296010000000000000082FFFFFF1040E09685FFFFFFD470A69898D63C980C5CE692010600001040E09685FFFFFF
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67080 0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E070A698F870A69804000000600000006081E395E0A63C9881FFFFFF6471A698F81F909800000000F870A6988C69909882010000C0241296010000000000000082FFFFFF1040E09685FFFFFF6471A69898D03C981053E692010600001040E09685FFFFFF0000000082FFFFFFC024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000006011EE9600000000E0585096600000009011EE9604000000182DE6927471A69878B4EF98040000008871A6988C69909882010000E0241296010000000000000082FFFFFF6011EE9688FFFFFF0472A69890A53C98244AE692010700006011EE9688FFFFFF0000000082FFFFFFE024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFF1040E09685FFFFFF00000000F871A698F471A69888FFFFFF700000003011EE9660CFE596849102990000403F00000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67200 040000002872A6988C699098820100006025129601000000706FA79788FFFFFF90FDE29688FFFFFF8472A69860FB3B989043E6920105000090FDE29688FFFFFF706FA79788FFFFFF6025129688FFFFFFC0D3719885FFFFFF60CFE59601000000B472A698CC72A69850000000E0D542940200000070C87D9AA472A698C8B3EF9800000000B872A698DC4D8F9B8202000020D57197030000000000000082FFFFFF90FDE29688FFFFFF0000000081FFFFFF60CFE59688FFFFFF5473A698D0570595E8320D940109000060CFE59688FFFFFF0000000081FFFFFF90FDE29688FFFFFF0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF0012C99588FFFFFF0000000082FFFFFF0900000081FFFFFF60CFE59688FFFFFFB0CFE596000000008473A698C0D662989000000020C06298182DE6920200000070F23B9881FFFFFF000000007873A6988C69909882010000B00263980100000060CFE59688FFFFFF20D5719788FFFFFFFC73A69828F73B98
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67380 003DE6928107000020D5719788FFFFFF60CFE59688FFFFFFB002639888FFFFFFB0CFE59688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFFB0CFE59688FFFFFF0000000082FFFFFF2074A698385F909800000000E473A69878000000E0D54294000000005433E6924203000003000000000000002874A6988C6990980202000040D571970200000030F70D9688FFFFFFE0FC5A9788FFFFFF60CFE59688FFFFFF9474A69878EC48972038E6920106000060CFE59688FFFFFFE0FC5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF0000000082FFFFFF5874A698A03564984041E0964011719860000000E0D5429485FFFFFF2C442C9385FFFFFF9474A6980000000000376498384F2C93800B000080D57197020000000037649888FFFFFFE0FC5A9788FFFFFF70C9E59688FFFFFF5041E09685FFFFFF10CFE59688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFB0FEE29670C9E596A0356498603CEA968A000000
08-26 15:00:13.647  6868  6879 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6868, getuid(): 10011
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67500 7010EE965041E09610CFE59670C9E596A03564984041E09680187098C03CEA960900000000163297D0B06298D0B0629870C9E59688FFFFFF09000000401171980900000000376498E0FC5A9760FDE2960016329788FFFFFF000000007CDB429820DD42980004000080366498010000000037649888FFFFFFE0FC5A9788FFFFFF0000000082FFFFFFF0DA5C99E0FC5A9730FDE29600FDE2960000000087FFFFFFA00F6398D0FCE29600FDE296E0153297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFFD0FCE29688FFFFFF1076A698D0FCE29670FCE296A0FCE296FCDE0F9480020000003764980000000070FCE29688FFFFFF0098E6968A000000070000001098E696E0A806AE40B06298503CEA960037649820988F9803020000603F67980100000040B0629888FFFFFF503CEA9685FFFFFF0000403F0000803E0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67680 0000000000000000E0A806AEC05ECFB6E877A6980100000081FFFFFF4077A698AC77A6981474F598603F679800000000000000001077A698C476A69838978F98588B5399E0A806AE001E899A2C88A69800000000000000000000000001000000147FA698E0A806AE0001000000000000B0DD0F9400000000603F6798A07BA698020000000100000000000000000000000100000081FFFFFF0000000000000000787BA698F6FFFFFFECA806AE01000000E0A806AE4077A698000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000E877A698E0A806AE78EB5C9900826A98000000009006DF95AC77A698CE83AA1A00000000E0A806AEE877A698B077A698603F679800826A98000000009006DF95D477A6982C151399000000000000000000000000C05ECFB601000000E0A806AEA87BA698E077A6985C7BA6982416139952106D96FB116D96A87BA69801000000E8BC52990100000000826A98E077A6980000000000126D96
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67800 02000000020000000100000000000000806A52995C00000006000000000000001887A6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086D96000000000000000001000000020000004015329700836A9825EBBBAD0000000000000000CE83AA1A00000000C05ECFB600000000E0A806AEC86A05997879A698F47CA698A81613990000000000000000987DA69800000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67980 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67B00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CE83AA1AC05ECFB6987BA698E0A806AE487CA698A87BA6989006DF95047CA698E41A139900000000000000000000000040B06298A87BA698010000008888A698F6FFFFFFECA806AE00000000E0A806AE987BA6980300000008000000603F679888FFFFFF40B0629888FFFFFF503CEA9685FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000CE83AA1A04000000E0A806AE587CA698487CA698507CA698447CA69882FFFFFF8806DF95347CA698380503998806DF95507CA69840B0629888FFFFFFB87CA698C87CA698A87DA69801000000607CA69800000000947CA698209B2499507CA698000000001800000040B06298603F679888FFFFFF0000000082FFFFFF010000008806DF950000000082FFFFFFE0A806AE000000006CC73D99C87CA698B87CA69800834E9A
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67C80 98854E9AE0A806AEA87DA6986CC73D99047DA698B8AA1B99C87CA6981C7DA698070000004F000000AC3464963C9A409600000000309A409640B0629888FFFFFFE0A806AE00000000503CEA9685FFFFFFE0A806AE00000000187DA69818203F995D9A4096387DA698A87DA698287DA698E0A806AE1C7DA6982200000000834E9A6C7DA698EC1A1D99E4883D99508C3D99588B5399220000003C9A40961C422196000000003C7DA6982200000000000000C07EA69800000000547DA69814E5DA98F07DA698C07EA69818715499B87DA6980000000001000000A87DA698987DA69822000000E0A806AEFC7EA698284420997806DF9500000000E0A806AE887DA69802000000D07DA69890FC5A97F07DA698C0F7E29688FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0A806AE01000000207FA698307FA698010000007806DF95070000000700000001000000F03AEA9600000000E0A806AE0000000000000000060000003C7154993C715499
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67E00 060000001871549900000000FFFFFFFF000000008006DF9522000000F83AEA96070000000000000001000000180070985098289681FFFFFF5C7EA698E05A0D9907000000F03AEA96E0A806AE0000000010007098687EA6989C7EA698E89C0D990000000000000000000000000CB20F94D07EA698010000000000000040FCE296E01B7198F03AEA9600000000FFFFFFFF5098289681FFFFFF387FA698B0B20F94907FA698AC7EA698F87EA698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFFF03AEA9685FFFFFF1000709885FFFFFF000000006049669888FFFFFF88DC8D9B00000000FFFFFFFFC098289681FFFFFF387FA698385F9098000000000C7FA6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFFF03AEA9685FFFFFF947FA698C098289688DC8D9B01050000F03AEA9685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C9340020000000000005000000030BD6298
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A67F80 F0D9719885FFFFFFC47FA698DC7FA69800000000B87FA6988C6990988201000080866698010000000000000082FFFFFFF03AEA9685FFFFFF6480A698C0F6A8962CACF097010A0000F03AEA9685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFF182DE69202000000000000009080A6988C69909802020000C04C669802000000A0C6659888FFFFFFF03AEA9685FFFFFFC015329788FFFFFF0481A69880673D98EC6DE69281060000F0D9719885FFFFFFF03AEA9685FFFFFFA0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000E880A6980000000083FFFFFF680000006081E395F83AEA9601000000300000006081E395
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68100 000000002881A6988C6990988201000060241296010000000000000082FFFFFFF03AEA9685FFFFFFAC81A69870603D982C66E69281070000F03AEA9685FFFFFF0000000082FFFFFF6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC881A698C081A698B881A6982C82A698780000006081E3950000000016AC6F96588B5399E0A806AE00000000D081A6988C69909882010000A0241296010000000000000082FFFFFFF03AEA9685FFFFFF3C82A69898D63C980C5CE69201060000F03AEA9685FFFFFF0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000004882A6986082A69804000000600000006081E395E0A63C9881FFFFFFCC82A698F81F9098000000006082A6988C69909882010000C0241296010000000000000082FFFFFFF03AEA9685FFFFFFCC82A69898D03C981053E69201060000F03AEA9685FFFFFF0000000082FFFFFF
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68280 C024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E0FBE29600000000E05850966000000010FCE29604000000182DE692DC82A69878B4EF9804000000F082A6988C69909882010000E0241296010000000000000082FFFFFFE0FBE29688FFFFFF6C83A69890A53C98244AE69201070000E0FBE29688FFFFFF0000000082FFFFFFE024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFFF03AEA9685FFFFFF000000006083A6985C83A69888FFFFFF70000000B0FBE296D0C8E596849102990000403F00000000040000009083A6988C699098820100006025129601000000706FA79788FFFFFF20F8E29688FFFFFFEC83A69860FB3B989043E6920105000020F8E29688FFFFFF706FA79788FFFFFF6025129688FFFFFFC0D3719885FFFFFFD0C8E596010000001C84A6983484A69850000000E0D542940200000070C87D9A0C84A698C8B3EF98000000002084A698DC4D8F9B8202000020D5719703000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68400 0000000082FFFFFF20F8E29688FFFFFF0000000081FFFFFFD0C8E59688FFFFFFBC84A698D0570595E8320D9401090000D0C8E59688FFFFFF0000000081FFFFFF20F8E29688FFFFFF0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF9011C99588FFFFFF0000000082FFFFFF0900000081FFFFFFD0C8E59688FFFFFF20C9E59600000000EC84A698C0D662989000000020C06298182DE6920200000070F23B9881FFFFFF00000000E084A6988C69909882010000B002639801000000D0C8E59688FFFFFF20D5719788FFFFFF6485A69828F73B98003DE6928107000020D5719788FFFFFFD0C8E59688FFFFFFB002639888FFFFFF20C9E59688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFF20C9E59688FFFFFF0000000082FFFFFF8885A698385F9098000000004C85A69878000000E0D54294000000005433E6924203000003000000000000009085A6988C6990980202000040D571970200000030F70D9688FFFFFF
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68580 90FC5A9788FFFFFFD0C8E59688FFFFFFFC85A69878EC48972038E69201060000D0C8E59688FFFFFF90FC5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF0000000082FFFFFFC085A698A0356498203CEA964011719860000000E0D5429485FFFFFF2C442C9385FFFFFFFC85A6980000000000376498384F2C93800B000080D57197020000000037649888FFFFFF90FC5A9788FFFFFFE0C2E59688FFFFFF303CEA9685FFFFFF80C8E59688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF40F9E296E0C2E596A03564980098E6968A000000F0FAE296303CEA9680C8E596E0C2E596A0356498203CEA96801870986098E6960900000060153297D0B06298D0B06298E0C2E59688FFFFFF0900000040117198090000000037649890FC5A97F0F7E2966015329788FFFFFF000000007CDB429820DD42980004000080366498010000000037649888FFFFFF90FC5A9788FFFFFF0000000082FFFFFFF0DA5C9990FC5A97C0F7E29690F7E296
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68700 0000000087FFFFFFA00F639860F7E29690F7E29640153297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFF60F7E29688FFFFFF7887A69860F7E29600F7E29630F7E296FCDE0F9480020000003764980000000000F7E29688FFFFFF50A4ED968A0000000700000060A4ED96E0A806AE40B06298F097E6960037649820988F9803020000603F67980100000040B0629888FFFFFFF097E69685FFFFFF0000403F0000803E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0A806AEC05ECFB65089A6980100000081FFFFFFA888A6981489A6981474F598603F679800000000000000007888A6982C88A69838978F98588B5399E0A806AE001E899A9499A698000000000000000000000000010000007C90A698E0A806AE0001000000000000B0DD0F9400000000603F6798088DA698020000000100000000000000000000000100000081FFFFFF
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68880 0000000000000000E08CA698F6FFFFFFECA806AE01000000E0A806AEA888A6980000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000005089A698E0A806AE78EB5C9900826A98000000007006DF951489A698CE83AA1A00000000E0A806AE5089A6981889A698603F679800826A98000000007006DF953C89A6982C151399000000000000000000000000C05ECFB601000000E0A806AE108DA6984889A698C48CA6982416139952106D96FB116D96108DA69801000000E8BC52990100000000826A984889A6980000000000126D9602000000020000000100000000000000806A52995C00000006000000000000008098A6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68A00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086D9600000000000000000100000002000000A014329700836A9825EBBBAD0000000000000000CE83AA1A00000000C05ECFB600000000E0A806AEC86A0599E08AA6985C8EA698A81613990000000000000000008FA698000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68B80 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CE83AA1AC05ECFB6008DA698E0A806AEB08DA698108DA6987006DF956C8DA698E41A139900000000000000000000000040B06298108DA69801000000F099A698F6FFFFFFECA806AE00000000E0A806AE008DA6980300000008000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68D00 603F679888FFFFFF40B0629888FFFFFFF097E69685FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000CE83AA1A04000000E0A806AEC08DA698B08DA698B88DA698AC8DA69882FFFFFF6806DF959C8DA698380503996806DF95B88DA69840B0629888FFFFFF208EA698308EA698108FA69801000000C88DA69800000000FC8DA698209B2499B88DA698000000001800000040B06298603F679888FFFFFF0000000082FFFFFF010000006806DF950000000082FFFFFFE0A806AE000000006CC73D99308EA698208EA69800834E9A98854E9AE0A806AE108FA6986CC73D996C8EA698B8AA1B99308EA698848EA698070000004F000000AC346496EC99409600000000E099409640B0629888FFFFFFE0A806AE00000000F097E69685FFFFFFE0A806AE00000000808EA69818203F990D9A4096A08EA698108FA698908EA698E0A806AE848EA6982200000000834E9AD48EA698EC1A1D99E4883D99508C3D99588B539922000000
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A68E80 EC994096D441219600000000A48EA69822000000000000002890A69800000000BC8EA69814E5DA98588FA6982890A69818715499208FA6980000000001000000108FA698008FA69822000000E0A806AE6490A698284420995806DF9500000000E0A806AEF08EA69802000000388FA69840FC5A97588FA69850F2E29688FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0A806AE010000008890A6989890A698010000005806DF950700000007000000010000009096E69600000000E0A806AE0000000000000000060000003C7154993C715499060000001871549900000000FFFFFFFF000000006006DF95220000009896E696070000000000000001000000180070985098289681FFFFFFC48FA698E05A0D99070000009096E696E0A806AE0000000010007098D08FA6980490A698E89C0D990000000000000000000000000CB20F943890A6980100000000000000D0F6E296E01B71989096E69600000000FFFFFFFF5098289681FFFFFF
08-26 15:00:13.647  6891  6891 F google-breakpad: S 98A69000 A090A698B0B20F94F890A6981490A6986090A698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFF9096E69685FFFFFF1000709885FFFFFF000000006049669888FFFFFF88DC8D9B00000000FFFFFFFFC098289681FFFFFFA090A698385F9098000000007490A6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFF9096E69685FFFFFFFC90A698C098289688DC8D9B010500009096E69685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C9340020000000000005000000030BD6298F0D9719885FFFFFF2C91A6984491A698000000002091A6988C6990988201000080866698010000000000000082FFFFFF9096E69685FFFFFFCC91A698C0F6A8962CACF097010A00009096E69685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69180 0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFF182DE6920200000000000000F891A6988C69909802020000C04C669802000000A0C6659888FFFFFF9096E69685FFFFFF2015329788FFFFFF6C92A69880673D98EC6DE69281060000F0D9719885FFFFFF9096E69685FFFFFFA0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300005092A6980000000083FFFFFF680000006081E3959896E69601000000300000006081E395000000009092A6988C6990988201000060241296010000000000000082FFFFFF9096E69685FFFFFF1493A69870603D982C66E692810700009096E69685FFFFFF0000000082FFFFFF6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3093A6982893A6982093A6989493A698780000006081E395
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69300 0000000016AC6F96588B5399E0A806AE000000003893A6988C69909882010000A0241296010000000000000082FFFFFF9096E69685FFFFFFA493A69898D63C980C5CE692010600009096E69685FFFFFF0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000B093A698C893A69804000000600000006081E395E0A63C9881FFFFFF3494A698F81F909800000000C893A6988C69909882010000C0241296010000000000000082FFFFFF9096E69685FFFFFF3494A69898D03C981053E692010600009096E69685FFFFFF0000000082FFFFFFC024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000070F6E29600000000E058509660000000A0F6E29604000000182DE6924494A69878B4EF98040000005894A6988C69909882010000E0241296010000000000000082FFFFFF70F6E29688FFFFFFD494A69890A53C98244AE6920107000070F6E29688FFFFFF0000000082FFFFFFE024129688FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69480 0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFF9096E69685FFFFFF00000000C894A698C494A69888FFFFFF7000000040F6E29640C2E596849102990000403F0000000004000000F894A6988C699098820100006025129601000000706FA79788FFFFFFB0F2E29688FFFFFF5495A69860FB3B989043E69201050000B0F2E29688FFFFFF706FA79788FFFFFF6025129688FFFFFFC0D3719885FFFFFF40C2E596010000008495A6989C95A69850000000E0D542940200000070C87D9A7495A698C8B3EF98000000008895A698DC4D8F9B8202000020D57197030000000000000082FFFFFFB0F2E29688FFFFFF0000000081FFFFFF40C2E59688FFFFFF2496A698D0570595E8320D940109000040C2E59688FFFFFF0000000081FFFFFFB0F2E29688FFFFFF0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF2011C99588FFFFFF0000000082FFFFFF0900000081FFFFFF40C2E59688FFFFFF90C2E59600000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69600 5496A698C0D662989000000020C06298182DE6920200000070F23B9881FFFFFF000000004896A6988C69909882010000B00263980100000040C2E59688FFFFFF20D5719788FFFFFFCC96A69828F73B98003DE6928107000020D5719788FFFFFF40C2E59688FFFFFFB002639888FFF,FFF90C2E59688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFF90C2E59688FFFFFF0000000082FFFFFFF096A698385F909800000000B496A69878000000E0D54294000000005433E692420300000300000000000000F896A6988C6990980202000040D571970200000030F70D9688FFFFFF40FC5A9788FFFFFF40C2E59688FFFFFF6497A69878EC48972038E6920106000040C2E59688FFFFFF40FC5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF0000000082FFFFFF2897A698A0356498C097E6964011719860000000E0D5429485FFFFFF2C442C9385FFFFFF6497A6980000000000376498384F2C93800B000080D57197020000000037649888FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69780 40FC5A9788FFFFFF409CE59688FFFFFFD097E69685FFFFFFF0C1E59688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFD0F3E296409CE596A035649850A4ED968A00000080F5E296D097E696F0C1E596409CE596A0356498C097E69680187098B0A4ED9609000000C0143297D0B06298D0B06298409CE59688FFFFFF0900000040117198090000000037649840FC5A9780F2E296C014329788FFFFFF000000007CDB429820DD42980004000080366498010000000037649888FFFFFF40FC5A9788FFFFFF0000000082FFFFFFF0DA5C9940FC5A9750F2E29620F2E2960000000087FFFFFFA00F6398F0F1E29620F2E296A0143297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFFF0F1E29688FFFFFFE098A698F0F1E29690F1E296C0F1E296FCDE0F9480020000003764980000000090F1E29688FFFFFF50A1E7968A0000000700000060A1E796E0A806AE40B0629840A4ED960037649820988F9803020000603F679801000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69900 40B0629888FFFFFF40A4ED9685FFFFFF0000403F0000803E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0A806AEC05ECFB6B89AA6980100000081FFFFFF109AA6987C9AA6981474F598603F67980000000000000000E099A6989499A69838978F98588B5399E0A806AE001E899AFCAAA69800000000000000000000000001000000E4A1A698E0A806AE0001A69800000000B0DD0F9400000000603F6798709EA6980200000001000000049AA698000000000100000081FFFFFF009CA69800000005489EA698F6FFFFFFECA806AE01000000E0A806AE109AA6980000000008000000349AA698145419990000800020000000B89CA698F87B6A980000100000000000849AA69801000000B89AA698E0A806AE78EB5C9900826A98000000005006DF957C9AA698CE83AA1A00000000E0A806AEB89AA698809AA698603F679800826A98000000005006DF95A49AA6982C151399
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69A80 00000000B4B81A9902000000C05ECFB601000000E0A806AE789EA698B09AA6982C9EA69824161399BC9AA6980CB91A99789EA69801000000E8BC52990100000000826A98B09AA69800000000004B19990200000038000000C45090942C4A1999119BA69838000000B09EA698119CA6983C000000000000E0C05ECFB6B89CA698509BA698F87B6A98F0FB5A970000000094509094F0671999D85090942C9BA698010000003C9BA6983C9BA698FFFFFF00010000004C9BA69808000000DC509094B05090947C79E6928879E692203019996079E692F0FFFFFFFFFFFFFF00000000B89CA69844AF6F6B08E6339A005090940080879AD09EA69808E6339A3806DF950080879AB89CA6980CE3CFB600E6339A9415CFB608E6339A3806DF95EB32CDB604000000649CA698208ED394E89BA698DC9BA69848B8F8987C79E6928C79E69278ADC69478ADC694EC9BA698D09EA6980100000078ADC694E0A806AEB89CA6980100000078ADC694E0A806AEF0FB5A97F0FB5A97000000000C9CA6982C73E598
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69C00 E8A3A698B89CA6981C9CA698241BF49800000000C05ECFB6A4A7A6985CEDF89800A0C694BC703E990D0000007C841394030000000000000000000000005BF99800A0C69464733E9968622C93B89CA6980100000000A0C694709CA698F87B6A98F0FB5A97287B519941B06298584E2C9310000000280000001C0000002C0000000000000078ADC6940D0000007C84139403000000000000000D000000CC2A19990200000001000000B89CA698000000000000000000000000C89CA6980000000000000000000000000000000000000000E09CA6980000000000000000000000000000000000000000F89CA6980000000000000000000000000000000000000000109DA698000000000000000000000000209DA698000000000100000000000000309DA6980000000000000000000000000800000000000000489DA698000000000800000000000000589DA698000000000800000000000000689DA698000000000800000000000000789DA698000000000000000000000000889DA69800000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69D80 0000000005000000989DA69800000000000000000200000002000000000000003806DF950100000001000000000000000000000000000000C89DA6980000000000000000000000002000000000000000E09DA698000000002000000000000000019DA69800000000F89DA698050000000100000005000000089EA6980200000001000000D0000000189EA698CE83AA1AC05ECFB6689EA698E0A806AE189FA698789EA6985006DF95D49EA698E41A1399409EA698000000000100000040B06298789EA6980100000058ABA698F6FFFFFFECA806AE00000000E0A806AE689EA6980300000008000000603F679888FFFFFF40B0629888FFFFFF40A4ED9685FFFFFF2000000000000000019EA6980000000070DA5099B0509094015490940000909470DA5099B050909401549094CE83AA1A04000000E0A806AE289FA698189FA698209FA698149FA69882FFFFFF4806DF95049FA698380503994806DF95209FA69840B0629888FFFFFF889FA698989FA69878A0A69801000000309FA69800000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A69F00 649FA698209B2499209FA698080000001800000040B06298603F679888FFFFFF0000000082FFFFFF010000004806DF950000000082FFFFFFE0A806AE000000006CC73D99989FA698889FA69800834E9A98854E9AE0A806AE78A0A6986CC73D99D49FA698B8AA1B99989FA698EC9FA698070000004F000000AC3464969C994096000000009099409640B0629888FFFFFFE0A806AE0000000040A4ED9685FFFFFFE0A806AE00000000E89FA69818203F99BD99409608A0A69878A0A698F89FA698E0A806AEEC9FA6982200000000834E9A3CA0A698EC1A1D99E4883D99508C3D99588B5399220000009C9940968C412196000000000CA0A698220000000000000090A1A6980000000024A0A69814E5DA98C0A0A69890A1A6981871549988A0A698000000000100000078A0A69868A0A69822000000E0A806AECCA1A698284420993806DF95F80DE4930000000000100000F80DE493A0A0A698C0A0A698C0A0A698F80DE493A4537DB40000000082FFFFFF00000000000100002200000000000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A080 00000000000000000012C494E0A806AE01000000F0A1A69800A2A69801FFFFFF3806DF95070000000700000001FFFFFFE0A2ED9600FFFFFFE0A806AEFFFFFFFFF80DE493060000003C7154993C715499060000001871549900000000FFFFFFFF000000004006DF9522000000E8A2ED96070000000000000001000000180070985098289681FFFFFF2CA1A698E05A0D9907000000E0A2ED96E0A806AE000000001000709838A1A6986CA1A698E89C0D99F4E2CFB64B45CCB6B80838980CB20F94A0A1A69801000000C804649660F1E296E01B7198E0A2ED9600000000FFFFFFFF5098289681FFFFFF08A2A698B0B20F9460A2A6987CA1A698C8A1A698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFFE0A2ED9685FFFFFF1000709885FFFFFFA4537DB46049669888FFFFFF88DC8D9B00000000FFFFFFFFC098289681FFFFFF08A2A698385F909800000000DCA1A6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A200 E0A2ED9685FFFFFF64A2A698C098289688DC8D9B01050000E0A2ED9685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C9340020000000000005000000030BD6298F0D9719885FFFFFF94A2A698ACA2A6980000000088A2A6988C6990988201000080866698010000000000000082FFFFFFE0A2ED9685FFFFFF34A3A698C0F6A8962CACF097010A0000E0A2ED9685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFF182DE692020000000000000060A3A6988C69909802020000C04C669802000000A0C6659888FFFFFFE0A2ED9685FFFFFF8014329788FFFFFFD4A3A69880673D98EC6DE69281060000F0D9719885FFFFFFE0A2ED9685FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A380 A0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000B8A3A6980000000083FFFFFF680000006081E395E8A2ED9601000000300000006081E39500000000F8A3A6988C6990988201000060241296010000000000000082FFFFFFE0A2ED9685FFFFFF7CA4A69870603D982C66E69281070000E0A2ED9685FFFFFF0000000082FFFFFF6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF98A4A69890A4A69888A4A698FCA4A698780000006081E3950000000016AC6F96588B5399E0A806AE00000000A0A4A6988C69909882010000A0241296010000000000000082FFFFFFE0A2ED9685FFFFFF0CA5A69898D63C980C5CE69201060000E0A2ED9685FFFFFF0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000018A5A69830A5A69804000000600000006081E395E0A63C9881FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A500 9CA5A698F81F90980000000030A5A6988C69909882010000C0241296010000000000000082FFFFFFE0A2ED9685FFFFFF9CA5A69898D03C981053E69201060000E0A2ED9685FFFFFF0000000082FFFFFFC024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000F1E29600000000E05850966000000030F1E29604000000182DE692ACA5A69878B4EF9804000000C0A5A6988C69909882010000E0241296010000000000000082FFFFFF00F1E29688FFFFFF3CA6A69890A53C98244AE6920107000000F1E29688FFFFFF0000000082FFFFFFE024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFFE0A2ED9685FFFFFF0000000030A6A6982CA6A69888FFFFFF70000000D0F0E296A09BE596849102990000403F000000000400000060A6A6988C699098820100006025129601000000706FA79788FFFFFF302DE09688FFFFFFBCA6A69860FB3B989043E69201050000302DE09688FFFFFF706FA79788FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A680 6025129688FFFFFFC0D3719885FFFFFFA09BE59601000000ECA6A69804A7A69850000000E0D542940200000070C87D9ADCA6A698C8B3EF9800000000F0A6A698DC4D8F9B8202000020D57197030000000000000082FFFFFF302DE09688FFFFFF0000000081FFFFFFA09BE59688FFFFFF8CA7A698D0570595E8320D9401090000A09BE59688FFFFFF0000000081FFFFFF302DE09688FFFFFF0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFB010C99588FFFFFF0000000082FFFFFF0900000081FFFFFFA09BE59688FFFFFFF09BE59600000000BCA7A698C0D662989000000020C06298182DE6920200000070F23B9881FFFFFF00000000B0A7A6988C69909882010000B002639801000000A09BE59688FFFFFF20D5719788FFFFFF34A8A69828F73B98003DE6928107000020D5719788FFFFFFA09BE59688FFFFFFB002639888FFFFFFF09BE59688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFFF09BE59688FFFFFF
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A800 0000000082FFFFFF58A8A698385F9098000000001CA8A69878000000E0D54294000000005433E69242030000030000000000000060A8A6988C6990980202000040D571970200000030F70D9688FFFFFFF0FB5A9788FFFFFFA09BE59688FFFFFFCCA8A69878EC48972038E69201060000A09BE59688FFFFFFF0FB5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF0000000082FFFFFF90A8A698A035649810A4ED964011719860000000E0D5429485FFFFFF2C442C9385FFFFFFCCA8A6980000000000376498384F2C93800B000080D57197020000000037649888FFFFFFF0FB5A9788FFFFFFB095E59688FFFFFF20A4ED9685FFFFFF509BE59688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF502EE096B095E596A035649850A1E7968A00000010F0E29620A4ED96509BE596B095E596A035649810A4ED9680187098B0A1E7960900000020143297D0B06298D0B06298B095E59688FFFFFF09000000401171980900000000376498
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6A980 F0FB5A97002DE0962014329788FFFFFF000000007CDB429820DD42980004000080366498010000000037649888FFFFFFF0FB5A9788FFFFFF0000000082FFFFFFF0DA5C99F0FB5A97D02CE096A02CE0960000000087FFFFFFA00F6398702CE096A02CE09600143297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFF702CE09688FFFFFF00000000702CE096102CE096402CE096FCDE0F94800200000037649800000000102CE09688FFFFFF10B4A6984800000054AAA69820B2A6984800000040B0629840A1E7960037649820988F9803020000603F67980100000040B0629888FFFFFF40A1E79685FFFFFF0000403F0000803E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0A806AEC05ECFB620ACA6980100000081FFFFFF78ABA698E4ABA6981474F598603F6798000000000000000048ABA698FCAAA69838978F98588B5399E0A806AE
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6AB00 001E899A64BCA698000000000000000000000000010000004CB3A698E0A806AE0001599400000000B0DD0F9400000000603F6798D8AFA698020000000100000070491B94000000000100000081FFFFFF0080879A986CE693B0AFA698F6FFFFFFECA806AE01000000E0A806AE78ABA69800000000080000002060599400605994C0491B949A010000B03F1B940060599470605994180400004881F6970100000020ACA698E0A806AE78EB5C9900826A98000000003006DF95E4ABA698CE83AA1A00000000E0A806AE20ACA698E8ABA698603F679800826A98000000003006DF950CACA6982C15139900000000F88F139400000000C05ECFB601000000E0A806AEE0AFA69818ACA69894AFA6982416139952106D96FB116D96E0AFA69801000000E8BC52990100000000826A9818ACA6980000000000126D9602000000020000000100000000000000806A52995C000000060000000000000050BBA698000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6AC80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086D96000000000000000001000000020000006013329700836A9825EBBBAD0000000000000000CE83AA1A00000000C05ECFB600000000E0A806AEC86A0599B0ADA6982CB1A698A81613990000000000000000D0B1A69800000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6AE00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000009000DC93FC0CDC930000000000800000FC0CDC932744CCB650AFA69810AFA698FC0CDC93A4537DB4A8537DB4FC0CDC93000000005346CCB6B808389801000000FC0C0495FFFFFFFFE8114497FFFFFFFF24036096FFFFFFFF40119094FFFFFFFF74043494FFFFFFFFC405E093FFFFFFFF4C0E209601000000FC0CDC9301000000A8537DB4FFFFFFFF18060094FFFFFFFF1407D093FFFFFFFF1407D093CE83AA1AC05ECFB6D0AFA698
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6AF80 E0A806AE80B0A698E0AFA6983006DF953CB0A698E41A139900000000000000000000000040B06298E0AFA69801000000C0BCA698F6FFFFFFECA806AE00000000E0A806AED0AFA6980300000008000000603F679888FFFFFF40B0629888FFFFFF40A1E79685FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000CE83AA1A04000000E0A806AE90B0A69880B0A69888B0A6987CB0A69882FFFFFF2806DF956CB0A698380503992806DF9588B0A69840B0629888FFFFFFF0B0A69800B1A698E0B1A6980100000098B0A69800000000CCB0A698209B249988B0A698000000001800000040B06298603F679888FFFFFF0000000082FFFFFF010000002806DF950000000082FFFFFFE0A806AE000000006CC73D9900B1A698F0B0A69800834E9A98854E9AE0A806AEE0B1A6986CC73D993CB1A698B8AA1B9900B1A69854B1A698070000004F000000AC3464964C994096000000004099409640B0629888FFFFFFE0A806AE00000000
08-26 15:00:13.657  6891  6891 F google-breakpad: S 98A6B100 40A1E79685FFFFFFE0A806AE0000000050B1A69818203F996D99409670B1A698E0B1A69860B1A698E0A806AE54B1A6982200000000834E9AA4B1A698EC1A1D99E4883D99508C3D99588B5399220000004C9940965C41219660E36A9674B1A6982200000000000000F8B2A698000000008CB1A69814E5DA9828B2A698F8B2A69818715499F0B1A6980000000001000000E0B1A698D0B1A69822000000E0A806AE34B3A698284420991806DF95000000003860DE93000000000000000008B2A69824B2A69828B2A69840B2A698000000000000000082FFFFFF00000000000100002200000000000000000000000000000000B2A698E0A806AE0100000058B3A69868B3A698011000001806DF95070000000700000001000000D04FE49600000020E0A806AED4ABA698986CE693060000003C7154993C715499060000001871549900000000FFFFFFFF000000001006DF9522000000D84FE49607000000000000000100000018007098509828960100000094B2A698E05A0D9907000000D04FE496
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6B280 E0A806AE0000000010007098A0B2A698D4B2A698E89C0D9960681494B8681494106914940CB20F9408B3A69801000000706A1494E02BE096E01B7198D04FE49600000000FFFFFFFF509828960100000070B3A698B0B20F94C8B3A698E4B2A69830B3A698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFFD04FE49685FFFFFF1000709885FFFFFFB07214946049669888FFFFFF88DC8D9B00000000FFFFFFFFC09828960100000070B3A698385F90980000000044B3A6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFFD04FE49685FFFFFFCCB3A698C098289688DC8D9B01050000D04FE49685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C9340020000000000005000000030BD6298F0D9719885FFFFFFFCB3A69814B4A69800000000F0B3A6988C6990988201000080866698010000000000000082FFFFFFD04FE49685FFFFFF9CB4A698C0F6A8962CACF097010A0000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6B400 D04FE49685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFF902AE0960302000000000000C8B4A6988C69909802020000C04C669802000000A0C6659888FFFFFFD04FE49685FFFFFFE013329788FFFFFF3CB5A69880673D98EC6DE69281060000F0D9719885FFFFFFD04FE49685FFFFFFA0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000020B5A6980000000083FFFFFF680000006081E395D84FE49601000000300000006081E3950000000060B5A6988C6990988201000060241296010000000000000082FFFFFFD04FE49685FFFFFFE4B5A69870603D982C66E69281070000D04FE49685FFFFFF0000000082FFFFFF
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6B580 6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00B6A698F8B5A698F0B5A69864B6A698780000006081E3950000000016AC6F96588B5399E0A806AE0000000008B6A6988C69909882010000A0241296010000000000000082FFFFFFD04FE49685FFFFFF74B6A69898D63C980C5CE69201060000D04FE49685FFFFFF0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000080B6A69898B6A69804000000600000006081E395E0A63C980100000004B7A698F81F90980000000098B6A6988C69909882010000C0241296010000000000000082FFFFFFD04FE49685FFFFFF04B7A69898D03C981053E69201060000D04FE49685FFFFFF0000000082FFFFFFC024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000802BE09600000000E058509660000000B02BE09604000000902AE09614B7A69878B4EF98
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6B700 0400000028B7A6988C69909882010000E0241296010000000000000082FFFFFF802BE09688FFFFFFA4B7A69890A53C98244AE69201070000802BE09688FFFFFF0000000082FFFFFFE024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFFD04FE49685FFFFFF0000000098B7A69894B7A69888FFFFFF70000000502BE0961095E596849102990000403F0000000004000000C8B7A6988C699098820100006025129601000000706FA79788FFFFFFC027E09688FFFFFF24B8A69860FB3B989043E69201050000C027E09688FFFFFF706FA79788FFFFFF6025129688FFFFFFC0D3719885FFFFFF1095E5960100000054B8A6986CB8A69850000000E0D542940302000070C87D9A44B8A698C8B3EF980000000058B8A698DC4D8F9B8202000020D57197030000000000000082FFFFFFC027E09688FFFFFF0000000081FFFFFF1095E59688FFFFFFF4B8A698D0570595E8320D94010900001095E59688FFFFFF0000000081FFFFFFC027E09688FFFFFF
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6B880 0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF4010C99588FFFFFF0000000082FFFFFF0900000081FFFFFF1095E59688FFFFFF6095E5960000000024B9A698C0D662989000000020C06298902AE0960302000070F23B98010000000000000018B9A6988C69909882010000B0026398010000001095E59688FFFFFF20D5719788FFFFFF9CB9A69828F73B98003DE6928107000020D5719788FFFFFF1095E59688FFFFFFB002639888FFFFFF6095E59688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFF6095E59688FFFFFF0000000082FFFFFFC0B9A698385F90980000000084B9A69878000000E0D54294000000005433E692420300000300000000000000C8B9A6988C6990980202000040D571970200000030F70D9688FFFFFFA0FB5A9788FFFFFF1095E59688FFFFFF34BAA69878EC48972038E692010600001095E59688FFFFFFA0FB5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6BA00 0000000082FFFFFFCC8190987CBAA69880BAA6980000000060000000E0D5429468BAA69800000000902AE096030200000000000060BAA6988C6990980202000080D57197020000000037649888FFFFFFA0FB5A9788FFFFFF10FFE69688FFFFFFFCBAA69858F55798FC148D9B0109000010FFE69688FFFFFFA0FB5A9788FFFFFF0037649888FFFFFF80D5719788FFFFFF0000000082FFFFFF0000000082FFFFFF20A1E79685FFFFFFC094E59688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF8013329788FFFFFF902AE09688FFFFFF603F679801000000900000009027E09604BBA698F4BAA69808D55C9900000000040000004CBDA69820DD42980004000080366498010000000037649888FFFFFFA0FB5A9788FFFFFF0000000082FFFFFFF0DA5C99A0FB5A976027E0963027E0960000000087FFFFFFA00F63980027E0963027E09660133297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFF0027E09688FFFFFFB0BBA6980027E096
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6BB80 A026E096D026E096FCDE0F94800200000037649800000000A026E09688FFFFFF500DE7968A00000007000000600DE796E0A806AE40B06298E00EEE960037649820988F9803020000603F67980100000040B0629888FFFFFFE00EEE9685FFFFFF0000403F0000803E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0A806AEC05ECFB688BDA6980100000081FFFFFFE0BCA6984CBDA6981474F598603F67980000000000000000B0BCA69864BCA69838978F98588B5399E0A806AE001E899ACCCDA69800000000000000000000000001000000B4C4A698E0A806AE0001000000000000B0DD0F9400000000603F679840C1A698020000000100000000000000000000000100000081FFFFFF000000000000000018C1A698F6FFFFFFECA806AE01000000E0A806AEE0BCA69800000000080000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6BD00 000000000100000088BDA698E0A806AE78EB5C9900826A98000000001006DF954CBDA698CE83AA1A00000000E0A806AE88BDA69850BDA698603F679800826A98000000001006DF9574BDA6982C151399000000000000000000000000C05ECFB601000000E0A806AE48C1A69880BDA698FCC0A6982416139952106D96FB116D9648C1A69801000000E8BC52990100000000826A9880BDA6980000000000126D9602000000020000000100000000000000806A52995C0000000600000000000000B8CCA6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6BE80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086D9600000000000000000100000002000000C012329700836A9825EBBBAD0000000000000000CE83AA1A00000000C05ECFB600000000E0A806AEC86A059918BFA69894C2A698A8161399000000000000000038C3A698000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C000 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CE83AA1AC05ECFB638C1A698E0A806AEE8C1A69848C1A6981006DF95A4C1A698E41A139900000000000000000000000040B0629848C1A6980100000028CEA698F6FFFFFFECA806AE00000000E0A806AE38C1A6980300000008000000603F679888FFFFFF40B0629888FFFFFFE00EEE9685FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000CE83AA1A
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C180 04000000E0A806AEF8C1A698E8C1A698F0C1A698E4C1A69882FFFFFF0806DF95D4C1A698380503990806DF95F0C1A69840B0629888FFFFFF58C2A69868C2A69848C3A6980100000000C2A6980000000034C2A698209B2499F0C1A698000000001800000040B06298603F679888FFFFFF0000000082FFFFFF010000000806DF950000000082FFFFFFE0A806AE000000006CC73D9968C2A69858C2A69800834E9A98854E9AE0A806AE48C3A6986CC73D99A4C2A698B8AA1B9968C2A698BCC2A698070000004F000000AC346496FC98409600000000F098409640B0629888FFFFFFE0A806AE00000000E00EEE9685FFFFFFE0A806AE00000000B8C2A69818203F991D994096D8C2A69848C3A698C8C2A698E0A806AEBCC2A6982200000000834E9A0CC3A698EC1A1D99E4883D99508C3D99588B539922000000FC9840961441219600000000DCC2A698220000000000000060C4A69800000000F4C2A69814E5DA9890C3A69860C4A6981871549958C3A698000000000100000048C3A69838C3A698
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C300 22000000E0A806AE9CC4A69828442099F805DF9500000000E0A806AE28C3A6980200000070C3A69850FB5A9790C3A698F021E09688FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0A806AE01000000C0C4A698D0C4A69801000000F805DF95070000000700000001000000800DEE9600000000E0A806AE0000000000000000060000003C7154993C715499060000001871549900000000FFFFFFFF000000000006DF9522000000880DEE96070000000000000001000000180070985098289601000000FCC3A698E05A0D9907000000800DEE96E0A806AE000000001000709808C4A6983CC4A698E89C0D99F4E2CFB64B45CCB6B80838980CB20F9470C4A69801000000C80464967026E096E01B7198800DEE9600000000FFFFFFFF5098289601000000D8C4A698B0B20F9430C5A6984CC4A69898C4A698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFF800DEE9685FFFFFF1000709885FFFFFFA4537DB460496698
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C480 88FFFFFF88DC8D9B00000000FFFFFFFFC098289601000000D8C4A698385F909800000000ACC4A6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFF800DEE9685FFFFFF34C5A698C098289688DC8D9B01050000800DEE9685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C9340020000000000005000000030BD6298F0D9719885FFFFFF64C5A6987CC5A6980000000058C5A6988C6990988201000080866698010000000000000082FFFFFF800DEE9685FFFFFF04C6A698C0F6A8962CACF097010A0000800DEE9685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFF2025E09603020000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C600 0000000030C6A6988C69909802020000C04C669802000000A0C6659888FFFFFF800DEE9685FFFFFF4013329788FFFFFFA4C6A69880673D98EC6DE69281060000F0D9719885FFFFFF800DEE9685FFFFFFA0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000088C6A6980000000083FFFFFF680000006081E395880DEE9601000000300000006081E39500000000C8C6A6988C6990988201000060241296010000000000000082FFFFFF800DEE9685FFFFFF4CC7A69870603D982C66E69281070000800DEE9685FFFFFF0000000082FFFFFF6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF68C7A69860C7A69858C7A698CCC7A698780000006081E3950000000016AC6F96588B5399E0A806AE0000000070C7A6988C69909882010000A0241296010000000000000082FFFFFF800DEE9685FFFFFFDCC7A69898D63C980C5CE69201060000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C780 800DEE9685FFFFFF0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000E8C7A69800C8A69804000000600000006081E395E0A63C98010000006CC8A698F81F90980000000000C8A6988C69909882010000C0241296010000000000000082FFFFFF800DEE9685FFFFFF6CC8A69898D03C981053E69201060000800DEE9685FFFFFF0000000082FFFFFFC024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000001026E09600000000E0585096600000004026E096040000002025E0967CC8A69878B4EF980400000090C8A6988C69909882010000E0241296010000000000000082FFFFFF1026E09688FFFFFF0CC9A69890A53C98244AE692010700001026E09688FFFFFF0000000082FFFFFFE024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFF800DEE9685FFFFFF0000000000C9A698FCC8A69888FFFFFF70000000E025E09670FEE69684910299
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6C900 0000403F000000000400000030C9A6988C699098820100006025129601000000706FA79788FFFFFF5022E09688FFFFFF8CC9A69860FB3B989043E692010500005022E09688FFFFFF706FA79788FFFFFF6025129688FFFFFFC0D3719885FFFFFF70FEE69601000000BCC9A698D4C9A69850000000E0D542940302000070C87D9AACC9A698C8B3EF9800000000C0C9A698DC4D8F9B8202000020D57197030000000000000082FFFFFF5022E09688FFFFFF0000000081FFFFFF70FEE69688FFFFFF5CCAA698D0570595E8320D940109000070FEE69688FFFFFF0000000081FFFFFF5022E09688FFFFFF0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF907FE29588FFFFFF0000000082FFFFFF0900000081FFFFFF70FEE69688FFFFFFC0FEE696000000008CCAA698C0D662989000000020C062982025E0960302000070F23B98010000000000000080CAA6988C69909882010000B00263980100000070FEE69688FFFFFF20D5719788FFFFFF
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6CA80 04CBA69828F73B98003DE6928107000020D5719788FFFFFF70FEE69688FFFFFFB002639888FFFFFFC0FEE69688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFFC0FEE69688FFFFFF0000000082FFFFFF28CBA698385F909800000000ECCAA69878000000E0D54294000000005433E69242030000030000000000000030CBA6988C6990980202000040D571970200000030F70D9688FFFFFF50FB5A9788FFFFFF70FEE69688FFFFFF9CCBA69878EC48972038E6920106000070FEE69688FFFFFF50FB5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF0000000082FFFFFFCC819098E4CBA698E8CBA6980000000060000000E0D54294D0CBA698000000002025E0960302000000000000C8CBA6988C6990980202000080D57197020000000037649888FFFFFF50FB5A9788FFFFFF80F8E69688FFFFFF64CCA69858F55798FC148D9B0109000080F8E69688FFFFFF50FB5A9788FFFFFF0037649888FFFFFF80D5719788FFFFFF0000000082FFFFFF
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6CC00 0000000082FFFFFFC00EEE9685FFFFFF20FEE69688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFE012329788FFFFFF2025E09688FFFFFF603F679801000000900000002022E0966CCCA6985CCCA69808D55C990000000004000000B4CEA69820DD42980004000080366498010000000037649888FFFFFF50FB5A9788FFFFFF0000000082FFFFFFF0DA5C9950FB5A97F021E096C021E0960000000087FFFFFFA00F63989021E096C021E096C0123297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFF9021E09688FFFFFF18CDA6989021E0963021E0966021E096FCDE0F948002000000376498000000003021E09688FFFFFF60CCE1968A0000000700000070CCE196E0A806AE40B06298400DE7960037649820988F9803020000603F67980100000040B0629888FFFFFF400DE79685FFFFFF0000403F0000803E000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6CD80 00000000000000000000000000000000E0A806AEC05ECFB6F0CEA6980100000081FFFFFF48CEA698B4CEA6981474F598603F6798000000000000000018CEA698CCCDA69838978F98588B5399E0A806AE001E899A34DFA698000000000000000000000000010000001CD6A698E0A806AE0001000000000000B0DD0F9400000000603F6798A8D2A698020000000100000000000000000000000100000081FFFFFF000000000000000080D2A698F6FFFFFFECA806AE01000000E0A806AE48CEA698000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000F0CEA698E0A806AE78EB5C9900826A9800000000E805DF95B4CEA698CE83AA1A00000000E0A806AEF0CEA698B8CEA698603F679800826A9800000000E805DF95DCCEA6982C151399000000000000000000000000C05ECFB601000000E0A806AEB0D2A698E8CEA69864D2A6982416139952106D96FB116D96B0D2A69801000000E8BC52990100000000826A98E8CEA698
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6CF00 0000000000126D9602000000020000000100000000000000806A52995C000000060000000000000020DEA6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000086D96000000000000000001000000020000002012329700836A9825EBBBAD0000000000000000CE83AA1A00000000C05ECFB600000000E0A806AEC86A059980D0A698FCD3A698A81613990000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D080 A0D4A6980000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D200 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000CE83AA1AC05ECFB6A0D2A698E0A806AE50D3A698B0D2A698E805DF950CD3A698E41A139900000000000000000000000040B06298B0D2A6980100000090DFA698F6FFFFFFECA806AE00000000E0A806AEA0D2A6980300000008000000603F679888FFFFFF40B0629888FFFFFF400DE79685FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000004000000CE83AA1A04000000E0A806AE60D3A69850D3A69858D3A6984CD3A69882FFFFFFE005DF953CD3A69838050399E005DF9558D3A69840B0629888FFFFFFC0D3A698D0D3A698B0D4A6980100000068D3A698000000009CD3A698209B249958D3A698000000001800000040B06298603F679888FFFFFF0000000082FFFFFF01000000E005DF950000000082FFFFFFE0A806AE000000006CC73D99D0D3A698
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D380 C0D3A69800834E9A98854E9AE0A806AEB0D4A6986CC73D990CD4A698B8AA1B99D0D3A69824D4A698070000004F000000AC346496AC98409600000000A098409640B0629888FFFFFFE0A806AE00000000400DE79685FFFFFFE0A806AE0000000020D4A69818203F99CD98409640D4A698B0D4A69830D4A698E0A806AE24D4A6982200000000834E9A74D4A698EC1A1D99E4883D99508C3D99588B539922000000AC984096E44021960000000044D4A6982200000000000000C8D5A698000000005CD4A69814E5DA98F8D4A698C8D5A69818715499C0D4A6980000000001000000B0D4A698A0D4A69822000000E0A806AE04D6A69828442099C805DF9500000000E0A806AE90D4A69802000000D8D4A69800FB5A97F8D4A69870EC319788FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000E0A806AE0100000028D6A69838D6A69801000000C805DF95070000000700000001000000E00BE79600000000E0A806AE000000000000000006000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D500 3C7154993C715499060000001871549900000000FFFFFFFF00000000D805DF9522000000E80BE79607000000000000000100000018007098509828960100000064D5A698E05A0D9907000000E00BE796E0A806AE000000001000709870D5A698A4D5A698E89C0D99F4E2CFB64B45CCB6B80838980CB20F94D8D5A69801000000F00F64970021E096E01B7198E00BE79600000000FFFFFFFF509828960100000040D6A698B0B20F9498D6A698B4D5A69800D6A698000000000000000078B20F944003000001000000FFFFFFFF81FFFFFFE00BE79685FFFFFF1000709885FFFFFFA4537DB46049669888FFFFFF88DC8D9B00000000FFFFFFFFC09828960100000040D6A698385F90980000000014D6A6988C699098000000000000000088DC8D9B42020000010000006049669888FFFFFF00EA629888FFFFFFE00BE79685FFFFFF9CD6A698C098289688DC8D9B01050000E00BE79685FFFFFF00EA629888FFFFFF6049669888FFFFFF0000000082FFFFFF0000000028012C934002000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D680 5000000030BD6298F0D9719885FFFFFFCCD6A698E4D6A69800000000C0D6A6988C6990988201000080866698010000000000000082FFFFFFE00BE79685FFFFFF6CD7A698C0F6A8962CACF097010A0000E00BE79685FFFFFF0000000082FFFFFF8086669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007709885FFFFFFF0D9719885FFFFFF82FFFFFF58C85C99F0FB71981C2CE692A000000030BD62980000000083FFFFFFA0EF3197030200000000000098D7A6988C69909802020000C04C669802000000A0C6659888FFFFFFE00BE79685FFFFFFA012329788FFFFFF0CD8A69880673D98EC6DE69281060000F0D9719885FFFFFFE00BE79685FFFFFFA0C6659888FFFFFFC04C669888FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000F0D7A6980000000083FFFFFF680000006081E395E80BE79601000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D800 300000006081E3950000000030D8A6988C6990988201000060241296010000000000000082FFFFFFE00BE79685FFFFFFB4D8A69870603D982C66E69281070000E00BE79685FFFFFF0000000082FFFFFF6024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFD0D8A698C8D8A698C0D8A69834D9A698780000006081E3950000000016AC6F96588B5399E0A806AE00000000D8D8A6988C69909882010000A0241296010000000000000082FFFFFFE00BE79685FFFFFF44D9A69898D63C980C5CE69201060000E00BE79685FFFFFF0000000082FFFFFFA024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000050D9A69868D9A69804000000600000006081E395E0A63C9801000000D4D9A698F81F90980000000068D9A6988C69909882010000C0241296010000000000000082FFFFFFE00BE79685FFFFFFD4D9A69898D03C981053E69201060000E00BE79685FFFFFF
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6D980 0000000082FFFFFFC024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A020E09600000000E058509660000000D020E09604000000A0EF3197E4D9A69878B4EF9804000000F8D9A6988C69909882010000E0241296010000000000000082FFFFFFA020E09688FFFFFF74DAA69890A53C98244AE69201070000A020E09688FFFFFF0000000082FFFFFFE024129688FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013719885FFFFFFE00BE79685FFFFFF0000000068DAA69864DAA69888FFFFFF700000007020E096E0F7E696849102990000403F000000000400000098DAA6988C699098820100006025129601000000706FA79788FFFFFFD0EC319788FFFFFFF4DAA69860FB3B989043E69201050000D0EC319788FFFFFF706FA79788FFFFFF6025129688FFFFFFC0D3719885FFFFFFE0F7E6960100000024DBA6983CDBA69850000000E0D542940302000070C87D9A14DBA698C8B3EF980000000028DBA698DC4D8F9B82020000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6DB00 20D57197030000000000000082FFFFFFD0EC319788FFFFFF0000000081FFFFFFE0F7E69688FFFFFFC4DBA698D0570595E8320D9401090000E0F7E69688FFFFFF0000000081FFFFFFD0EC319788FFFFFF0000000082FFFFFF20D5719788FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF207FE29588FFFFFF0000000082FFFFFF0900000081FFFFFFE0F7E69688FFFFFF30F8E69600000000F4DBA698C0D662989000000020C06298A0EF31970302000070F23B980100000000000000E8DBA6988C69909882010000B002639801000000E0F7E69688FFFFFF20D5719788FFFFFF6CDCA69828F73B98003DE6928107000020D5719788FFFFFFE0F7E69688FFFFFFB002639888FFFFFF30F8E69688FFFFFFC0D6629888FFFFFFC0D0629888FFFFFF0000000082FFFFFF30F8E69688FFFFFF0000000082FFFFFF90DCA698385F90980000000054DCA69878000000E0D54294000000005433E69242030000030000000000000098DCA6988C6990980202000040D5719702000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6DC80 30F70D9688FFFFFF00FB5A9788FFFFFFE0F7E69688FFFFFF04DDA69878EC48972038E69201060000E0F7E69688FFFFFF00FB5A9788FFFFFF30F70D9688FFFFFF40D5719788FFFFFF0000000082FFFFFF0000000082FFFFFFCC8190984CDDA69850DDA6980000000060000000E0D5429438DDA69800000000A0EF3197030200000000000030DDA6988C6990980202000080D57197020000000037649888FFFFFF00FB5A9788FFFFFFF0F1E69688FFFFFFCCDDA69858F55798FC148D9B01090000F0F1E69688FFFFFF00FB5A9788FFFFFF0037649888FFFFFF80D5719788FFFFFF0000000082FFFFFF0000000082FFFFFF200DE79685FFFFFF90F7E69688FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF4012329788FFFFFFA0EF319788FFFFFF603F67980100000090000000A0EC3197D4DDA698C4DDA69808D55C9900000000040000001CE0A69820DD42980004000080366498010000000037649888FFFFFF00FB5A9788FFFFFF0000000082FFFFFFF0DA5C9900FB5A97
,08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6DE00 70EC319740EC31970000000087FFFFFFA00F639810EC319740EC319720123297E0BB0F9480020000C0366498020000000000000082FFFFFFA00F639888FFFFFF10EC319788FFFFFF80DEA69810EC3197B0EB3197E0EB3197FCDE0F94800200000037649800000000B0EB319788FFFFFF205C3F978A00000007000000305C3F97E0A806AE40B0629850CCE1960037649820988F9803020000603F67980100000040B0629888FFFFFF50CCE19685FFFFFF0000403F0000803E00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000E0A806AEC05ECFB658E0A6980100000081FFFFFFB0DFA6981CE0A6981474F598603F6798000000000000000080DFA69834DFA69838978F98588B5399E0A806AE001E899A9CF0A6980000000000000000000000000100000084E7A698E0A806AE0001000000000000B0DD0F9400000000603F679810E4A69802000000010000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: S 98A6DF80 0100000081FFFFFF0000000000000000E8E3A698F6FFFFFFECA806AE01000000E0A806AEB0DFA69800000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000058E0A698E0A806AE78EB5C9900826A9800000000C005DF951CE0A698CE83AA1A00000000E0A806AE
08-26 15:00:13.667  6891  6891 F google-breakpad: C 060000400000579A00000000546BA698D06BA698286BA6987C6BA698E0A806AE546BA698A041E09685FFFFFF00834E9A4C6BA698106BA698186BA69878D902997CD9029910000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:13.667  6891  6891 F google-breakpad: M B6F5C000 00000000 00005000 6737634E81D84DB8656B1FE66D1027010 app_process32
08-26 15:00:13.667  6891  6891 F google-breakpad: M 98AE6000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-26 15:00:13.667  6891  6891 F google-breakpad: M 9BE85000 00000000 0000B000 1F1CAF02D318FA95C8B96499F1F825B20 libqservice.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M 9BF87000 00000000 0000B000 D3E3DE2840837B61BFB94E439D9E0BDF0 libqdutils.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M 9BF92000 00000000 00007000 91BF5CFF7B201D4C458CB0C031FDB4630 libmemalloc.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M 9C703000 00000000 0001D000 AAEAB4160D24A01BF32C3DEDD8CDF4D30 gralloc.msm8974.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M A0CC0000 008F2000 01C47000 8506F83DD6FA1E55AAEDF5288D23914C0 libwebviewchromium.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A7138000 00000000 004B2000 D8C1C872B9D270C50A8E4BDDB0C7A3080 libsc-a3xx.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A75ED000 00000000 0014B000 C18304CC04A824E5077B982B15864E1C0 libGLESv2_adreno.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A77E9000 00000000 0000A000 609798789A4F346EDDF0704B12C40B1F0 libcompiler_rt.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A77FA000 00000000 00012000 19452302FFD56576D48927053184C89F0 libandroid.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A7885000 00000000 00035000 FC8241AF9D67527BCAA6B19D252BFB5E0 libGLESv1_CM_adreno.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M A78E2000 00000000 00008000 65F04F37F554F20F6DC201893364FF680 libadreno_utils.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A78EC000 00000000 0003D000 E5665D9058010C6C4E7538398D13FF4E0 libgsl.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A7929000 00000000 0002D000 E4CD5C4EEC88956FF88EE5CE43BCB4A10 libEGL_adreno.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A79CE000 00000000 0001B000 DC42B82CBF18DDB80615D78CF3B6E0880 libkeymaster1.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A79E9000 00000000 0000B000 8488EC176A697A1DF2F0FBD2618160640 libkeymaster_messages.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A79F4000 00000000 00018000 F14B9F542B51BDEBBE996FFCA199963A0 libsoftkeymasterdevice.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A7A0C000 00000000 0000F000 567E6E7C18C76037D687723853DB5BC60 libkeystore_binder.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M A7A1B000 00000000 00006000 304B6D35FF758AF183CD9EC42E6D8B940 libkeystore-engine.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A7A21000 00000000 00009000 82524A1E1CCD194F6458EB49532AB3130 libucsengine.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A7A2A000 00000000 0000C000 0A79DC15C1863625626306DC8FA2F5C90 libsecpkcs11_engine.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A9047000 00000000 0001A000 4F99845A9F79999FA7ECB00AE378809B0 libjavacrypto.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A9061000 00000000 00010000 297587A1751182FA38E057391EC59E300 libstagefright_amrnb_common.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A906E000 00000000 0002F000 FBF9E7B8F8A3F63E90D9647B5BED53C30 libexif.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A909D000 00000000 00018000 66E885E66029A1CB80EE21A6420A5FF90 libmtp.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M A90B3000 00000000 0004C000 7AAA9785F265DB2DFC786A0F0E2F5B580 libmedia_jni.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M A91C3000 00000000 0000D000 6BA1CC6F53B67549A349F60077CB42C10 libjhead.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M ADBC0000 00000000 00006000 DB3C5BFD6C8466710D91F815447EEA750 libwebviewchromium_loader.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M ADE07000 00000000 00005000 241063A12063BB58649E01043E4EBE530 libqti-perfd-client.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M ADE2C000 00000000 00005000 267E141D40FE019F1232E8FAA285A69A0 memtrack.msm8974.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M ADE31000 00000000 00006000 C075199D7439C4ECAC1DD9A2E88C01000 libjnigraphics.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M AF8CF000 00000000 00039000 6F3B3E305C6B2FD367A2A1177241A6770 libjavacore.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M B2851000 00000000 0000B000 53A5669194140A09026C9B112B3CEAEF0 eglsubAndroid.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M B28FF000 00000000 00007000 643E8CC447EC54F126B0B481E6DD690B0 libwebviewchromium_plat_support.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M B3A96000 00000000 00468000 2A5E83A781F59B5A348D00E09146C0020 libart.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F40000 00000000 00005000 5ED94A53921F70AD35BF0AD48F8C38410 libsigchain.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F46000 00000000 0000D000 59DA4C27AF8001AE53B07B2A092A09CF0 lib_SoundAlive_SRC192_ver205.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F54000 00000000 00009000 F72B2C9B449DDD359DC35D153240E5C80 libQSEEComAPI.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F5E000 00000000 00015000 185A43D1D408D58244EB5589ADF7B3870 lib_SoundBooster_ver610.so
08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F74000 00000000 00006000 A07ED434CEE44EDACBE9BDE478EBC0A60 lib_soundaliveresampler.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F7B000 00000000 0000D000 C9DE076ED8C579E7E9E535D5F0933AF60 libSoundAlive_VSP_ver315b_arm.so
,08-26 15:00:13.677  6891  6891 F google-breakpad: M B3F89000 00000000 0000C000 766DDC588579E6B6AE4E15FCA4052D1C0 lib_Samsung_Resampler.so
,08-26 15:00:13.687  6891  6891 F google-breakpad: M B3F96000 00000000 00189000 D4CAEF1AF2D8EECE7C2CB46E19D898200 lib_SoundAlive_ver118t.so
,08-26 15:00:13.687  6891  6891 F google-breakpad: M B4120000 00000000 00212000 01248AEA926C6DE75A4306A11F8C6C3C0 libsthmb.so
,08-26 15:00:13.687  6891  6891 F google-breakpad: M B4338000 00000000 0000D000 024D67823D6854B0DDD338CBDA5988070 libsecuibc.so
08-26 15:00:13.687  6891  6891 F google-breakpad: M B4345000 00000000 0000F000 7604BE0956E6A182C5ECC024D089CB530 libhdcp2.so
,08-26 15:00:13.687  6891  6891 F google-breakpad: M B4354000 00000000 00006000 0A9331837678331CEFDFC710D6F86B150 libsamsungSoundbooster_ext.so
08-26 15:00:13.687  6891  6891 F google-breakpad: M B435B000 00000000 00028000 8CBB62A86BAF7D2DD787059C09A31A870 libaudioresampler.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B4384000 00000000 00236000 C28ABE2A4A7EB279A3CAEB2DA8AC65B50 libMMFW_scone_stub.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B45C3000 00000000 00008000 260B593D3FBABBC93B30C5B94839C9B40 libsoundalive.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B45CB000 00000000 0000B000 253DDA8436E246D1EDF419319D3493180 libsavsmeta.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B45D6000 00000000 0006E000 CA3723DA44C84ACCE7DEB20CEDFB88390 libstagefright_wfd.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B4640000 00000000 000D6000 706D2644A0006C3830CC7BA6BA5EA3080 libmediaplayerservice.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B4716000 00000000 0002A000 77072D9F7F37A8820D556400F0BD63B90 libstagefright_httplive.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B4801000 00000000 00006000 73C8BC96B0E956B4A6DF488B9A2B2D3C0 libsoundspeed.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B4807000 00000000 0001D000 60A14086C7C565AB3E81121BF15CC33A0 libstagefright_nts.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B4825000 00000000 00005000 F08D3CFC3256D7BAD9488B15C0CE72860 libavenhancements.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B4827000 00000000 00A80000 D03C37FE3E5858C128EC62FD91B13D0B0 libLLVM.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B52B0000 00000000 00038000 3103EAA00263A40EEB12537E872DDFB00 libbcinfo.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B52E8000 00000000 0005B000 F7EE794D521AE3FCE3269909982A40390 libbcc.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B5344000 00000000 00008000 4FC38AABACC8A2923C959CFB03E3042C0 lib_SamsungVAD_v01009.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B534E000 00000000 0000F000 F2906C873F2FE54EBACF6DC2318855450 libcommon_time_client.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B535E000 00000000 0001A000 C2513677603465F7712EEE50C88BBF420 libprotobuf-cpp-lite.so
08-26 15:00:13.697  6891  6891 F google-breakpad: M B5379000 00000000 0000C000 D70A6468953AF0ACEC1F3B10FE7AB9520 libsec_km.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B5385000 00000000 00006000 C2DAAD976FF58B60214C62A62B1BC9310 libSEF4MP4.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B538B000 00000000 00018000 D57EFF53D61C0F0EDF0B2F83706A07980 libSEF.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B53A3000 00000000 0000F000 BA58BCAD0D4E4E73908D9D3C4EC29FEC0 libsfextcp.so
,08-26 15:00:13.697  6891  6891 F google-breakpad: M B53B2000 00000000 00063000 001CDB57429A2936C1966CECFC556CCD0 libsavsff.so
,08-26 15:00:13.707  6891  6891 F google-breakpad: M B5419000 00000000 00062000 1AE59469FDCEB58FC0159C6CFAB604870 libsavscmn.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B547B000 00000000 00052000 6A6AD57F8AB1F88829117B6417C058DB0 libomafldrm.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B54CE000 00000000 00009000 DDA4B8DB553A1D468CDEBA159CBBB79F0 libstagefright_avc_common.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B54D8000 00000000 00005000 04FA09F5D9A3CC342EB22691B54BE5D20 libstagefright_enc_common.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B54DE000 00000000 00007000 3DFB0E09A4C351EA0F24A79B149C7E3E0 libpowermanager.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B54E6000 00000000 0001F000 1516FAE1617A4462D8EFA9598A1262C60 libvorbisidec.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5506000 00000000 00007000 777E402E091981606F856931FA8BD9D30 libstagefright_yuv.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B550D000 00000000 00036000 D5FCDC07D4F779ABB597709C383AA2890 libstagefright_omx.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5544000 00000000 0003D000 33F32F45CA2E069551D46DA8E0D852770 libopus.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5582000 00000000 0000A000 DAD9CBF0CA51BA939DD94BDAAA64CE270 libmediautils.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B558C000 00000000 0001D000 C046FD28BD3B900B897709B944122FE30 libdrmframework.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B55A9000 00000000 00021000 F411BF677364CE04EDD4750EFA4527430 libRScpp.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B55CA000 00000000 00042000 DA4DA74AB4F96C85074C37561213FD730 libRS.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B560D000 00000000 00009000 CE8BC84F1628E74454122C3C80006DAE0 libspeexresampler.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5617000 00000000 00005000 377135FD854F7B9763B2E9B259FF30150 libsamsungvad.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B561C000 00000000 00009000 CE95EB42F5F7EE7D82F69EFD7AAE93900 libedmnativehelper.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5625000 00000000 0000B000 457A0D71F244B909C22EC61817DA51680 libnbaio.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5630000 00000000 0009E000 A593AC7AF0EB4B78DDEA72C6670E47890 libcrypto-rename.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B56CF000 00000000 00014000 70D715D3A4D83FDC8777DEC15DC8555F0 libpcre.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B56E4000 00000000 00007000 6E6E2C885B035A29E0525717D7BCDFCC0 libwpa_client.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B56EC000 00000000 00071000 F51DEF66C14FB48859F3961971C2EA610 libGLES_trace.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B575E000 00000000 00009000 4066E0E246E60AAE5ED64D93195895380 libsdp_crypto.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5768000 00000000 00083000 E0147D7E45E4476ADE4E057B8BEE649D0 libAstcEnc.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5802000 00000000 00039000 60DA07F90F4818F51CBBD6435857E9970 libqc-opt.so
,08-26 15:00:13.707  6891  6891 F google-breakpad: M B583B000 00000000 0001E000 18C32F00634AB7BB4010F2D59861567F0 libquramimagecodec.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B585A000 00000000 00064000 0B0A006D6500C26963314522CCA11EC40 libft2.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B58BF000 00000000 0002A000 8C5E56EE77F881F59C4F8AFB157FE0850 libpng.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B58E9000 00000000 0000C000 7BECFDE402102EC7A0BF4AC65D0F3E570 libremotedesktop_client.so
,08-26 15:00:13.707  6891  6891 F google-breakpad: M B58F6000 00000000 00005000 ABF5C665DE31BEB25EDA8C0C288894280 libsync.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B58FB000 00000000 00007000 165EEF24EDACC705C1C8B42AA30E48910 libstdc++.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5902000 00000000 00012000 B6E3D42145FFC73E97951D6F68C9B96A0 libunwind.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B595A000 00000000 0000B000 DE11AAFDA75875AD3B4AA6266C6C3A4D0 libbase.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5966000 00000000 00007000 B3B89AA9A2FDAFF3014AA68F6F4CF20E0 libeffects.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B596D000 00000000 00006000 015B5D48862D440354C333C5937C3AB80 libstagefright_http_support.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5974000 00000000 0001B000 2DA99727E5C0E5970F5877ECE29A90DC0 libstagefright_foundation.so
,08-26 15:00:13.707  6891  6891 F google-breakpad: M B5988000 00000000 001B1000 20AABF035B3C72AAA0891AB28D71B0E40 libstagefright.so
,08-26 15:00:13.707  6891  6891 F google-breakpad: M B5B39000 00000000 00007000 7E4568EC628B9596FAB2BF4E757FF0430 libpersona.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5B40000 00000000 00015000 8449DDC0FB4180B6B96988E7CC2C1DCB0 libimagefilter.so
,08-26 15:00:13.707  6891  6891 F google-breakpad: M B5B56000 00000000 0004D000 964801C5524016D56736B2880A485C130 libsecure_storage.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5BA6000 00000000 00014000 04FB7B529F95BF1C7CA4F902318F5DC40 libsamsungeffect.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5BBB000 00000000 0000D000 D8DB38F6E4F137A0D15ECEB89633C0A10 libsensorhub.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5BC8000 00000000 0001D000 876D3B4E1A76575A207E7D9C88CD9A6D0 libmctraster.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5BE7000 00000000 0007B000 A01D38174A635EF479001144627EA5350 libhwui.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C63000 00000000 00005000 8CD379AFD04CC676AD564EF681CCCB010 libcc_manager.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C69000 00000000 00007000 32196C5A7967EBF86ABD7894BCA69EDC0 libsecnativefeature.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C71000 00000000 00005000 15601B6E636F524501E2244E685E973E0 libradio_metadata.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C77000 00000000 00006000 960C748A5A19DA4D42D63B872E26E6820 libnativebridge.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C7E000 00000000 00006000 0EF675792B45332FFF70F5446162177D0 libprocessgroup.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C85000 00000000 00011000 F3AE7047650829200638C6500FAB18F30 libminikin.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5C95000 00000000 0000F000 8C3EB649ADAC03C8FD5CB12FDB1B36410 libsoundtrigger.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5CA4000 00000000 0000F000 2649179EBD0F9F069DF4EC95A8A2BE370 libradio.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5CB3000 00000000 00006000 25B6D207A9C00127CD065E6BD07564650 libnetd_client.so
08-26 15:00:13.707  6891  6891 F google-breakpad: M B5CBA000 00000000 00010000 D1BA0E60254F0357A81E152B12258AD90 libimg_utils.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B5CC4000 00000000 00426000 014010409C0E2E38A5DE8879698B198F0 libpdfium.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B60EB000 00000000 00009000 87DFBD5B2879590605C2A161FF0E500B0 libaudioutils.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B60F5000 00000000 0001D000 1131869B578817F0661C8BC46988FBCA0 libz.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6113000 00000000 0004F000 58A4A022E67058363F45CAE5B44B68230 libharfbuzz_ng.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6163000 00000000 00007000 CA4CC110C3A639479AE00D63E021DD2C0 libusbhost.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B616A000 00000000 0003A000 815955CCD37387B64ADCC0518AC295F80 libjpeg.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B618B000 00000000 000D8000 766415D0998448F5F89D6B1F084AC16D0 libmedia.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B625C000 00000000 00186000 A3D4E1161B12FD940045538BA78D594F0 libicui18n.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B63DB000 00000000 0012A000 443AC89AC4BEEB2FE71B142136F7D0E50 libicuuc.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6509000 00000000 00027000 82682FF5D1AB61962A254AF75C9FE8ED0 libssl.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6530000 00000000 000B4000 00727E385FA14DABB0D5C8159669B9840 libcrypto.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B65E5000 00000000 00056000 61B71F89B1565A65DBF28816BE22CFCA0 libsonivox.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6640000 00000000 00015000 BB90A0D050AD8CE38005AB16E0FB7DB10 libselinux.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6655000 00000000 00009000 E8E0858D51ECC443B3933372A2CCB3610 libhardware_legacy.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B665F000 00000000 00005000 B34DE6D4026D30AA3446A89D0FFD981B0 libhardware.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6664000 00000000 00006000 616A5E4AEA5C8E72AE9509BF20C74B1A0 libETC1.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B666A000 00000000 00011000 2FB1F3D0AA0FF03CDE0808981D4363A30 libGLESv2.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B667B000 00000000 0000B000 DEE69F8F2A48F2620A0E1520F8734A310 libGLESv1_CM.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B667E000 00000000 0007A000 1BA416D926EC5B9299A59EFA34C23AA10 libEGL.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B66FA000 00000000 0009B000 79206C6619BA5A87CFB8D64E0161092D0 libsqlite.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6784000 00000000 00353000 D144E08B2D8F93EA79F266F2AE99A8140 libskia.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6ADC000 00000000 0000A000 6BBC41B12B612FDF8D1A0EFA4E5929A00 libcamera_metadata.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6AE2000 00000000 0003B000 61B47CE6FC6F49EE6AC7629405ABC1730 libcamera_client.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B6B1C000 00000000 0004C000 B667609ACEA8B231D071A078C2F01A6F0 libinputflinger.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6B66000 00000000 00022000 64DEDCD1FB75BB0267C343297DD3CB180 libinput.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6B7F000 00000000 00064000 02B123A58ED6EEA81CEE4B9734EF53700 libgui.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6BE3000 00000000 00010000 B7A5F6DBC154063E6DA93FC3B7E01A400 libui.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6BF3000 00000000 0000B000 F09ED8765DE808A64B47FDDA5F03933F0 libnetutils.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6BFE000 00000000 00009000 D22C726707D32BAB46D0C83E7CE3B3720 libnativehelper.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B6C07000 00000000 00017000 9CAFE89A7B15F0C9EE3C8445FC36A7FB0 libexpat.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6C1E000 00000000 0002B000 30DC4AF71742721EE01C1872B73B22BD0 libandroidfw.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6C49000 00000000 00005000 1622866B32DAD4D6B99CCCFFEB3A26B40 libmemtrack.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6C4E000 00000000 0000B000 ADD7554080FA3ECA80C68376E08CF8430 libbacktrace.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6C59000 00000000 00022000 328148F7DAAA68C87C6BD885EB8A2B7A0 libm.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6C7B000 00000000 0007A000 DB5162511942845F44D05BB7EEB2C46E0 libc.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6CFD000 00000000 00090000 7A09CEB731533E48903F464EAD4344BA0 libc++.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B6D8C000 00000000 00030000 01EF062860881A516B34421BF70B89AE0 libwilhelm.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6DAD000 00000000 000F8000 8A50AA6CF32156DDD1772BE5A59994E70 libandroid_runtime.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6EA8000 00000000 00032000 D5AB9CE1672F40A8C103C9643FF03A6F0 libbinder.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6EDA000 00000000 00009000 8B6CACA1AC968A15D5A9C8206CB3EC380 liblog.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6EE4000 00000000 0001B000 71AF0D1797004B60F463A39BBBE500CD0 libutils.so
08-26 15:00:13.717  6891  6891 F google-breakpad: M B6EFF000 00000000 00011000 12B7D89CFB60A9AFB040F0194EC35BC10 libcutils.so
,08-26 15:00:13.717  6891  6891 F google-breakpad: M B6F3C000 00000000 0001E000 385BE39335FF44C8B393EC3D82F5FBED0 linker
08-26 15:00:13.717  6891  6891 F google-breakpad: -----END BREAKPAD MICRODUMP-----
,08-26 15:00:13.747  6453  6560 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:13.747  6453  6560 W google-breakpad: Chrome build fingerprint:
08-26 15:00:13.747  6453  6560 W google-breakpad: 0.0.1
08-26 15:00:13.747  6453  6560 W google-breakpad: 19
08-26 15:00:13.747  6453  6560 W google-breakpad: 6d6f4589-33a4-4709-9279-1a8b5e855d5c
08-26 15:00:13.747  6453  6560 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:13.747  6453  6560 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 6560 (Thread-899)
,08-26 15:00:13.767   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{259919a: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:13.807  6868  6879 I qtaguid : Untagging socket 21
,08-26 15:00:13.847  6868  6879 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-26 15:00:13.847  6868  6879 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-26 15:00:13.857   305   305 F DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,08-26 15:00:13.857   305   305 F DEBUG   : Build fingerprint: 'samsung/kltexx/klte:6.0.1/MMB29M/G900FXXU1CPEM:user/release-keys'
08-26 15:00:13.857   305   305 F DEBUG   : Revision: '14'
08-26 15:00:13.857   305   305 F DEBUG   : ABI: 'arm'
,08-26 15:00:13.857   305   305 F DEBUG   : pid: 6453, tid: 6560, name: Thread-899  >>> com.test.thalitest <<<
,08-26 15:00:13.857   305   305 F DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,08-26 15:00:13.887   305   305 F DEBUG   :     r0 9a570000  r1 00000000  r2 98a66b54  r3 98a66bd0
,08-26 15:00:13.887   305   305 F DEBUG   :     r4 98a66b28  r5 98a66b7c  r6 ae06a8e0  r7 98a66b54
08-26 15:00:13.887   305   305 F DEBUG   :     r8 96e041a0  r9 ffffff85  sl 9a4e8300  fp 98a66b4c
08-26 15:00:13.897   305   305 F DEBUG   :     ip 98a66b10  sp 98a66b18  lr 9902d978  pc 9902d97c  cpsr 200f0010
,08-26 15:00:13.897   305   305 F DEBUG   : 
08-26 15:00:13.897   305   305 F DEBUG   : backtrace:
,08-26 15:00:13.897   305   305 F DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-26 15:00:13.897   305   305 F DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
08-26 15:00:13.897   305   305 F DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,08-26 15:00:13.997  2102  6899 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:00:13.997  2102  6897 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:00:14.007  2102  6899 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:00:14.007  2102  6897 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:00:14.027  2102  6899 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:00:14.027  2102  6897 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:00:14.027  2102  6897 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-26 15:00:14.037  2102  6897 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:00:14.117   781  1319 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.207  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.207  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.207   304  1125 D EnterpriseController: netId is 0
08-26 15:00:14.207   304  1125 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:00:14.207  2102  6897 I qtaguid : Tagging socket 55 with tag 1106541400000000{285627412,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:14.257  2102  6897 I qtaguid : Tagging socket 58 with tag 1106541400000000{285627412,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:14.527   781  1747 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.527  2102  6897 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-26 15:00:14.537  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.537  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:14.537  2102  6897 I qtaguid : Tagging socket 55 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:14.647   781   794 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.667  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.667  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:14.667  2102  6897 I qtaguid : Tagging socket 55 with tag fffffca200000000{4294966434,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:14.777  6909  6909 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-26 15:00:14.807   781  1731 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.817  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.817  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.827  2102  6897 I qtaguid : Tagging socket 55 with tag 11065c0800000000{285629448,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:14.907  6909  6909 I dex2oat : ----------------------------------------------------
08-26 15:00:14.907  6909  6909 I dex2oat : <SS>: S T A R T I N G . . .
08-26 15:00:14.907  6909  6909 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
08-26 15:00:14.907  6909  6909 I dex2oat : dex2oat took 136.914ms (threads: 4) arena alloc=109KB java alloc=59KB native alloc=1801KB free=1782KB
,08-26 15:00:14.917  6868  6879 W System  : ClassLoader referenced unknown path: 
,08-26 15:00:14.917  6868  6879 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-26 15:00:14.927  6868  6879 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-26 15:00:14.927  6868  6879 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-26 15:00:14.927  6868  6879 I Adreno-EGL: Build Date: 01/28/16 Thu
08-26 15:00:14.927  6868  6879 I Adreno-EGL: Local Branch: ss
08-26 15:00:14.927  6868  6879 I Adreno-EGL: Remote Branch: 
08-26 15:00:14.927  6868  6879 I Adreno-EGL: Local Patches: 
08-26 15:00:14.927  6868  6879 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:14.937  6868  6879 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,08-26 15:00:14.937   781   794 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:14.947  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:14.947  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:14.947  2102  6897 I qtaguid : Tagging socket 55 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:15.007  6868  6879 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,08-26 15:00:15.017  6868  6879 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-26 15:00:15.017  6868  6879 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-26 15:00:15.017  6868  6879 I Adreno-EGL: Build Date: 01/28/16 Thu
08-26 15:00:15.017  6868  6879 I Adreno-EGL: Local Branch: ss
08-26 15:00:15.017  6868  6879 I Adreno-EGL: Remote Branch: 
08-26 15:00:15.017  6868  6879 I Adreno-EGL: Local Patches: 
08-26 15:00:15.017  6868  6879 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:15.017  6868  6879 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,08-26 15:00:15.037   305   305 F DEBUG   : 
08-26 15:00:15.037   305   305 F DEBUG   : Tombstone written to: /data/tombstones/tombstone_06
08-26 15:00:15.037   305   305 E DEBUG   : AM write failed: Broken pipe
08-26 15:00:15.037   305   305 E         : ro.product_ship = true
08-26 15:00:15.037   305   305 E         : ro.debug_level = 0x4f4c
08-26 15:00:15.037   305   305 E         : sys.mobilecare.preload = false
,08-26 15:00:15.037  2165  2165 E audit   : type=1701 msg=audit(1472216415.037:290): auid=4294967295 uid=10004 gid=10004 ses=4294967295 subj=u:r:untrusted_app:s0:c512,c768 pid=6560 comm="Thread-899" reason="memory violation" sig=11
,08-26 15:00:15.047   781   895 I BootReceiver: Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,08-26 15:00:15.047   781  3388 W System.err: mkdir failed: ENOENT (No such file or directory) : /data/user/0/android/shared_prefs
,08-26 15:00:15.047   781  3388 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/android/shared_prefs/log_files.xml
,08-26 15:00:15.077  6868  6879 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,08-26 15:00:15.087  6868  6879 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-26 15:00:15.087  6868  6879 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-26 15:00:15.087  6868  6879 I Adreno-EGL: Build Date: 01/28/16 Thu
08-26 15:00:15.087  6868  6879 I Adreno-EGL: Local Branch: ss
08-26 15:00:15.087  6868  6879 I Adreno-EGL: Remote Branch: 
08-26 15:00:15.087  6868  6879 I Adreno-EGL: Local Patches: 
08-26 15:00:15.087  6868  6879 I Adreno-EGL: Reconstruct Branch: 
,08-26 15:00:15.087  6868  6879 D libEGL  : eglInitialize EGLDisplay = 0xb2f0e264
,08-26 15:00:15.087  6918  6918 E Zygote  : v2
08-26 15:00:15.087   781   854 I ActivityManager: Start proc 6918:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
08-26 15:00:15.087  6918  6918 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:00:15.087  6918  6918 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:15.097  6918  6918 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 15:00:15.097  6918  6918 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:00:15.097  6918  6918 E Zygote  : accessInfo : 0
,08-26 15:00:15.107   781  1791 D GraphicsStats: Buffer count: 4
,08-26 15:00:15.107   781  2274 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@26f57f9)
,08-26 15:00:15.107   781  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:00:15.107   781  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:00:15.107   781  1489 I WindowState: WIN DEATH: Window{595101c u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:00:15.107   293   378 I SurfaceFlinger: id=20 Removed NainActivit (4/10)
,08-26 15:00:15.107   781  1412 I ActivityManager: Process com.test.thalitest (pid 6453)(adj 1) has died(159,721)
08-26 15:00:15.107   781  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:00:15.107   293   378 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-26 15:00:15.117   781  1412 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-26 15:00:15.117   293  5144 I SurfaceFlinger: id=20 Removed NainActivit (-2/10)
,08-26 15:00:15.127   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe9da3a4
,08-26 15:00:15.137   781  1412 I ActivityManager: Start proc 6930:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
,08-26 15:00:15.137  6930  6930 E Zygote  : v2
,08-26 15:00:15.137  6930  6930 I libpersona: KNOX_SDCARD checking this for 10004
08-26 15:00:15.137  6930  6930 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:15.137  6930  6930 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:00:15.137  6930  6930 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:00:15.137  6930  6930 E Zygote  : accessInfo : 0
,08-26 15:00:15.147  6930  6930 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-26 15:00:15.157   781  1717 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:15.157  6918  6918 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:00:15.157  6918  6918 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:15.167   781  1810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9cc833e u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c04f59f 6918:com.samsung.android.sm/1000}
,08-26 15:00:15.177  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:00:15.177  6930  6930 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:15.177   781  1412 I ActivityManager: Killing 5833:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-26 15:00:15.177  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:15.177  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:15.177  6918  6918 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
08-26 15:00:15.177  2102  6897 I qtaguid : Tagging socket 55 with tag 11065fff00000000{285630463,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:15.187  6868  6879 D libEGL  : eglTerminate EGLDisplay = 0xb2f0e2bc
,08-26 15:00:15.187  6930  6930 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-26 15:00:15.197   781  1717 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-26 15:00:15.237  6918  6918 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-26 15:00:15.247   781  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{9cc833e u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d567e0 4192:com.google.android.gms/u0a11}
,08-26 15:00:15.257   348   348 I Zygote  : Process 6453 exited due to signal (11)
,08-26 15:00:15.267   781  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{989954a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c04f59f 6918:com.samsung.android.sm/1000}
,08-26 15:00:15.277   781  1717 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{989954a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5d567e0 4192:com.google.android.gms/u0a11}
,08-26 15:00:15.297  2102  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:15.297  2102  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:15.297   304  1125 D EnterpriseController: netId is 0
08-26 15:00:15.297   304  1125 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:00:15.297  2102  6866 I qtaguid : Tagging socket 54 with tag 1000040100000000{268436481,0} uid 10011, pid: 2102, getuid(): 10011
,08-26 15:00:15.327   781  2302 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:15.347  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:15.347  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:15.347  2102  6897 I qtaguid : Tagging socket 55 with tag 11065c9100000000{285629585,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:15.347  2102  6866 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} uid 10011, pid: 2102, getuid(): 10011
,08-26 15:00:15.407  4192  6948 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-26 15:00:15.437  4192  6948 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-26 15:00:15.447   781  1810 I ActivityManager: Killing 5971:com.google.android.apps.photos/u0a199 (adj 15): DHA:empty #37
,08-26 15:00:15.467   781  2302 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:00:15.467   781  1747 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.photos, Auto Run ON
,08-26 15:00:15.487  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:15.487  2102  6897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:15.487  2102  6897 I qtaguid : Tagging socket 55 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2102, getuid(): 10011
,08-26 15:00:15.627  2102  2707 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:00:15.627  2102  2707 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 15:00:15.637  2102  6956 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:00:15.637  2102  6956 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:15.637   304  1125 D EnterpriseController: netId is 0
08-26 15:00:15.637   304  1125 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 15:00:15.637  2102  2707 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 15:00:13.788+0200, stopTime=2016-08-26 15:00:15.646+0200, duration=1858ms
,08-26 15:00:15.647  2102  6956 I qtaguid : Tagging socket 63 with tag 1000310500000000{268448005,0} uid 10011, pid: 2102, getuid(): 10011
,08-26 15:00:15.647   781  1625 V AlarmManager:  remove PendingIntent] PendingIntent{b5a9833: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:15.677  2102  6956 I qtaguid : Tagging socket 52 with tag 1000310500000000{268448005,0} uid 10011, pid: 2102, getuid(): 10011
,08-26 15:00:15.727   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{1d93169: PendingIntentRecord{a6acab8 com.google.android.gms broadcastIntent}}
,08-26 15:00:16.027  2102  6956 I qtaguid : Untagging socket 63
,08-26 15:00:16.067  2102  2707 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 15:00:17.247   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:17.867  2102  6953 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:17.867  2102  6953 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:00:17.867  2102  6953 I qtaguid : Tagging socket 63 with tag 1000310200000000{268448002,0} uid 10011, pid: 2102, getuid(): 10011
,08-26 15:00:18.147  2102  6953 I qtaguid : Untagging socket 63
,08-26 15:00:18.177  2102  2707 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-26 15:00:18.407   781  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-26 15:00:18.407   781  1322 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-26 15:00:18.497   781  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:18.507   781  1319 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4366, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:00:18.507   781  1319 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:00:18.507   781  1319 D BatteryService: stay LED for charging
,08-26 15:00:18.517   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:18.537   781   781 I MotionRecognitionService: Plugged
,08-26 15:00:18.547   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:00:18.547   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:00:18.547   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:00:18.557  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:18.557  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:18.557  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:18.587  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:18.587  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:00:18.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:18.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:18.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:18.617   781  3423 D SSRM:n  : SIOP:: AP = 430, PST = 457, CUR = 350, LCD = 0
,08-26 15:00:20.258   781  1625 I ActivityManager: Killing 6082:com.google.android.gms:car/u0a11 (adj 15): DHA:empty #37
,08-26 15:00:20.378   781  1642 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gms, Auto Run ON
,08-26 15:00:28.577   781  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:28.577   781  1731 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4368, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:00:28.577   781  1731 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-26 15:00:28.577   781  1731 D BatteryService: stay LED for charging
,08-26 15:00:28.577   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:28.577   781   781 I MotionRecognitionService: Plugged
,08-26 15:00:28.577   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:00:28.577   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-26 15:00:28.577   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:00:28.577  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:28.577  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:00:28.577  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:28.587  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:28.587  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:00:28.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:28.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:28.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:28.667   781  3423 D SSRM:n  : SIOP:: AP = 400, PST = 445, CUR = 350, LCD = 0
,08-26 15:00:28.667   781  3423 D M       : limitCPUFreq:: freq = -1
,08-26 15:00:28.667   781  3423 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 781  tag : SIOP_ARM_MAX@25
08-26 15:00:28.667   781  3423 D M       : limitGPUFreq:: freq = -1
,08-26 15:00:28.667   781  3423 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,08-26 15:00:28.687   781   854 I ActivityManager: Start proc 6984:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,08-26 15:00:28.687   781  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-26 15:00:28.697  6984  6984 E Zygote  : v2
,08-26 15:00:28.697  6984  6984 I libpersona: KNOX_SDCARD checking this for 10053
,08-26 15:00:28.697  6984  6984 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:28.697  6984  6984 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:00:28.697  6984  6984 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:00:28.707   781  3423 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-26 15:00:28.707  2813  2813 D ContentApp:  LEVEL : 1
,08-26 15:00:28.707  6984  6984 E Zygote  : accessInfo : 0
,08-26 15:00:28.707  6984  6984 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-26 15:00:28.747  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:28.757  6984  6984 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:28.767   781  1810 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{41c848f u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{622331c 6984:com.sec.android.app.videoplayer/u0a53}
,08-26 15:00:28.847   781  1322 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-26 15:00:28.867  6984  6984 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null,
,08-26 15:00:28.917  6984  6984 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-26 15:00:28.947  6984  6984 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-26 15:00:28.987  6984  6984 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-26 15:00:28.997  6984  6984 D videowall-Global: core_num = 4
,08-26 15:00:29.017  6984  6984 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
08-26 15:00:29.017  6984  6984 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-26 15:00:29.027  6984  6984 D TranscodeReceiver:  SIOP_LEVEL: 1
,08-26 15:00:29.027   781  2302 I ActivityManager: Killing 5582:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-26 15:00:29.047   781  1625 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-26 15:00:33.167   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found,
,08-26 15:00:33.167   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found,
,08-26 15:00:33.167   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found,
,08-26 15:00:37.257   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:37.597   781  1574 E Watchdog: !@Sync 4 [08-26 15:00:37.602]
,08-26 15:00:38.328  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:00:38.798   781  3423 D SSRM:n  : SIOP:: AP = 390, PST = 435, CUR = 350, LCD = 0
,08-26 15:00:38.807   781  1810 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:38.817   781  1810 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4388, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:00:38.817   781  1810 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-26 15:00:38.817   781  1810 D BatteryService: stay LED for charging
,08-26 15:00:38.817   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:38.817   781   781 I MotionRecognitionService: Plugged
,08-26 15:00:38.817   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:00:38.817   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:00:38.827   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:00:38.827  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:38.827  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:38.827  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:38.848  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:38.848  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:00:38.858  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:38.858  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:38.858  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:48.887   781  3423 D SSRM:n  : SIOP:: AP = 370, PST = 427, CUR = 350, LCD = 0
,08-26 15:00:48.897   781  3423 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-26 15:00:48.918  2813  2813 D ContentApp:  LEVEL : 0
,08-26 15:00:48.948   781  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:48.948   781  1412 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:00:48.948   781  1412 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:00:48.948   781  1412 D BatteryService: stay LED for charging
08-26 15:00:48.948   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:48.958   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bca7b25 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{622331c 6984:com.sec.android.app.videoplayer/u0a53}
,08-26 15:00:48.958   781   781 I MotionRecognitionService: Plugged
,08-26 15:00:48.958   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:00:48.958   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-26 15:00:48.958   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:00:48.968   781  3423 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-26 15:00:48.977  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:48.977  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:00:48.977  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:48.987  6984  6984 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-26 15:00:48.997  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:48.997  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:00:48.997  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:48.997  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:48.997  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:00:49.007  6984  6984 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-26 15:00:57.258   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:59.077   781  3423 D SSRM:n  : SIOP:: AP = 360, PST = 420, CUR = 350, LCD = 0
,08-26 15:00:59.998   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:01:00.078   781  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:00.088   781  1731 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4387, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:01:00.088   781  1731 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:01:00.088   781  1731 D BatteryService: stay LED for charging
,08-26 15:01:00.098   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:00.108   781   781 I MotionRecognitionService: Plugged
,08-26 15:01:00.108   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:01:00.108   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:01:00.118   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:01:00.128  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:00.128  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:00.128  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:00.148  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:00.148  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:00.158  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:00.158  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:00.158  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:01:03.507  4192  5066 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 15:01:05.918  2102  3307 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 15:01:07.608   781  1574 E Watchdog: !@Sync 5 [08-26 15:01:07.610]
,08-26 15:01:07.718   781  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-26 15:01:07.728   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2e446d9 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23ca5f 6386:com.samsung.android.sm.provider/1000}
,08-26 15:01:07.838   781  3427 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-26 15:01:07.848   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d6daf7f u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d23ca5f 6386:com.samsung.android.sm.provider/1000}
,08-26 15:01:09.158   781  3423 D SSRM:n  : SIOP:: AP = 350, PST = 412, CUR = 350, LCD = 0
,08-26 15:01:10.277   781  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:10.287   781  1731 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:01:10.287   781  1731 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:01:10.287   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:10.297   781   781 I MotionRecognitionService: Plugged
,08-26 15:01:10.308   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:01:10.308   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:01:10.308   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:01:10.318   781  1731 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-26 15:01:10.318   781  1731 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 781) 
,08-26 15:01:10.328  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:10.328  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:10.328  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:10.337  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:01:10.347   781  1731 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,08-26 15:01:10.357   781  1731 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-26 15:01:10.367  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:10.367  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:10.377  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:10.377  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:10.377  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:10.377   781  1731 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-26 15:01:10.397   781  1731 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-26 15:01:10.397   781  1731 D BatteryService: turn on LED for fully charged
,08-26 15:01:10.778   781  1218 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-26 15:01:10.778   781   913 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-26 15:01:10.778   781   913 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-26 15:01:10.787   781   913 D SensorManager: unregisterListener ::   
,08-26 15:01:10.787   781   913 D lights  : led_pattern : 5 +
,08-26 15:01:10.807   781   913 D lights  : led_pattern : 5 -
,08-26 15:01:10.807   781   913 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,08-26 15:01:10.807   781   913 V AlarmManager:  remove PendingIntent] PendingIntent{1d24369: PendingIntentRecord{a18e68f android broadcastIntent}}
,08-26 15:01:17.268   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:01:19.238   781  3423 D SSRM:n  : SIOP:: AP = 340, PST = 403, CUR = 350, LCD = 0
,08-26 15:01:19.248   781  3423 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-26 15:01:19.297   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{dc97795 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{622331c 6984:com.sec.android.app.videoplayer/u0a53}
,08-26 15:01:19.297  6984  6984 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-26 15:01:19.297  6984  6984 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-26 15:01:19.307  2813  2813 D ContentApp:  LEVEL : -1
,08-26 15:01:20.367   781  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:20.378   781  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:01:20.378   781  1489 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:01:20.378   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:20.388   781   781 I MotionRecognitionService: Plugged
,08-26 15:01:20.398   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:01:20.398   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:01:20.398   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:01:20.398   781  1489 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:01:20.407   781  1489 D BatteryService: stay LED for fully charged
,08-26 15:01:20.407  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:20.407  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:20.417  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:20.447  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:20.447  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:01:20.447  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:20.447  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:01:20.447  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:29.368   781  3423 D SSRM:n  : SIOP:: AP = 340, PST = 391, CUR = 350, LCD = 0
,08-26 15:01:30.447   781  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:30.457   781  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:01:30.457   781  1747 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:01:30.457   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:30.467   781   781 I MotionRecognitionService: Plugged
,08-26 15:01:30.478   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:01:30.478   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:01:30.478   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:01:30.478   781  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:01:30.488   781  1747 D BatteryService: stay LED for fully charged
,08-26 15:01:30.498  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:30.508  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:30.508  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:30.527  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:30.527  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:30.537  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:30.537  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:30.537  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:37.268   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:01:37.628   781  1574 E Watchdog: !@Sync 6 [08-26 15:01:37.629]
,08-26 15:01:38.418  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:01:39.457   781  3423 D SSRM:n  : SIOP:: AP = 330, PST = 376, CUR = 350, LCD = 0
,08-26 15:01:40.547   781  1810 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:40.547   781  1810 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:01:40.547   781  1810 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:01:40.557   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:01:40.567   781   781 I MotionRecognitionService: Plugged
,08-26 15:01:40.567   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:01:40.567   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:01:40.567   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:01:40.577   781  1810 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-26 15:01:40.577   781  1810 D BatteryService: stay LED for fully charged
,08-26 15:01:40.587  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:40.587  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:01:40.597  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:01:40.618  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:01:40.618  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:01:40.628  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:40.628  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:40.628  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:01:42.548   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:01:42.548   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:01:42.548   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:01:49.537   781  3423 D SSRM:n  : SIOP:: AP = 330, PST = 364, CUR = 350, LCD = 0
,08-26 15:01:50.698   781  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:57.277   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:01:57.608   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:01:57.608   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:01:57.608   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:01:59.617   781  3423 D SSRM:n  : SIOP:: AP = 330, PST = 354, CUR = 350, LCD = 0
,08-26 15:02:00.917   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:00.928   781  2302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:02:00.928   781  2302 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:02:00.928   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:00.938   781   781 I MotionRecognitionService: Plugged
,08-26 15:02:00.948   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:02:00.948   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:02:00.948   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:02:00.948   781  2302 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-26 15:02:00.958   781  2302 D BatteryService: stay LED for fully charged
,08-26 15:02:00.967  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:00.967  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:00.967  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:00.997  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:02:00.997  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:02:01.007  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:01.007  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:01.007  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:07.628   781  1574 E Watchdog: !@Sync 7 [08-26 15:02:07.633]
,08-26 15:02:09.688   781  3423 D SSRM:n  : SIOP:: AP = 330, PST = 347, CUR = 350, LCD = 0
,08-26 15:02:11.037   781  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:11.037   781  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:02:11.048   781  1642 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:02:11.048   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:11.058   781   781 I MotionRecognitionService: Plugged
,08-26 15:02:11.058   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:02:11.058   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:02:11.068   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:02:11.068   781  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:02:11.068   781  1642 D BatteryService: stay LED for fully charged
,08-26 15:02:11.078  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:11.088  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:11.088  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:11.107  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:02:11.107  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:02:11.117  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:11.117  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:02:11.117  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:17.278   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:02:19.778   781  3423 D SSRM:n  : SIOP:: AP = 330, PST = 341, CUR = 350, LCD = 0
,08-26 15:02:21.408   781   795 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:29.867   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 336, CUR = 350, LCD = 0
,08-26 15:02:31.497   781  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:31.507   781  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:02:31.507   781  1319 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:02:31.507   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:31.517   781   781 I MotionRecognitionService: Plugged
,08-26 15:02:31.517   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:02:31.527   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:02:31.527   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:02:31.527   781  1319 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-26 15:02:31.537   781  1319 D BatteryService: stay LED for fully charged
,08-26 15:02:31.547  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:31.547  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:31.547  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:31.567  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:02:31.567  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:02:31.577  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:31.577  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:31.577  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:37.287   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:02:37.638   781  1574 E Watchdog: !@Sync 8 [08-26 15:02:37.639]
,08-26 15:02:38.527  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:02:38.767  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 236ms lastUpdatedAfter : 164170ms
,08-26 15:02:39.928   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 332, CUR = 350, LCD = 0
,08-26 15:02:41.627   781  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:41.627   781  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:02:41.627   781  1642 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:02:41.637   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:41.647   781   781 I MotionRecognitionService: Plugged
,08-26 15:02:41.647   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:02:41.647   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:02:41.647   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:02:41.658   781  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,08-26 15:02:41.658   781  1642 D BatteryService: stay LED for fully charged
,08-26 15:02:41.668  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:41.668  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:41.678  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:41.688  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:02:41.697  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:02:41.707  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:41.707  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:41.707  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:50.017   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 350, LCD = 0
,08-26 15:02:52.038   781  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:52.038   781  1412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:02:52.038   781  1412 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:02:52.038   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:52.048   781   781 I MotionRecognitionService: Plugged
,08-26 15:02:52.058   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:02:52.058   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:02:52.058   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:02:52.058   781  1412 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:02:52.068   781  1412 D BatteryService: stay LED for fully charged
,08-26 15:02:52.077  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:52.077  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:02:52.077  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:02:52.107  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:02:52.107  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:02:52.117  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:52.117  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:02:52.117  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:57.288   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:02:59.968   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:02:59.968   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:02:59.968   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:03:00.088   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 350, LCD = 0
,08-26 15:03:02.237   781  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:02.247   781  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:03:02.247   781  1791 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:03:02.247   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:02.257   781   781 I MotionRecognitionService: Plugged
,08-26 15:03:02.257   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:03:02.257   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:03:02.267   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:03:02.267   781  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-26 15:03:02.267   781  1791 D BatteryService: stay LED for fully charged
,08-26 15:03:02.278  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:02.288  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:02.288  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:02.307  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:02.307  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:03:02.317  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:02.317  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:02.317  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:07.637   781  1574 E Watchdog: !@Sync 9 [08-26 15:03:07.643]
,08-26 15:03:10.167   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 350, LCD = 0
,08-26 15:03:12.417   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:12.427   781  2302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:03:12.427   781  2302 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:03:12.427   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:12.437   781   781 I MotionRecognitionService: Plugged
,08-26 15:03:12.437   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:03:12.448   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:03:12.448   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:03:12.448   781  2302 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:03:12.448   781  2302 D BatteryService: stay LED for fully charged
,08-26 15:03:12.468  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:12.468  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:12.468  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:12.488  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:12.488  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:03:12.507  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:12.507  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:03:12.507  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:15.047   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:03:15.047   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:03:15.047   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:03:17.288   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:03:20.257   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 350, LCD = 0
,08-26 15:03:22.367   781  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:03:22.377   781  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:03:22.377   781  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:03:22.387   781  1229 I TLC_TIMA_PKM_initialize: initializing...
,08-26 15:03:22.387   781  1229 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-26 15:03:22.397   781  1229 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-26 15:03:22.397   781  1229 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-26 15:03:22.397   781  1229 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-26 15:03:22.397   781  1229 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-26 15:03:22.397   781  1229 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-26 15:03:22.397   781  1229 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080,
08-26 15:03:22.407   781  1229 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-26 15:03:22.407   781  1229 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:03:22.468   781  1229 D QSEECOMAPI: : Loaded image: APP id = 4
,08-26 15:03:22.468   781  1229 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-26 15:03:22.498   781  1229 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-26 15:03:22.498   781  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:22.498   781  1625 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:03:22.498   781  1625 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:03:22.498   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:22.507   781   781 I MotionRecognitionService: Plugged
,08-26 15:03:22.507   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:03:22.507   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-26 15:03:22.507   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:03:22.507   781  1625 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
,08-26 15:03:22.507   781  1625 D BatteryService: stay LED for fully charged
,08-26 15:03:22.517  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:22.517  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:03:22.517  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:22.537  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:22.537  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:03:22.547  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:22.547  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:22.547  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:25.447   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:03:25.447   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:03:25.457   781  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:03:25.457   781  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:03:30.348   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 350, LCD = 0
,08-26 15:03:35.287   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:03:35.287   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:03:35.287   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:03:37.298   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:03:37.647   781  1574 E Watchdog: !@Sync 10 [08-26 15:03:37.649]
,08-26 15:03:38.348   781  1235 V AlarmManager: Expired Alarm result :4
,08-26 15:03:38.408   781  1235 I ActivityManager: Start proc 7066:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-26 15:03:38.418  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 15:03:38.418  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
08-26 15:03:38.418  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:03:38.428  7066  7066 E Zygote  : v2
,08-26 15:03:38.437   781  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:38.437   781  1625 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:03:38.437  7066  7066 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:03:38.437  7066  7066 I libpersona: KNOX_SDCARD not a persona
,08-26 15:03:38.437   781  1625 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-26 15:03:38.437   781  1625 D BatteryService: stay LED for fully charged
,08-26 15:03:38.437  7066  7066 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:03:38.437  7066  7066 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:03:38.447  7066  7066 E Zygote  : accessInfo : 0
,08-26 15:03:38.467  1552  1552 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 15:03:38.467  1552  1552 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-26 15:03:38.488   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:38.488  1552  1552 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:03:38.488  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:03:38.508   781   781 I MotionRecognitionService: Plugged
,08-26 15:03:38.508   781   781 D MotionRecognitionService:   cableConnection= 1
08-26 15:03:38.508   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:03:38.508   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:03:38.518  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:03:38.518  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:38.518  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 15:03:38.518  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.518  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-26 15:03:38.518  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.527  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.527  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.527  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.527  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.527  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:03:38.527  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:38.527  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:38.527  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:03:38.527  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:38.527  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:38.547  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:03:38.547  7066  7066 D ActivityThread: Added TimaKeyStore provider
,08-26 15:03:38.577  7066  7066 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-26 15:03:38.588  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:03:38.598  7066  7066 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-26 15:03:38.617   781  1717 I ActivityManager: Killing 6153:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-26 15:03:38.677   781   795 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-26 15:03:38.857  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:03:40.427   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 350, LCD = 0
,08-26 15:03:42.297  1552  1552 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
,08-26 15:03:42.307   304  1122 D Netd    : Iface wlan0 link up
,08-26 15:03:42.317   781   862 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:03:42.317   781   862 D Tethering: interfaceStatusChanged wlan0, true
,08-26 15:03:42.327  1552  1552 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-26 15:03:42.357   781  1323 D WifiP2pService: InactiveState{ what=147461 }
,08-26 15:03:42.367   781  1323 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-26 15:03:42.367   781  1323 D WifiP2pService: DefaultState{ what=147461 }
,08-26 15:03:42.427   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{c02fd76 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c0a3658 1383:com.android.systemui/u0a58}
,08-26 15:03:48.528   781  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:48.528   781  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:03:48.538   781  1319 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:03:48.538   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:48.548   781   781 I MotionRecognitionService: Plugged
,08-26 15:03:48.548   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:03:48.548   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:03:48.548   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:03:48.557   781  1319 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:03:48.557   781  1319 D BatteryService: stay LED for fully charged
,08-26 15:03:48.557  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:03:48.557  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:03:48.557  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:03:48.567  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:48.577  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:03:48.587  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:48.587  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:48.587  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:50.408   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:03:50.408   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:03:50.408   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:03:50.487   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 350, LCD = 0
,08-26 15:03:57.298   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:03:58.688   781  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:59.997   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:04:00.577   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-26 15:04:07.647   781  1574 E Watchdog: !@Sync 11 [08-26 15:04:07.651]
,08-26 15:04:08.768   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:08.778   781  2302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:04:08.778   781  2302 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:04:08.778   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:08.788   781   781 I MotionRecognitionService: Plugged
,08-26 15:04:08.788   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:04:08.788   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:04:08.797   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:04:08.797   781  2302 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:04:08.797   781  2302 D BatteryService: stay LED for fully charged
,08-26 15:04:08.807  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:08.817  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:08.817  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:04:08.837  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:08.837  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:04:08.848  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:08.848  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:08.848  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:10.637   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-26 15:04:14.607   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:04:14.607   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:04:14.607   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:04:14.777  5870  5907 I PlayCommon: [837] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:04:14.797  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:04:14.827  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:04:14.827  2102  2102 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:04:14.897  5870  5907 I PlayCommon: [837] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-26 15:04:14.907  5870  5907 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:04:14.907  5870  5907 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:04:14.927   304  1125 D EnterpriseController: netId is 0
08-26 15:04:14.927   304  1125 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-26 15:04:15.087  5870  5907 I PlayCommon: [837] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,08-26 15:04:17.308   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:04:18.887   781  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:18.887   781  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:04:18.898   781  1747 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:04:18.898   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:18.908   781   781 I MotionRecognitionService: Plugged
,08-26 15:04:18.908   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:04:18.908   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:04:18.917   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:04:18.917   781  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:04:18.917   781  1747 D BatteryService: stay LED for fully charged
,08-26 15:04:18.927  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:18.927  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:18.937  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:04:18.957  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:18.957  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:04:18.967  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:18.967  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:04:18.967  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:20.697   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-26 15:04:29.528   781  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:29.528   781  1727 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:04:29.528   781  1727 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:04:29.528   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:29.538   781   781 I MotionRecognitionService: Plugged
,08-26 15:04:29.548   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:04:29.548   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:04:29.548   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:04:29.548   781  1727 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-26 15:04:29.558   781  1727 D BatteryService: stay LED for fully charged
,08-26 15:04:29.568  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:29.568  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:29.568  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:04:29.588  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:29.588  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:04:29.598  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:29.608  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:04:29.608  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:30.757   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-26 15:04:33.288   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:04:33.288   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:04:33.288   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:04:34.648  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:04:34.648  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:04:37.307   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:04:37.648   781  1574 E Watchdog: !@Sync 12 [08-26 15:04:37.655]
,08-26 15:04:38.978  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:04:39.628   781  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:39.637   781  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:04:39.637   781  1489 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:04:39.637   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:39.647   781   781 I MotionRecognitionService: Plugged
,08-26 15:04:39.647   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:04:39.657   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:04:39.657   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:04:39.657   781  1489 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:04:39.667   781  1489 D BatteryService: stay LED for fully charged
,08-26 15:04:39.677  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:39.677  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:04:39.688  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:04:39.698  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:39.708  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:04:39.718  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:39.718  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:04:39.718  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:40.817   781  3423 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 350, LCD = 0
,08-26 15:04:49.818   781   795 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:50.898   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 350, LCD = 0
,08-26 15:04:57.307   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:04:59.987   781  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:59.987   781  1489 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:04:59.997   781  1489 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:04:59.997   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:05:00.007   781   781 I MotionRecognitionService: Plugged
,08-26 15:05:00.007   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:05:00.007   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:05:00.007   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:05:00.017   781  1489 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:05:00.017   781  1489 D BatteryService: stay LED for fully charged
,08-26 15:05:00.027  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:00.037  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:00.037  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:05:00.057  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:00.057  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:05:00.067  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:00.067  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:00.067  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:00.958   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 350, LCD = 0
,08-26 15:05:07.658   781  1574 E Watchdog: !@Sync 13 [08-26 15:05:07.660]
,08-26 15:05:10.098   781   795 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:10.098   781   795 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:05:10.108   781   795 D BatteryService: online:4, current avg:350, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:05:10.108   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:05:10.118   781   781 I MotionRecognitionService: Plugged
,08-26 15:05:10.118   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:05:10.118   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:05:10.127   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:05:10.127   781   795 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:05:10.127   781   795 D BatteryService: stay LED for fully charged
,08-26 15:05:10.137  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:10.147  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:10.147  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:05:10.167  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:10.167  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:05:10.177  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:10.177  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:10.177  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:11.018   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 350, LCD = 0
,08-26 15:05:13.817   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:05:13.817   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:05:13.817   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:05:17.317   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:05:20.227   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:20.227   781   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:05:20.227   781   794 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:05:20.227   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:05:20.237   781   781 I MotionRecognitionService: Plugged
,08-26 15:05:20.247   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:05:20.247   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:05:20.247   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:05:20.257   781   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-26 15:05:20.257   781   794 D BatteryService: stay LED for fully charged
,08-26 15:05:20.267  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:20.267  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:20.267  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:05:20.287  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:20.287  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:05:20.297  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:20.297  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:20.297  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:21.078   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 350, LCD = 0
,08-26 15:05:31.158   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 350, LCD = 0
,08-26 15:05:33.208   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:05:33.208   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:05:33.208   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:05:37.318   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:05:37.657   781  1574 E Watchdog: !@Sync 14 [08-26 15:05:37.664]
,08-26 15:05:39.097  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:05:39.247  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 142ms lastUpdatedAfter : 180474ms
,08-26 15:05:41.248   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 350, LCD = 0
,08-26 15:05:51.018   781   795 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:51.018   781   795 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:05:51.018   781   795 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:05:51.018   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:05:51.028   781   781 I MotionRecognitionService: Plugged
,08-26 15:05:51.038   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:05:51.038   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:05:51.038   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:05:51.048   781   795 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:05:51.048   781   795 D BatteryService: stay LED for fully charged
,08-26 15:05:51.058  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:51.058  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:05:51.068  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:05:51.088  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:51.088  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:05:51.098  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:51.098  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:05:51.098  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:51.307   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 350, LCD = 0
,08-26 15:05:57.318   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:06:01.398   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 350, LCD = 0
,08-26 15:06:07.667   781  1574 E Watchdog: !@Sync 15 [08-26 15:06:07.669]
,08-26 15:06:11.478   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 350, LCD = 0
,08-26 15:06:12.147   353   353 I bootchecker: bootchecker wake up!!
,08-26 15:06:17.327   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:06:21.157   781  1810 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:21.167   781  1810 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:06:21.167   781  1810 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:06:21.167   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:06:21.177   781   781 I MotionRecognitionService: Plugged
,08-26 15:06:21.177   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:06:21.187   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:06:21.187   781  1810 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
,08-26 15:06:21.187   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:06:21.187   781  1810 D BatteryService: stay LED for fully charged
,08-26 15:06:21.207  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:06:21.207  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:06:21.207  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:06:21.227  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:06:21.237  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:06:21.247  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:06:21.247  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:06:21.247  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:06:21.527   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:06:31.617   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:06:37.327   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:06:37.668   781  1574 E Watchdog: !@Sync 16 [08-26 15:06:37.673]
,08-26 15:06:39.318  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:06:41.698   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:06:51.337   781  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:51.337   781  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:06:51.337   781  1747 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:06:51.337   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:06:51.357   781   781 I MotionRecognitionService: Plugged
,08-26 15:06:51.357   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:06:51.357   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:06:51.357   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:06:51.367   781  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:06:51.367   781  1747 D BatteryService: stay LED for fully charged
,08-26 15:06:51.377  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:06:51.377  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:06:51.387  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:06:51.407  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:06:51.407  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:06:51.417  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:06:51.417  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:06:51.417  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:06:51.747   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:06:57.327   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:06:59.998   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:06:59.998   781  1235 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=533418 batch.start=691712
,08-26 15:07:00.008  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 15:07:00.008  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-26 15:07:00.008  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:07:00.038  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:07:00.048  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:07:00.057  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.057  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.057  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.057  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.067  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.077  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.077  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:00.127  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:07:01.838   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:07:07.678   781  1574 E Watchdog: !@Sync 17 [08-26 15:07:07.679]
,08-26 15:07:11.918   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:07:17.338   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:07:21.487   781  1731 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:22.008   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:07:32.098   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:07:37.338   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:07:37.677   781  1574 E Watchdog: !@Sync 18 [08-26 15:07:37.683]
,08-26 15:07:39.418  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:07:42.177   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:07:47.598   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:07:47.598   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:07:47.598   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:07:51.658   781   795 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:51.658   781   795 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:07:51.658   781   795 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:07:51.667   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:51.677   781   781 I MotionRecognitionService: Plugged
,08-26 15:07:51.677   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:07:51.677   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:07:51.677   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:07:51.687   781   795 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,08-26 15:07:51.687   781   795 D BatteryService: stay LED for fully charged
,08-26 15:07:51.697  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:07:51.707  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:07:51.707  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:07:51.728  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:51.737  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:07:51.747  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:51.747  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:07:51.747  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:52.228   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:07:57.347   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:07:59.997   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:08:02.318   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:08:02.647   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:08:02.647   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:08:02.647   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:08:07.678   781  1574 E Watchdog: !@Sync 19 [08-26 15:08:07.687]
,08-26 15:08:12.408   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:08:15.968   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:08:15.968   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:08:15.968   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:08:17.348   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:08:21.838   781  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:21.838   781  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:08:21.838   781  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:08:21.838   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:08:21.858   781  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,08-26 15:08:21.858   781  1791 D BatteryService: stay LED for fully charged
,08-26 15:08:21.868   781   781 I MotionRecognitionService: Plugged
,08-26 15:08:21.868   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:08:21.868   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:08:21.878   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:08:21.878  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:08:21.878  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:08:21.887  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:08:21.897  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:08:21.907  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:08:21.917  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:21.917  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:08:21.917  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:22.368   781  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:08:22.368   781  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:08:22.368   781  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:08:22.457   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:08:23.647   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:08:23.647   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:08:23.657   781  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:08:23.657   781  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:08:31.008   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:08:31.008   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:08:31.008   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:08:32.557   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:08:37.347   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:08:37.688   781  1574 E Watchdog: !@Sync 20 [08-26 15:08:37.691]
,08-26 15:08:39.527  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:08:39.677  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 136ms lastUpdatedAfter : 180428ms
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLoc,ked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false,
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false,
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-26 15:08:41.257   781   838 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-26 15:08:41.337   781   902 I ActivityManager: setMaxStartingBackgroundTimer onfinish,
08-26 15:08:41.337   781   902 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,08-26 15:08:42.648   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:08:51.997   781  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:51.997   781  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:08:51.997   781  1319 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:08:52.007   781  1319 D BatteryService: stay LED for fully charged
,08-26 15:08:52.007   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:08:52.027   781   781 I MotionRecognitionService: Plugged
,08-26 15:08:52.027   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:08:52.037   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:08:52.037   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:08:52.037  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:08:52.037  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:08:52.047  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:08:52.067  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:08:52.067  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:08:52.077  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:52.077  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:52.077  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:52.697   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:08:57.358   781  3461 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:09:02.788   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:09:07.688   781  1574 E Watchdog: !@Sync 21 [08-26 15:09:07.695]
,08-26 15:09:12.878   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:09:15.137   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:09:15.137   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:09:15.137   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:09:15.158   781  1747 I ActivityManager: Killing 4443:com.wssyncmldm/1000 (adj 8): SSR - service for lastStateTime 616s, lastActivityTime 606s
,08-26 15:09:15.158   781  1747 I ActivityManager: Killing 3788:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 608s
,08-26 15:09:15.168   781  1747 I ActivityManager: Killing 4586:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 616s, lastActivityTime 616s
,08-26 15:09:15.168   781  1747 I ActivityManager: Killing 3860:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 620s, lastActivityTime 620s
,08-26 15:09:15.217   292   292 I ServiceManager: service 'AtCmdFwd' died
,08-26 15:09:15.217   372  4798 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,08-26 15:09:15.227   372  4798 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:09:15.227   781  1319 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,08-26 15:09:15.227   781  1319 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
08-26 15:09:15.227   781  1319 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,08-26 15:09:15.267   781  1642 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,08-26 15:09:15.267   781  1642 I ActivityManager: isWidgetUsingPkg : com.wssyncmldm no widget is using.
,08-26 15:09:15.277   781  1489 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,08-26 15:09:15.277   781  1489 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-26 15:09:15.277   781  1489 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10946ms
,08-26 15:09:15.297   781  1731 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
08-26 15:09:15.297   781  1731 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,08-26 15:09:16.237   372  4798 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:09:16.307   781   854 I ActivityManager: Start proc 7159:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,08-26 15:09:16.317  7159  7159 E Zygote  : v2
,08-26 15:09:16.317  7159  7159 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:09:16.317  7159  7159 I libpersona: KNOX_SDCARD not a persona
,08-26 15:09:16.317  7159  7159 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:09:16.327  7159  7159 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:09:16.327  7159  7159 E Zygote  : accessInfo : 0
,08-26 15:09:16.377  7159  7159 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:09:16.377  7159  7159 D ActivityThread: Added TimaKeyStore provider
,08-26 15:09:16.397  7159  7159 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,08-26 15:09:16.417  7159  7159 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,08-26 15:09:16.417  7159  7159 D AtFwdService: onCreate method
,08-26 15:09:16.417  7159  7159 I AtFwdService: Instantiate AtCmdFwd Service
,08-26 15:09:16.437  7159  7171 D AtCkpdCmdHandler: De-queing command
,08-26 15:09:22.107   781  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:22.118   781  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:09:22.118   781  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:09:22.118   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:09:22.128   781   781 I MotionRecognitionService: Plugged
,08-26 15:09:22.128   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:09:22.138   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:09:22.138   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:09:22.138   781  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:09:22.138   781  1791 D BatteryService: stay LED for fully charged
,08-26 15:09:22.158  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:09:22.158  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:09:22.158  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:09:22.177  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:09:22.187  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:09:22.197  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:09:22.197  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:09:22.197  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:09:22.928   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:09:26.288  7173  7173 E Zygote  : v2
,08-26 15:09:26.288   781   854 I ActivityManager: Start proc 7173:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,08-26 15:09:26.297  7173  7173 I libpersona: KNOX_SDCARD checking this for 10026
08-26 15:09:26.297  7173  7173 I libpersona: KNOX_SDCARD not a persona
,08-26 15:09:26.297  7173  7173 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:09:26.297  7173  7173 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:09:26.297  7173  7173 E Zygote  : accessInfo : 0
,08-26 15:09:26.297  7173  7173 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,08-26 15:09:26.347  7173  7173 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:09:26.347  7173  7173 D ActivityThread: Added TimaKeyStore provider
,08-26 15:09:26.367  7173  7173 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,08-26 15:09:26.387  7173  7173 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,08-26 15:09:26.397  7173  7173 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,08-26 15:09:26.407  7173  7173 D ContextualPageNotification: resetAllNotification : all clear!!!
,08-26 15:09:30.248   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:09:30.248   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:09:30.248   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:09:33.028   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:09:34.757  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:09:34.757  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:09:37.698   781  1574 E Watchdog: !@Sync 22 [08-26 15:09:37.700]
,08-26 15:09:38.287   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:09:39.788  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:09:43.118   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:09:52.327   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:53.167   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:09:59.457   781   791 I art     : Background sticky concurrent mark sweep GC freed 81101(8MB) AllocSpace objects, 308(6MB) LOS objects, 26% free, 42MB/58MB, paused 2.536ms total 159.728ms
,08-26 15:10:03.257   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:10:07.697   781  1574 E Watchdog: !@Sync 23 [08-26 15:10:07.704]
,08-26 15:10:13.357   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:10:22.537   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:22.547   781  2302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:10:22.547   781  2302 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:10:22.547   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:22.557   781   781 I MotionRecognitionService: Plugged
,08-26 15:10:22.557   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:10:22.568   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:10:22.568   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:10:22.568   781  2302 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,08-26 15:10:22.568   781  2302 D BatteryService: stay LED for fully charged
,08-26 15:10:22.588  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:22.588  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:22.588  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:22.608  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:22.608  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:10:22.617  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:22.627  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:22.627  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:23.407   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:10:33.497   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:10:37.707   781  1574 E Watchdog: !@Sync 24 [08-26 15:10:37.709]
,08-26 15:10:39.928  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:10:43.598   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:10:52.678   781   795 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:53.668   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:11:03.727   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:11:07.708   781  1574 E Watchdog: !@Sync 25 [08-26 15:11:07.717]
,08-26 15:11:10.828   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:11:13.787   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:11:22.817   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:22.828   781   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:11:22.828   781   794 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:11:22.828   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:11:22.838   781   781 I MotionRecognitionService: Plugged
,08-26 15:11:22.838   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:11:22.848   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:11:22.848   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:11:22.848   781   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:11:22.848   781   794 D BatteryService: stay LED for fully charged
,08-26 15:11:22.867  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:11:22.867  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:11:22.867  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:11:22.887  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:11:22.887  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:11:22.897  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:11:22.907  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:11:22.907  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:11:23.847   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:11:33.947   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:11:37.717   781  1574 E Watchdog: !@Sync 26 [08-26 15:11:37.726]
,08-26 15:11:40.037  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:11:40.187  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 137ms lastUpdatedAfter : 180508ms
,08-26 15:11:41.457   781  2259 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-26 15:11:41.457   781  2259 V MARsPolicyManager: updateSMDBValues
,08-26 15:11:41.457   781   899 E MARsDBManager: updateDBAll : begin --size 1
,08-26 15:11:41.477   781   899 I ActivityManager: Killing 1888:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 781s, lastActivityTime 704s
,08-26 15:11:41.487   781   899 I ActivityManager: Killing 6538:com.samsung.android.sdk.samsunglink/u0a41 (adj 8): SSR - service for lastStateTime 707s, lastActivityTime 707s
,08-26 15:11:41.487   781   899 I ActivityManager: Killing 1511:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 722s, lastActivityTime 722s
,08-26 15:11:41.517   781   899 E MARsDBManager: updateDBAll : end
,08-26 15:11:41.517   781   899 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-26 15:11:41.597   781  1717 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,08-26 15:11:41.597   781  1717 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,08-26 15:11:41.607  5920  5920 D HealthConsole: Service for HealthDataStore is disconnected
08-26 15:11:41.617   781  1731 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
08-26 15:11:41.617   781  1731 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-26 15:11:41.617   781  1731 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
,08-26 15:11:41.637   781  2302 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
08-26 15:11:41.637   781  2302 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
08-26 15:11:41.637   781  2302 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 10989ms
,08-26 15:11:41.677  7209  7209 E Zygote  : v2
08-26 15:11:41.677  7209  7209 I libpersona: KNOX_SDCARD checking this for 10034
08-26 15:11:41.677  7209  7209 I libpersona: KNOX_SDCARD not a persona
08-26 15:11:41.677   781  1727 I ActivityManager: Start proc 7209:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,08-26 15:11:41.677  7209  7209 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 15:11:41.677  7209  7209 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:11:41.687  7209  7209 E Zygote  : accessInfo : 0
,08-26 15:11:41.687  7209  7209 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,08-26 15:11:41.727  7209  7209 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:11:41.727  7209  7209 D ActivityThread: Added TimaKeyStore provider
,08-26 15:11:41.747  7209  7209 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-26 15:11:41.787  7209  7209 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-26 15:11:41.797  7209  7209 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:11:41.797  7209  7209 I MultiDex: install
08-26 15:11:41.797  7209  7209 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-26 15:11:41.797  7209  7209 I MultiDex: install
08-26 15:11:41.797  7209  7209 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:11:42.077  7232  7232 E Zygote  : v2
,08-26 15:11:42.087   781  1727 I ActivityManager: Start proc 7232:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,08-26 15:11:42.097  7232  7232 I libpersona: KNOX_SDCARD checking this for 10016
,08-26 15:11:42.097  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-26 15:11:42.107  7232  7232 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:11:42.107  7232  7232 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:11:42.107  7232  7232 E Zygote  : accessInfo : 0
,08-26 15:11:42.107  7232  7232 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,08-26 15:11:42.147  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:11:42.147  7232  7232 D ActivityThread: Added TimaKeyStore provider
,08-26 15:11:42.177  7232  7232 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,08-26 15:11:42.207  7209  7209 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-26 15:11:42.207  7209  7209 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-26 15:11:42.227  1383  1383 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,08-26 15:11:42.237   781  1791 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,08-26 15:11:42.247   781  1625 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,08-26 15:11:42.247  1383  1383 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{e98879 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
08-26 15:11:42.247  1383  1383 D AdaptiveEventManager: M updateContainers()
08-26 15:11:42.247  1383  1383 D AdaptiveEventContainerSmall: C updatePedoContainer()
08-26 15:11:42.247  1383  1383 D AdaptiveEventContainerSmall: handlePedoUpdate()
,08-26 15:11:42.257  1383  1383 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,08-26 15:11:42.257   781  1717 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,08-26 15:11:42.267   781  1642 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,08-26 15:11:42.287  7209  7209 I Health.HealthService: HealthService: onCreate() start (7209)
,08-26 15:11:42.377  5920  5920 D HealthDataStore: Service for HealthDataStore is connected
,08-26 15:11:42.377  5920  5920 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-26 15:11:42.397   781  1319 I ActivityManager: Killing 6208:com.android.email/u0a162 (adj 15): DHA:empty #37
,08-26 15:11:42.427  5920  5920 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-26 15:11:42.427  5920  5920 E HealthDataStore: disconnectService: Context instance is invalid
,08-26 15:11:42.477   781  1791 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,08-26 15:11:42.497  7209  7209 D HealthDataStore: Service for HealthDataStore is connected
,08-26 15:11:42.497  7209  7209 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-26 15:11:42.497  7209  7209 D HealthConsole: Service for HealthDataConsole is connected
,08-26 15:11:42.507  7209  7209 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-26 15:11:42.507  7209  7209 E HealthDataStore: disconnectService: Context instance is invalid
,08-26 15:11:42.697  7209  7246 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,08-26 15:11:42.757  7209  7269 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,08-26 15:11:42.777  7232  7243 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 15:11:42.777   382   382 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 7232
08-26 15:11:42.777   382   382 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,08-26 15:11:42.947  7232  7243 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,08-26 15:11:43.127  7209  7269 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,08-26 15:11:43.267  7209  7269 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-26 15:11:43.277  7209  7269 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-26 15:11:43.377   382   382 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,08-26 15:11:43.427  7232  7243 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,08-26 15:11:43.427  7232  7243 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,08-26 15:11:43.427  7232  7243 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,08-26 15:11:44.047   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:11:52.687  7291  7291 E Zygote  : v2
,08-26 15:11:52.687  7291  7291 I libpersona: KNOX_SDCARD checking this for 10181
08-26 15:11:52.687  7291  7291 I libpersona: KNOX_SDCARD not a persona
,08-26 15:11:52.687  7291  7291 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-26 15:11:52.687  7291  7291 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:11:52.697  7291  7291 E Zygote  : accessInfo : 0
,08-26 15:11:52.697   781   854 I ActivityManager: Start proc 7291:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
08-26 15:11:52.697   781  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-26 15:11:52.697  7291  7291 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,08-26 15:11:52.747  7291  7291 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:11:52.747  7291  7291 D ActivityThread: Added TimaKeyStore provider
,08-26 15:11:52.767   781  1322 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-26 15:11:52.767  7291  7291 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null,
,08-26 15:11:52.797  7291  7291 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,08-26 15:11:52.827  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,08-26 15:11:52.837  7291  7291 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-26 15:11:52.847   781   854 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{85359c8 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9885a61 7291:com.sec.android.daemonapp/u0a181}
,08-26 15:11:52.857  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,08-26 15:11:52.857  7291  7291 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-26 15:11:52.867  7291  7291 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,08-26 15:11:52.867  7291  7291 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-26 15:11:52.867  7291  7291 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,08-26 15:11:52.867  7291  7291 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-26 15:11:52.877   781  1810 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:52.877   781  1810 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-26 15:11:52.877   781  1810 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
08-26 15:11:52.877   781  1810 D BatteryService: stay LED for fully charged
,08-26 15:11:52.877   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:11:52.877   781   781 I MotionRecognitionService: Plugged
,08-26 15:11:52.877   781   781 D MotionRecognitionService:   cableConnection= 1
08-26 15:11:52.877   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-26 15:11:52.877   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:11:52.887  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:11:52.887  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:11:52.887  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:11:52.897  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:11:52.897  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:11:52.907  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:11:52.907  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:11:52.907  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:11:52.917  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-26 15:11:52.917  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-26 15:11:52.927  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,08-26 15:11:52.927  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-26 15:11:52.927  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-26 15:11:52.927  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,08-26 15:11:52.937  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-26 15:11:52.957  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,08-26 15:11:52.957  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-26 15:11:52.957  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-26 15:11:52.957  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,08-26 15:11:52.967  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-26 15:11:52.967  7291  7291 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-26 15:11:52.967  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 15:11:52.967  7291  7291 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-26 15:11:52.967  7291  7291 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 15:11:52.967  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 15:11:52.967  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-26 15:11:52.977  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-26 15:11:52.977  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-26 15:11:52.977  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-26 15:11:52.977  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-26 15:11:52.977  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:52.977  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-26 15:11:52.987   781   795 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{98f3b9d u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9885a61 7291:com.sec.android.daemonapp/u0a181}
,08-26 15:11:52.997  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-26 15:11:52.997  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-26 15:11:52.997  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:11:52.997  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:52.997  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-26 15:11:52.997  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:11:53.007  7291  7291 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-26 15:11:53.007  7291  7291 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 15:11:53.007  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:53.007  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-26 15:11:53.017   781  1727 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e946812 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9885a61 7291:com.sec.android.daemonapp/u0a181}
,08-26 15:11:53.017  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-26 15:11:53.017  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-26 15:11:53.017  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-26 15:11:53.027  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:11:53.027  7291  7291 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-26 15:11:53.027  7291  7291 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 15:11:53.027  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-26 15:11:53.027  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:53.037  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-26 15:11:53.037   781  1642 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cd1fbe3 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9885a61 7291:com.sec.android.daemonapp/u0a181}
,08-26 15:11:53.047  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-26 15:11:53.047  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-26 15:11:53.047  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:11:53.047  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-26 15:11:53.057  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:11:53.057  7291  7291 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-26 15:11:53.057  7291  7291 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 15:11:53.057  7291  7291 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 15:11:53.057  7291  7291 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-26 15:11:54.107   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:12:04.207   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:12:07.727   781  1574 E Watchdog: !@Sync 27 [08-26 15:12:07.731]
,08-26 15:12:14.298   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:12:23.028   781  1727 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:24.368   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:12:34.457   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:12:37.727   781  1574 E Watchdog: !@Sync 28 [08-26 15:12:37.735]
,08-26 15:12:40.297  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:12:44.558   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 350, LCD = 0
,08-26 15:12:53.388   781  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:53.388   781  1319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:12:53.388   781  1319 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:12:53.398   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:12:53.398   781   781 I MotionRecognitionService: Plugged
,08-26 15:12:53.408   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:12:53.408   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:12:53.408   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:12:53.408   781  1319 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,08-26 15:12:53.418   781  1319 D BatteryService: stay LED for fully charged
,08-26 15:12:53.428  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:12:53.428  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:12:53.428  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:12:53.458  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:12:53.458  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:12:53.468  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:12:53.468  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:12:53.468  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:12:54.618   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 350, LCD = 0
,08-26 15:13:04.717   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 350, LCD = 0
,08-26 15:13:07.738   781  1574 E Watchdog: !@Sync 29 [08-26 15:13:07.740]
,08-26 15:13:14.818   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 350, LCD = 0
,08-26 15:13:22.367   781  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:13:22.367   781  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:13:22.367   781  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:13:23.487   781  1810 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:23.487   781  1810 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:13:23.497   781  1810 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:13:23.497   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:23.507   781   781 I MotionRecognitionService: Plugged
,08-26 15:13:23.507   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:13:23.517   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:13:23.517   781  1810 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:13:23.517   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:13:23.517   781  1810 D BatteryService: stay LED for fully charged
,08-26 15:13:23.527  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:13:23.527  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:13:23.527  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:13:23.537  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:13:23.537  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:13:23.547  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:23.547  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:23.557  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:24.887   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 307, CUR = 350, LCD = 0
,08-26 15:13:25.307   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:13:25.307   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:13:25.317   781  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:13:25.317   781  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:13:34.988   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 307, CUR = 350, LCD = 0
,08-26 15:13:37.737   781  1574 E Watchdog: !@Sync 30 [08-26 15:13:37.744]
,08-26 15:13:40.417  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:13:43.777   781  1235 V AlarmManager: Expired Alarm result :4
,08-26 15:13:43.817  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 15:13:43.817  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
08-26 15:13:43.817  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:13:43.827  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:13:43.827  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:13:43.837  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.837  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.837  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.847  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.847   781   854 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,08-26 15:13:43.867  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.867  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.867  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.877   781   781 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,08-26 15:13:43.877   781   781 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,08-26 15:13:43.888   781   781 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,08-26 15:13:43.898   781   781 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,08-26 15:13:43.918  2158  2364 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-26 15:13:43.918  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.918  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-26 15:13:43.918  2158  2364 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-26 15:13:43.918  2158  2364 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
08-26 15:13:43.918  2158  2364 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-26 15:13:43.918  2158  2433 D bt_upio : upio_start_stop_timer : timer_settime success
,08-26 15:13:43.918  2158  2433 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-26 15:13:43.928  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.928  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-26 15:13:43.928  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.937  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.937  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.937  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.937  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.937  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.937  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.937  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.937  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.937  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.937  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.937  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.937  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.937  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.937  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.937  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.947  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.947  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.947  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.957  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.957  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.957  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.957  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.957  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.957  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.957  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.957  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.957  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.957  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.957  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.957  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.957  2158  2433 D bt_vendor: op for 7
08-26 15:13:43.957  2158  2433 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-26 15:13:43.957  2158  2433 D bt_upio : BT_WAKE is asserted already
,08-26 15:13:43.967   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{a70e76a: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:43.987  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-26 15:13:43.987   781  1489 V AlarmManager:  remove PendingIntent] PendingIntent{e91045b: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:43.997   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{c74c4f8: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.017   781  1412 V AlarmManager:  remove PendingIntent] PendingIntent{18b9dd1: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.027   781  1810 V AlarmManager:  remove PendingIntent] PendingIntent{32e1036: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.027   781  1642 V AlarmManager:  remove PendingIntent] PendingIntent{3518b37: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.037   781  1319 V AlarmManager:  remove PendingIntent] PendingIntent{5ad38a4: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.037   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{4db460d: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.047   781  1625 V AlarmManager:  remove PendingIntent] PendingIntent{bc2f9c2: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.047   781  1717 V AlarmManager:  remove PendingIntent] PendingIntent{829a3d3: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.057   781   795 V AlarmManager:  remove PendingIntent] PendingIntent{1d73b10: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.057   781  1791 V AlarmManager:  remove PendingIntent] PendingIntent{b033609: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.057   781  2274 V AlarmManager:  remove PendingIntent] PendingIntent{ecaf00e: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.067   781  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a60aa2f: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.067   781  1412 V AlarmManager:  remove PendingIntent] PendingIntent{e5cf83c: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.077   781  1727 V AlarmManager:  remove PendingIntent] PendingIntent{ba029c5: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.077   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{349ff1a: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.087   781  2302 V AlarmManager:  remove PendingIntent] PendingIntent{a57ba4b: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.097   781  1489 V AlarmManager:  remove PendingIntent] PendingIntent{31f5c28: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.097   781  1810 V AlarmManager:  remove PendingIntent] PendingIntent{15e9d41: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.107   781  1642 V AlarmManager:  remove PendingIntent] PendingIntent{a78f2e6: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.107   781  1319 V AlarmManager:  remove PendingIntent] PendingIntent{365b027: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.117   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{32212d4: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.117   781  1810 V AlarmManager:  remove PendingIntent] PendingIntent{b36cc7d: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.127   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{e515772: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.127   781  1747 V AlarmManager:  remove PendingIntent] PendingIntent{57327c3: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.127   781   795 V AlarmManager:  remove PendingIntent] PendingIntent{bf78840: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.137   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{568b379: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.137   781  1810 V AlarmManager:  remove PendingIntent] PendingIntent{cd978be: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.137   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{c567d1f: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.147   781  1747 V AlarmManager:  remove PendingIntent] PendingIntent{fece86c: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.147   781   795 V AlarmManager:  remove PendingIntent] PendingIntent{6380e35: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.147   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{c3062ca: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.157   781  1810 V AlarmManager:  remove PendingIntent] PendingIntent{efcc3b: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.157   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{6f61f58: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.167   781  1747 V AlarmManager:  remove PendingIntent] PendingIntent{a6858b1: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.167   781   795 V AlarmManager:  remove PendingIntent] PendingIntent{359e196: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.177   781  1731 V AlarmManager:  remove PendingIntent] PendingIntent{4f117: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.177   781  1810 V AlarmManager:  remove PendingIntent] PendingIntent{259d904: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.187   781   794 V AlarmManager:  remove PendingIntent] PendingIntent{d78ceed: PendingIntentRecord{70b4155 com.android.bluetooth broadcastIntent}}
,08-26 15:13:44.257   781  1218 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,08-26 15:13:44.257   781   913 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,08-26 15:13:44.257   781   913 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,08-26 15:13:44.267   781   913 D SensorManager: unregisterListener ::   
,08-26 15:13:44.267   781   913 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
08-26 15:13:44.267   781   913 V AlarmManager:  remove PendingIntent] PendingIntent{1d24369: PendingIntentRecord{a18e68f android broadcastIntent}}
,08-26 15:13:44.717  2158  2700 D bt_upio : ..proc_btwrite_timeout..,
08-26 15:13:44.717  2158  2700 D bt_upio : upio_set : pio 0 action 1, polarity 1,
,08-26 15:13:45.087   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 307, CUR = 350, LCD = 0
,08-26 15:13:53.738   781  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:53.738   781  1642 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:13:53.738   781  1642 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:13:53.748   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:53.758   781   781 I MotionRecognitionService: Plugged
,08-26 15:13:53.758   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:13:53.758   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:13:53.758   781  1642 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,08-26 15:13:53.758   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:13:53.768   781  1642 D BatteryService: stay LED for fully charged
,08-26 15:13:53.778  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:13:53.778  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:13:53.788  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:13:53.808  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:13:53.808  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:13:53.818  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:53.818  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:13:53.818  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:55.167   781  3423 D SSRM:n  : SIOP:: AP = 310, PST = 307, CUR = 350, LCD = 0
,08-26 15:13:59.997   781  1235 V AlarmManager: Expired Alarm result :8
,08-26 15:14:05.257   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 350, LCD = 0
,08-26 15:14:07.747   781  1574 E Watchdog: !@Sync 31 [08-26 15:14:07.749]
,08-26 15:14:15.368   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 350, LCD = 0
,08-26 15:14:23.928   781  1319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:25.438   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 350, LCD = 0
,08-26 15:14:34.868  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:14:34.868  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:14:35.507   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 350, LCD = 0
,08-26 15:14:37.748   781  1574 E Watchdog: !@Sync 32 [08-26 15:14:37.753]
,08-26 15:14:40.537  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:14:40.687  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 145ms lastUpdatedAfter : 180499ms
,08-26 15:14:45.567   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 350, LCD = 0
,08-26 15:14:54.128   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:54.128   781  2302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:14:54.138   781  2302 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:14:54.138   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:14:54.148   781   781 I MotionRecognitionService: Plugged
,08-26 15:14:54.148   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:14:54.148   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:14:54.158   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:14:54.158   781  2302 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:14:54.158   781  2302 D BatteryService: stay LED for fully charged
,08-26 15:14:54.168  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:14:54.178  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:14:54.178  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:14:54.198  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:14:54.198  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:14:54.207  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:54.207  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:54.207  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:55.627   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 350, LCD = 0
,08-26 15:15:05.728   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 350, LCD = 0
,08-26 15:15:07.757   781  1574 E Watchdog: !@Sync 33 [08-26 15:15:07.764]
,08-26 15:15:15.828   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 350, LCD = 0
,08-26 15:15:24.308   781  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:24.308   781  1412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:15:24.308   781  1412 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:15:24.308   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:15:24.318   781   781 I MotionRecognitionService: Plugged
,08-26 15:15:24.318   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:15:24.328   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:15:24.328   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:15:24.328   781  1412 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-26 15:15:24.328   781  1412 D BatteryService: stay LED for fully charged
,08-26 15:15:24.348  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:15:24.348  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:15:24.348  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:15:24.368  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:15:24.368  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:15:24.378  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:24.388  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:24.388  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:25.888   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 350, LCD = 0
,08-26 15:15:35.987   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:15:37.768   781  1574 E Watchdog: !@Sync 34 [08-26 15:15:37.769]
,08-26 15:15:40.798  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:15:46.087   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:15:54.458   781  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:54.458   781  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:15:54.458   781  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:15:54.467   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:15:54.477   781   781 I MotionRecognitionService: Plugged
,08-26 15:15:54.477   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:15:54.477   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:15:54.477   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:15:54.477   781  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-26 15:15:54.487   781  1791 D BatteryService: stay LED for fully charged
,08-26 15:15:54.497  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:15:54.497  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:15:54.507  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:15:54.517  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:15:54.527  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:15:54.537  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:54.537  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:15:54.537  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:56.147   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:16:06.247   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:16:07.767   781  1574 E Watchdog: !@Sync 35 [08-26 15:16:07.773]
,08-26 15:16:16.347   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:16:24.608   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:24.608   781   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:16:24.608   781   794 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:16:24.608   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:24.618   781   781 I MotionRecognitionService: Plugged
,08-26 15:16:24.628   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:16:24.628   781   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 22ms
,08-26 15:16:24.628   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:16:24.628   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:16:24.638   781   794 D BatteryService: stay LED for fully charged
,08-26 15:16:24.648  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:16:24.648  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:16:24.648  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:16:24.667  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:24.667  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:16:24.677  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:24.687  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:16:24.687  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:26.397   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:16:36.497   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:16:37.777   781  1574 E Watchdog: !@Sync 36 [08-26 15:16:37.779]
,08-26 15:16:40.917  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:16:46.598   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:16:54.747   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:56.668   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:17:06.777   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:17:07.777   781  1574 E Watchdog: !@Sync 37 [08-26 15:17:07.783]
,08-26 15:17:16.878   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:17:24.907   781  1642 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:26.948   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:17:37.058   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:17:37.787   781  1574 E Watchdog: !@Sync 38 [08-26 15:17:37.789]
,08-26 15:17:41.037  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:17:41.218  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 175ms lastUpdatedAfter : 180531ms
,08-26 15:17:47.118   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:17:55.187   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:55.187   781   794 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:17:55.187   781   794 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:17:55.187   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:55.197   781   781 I MotionRecognitionService: Plugged
,08-26 15:17:55.207   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:17:55.207   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:17:55.207   781   794 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 21ms
,08-26 15:17:55.207   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:17:55.207   781   794 D BatteryService: stay LED for fully charged
,08-26 15:17:55.227  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:17:55.227  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:17:55.227  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:17:55.247  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:55.247  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:17:55.257  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:55.267  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:55.267  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:57.167   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:18:07.257   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:18:07.788   781  1574 E Watchdog: !@Sync 39 [08-26 15:18:07.793]
,08-26 15:18:17.357   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:18:22.367   781  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:18:22.367   781  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:18:22.367   781  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:18:23.647   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:18:23.647   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:18:23.657   781  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:18:23.657   781  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:18:25.358   781  2302 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:25.358   781  2302 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:18:25.358   781  2302 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:18:25.358   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:25.368   781   781 I MotionRecognitionService: Plugged
,08-26 15:18:25.378   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:18:25.378   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:18:25.378   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:18:25.378   781  2302 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,08-26 15:18:25.388   781  2302 D BatteryService: stay LED for fully charged
,08-26 15:18:25.398  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:18:25.398  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:18:25.398  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:18:25.418  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:18:25.418  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:18:25.428  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:25.428  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:18:25.438  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:27.427   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:18:34.448   781   838 I UsageStatsService: User[0] Flushing usage stats to disk
,08-26 15:18:37.527   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:18:37.787   781  1574 E Watchdog: !@Sync 40 [08-26 15:18:37.798]
,08-26 15:18:41.327  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:18:47.627   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:18:55.527   781  2274 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:55.537   781  2274 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:18:55.537   781  2274 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:18:55.537   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:55.547   781   781 I MotionRecognitionService: Plugged
,08-26 15:18:55.547   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:18:55.547   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:18:55.557   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:18:55.557   781  2274 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:18:55.557   781  2274 D BatteryService: stay LED for fully charged
,08-26 15:18:55.577  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:18:55.577  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:18:55.577  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:18:55.597  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:18:55.597  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:18:55.607  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:55.617  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:55.617  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:57.687   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:19:07.788   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:19:07.788   781  1574 E Watchdog: !@Sync 41 [08-26 15:19:07.802]
,08-26 15:19:15.198  5870  5907 I PlayCommon: [837] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:19:15.198  5870  5907 I PlayCommon: [837] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:19:17.887   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:19:25.698   781  1791 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:25.698   781  1791 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:19:25.708   781  1791 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:19:25.708   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:19:25.718   781   781 I MotionRecognitionService: Plugged
,08-26 15:19:25.718   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:19:25.718   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:19:25.718   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:19:25.728   781  1791 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,08-26 15:19:25.728   781  1791 D BatteryService: stay LED for fully charged
,08-26 15:19:25.738  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:19:25.738  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:19:25.748  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:19:25.768  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:19:25.768  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:19:25.778  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:25.778  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:25.778  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:27.947   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:19:34.957  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-26 15:19:34.957  5870  6121 I PlayCommon: [857] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:19:37.797   781  1574 E Watchdog: !@Sync 42 [08-26 15:19:37.806]
,08-26 15:19:37.998   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:19:41.457  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:19:48.097   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:19:55.867   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:58.177   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:20:07.808   781  1574 E Watchdog: !@Sync 43 [08-26 15:20:07.811]
,08-26 15:20:08.277   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:20:17.578   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:20:17.578   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:20:17.578   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:20:17.598   781  1791 I ActivityManager: Killing 7173:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 651s, lastActivityTime 651s
,08-26 15:20:17.598   781  1791 I ActivityManager: Killing 7159:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 661s, lastActivityTime 661s
,08-26 15:20:17.667   292   292 I ServiceManager: service 'AtCmdFwd' died
,08-26 15:20:17.667   372  4799 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,08-26 15:20:17.677   372  4799 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:20:17.677   781  1319 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,08-26 15:20:17.677   781  1319 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
08-26 15:20:17.677   781  1319 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,08-26 15:20:17.707   781  1731 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,08-26 15:20:17.707   781  1731 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-26 15:20:17.707   781  1731 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10971ms
,08-26 15:20:18.357   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:20:18.677   372  4799 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:20:18.687   781   854 I ActivityManager: Start proc 7368:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,08-26 15:20:18.697  7368  7368 E Zygote  : v2
,08-26 15:20:18.697  7368  7368 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:20:18.697  7368  7368 I libpersona: KNOX_SDCARD not a persona
,08-26 15:20:18.697  7368  7368 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:20:18.697  7368  7368 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:20:18.697  7368  7368 E Zygote  : accessInfo : 0
,08-26 15:20:18.727  7368  7368 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:20:18.727  7368  7368 D ActivityThread: Added TimaKeyStore provider
,08-26 15:20:18.737  7368  7368 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,08-26 15:20:18.747  7368  7368 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,08-26 15:20:18.747  7368  7368 D AtFwdService: onCreate method
,08-26 15:20:18.747  7368  7368 I AtFwdService: Instantiate AtCmdFwd Service
,08-26 15:20:18.757  7368  7380 D AtCkpdCmdHandler: De-queing command
,08-26 15:20:26.017   781  2274 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:28.437   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:20:28.737  7389  7389 E Zygote  : v2
,08-26 15:20:28.737   781   854 I ActivityManager: Start proc 7389:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,08-26 15:20:28.747  7389  7389 I libpersona: KNOX_SDCARD checking this for 10026
08-26 15:20:28.747  7389  7389 I libpersona: KNOX_SDCARD not a persona
,08-26 15:20:28.747  7389  7389 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-26 15:20:28.747  7389  7389 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-26 15:20:28.747  7389  7389 E Zygote  : accessInfo : 0
,08-26 15:20:28.747  7389  7389 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,08-26 15:20:28.797  7389  7389 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:20:28.797  7389  7389 D ActivityThread: Added TimaKeyStore provider
,08-26 15:20:28.817  7389  7389 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,08-26 15:20:28.827  7389  7389 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,08-26 15:20:28.837  7389  7389 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,08-26 15:20:28.847  7389  7389 D ContextualPageNotification: resetAllNotification : all clear!!!
,08-26 15:20:32.608   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-26 15:20:32.608   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-26 15:20:32.608   304  1121 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-26 15:20:37.807   781  1574 E Watchdog: !@Sync 44 [08-26 15:20:37.815]
,08-26 15:20:38.538   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:20:41.578  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:20:41.717  1651  1710 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 132ms lastUpdatedAfter : 180500ms
,08-26 15:20:48.637   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:20:56.098   781  1810 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:56.098   781  1810 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:20:56.098   781  1810 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:20:56.108   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:20:56.108   781   781 I MotionRecognitionService: Plugged
,08-26 15:20:56.118   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:20:56.118   781  1810 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 20ms
,08-26 15:20:56.118   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:20:56.128   781  1810 D BatteryService: stay LED for fully charged
,08-26 15:20:56.128   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:20:56.138  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:20:56.138  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:20:56.138  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:20:56.167  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:20:56.177  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:20:56.177  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:56.177  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:20:56.177  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:58.697   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:21:07.817   781  1574 E Watchdog: !@Sync 45 [08-26 15:21:07.820]
,08-26 15:21:08.788   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:21:18.887   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:21:26.358   781  1747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:26.358   781  1747 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:21:26.358   781  1747 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:21:26.368   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:21:26.378   781   781 I MotionRecognitionService: Plugged
,08-26 15:21:26.378   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:21:26.378   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:21:26.378   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:21:26.388   781  1747 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,08-26 15:21:26.388   781  1747 D BatteryService: stay LED for fully charged
,08-26 15:21:26.398  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:21:26.398  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:21:26.407  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:21:26.417  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:21:26.427  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:21:26.437  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:26.437  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:21:26.437  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:28.947   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:21:37.818   781  1574 E Watchdog: !@Sync 46 [08-26 15:21:37.824]
,08-26 15:21:39.048   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:21:41.827  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:21:49.147   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:21:56.588   781  1625 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:56.588   781  1625 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:21:56.588   781  1625 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:21:56.588   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:21:56.598   781   781 I MotionRecognitionService: Plugged
,08-26 15:21:56.608   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:21:56.608   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:21:56.608   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:21:56.608   781  1625 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-26 15:21:56.618   781  1625 D BatteryService: stay LED for fully charged
,08-26 15:21:56.628  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:21:56.628  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:21:56.628  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:21:56.648  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:21:56.648  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:21:56.668  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:56.668  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:56.668  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:59.207   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:22:07.827   781  1574 E Watchdog: !@Sync 47 [08-26 15:22:07.829]
,08-26 15:22:09.307   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:22:19.407   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:22:26.698   781   794 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:29.497   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:22:37.828   781  1574 E Watchdog: !@Sync 48 [08-26 15:22:37.833]
,08-26 15:22:39.598   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:22:41.947  1651  1710 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-26 15:22:49.727   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:22:49.857   781   791 I art     : Background sticky concurrent mark sweep GC freed 54387(7MB) AllocSpace objects, 389(7MB) LOS objects, 26% free, 42MB/58MB, paused 2.412ms total 154.258ms
,08-26 15:22:56.957   781  1412 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:56.957   781  1412 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-26 15:22:56.968   781  1412 D BatteryService: online:4, current avg:350, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:350
,08-26 15:22:56.968   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:56.978   781   781 I MotionRecognitionService: Plugged
,08-26 15:22:56.978   781   781 D MotionRecognitionService:   cableConnection= 1
,08-26 15:22:56.978   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-26 15:22:56.988   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-26 15:22:56.988   781  1412 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-26 15:22:56.988   781  1412 D BatteryService: stay LED for fully charged
,08-26 15:22:56.998  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:22:57.007  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:22:57.007  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:22:57.027  2158  2158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:57.027  2158  2725 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-26 15:22:57.037  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:57.037  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:57.037  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:59.797   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:23:07.837   781  1574 E Watchdog: !@Sync 49 [08-26 15:23:07.839]
,08-26 15:23:09.897   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:23:19.998   781  3423 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 350, LCD = 0
,08-26 15:23:22.368   781  1229 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:23:22.368   781  1229 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:23:22.368   781  1228 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:23:25.277   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:23:25.277   781  1229 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:23:25.297   781  1229 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:23:25.297   781  1229 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,TIME-OUT KILL (timeout was 1400000ms)
```
