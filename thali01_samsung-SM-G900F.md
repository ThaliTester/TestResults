#### Test 79763830edacfaa_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
,08-23 16:34:44.510   760  1328 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-23 16:34:44.520   760  1328 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-23 16:34:44.689   760  3447 D SSRM:n  : SIOP:: AP = 400, PST = 475, CUR = 300, LCD = 0
08-23 16:34:44.729   760  3447 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 16:34:44.969   760  1240 V AlarmManager: Expired Alarm result :4
08-23 16:34:45.049   760  2423 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 16:34:45.049   760  2423 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 16:34:45.049   760  2423 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-23 16:34:45.049   760  2423 D BatteryService: stay LED for fully charged
08-23 16:34:45.049   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-23 16:34:45.069  5921  5981 I Finsky  : [841] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
08-23 16:34:45.089  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:34:45.089  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:34:45.089  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 16:34:45.109  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:34:45.109  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:34:45.119  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:34:45.119  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 16:34:45.119  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 16:34:45.139   760   760 I MotionRecognitionService: Plugged
08-23 16:34:45.139   760   760 D MotionRecognitionService:   cableConnection= 1
08-23 16:34:45.139   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:34:45.139   760   760 D MotionRecognitionService: skip setTransmitPower. 
08-23 16:34:45.559  5921  5981 I Finsky  : [841] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
08-23 16:34:45.559  5921  5921 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
08-23 16:34:46.019  2332  2332 E audit   : type=1400 msg=audit(1471962886.019:284): avc:  denied  { execmod } for  pid=6489 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 16:34:46.019  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:34:46.019  2332  2332 E audit   : type=1300 msg=audit(1471962886.019:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f45000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=6489 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 16:34:46.019  2332  2332 E audit   : type=1327 msg=audit(1471962886.019:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 16:34:46.019  2332  2332 E audit   : type=1320 msg=audit(1471962886.019:284): 
08-23 16:34:46.069   760  1601 E Watchdog: !@Sync 3 [08-23 16:34:46.079]
08-23 16:34:46.109  2332  2332 E audit   : type=1400 msg=audit(1471962886.109:285): avc:  denied  { execmod } for  pid=6489 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 16:34:46.109  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:34:46.109  2332  2332 E audit   : type=1300 msg=audit(1471962886.109:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f08000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=6489 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 16:34:46.109  2332  2332 E audit   : type=1327 msg=audit(1471962886.109:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 16:34:46.119  2332  2332 E audit   : type=1320 msg=audit(1471962886.109:285): 
08-23 16:34:46.179  2332  2332 E audit   : type=1400 msg=audit(1471962886.179:286): avc:  denied  { execmod } for  pid=6489 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 16:34:46.179  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:34:46.179  2332  2332 E audit   : type=1300 msg=audit(1471962886.179:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f08000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=6489 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 16:34:46.179  2332  2332 E audit   : type=1327 msg=audit(1471962886.179:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-23 16:34:46.179  2332  2332 E audit   : type=1320 msg=audit(1471962886.179:286): 
08-23 16:34:46.179  6489  6489 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 16:34:46.189  6489  6489 D AndroidRuntime: CheckJNI is OFF
08-23 16:34:46.189  6489  6489 D AndroidRuntime: readGMSProperty: start
08-23 16:34:46.189  6489  6489 D AndroidRuntime: readGMSProperty: already setted!!
08-23 16:34:46.189  6489  6489 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 16:34:46.189  6489  6489 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 16:34:46.189  6489  6489 D AndroidRuntime: readGMSProperty: end
08-23 16:34:46.189  6489  6489 D AndroidRuntime: addProductProperty: start
08-23 16:34:46.209  6489  6489 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 16:34:46.209  6489  6489 W art     : aed6c000-b1c92000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 16:34:46.209  6489  6489 W art     : b1c92000-b3f01000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 16:34:46.209  6489  6489 W art     : b3f01000-b3f02000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 16:34:46.209  6489  6489 W art     : b3f02000-b3f03000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.209  6489  6489 W art     : b423a000-b4263000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 16:34:46.209  6489  6489 W art     : b4263000-b46b1000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 16:34:46.209  6489  6489 W art     : b46b1000-b46b2000 ---p 00000000 00:00 0 
08-23 16:34:46.209  6489  6489 W art     : b46b2000-b46bc000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 16:34:46.209  6489  6489 W art     : b46bc000-b46bd000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 16:34:46.209  6489  6489 W art     : b46bd000-b46bf000 rw-p 00000000 00:00 0 
08-23 16:34:46.209  6489  6489 W art     : b46bf000-b46c0000 r--p 00000000 00:00 0 
08-23 16:34:46.209  6489  6489 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 16:34:46.209  6489  6489 W art     : b47d6000-b47d9000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 16:34:46.209  6489  6489 W art     : b47d9000-b47da000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 16:34:46.209  6489  6489 W art     : b47da000-b47db000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 16:34:46.209  6489  6489 W art     : b47db000-b47dc000 r--p 00000000 00:00 0 
08-23 16:34:46.209  6489  6489 W art     : b47dc000-b47fc000 r--s 00000000 00:0b 7179       /dev/__properties__
08-23 16:34:46.209  6489  6489 W art     : b47fc000-b520d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 16:34:46.219  6489  6489 W art     : b520d000-b520e000 ---p 00000000 00:00 0 
08-23 16:34:46.219  6489  6489 W art     : b520e000-b5257000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 16:34:46.219  6489  6489 W art     : b5257000-b5258000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 16:34:46.219  6489  6489 W art     : b5258000-b5260000 rw-p 00000000 00:00 0 
08-23 16:34:46.219  6489  6489 W art     : b5260000-b5261000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.219  6489  6489 W art     : b5261000-b5296000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 16:34:46.219  6489  6489 W art     : b5296000-b5297000 ---p 00000000 00:00 0 
08-23 16:34:46.219  6489  6489 W art     : b5297000-b5298000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 16:34:46.219  6489  6489 W art     : b5298000-b5299000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 16:34:46.219  6489  6489 W art     : b5299000-b52f1000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 16:34:46.219  6489  6489 W art     : b52f1000-b52f2000 ---p 00000000 00:00 0 
08-23 16:34:46.219  6489  6489 W art     : b52f2000-b52f3000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 16:34:46.219  6489  6489 W art     : b52f3000-b52f4000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 16:34:46.219  6489  6489 W art     : b52f5000-b52fb000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 16:34:46.219  6489  6489 W art     : b52fb000-b52fc000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 16:34:46.219  6489  6489 W art     : b52fc000-b52fd000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 16:34:46.219  6489  6489 W art     : b52fd000-b52ff000 rw-p 00000000 00:00 0 
08-23 16:34:46.219  6489  6489 W art     : b5300000-b530a000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 16:34:46.219  6489  6489 W art     : b530a000-b530d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 16:34:46.219  6489  6489 W art     : b530d000-b530e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 16:34:46.219  6489  6489 W art     : b530f000-b5326000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 16:34:46.219  6489  6489 W art     : b5326000-b5327000 ---p 00000000 00:00 0 
08-23 16:34:46.219  6489  6489 W art     : b5327000-b5328000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 16:34:46.219  6489  6489 W art     : b5328000-b5329000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 16:34:46.219  6489  6489 W art     : b532a000-b5334000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 16:34:46.219  6489  6489 W art     : b5334000-b5335000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 16:34:46.219  6489  6489 W art     : b5335000-b5336000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 16:34:46.219  6489  6489 W art     : b5336000-b533a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 16:34:46.219  6489  6489 W art     : b533a000-b533b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 16:34:46.219  6489  6489 W art     : b533b000-b533c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 16:34:46.219  6489  6489 W art     : b533c000-b5352000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 16:34:46.219  6489  6489 W art     : b5352000-b5353000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 16:34:46.219  6489  6489 W art     : b5353000-b5354000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 16:34:46.219  6489  6489 W art     : b5354000-b5361000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 16:34:46.219  6489  6489 W art     : b5361000-b5362000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 16:34:46.219  6489  6489 W art     : b5362000-b5363000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 16:34:46.219  6489  6489 W art     : b5363000-b53c3000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 16:34:46.229  6489  6489 W art     : b53c3000-b53c6000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 16:34:46.229  6489  6489 W art     : b53c6000-b53ca000 rw-p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b53ca000-b542b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 16:34:46.229  6489  6489 W art     : b542b000-b542c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 16:34:46.229  6489  6489 W art     : b542c000-b547b000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 16:34:46.229  6489  6489 W art     : b547b000-b547d000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 16:34:46.229  6489  6489 W art     : b547d000-b547e000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 16:34:46.229  6489  6489 W art     : b547e000-b547f000 rw-p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b547f000-b5486000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 16:34:46.229  6489  6489 W art     : b5486000-b5487000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 16:34:46.229  6489  6489 W art     : b5487000-b5488000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 16:34:46.229  6489  6489 W art     : b5489000-b548c000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 16:34:46.229  6489  6489 W art     : b548c000-b548d000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 16:34:46.229  6489  6489 W art     : b548d000-b548e000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 16:34:46.229  6489  6489 W art     : b548f000-b5493000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 16:34:46.229  6489  6489 W art     : b5493000-b5494000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b5494000-b5495000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 16:34:46.229  6489  6489 W art     : b5495000-b5496000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-23 16:34:46.229  6489  6489 W art     : b5497000-b54b4000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 16:34:46.229  6489  6489 W art     : b54b4000-b54b5000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 16:34:46.229  6489  6489 W art     : b54b5000-b54b6000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 16:34:46.229  6489  6489 W art     : b54b7000-b54bc000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 16:34:46.229  6489  6489 W art     : b54bc000-b54bd000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 16:34:46.229  6489  6489 W art     : b54bd000-b54be000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 16:34:46.229  6489  6489 W art     : b54bf000-b54f0000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 16:34:46.229  6489  6489 W art     : b54f0000-b54f3000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 16:34:46.229  6489  6489 W art     : b54f3000-b54f4000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 16:34:46.229  6489  6489 W art     : b54f5000-b5530000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 16:34:46.229  6489  6489 W art     : b5530000-b5531000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 16:34:46.229  6489  6489 W art     : b5531000-b5532000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 16:34:46.229  6489  6489 W art     : b5533000-b553a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 16:34:46.229  6489  6489 W art     : b553a000-b553b000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b553b000-b553c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 16:34:46.229  6489  6489 W art     : b553c000-b553d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 16:34:46.229  6489  6489 W art     : b553d000-b553e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.229  6489  6489 W art     : b553e000-b5555000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 16:34:46.229  6489  6489 W art     : b5555000-b5556000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b5556000-b5559000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 16:34:46.229  6489  6489 W art     : b5559000-b555a000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 16:34:46.229  6489  6489 W art     : b555a000-b5579000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 16:34:46.229  6489  6489 W art     : b5579000-b557a000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 16:34:46.229  6489  6489 W art     : b557a000-b557b000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 16:34:46.229  6489  6489 W art     : b557b000-b55b9000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 16:34:46.229  6489  6489 W art     : b55b9000-b55ba000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b55ba000-b55bc000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 16:34:46.229  6489  6489 W art     : b55bc000-b55bd000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 16:34:46.229  6489  6489 W art     : b55be000-b55c5000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 16:34:46.229  6489  6489 W art     : b55c5000-b55c6000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 16:34:46.229  6489  6489 W art     : b55c6000-b55c7000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 16:34:46.229  6489  6489 W art     : b55c8000-b55cb000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 16:34:46.229  6489  6489 W art     : b55cb000-b55cc000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 16:34:46.229  6489  6489 W art     : b55cc000-b55cd000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 16:34:46.229  6489  6489 W art     : b55cd000-b55d3000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 16:34:46.229  6489  6489 W art     : b55d3000-b55d4000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b55d4000-b55d5000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 16:34:46.229  6489  6489 W art     : b55d5000-b55d6000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 16:34:46.229  6489  6489 W art     : b55d6000-b55df000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 16:34:46.229  6489  6489 W art     : b55df000-b55e0000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 16:34:46.229  6489  6489 W art     : b55e0000-b55e1000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 16:34:46.229  6489  6489 W art     : b55e1000-b5672000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 16:34:46.229  6489  6489 W art     : b5672000-b5673000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b5673000-b567e000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 16:34:46.229  6489  6489 W art     : b567e000-b567f000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 16:34:46.229  6489  6489 W art     : b5680000-b5692000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 16:34:46.229  6489  6489 W art     : b5692000-b5693000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 16:34:46.229  6489  6489 W art     : b5693000-b5694000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 16:34:46.229  6489  6489 W art     : b5695000-b569a000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 16:34:46.229  6489  6489 W art     : b569a000-b569b000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 16:34:46.229  6489  6489 W art     : b569b000-b569c000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 16:34:46.229  6489  6489 W art     : b569d000-b570a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 16:34:46.229  6489  6489 W art     : b570a000-b570b000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b570b000-b570d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 16:34:46.229  6489  6489 W art     : b570d000-b570e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 16:34:46.229  6489  6489 W art     : b570e000-b570f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.229  6489  6489 W art     : b570f000-b5716000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 16:34:46.229  6489  6489 W art     : b5716000-b5717000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 16:34:46.229  6489  6489 W art     : b5717000-b5718000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 16:34:46.229  6489  6489 W art     : b5719000-b5799000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 16:34:46.229  6489  6489 W art     : b5799000-b579a000 ---p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b579a000-b579b000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 16:34:46.229  6489  6489 W art     : b579b000-b579c000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 16:34:46.229  6489  6489 W art     : b579c000-b57b3000 rw-p 00000000 00:00 0 
08-23 16:34:46.229  6489  6489 W art     : b57b3000-b57ea000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 16:34:46.229  6489  6489 W art     : ib/libqc-opt.so
08-23 16:34:46.229  6489  6489 W art     : b57ea000-b57eb000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 16:34:46.229  6489  6489 W art     : b57eb000-b57ec000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 16:34:46.229  6489  6489 W art     : b57ec000-b5808000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 16:34:46.229  6489  6489 W art     : b5808000-b5809000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 16:34:46.229  6489  6489 W art     : b5809000-b580a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 16:34:46.229  6489  6489 W art     : b580b000-b586c000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 16:34:46.229  6489  6489 W art     : b586c000-b586e000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 16:34:46.229  6489  6489 W art     : b586e000-b586f000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 16:34:46.239  6489  6489 W art     : b5870000-b5897000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 16:34:46.239  6489  6489 W art     : b5897000-b5898000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5898000-b5899000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 16:34:46.239  6489  6489 W art     : b5899000-b589a000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 16:34:46.239  6489  6489 W art     : b589b000-b58a3000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 16:34:46.239  6489  6489 W art     : b58a3000-b58a5000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 16:34:46.239  6489  6489 W art     : b58a5000-b58a6000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 16:34:46.239  6489  6489 W art     : b58a7000-b58aa000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 16:34:46.239  6489  6489 W art     : b58aa000-b58ab000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 16:34:46.239  6489  6489 W art     : b58ab000-b58ac000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 16:34:46.239  6489  6489 W art     : b58ac000-b58b0000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 16:34:46.239  6489  6489 W art     : b58b0000-b58b1000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b58b1000-b58b2000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 16:34:46.239  6489  6489 W art     : b58b2000-b58b3000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 16:34:46.239  6489  6489 W art     : b58b3000-b58c3000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 16:34:46.239  6489  6489 W art     : b58c3000-b58c4000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 16:34:46.239  6489  6489 W art     : b58c4000-b58c5000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 16:34:46.239  6489  6489 W art     : b58c5000-b590b000 rw-p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b590b000-b5914000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 16:34:46.239  6489  6489 W art     : b5914000-b5915000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 16:34:46.239  6489  6489 W art     : b5915000-b5916000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 16:34:46.239  6489  6489 W art     : b5917000-b591c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 16:34:46.239  6489  6489 W art     : b591c000-b591d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 16:34:46.239  6489  6489 W art     : b591d000-b591e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 16:34:46.239  6489  6489 W art     : b591e000-b5921000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 16:34:46.239  6489  6489 W art     : b5921000-b5922000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5922000-b5923000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 16:34:46.239  6489  6489 W art     : b5923000-b5924000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 16:34:46.239  6489  6489 W art     : b5925000-b593d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 16:34:46.239  6489  6489 W art     : b593d000-b593e000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b593e000-b593f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 16:34:46.239  6489  6489 W art     : b593f000-b5940000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 16:34:46.239  6489  6489 W art     : b5941000-b5adb000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 16:34:46.239  6489  6489 W art     : b5adb000-b5adc000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5adc000-b5ae9000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 16:34:46.239  6489  6489 W art     : b5ae9000-b5aea000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 16:34:46.239  6489  6489 W art     : b5aea000-b5aee000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 16:34:46.239  6489  6489 W art     : b5aee000-b5aef000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5aef000-b5af0000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 16:34:46.239  6489  6489 W art     : b5af0000-b5af1000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 16:34:46.239  6489  6489 W art     : b5af1000-b5b04000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 16:34:46.239  6489  6489 W art     : b5b04000-b5b05000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 16:34:46.239  6489  6489 W art     : b5b05000-b5b06000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 16:34:46.239  6489  6489 W art     : b5b07000-b5b52000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 16:34:46.239  6489  6489 W art     : b5b52000-b5b53000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 16:34:46.239  6489  6489 W art     : b5b53000-b5b54000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 16:34:46.239  6489  6489 W art     : b5b54000-b5b56000 rw-p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5b56000-b5b57000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:34:46.239  6489  6489 W art     : b5b57000-b5b68000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 16:34:46.239  6489  6489 W art     : b5b68000-b5b69000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5b69000-b5b6a000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 16:34:46.239  6489  6489 W art     : b5b6a000-b5b6b000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 16:34:46.239  6489  6489 W art     : b5b6c000-b5b76000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 16:34:46.239  6489  6489 W art     : b5b76000-b5b78000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 16:34:46.239  6489  6489 W art     : b5b78000-b5b79000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 16:34:46.239  6489  6489 W art     : b5b79000-b5b92000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 16:34:46.239  6489  6489 W art     : b5b92000-b5b93000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 16:34:46.239  6489  6489 W art     : b5b93000-b5b96000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 16:34:46.239  6489  6489 W art     : b5b96000-b5b9a000 rw-p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5b9a000-b5c0e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 16:34:46.239  6489  6489 W art     : b5c0e000-b5c0f000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5c0f000-b5c12000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 16:34:46.239  6489  6489 W art     : b5c12000-b5c13000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 16:34:46.239  6489  6489 W art     : b5c14000-b5c17000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 16:34:46.239  6489  6489 W art     : b5c17000-b5c18000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 16:34:46.239  6489  6489 W art     : b5c18000-b5c19000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 16:34:46.239  6489  6489 W art     : b5c19000-b5c1a000 r--p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5c1a000-b5c1f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 16:34:46.239  6489  6489 W art     : b5c1f000-b5c20000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 16:34:46.239  6489  6489 W art     : b5c20000-b5c21000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 16:34:46.239  6489  6489 W art     : b5c21000-b5c22000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.239  6489  6489 W art     : b5c22000-b5c25000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 16:34:46.239  6489  6489 W art     : b5c25000-b5c26000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 16:34:46.239  6489  6489 W art     : b5c26000-b5c27000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 16:34:46.239  6489  6489 W art     : b5c27000-b5c28000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.239  6489  6489 W art     : b5c28000-b5c2c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 16:34:46.239  6489  6489 W art     : b5c2c000-b5c2d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 16:34:46.239  6489  6489 W art     : b5c2d000-b5c2e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 16:34:46.239  6489  6489 W art     : b5c2e000-b5c2f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:34:46.239  6489  6489 W art     : b5c2f000-b5c33000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 16:34:46.239  6489  6489 W art     : b5c33000-b5c34000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 16:34:46.239  6489  6489 W art     : b5c34000-b5c35000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 16:34:46.239  6489  6489 W art     : b5c35000-b5c36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.239  6489  6489 W art     : b5c36000-b5c44000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 16:34:46.239  6489  6489 W art     : b5c44000-b5c45000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b5c45000-b5c46000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 16:34:46.239  6489  6489 W art     : b5c46000-b5c47000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 16:34:46.239  6489  6489 W art     : b5c47000-b5c51000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 16:34:46.239  6489  6489 W art     : b5c51000-b5c54000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 16:34:46.239  6489  6489 W art     : b5c54000-b5c55000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 16:34:46.239  6489  6489 W art     : b5c55000-b5c56000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.239  6489  6489 W art     : b5c56000-b5c60000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 16:34:46.239  6489  6489 W art     : b5c60000-b5c63000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 16:34:46.239  6489  6489 W art     : b5c63000-b5c64000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 16:34:46.239  6489  6489 W art     : b5c64000-b5c68000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 16:34:46.239  6489  6489 W art     : b5c68000-b5c69000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 16:34:46.239  6489  6489 W art     : b5c69000-b5c6a000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 16:34:46.239  6489  6489 W art     : b5c6a000-b5c6b000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.239  6489  6489 W art     : b5c6b000-b5c78000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 16:34:46.239  6489  6489 W art     : b5c78000-b5c7a000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 16:34:46.239  6489  6489 W art     : b5c7a000-b5c7b000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 16:34:46.239  6489  6489 W art     : b5c7b000-b608d000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 16:34:46.239  6489  6489 W art     : b608d000-b608e000 ---p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b608e000-b6097000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 16:34:46.239  6489  6489 W art     : b6097000-b609b000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 16:34:46.239  6489  6489 W art     : b609b000-b609c000 rw-p 00000000 00:00 0 
08-23 16:34:46.239  6489  6489 W art     : b609c000-b60a3000 r-xp 00000000 b3:17 2571       /system/lib/libaud
08-23 16:34:46.249  6489  6489 W art     : ioutils.so
08-23 16:34:46.249  6489  6489 W art     : b60a3000-b60a4000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 16:34:46.249  6489  6489 W art     : b60a4000-b60a5000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 16:34:46.249  6489  6489 W art     : b60a5000-b60a6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.249  6489  6489 W art     : b60a6000-b60c1000 r-xp 00000000
08-23 16:34:46.249  6489  6489 W art     :  b3:17 1184       /system/lib/libz.so
08-23 16:34:46.249  6489  6489 W art     : b60c1000-b60c2000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 16:34:46.249  6489  6489 W art     : b60c2000-b60c3000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 16:34:46.249  6489  6489 W art     : b60c3000-b60c4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.249  6489  6489 W art     : b60c4000-b6110000 r-xp 00000000 b3:17 994        
08-23 16:34:46.249  6489  6489 W art     : /system/lib/libharfbuzz_ng.so
08-23 16:34:46.249  6489  6489 W art     : b6110000-b6111000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6111000-b6112000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 16:34:46.249  6489  6489 W art     : b6112000-b6113000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 16:34:46.249  6489  6489 W art     : b6113000-b6114000 r--p 00000000 00:00 0          [anon:li
08-23 16:34:46.249  6489  6489 W art     : nker_alloc]
08-23 16:34:46.249  6489  6489 W art     : b6114000-b6118000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 16:34:46.249  6489  6489 W art     : b6118000-b6119000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6119000-b611a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 16:34:46.249  6489  6489 W art     : b611a000-b611b000 rw-p 00005000 b3:17 2681       /system/lib/libu
08-23 16:34:46.249  6489  6489 W art     : sbhost.so
08-23 16:34:46.249  6489  6489 W art     : b611b000-b6153000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 16:34:46.249  6489  6489 W art     : b6153000-b6154000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 16:34:46.249  6489  6489 W art     : b6154000-b6155000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 16:34:46.249  6489  6489 W art     : b6155000-b6156000 r--p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     :          [anon:linker_alloc]
08-23 16:34:46.249  6489  6489 W art     : b6156000-b61f4000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 16:34:46.249  6489  6489 W art     : b61f4000-b61f5000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b61f5000-b6213000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 16:34:46.249  6489  6489 W art     : b6213000-b6214000 rw-p 000bc000 b3:17 496        /system/lib/libmedia
08-23 16:34:46.249  6489  6489 W art     : .so
08-23 16:34:46.249  6489  6489 W art     : b6214000-b6387000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 16:34:46.249  6489  6489 W art     : b6387000-b6392000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 16:34:46.249  6489  6489 W art     : b6392000-b6393000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 16:34:46.249  6489  6489 W art     : b6393000-b64aa000 r-xp 00000000
08-23 16:34:46.249  6489  6489 W art     :  b3:17 2041       /system/lib/libicuuc.so
08-23 16:34:46.249  6489  6489 W art     : b64aa000-b64b5000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 16:34:46.249  6489  6489 W art     : b64b5000-b64b6000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 16:34:46.249  6489  6489 W art     : b64b6000-b64ba000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b64ba000-b64de000 r-xp 00000000 b3:17 400        /system/lib/libssl.s
08-23 16:34:46.249  6489  6489 W art     : o
08-23 16:34:46.249  6489  6489 W art     : b64de000-b64e0000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 16:34:46.249  6489  6489 W art     : b64e0000-b64e1000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 16:34:46.249  6489  6489 W art     : b64e1000-b6587000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 16:34:46.249  6489  6489 W art     : b6587000-b6594000 r--p 000a5000 b3:17 13
08-23 16:34:46.249  6489  6489 W art     : 2        /system/lib/libcrypto.so
08-23 16:34:46.249  6489  6489 W art     : b6594000-b6595000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 16:34:46.249  6489  6489 W art     : b6595000-b6596000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6596000-b65e9000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 16:34:46.249  6489  6489 W art     : b65e9000-b65ea000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b65ea000-b65eb000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 16:34:46.249  6489  6489 W art     : b65eb000-b65ec000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 16:34:46.249  6489  6489 W art     : b65ec000-b65f1000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b65f1000-b6603000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 16:34:46.249  6489  6489 W art     : b6603000-b6604000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6604000-b6605000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 16:34:46.249  6489  6489 W art     : b6605000-b6606000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 16:34:46.249  6489  6489 W art     : b6606000-b660d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 16:34:46.249  6489  6489 W art     : b660d000-b660e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 16:34:46.249  6489  6489 W art     : b660e000-b660f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 16:34:46.249  6489  6489 W art     : b660f000-b6610000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6610000-b6613000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 16:34:46.249  6489  6489 W art     : b6613000-b6614000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 16:34:46.249  6489  6489 W art     : b6614000-b6615000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 16:34:46.249  6489  6489 W art     : b6615000-b6619000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 16:34:46.249  6489  6489 W art     : b6619000-b661a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 16:34:46.249  6489  6489 W art     : b661a000-b661b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 16:34:46.249  6489  6489 W art     : b661b000-b6629000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 16:34:46.249  6489  6489 W art     : b6629000-b662a000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b662a000-b662b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 16:34:46.249  6489  6489 W art     : b662b000-b662c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 16:34:46.249  6489  6489 W art     : b662c000-b6635000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 16:34:46.249  6489  6489 W art     : b6635000-b6636000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 16:34:46.249  6489  6489 W art     : b6636000-b6637000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 16:34:46.249  6489  6489 W art     : b6637000-b669d000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 16:34:46.249  6489  6489 W art     : b669d000-b669e000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b669e000-b66a0000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 16:34:46.249  6489  6489 W art     : b66a0000-b66a9000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 16:34:46.249  6489  6489 W art     : b66a9000-b66ac000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b66ac000-b6743000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 16:34:46.249  6489  6489 W art     : b6743000-b6745000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 16:34:46.249  6489  6489 W art     : b6745000-b6746000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 16:34:46.249  6489  6489 W art     : b6746000-b6747000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6747000-b6a68000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 16:34:46.249  6489  6489 W art     : b6a68000-b6a69000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6a69000-b6a84000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 16:34:46.249  6489  6489 W art     : b6a84000-b6a88000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 16:34:46.249  6489  6489 W art     : b6a88000-b6a8d000 rw-p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6a8d000-b6a95000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 16:34:46.249  6489  6489 W art     : b6a95000-b6a96000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 16:34:46.249  6489  6489 W art     : b6a96000-b6a97000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 16:34:46.249  6489  6489 W art     : b6a97000-b6ac5000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 16:34:46.249  6489  6489 W art     : b6ac5000-b6ac6000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6ac6000-b6acd000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 16:34:46.249  6489  6489 W art     : b6acd000-b6ace000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 16:34:46.249  6489  6489 W art     : b6ace000-b6b14000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 16:34:46.249  6489  6489 W art     : b6b14000-b6b15000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6b15000-b6b18000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 16:34:46.249  6489  6489 W art     : b6b18000-b6b19000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 16:34:46.249  6489  6489 W art     : b6b19000-b6b34000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 16:34:46.249  6489  6489 W art     : b6b34000-b6b38000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 16:34:46.249  6489  6489 W art     : b6b38000-b6b39000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 16:34:46.249  6489  6489 W art     : b6b39000-b6b86000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 16:34:46.249  6489  6489 W art     : b6b86000-b6b87000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6b87000-b6b93000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 16:34:46.249  6489  6489 W art     : b6b93000-b6b94000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 16:34:46.249  6489  6489 W art     : b6b94000-b6ba1000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 16:34:46.249  6489  6489 W art     : b6ba1000-b6ba2000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6ba2000-b6ba3000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 16:34:46.249  6489  6489 W art     : b6ba3000-b6ba4000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 16:34:46.249  6489  6489 W art     : b6ba4000-b6bac000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 16:34:46.249  6489  6489 W art     : b6bac000-b6bad000 ---p 00000000 00:00 0 
08-23 16:34:46.249  6489  6489 W art     : b6bad000-b6bae000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 16:34:46.249  6489  6489 W art     : b6bae000-b6baf000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 16:34:46.249  6489  6489 W art     : b6baf000-b6bb6000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 16:34:46.249  6489  6489 W art     : b6bb6000-b6bb7000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 16:34:46.249  6489  6489 W art     : b6bb7000-b6bb8000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 16:34:46.249  6489  6489 W art     : b6bb8000-b6bcc000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 16:34:46.249  6489  6489 W art     : b6bcc000-b6bce000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 16:34:46.259  6489  6489 W art     : b6bce000-b6bcf000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 16:34:46.259  6489  6489 W art     : b6bcf000-b6bf7000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 16:34:46.259  6489  6489 W art     : b6bf7000-b6bf9000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 16:34:46.259  6489  6489 W art     : b6bf9000-b6bfa000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 16:34:46.259  6489  6489 W art     : b6bfa000-b6bfd000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 16:34:46.259  6489  6489 W art     : b6bfd000-b6bfe000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 16:34:46.259  6489  6489 W art     : b6bfe000-b6bff000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 16:34:46.259  6489  6489 W art     : b6bff000-b6c08000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 16:34:46.259  6489  6489 W art     : b6c08000-b6c09000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 16:34:46.259  6489  6489 W art     : b6c09000-b6c0a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 16:34:46.259  6489  6489 W art     : b6c0a000-b6c2a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 16:34:46.259  6489  6489 W art     : b6c2a000-b6c2b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 16:34:46.259  6489  6489 W art     : b6c2b000-b6c2c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 16:34:46.259  6489  6489 W art     : b6c2c000-b6c9f000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 16:34:46.259  6489  6489 W art     : b6c9f000-b6ca3000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 16:34:46.259  6489  6489 W art     : b6ca3000-b6ca6000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 16:34:46.259  6489  6489 W art     : b6ca6000-b6cb0000 rw-p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6cb0000-b6d38000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 16:34:46.259  6489  6489 W art     : b6d38000-b6d39000 ---p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6d39000-b6d3d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 16:34:46.259  6489  6489 W art     : b6d3d000-b6d3e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 16:34:46.259  6489  6489 W art     : b6d3e000-b6d3f000 rw-p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6d3f000-b6d68000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 16:34:46.259  6489  6489 W art     : b6d68000-b6d69000 ---p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6d69000-b6d6c000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 16:34:46.259  6489  6489 W art     : b6d6c000-b6d6d000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 16:34:46.259  6489  6489 W art     : b6d6d000-b6e47000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 16:34:46.259  6489  6489 W art     : b6e47000-b6e4e000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 16:34:46.259  6489  6489 W art     : b6e4e000-b6e56000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 16:34:46.259  6489  6489 W art     : b6e56000-b6e57000 rw-p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6e57000-b6e58000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:34:46.259  6489  6489 W art     : b6e58000-b6e59000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 16:34:46.259  6489  6489 W art     : b6e59000-b6e5a000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.259  6489  6489 W art     : b6e5a000-b6e5d000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.259  6489  6489 W art     : b6e5d000-b6e82000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 16:34:46.259  6489  6489 W art     : b6e82000-b6e83000 ---p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6e83000-b6e8a000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 16:34:46.259  6489  6489 W art     : b6e8a000-b6e8b000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 16:34:46.259  6489  6489 W art     : b6e8b000-b6e92000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 16:34:46.259  6489  6489 W art     : b6e92000-b6e93000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 16:34:46.259  6489  6489 W art     : b6e93000-b6e94000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 16:34:46.259  6489  6489 W art     : b6e94000-b6e95000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.259  6489  6489 W art     : b6e95000-b6ead000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 16:34:46.259  6489  6489 W art     : b6ead000-b6eae000 ---p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6eae000-b6eaf000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 16:34:46.259  6489  6489 W art     : b6eaf000-b6eb0000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 16:34:46.259  6489  6489 W art     : b6eb0000-b6ebe000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 16:34:46.259  6489  6489 W art     : b6ebe000-b6ebf000 ---p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6ebf000-b6ec0000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 16:34:46.259  6489  6489 W art     : b6ec0000-b6ec1000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 16:34:46.259  6489  6489 W art     : b6ec1000-b6ec2000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:34:46.259  6489  6489 W art     : b6ec2000-b6ec4000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.259  6489  6489 W art     : b6ec4000-b6ec5000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.259  6489  6489 W art     : b6ec5000-b6ec6000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:34:46.259  6489  6489 W art     : b6ec6000-b6ec7000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 16:34:46.259  6489  6489 W art     : b6ec7000-b6ec8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:34:46.259  6489  6489 W art     : b6ec8000-b6ee8000 r--s 00000000 00:0b 7179       /dev/__properties__
08-23 16:34:46.259  6489  6489 W art     : b6ee8000-b6ee9000 r--p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6ee9000-b6eea000 ---p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6eea000-b6eec000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 16:34:46.259  6489  6489 W art     : b6eec000-b6eed000 r-xp 00000000 00:00 0          [sigpage]
08-23 16:34:46.259  6489  6489 W art     : b6eed000-b6f08000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 16:34:46.259  6489  6489 W art     : b6f08000-b6f09000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 16:34:46.259  6489  6489 W art     : b6f09000-b6f0b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 16:34:46.259  6489  6489 W art     : b6f0b000-b6f0d000 rw-p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : b6f0d000-b6f12000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 16:34:46.259  6489  6489 W art     : b6f12000-b6f13000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 16:34:46.259  6489  6489 W art     : b6f13000-b6f14000 rw-p 00000000 00:00 0 
08-23 16:34:46.259  6489  6489 W art     : bed88000-beda9000 rw-p 00000000 00:00 0          [stack]
08-23 16:34:46.259  6489  6489 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 16:34:46.389  6489  6489 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 16:34:46.479  6489  6489 I Radio-JNI: register_android_hardware_Radio DONE
08-23 16:34:46.489  6489  6489 E AffinityControl: AffinityControl: registerfunction enter
08-23 16:34:46.519  6489  6489 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 16:34:46.539   760  1911 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-23 16:34:46.559   760  1911 D ActivityManager: mDVFSHelper.acquire()
08-23 16:34:46.559   760  1911 V WindowManager: addAppToken: AppWindowToken{3a93344 token=Token{46c4c57 ActivityRecord{224a1d6 u0 com.test.thalitest/.MainActivity t169}}} to stack=1 task=169 at 0
08-23 16:34:46.579   760   891 D SecWifiDisplayUtil: Metadata value : none
08-23 16:34:46.579   760   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{749a6dc V.E...... R.....ID 0,0-0,0}
08-23 16:34:46.579   760   891 D ISSUE_DEBUG: InputChannelName : ea9deba Starting com.test.thalitest
08-23 16:34:46.599   760  1911 I ActivityManager: Start proc 6531:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 16:34:46.599  6531  6531 E Zygote  : v2
08-23 16:34:46.599  6531  6531 I libpersona: KNOX_SDCARD checking this for 10004
08-23 16:34:46.599  6531  6531 I libpersona: KNOX_SDCARD not a persona
08-23 16:34:46.599  6531  6531 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 16:34:46.599  6531  6531 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 16:34:46.599   760  1911 D InputDispatcher: Focused application set to: xxxx
08-23 16:34:46.599   760  1911 D InputDispatcher: Focus left window: 3709
08-23 16:34:46.599   294   294 I SurfaceFlinger: id=23 createSurf (1x1),1 flag=404, uhalitest
08-23 16:34:46.599  6531  6531 E Zygote  : accessInfo : 0
08-23 16:34:46.609  6531  6531 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-23 16:34:46.609   760  1328 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 16:34:46.609   760   845 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{91eebf7 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-23 16:34:46.609  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
08-23 16:34:46.609  6489  6489 D AndroidRuntime: Shutting down VM
08-23 16:34:46.629   760   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:760 uid:1000
08-23 16:34:46.629   760   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 16:34:46.629   760   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:760 uid:1000
08-23 16:34:46.629   760   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 16:34:46.629   760   891 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-23 16:34:46.669  6531  6531 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:34:46.669  6531  6531 D ActivityThread: Added TimaKeyStore provider
08-23 16:34:46.669   760  1784 V WindowOrientationListener: setCurrentAppOrientation :-1
08-23 16:34:46.669   760  1784 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 16:34:46.679   760   891 V WindowStateAnimator: Finishing drawing window Window{ea9deba u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-23 16:34:46.679   760   845 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{ea9deba u0 d0 Starting com.test.thalitest}
08-23 16:34:46.679  1386  1386 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-23 16:34:46.689   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebf3364
08-23 16:34:46.699   760  1784 D ActivityManager:  Launching com.test.thalitest, updated priority
08-23 16:34:46.709   760   844 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
08-23 16:34:46.719  1742  1878 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-23 16:34:46.719  1742  1742 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-23 16:34:46.719   294   362 D libEGL  : eglTerminate EGLDisplay = 0xb694164c
08-23 16:34:46.739   294   367 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
08-23 16:34:46.739   294   367 D libEGL  : eglTerminate EGLDisplay = 0xb66bf64c
08-23 16:34:46.749   294   367 I SurfaceFlinger: id=8 Removed Mauncher (4/12)
08-23 16:34:46.749   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebf33a4
08-23 16:34:46.759   760  1328 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
08-23 16:34:46.759   294   367 I SurfaceFlinger: id=19 Removed YUIInstallC (4/11)
08-23 16:34:46.759   294  1828 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/11)
08-23 16:34:46.759   760  3447 D M       : limitCPUFreq:: freq = -1
08-23 16:34:46.759   760  3447 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1497600  uid : 1000  pid : 760  tag : SIOP_ARM_MAX@25
08-23 16:34:46.769   760  3447 D M       : limitGPUFreq:: freq = -1
08-23 16:34:46.769  6531  6531 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 16:34:46.769   294  1301 I SurfaceFlinger: id=21 Removed VSBConnecti (6/10)
08-23 16:34:46.769   294   362 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/10)
08-23 16:34:46.769   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebf33a4
08-23 16:34:46.769  3709  3709 V ActivityThread: updateVisibility : ActivityRecord{7560cff token=android.os.BinderProxy@c2eb621 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
08-23 16:34:46.769  4526  4526 V ActivityThread: updateVisibility : ActivityRecord{e5d47c4 token=android.os.BinderProxy@1f8200b {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 16:34:46.779   760  3447 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-23 16:34:46.779  2183  2194 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-23 16:34:46.779  1742  1742 V ActivityThread: updateVisibility : ActivityRecord{40a651 token=android.os.BinderProxy@2524fcb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 16:34:46.779  1742  1742 D Launcher: onTrimMemory. Level: 20
08-23 16:34:46.789   294  1301 I SurfaceFlinger: id=22 Removed VSBConnecti (4/9)
08-23 16:34:46.799   294   362 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/9)
08-23 16:34:46.799   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebf33a4
08-23 16:34:46.809  6531  6531 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 16:34:46.809  6531  6531 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
08-23 16:34:46.829  6531  6531 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-23 16:34:46.869  6531  6531 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-23 16:34:46.879  6531  6531 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 16:34:46.889  6531  6531 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 1929-1933)
08-23 16:34:46.889  6531  6531 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 16:34:46.919  6531  6557 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-23 16:34:46.919   760   770 I art     : Background partial concurrent mark sweep GC freed 35027(2MB) AllocSpace objects, 21(420KB) LOS objects, 27% free, 42MB/58MB, paused 2.671ms total 178.758ms
,08-23 16:34:46.919  6531  6531 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e43a9b}
,08-23 16:34:46.919  6531  6531 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-23 16:34:46.919  6531  6531 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 16:34:46.929  6531  6531 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 16:34:46.979  6531  6531 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 16:34:46.979  6531  6531 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 16:34:46.979  6531  6531 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 16:34:46.979  6531  6531 I Adreno-EGL: Local Branch: ss
08-23 16:34:46.979  6531  6531 I Adreno-EGL: Remote Branch: 
08-23 16:34:46.979  6531  6531 I Adreno-EGL: Local Patches: 
08-23 16:34:46.979  6531  6531 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:34:46.989  6531  6531 D libEGL  : eglInitialize EGLDisplay = 0xbee3bdac
,08-23 16:34:47.039   760  1592 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-23 16:34:47.039   760  1592 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-23 16:34:47.099  6531  6531 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-23 16:34:47.119  6531  6531 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 16:34:47.119  6531  6531 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-23 16:34:47.119  6531  6531 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-23 16:34:47.119  6531  6531 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-23 16:34:47.149  6531  6531 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-23 16:34:47.159  6531  6531 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 16:34:47.249   760   844 W ActivityManager: Activity pause timeout for ActivityRecord{224a1d6 u0 com.test.thalitest/.MainActivity t169}
,08-23 16:34:47.279  6531  6531 D SecWifiDisplayUtil: Metadata value : none
,08-23 16:34:47.289  6531  6531 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{51138f1 I.E...... R.....ID 0,0-0,0}
,08-23 16:34:47.289  6531  6585 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 16:34:47.299   760  1325 D ISSUE_DEBUG: InputChannelName : 6f5c12f com.test.thalitest/com.test.thalitest.MainActivity
,08-23 16:34:47.299   760   781 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
,08-23 16:34:47.299   760   781 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 16:34:47.299   760   760 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 16:34:47.299   760   760 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-23 16:34:47.329  6531  6531 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6531
,08-23 16:34:47.329   760  1592 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6531 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 16:34:47.329   760  1337 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-23 16:34:47.329   760  1337 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-23 16:34:47.329   760  1337 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
08-23 16:34:47.329   760  1337 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 16:34:47.329   760  1337 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 16:34:47.329   760  1337 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 16:34:47.329   760  1337 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-23 16:34:47.329   760  1337 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-23 16:34:47.329   760  1337 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,08-23 16:34:47.329   760  1337 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 16:34:47.349  6531  6557 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-23 16:34:47.349  6531  6531 V ActivityThread: updateVisibility : ActivityRecord{c5565f3 token=android.os.BinderProxy@fb15898 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 16:34:47.349  6531  6531 D SecWifiDisplayUtil: Metadata value : none
,08-23 16:34:47.369   294   294 I SurfaceFlinger: id=24 createSurf (1x1),1 flag=404, NainActivit
,08-23 16:34:47.389   760  1256 D InputDispatcher: Focus entered window: 6531
,08-23 16:34:47.389   760   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:760 uid:1000
,08-23 16:34:47.389   760   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 16:34:47.389  6531  6585 D libEGL  : eglInitialize EGLDisplay = 0x9c93f7c4
08-23 16:34:47.389  6531  6585 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 16:34:47.389   760   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:760 uid:1000
08-23 16:34:47.389   760   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-23 16:34:47.449  6531  6531 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-23 16:34:47.459   760  1755 V WindowStateAnimator: Finishing drawing window Window{6f5c12f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-23 16:34:47.459  6531  6531 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-23 16:34:47.469  6531  6531 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-23 16:34:47.469   760  2423 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 16:34:47.479   760   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 16:34:47.479   760   760 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-23 16:34:47.479   760   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +726ms (total +903ms)
,08-23 16:34:47.479   760   760 I KnoxTimeoutHandler: SD activityfalse
,08-23 16:34:47.479   760   891 D ActivityManager: mDVFSHelper.release()
,08-23 16:34:47.479   760   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{224a1d6 u0 com.test.thalitest/.MainActivity t169} time:122526
,08-23 16:34:47.479   760   891 D ViewRootImpl: #3 mView = null
,08-23 16:34:47.489   294   362 I SurfaceFlinger: id=23 Removed uhalitest (7/9)
,08-23 16:34:47.489   294  1828 I SurfaceFlinger: id=23 Removed uhalitest (-2/9)
,08-23 16:34:47.489  6531  6531 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-23 16:34:47.499   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebf33a4
,08-23 16:34:47.529  6531  6592 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 16:34:47.529  6531  6592 D libEGL  : eglInitialize EGLDisplay = 0x9ba3f3ec
,08-23 16:34:47.549   760   781 V WindowStateAnimator: Finishing drawing window Window{6f5c12f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-23 16:34:47.549  6531  6531 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@fb15898 time:122596
,08-23 16:34:47.549   294   294 D libEGL  : eglInitialize EGLDisplay = 0xbebf3364
,08-23 16:34:47.589  6531  6531 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6531
,08-23 16:34:47.739  6531  6531 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 16:34:47.759   760  3448 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-23 16:34:48.039  6531  6609 D jxcore_app_log: JniHelper::setJavaVM(0xb47fc000), pthread_self() = -1717700304
,08-23 16:34:48.039  6531  6609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 16:34:48.039  6531  6609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 16:34:48.039  6531  6609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 16:34:48.039  6531  6609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 16:34:48.039  6531  6609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 16:34:48.039  6531  6609 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c2786 added. We now have 1 listener(s)
,08-23 16:34:48.049  6531  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-23 16:34:48.049  6531  6609 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-23 16:34:48.059  6531  6609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 16:34:48.059  6531  6609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 16:34:48.059  6531  6609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@840819d added. We now have 1 listener(s)
,08-23 16:34:48.059  6531  6609 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 16:34:48.069  6531  6609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-23 16:34:48.079  6531  6609 D BluetoothAdapter: STATE_ON
,08-23 16:34:48.079  6531  6609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:34:48.079  6531  6609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 16:34:48.079  6531  6609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 16:34:48.089  6531  6609 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 16:34:48.089  6531  6609 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 16:34:48.089  6531  6531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 16:34:48.089  6531  6531 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 16:34:48.119  6531  6531 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 16:34:48.259  1451  1451 D Recents : onTaskStackChanged
,08-23 16:34:48.269  1451  1451 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-23 16:34:49.099  6531  6610 W jxcore-log: Initializing JXcore engine
,08-23 16:34:49.099  6531  6610 W jxcore-log: JXcore engine is ready
,08-23 16:34:49.149  2332  2332 E audit   : type=1400 msg=audit(1471962889.149:287): avc:  denied  { ioctl } for  pid=6610 comm="Thread-935" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 16:34:49.149  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:34:49.149  2332  2332 E audit   : type=1300 msg=audit(1471962889.149:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=98ddf3c8 items=0 ppid=357 ppcomm=main pid=6610 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-935" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,08-23 16:34:49.149  2332  2332 E audit   : type=1327 msg=audit(1471962889.149:287): proctitle="com.test.thalitest"
08-23 16:34:49.149  2332  2332 E audit   : type=1320 msg=audit(1471962889.149:287): 
08-23 16:34:49.149  2332  2332 E audit   : type=1400 msg=audit(1471962889.149:288): avc:  denied  { ioctl } for  pid=6610 comm="Thread-935" path="socket:[42513]" dev="sockfs" ino=42513 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 16:34:49.149  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-23 16:34:49.149  2332  2332 E audit   : type=1300 msg=audit(1471962889.149:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=98ddf3c8 items=0 ppid=357 ppcomm=main pid=6610 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-935" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-23 16:34:49.149  2332  2332 E audit   : type=1327 msg=audit(1471962889.149:288): proctitle="com.test.thalitest"
08-23 16:34:49.149  2332  2332 E audit   : type=1320 msg=audit(1471962889.149:288): 
,08-23 16:34:49.159  6531  6610 W jxcore-log: Starting JXcore engine
,08-23 16:34:49.229  6531  6610 W jxcore-log: Platform android
08-23 16:34:49.229  6531  6610 W jxcore-log: 
,08-23 16:34:49.229  6531  6610 W jxcore-log: Process ARCH arm
08-23 16:34:49.229  6531  6610 W jxcore-log: 
,08-23 16:34:49.439  6531  6610 I jxcore-log: JXcore Cordova bridge is ready!
08-23 16:34:49.439  6531  6610 I jxcore-log: 
08-23 16:34:49.439  6531  6610 W jxcore-log: JXcore engine is started
,08-23 16:34:49.449  6531  6609 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 16:34:49.449  6531  6531 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 16:34:49.599   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:34:49.599   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:34:49.599   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:34:49.619   760  1370 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/169_task.xml.bak
,08-23 16:34:51.809   760  1240 V AlarmManager: Expired Alarm result :4
,08-23 16:34:51.819   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e334bbe u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d96fb72 1996:com.google.android.gms.persistent/u0a11}
,08-23 16:34:51.829   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{fdf541f: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:51.959   760  1325 V AlarmManager:  remove PendingIntent] PendingIntent{8ae3d35: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:52.059  1996  1996 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:34:52.079   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ae5c404 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d96fb72 1996:com.google.android.gms.persistent/u0a11}
,08-23 16:34:52.089  2804  6632 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-23 16:34:52.089  2804  6632 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 16:34:52.089   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{4a5dded: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:52.129   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{68be422: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:52.159   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{d5eaeb3: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:52.369   760  1910 I ActivityManager: Start proc 6638:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-23 16:34:52.369  6638  6638 E Zygote  : v2
08-23 16:34:52.369  6638  6638 I libpersona: KNOX_SDCARD checking this for 10011
08-23 16:34:52.369  6638  6638 I libpersona: KNOX_SDCARD not a persona
,08-23 16:34:52.369  6638  6638 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 16:34:52.369  6638  6638 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:34:52.369  6638  6638 E Zygote  : accessInfo : 0
,08-23 16:34:52.369  6638  6638 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,08-23 16:34:52.399  6638  6638 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:34:52.399  6638  6638 D ActivityThread: Added TimaKeyStore provider
,08-23 16:34:52.409  6638  6638 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-23 16:34:52.449  6638  6638 I MultiDex: VM with version 2.1.0 has multidex support
08-23 16:34:52.449  6638  6638 I MultiDex: install
08-23 16:34:52.449  6638  6638 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 16:34:52.479  6638  6638 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-23 16:34:52.489  6638  6638 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
08-23 16:34:52.489  6638  6638 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
08-23 16:34:52.499  6638  6638 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 16:34:52.529  6638  6638 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 16:34:52.539  6638  6638 D ChimeraCfgMgr: Reading stored module config
,08-23 16:34:52.639  6638  6653 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-23 16:34:52.659  1996  1996 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=e3967cec-a7ed-4873-9e02-b0de67c10a8c
,08-23 16:34:52.669  1996  1996 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:34:52.669  1996  1996 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 16:34:52.699   330   330 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6638)
,08-23 16:34:52.739   330   961 D WVCdm   : Instantiating CDM.
,08-23 16:34:52.739   330   330 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6638)
08-23 16:34:52.739   330   330 I WVCdm   : CdmEngine::OpenSession
,08-23 16:34:52.739   330   330 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-23 16:34:52.749   330   330 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 16:34:52.759   330   330 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
08-23 16:34:52.759   330   330 D DrmWidevineDash: Service_Initialize: starts!
08-23 16:34:52.759   330   330 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-23 16:34:52.759   330   330 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 16:34:52.759   330   330 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-23 16:34:52.759   330   330 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 16:34:52.759   330   330 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 16:34:52.759   330   330 D QSEECOMAPI: : App is not loaded in QSEE
08-23 16:34:52.759   330   330 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-23 16:34:52.759   330   330 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 16:34:52.759   330   330 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 16:34:52.759   330   330 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 16:34:52.779   330   330 D QSEECOMAPI: : Loaded image: APP id = 2
,08-23 16:34:52.779   760  3447 D M       : limitCPUFreq:: freq = 1497600
,08-23 16:34:52.779   760  3447 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1497600  uid : 1000  pid : 760  pkgName : SIOP_ARM_MAX@25
,08-23 16:34:52.779   330   330 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-23 16:34:52.779   330   330 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef11000
08-23 16:34:52.779   330   330 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaef11000
,08-23 16:34:52.789   760  3447 D M       : limitGPUFreq:: freq = 320000000
,08-23 16:34:52.809   760  3447 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 16:34:52.819   330   330 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-23 16:34:52.819   330   330 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-23 16:34:52.819   330   330 D DrmWidevineDash: hlos api version =  10
08-23 16:34:52.819   330   330 D DrmWidevineDash: tz api version =  10
08-23 16:34:52.819   330   330 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-23 16:34:52.819   330   330 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-23 16:34:52.839  6638  6648 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 16:34:52.839  6638  6648 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:52.839   307  1193 D EnterpriseController: netId is 0
08-23 16:34:52.839   307  1193 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 16:34:52.849   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:34:52.849   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:34:52.849   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:34:52.849   330   330 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-23 16:34:52.849   330   330 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-23 16:34:52.849   330   330 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbeeee6b4
,08-23 16:34:52.849   330   330 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-23 16:34:52.849   330   330 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-23 16:34:52.849   330   330 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xae423508, dataLength=8
,08-23 16:34:52.849   330   330 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-23 16:34:52.859   330   330 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xad820400, wrapped_rsa_key_length=1280
,08-23 16:34:52.859   330   330 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-23 16:34:52.859   330   330 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-23 16:34:52.859   330   969 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-23 16:34:52.859   330   969 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-23 16:34:52.859   330   969 I WVCdm   : CdmEngine::GenerateKeyRequest
08-23 16:34:52.859   330   969 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xae3fee60, idLength=0xaebfef2c
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-23 16:34:52.869   330   969 D DrmWidevineDash: hlos api version =  10
08-23 16:34:52.869   330   969 D DrmWidevineDash: tz api version =  10
08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-23 16:34:52.869   330   969 D WVCdm   : PrepareKeyRequest: nonce=370097629
,08-23 16:34:52.869   330   969 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1e07400
08-23 16:34:52.869   330   969 D DrmWidevineDash: message_length=1631, signature=0xae7e58c0, signature_length=2931814404
,08-23 16:34:52.909  6638  6648 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6638, getuid(): 10011
,08-23 16:34:52.919  1996  2203 W GCoreFlp: No location to return for getLastLocation()
,08-23 16:34:52.989   330   969 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-23 16:34:52.989   330   959 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6638)
,08-23 16:34:52.989   330   959 I WVCdm   : CdmEngine::CloseSession
08-23 16:34:52.989   330   959 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-23 16:34:52.989   330   959 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-23 16:34:52.989   330   959 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-23 16:34:52.989   330   959 D DrmWidevineDash: Service_Uninitialize: starts!
08-23 16:34:52.989   330   959 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-23 16:34:52.989   330   959 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,08-23 16:34:52.989   330   959 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-23 16:34:52.989   330   959 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-23 16:34:53.009  2804  6633 D UdcContextInitService: registered all accounts: true
,08-23 16:34:53.019  1996  2285 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 16:34:53.039  1996  2577 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 16:34:53.059  6638  6648 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6638, getuid(): 10011
,08-23 16:34:53.209  6638  6648 I qtaguid : Untagging socket 21
,08-23 16:34:53.249  6638  6648 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-23 16:34:53.249  6638  6648 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-23 16:34:53.649  6668  6668 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-23 16:34:53.799  6668  6668 I dex2oat : ----------------------------------------------------
08-23 16:34:53.799  6668  6668 I dex2oat : <SS>: S T A R T I N G . . .
08-23 16:34:53.799  6668  6668 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,08-23 16:34:53.799  6668  6668 I dex2oat : dex2oat took 149.814ms (threads: 4) arena alloc=234KB java alloc=43KB native alloc=1541KB free=1530KB
,08-23 16:34:53.809  6638  6648 W System  : ClassLoader referenced unknown path: 
,08-23 16:34:53.809  6638  6648 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,08-23 16:34:53.819  6638  6648 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 16:34:53.819  6638  6648 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 16:34:53.819  6638  6648 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 16:34:53.819  6638  6648 I Adreno-EGL: Local Branch: ss
08-23 16:34:53.819  6638  6648 I Adreno-EGL: Remote Branch: 
08-23 16:34:53.819  6638  6648 I Adreno-EGL: Local Patches: 
08-23 16:34:53.819  6638  6648 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:34:53.819  6638  6648 D libEGL  : eglInitialize EGLDisplay = 0xb3076264
,08-23 16:34:53.899  6638  6648 D libEGL  : eglTerminate EGLDisplay = 0xb30762bc
,08-23 16:34:54.019  6638  6648 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 16:34:54.019  6638  6648 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 16:34:54.019  6638  6648 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 16:34:54.019  6638  6648 I Adreno-EGL: Local Branch: ss
08-23 16:34:54.019  6638  6648 I Adreno-EGL: Remote Branch: 
08-23 16:34:54.019  6638  6648 I Adreno-EGL: Local Patches: 
08-23 16:34:54.019  6638  6648 I Adreno-EGL: Reconstruct Branch: 
08-23 16:34:54.019  6638  6648 D libEGL  : eglInitialize EGLDisplay = 0xb3076264
,08-23 16:34:54.069  6638  6648 D libEGL  : eglTerminate EGLDisplay = 0xb30762bc
,08-23 16:34:54.079  6638  6648 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-23 16:34:54.079  6638  6648 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-23 16:34:54.079  6638  6648 I Adreno-EGL: Build Date: 01/28/16 Thu
08-23 16:34:54.079  6638  6648 I Adreno-EGL: Local Branch: ss
08-23 16:34:54.079  6638  6648 I Adreno-EGL: Remote Branch: 
08-23 16:34:54.079  6638  6648 I Adreno-EGL: Local Patches: 
08-23 16:34:54.079  6638  6648 I Adreno-EGL: Reconstruct Branch: 
,08-23 16:34:54.079  6638  6648 D libEGL  : eglInitialize EGLDisplay = 0xb3076264
,08-23 16:34:54.129  6638  6648 D libEGL  : eglTerminate EGLDisplay = 0xb30762bc
,08-23 16:34:54.429  1996  6635 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 16:34:54.429  1996  6635 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:54.429   307  1193 D EnterpriseController: netId is 0
08-23 16:34:54.429   307  1193 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 16:34:54.429  1996  6635 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 1996, getuid(): 10011
,08-23 16:34:54.469  1996  6635 I qtaguid : Tagging socket 50 with tag 1000040100000000{268436481,0} uid 10011, pid: 1996, getuid(): 10011
,08-23 16:34:54.619  1996  2577 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 16:34:54.629  1996  2577 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-23 16:34:54.629  1996  2577 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-23 16:34:53.123+0200, stopTime=2016-08-23 16:34:54.637+0200, duration=1514ms
,08-23 16:34:54.639  1996  6699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 16:34:54.639  1996  6699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:54.649   307  1193 D EnterpriseController: netId is 0
08-23 16:34:54.649   307  1193 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 16:34:54.649   760  1910 V AlarmManager:  remove PendingIntent] PendingIntent{3e1bfad: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:54.649  1996  6699 I qtaguid : Tagging socket 51 with tag 1000310500000000{268448005,0} uid 10011, pid: 1996, getuid(): 10011
,08-23 16:34:54.699  1996  6699 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} uid 10011, pid: 1996, getuid(): 10011
,08-23 16:34:54.779   760  3447 D SSRM:n  : SIOP:: AP = 420, PST = 468, CUR = 300, LCD = 0
08-23 16:34:54.779   760  3447 D M       : limitCPUFreq:: freq = 1728000
08-23 16:34:54.779   760  3447 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1497600  uid : 1000  pid : 760  tag : SIOP_ARM_MAX@25
,08-23 16:34:54.779   760  3447 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 760  pkgName : SIOP_ARM_MAX@25
,08-23 16:34:54.779   760  3447 D M       : limitGPUFreq:: freq = 389000000
,08-23 16:34:54.789   760  3447 D M       : limitSmartBonding:: limit = false
08-23 16:34:54.789   760  3447 D M       : broadcastSiopChangedIntent:: FLASH = false, CAMERA = false, RECORDING = false, RECORDING_FPS = false, SMARTBONDING = false, LIVETHUMBNAIL = false
,08-23 16:34:54.789   760  3447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1096 com.android.server.ssrm.M.do:-1 i.t.z:-1 i.t.c:-1 i.e.hr:-1 
,08-23 16:34:54.789   760  3447 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 2
,08-23 16:34:54.799  2786  2786 D ContentApp:  LEVEL : 2
08-23 16:34:54.799  2786  2786 D ContentApp: stopScan() is called.
,08-23 16:34:54.809  6708  6708 E Zygote  : v2
08-23 16:34:54.809  6708  6708 I libpersona: KNOX_SDCARD checking this for 10053
08-23 16:34:54.809  6708  6708 I libpersona: KNOX_SDCARD not a persona
,08-23 16:34:54.809  6708  6708 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 16:34:54.809  6708  6708 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:34:54.809   760   844 I ActivityManager: Start proc 6708:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
08-23 16:34:54.809   760  1328 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-23 16:34:54.809  6708  6708 E Zygote  : accessInfo : 0
08-23 16:34:54.809  6708  6708 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,08-23 16:34:54.819   760  3447 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 16:34:54.859  6708  6708 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:34:54.859  6708  6708 D ActivityThread: Added TimaKeyStore provider
,08-23 16:34:54.879   760  2422 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e3bc673 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dcb930 6708:com.sec.android.app.videoplayer/u0a53}
,08-23 16:34:54.879   760  1328 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-23 16:34:54.899  6708  6708 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-23 16:34:54.919  6708  6708 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,08-23 16:34:54.949  6708  6708 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,08-23 16:34:54.979  6708  6708 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 16:34:54.979  6708  6708 D videowall-Global: core_num = 4
,08-23 16:34:54.999  6708  6708 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,08-23 16:34:54.999  6708  6708 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,08-23 16:34:54.999  6708  6708 D TranscodeReceiver:  SIOP_LEVEL: 2
,08-23 16:34:55.009   760  1910 I ActivityManager: Killing 5743:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,08-23 16:34:55.029  1996  6699 I qtaguid : Untagging socket 51
,08-23 16:34:55.029   760  2422 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,08-23 16:34:55.039   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{a87a9a9: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:55.099   760  2419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:34:55.099   760  2419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4287, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-23 16:34:55.099   760  2419 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-23 16:34:55.099   760  2419 D BatteryService: stay LED for fully charged
,08-23 16:34:55.099   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:34:55.099   760   760 I MotionRecognitionService: Plugged
08-23 16:34:55.099   760   760 D MotionRecognitionService:   cableConnection= 1
08-23 16:34:55.099   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:34:55.099   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:34:55.109  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:34:55.109  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:34:55.109  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:34:55.119  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:34:55.119  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:34:55.129  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:34:55.129  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:34:55.129  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:34:55.149  1996  2551 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-23 16:34:55.279  1996  6725 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 16:34:55.279  1996  6723 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 16:34:55.299  1996  6725 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 16:34:55.299  1996  6723 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 16:34:55.309  1996  6725 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 16:34:55.309  1996  6723 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 16:34:55.309  1996  6723 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-23 16:34:55.309  1996  6723 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 16:34:55.379   760  1756 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:55.429  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:55.429  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:55.429   307  1193 D EnterpriseController: netId is 0
08-23 16:34:55.429   307  1193 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-23 16:34:55.429  1996  6723 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:55.479  1996  6723 I qtaguid : Tagging socket 66 with tag 11065c9100000000{285629585,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:55.669   760  1491 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:55.679  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 16:34:55.679  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:55.679  1996  6723 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:55.779   760  1911 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:55.789  1996  6723 W Uploader: UNKNOWN no longer exists, so no auth token.
,08-23 16:34:55.799  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 16:34:55.799  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:55.799  1996  6723 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:55.899   760  1755 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:55.919  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:55.919  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 16:34:55.919  1996  6723 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:56.059   760  2421 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:56.059  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.059  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.069  1996  6723 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:56.179   760  1491 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:56.179   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:34:56.179  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.179  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.189  1996  6723 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:56.319   760  1911 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 16:34:56.329  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.329  1996  6723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.329  1996  6723 I qtaguid : Tagging socket 63 with tag 11065b5800000000{285629272,0} uid -1, pid: 1996, getuid(): 10011
,08-23 16:34:56.469   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{2f790eb: PendingIntentRecord{46e96bb com.google.android.gms broadcastIntent}}
,08-23 16:34:56.619   760   919 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 16:34:56.629   760   919 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-23 16:34:56.749  1996  6698 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.749  1996  6698 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 16:34:56.749  1996  6698 I qtaguid : Tagging socket 51 with tag 1000310200000000{268448002,0} uid 10011, pid: 1996, getuid(): 10011
,08-23 16:34:56.999  1996  6698 I qtaguid : Untagging socket 51
,08-23 16:34:56.999  1996  2551 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-23 16:34:59.379   760  1911 I ActivityManager: Killing 5821:com.android.email/u0a162 (adj 15): DHA:empty #37
,08-23 16:34:59.439   760  2423 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,08-23 16:34:59.989   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:35:01.089  6531  6610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 16:35:01.089  6531  6610 I jxcore-log: 
,08-23 16:35:01.089  6531  6610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 16:35:01.089  6531  6610 I jxcore-log: 
,08-23 16:35:01.099  6531  6610 D BluetoothAdapter: STATE_ON
,08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:35:01.099  6531  6610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 16:35:01.109  6531  6610 D BluetoothAdapter: STATE_ON
,08-23 16:35:01.109  6531  6610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 16:35:01.119  6531  6610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 16:35:01.119  6531  6610 I jxcore-log: 
,08-23 16:35:01.119  6531  6610 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 16:35:01.119  6531  6610 I jxcore-log: 
,08-23 16:35:01.759  6531  6610 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-23 16:35:01.759  6531  6610 I jxcore-log: Failed to execute UT.
08-23 16:35:01.759  6531  6610 I jxcore-log: 
,08-23 16:35:01.759  6531  6610 I jxcore-log: Unit Test app is loaded
08-23 16:35:01.759  6531  6610 I jxcore-log: 
,08-23 16:35:01.769  6531  6610 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 16:35:01.769  6531  6610 I jxcore-log: 
,08-23 16:35:01.779  6531  6531 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-23 16:35:01.779  6531  6610 I jxcore-log: My device name is: samsung-SM-G900F
08-23 16:35:01.779  6531  6610 I jxcore-log: 
,08-23 16:35:01.779  6531  6610 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 16:35:01.779  6531  6610 I jxcore-log: 
,08-23 16:35:04.859   760  3447 D SSRM:n  : SIOP:: AP = 420, PST = 456, CUR = 300, LCD = 0
,08-23 16:35:05.179   760  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:35:05.179   760  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:35:05.179   760  1756 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-23 16:35:05.179   760  1756 D BatteryService: stay LED for fully charged
08-23 16:35:05.179   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:35:05.179   760   760 I MotionRecognitionService: Plugged
,08-23 16:35:05.179   760   760 D MotionRecognitionService:   cableConnection= 1
08-23 16:35:05.179   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:35:05.179   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:35:05.179  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:05.179  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:05.189  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:35:05.189  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:05.189  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:05.189  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:35:05.189  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:05.209  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:06.799  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 16:35:06.799  6531  6610 I jxcore-log: 
,08-23 16:35:07.969  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 16:35:07.969  6531  6610 I jxcore-log: 
,08-23 16:35:07.999  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 16:35:07.999  6531  6610 I jxcore-log: 
,08-23 16:35:08.009  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 16:35:08.009  6531  6610 I jxcore-log: 
,08-23 16:35:08.029  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 16:35:08.029  6531  6610 I jxcore-log: 
,08-23 16:35:08.029  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 16:35:08.029  6531  6610 I jxcore-log: 
,08-23 16:35:11.999   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:35:11.999   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:35:11.999   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:35:11.999  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 16:35:11.999  6531  6610 I jxcore-log: 
,08-23 16:35:12.019  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 16:35:12.019  6531  6610 I jxcore-log: 
,08-23 16:35:12.029  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 16:35:12.029  6531  6610 I jxcore-log: 
,08-23 16:35:12.229  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 16:35:12.229  6531  6610 I jxcore-log: 
,08-23 16:35:13.269  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 16:35:13.269  6531  6610 I jxcore-log: 
,08-23 16:35:13.569  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 16:35:13.569  6531  6610 I jxcore-log: 
,08-23 16:35:13.579  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 16:35:13.579  6531  6610 I jxcore-log: 
,08-23 16:35:13.819  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 16:35:13.819  6531  6610 I jxcore-log: 
,08-23 16:35:13.839  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 16:35:13.839  6531  6610 I jxcore-log: 
,08-23 16:35:13.849  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 16:35:13.849  6531  6610 I jxcore-log: 
,08-23 16:35:13.859  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 16:35:13.859  6531  6610 I jxcore-log: 
,08-23 16:35:13.879  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-23 16:35:13.879  6531  6610 I jxcore-log: 
,08-23 16:35:13.899  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-23 16:35:13.899  6531  6610 I jxcore-log: 
,08-23 16:35:13.999  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 16:35:13.999  6531  6610 I jxcore-log: 
,08-23 16:35:14.009  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 16:35:14.009  6531  6610 I jxcore-log: 
,08-23 16:35:14.039  6531  6610 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 16:35:14.039  6531  6610 I jxcore-log: 
,08-23 16:35:14.049  6531  6610 D BluetoothAdapter: STATE_ON
,08-23 16:35:14.059  6531  6610 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 16:35:14.059  6531  6610 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 16:35:14.059  6531  6610 I jxcore-log: 
,08-23 16:35:14.909   760  3447 D SSRM:n  : SIOP:: AP = 410, PST = 444, CUR = 300, LCD = 0
,08-23 16:35:14.919   760  3447 D M       : limitCPUFreq:: freq = -1
,08-23 16:35:14.919   760  3447 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 760  tag : SIOP_ARM_MAX@25
,08-23 16:35:14.929   760  3447 D M       : limitGPUFreq:: freq = -1
,08-23 16:35:14.939   760  3447 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,08-23 16:35:14.959  2786  2786 D ContentApp:  LEVEL : 1
,08-23 16:35:14.989   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{349e4e1 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dcb930 6708:com.sec.android.app.videoplayer/u0a53}
,08-23 16:35:14.999   760  3447 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 16:35:14.999  6708  6708 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 16:35:15.009  6708  6708 D TranscodeReceiver:  SIOP_LEVEL: 1
,08-23 16:35:15.239   760  2421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:35:15.239   760  2421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:35:15.239   760  2421 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-23 16:35:15.239   760  2421 D BatteryService: stay LED for fully charged
,08-23 16:35:15.239   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:35:15.239   760   760 I MotionRecognitionService: Plugged
,08-23 16:35:15.239   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:35:15.239   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:35:15.239   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:35:15.239  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:15.239  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:35:15.249  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:35:15.249  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:35:15.249  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:15.269  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:15.269  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:35:15.269  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:16.079   760  1601 E Watchdog: !@Sync 4 [08-23 16:35:16.081]
,08-23 16:35:16.179   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:35:17.059  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:35:22.369   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:35:22.369   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:35:22.369   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:35:25.059   760  3447 D SSRM:n  : SIOP:: AP = 400, PST = 436, CUR = 300, LCD = 0
,08-23 16:35:25.329   760  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:35:25.329   760  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:35:25.329   760  1756 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:35:25.339   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:35:25.349   760   760 I MotionRecognitionService: Plugged
,08-23 16:35:25.349   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:35:25.349   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:35:25.359   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:35:25.369   760  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-23 16:35:25.369   760  1756 D BatteryService: stay LED for fully charged
,08-23 16:35:25.379  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:25.379  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:25.379  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:35:25.389  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:35:25.389  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:25.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:25.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:25.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:30.849   760  3447 D PowerManagerService: [api] setMasterBrightnessLimit : minBrightnss : -1  maxBrightness : 255 (uid: 1000 pid: 760)
,08-23 16:35:30.859   760   895 D DisplayPowerController: animateScreenStateChange[0]: target=1
,08-23 16:35:30.859   760   895 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
,08-23 16:35:30.859   760   895 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,08-23 16:35:30.869   760   895 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ 255))
,08-23 16:35:30.869   760   895 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,08-23 16:35:30.869   760  3447 D PowerManagerService: mDisplayReady: false
,08-23 16:35:30.869   760  3447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1096 com.android.server.ssrm.R.c:-1 com.android.server.ssrm.at.dT:-1 com.android.server.ssrm.at.dS:-1 com.android.server.ssrm.at.run:-1 
,08-23 16:35:30.879   760   895 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,08-23 16:35:30.879   760   895 D PowerManagerService: mDisplayReady: true
,08-23 16:35:30.879   760   895 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,08-23 16:35:30.929   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1393206 u0 com.sec.intent.action.MAX_BRIGHTNESS_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3c73165 2864:com.android.settings/1000}
,08-23 16:35:35.119   760  3447 D SSRM:n  : SIOP:: AP = 370, PST = 425, CUR = 300, LCD = 0
,08-23 16:35:35.129   760  3447 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,08-23 16:35:35.179   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{93c50c7 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dcb930 6708:com.sec.android.app.videoplayer/u0a53}
,08-23 16:35:35.189   760  3447 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-23 16:35:35.199  2786  2786 D ContentApp:  LEVEL : 0
,08-23 16:35:35.199  6708  6708 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 16:35:35.199  6708  6708 D TranscodeReceiver:  SIOP_LEVEL: 0
,08-23 16:35:35.379   760   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:35:35.379   760   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:35:35.379   760   781 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-23 16:35:35.379   760   781 D BatteryService: stay LED for fully charged
,08-23 16:35:35.379   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:35:35.379   760   760 I MotionRecognitionService: Plugged
,08-23 16:35:35.379   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:35:35.389   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:35:35.389   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:35:35.389  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:35.389  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:35:35.389  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:35:35.399  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:35:35.399  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:35.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:35.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:35.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:36.189   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:35:37.399   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:35:37.399   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:35:37.399   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:35:43.029  2804  5033 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:35:45.249   760  3447 D SSRM:n  : SIOP:: AP = 360, PST = 413, CUR = 300, LCD = 0
,08-23 16:35:45.459   760  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:35:45.469   760  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 326, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:35:45.469   760  1491 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:35:45.479   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:35:45.489   760   760 I MotionRecognitionService: Plugged
,08-23 16:35:45.489   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:35:45.499   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:35:45.499   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:35:45.509   760  1491 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms,
,08-23 16:35:45.509   760  1491 D BatteryService: stay LED for fully charged
,08-23 16:35:45.519  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:45.529  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:45.529  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:35:45.539  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:35:45.549  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:45.549  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:45.559  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:45.559  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:45.559  1996  3316 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:35:46.079   760  1601 E Watchdog: !@Sync 5 [08-23 16:35:46.090]
,08-23 16:35:46.099   760  3448 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,08-23 16:35:46.109   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d028adb u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb47b01 5952:com.samsung.android.sm.provider/1000}
,08-23 16:35:46.219   760  3448 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,08-23 16:35:46.229   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{604c851 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{cb47b01 5952:com.samsung.android.sm.provider/1000}
,08-23 16:35:55.309   760  3447 D SSRM:n  : SIOP:: AP = 350, PST = 401, CUR = 300, LCD = 0
,08-23 16:35:55.319   760  3447 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,08-23 16:35:55.329  2786  2786 D ContentApp:  LEVEL : -1
,08-23 16:35:55.379   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{194f9b7 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5dcb930 6708:com.sec.android.app.videoplayer/u0a53}
,08-23 16:35:55.379  6708  6708 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,08-23 16:35:55.379  6708  6708 D TranscodeReceiver:  SIOP_LEVEL: -1
,08-23 16:35:55.549   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:35:55.549   760  1784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0,
,08-23 16:35:55.559   760  1784 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:35:55.559   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:35:55.569   760   760 I MotionRecognitionService: Plugged
,08-23 16:35:55.569   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:35:55.579   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:35:55.579   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:35:55.579  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:55.579  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:35:55.589  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:35:55.589   760  1784 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-23 16:35:55.589   760  1784 D BatteryService: stay LED for fully charged
,08-23 16:35:55.599  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:35:55.599  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:35:55.609  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:55.609  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:55.609  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:35:56.189   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:35:57.289   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:35:57.289   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:35:57.289   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:36:05.429   760  3447 D SSRM:n  : SIOP:: AP = 340, PST = 389, CUR = 300, LCD = 0
,08-23 16:36:05.629   760  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:36:05.629   760  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 325, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:36:05.629   760  1325 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:36:05.639   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:36:05.659   760   760 I MotionRecognitionService: Plugged
,08-23 16:36:05.659   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:36:05.659   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:36:05.669   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:36:05.669   760  1325 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 41ms
,08-23 16:36:05.679   760  1325 D BatteryService: stay LED for fully charged
,08-23 16:36:05.679  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:05.679  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:05.679  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:36:05.689  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:36:05.699  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:05.699  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:05.709  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:05.709  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:14.359   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:36:14.359   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:36:14.359   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:36:15.489   760  3447 D SSRM:n  : SIOP:: AP = 340, PST = 381, CUR = 300, LCD = 0
,08-23 16:36:15.719   760  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:36:16.089   760  1601 E Watchdog: !@Sync 6 [08-23 16:36:16.092]
,08-23 16:36:16.199   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:36:17.149  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:36:25.549   760  3447 D SSRM:n  : SIOP:: AP = 340, PST = 375, CUR = 300, LCD = 0
,08-23 16:36:25.809   760  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:36:25.809   760  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:36:25.809   760  1325 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:36:25.819   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:36:25.829   760   760 I MotionRecognitionService: Plugged
,08-23 16:36:25.829   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:36:25.829   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:36:25.839   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:36:25.839   760  1325 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 16:36:25.839   760  1325 D BatteryService: stay LED for fully charged
,08-23 16:36:25.849  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:25.849  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:25.849  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:36:25.879  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:36:25.879  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:25.889  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:25.889  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:25.889  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:30.159   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:36:30.159   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:36:30.159   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:36:35.609   760  3447 D SSRM:n  : SIOP:: AP = 330, PST = 366, CUR = 300, LCD = 0
,08-23 16:36:35.899   760  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:36:35.899   760  1256 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 324, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:36:35.899   760  1256 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:36:35.909   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:36:35.929   760   760 I MotionRecognitionService: Plugged
,08-23 16:36:35.929   760   760 D MotionRecognitionService:   cableConnection= 1
08-23 16:36:35.929   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:36:35.929   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:36:35.929   760  1256 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:36:35.929   760  1256 D BatteryService: stay LED for fully charged
,08-23 16:36:35.929  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:35.939  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:36:35.939  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:36:35.949  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:36:35.949  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:35.959  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:35.959  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:35.959  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:36.209   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:36:45.669   760  3447 D SSRM:n  : SIOP:: AP = 330, PST = 357, CUR = 300, LCD = 0
,08-23 16:36:45.989   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:36:45.999   760  1755 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:36:45.999   760  1755 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:36:45.999   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:36:46.019   760   760 I MotionRecognitionService: Plugged
,08-23 16:36:46.019   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:36:46.019   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:36:46.029   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:36:46.029   760  1755 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-23 16:36:46.029   760  1755 D BatteryService: stay LED for fully charged
,08-23 16:36:46.029  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:46.029  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:46.029  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:36:46.049  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:36:46.049  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:46.059  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:46.059  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:46.059  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:46.089   760  1601 E Watchdog: !@Sync 7 [08-23 16:36:46.098]
,08-23 16:36:49.279   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:36:49.279   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:36:49.279   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:36:55.729   760  3447 D SSRM:n  : SIOP:: AP = 330, PST = 349, CUR = 300, LCD = 0
,08-23 16:36:56.079   760  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:36:56.079   760  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 323, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:36:56.079   760  1325 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:36:56.089   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:36:56.099   760   760 I MotionRecognitionService: Plugged
,08-23 16:36:56.099   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:36:56.099   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:36:56.109   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:36:56.109   760  1325 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:36:56.119   760  1325 D BatteryService: stay LED for fully charged
,08-23 16:36:56.129  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:36:56.129  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:36:56.129  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:36:56.139  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:36:56.139  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:36:56.149  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:56.159  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:56.159  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:36:56.209   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:37:05.799   760  3447 D SSRM:n  : SIOP:: AP = 330, PST = 342, CUR = 300, LCD = 0
,08-23 16:37:06.169   760  1911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:37:06.179   760  1911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:37:06.179   760  1911 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:37:06.189   760  1911 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 10ms
,08-23 16:37:06.189   760  1911 D BatteryService: stay LED for fully charged
,08-23 16:37:06.189   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:37:06.219   760   760 I MotionRecognitionService: Plugged
,08-23 16:37:06.219   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:37:06.219   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:37:06.229  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:06.229  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:37:06.229  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:37:06.229   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:37:06.239  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:37:06.239  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:37:06.249  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:06.249  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:06.249  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:15.849   760  3447 D SSRM:n  : SIOP:: AP = 330, PST = 338, CUR = 300, LCD = 0
,08-23 16:37:16.099   760  1601 E Watchdog: !@Sync 8 [08-23 16:37:16.102]
,08-23 16:37:16.209   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:37:16.259   760  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:37:16.269   760  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 322, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:37:16.269   760  1491 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:37:16.269   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:37:16.279   760   760 I MotionRecognitionService: Plugged
,08-23 16:37:16.289   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:37:16.289   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:37:16.289   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:37:16.289   760  1491 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-23 16:37:16.299   760  1491 D BatteryService: stay LED for fully charged
,08-23 16:37:16.299  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:16.299  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:16.309  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:37:16.329  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:37:16.329  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:37:16.339  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:16.339  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:37:16.339  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:17.259  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:37:17.419  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 148ms lastUpdatedAfter : 178696ms
,08-23 16:37:25.909   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 334, CUR = 300, LCD = 0
,08-23 16:37:26.349   760  2421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:37:26.349   760  2421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 321, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:37:26.359   760  2421 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:37:26.359   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:37:26.369   760   760 I MotionRecognitionService: Plugged
,08-23 16:37:26.369   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:37:26.379   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:37:26.379   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:37:26.379  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:26.379  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:37:26.379  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:37:26.379   760  2421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
08-23 16:37:26.379   760  2421 D BatteryService: stay LED for fully charged
,08-23 16:37:26.399  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:37:26.399  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:37:26.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:26.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:26.409  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:35.969   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 331, CUR = 300, LCD = 0
,08-23 16:37:36.219   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:37:36.429   760  2419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:37:46.029   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 300, LCD = 0
,08-23 16:37:46.099   760  1601 E Watchdog: !@Sync 9 [08-23 16:37:46.109]
,08-23 16:37:46.519   760  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:37:46.519   760  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:37:46.519   760  1756 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:37:46.529   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:37:46.539   760   760 I MotionRecognitionService: Plugged
,08-23 16:37:46.539   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:37:46.539   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:37:46.549   760  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 16:37:46.549   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:37:46.549   760  1756 D BatteryService: stay LED for fully charged
,08-23 16:37:46.569  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:46.569  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:46.579  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:37:46.589  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:37:46.589  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:37:46.599  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:46.599  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:46.599  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:56.089   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 300, LCD = 0
,08-23 16:37:56.219   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:37:56.609   760   780 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:37:56.609   760   780 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 320, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:37:56.609   760   780 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:37:56.619   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:37:56.629   760   760 I MotionRecognitionService: Plugged
,08-23 16:37:56.629   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:37:56.629   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:37:56.639   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:37:56.639   760   780 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 16:37:56.639   760   780 D BatteryService: stay LED for fully charged
,08-23 16:37:56.649  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:56.649  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:37:56.649  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:37:56.679  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:37:56.679  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:37:56.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:56.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:37:56.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:37:59.989   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:37:59.989   760  1240 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=315036 batch.start=331962
,08-23 16:38:00.019   760   760 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-23 16:38:00.019   760   760 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-23 16:38:00.019   760   760 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-23 16:38:00.029  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 16:38:00.029  1386  1386 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-23 16:38:00.039  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:38:00.099  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 16:38:00.099  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 16:38:00.119  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.119  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.119  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.119  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.119  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.119  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.129  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.179  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:38:00.729   760  1234 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 16:38:00.729   760  1234 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 16:38:00.739   760  1233 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 16:38:00.749   760  1234 I TLC_TIMA_PKM_initialize: initializing...
,08-23 16:38:00.749   760  1234 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,08-23 16:38:00.759   760  1234 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,08-23 16:38:00.759   760  1234 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,08-23 16:38:00.759   760  1234 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,08-23 16:38:00.759   760  1234 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-23 16:38:00.759   760  1234 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,08-23 16:38:00.769   760  1234 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,08-23 16:38:00.769   760  1234 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,08-23 16:38:00.769   760  1234 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 16:38:00.799   760  1234 D QSEECOMAPI: : Loaded image: APP id = 2
,08-23 16:38:00.809   760  1234 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-23 16:38:00.819   760  1234 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-23 16:38:04.149   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 16:38:04.149   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 16:38:04.159   760  1234 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:38:04.169   760  1234 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:38:06.149   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 300, LCD = 0
,08-23 16:38:06.699   760   780 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:38:06.709   760   780 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:38:06.709   760   780 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:38:06.709   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:38:06.719   760   760 I MotionRecognitionService: Plugged
,08-23 16:38:06.729   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:38:06.729   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:38:06.729   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:38:06.729   760   780 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,08-23 16:38:06.729   760   780 D BatteryService: stay LED for fully charged
,08-23 16:38:06.729  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:06.729  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:38:06.729  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:38:06.749  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:38:06.749  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:06.759  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:06.759  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:38:06.759  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:16.109   760  1601 E Watchdog: !@Sync 10 [08-23 16:38:16.115]
,08-23 16:38:16.209   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 300, LCD = 0
,08-23 16:38:16.219   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:38:16.929   760  1240 V AlarmManager: Expired Alarm result :4
,08-23 16:38:16.989   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5757a53 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b6fd09 2804:com.google.android.gms/u0a11}
,08-23 16:38:16.999   760  2423 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:38:16.999   760  2423 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 319, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:38:16.999   760  2423 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
08-23 16:38:16.999   760  2423 D BatteryService: stay LED for fully charged
08-23 16:38:16.999   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:38:17.029  6784  6784 E Zygote  : v2
,08-23 16:38:17.029  6784  6784 I libpersona: KNOX_SDCARD checking this for 1000
08-23 16:38:17.029  6784  6784 I libpersona: KNOX_SDCARD not a persona
,08-23 16:38:17.029  6784  6784 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 16:38:17.029  6784  6784 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:38:17.039   760  1240 I ActivityManager: Start proc 6784:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,08-23 16:38:17.039  6784  6784 E Zygote  : accessInfo : 0
,08-23 16:38:17.039   760   760 I MotionRecognitionService: Plugged
,08-23 16:38:17.039   760   760 D MotionRecognitionService:   cableConnection= 1
08-23 16:38:17.039   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:38:17.039   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:38:17.049  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:17.049  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:38:17.049  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:38:17.049  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:38:17.059  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:17.069  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:17.069  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:17.069  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:17.099  1555  1555 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-23 16:38:17.099  1555  1555 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-23 16:38:17.109  6784  6784 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:38:17.109  6784  6784 D ActivityThread: Added TimaKeyStore provider
,08-23 16:38:17.119  1555  1555 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-23 16:38:17.129  6784  6784 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,08-23 16:38:17.149  2804  6810 I EventLogChimeraService: Aggregate from 1471961273266 (log), 1471961273266 (data)
,08-23 16:38:17.149  6784  6784 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,08-23 16:38:17.269   760   770 I art     : Background partial concurrent mark sweep GC freed 66639(4MB) AllocSpace objects, 116(2MB) LOS objects, 27% free, 42MB/58MB, paused 1.815ms total 162.166ms
,08-23 16:38:17.399  6817  6817 E Zygote  : v2
,08-23 16:38:17.399  6817  6817 I libpersona: KNOX_SDCARD checking this for 1000
08-23 16:38:17.409  6817  6817 I libpersona: KNOX_SDCARD not a persona
08-23 16:38:17.409   760   844 I ActivityManager: Start proc 6817:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-23 16:38:17.409  6817  6817 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 16:38:17.409  6817  6817 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:38:17.409  6817  6817 E Zygote  : accessInfo : 0
,08-23 16:38:17.479  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:38:17.489  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:38:17.489  6817  6817 D ActivityThread: Added TimaKeyStore provider
,08-23 16:38:17.509   760  1911 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d0af9a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d77e0cb 6817:com.samsung.android.sm/1000}
,08-23 16:38:17.529  6817  6817 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-23 16:38:17.529   760  2423 I ActivityManager: Killing 5254:com.android.exchange/u0a163 (adj 15): DHA:empty #37
,08-23 16:38:17.579   760  1591 D ActivityManager: isAutoRunBlockedApp:: com.android.exchange, Auto Run ON
,08-23 16:38:17.619   760  2421 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{4d0af9a u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b6fd09 2804:com.google.android.gms/u0a11}
,08-23 16:38:17.649   760  1756 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db767c1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{d77e0cb 6817:com.samsung.android.sm/1000}
,08-23 16:38:17.669   760  1491 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{db767c1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7b6fd09 2804:com.google.android.gms/u0a11}
,08-23 16:38:17.849  2804  6829 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 16:38:17.879  2804  6829 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 16:38:17.889   760  2421 I ActivityManager: Killing 5849:com.sec.android.provider.badge/u0a77 (adj 15): DHA:empty #37
,08-23 16:38:17.919   760  1910 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
,08-23 16:38:19.769   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:38:19.769   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:38:19.769   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:38:20.869  1555  1555 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
,08-23 16:38:20.879   307  1190 D Netd    : Iface wlan0 link up
,08-23 16:38:20.889   760   848 D Tethering: interfaceLinkStateChanged wlan0, true
,08-23 16:38:20.889   760   848 D Tethering: interfaceStatusChanged wlan0, true
,08-23 16:38:20.899  1555  1555 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,08-23 16:38:20.929   760  1329 D WifiP2pService: InactiveState{ what=147461 }
,08-23 16:38:20.929   760  1329 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-23 16:38:20.929   760  1329 D WifiP2pService: DefaultState{ what=147461 }
,08-23 16:38:20.999   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fdafcc0 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{2ff499a 1386:com.android.systemui/u0a58}
,08-23 16:38:26.269   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 300, LCD = 0
,08-23 16:38:27.089   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:38:27.099   760  1755 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:38:27.099   760  1755 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:38:27.109   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:38:27.119   760   760 I MotionRecognitionService: Plugged
,08-23 16:38:27.119   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:38:27.119   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:38:27.119   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:38:27.129   760  1755 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:38:27.129   760  1755 D BatteryService: stay LED for fully charged
,08-23 16:38:27.139  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:27.139  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:27.139  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:38:27.169  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:38:27.169  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:27.179  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:27.179  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:38:27.179  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:36.229   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:38:36.329   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 300, LCD = 0
,08-23 16:38:37.179   760  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:38:37.189   760  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:38:37.189   760  2422 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:38:37.189   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:38:37.199   760   760 I MotionRecognitionService: Plugged
,08-23 16:38:37.199   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:38:37.209   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:38:37.209   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:38:37.209   760  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 27ms
,08-23 16:38:37.209   760  2422 D BatteryService: stay LED for fully charged
,08-23 16:38:37.209  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:37.209  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:38:37.209  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:38:37.229  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:38:37.229  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:37.239  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:37.239  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:37.239  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:38.159   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:38:38.159   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:38:38.159   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:38:46.109   760  1601 E Watchdog: !@Sync 11 [08-23 16:38:46.119]
,08-23 16:38:46.389   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 300, LCD = 0
,08-23 16:38:47.259   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:38:47.269   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 318, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:38:47.269   760  1592 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:38:47.269   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:38:47.289   760   760 I MotionRecognitionService: Plugged
,08-23 16:38:47.289   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:38:47.289   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:38:47.289   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:38:47.299   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:38:47.299   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:38:47.309  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:47.309  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:47.309  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:38:47.319  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 16:38:47.319  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:47.329  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:47.339  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:47.339  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:53.339   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:38:53.339   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:38:53.339   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:38:56.229   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:38:56.449   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 300, LCD = 0
,08-23 16:38:57.349   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:38:57.349   760  1755 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:38:57.349   760  1755 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:38:57.359   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:38:57.369   760   760 I MotionRecognitionService: Plugged
,08-23 16:38:57.369   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:38:57.369   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:38:57.379   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:38:57.379   760  1755 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:38:57.379   760  1755 D BatteryService: stay LED for fully charged
,08-23 16:38:57.399  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:57.399  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:38:57.409  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:38:57.419  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:38:57.419  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:38:57.429  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:57.429  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:57.429  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:38:59.989   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:39:06.519   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 300, LCD = 0
,08-23 16:39:07.439   760  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:39:07.439   760  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 317, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:39:07.439   760  2422 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:39:07.449   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:39:07.459   760   760 I MotionRecognitionService: Plugged
,08-23 16:39:07.459   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:39:07.459   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:39:07.459   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:39:07.469   760  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:39:07.469   760  2422 D BatteryService: stay LED for fully charged
,08-23 16:39:07.479  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:07.479  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:07.489  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:39:07.509  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:39:07.509  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:39:07.519  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:07.519  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:07.519  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:10.129  5921  5945 I PlayCommon: [825] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 16:39:10.139  5921  5945 I PlayCommon: [825] com.google.android.play.a.al.e(732): No file ready to send
,08-23 16:39:12.839   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:39:12.839   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:39:12.839   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:39:16.119   760  1601 E Watchdog: !@Sync 12 [08-23 16:39:16.126]
,08-23 16:39:16.239   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:39:16.569   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 300, LCD = 0
,08-23 16:39:17.519   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:39:17.529   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:39:17.529   760  1592 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:39:17.529   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:39:17.549   760   760 I MotionRecognitionService: Plugged
,08-23 16:39:17.549   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:39:17.549   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:39:17.549   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:39:17.559   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:39:17.559   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:39:17.559  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:17.559  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:39:17.559  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:39:17.579  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 16:39:17.579  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:39:17.589  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:17.589  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:17.589  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:17.589  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:39:22.279   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:39:22.279   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:39:22.279   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:39:26.629   760  3447 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 300, LCD = 0
,08-23 16:39:27.609   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:39:27.609   760  1755 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:39:27.619   760  1755 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:39:27.619   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:39:27.629   760   760 I MotionRecognitionService: Plugged
,08-23 16:39:27.629   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:39:27.629   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:39:27.639   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:39:27.639   760  1755 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:39:27.639   760  1755 D BatteryService: stay LED for fully charged
,08-23 16:39:27.659  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:27.659  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:39:27.659  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:39:27.669  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:39:27.669  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:39:27.679  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:27.679  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:27.679  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:36.239   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:39:36.679   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 300, LCD = 0
,08-23 16:39:37.359   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:39:37.359   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:39:37.359   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:39:37.699   760  2421 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:39:37.699   760  2421 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 316, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:39:37.699   760  2421 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:39:37.709   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:39:37.719   760   760 I MotionRecognitionService: Plugged
,08-23 16:39:37.729   760  2421 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-23 16:39:37.729   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:39:37.729   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:39:37.729   760  2421 D BatteryService: stay LED for fully charged
,08-23 16:39:37.739   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:39:37.749  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:37.759  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:39:37.759  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:39:37.769  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:39:37.769  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:39:37.779  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:37.779  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:37.779  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:46.119   760  1601 E Watchdog: !@Sync 13 [08-23 16:39:46.130]
,08-23 16:39:46.739   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 300, LCD = 0
,08-23 16:39:47.789   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:39:47.789   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 315, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:39:47.799   760  1592 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:39:47.799   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:39:47.809   760   760 I MotionRecognitionService: Plugged
,08-23 16:39:47.809   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:39:47.819   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:39:47.819   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:39:47.819   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 16:39:47.829   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:39:47.829  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:47.829  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:39:47.839  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:39:47.859  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:39:47.859  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:39:47.869  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:47.869  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:47.869  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:39:53.219   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:39:53.219   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:39:53.219   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:39:56.239   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:39:56.809   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 300, LCD = 0
,08-23 16:39:57.859   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:40:06.859   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 300, LCD = 0
,08-23 16:40:07.949   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:40:07.949   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:40:07.949   760  1592 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:40:07.959   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:40:07.969   760   760 I MotionRecognitionService: Plugged
,08-23 16:40:07.979   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:40:07.979   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:40:07.989   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:40:07.989   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 41ms
,08-23 16:40:07.999   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:40:08.009  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:40:08.009  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:40:08.009  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:40:08.019  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:40:08.019  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:40:08.029  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:08.029  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:08.029  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:12.079   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
08-23 16:40:12.079   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
08-23 16:40:12.079   307  1189 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,08-23 16:40:16.129   760  1601 E Watchdog: !@Sync 14 [08-23 16:40:16.135]
,08-23 16:40:16.249   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:40:16.919   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 300, LCD = 0
,08-23 16:40:17.609  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:40:17.719  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 95ms lastUpdatedAfter : 180300ms
,08-23 16:40:18.039   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:40:18.039   760  1755 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 314, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:40:18.039   760  1755 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:40:18.049   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:40:18.059   760   760 I MotionRecognitionService: Plugged
,08-23 16:40:18.059   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:40:18.069   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:40:18.069   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:40:18.069   760  1755 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 16:40:18.069   760  1755 D BatteryService: stay LED for fully charged
,08-23 16:40:18.079  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:40:18.079  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:40:18.089  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:40:18.109  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:40:18.109  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:40:18.119  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:18.119  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:18.119  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:26.979   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 300, LCD = 0
,08-23 16:40:28.109   760  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:40:36.249   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:40:37.039   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 300, LCD = 0
,08-23 16:40:38.199   760  1910 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:40:38.209   760  1910 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:40:38.209   760  1910 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:40:38.219   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:40:38.229   760   760 I MotionRecognitionService: Plugged
,08-23 16:40:38.229   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:40:38.229   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:40:38.239   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:40:38.239   760  1910 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 37ms
,08-23 16:40:38.239   760  1910 D BatteryService: stay LED for fully charged
,08-23 16:40:38.259  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:40:38.259  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:40:38.259  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:40:38.269  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:40:38.269  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:40:38.279  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:38.279  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:38.289  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:40:46.129   760  1601 E Watchdog: !@Sync 15 [08-23 16:40:46.140]
,08-23 16:40:47.099   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300, LCD = 0
,08-23 16:40:48.289   760   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:40:50.419   376   376 I bootchecker: bootchecker wake up!!
,08-23 16:40:56.259   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:40:57.159   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300, LCD = 0
,08-23 16:40:58.369   760  2423 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:41:07.219   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:41:08.479   760  2419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:41:08.479   760  2419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:41:08.479   760  2419 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:41:08.489   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:41:08.499   760   760 I MotionRecognitionService: Plugged
,08-23 16:41:08.499   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:41:08.499   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:41:08.499   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:41:08.509   760  2419 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:41:08.509   760  2419 D BatteryService: stay LED for fully charged
,08-23 16:41:08.509  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:41:08.509  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:41:08.509  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:41:08.529  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:41:08.529  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:41:08.539  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:41:08.539  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:41:08.539  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:41:16.139   760  1601 E Watchdog: !@Sync 16 [08-23 16:41:16.146]
,08-23 16:41:16.259   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:41:17.279   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:41:17.779  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:41:27.329   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:41:36.259   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:41:37.389   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:41:38.549   760  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:41:38.549   760  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 311, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:41:38.549   760  1491 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:41:38.559   760  1491 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 13ms
,08-23 16:41:38.559   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:41:38.569   760  1491 D BatteryService: stay LED for fully charged
,08-23 16:41:38.589   760   760 I MotionRecognitionService: Plugged
,08-23 16:41:38.589   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:41:38.589   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:41:38.589   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:41:38.599  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:41:38.599  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:41:38.609  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:41:38.619  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:41:38.619  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:41:38.629  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:41:38.629  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:41:38.629  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:41:46.139   760  1601 E Watchdog: !@Sync 17 [08-23 16:41:46.150]
,08-23 16:41:47.449   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:41:56.269   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:41:57.499   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:41:59.989   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:41:59.999   760  1240 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=555039 batch.start=679440
,08-23 16:42:00.019  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 16:42:00.019  1386  1386 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-23 16:42:00.019  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:42:00.059  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 16:42:00.059  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 16:42:00.069  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.069  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.069  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.079  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.089  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.089  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.089  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:00.149  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:42:07.559   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:42:08.609   760  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:42:08.609   760  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 310, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:42:08.619   760  2422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:42:08.619   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:42:08.629   760   760 I MotionRecognitionService: Plugged
,08-23 16:42:08.629   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:42:08.639   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:42:08.639   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:42:08.649   760  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:42:08.649   760  2422 D BatteryService: stay LED for fully charged
,08-23 16:42:08.659  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:42:08.659  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:42:08.659  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:42:08.669  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:42:08.669  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:42:08.679  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:42:08.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:42:08.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:42:16.149   760  1601 E Watchdog: !@Sync 18 [08-23 16:42:16.154]
,08-23 16:42:16.269   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:42:17.609   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:42:17.879  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:42:27.669   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:42:36.279   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:42:37.719   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:42:38.679   760  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:42:38.679   760  1325 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 309, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:42:38.689   760  1325 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:42:38.689   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:42:38.699   760   760 I MotionRecognitionService: Plugged
,08-23 16:42:38.699   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:42:38.709   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:42:38.709   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:42:38.709   760  1325 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:42:38.719   760  1325 D BatteryService: stay LED for fully charged
,08-23 16:42:38.729  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:42:38.729  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:42:38.729  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:42:38.759  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:42:38.759  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:42:38.759  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:42:38.759  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:42:38.759  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:42:46.149   760  1601 E Watchdog: !@Sync 19 [08-23 16:42:46.158]
,08-23 16:42:47.779   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:42:56.279   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:42:57.829   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:42:59.989   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:43:00.719   760  1234 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 16:43:00.719   760  1234 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 16:43:00.719   760  1233 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 16:43:02.199   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 16:43:02.199   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 16:43:02.209   760  1234 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:43:02.219   760  1234 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:43:07.889   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:43:08.749   760  2423 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:43:08.749   760  2423 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:43:08.759   760  2423 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:43:08.759   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:43:08.769   760   760 I MotionRecognitionService: Plugged
,08-23 16:43:08.769   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:43:08.779   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:43:08.779   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:43:08.779   760  2423 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 16:43:08.789   760  2423 D BatteryService: stay LED for fully charged
,08-23 16:43:08.799  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:43:08.809  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:43:08.809  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:43:08.819  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:43:08.819  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:43:08.829  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:43:08.829  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:43:08.829  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:43:16.159   760  1601 E Watchdog: !@Sync 20 [08-23 16:43:16.162]
,08-23 16:43:16.289   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:43:17.949   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:43:17.999  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:43:18.119  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 102ms lastUpdatedAfter : 180404ms
,08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10018, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10021, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10027, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10029, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10031, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10037, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10039, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.559   760   837 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10043, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10049, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10052, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10057, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10061, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10069, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10075, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10081, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10083, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10087, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10090, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10095, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10100, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10102, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10104, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10110, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10118, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10121, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.569   760   837 D NetworkPolicy: isUidForegroundLocked: 10123, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10125, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10134, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10137, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10139, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10146, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10149, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10151, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10161, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10165, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10170, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10172, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10174, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10176, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10180, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10184, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10188, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10193, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10194, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.579   760   837 D NetworkPolicy: isUidForegroundLocked: 10200, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.589   760   837 D NetworkPolicy: isUidForegroundLocked: 10201, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.589   760   837 D NetworkPolicy: isUidForegroundLocked: 10203, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.589   760   837 D NetworkPolicy: isUidForegroundLocked: 10204, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.589   760   837 D NetworkPolicy: isUidForegroundLocked: 10205, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-23 16:43:20.589   760   837 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-23 16:43:20.679   760   891 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,08-23 16:43:20.679   760   891 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,08-23 16:43:27.999   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,08-23 16:43:36.289   760  3477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 16:43:38.049   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 300, LCD = 0
,08-23 16:43:38.819   760  1911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:43:38.819   760  1911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 308, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:43:38.829   760  1911 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:43:38.829   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:43:38.839   760   760 I MotionRecognitionService: Plugged
,08-23 16:43:38.839   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:43:38.849   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:43:38.849   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:43:38.849   760  1911 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,08-23 16:43:38.859   760  1911 D BatteryService: stay LED for fully charged
,08-23 16:43:38.859  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:43:38.859  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:43:38.859  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:43:38.879  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:43:38.879  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:43:38.889  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:43:38.889  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:43:38.889  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:43:46.159   760  1601 E Watchdog: !@Sync 21 [08-23 16:43:46.170]
,08-23 16:43:48.109   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,08-23 16:43:58.179   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 300, LCD = 0
,08-23 16:44:04.399   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:44:08.239   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,08-23 16:44:08.899   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:44:08.899   760  1784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:44:08.899   760  1784 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:44:08.909   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:44:08.919   760   760 I MotionRecognitionService: Plugged
,08-23 16:44:08.919   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:44:08.919   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:44:08.929   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:44:08.929   760  1784 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 16:44:08.929   760  1784 D BatteryService: stay LED for fully charged
,08-23 16:44:08.949  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:44:08.949  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:44:08.949  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:44:08.969  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:44:08.969  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:44:08.979  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:44:08.979  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:44:08.979  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:44:16.169   760  1601 E Watchdog: !@Sync 22 [08-23 16:44:16.174]
,08-23 16:44:18.129  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:44:18.289   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,08-23 16:44:28.349   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,08-23 16:44:38.409   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,08-23 16:44:38.959   760  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:44:38.969   760  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:44:38.969   760  1491 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:44:38.969   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:44:38.979   760   760 I MotionRecognitionService: Plugged
,08-23 16:44:38.989   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:44:38.989   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:44:38.989   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:44:38.999   760  1491 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:44:38.999   760  1491 D BatteryService: stay LED for fully charged
,08-23 16:44:39.009  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:44:39.009  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:44:39.009  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:44:39.019  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:44:39.019  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:44:39.029  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:44:39.029  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:44:39.029  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:44:46.169   760  1601 E Watchdog: !@Sync 23 [08-23 16:44:46.178]
,08-23 16:44:48.459   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,08-23 16:44:58.519   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:45:08.579   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:45:09.029   760  2419 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:45:09.029   760  2419 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:45:09.039   760  2419 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:45:09.039   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:45:09.049   760   760 I MotionRecognitionService: Plugged
,08-23 16:45:09.049   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:45:09.059   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:45:09.059   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:45:09.059   760  2419 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:45:09.069   760  2419 D BatteryService: stay LED for fully charged
,08-23 16:45:09.079  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:45:09.079  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:45:09.079  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:45:09.109  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:45:09.109  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:45:09.109  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:45:09.109  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:45:09.109  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:45:16.179   760  1601 E Watchdog: !@Sync 24 [08-23 16:45:16.182]
,08-23 16:45:18.209  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:45:18.649   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:45:28.699   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:45:38.759   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:45:39.099   760  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:45:39.099   760  1591 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:45:39.099   760  1591 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:45:39.109   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:45:39.119   760   760 I MotionRecognitionService: Plugged
,08-23 16:45:39.129   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:45:39.129   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:45:39.129   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:45:39.139   760  1591 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-23 16:45:39.139   760  1591 D BatteryService: stay LED for fully charged
,08-23 16:45:39.159  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:45:39.159  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:45:39.159  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:45:39.169  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:45:39.169  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:45:39.179  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:45:39.179  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:45:39.179  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:45:46.179   760  1601 E Watchdog: !@Sync 25 [08-23 16:45:46.189]
,08-23 16:45:48.839   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:45:58.899   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:46:08.959   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:46:09.169   760  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:46:16.189   760  1601 E Watchdog: !@Sync 26 [08-23 16:46:16.195]
,08-23 16:46:18.329  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:46:18.459  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 115ms lastUpdatedAfter : 180339ms
,08-23 16:46:19.009   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:46:20.659   760  2426 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,08-23 16:46:20.669   760  2426 V MARsPolicyManager: updateSMDBValues
,08-23 16:46:20.669   760   888 E MARsDBManager: updateDBAll : begin --size 1
,08-23 16:46:20.699   760   888 I ActivityManager: Killing 1889:com.sec.android.app.shealth:remote/u0a34 (adj 5): SSR - service for lastStateTime 782s, lastActivityTime 718s
,08-23 16:46:20.699   760   888 I ActivityManager: Killing 1935:com.sec.android.service.health/u0a16 (adj 5): SSR - service for lastStateTime 776s, lastActivityTime 718s
,08-23 16:46:20.709   760   888 I ActivityManager: Killing 6106:com.samsung.android.sdk.samsunglink/u0a41 (adj 5): SSR - service for lastStateTime 722s, lastActivityTime 722s
,08-23 16:46:20.709   760   888 I ActivityManager: Killing 1510:com.sec.android.daemonapp/u0a181 (adj 8): SSR - service for lastStateTime 731s, lastActivityTime 731s
,08-23 16:46:20.719   760   888 I ActivityManager: Killing 3773:com.sec.spp.push/u0a37 (adj 8): SSR - service for lastStateTime 767s, lastActivityTime 732s
,08-23 16:46:20.719   760   888 I ActivityManager: Killing 4651:com.sec.android.pagebuddynotisvc/u0a26 (adj 8): SSR - service for lastStateTime 762s, lastActivityTime 762s
,08-23 16:46:20.719   760   888 I ActivityManager: Killing 3881:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 767s, lastActivityTime 767s
,08-23 16:46:20.769   760   888 E MARsDBManager: updateDBAll : end
,08-23 16:46:20.769   760   888 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,08-23 16:46:20.819   293   293 I ServiceManager: service 'AtCmdFwd' died
,08-23 16:46:20.819   383  4700 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,08-23 16:46:20.819   383  4700 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 16:46:20.819   760  1911 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,08-23 16:46:20.819   760  1911 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
08-23 16:46:20.819   760  1911 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,08-23 16:46:20.879   760   781 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
,08-23 16:46:20.879   760   781 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-23 16:46:20.879   760   781 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10944ms
,08-23 16:46:20.889  5986  5986 D HealthConsole: Service for HealthDataStore is disconnected
,08-23 16:46:20.889   760  1591 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
08-23 16:46:20.889   760  1591 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,08-23 16:46:20.899   760  2421 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
08-23 16:46:20.899   760  2421 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
08-23 16:46:20.899   760  2421 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20920ms
,08-23 16:46:20.909   760  1784 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.service.health, Auto Run ON
08-23 16:46:20.909   760  1784 I ActivityManager: isWidgetUsingPkg : com.sec.android.service.health no widget is using.
08-23 16:46:20.909   760  1784 W ActivityManager: Scheduling restart of crashed service com.sec.android.service.health/com.sec.android.sensor.framework.SensorService in 30910ms
,08-23 16:46:20.919   760  2423 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
08-23 16:46:20.919   760  2423 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-23 16:46:20.919   760  2423 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 30901ms
08-23 16:46:20.919   760  2423 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-23 16:46:20.919   760  2423 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 40901ms
,08-23 16:46:20.929   760  1911 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
,08-23 16:46:20.929   760  1911 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,08-23 16:46:20.959   760  1755 I ActivityManager: Start proc 6881:com.sec.android.app.shealth:remote/u0a34 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
,08-23 16:46:20.959  6881  6881 E Zygote  : v2
,08-23 16:46:20.969  6881  6881 I libpersona: KNOX_SDCARD checking this for 10034
08-23 16:46:20.969  6881  6881 I libpersona: KNOX_SDCARD not a persona
,08-23 16:46:20.969  6881  6881 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 16:46:20.969  6881  6881 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:46:20.979  6881  6881 E Zygote  : accessInfo : 0
,08-23 16:46:20.979  6881  6881 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,08-23 16:46:21.019  6881  6881 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:46:21.019  6881  6881 D ActivityThread: Added TimaKeyStore provider
,08-23 16:46:21.049  6881  6881 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,08-23 16:46:21.089  6881  6881 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,08-23 16:46:21.119  6881  6881 I MultiDex: VM with version 2.1.0 has multidex support
08-23 16:46:21.119  6881  6881 I MultiDex: install
08-23 16:46:21.119  6881  6881 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-23 16:46:21.119  6881  6881 I MultiDex: install
08-23 16:46:21.119  6881  6881 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 16:46:21.399  6904  6904 E Zygote  : v2
,08-23 16:46:21.399  6904  6904 I libpersona: KNOX_SDCARD checking this for 10016
,08-23 16:46:21.399  6904  6904 I libpersona: KNOX_SDCARD not a persona
,08-23 16:46:21.399  6904  6904 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 16:46:21.399  6904  6904 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:46:21.409  6904  6904 E Zygote  : accessInfo : 0
,08-23 16:46:21.409  6904  6904 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,08-23 16:46:21.409   760  1784 I ActivityManager: Start proc 6904:com.sec.android.service.health/u0a16 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,08-23 16:46:21.439  6904  6904 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 16:46:21.439  6904  6904 D ActivityThread: Added TimaKeyStore provider
,08-23 16:46:21.459  6904  6904 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,08-23 16:46:21.499  6881  6881 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-23 16:46:21.499  6881  6881 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-23 16:46:21.529  1386  1386 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,08-23 16:46:21.529   760  1755 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10034
,08-23 16:46:21.539   760  2419 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10034
,08-23 16:46:21.549  1386  1386 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{60348e VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
,08-23 16:46:21.549  1386  1386 D AdaptiveEventManager: M updateContainers()
08-23 16:46:21.549  1386  1386 D AdaptiveEventContainerSmall: C updatePedoContainer()
08-23 16:46:21.549  1386  1386 D AdaptiveEventContainerSmall: handlePedoUpdate()
,08-23 16:46:21.549  1386  1386 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,08-23 16:46:21.549   760  1325 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10034
,08-23 16:46:21.559   760  1256 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10034
,08-23 16:46:21.579  6881  6881 I Health.HealthService: HealthService: onCreate() start (6881)
,08-23 16:46:21.659  5986  5986 D HealthDataStore: Service for HealthDataStore is connected
,08-23 16:46:21.659  5986  5986 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-23 16:46:21.669   760   781 I ActivityManager: Killing 5865:com.samsung.android.service.travel/u0a177 (adj 15): DHA:empty #37
,08-23 16:46:21.699  5986  5986 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-23 16:46:21.699  5986  5986 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 16:46:21.699   760  2419 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.service.travel, Auto Run ON
,08-23 16:46:21.739  6881  6881 D HealthDataStore: Service for HealthDataStore is connected
,08-23 16:46:21.739  6881  6881 D HealthDataStore: HealthConnectionErrorResult code : 9
,08-23 16:46:21.739  6881  6881 D HealthConsole: Service for HealthDataConsole is connected
,08-23 16:46:21.739  6881  6881 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,08-23 16:46:21.739  6881  6881 E HealthDataStore: disconnectService: Context instance is invalid
,08-23 16:46:21.819   383  4700 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 16:46:21.839   760   844 I ActivityManager: Start proc 6927:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,08-23 16:46:21.839  6927  6927 E Zygote  : v2
08-23 16:46:21.839  6927  6927 I libpersona: KNOX_SDCARD checking this for 1000
08-23 16:46:21.839  6927  6927 I libpersona: KNOX_SDCARD not a persona
,08-23 16:46:21.839  6927  6927 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 16:46:21.839  6927  6927 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:46:21.839  6927  6927 E Zygote  : accessInfo : 0
,08-23 16:46:21.859  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 16:46:21.869  6927  6927 D ActivityThread: Added TimaKeyStore provider
,08-23 16:46:21.879  6927  6927 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,08-23 16:46:21.889  6927  6927 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,08-23 16:46:21.889  6927  6927 D AtFwdService: onCreate method
,08-23 16:46:21.889  6927  6927 I AtFwdService: Instantiate AtCmdFwd Service
,08-23 16:46:21.899  6927  6939 D AtCkpdCmdHandler: De-queing command
,08-23 16:46:21.909  6881  6918 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,08-23 16:46:21.949  6881  6941 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,08-23 16:46:21.959  6904  6915 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-23 16:46:21.969   420   420 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10016, gid 10016, pid 6904
08-23 16:46:21.969   420   420 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,08-23 16:46:22.099  6904  6915 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,08-23 16:46:22.129  6881  6941 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,08-23 16:46:22.279  6881  6941 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,08-23 16:46:22.279  6881  6941 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,08-23 16:46:22.399   420   420 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,08-23 16:46:22.459  6904  6915 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,08-23 16:46:22.459  6904  6915 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,08-23 16:46:22.459  6904  6915 D HSCheck : SS_G-f9 72 b5 9e 08 97 75 b4 ec eb 60 ef 74 94 30 b0 
,08-23 16:46:29.069   760  3447 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 300, LCD = 0
,08-23 16:46:31.889  6959  6959 E Zygote  : v2
,08-23 16:46:31.899   760   844 I ActivityManager: Start proc 6959:com.sec.android.pagebuddynotisvc/u0a26 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,08-23 16:46:31.899  6959  6959 I libpersona: KNOX_SDCARD checking this for 10026
08-23 16:46:31.899  6959  6959 I libpersona: KNOX_SDCARD not a persona
,08-23 16:46:31.899  6959  6959 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-23 16:46:31.899  6959  6959 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:46:31.909  6959  6959 E Zygote  : accessInfo : 0
,08-23 16:46:31.909  6959  6959 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,08-23 16:46:31.949  6959  6959 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 16:46:31.949  6959  6959 D ActivityThread: Added TimaKeyStore provider
,08-23 16:46:31.969  6959  6959 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,08-23 16:46:31.989  6959  6959 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,08-23 16:46:31.999  6959  6959 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,08-23 16:46:31.999  6959  6959 D ContextualPageNotification: resetAllNotification : all clear!!!
,08-23 16:46:39.129   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:46:39.239   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:46:39.249   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:46:39.249   760  1592 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:46:39.259   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:46:39.269   760   760 I MotionRecognitionService: Plugged
,08-23 16:46:39.269   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:46:39.269   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:46:39.269   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:46:39.279   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:46:39.279   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:46:39.289  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:46:39.289  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:46:39.289  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:46:39.309  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:46:39.309  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:46:39.319  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:46:39.319  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:46:39.319  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:46:41.889   760   844 I ActivityManager: Start proc 6972:com.sec.android.daemonapp/u0a181 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
08-23 16:46:41.889   760  1328 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-23 16:46:41.899  6972  6972 E Zygote  : v2
,08-23 16:46:41.899  6972  6972 I libpersona: KNOX_SDCARD checking this for 10181
08-23 16:46:41.899  6972  6972 I libpersona: KNOX_SDCARD not a persona
,08-23 16:46:41.899  6972  6972 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51,
08-23 16:46:41.909  6972  6972 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-23 16:46:41.909  6972  6972 E Zygote  : accessInfo : 0
,08-23 16:46:41.909  6972  6972 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,08-23 16:46:41.949  6972  6972 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 16:46:41.949  6972  6972 D ActivityThread: Added TimaKeyStore provider
,08-23 16:46:41.969   760  1328 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,08-23 16:46:41.979  6972  6972 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,08-23 16:46:42.009  6972  6972 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,08-23 16:46:42.029  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,08-23 16:46:42.039  6972  6972 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 16:46:42.039   760   844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{6db894c u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c16cd95 6972:com.sec.android.daemonapp/u0a181}
,08-23 16:46:42.039  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,08-23 16:46:42.039  6972  6972 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 16:46:42.049  6972  6972 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
08-23 16:46:42.049  6972  6972 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 16:46:42.049  6972  6972 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,08-23 16:46:42.049  6972  6972 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,08-23 16:46:42.059  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 16:46:42.059  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,08-23 16:46:42.059  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,08-23 16:46:42.069  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 16:46:42.069  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 16:46:42.069  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,08-23 16:46:42.069  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-23 16:46:42.089  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,08-23 16:46:42.089  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 16:46:42.089  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 16:46:42.089  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,08-23 16:46:42.099  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,08-23 16:46:42.099  6972  6972 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 16:46:42.099  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-23 16:46:42.099  6972  6972 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-23 16:46:42.099  6972  6972 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 16:46:42.099  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-23 16:46:42.099  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-23 16:46:42.099  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-23 16:46:42.099  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 16:46:42.099  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 16:46:42.099  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-23 16:46:42.099  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.109  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 16:46:42.109   760  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b63ae11 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c16cd95 6972:com.sec.android.daemonapp/u0a181}
,08-23 16:46:42.109  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 16:46:42.109  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 16:46:42.109  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 16:46:42.119  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 16:46:42.119  6972  6972 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-23 16:46:42.119  6972  6972 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 16:46:42.119  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.119  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 16:46:42.129   760  1911 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aa07b76 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c16cd95 6972:com.sec.android.daemonapp/u0a181}
,08-23 16:46:42.129  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 16:46:42.129  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 16:46:42.129  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 16:46:42.129  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 16:46:42.139  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 16:46:42.139  6972  6972 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
08-23 16:46:42.139  6972  6972 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 16:46:42.139  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.139  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 16:46:42.149   760  1591 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f36b577 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{c16cd95 6972:com.sec.android.daemonapp/u0a181}
,08-23 16:46:42.149  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,08-23 16:46:42.149  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
08-23 16:46:42.149  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 16:46:42.149  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.149  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,08-23 16:46:42.149  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 16:46:42.159  6972  6972 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,08-23 16:46:42.159  6972  6972 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 16:46:42.159  6972  6972 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 16:46:42.159  6972  6972 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,08-23 16:46:46.189   760  1601 E Watchdog: !@Sync 27 [08-23 16:46:46.199]
,08-23 16:46:49.189   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:46:59.249   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:47:09.299   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:47:09.309   760  1784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:47:09.309   760  1784 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:47:09.319   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:47:09.329   760   760 I MotionRecognitionService: Plugged
,08-23 16:47:09.329   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:47:09.339   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:47:09.339   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:47:09.339   760  1784 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-23 16:47:09.349   760  1784 D BatteryService: stay LED for fully charged
,08-23 16:47:09.359  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:47:09.359  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:47:09.359  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:47:09.369  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:47:09.369  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:47:09.379  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:47:09.379  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:47:09.379  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:47:09.389   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:47:16.199   760  1601 E Watchdog: !@Sync 28 [08-23 16:47:16.204]
,08-23 16:47:18.569  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:47:19.439   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:47:29.499   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:47:39.379   760  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:47:39.379   760  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:47:39.389   760  1756 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:47:39.389   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:47:39.399   760   760 I MotionRecognitionService: Plugged,
08-23 16:47:39.409   760   760 D MotionRecognitionService:   cableConnection= 1
08-23 16:47:39.409   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-23 16:47:39.409   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:47:39.409   760  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,08-23 16:47:39.409   760  1756 D BatteryService: stay LED for fully charged
,08-23 16:47:39.409  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:47:39.409  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:47:39.419  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:47:39.429  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:47:39.429  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:47:39.439  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:47:39.439  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:47:39.439  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:47:39.549   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:47:46.199   760  1601 E Watchdog: !@Sync 29 [08-23 16:47:46.208]
,08-23 16:47:49.609   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:47:59.659   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,08-23 16:48:00.719   760  1234 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 16:48:00.719   760  1234 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 16:48:00.719   760  1233 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 16:48:04.099   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 16:48:04.099   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 16:48:04.109   760  1234 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:48:04.119   760  1234 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:48:09.449   760  2423 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:48:09.449   760  2423 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:48:09.459   760  2423 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:48:09.459   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:48:09.469   760   760 I MotionRecognitionService: Plugged
,08-23 16:48:09.469   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:48:09.479   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:48:09.479   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:48:09.479   760  2423 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,08-23 16:48:09.489   760  2423 D BatteryService: stay LED for fully charged
,08-23 16:48:09.499  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:48:09.499  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:48:09.509  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:48:09.519  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:48:09.519  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:48:09.529  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:48:09.539  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:48:09.539  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:48:09.729   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:48:16.209   760  1601 E Watchdog: !@Sync 30 [08-23 16:48:16.212]
,08-23 16:48:18.629  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:48:19.789   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:48:22.929   760  1240 V AlarmManager: Expired Alarm result :4
,08-23 16:48:22.969  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 16:48:22.969  1386  1386 I PERF    : received broadcast android.intent.action.TIME_TICK
,08-23 16:48:22.969  1386  1386 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 16:48:23.009  1386  1386 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 16:48:23.019  1386  1386 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 16:48:23.029   760   844 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
,08-23 16:48:23.039  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.049  2327  2478 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 16:48:23.049  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.049  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 16:48:23.059  2327  2478 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 16:48:23.059  2327  2478 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 16:48:23.059  2327  2478 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,08-23 16:48:23.059  2327  2548 D bt_upio : upio_start_stop_timer : timer_settime success
,08-23 16:48:23.059  2327  2548 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,08-23 16:48:23.069  2327  2548 D bt_vendor: op for 7
,08-23 16:48:23.069  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.069  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.069  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.069  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.069  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.069  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.069  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 16:48:23.069  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.069  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.069  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.069  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.069  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.069  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 16:48:23.069  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.079  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.079  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
,08-23 16:48:23.079  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.079  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.079  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.079  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.079  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 16:48:23.079  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.079  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.079  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.079  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.079  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.079  2327  2548 D bt_vendor: op for 7
,08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.089  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.089  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.089  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.089  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 16:48:23.089  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.089  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.089  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.089  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.089  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.089  2327  2548 D bt_vendor: op for 7
,08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.089  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.089  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.089  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
,08-23 16:48:23.099  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.099  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
08-23 16:48:23.099  2327  2548 D bt_vendor: op for 7
08-23 16:48:23.099  2327  2548 D bt_upio : upio_set : pio 0 action 2, polarity 1
08-23 16:48:23.099  2327  2548 D bt_upio : BT_WAKE is asserted already
,08-23 16:48:23.109  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.109  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.109  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.109  1386  1386 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.109  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.119   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{d450e49: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.129   760   780 V AlarmManager:  remove PendingIntent] PendingIntent{637834e: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.129   760  2419 V AlarmManager:  remove PendingIntent] PendingIntent{bf8dc6f: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.139   760   781 V AlarmManager:  remove PendingIntent] PendingIntent{8f9dd7c: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.159   760  1591 V AlarmManager:  remove PendingIntent] PendingIntent{dc74605: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.159  1386  1386 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-23 16:48:23.169   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{20c865a: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.179   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{3e0d08b: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.179   760  2423 V AlarmManager:  remove PendingIntent] PendingIntent{cc55568: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.179   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{67b3d81: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.189   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{1fcae26: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.189   760  2419 V AlarmManager:  remove PendingIntent] PendingIntent{d09ea67: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.189   760  2423 V AlarmManager:  remove PendingIntent] PendingIntent{54e6014: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.199   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{71d30bd: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.199   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{b7586b2: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.199   760  2419 V AlarmManager:  remove PendingIntent] PendingIntent{fc0c603: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.199   760  2423 V AlarmManager:  remove PendingIntent] PendingIntent{abb6980: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.209   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{4f11bb9: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.209   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{b315bfe: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.209   760  2419 V AlarmManager:  remove PendingIntent] PendingIntent{27fbf5f: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.219   760  2423 V AlarmManager:  remove PendingIntent] PendingIntent{f2d9dac: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.219   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{b7eba75: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.219   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{d433a0a: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.219   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{f0af27b: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.229   760   781 V AlarmManager:  remove PendingIntent] PendingIntent{3ace898: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.229   760  1755 V AlarmManager:  remove PendingIntent] PendingIntent{d0d88f1: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.229   760  1256 V AlarmManager:  remove PendingIntent] PendingIntent{9e2ecd6: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.239   760  2422 V AlarmManager:  remove PendingIntent] PendingIntent{d4c3b57: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.239   760  1756 V AlarmManager:  remove PendingIntent] PendingIntent{fd3f644: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.239   760  1592 V AlarmManager:  remove PendingIntent] PendingIntent{ee0c32d: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.239   760  2423 V AlarmManager:  remove PendingIntent] PendingIntent{2f90062: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.249   760  1910 V AlarmManager:  remove PendingIntent] PendingIntent{fef35f3: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.249   760  1325 V AlarmManager:  remove PendingIntent] PendingIntent{83c32b0: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.249   760  1591 V AlarmManager:  remove PendingIntent] PendingIntent{d336529: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.249   760  2419 V AlarmManager:  remove PendingIntent] PendingIntent{e6ac0ae: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.259   760  1784 V AlarmManager:  remove PendingIntent] PendingIntent{ebd3e4f: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.259   760  1911 V AlarmManager:  remove PendingIntent] PendingIntent{fa9c9dc: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.259   760   780 V AlarmManager:  remove PendingIntent] PendingIntent{2f42ae5: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.259   760  2421 V AlarmManager:  remove PendingIntent] PendingIntent{92639ba: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.259   760  1491 V AlarmManager:  remove PendingIntent] PendingIntent{ab9706b: PendingIntentRecord{d944c50 com.android.bluetooth broadcastIntent}}
,08-23 16:48:23.859  2327  2770 D bt_upio : ..proc_btwrite_timeout..
,08-23 16:48:23.859  2327  2770 D bt_upio : upio_set : pio 0 action 1, polarity 1
,08-23 16:48:29.839   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:48:38.279   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:48:39.529   760  2422 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:48:39.529   760  2422 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:48:39.529   760  2422 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:48:39.539   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:48:39.549   760   760 I MotionRecognitionService: Plugged
,08-23 16:48:39.549   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:48:39.549   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:48:39.559   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:48:39.569   760  2422 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-23 16:48:39.569   760  2422 D BatteryService: stay LED for fully charged
,08-23 16:48:39.569  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:48:39.569  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:48:39.569  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:48:39.579  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:48:39.589  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:48:39.589  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:48:39.599  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:48:39.599  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:48:39.889   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:48:46.209   760  1601 E Watchdog: !@Sync 31 [08-23 16:48:46.216]
,08-23 16:48:49.949   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:48:59.989   760  1240 V AlarmManager: Expired Alarm result :8
,08-23 16:48:59.999   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:49:09.609   760  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:49:09.619   760  1591 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:49:09.619   760  1591 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:49:09.619   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:49:09.639   760   760 I MotionRecognitionService: Plugged
,08-23 16:49:09.639   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:49:09.639   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:49:09.639   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:49:09.649   760  1591 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:49:09.649   760  1591 D BatteryService: stay LED for fully charged
,08-23 16:49:09.669  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:49:09.669  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:49:09.669  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:49:09.679  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:49:09.679  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:49:09.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:49:09.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:49:09.689  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:49:10.059   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:49:16.209   760  1601 E Watchdog: !@Sync 32 [08-23 16:49:16.221]
,08-23 16:49:18.649  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:49:18.769  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 103ms lastUpdatedAfter : 180307ms
,08-23 16:49:20.119   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:49:22.289  5921  5945 I PlayCommon: [825] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 16:49:22.289  5921  5945 I PlayCommon: [825] com.google.android.play.a.al.e(732): No file ready to send
,08-23 16:49:30.179   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:49:39.679   760  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:49:39.689   760  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:49:39.689   760  1491 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:49:39.689   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:49:39.699   760   760 I MotionRecognitionService: Plugged
,08-23 16:49:39.709   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:49:39.709   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:49:39.709   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:49:39.719   760  1491 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-23 16:49:39.719   760  1491 D BatteryService: stay LED for fully charged
,08-23 16:49:39.729  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:49:39.729  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:49:39.729  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:49:39.769  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:49:39.769  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:49:39.769  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:49:39.769  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:49:39.769  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:49:40.229   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:49:46.219   760  1601 E Watchdog: !@Sync 33 [08-23 16:49:46.226]
,08-23 16:49:50.279   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:50:00.339   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:50:09.759   760   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:50:09.769   760   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:50:09.769   760   781 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:50:09.769   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:50:09.779   760   760 I MotionRecognitionService: Plugged
,08-23 16:50:09.789   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:50:09.789   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:50:09.789   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:50:09.799   760   781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 16:50:09.799   760   781 D BatteryService: stay LED for fully charged
,08-23 16:50:09.809  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:50:09.819  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:50:09.819  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:50:09.829  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:50:09.829  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:50:09.839  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:50:09.839  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:50:09.839  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:50:10.389   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:50:13.429   760   770 I art     : Background sticky concurrent mark sweep GC freed 66631(8MB) AllocSpace objects, 360(7MB) LOS objects, 27% free, 42MB/58MB, paused 2.652ms total 146.781ms
,08-23 16:50:16.219   760  1601 E Watchdog: !@Sync 34 [08-23 16:50:16.230]
,08-23 16:50:18.779  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:50:20.439   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:50:30.499   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:50:39.829   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:50:39.839   760  1784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:50:39.839   760  1784 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:50:39.849   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:50:39.859   760   760 I MotionRecognitionService: Plugged
,08-23 16:50:39.859   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:50:39.859   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:50:39.859   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:50:39.869   760  1784 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:50:39.869   760  1784 D BatteryService: stay LED for fully charged
,08-23 16:50:39.869  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:50:39.869  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:50:39.869  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:50:39.889  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:50:39.889  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:50:39.899  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:50:39.899  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:50:39.899  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:50:40.559   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:50:46.229   760  1601 E Watchdog: !@Sync 35 [08-23 16:50:46.238]
,08-23 16:50:50.609   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:51:00.669   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:51:09.909   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:51:10.729   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:51:16.239   760  1601 E Watchdog: !@Sync 36 [08-23 16:51:16.242]
,08-23 16:51:18.809  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:51:20.779   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:51:30.839   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:51:39.989   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:51:39.999   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:51:39.999   760  1592 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:51:39.999   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:51:40.009   760   760 I MotionRecognitionService: Plugged
,08-23 16:51:40.009   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:51:40.019   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:51:40.019   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:51:40.029   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,08-23 16:51:40.029   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:51:40.039  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:51:40.039  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:51:40.039  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:51:40.079  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:51:40.079  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:51:40.079  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:51:40.079  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:51:40.079  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:51:40.889   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:51:46.239   760  1601 E Watchdog: !@Sync 37 [08-23 16:51:46.247]
,08-23 16:51:50.949   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:52:01.009   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,08-23 16:52:10.069   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:52:11.059   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,08-23 16:52:16.249   760  1601 E Watchdog: !@Sync 38 [08-23 16:52:16.251]
,08-23 16:52:18.919  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:52:19.029  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 91ms lastUpdatedAfter : 180258ms
,08-23 16:52:21.119   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,08-23 16:52:31.179   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,08-23 16:52:40.149   760   781 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:52:40.149   760   781 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:52:40.159   760   781 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:52:40.159   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:52:40.179   760   760 I MotionRecognitionService: Plugged
,08-23 16:52:40.179   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:52:40.179   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:52:40.179   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:52:40.189   760   781 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,08-23 16:52:40.189   760   781 D BatteryService: stay LED for fully charged
,08-23 16:52:40.209  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:52:40.209  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:52:40.209  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-23 16:52:40.229  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:52:40.229  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:52:40.239  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:52:40.239  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:52:40.239  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:52:41.239   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,08-23 16:52:46.249   760  1601 E Watchdog: !@Sync 39 [08-23 16:52:46.256]
,08-23 16:52:51.299   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,08-23 16:53:00.719   760  1234 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 16:53:00.719   760  1234 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 16:53:00.719   760  1233 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 16:53:01.369   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,08-23 16:53:02.229   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 16:53:02.229   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 16:53:02.239   760  1234 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:53:02.249   760  1234 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:53:10.229   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:53:10.229   760  1592 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:53:10.239   760  1592 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:53:10.239   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:53:10.249   760   760 I MotionRecognitionService: Plugged
,08-23 16:53:10.249   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:53:10.259   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:53:10.259   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:53:10.259   760  1592 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,08-23 16:53:10.269   760  1592 D BatteryService: stay LED for fully charged
,08-23 16:53:10.269  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:53:10.269  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:53:10.269  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:53:10.279  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:53:10.289  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:53:10.299  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:53:10.299  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-23 16:53:10.299  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:53:11.439   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 294, CUR = 300, LCD = 0
,08-23 16:53:12.799   760   837 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 16:53:16.249   760  1601 E Watchdog: !@Sync 40 [08-23 16:53:16.260]
,08-23 16:53:19.089  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:53:21.489   760  3447 D SSRM:n  : SIOP:: AP = 300, PST = 294, CUR = 300, LCD = 0
,08-23 16:53:31.539   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,08-23 16:53:40.309   760  1755 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:53:40.319   760  1755 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:53:40.319   760  1755 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:53:40.319   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:53:40.339   760   760 I MotionRecognitionService: Plugged
,08-23 16:53:40.339   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:53:40.339   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:53:40.349   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:53:40.349   760  1755 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,08-23 16:53:40.349   760  1755 D BatteryService: stay LED for fully charged
,08-23 16:53:40.369  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:53:40.369  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-23 16:53:40.369  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:53:40.379  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:53:40.379  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:53:40.389  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:53:40.389  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:53:40.389  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:53:41.599   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:53:46.259   760  1601 E Watchdog: !@Sync 41 [08-23 16:53:46.264]
,08-23 16:53:51.659   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:54:01.719   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:54:10.389   760  1256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:54:11.769   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:54:16.259   760  1601 E Watchdog: !@Sync 42 [08-23 16:54:16.268]
,08-23 16:54:19.279  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:54:21.829   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:54:22.379  5921  5945 I PlayCommon: [825] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-23 16:54:22.379  5921  5945 I PlayCommon: [825] com.google.android.play.a.al.e(732): No file ready to send
,08-23 16:54:31.889   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:54:40.479   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:54:40.479   760  1784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:54:40.489   760  1784 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:54:40.489   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:54:40.509   760   760 I MotionRecognitionService: Plugged
,08-23 16:54:40.509   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:54:40.509   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:54:40.509   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:54:40.519   760  1784 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,08-23 16:54:40.519   760  1784 D BatteryService: stay LED for fully charged
,08-23 16:54:40.519  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:54:40.519  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:54:40.519  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:54:40.539  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:54:40.539  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:54:40.549  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:54:40.559  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:54:40.559  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:54:41.939   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,08-23 16:54:46.269   760  1601 E Watchdog: !@Sync 43 [08-23 16:54:46.274]
,08-23 16:54:51.999   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,08-23 16:55:02.059   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:55:10.539   760  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:55:12.119   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:55:16.269   760  1601 E Watchdog: !@Sync 44 [08-23 16:55:16.278]
,08-23 16:55:19.309  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:55:19.429  1678  1769 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 106ms lastUpdatedAfter : 180397ms
,08-23 16:55:22.179   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:55:32.229   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:55:40.619   760  1325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:55:42.279   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:55:46.279   760  1601 E Watchdog: !@Sync 45 [08-23 16:55:46.282]
,08-23 16:55:52.339   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:56:02.389   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:56:10.699   760  1784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:56:12.449   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:56:16.279   760  1601 E Watchdog: !@Sync 46 [08-23 16:56:16.287]
,08-23 16:56:19.429  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:56:22.499   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:56:32.549   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:56:40.789   760  1911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:56:40.789   760  1911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:56:40.789   760  1911 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:56:40.799   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:56:40.809   760   760 I MotionRecognitionService: Plugged
,08-23 16:56:40.809   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:56:40.809   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:56:40.819   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:56:40.819   760  1911 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,08-23 16:56:40.819   760  1911 D BatteryService: stay LED for fully charged
,08-23 16:56:40.819  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:56:40.819  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:56:40.819  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:56:40.839  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:56:40.839  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:56:40.849  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:56:40.849  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:56:40.849  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:56:42.609   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:56:46.289   760  1601 E Watchdog: !@Sync 47 [08-23 16:56:46.292]
,08-23 16:56:52.669   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:57:02.719   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:57:10.849   760  1592 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:57:12.779   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:57:16.289   760  1601 E Watchdog: !@Sync 48 [08-23 16:57:16.300]
,08-23 16:57:19.549  1678  1769 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,08-23 16:57:22.829   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:57:32.889   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:57:40.929   760  1910 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:57:42.939   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:57:46.299   760  1601 E Watchdog: !@Sync 49 [08-23 16:57:46.305]
,08-23 16:57:52.999   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:58:00.719   760  1234 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 16:58:00.719   760  1233 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 16:58:00.719   760  1234 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 16:58:03.059   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:58:04.099   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 16:58:04.099   760  1234 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 16:58:04.109   760  1234 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:58:04.109   760  1234 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 16:58:11.009   760  1756 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 16:58:11.019   760  1756 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4363, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-23 16:58:11.019   760  1756 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,08-23 16:58:11.019   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 16:58:11.029   760   760 I MotionRecognitionService: Plugged
,08-23 16:58:11.039   760   760 D MotionRecognitionService:   cableConnection= 1
,08-23 16:58:11.039   760   760 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,08-23 16:58:11.039   760   760 D MotionRecognitionService: skip setTransmitPower. 
,08-23 16:58:11.059   760  1756 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 41ms
,08-23 16:58:11.059   760  1756 D BatteryService: stay LED for fully charged
,08-23 16:58:11.069  1386  1386 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:58:11.069  1386  1386 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-23 16:58:11.069  1386  1386 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 16:58:11.079  2327  2327 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 16:58:11.079  2327  2775 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-23 16:58:11.089  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:58:11.089  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:58:11.089  1386  1386 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-23 16:58:13.119   760  3447 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,08-23 16:58:16.299   760  1601 E Watchdog: !@Sync 50 [08-23 16:58:16.310]
,TIME-OUT KILL (timeout was 1400000ms),08-23 16:58:17.929  2332  2332 E audit   : type=1400 msg=audit(1471964297.919:293): avc:  denied  { execmod } for  pid=7046 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 16:58:17.929  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:58:17.929  2332  2332 E audit   : type=1300 msg=audit(1471964297.919:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4013000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7046 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 16:58:17.939  2332  2332 E audit   : type=1327 msg=audit(1471964297.919:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 16:58:17.939  2332  2332 E audit   : type=1320 msg=audit(1471964297.919:293): 
08-23 16:58:17.979  2332  2332 E audit   : type=1400 msg=audit(1471964297.979:294): avc:  denied  { execmod } for  pid=7046 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 16:58:17.979  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:58:17.979  2332  2332 E audit   : type=1300 msg=audit(1471964297.979:294): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd3000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7046 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 16:58:17.979  2332  2332 E audit   : type=1327 msg=audit(1471964297.979:294): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 16:58:17.979  2332  2332 E audit   : type=1320 msg=audit(1471964297.979:294): 
08-23 16:58:18.019  2332  2332 E audit   : type=1400 msg=audit(1471964298.019:295): avc:  denied  { execmod } for  pid=7046 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-23 16:58:18.019  7046  7046 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 16:58:18.019  2332  2332 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-23 16:58:18.019  2332  2332 E audit   : type=1300 msg=audit(1471964298.019:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fd3000 a1=51000 a2=5 a3=4 items=0 ppid=3575 ppcomm=adbd pid=7046 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-23 16:58:18.019  2332  2332 E audit   : type=1327 msg=audit(1471964298.019:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-23 16:58:18.019  2332  2332 E audit   : type=1320 msg=audit(1471964298.019:295): 
08-23 16:58:18.029  7046  7046 D AndroidRuntime: CheckJNI is OFF
08-23 16:58:18.029  7046  7046 D AndroidRuntime: readGMSProperty: start
08-23 16:58:18.029  7046  7046 D AndroidRuntime: readGMSProperty: already setted!!
08-23 16:58:18.029  7046  7046 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 16:58:18.029  7046  7046 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 16:58:18.029  7046  7046 D AndroidRuntime: readGMSProperty: end
08-23 16:58:18.029  7046  7046 D AndroidRuntime: addProductProperty: start
08-23 16:58:18.029  7046  7046 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 16:58:18.029  7046  7046 W art     : af165000-b208b000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-23 16:58:18.029  7046  7046 W art     : b208b000-b42fa000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-23 16:58:18.029  7046  7046 W art     : b42fa000-b42fb000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-23 16:58:18.029  7046  7046 W art     : b42fb000-b4324000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-23 16:58:18.029  7046  7046 W art     : b4324000-b4772000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-23 16:58:18.029  7046  7046 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b4773000-b477d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-23 16:58:18.029  7046  7046 W art     : b477d000-b477e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-23 16:58:18.029  7046  7046 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-23 16:58:18.029  7046  7046 W art     : b48a1000-b48a4000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-23 16:58:18.029  7046  7046 W art     : b48a4000-b48a5000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-23 16:58:18.029  7046  7046 W art     : b48a5000-b48a6000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-23 16:58:18.029  7046  7046 W art     : b48a6000-b48a7000 r--p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b48a7000-b48c7000 r--s 00000000 00:0b 7179       /dev/__properties__
08-23 16:58:18.029  7046  7046 W art     : b48c7000-b52d8000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-23 16:58:18.029  7046  7046 W art     : b52d8000-b52d9000 ---p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b52d9000-b5322000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-23 16:58:18.029  7046  7046 W art     : b5322000-b5323000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-23 16:58:18.029  7046  7046 W art     : b5323000-b532b000 rw-p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b532b000-b532c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.029  7046  7046 W art     : b532c000-b5361000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-23 16:58:18.029  7046  7046 W art     : b5361000-b5362000 ---p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b5362000-b5363000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-23 16:58:18.029  7046  7046 W art     : b5363000-b5364000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-23 16:58:18.029  7046  7046 W art     : b5364000-b53bc000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-23 16:58:18.029  7046  7046 W art     : b53bc000-b53bd000 ---p 00000000 00:00 0 
08-23 16:58:18.029  7046  7046 W art     : b53bd000-b53be000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-23 16:58:18.039  7046  7046 W art     : b53be000-b53bf000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-23 16:58:18.039  7046  7046 W art     : b53c0000-b53c6000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 16:58:18.039  7046  7046 W art     : b53c6000-b53c7000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 16:58:18.039  7046  7046 W art     : b53c7000-b53c8000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-23 16:58:18.039  7046  7046 W art     : b53c8000-b53ca000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b53cb000-b53d5000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 16:58:18.039  7046  7046 W art     : b53d5000-b53d8000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 16:58:18.039  7046  7046 W art     : b53d8000-b53d9000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-23 16:58:18.039  7046  7046 W art     : b53da000-b53f1000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 16:58:18.039  7046  7046 W art     : b53f1000-b53f2000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b53f2000-b53f3000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 16:58:18.039  7046  7046 W art     : b53f3000-b53f4000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-23 16:58:18.039  7046  7046 W art     : b53f5000-b53ff000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-23 16:58:18.039  7046  7046 W art     : b53ff000-b5400000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-23 16:58:18.039  7046  7046 W art     : b5400000-b5401000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-23 16:58:18.039  7046  7046 W art     : b5401000-b5405000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 16:58:18.039  7046  7046 W art     : b5405000-b5406000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 16:58:18.039  7046  7046 W art     : b5406000-b5407000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-23 16:58:18.039  7046  7046 W art     : b5407000-b541d000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-23 16:58:18.039  7046  7046 W art     : b541d000-b541e000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-23 16:58:18.039  7046  7046 W art     : b541e000-b541f000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-23 16:58:18.039  7046  7046 W art     : b541f000-b542c000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-23 16:58:18.039  7046  7046 W art     : b542c000-b542d000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-23 16:58:18.039  7046  7046 W art     : b542d000-b542e000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-23 16:58:18.039  7046  7046 W art     : b542e000-b548e000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-23 16:58:18.039  7046  7046 W art     : b548e000-b5491000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-23 16:58:18.039  7046  7046 W art     : b5491000-b5495000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5495000-b54f6000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-23 16:58:18.039  7046  7046 W art     : b54f6000-b54f7000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-23 16:58:18.039  7046  7046 W art     : b54f7000-b5546000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-23 16:58:18.039  7046  7046 W art     : b5546000-b5548000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-23 16:58:18.039  7046  7046 W art     : b5548000-b5549000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-23 16:58:18.039  7046  7046 W art     : b5549000-b554a000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b554a000-b5551000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 16:58:18.039  7046  7046 W art     : b5551000-b5552000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 16:58:18.039  7046  7046 W art     : b5552000-b5553000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-23 16:58:18.039  7046  7046 W art     : b5554000-b5557000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 16:58:18.039  7046  7046 W art     : b5557000-b5558000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 16:58:18.039  7046  7046 W art     : b5558000-b5559000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-23 16:58:18.039  7046  7046 W art     : b555a000-b555e000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-23 16:58:18.039  7046  7046 W art     : b555e000-b555f000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b555f000-b5560000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-23 16:58:18.039  7046  7046 W art     : b5560000-b5561000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-23 16:58:18.039  7046  7046 W art     : b5562000-b557f000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 16:58:18.039  7046  7046 W art     : b557f000-b5580000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 16:58:18.039  7046  7046 W art     : b5580000-b5581000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-23 16:58:18.039  7046  7046 W art     : b5582000-b5587000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 16:58:18.039  7046  7046 W art     : b5587000-b5588000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 16:58:18.039  7046  7046 W art     : b5588000-b5589000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-23 16:58:18.039  7046  7046 W art     : b558a000-b55bb000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 16:58:18.039  7046  7046 W art     : b55bb000-b55be000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 16:58:18.039  7046  7046 W art     : b55be000-b55bf000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-23 16:58:18.039  7046  7046 W art     : b55c0000-b55fb000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-23 16:58:18.039  7046  7046 W art     : b55fb000-b55fc000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-23 16:58:18.039  7046  7046 W art     : b55fc000-b55fd000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-23 16:58:18.039  7046  7046 W art     : b55fe000-b5605000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-23 16:58:18.039  7046  7046 W art     : b5605000-b5606000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5606000-b5607000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-23 16:58:18.039  7046  7046 W art     : b5607000-b5608000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-23 16:58:18.039  7046  7046 W art     : b5608000-b5609000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5609000-b5620000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-23 16:58:18.039  7046  7046 W art     : b5620000-b5621000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5621000-b5624000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-23 16:58:18.039  7046  7046 W art     : b5624000-b5625000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-23 16:58:18.039  7046  7046 W art     : b5625000-b5644000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-23 16:58:18.039  7046  7046 W art     : b5644000-b5645000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-23 16:58:18.039  7046  7046 W art     : b5645000-b5646000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-23 16:58:18.039  7046  7046 W art     : b5646000-b5684000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-23 16:58:18.039  7046  7046 W art     : b5684000-b5685000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5685000-b5687000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-23 16:58:18.039  7046  7046 W art     : b5687000-b5688000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-23 16:58:18.039  7046  7046 W art     : b5689000-b5690000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 16:58:18.039  7046  7046 W art     : b5690000-b5691000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 16:58:18.039  7046  7046 W art     : b5691000-b5692000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-23 16:58:18.039  7046  7046 W art     : b5693000-b5696000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 16:58:18.039  7046  7046 W art     : b5696000-b5697000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 16:58:18.039  7046  7046 W art     : b5697000-b5698000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-23 16:58:18.039  7046  7046 W art     : b5698000-b569e000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 16:58:18.039  7046  7046 W art     : b569e000-b569f000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b569f000-b56a0000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 16:58:18.039  7046  7046 W art     : b56a0000-b56a1000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-23 16:58:18.039  7046  7046 W art     : b56a1000-b56aa000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-23 16:58:18.039  7046  7046 W art     : b56aa000-b56ab000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-23 16:58:18.039  7046  7046 W art     : b56ab000-b56ac000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-23 16:58:18.039  7046  7046 W art     : b56ac000-b573d000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 16:58:18.039  7046  7046 W art     : b573d000-b573e000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b573e000-b5749000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 16:58:18.039  7046  7046 W art     : b5749000-b574a000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-23 16:58:18.039  7046  7046 W art     : b574b000-b575d000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-23 16:58:18.039  7046  7046 W art     : b575d000-b575e000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-23 16:58:18.039  7046  7046 W art     : b575e000-b575f000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-23 16:58:18.039  7046  7046 W art     : b5760000-b5765000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-23 16:58:18.039  7046  7046 W art     : b5765000-b5766000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-23 16:58:18.039  7046  7046 W art     : b5766000-b5767000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-23 16:58:18.039  7046  7046 W art     : b5768000-b57d5000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-23 16:58:18.039  7046  7046 W art     : b57d5000-b57d6000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b57d6000-b57d8000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-23 16:58:18.039  7046  7046 W art     : b57d8000-b57d9000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-23 16:58:18.039  7046  7046 W art     : b57d9000-b57da000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b57da000-b57e1000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 16:58:18.039  7046  7046 W art     : b57e1000-b57e2000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 16:58:18.039  7046  7046 W art     : b57e2000-b57e3000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-23 16:58:18.039  7046  7046 W art     : b57e4000-b5864000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 16:58:18.039  7046  7046 W art     : b5864000-b5865000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5865000-b5866000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 16:58:18.039  7046  7046 W art     : b5866000-b5867000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-23 16:58:18.039  7046  7046 W art     : b5867000-b587e000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b587e000-b58b5000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-23 16:58:18.039  7046  7046 W art     : ib/libqc-opt.so
08-23 16:58:18.039  7046  7046 W art     : b58b5000-b58b6000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 16:58:18.039  7046  7046 W art     : b58b6000-b58b7000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-23 16:58:18.039  7046  7046 W art     : b58b7000-b58d3000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 16:58:18.039  7046  7046 W art     : b58d3000-b58d4000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 16:58:18.039  7046  7046 W art     : b58d4000-b58d5000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-23 16:58:18.039  7046  7046 W art     : b58d6000-b5937000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-23 16:58:18.039  7046  7046 W art     : b5937000-b5939000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-23 16:58:18.039  7046  7046 W art     : b5939000-b593a000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-23 16:58:18.039  7046  7046 W art     : b593b000-b5962000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-23 16:58:18.039  7046  7046 W art     : b5962000-b5963000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5963000-b5964000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-23 16:58:18.039  7046  7046 W art     : b5964000-b5965000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-23 16:58:18.039  7046  7046 W art     : b5966000-b596e000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 16:58:18.039  7046  7046 W art     : b596e000-b5970000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 16:58:18.039  7046  7046 W art     : b5970000-b5971000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-23 16:58:18.039  7046  7046 W art     : b5972000-b5975000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-23 16:58:18.039  7046  7046 W art     : b5975000-b5976000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-23 16:58:18.039  7046  7046 W art     : b5976000-b5977000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-23 16:58:18.039  7046  7046 W art     : b5977000-b597b000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-23 16:58:18.039  7046  7046 W art     : b597b000-b597c000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b597c000-b597d000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-23 16:58:18.039  7046  7046 W art     : b597d000-b597e000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-23 16:58:18.039  7046  7046 W art     : b597e000-b598e000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-23 16:58:18.039  7046  7046 W art     : b598e000-b598f000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-23 16:58:18.039  7046  7046 W art     : b598f000-b5990000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-23 16:58:18.039  7046  7046 W art     : b5990000-b59d6000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b59d6000-b59df000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-23 16:58:18.039  7046  7046 W art     : b59df000-b59e0000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-23 16:58:18.039  7046  7046 W art     : b59e0000-b59e1000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-23 16:58:18.039  7046  7046 W art     : b59e2000-b59e7000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-23 16:58:18.039  7046  7046 W art     : b59e7000-b59e8000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-23 16:58:18.039  7046  7046 W art     : b59e8000-b59e9000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-23 16:58:18.039  7046  7046 W art     : b59e9000-b59ec000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 16:58:18.039  7046  7046 W art     : b59ec000-b59ed000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b59ed000-b59ee000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 16:58:18.039  7046  7046 W art     : b59ee000-b59ef000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-23 16:58:18.039  7046  7046 W art     : b59f0000-b5a08000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 16:58:18.039  7046  7046 W art     : b5a08000-b5a09000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5a09000-b5a0a000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 16:58:18.039  7046  7046 W art     : b5a0a000-b5a0b000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-23 16:58:18.039  7046  7046 W art     : b5a0b000-b5a0c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:58:18.039  7046  7046 W art     : b5a0c000-b5ba6000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-23 16:58:18.039  7046  7046 W art     : b5ba6000-b5ba7000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5ba7000-b5bb4000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-23 16:58:18.039  7046  7046 W art     : b5bb4000-b5bb5000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-23 16:58:18.039  7046  7046 W art     : b5bb5000-b5bb9000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-23 16:58:18.039  7046  7046 W art     : b5bb9000-b5bba000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5bba000-b5bbb000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-23 16:58:18.039  7046  7046 W art     : b5bbb000-b5bbc000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-23 16:58:18.039  7046  7046 W art     : b5bbc000-b5bcf000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-23 16:58:18.039  7046  7046 W art     : b5bcf000-b5bd0000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-23 16:58:18.039  7046  7046 W art     : b5bd0000-b5bd1000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-23 16:58:18.039  7046  7046 W art     : b5bd2000-b5c1d000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-23 16:58:18.039  7046  7046 W art     : b5c1d000-b5c1e000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-23 16:58:18.039  7046  7046 W art     : b5c1e000-b5c1f000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-23 16:58:18.039  7046  7046 W art     : b5c1f000-b5c21000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5c22000-b5c33000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 16:58:18.039  7046  7046 W art     : b5c33000-b5c34000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5c34000-b5c35000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 16:58:18.039  7046  7046 W art     : b5c35000-b5c36000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-23 16:58:18.039  7046  7046 W art     : b5c36000-b5c37000 r--p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5c37000-b5c41000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-23 16:58:18.039  7046  7046 W art     : b5c41000-b5c43000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-23 16:58:18.039  7046  7046 W art     : b5c43000-b5c44000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-23 16:58:18.039  7046  7046 W art     : b5c44000-b5c5d000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-23 16:58:18.039  7046  7046 W art     : b5c5d000-b5c5e000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-23 16:58:18.039  7046  7046 W art     : b5c5e000-b5c61000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-23 16:58:18.039  7046  7046 W art     : b5c61000-b5c65000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5c65000-b5cd9000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-23 16:58:18.039  7046  7046 W art     : b5cd9000-b5cda000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5cda000-b5cdd000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-23 16:58:18.039  7046  7046 W art     : b5cdd000-b5cde000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-23 16:58:18.039  7046  7046 W art     : b5cde000-b5cdf000 r--p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5cdf000-b5ce2000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-23 16:58:18.039  7046  7046 W art     : b5ce2000-b5ce3000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-23 16:58:18.039  7046  7046 W art     : b5ce3000-b5ce4000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-23 16:58:18.039  7046  7046 W art     : b5ce4000-b5ce5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5ce5000-b5cea000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 16:58:18.039  7046  7046 W art     : b5cea000-b5ceb000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 16:58:18.039  7046  7046 W art     : b5ceb000-b5cec000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-23 16:58:18.039  7046  7046 W art     : b5cec000-b5ced000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5ced000-b5cf0000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 16:58:18.039  7046  7046 W art     : b5cf0000-b5cf1000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 16:58:18.039  7046  7046 W art     : b5cf1000-b5cf2000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-23 16:58:18.039  7046  7046 W art     : b5cf2000-b5cf3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5cf3000-b5cf7000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-23 16:58:18.039  7046  7046 W art     : b5cf7000-b5cf8000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-23 16:58:18.039  7046  7046 W art     : b5cf8000-b5cf9000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-23 16:58:18.039  7046  7046 W art     : b5cf9000-b5cfa000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:58:18.039  7046  7046 W art     : b5cfa000-b5cfe000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 16:58:18.039  7046  7046 W art     : b5cfe000-b5cff000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 16:58:18.039  7046  7046 W art     : b5cff000-b5d00000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-23 16:58:18.039  7046  7046 W art     : b5d00000-b5d01000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5d01000-b5d0f000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-23 16:58:18.039  7046  7046 W art     : b5d0f000-b5d10000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b5d10000-b5d11000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-23 16:58:18.039  7046  7046 W art     : b5d11000-b5d12000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-23 16:58:18.039  7046  7046 W art     : b5d12000-b5d1c000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 16:58:18.039  7046  7046 W art     : b5d1c000-b5d1f000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 16:58:18.039  7046  7046 W art     : b5d1f000-b5d20000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-23 16:58:18.039  7046  7046 W art     : b5d20000-b5d21000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5d21000-b5d2b000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-23 16:58:18.039  7046  7046 W art     : b5d2b000-b5d2e000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-23 16:58:18.039  7046  7046 W art     : b5d2e000-b5d2f000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-23 16:58:18.039  7046  7046 W art     : b5d2f000-b5d33000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-23 16:58:18.039  7046  7046 W art     : b5d33000-b5d34000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-23 16:58:18.039  7046  7046 W art     : b5d34000-b5d35000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-23 16:58:18.039  7046  7046 W art     : b5d35000-b5d36000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b5d36000-b5d43000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-23 16:58:18.039  7046  7046 W art     : b5d43000-b5d45000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-23 16:58:18.039  7046  7046 W art     : b5d45000-b5d46000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-23 16:58:18.039  7046  7046 W art     : b5d46000-b6158000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-23 16:58:18.039  7046  7046 W art     : b6158000-b6159000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6159000-b6162000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-23 16:58:18.039  7046  7046 W art     : b6162000-b6166000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-23 16:58:18.039  7046  7046 W art     : b6166000-b6167000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6167000-b616e000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-23 16:58:18.039  7046  7046 W art     : b616e000-b616f000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-23 16:58:18.039  7046  7046 W art     : b616f000-b6170000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-23 16:58:18.039  7046  7046 W art     : b6170000-b6171000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6171000-b618c000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-23 16:58:18.039  7046  7046 W art     : b618c000-b618d000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-23 16:58:18.039  7046  7046 W art     : b618d000-b618e000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-23 16:58:18.039  7046  7046 W art     : b618e000-b618f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b618f000-b61db000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 16:58:18.039  7046  7046 W art     : b61db000-b61dc000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b61dc000-b61dd000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 16:58:18.039  7046  7046 W art     : b61dd000-b61de000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-23 16:58:18.039  7046  7046 W art     : b61de000-b61df000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b61df000-b61e3000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-23 16:58:18.039  7046  7046 W art     : b61e3000-b61e4000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b61e4000-b61e5000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-23 16:58:18.039  7046  7046 W art     : b61e5000-b61e6000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-23 16:58:18.039  7046  7046 W art     : b61e6000-b621e000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-23 16:58:18.039  7046  7046 W art     : b621e000-b621f000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-23 16:58:18.039  7046  7046 W art     : b621f000-b6220000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-23 16:58:18.039  7046  7046 W art     : b6220000-b6221000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6221000-b62bf000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-23 16:58:18.039  7046  7046 W art     : b62bf000-b62c0000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b62c0000-b62de000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-23 16:58:18.039  7046  7046 W art     : b62de000-b62df000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-23 16:58:18.039  7046  7046 W art     : b62df000-b6452000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-23 16:58:18.039  7046  7046 W art     : b6452000-b645d000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-23 16:58:18.039  7046  7046 W art     : b645d000-b645e000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-23 16:58:18.039  7046  7046 W art     : b645e000-b6575000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-23 16:58:18.039  7046  7046 W art     : b6575000-b6580000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-23 16:58:18.039  7046  7046 W art     : b6580000-b6581000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-23 16:58:18.039  7046  7046 W art     : b6581000-b6585000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6585000-b65a9000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-23 16:58:18.039  7046  7046 W art     : b65a9000-b65ab000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-23 16:58:18.039  7046  7046 W art     : b65ab000-b65ac000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-23 16:58:18.039  7046  7046 W art     : b65ac000-b6652000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-23 16:58:18.039  7046  7046 W art     : b6652000-b665f000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-23 16:58:18.039  7046  7046 W art     : b665f000-b6660000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-23 16:58:18.039  7046  7046 W art     : b6660000-b6661000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6661000-b66b4000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-23 16:58:18.039  7046  7046 W art     : b66b4000-b66b5000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b66b5000-b66b6000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-23 16:58:18.039  7046  7046 W art     : b66b6000-b66b7000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-23 16:58:18.039  7046  7046 W art     : b66b7000-b66bc000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b66bc000-b66ce000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-23 16:58:18.039  7046  7046 W art     : b66ce000-b66cf000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b66cf000-b66d0000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-23 16:58:18.039  7046  7046 W art     : b66d0000-b66d1000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-23 16:58:18.039  7046  7046 W art     : b66d1000-b66d8000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 16:58:18.039  7046  7046 W art     : b66d8000-b66d9000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 16:58:18.039  7046  7046 W art     : b66d9000-b66da000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-23 16:58:18.039  7046  7046 W art     : b66da000-b66db000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b66db000-b66de000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-23 16:58:18.039  7046  7046 W art     : b66de000-b66df000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-23 16:58:18.039  7046  7046 W art     : b66df000-b66e0000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-23 16:58:18.039  7046  7046 W art     : b66e0000-b66e4000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-23 16:58:18.039  7046  7046 W art     : b66e4000-b66e5000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-23 16:58:18.039  7046  7046 W art     : b66e5000-b66e6000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-23 16:58:18.039  7046  7046 W art     : b66e6000-b66f4000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-23 16:58:18.039  7046  7046 W art     : b66f4000-b66f5000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b66f5000-b66f6000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-23 16:58:18.039  7046  7046 W art     : b66f6000-b66f7000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-23 16:58:18.039  7046  7046 W art     : b66f7000-b6700000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 16:58:18.039  7046  7046 W art     : b6700000-b6701000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 16:58:18.039  7046  7046 W art     : b6701000-b6702000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-23 16:58:18.039  7046  7046 W art     : b6702000-b6768000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-23 16:58:18.039  7046  7046 W art     : b6768000-b6769000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6769000-b676b000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-23 16:58:18.039  7046  7046 W art     : b676b000-b6774000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-23 16:58:18.039  7046  7046 W art     : b6774000-b6777000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6777000-b680e000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-23 16:58:18.039  7046  7046 W art     : b680e000-b6810000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-23 16:58:18.039  7046  7046 W art     : b6810000-b6811000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-23 16:58:18.039  7046  7046 W art     : b6811000-b6812000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6812000-b6b33000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-23 16:58:18.039  7046  7046 W art     : b6b33000-b6b34000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6b34000-b6b4f000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-23 16:58:18.039  7046  7046 W art     : b6b4f000-b6b53000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-23 16:58:18.039  7046  7046 W art     : b6b53000-b6b58000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6b58000-b6b60000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 16:58:18.039  7046  7046 W art     : b6b60000-b6b61000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 16:58:18.039  7046  7046 W art     : b6b61000-b6b62000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-23 16:58:18.039  7046  7046 W art     : b6b62000-b6b90000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-23 16:58:18.039  7046  7046 W art     : b6b90000-b6b91000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6b91000-b6b98000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-23 16:58:18.039  7046  7046 W art     : b6b98000-b6b99000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-23 16:58:18.039  7046  7046 W art     : b6b99000-b6bdf000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-23 16:58:18.039  7046  7046 W art     : b6bdf000-b6be0000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6be0000-b6be3000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-23 16:58:18.039  7046  7046 W art     : b6be3000-b6be4000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-23 16:58:18.039  7046  7046 W art     : b6be4000-b6bff000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-23 16:58:18.039  7046  7046 W art     : b6bff000-b6c03000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-23 16:58:18.039  7046  7046 W art     : b6c03000-b6c04000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-23 16:58:18.039  7046  7046 W art     : b6c04000-b6c51000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-23 16:58:18.039  7046  7046 W art     : b6c51000-b6c52000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6c52000-b6c5e000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-23 16:58:18.039  7046  7046 W art     : b6c5e000-b6c5f000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-23 16:58:18.039  7046  7046 W art     : b6c5f000-b6c6c000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-23 16:58:18.039  7046  7046 W art     : b6c6c000-b6c6d000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6c6d000-b6c6e000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-23 16:58:18.039  7046  7046 W art     : b6c6e000-b6c6f000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-23 16:58:18.039  7046  7046 W art     : b6c6f000-b6c77000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-23 16:58:18.039  7046  7046 W art     : b6c77000-b6c78000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6c78000-b6c79000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-23 16:58:18.039  7046  7046 W art     : b6c79000-b6c7a000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-23 16:58:18.039  7046  7046 W art     : b6c7a000-b6c81000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-23 16:58:18.039  7046  7046 W art     : b6c81000-b6c82000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-23 16:58:18.039  7046  7046 W art     : b6c82000-b6c83000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-23 16:58:18.039  7046  7046 W art     : b6c83000-b6c97000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-23 16:58:18.039  7046  7046 W art     : b6c97000-b6c99000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-23 16:58:18.039  7046  7046 W art     : b6c99000-b6c9a000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-23 16:58:18.039  7046  7046 W art     : b6c9a000-b6cc2000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-23 16:58:18.039  7046  7046 W art     : b6cc2000-b6cc4000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-23 16:58:18.039  7046  7046 W art     : b6cc4000-b6cc5000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-23 16:58:18.039  7046  7046 W art     : b6cc5000-b6cc8000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-23 16:58:18.039  7046  7046 W art     : b6cc8000-b6cc9000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-23 16:58:18.039  7046  7046 W art     : b6cc9000-b6cca000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-23 16:58:18.039  7046  7046 W art     : b6cca000-b6cd3000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-23 16:58:18.039  7046  7046 W art     : b6cd3000-b6cd4000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-23 16:58:18.039  7046  7046 W art     : b6cd4000-b6cd5000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-23 16:58:18.039  7046  7046 W art     : b6cd5000-b6cf5000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-23 16:58:18.039  7046  7046 W art     : b6cf5000-b6cf6000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-23 16:58:18.039  7046  7046 W art     : b6cf6000-b6cf7000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-23 16:58:18.039  7046  7046 W art     : b6cf7000-b6d6a000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-23 16:58:18.039  7046  7046 W art     : b6d6a000-b6d6e000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-23 16:58:18.039  7046  7046 W art     : b6d6e000-b6d71000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-23 16:58:18.039  7046  7046 W art     : b6d71000-b6d7b000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6d7b000-b6e03000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-23 16:58:18.039  7046  7046 W art     : b6e03000-b6e04000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6e04000-b6e08000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-23 16:58:18.039  7046  7046 W art     : b6e08000-b6e09000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-23 16:58:18.039  7046  7046 W art     : b6e09000-b6e0a000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6e0a000-b6e33000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-23 16:58:18.039  7046  7046 W art     : b6e33000-b6e34000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6e34000-b6e37000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-23 16:58:18.039  7046  7046 W art     : b6e37000-b6e38000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-23 16:58:18.039  7046  7046 W art     : b6e38000-b6f12000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 16:58:18.039  7046  7046 W art     : b6f12000-b6f19000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 16:58:18.039  7046  7046 W art     : b6f19000-b6f21000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-23 16:58:18.039  7046  7046 W art     : b6f21000-b6f22000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6f22000-b6f23000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:58:18.039  7046  7046 W art     : b6f23000-b6f24000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-23 16:58:18.039  7046  7046 W art     : b6f24000-b6f25000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6f25000-b6f28000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6f28000-b6f4d000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-23 16:58:18.039  7046  7046 W art     : b6f4d000-b6f4e000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6f4e000-b6f55000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-23 16:58:18.039  7046  7046 W art     : b6f55000-b6f56000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-23 16:58:18.039  7046  7046 W art     : b6f56000-b6f5d000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-23 16:58:18.039  7046  7046 W art     : b6f5d000-b6f5e000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-23 16:58:18.039  7046  7046 W art     : b6f5e000-b6f5f000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-23 16:58:18.039  7046  7046 W art     : b6f5f000-b6f60000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6f60000-b6f78000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-23 16:58:18.039  7046  7046 W art     : b6f78000-b6f79000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6f79000-b6f7a000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-23 16:58:18.039  7046  7046 W art     : b6f7a000-b6f7b000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-23 16:58:18.039  7046  7046 W art     : b6f7b000-b6f89000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-23 16:58:18.039  7046  7046 W art     : b6f89000-b6f8a000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6f8a000-b6f8b000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-23 16:58:18.039  7046  7046 W art     : b6f8b000-b6f8c000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-23 16:58:18.039  7046  7046 W art     : b6f8c000-b6f8d000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:58:18.039  7046  7046 W art     : b6f8d000-b6f8f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6f8f000-b6f90000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6f90000-b6f91000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-23 16:58:18.039  7046  7046 W art     : b6f91000-b6f92000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-23 16:58:18.039  7046  7046 W art     : b6f92000-b6f93000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-23 16:58:18.039  7046  7046 W art     : b6f93000-b6fb3000 r--s 00000000 00:0b 7179       /dev/__properties__
08-23 16:58:18.039  7046  7046 W art     : b6fb3000-b6fb4000 r--p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6fb4000-b6fb5000 ---p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6fb5000-b6fb7000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-23 16:58:18.039  7046  7046 W art     : b6fb7000-b6fb8000 r-xp 00000000 00:00 0          [sigpage]
08-23 16:58:18.039  7046  7046 W art     : b6fb8000-b6fd3000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-23 16:58:18.039  7046  7046 W art     : b6fd3000-b6fd4000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-23 16:58:18.039  7046  7046 W art     : b6fd4000-b6fd6000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-23 16:58:18.039  7046  7046 W art     : b6fd6000-b6fd8000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : b6fd8000-b6fdd000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-23 16:58:18.039  7046  7046 W art     : b6fdd000-b6fde000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-23 16:58:18.039  7046  7046 W art     : b6fde000-b6fdf000 rw-p 00000000 00:00 0 
08-23 16:58:18.039  7046  7046 W art     : be951000-be972000 rw-p 00000000 00:00 0          [stack]
08-23 16:58:18.039  7046  7046 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-23 16:58:18.089  7046  7046 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 16:58:18.139  7046  7046 I Radio-JNI: register_android_hardware_Radio DONE
08-23 16:58:18.149  7046  7046 E AffinityControl: AffinityControl: registerfunction enter
08-23 16:58:18.169  7046  7046 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 16:58:18.179   760  2423 D PackageManager: START PACKAGE DELETE: observer{251111368}
08-23 16:58:18.179   760  2423 D PackageManager: pkg{<packageName>}
08-23 16:58:18.179   760  2423 D PackageManager: user{0}
08-23 16:58:18.179   760  2423 D PackageManager: caller{2000}
08-23 16:58:18.179   760  2423 D PackageManager: flags{2}
08-23 16:58:18.179   760  2423 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 16:58:18.179   760  2423 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 16:58:18.179   760  2423 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 16:58:18.179   760  2423 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 16:58:18.179   760  2423 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 16:58:18.179   760   919 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 16:58:18.179   760   919 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 16:58:18.179   760   919 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 16:58:18.179   760   919 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 16:58:18.179   760   919 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-23 16:58:18.189   760   919 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 16:58:18.189   760   919 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-23 16:58:18.189   760   919 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-23 16:58:18.189   760   844 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-23 16:58:18.189   760   844 I ActivityManager: Killing 6531:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
08-23 16:58:18.189   760   844 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
08-23 16:58:18.199   760   919 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-23 16:58:18.199   760   919 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
08-23 16:58:18.199   760   844 D ActivityManager: mDVFSHelper.acquire()
08-23 16:58:18.209   760   891 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 16:58:18.209   760   891 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-23 16:58:18.209   760   891 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
08-23 16:58:18.209   760   891 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
08-23 16:58:18.209   760   891 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
08-23 16:58:18.209   760   891 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
08-23 16:58:18.209   760   891 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:58:18.209   760   891 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-23 16:58:18.209   760   891 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 16:58:18.209   760   891 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 16:58:18.209   760   891 D SecWifiDisplayUtil: Metadata value : none
08-23 16:58:18.209   760   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{5d9a7e0 V.E...... R.....ID 0,0-0,0}
08-23 16:58:18.209   760   891 W WindowManager: view not successfully added to wm, removing view
08-23 16:58:18.209   760   844 I ActivityManager: Start proc 7066:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-23 16:58:18.209   760   891 D ViewRootImpl: #3 mView = null
08-23 16:58:18.209   760   844 I ActivityManager: Killing 6972:com.sec.android.daemonapp/u0a181 (adj 5): SSR - service for lastStateTime 696s, lastActivityTime 696s
08-23 16:58:18.209   760   844 I ActivityManager: Killing 6959:com.sec.android.pagebuddynotisvc/u0a26 (adj 5): SSR - service for lastStateTime 706s, lastActivityTime 706s
08-23 16:58:18.209   760   844 I ActivityManager: Killing 6927:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 716s, lastActivityTime 716s
08-23 16:58:18.219   760   844 I ActivityManager: Killing 6881:com.sec.android.app.shealth:remote/u0a34 (adj 8): SSR - service for lastStateTime 717s, lastActivityTime 716s
08-23 16:58:18.219  7066  7066 E Zygote  : v2
08-23 16:58:18.219  7066  7066 I libpersona: KNOX_SDCARD checking this for 10004
08-23 16:58:18.219  7066  7066 I libpersona: KNOX_SDCARD not a persona
08-23 16:58:18.219  7066  7066 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-23 16:58:18.219  7066  7066 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-23 16:58:18.219  7066  7066 E Zygote  : accessInfo : 0
08-23 16:58:18.219  7066  7066 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-23 16:58:18.219   760   844 I ActivityManager:   Force finishing activity ActivityRecord{224a1d6 u0 com.test.thalitest/.MainActivity t169}
08-23 16:58:18.239   760   919 D AASAinstall: there is not AASApackages.xml file
08-23 16:58:18.239   293   293 I ServiceManager: service 'AtCmdFwd' died
08-23 16:58:18.239   383  4701 I Atfwd_Sendcmd: AtCmdFwd : binderDied
08-23 16:58:18.239   383  4701 I ServiceManager: Waiting for service AtCmdFwd...
08-23 16:58:18.249  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 16:58:18.249  7066  7066 D ActivityThread: Added TimaKeyStore provider
08-23 16:58:18.279   760  2422 D GraphicsStats: Buffer count: 5
08-23 16:58:18.279   760  2422 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@4deb15e)
08-23 16:58:18.279   760  1591 I WindowState: WIN DEATH: Window{6f5c12f u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 16:58:18.279   294  1828 I SurfaceFlinger: id=24 Removed NainActivit (6/8)
08-23 16:58:18.279   294  1828 I SurfaceFlinger: id=24 Removed NainActivit (-2/8)
08-23 16:58:18.279   294  1828 I SurfaceFlinger: id=24 Removed NainActivit (-2/8)
08-23 16:58:18.279   760  1337 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 16:58:18.279   760  1337 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 16:58:18.289   760  1337 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 16:58:18.289   760  1591 D InputDispatcher: Focus left window: 6531
08-23 16:58:18.299   294   294 D libEGL  : eglTerminate EGLDisplay = 0xbebf33a4
08-23 16:58:18.539   760   919 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
08-23 16:58:18.649   760   919 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
08-23 16:58:18.669   335   335 W keystore: ENTER clear_uid from uid 1000 for 10004
08-23 16:58:18.669   760   919 I art     : Starting a blocking GC Explicit
08-23 16:58:18.679   760   844 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
08-23 16:58:18.679   760  1784 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
08-23 16:58:18.679   760  1784 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
08-23 16:58:18.679   760  1784 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
08-23 16:58:18.699   760  1256 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
08-23 16:58:18.699   760  1256 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
08-23 16:58:18.699   760  1256 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 10987ms
08-23 16:58:18.699  1742  1742 D Launcher: onRestart, Launcher: 1371841
08-23 16:58:18.699   760  1592 I ActivityManager: Killing 4795:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
08-23 16:58:18.709   760  1491 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
08-23 16:58:18.709   760  1491 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
08-23 16:58:18.709   760  1491 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20974ms
08-23 16:58:18.709   760   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:760 uid:1000
08-23 16:58:18.709   760   891 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 16:58:18.709   760   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:760 uid:1000
08-23 16:58:18.709   760   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-23 16:58:18.719   760   844 D InputDispatcher: Focused application released
08-23 16:58:18.729  1742  1742 D Launcher: onStart, Launcher: 1371841
08-23 16:58:18.729  1742  1742 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
08-23 16:58:18.729  4526  4526 V ActivityThread: updateVisibility : ActivityRecord{e5d47c4 token=android.os.BinderProxy@1f8200b {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
08-23 16:58:18.729  1742  1742 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-23 16:58:18.729  1742  1742 D Launcher.HomeView: onStart
08-23 16:58:18.729   760  2421 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
08-23 16:58:18.729   760  2421 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
08-23 16:58:18.729   760  2421 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 30952ms
08-23 16:58:18.729   294   294 I SurfaceFlinger: id=25 createSurf (1146x1992),1 flag=4, YUIInstallC
08-23 16:58:18.739  1742  1742 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
08-23 16:58:18.739  1742  1742 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
08-23 16:58:18.739   760  2419 V WindowOrientationListener: setCurrentAppOrientation :1
08-23 16:58:18.739   760  2419 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-,1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-23 16:58:18.739  1742  1742 V ActivityThread: updateVisibility : ActivityRecord{40a651 token=android.os.BinderProxy@2524fcb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-23 16:58:18.739  2183  2261 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
08-23 16:58:18.749   760  2419 D InputDispatcher: Focus entered window: 4526
08-23 16:58:18.749   760   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:760 uid:1000

```
