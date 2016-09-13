#### Test 836273379690449_thali01_samsung-SM-G900F Logs


```
--------- beginning of system
,09-13 14:17:57.907   765  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
09-13 14:17:57.917   765  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
09-13 14:17:58.037   765  3518 D SSRM:n  : SIOP:: AP = 410, PST = 479, CUR = 300, LCD = 0
09-13 14:17:58.076   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
09-13 14:17:58.386   765  1237 V AlarmManager: Expired Alarm result :4
--------- beginning of main
09-13 14:17:58.476  6038  6079 I Finsky  : [860] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
09-13 14:17:58.476   765  2530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 14:17:58.476   765  2530 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4351, temperature: 331, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
09-13 14:17:58.476   765  2530 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 14:17:58.486   765  2530 D BatteryService: stay LED for charging
09-13 14:17:58.486   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 14:17:58.496   765   765 I MotionRecognitionService: Plugged
09-13 14:17:58.496   765   765 D MotionRecognitionService:   cableConnection= 1
09-13 14:17:58.496   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 14:17:58.496   765   765 D MotionRecognitionService: skip setTransmitPower. 
09-13 14:17:58.506  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:17:58.506  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:17:58.506  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 14:17:58.526  2438  2438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 14:17:58.536  2438  2893 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 14:17:58.546  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 14:17:58.546  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 14:17:58.546  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 14:17:58.846  6038  6079 I Finsky  : [860] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
09-13 14:17:58.856  6038  6038 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
09-13 14:17:59.206   765  1584 E Watchdog: !@Sync 3 [09-13 14:17:59.216]
09-13 14:17:59.276  2446  2446 E audit   : type=1400 msg=audit(1473769079.266:284): avc:  denied  { execmod } for  pid=6619 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 14:17:59.276  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 14:17:59.286  2446  2446 E audit   : type=1300 msg=audit(1473769079.266:284): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f58000 a1=51000 a2=5 a3=4 items=0 ppid=3670 ppcomm=adbd pid=6619 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 14:17:59.286  2446  2446 E audit   : type=1327 msg=audit(1473769079.266:284): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 14:17:59.286  2446  2446 E audit   : type=1320 msg=audit(1473769079.266:284): 
09-13 14:17:59.356  2446  2446 E audit   : type=1400 msg=audit(1473769079.346:285): avc:  denied  { execmod } for  pid=6619 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 14:17:59.356  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 14:17:59.356  2446  2446 E audit   : type=1300 msg=audit(1473769079.346:285): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f18000 a1=51000 a2=5 a3=4 items=0 ppid=3670 ppcomm=adbd pid=6619 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 14:17:59.356  2446  2446 E audit   : type=1327 msg=audit(1473769079.346:285): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 14:17:59.356  2446  2446 E audit   : type=1320 msg=audit(1473769079.346:285): 
09-13 14:17:59.416  2446  2446 E audit   : type=1400 msg=audit(1473769079.416:286): avc:  denied  { execmod } for  pid=6619 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 14:17:59.416  6619  6619 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 14:17:59.416  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 14:17:59.426  2446  2446 E audit   : type=1300 msg=audit(1473769079.416:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f18000 a1=51000 a2=5 a3=4 items=0 ppid=3670 ppcomm=adbd pid=6619 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
09-13 14:17:59.426  2446  2446 E audit   : type=1327 msg=audit(1473769079.416:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
09-13 14:17:59.426  6619  6619 D AndroidRuntime: CheckJNI is OFF
09-13 14:17:59.426  6619  6619 D AndroidRuntime: readGMSProperty: start
09-13 14:17:59.426  6619  6619 D AndroidRuntime: readGMSProperty: already setted!!
09-13 14:17:59.426  6619  6619 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 14:17:59.426  6619  6619 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 14:17:59.426  6619  6619 D AndroidRuntime: readGMSProperty: end
09-13 14:17:59.426  6619  6619 D AndroidRuntime: addProductProperty: start
09-13 14:17:59.426  2446  2446 E audit   : type=1320 msg=audit(1473769079.416:286): 
09-13 14:17:59.446  6619  6619 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 14:17:59.446  6619  6619 W art     : aed7f000-b1ca5000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
09-13 14:17:59.446  6619  6619 W art     : b1ca5000-b3f14000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
09-13 14:17:59.446  6619  6619 W art     : b3f14000-b3f15000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
09-13 14:17:59.446  6619  6619 W art     : b3f15000-b3f16000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.446  6619  6619 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 946        /system/lib/libart.so
09-13 14:17:59.446  6619  6619 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 946        /system/lib/libart.so
09-13 14:17:59.446  6619  6619 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 946        /system/lib/libart.so
09-13 14:17:59.446  6619  6619 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
09-13 14:17:59.446  6619  6619 W art     : b47c1000-b47ea000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 14:17:59.446  6619  6619 W art     : b47ea000-b47ed000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
09-13 14:17:59.446  6619  6619 W art     : b47ed000-b47ee000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
09-13 14:17:59.446  6619  6619 W art     : b47ee000-b47ef000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
09-13 14:17:59.446  6619  6619 W art     : b47ef000-b47f0000 r--p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b47f0000-b4810000 r--s 00000000 00:0b 6572       /dev/__properties__
09-13 14:17:59.446  6619  6619 W art     : b4810000-b5221000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
09-13 14:17:59.446  6619  6619 W art     : b5221000-b5222000 ---p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b5222000-b526b000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
09-13 14:17:59.446  6619  6619 W art     : b526b000-b526c000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
09-13 14:17:59.446  6619  6619 W art     : b526c000-b5274000 rw-p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b5274000-b52a9000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
09-13 14:17:59.446  6619  6619 W art     : b52a9000-b52aa000 ---p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b52aa000-b52ab000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
09-13 14:17:59.446  6619  6619 W art     : b52ab000-b52ac000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
09-13 14:17:59.446  6619  6619 W art     : b52ac000-b5304000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
09-13 14:17:59.446  6619  6619 W art     : b5304000-b5305000 ---p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b5305000-b5306000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
09-13 14:17:59.446  6619  6619 W art     : b5306000-b5307000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
09-13 14:17:59.446  6619  6619 W art     : b5308000-b530e000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
09-13 14:17:59.446  6619  6619 W art     : AD_v01009.so
09-13 14:17:59.446  6619  6619 W art     : b530e000-b530f000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 14:17:59.446  6619  6619 W art     : b530f000-b5310000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 14:17:59.446  6619  6619 W art     : b5310000-b5312000 rw-p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b5313000-b531d000 r-xp 00000000 b3:17 1088 
09-13 14:17:59.446  6619  6619 W art     :       /system/lib/libcommon_time_client.so
09-13 14:17:59.446  6619  6619 W art     : b531d000-b5320000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 14:17:59.446  6619  6619 W art     : b5320000-b5321000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 14:17:59.446  6619  6619 W art     : b5322000-b5339000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 14:17:59.446  6619  6619 W art     : b5339000-b533a000 ---p 00000000 00:00 0 
09-13 14:17:59.446  6619  6619 W art     : b533a000-b533b000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 14:17:59.446  6619  6619 W art     : b533b000-b533c000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 14:17:59.446  6619  6619 W art     : b533d000-b5347000 r-xp 00000000 b3:17 2671   
09-13 14:17:59.456  6619  6619 W art     :     /system/lib/libsec_km.so
09-13 14:17:59.456  6619  6619 W art     : b5347000-b5348000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
09-13 14:17:59.456  6619  6619 W art     : b5348000-b5349000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
09-13 14:17:59.456  6619  6619 W art     : b5349000-b534d000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 14:17:59.456  6619  6619 W art     : b534d000-b534e000 r--p 00003000 b
09-13 14:17:59.456  6619  6619 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
09-13 14:17:59.456  6619  6619 W art     : b534e000-b534f000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 14:17:59.456  6619  6619 W art     : b534f000-b5365000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
09-13 14:17:59.456  6619  6619 W art     : b5365000-b5366000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
09-13 14:17:59.456  6619  6619 W art     : b5366000-b5367000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
09-13 14:17:59.456  6619  6619 W art     : b5367000-b5374000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
09-13 14:17:59.456  6619  6619 W art     : b5374000-b5375000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
09-13 14:17:59.456  6619  6619 W art     : b5375000-b5376000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
09-13 14:17:59.456  6619  6619 W art     : b5376000-b53d6000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
09-13 14:17:59.456  6619  6619 W art     : b53d6000-b53d9000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
09-13 14:17:59.456  6619  6619 W art     : b53d9000-b53dd000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b53dd000-b543e000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
09-13 14:17:59.456  6619  6619 W art     : b543e000-b543f000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
09-13 14:17:59.456  6619  6619 W art     : b543f000-b548e000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
09-13 14:17:59.456  6619  6619 W art     : b548e000-b5490000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
09-13 14:17:59.456  6619  6619 W art     : b5490000-b5491000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
09-13 14:17:59.456  6619  6619 W art     : b5491000-b5492000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5492000-b5499000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 14:17:59.456  6619  6619 W art     : b5499000-b549a000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 14:17:59.456  6619  6619 W art     : b549a000-b549b000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
09-13 14:17:59.456  6619  6619 W art     : avc_common.so
09-13 14:17:59.456  6619  6619 W art     : b549c000-b549f000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 14:17:59.456  6619  6619 W art     : b549f000-b54a0000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 14:17:59.456  6619  6619 W art     : b54a0000-b54a1000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
09-13 14:17:59.456  6619  6619 W art     : enc_common.so
09-13 14:17:59.456  6619  6619 W art     : b54a2000-b54a6000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
09-13 14:17:59.456  6619  6619 W art     : b54a6000-b54a7000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b54a7000-b54a8000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
09-13 14:17:59.456  6619  6619 W art     : b54a8000-b54a9000 rw-p 00005000 b3:17 2510       /syste
09-13 14:17:59.456  6619  6619 W art     : m/lib/libpowermanager.so
09-13 14:17:59.456  6619  6619 W art     : b54aa000-b54c7000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 14:17:59.456  6619  6619 W art     : b54c7000-b54c8000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 14:17:59.456  6619  6619 W art     : b54c8000-b54c9000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 14:17:59.456  6619  6619 W art     : b54ca000-b54cf000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 14:17:59.456  6619  6619 W art     : b54cf000-b54d0000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 14:17:59.456  6619  6619 W art     : b54d0000-b54d1000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 14:17:59.456  6619  6619 W art     : b54d2000-b5503000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 14:17:59.456  6619  6619 W art     : b5503000-b5504000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5504000-b5507000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 14:17:59.456  6619  6619 W art     : b5507000-b5508000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 14:17:59.456  6619  6619 W art     : b5509000-b5544000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
09-13 14:17:59.456  6619  6619 W art     : b5544000-b5545000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
09-13 14:17:59.456  6619  6619 W art     : b5545000-b5546000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
09-13 14:17:59.456  6619  6619 W art     : b5547000-b554e000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
09-13 14:17:59.456  6619  6619 W art     : b554e000-b554f000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b554f000-b5550000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
09-13 14:17:59.456  6619  6619 W art     : b5550000-b5551000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
09-13 14:17:59.456  6619  6619 W art     : b5551000-b5552000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5552000-b5569000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
09-13 14:17:59.456  6619  6619 W art     : b5569000-b556a000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b556a000-b556d000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
09-13 14:17:59.456  6619  6619 W art     : b556d000-b556e000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
09-13 14:17:59.456  6619  6619 W art     : b556e000-b558d000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
09-13 14:17:59.456  6619  6619 W art     : b558d000-b558e000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
09-13 14:17:59.456  6619  6619 W art     : b558e000-b558f000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
09-13 14:17:59.456  6619  6619 W art     : b558f000-b55cd000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
09-13 14:17:59.456  6619  6619 W art     : b55cd000-b55ce000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b55ce000-b55d0000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
09-13 14:17:59.456  6619  6619 W art     : b55d0000-b55d1000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
09-13 14:17:59.456  6619  6619 W art     : b55d2000-b55d9000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 14:17:59.456  6619  6619 W art     : b55d9000-b55da000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 14:17:59.456  6619  6619 W art     : b55da000-b55db000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 14:17:59.456  6619  6619 W art     : b55dc000-b55df000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 14:17:59.456  6619  6619 W art     : b55df000-b55e0000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 14:17:59.456  6619  6619 W art     : b55e0000-b55e1000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 14:17:59.456  6619  6619 W art     : b55e1000-b55e7000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 14:17:59.456  6619  6619 W art     : b55e7000-b55e8000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b55e8000-b55e9000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 14:17:59.456  6619  6619 W art     : b55e9000-b55ea000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 14:17:59.456  6619  6619 W art     : b55ea000-b55f3000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
09-13 14:17:59.456  6619  6619 W art     : b55f3000-b55f4000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
09-13 14:17:59.456  6619  6619 W art     : b55f4000-b55f5000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
09-13 14:17:59.456  6619  6619 W art     : b55f5000-b5686000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 14:17:59.456  6619  6619 W art     : b5686000-b5687000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5687000-b5692000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 14:17:59.456  6619  6619 W art     : b5692000-b5693000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 14:17:59.456  6619  6619 W art     : b5694000-b56a6000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
09-13 14:17:59.456  6619  6619 W art     : b56a6000-b56a7000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
09-13 14:17:59.456  6619  6619 W art     : b56a7000-b56a8000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
09-13 14:17:59.456  6619  6619 W art     : b56a9000-b56ae000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
09-13 14:17:59.456  6619  6619 W art     : b56ae000-b56af000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
09-13 14:17:59.456  6619  6619 W art     : b56af000-b56b0000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
09-13 14:17:59.456  6619  6619 W art     : b56b1000-b571e000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
09-13 14:17:59.456  6619  6619 W art     : b571e000-b571f000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b571f000-b5721000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
09-13 14:17:59.456  6619  6619 W art     : b5721000-b5722000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
09-13 14:17:59.456  6619  6619 W art     : b5722000-b5723000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5723000-b572a000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 14:17:59.456  6619  6619 W art     : b572a000-b572b000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 14:17:59.456  6619  6619 W art     : b572b000-b572c000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 14:17:59.456  6619  6619 W art     : b572d000-b57ad000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 14:17:59.456  6619  6619 W art     : b57ad000-b57ae000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b57ae000-b57af000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 14:17:59.456  6619  6619 W art     : b57af000-b57b0000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 14:17:59.456  6619  6619 W art     : b57b0000-b57c7000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b57c7000-b57fe000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 14:17:59.456  6619  6619 W art     : b57fe000-b57ff000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 14:17:59.456  6619  6619 W art     : b57ff000-b5800000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 14:17:59.456  6619  6619 W art     : b5800000-b581c000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 14:17:59.456  6619  6619 W art     : b581c000-b581d000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 14:17:59.456  6619  6619 W art     : b581d000-b581e000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 14:17:59.456  6619  6619 W art     : b581f000-b5880000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
09-13 14:17:59.456  6619  6619 W art     : b5880000-b5882000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
09-13 14:17:59.456  6619  6619 W art     : b5882000-b5883000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
09-13 14:17:59.456  6619  6619 W art     : b5884000-b58a9000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
09-13 14:17:59.456  6619  6619 W art     : b58a9000-b58aa000 r--p 00024000 b3:17 126        /system/lib/libpng.so
09-13 14:17:59.456  6619  6619 W art     : b58aa000-b58ab000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
09-13 14:17:59.456  6619  6619 W art     : b58ac000-b58b4000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 14:17:59.456  6619  6619 W art     : b58b4000-b58b6000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 14:17:59.456  6619  6619 W art     : b58b6000-b58b7000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 14:17:59.456  6619  6619 W art     : b58b8000-b58bb000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
09-13 14:17:59.456  6619  6619 W art     : b58bb000-b58bc000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
09-13 14:17:59.456  6619  6619 W art     : b58bc000-b58bd000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
09-13 14:17:59.456  6619  6619 W art     : b58bd000-b58c1000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
09-13 14:17:59.456  6619  6619 W art     : b58c1000-b58c2000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b58c2000-b58c3000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
09-13 14:17:59.456  6619  6619 W art     : b58c3000-b58c4000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
09-13 14:17:59.456  6619  6619 W art     : b58c4000-b58d4000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
09-13 14:17:59.456  6619  6619 W art     : b58d4000-b58d5000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
09-13 14:17:59.456  6619  6619 W art     : b58d5000-b58d6000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
09-13 14:17:59.456  6619  6619 W art     : b58d6000-b591c000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b591c000-b5925000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
09-13 14:17:59.456  6619  6619 W art     : b5925000-b5926000 r--p 00008000 b3:17 982        /system/lib/libbase.so
09-13 14:17:59.456  6619  6619 W art     : b5926000-b5927000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
09-13 14:17:59.456  6619  6619 W art     : b5928000-b592d000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
09-13 14:17:59.456  6619  6619 W art     : b592d000-b592e000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
09-13 14:17:59.456  6619  6619 W art     : b592e000-b592f000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
09-13 14:17:59.456  6619  6619 W art     : b592f000-b5932000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 14:17:59.456  6619  6619 W art     : b5932000-b5933000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5933000-b5934000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 14:17:59.456  6619  6619 W art     : b5934000-b5935000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 14:17:59.456  6619  6619 W art     : b5936000-b594e000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
09-13 14:17:59.456  6619  6619 W art     : ght_foundation.so
09-13 14:17:59.456  6619  6619 W art     : b594e000-b594f000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b594f000-b5950000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 14:17:59.456  6619  6619 W art     : b5950000-b5951000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 14:17:59.456  6619  6619 W art     : b5951000-b5952000 rw-p 00000000 00:
09-13 14:17:59.456  6619  6619 W art     : 00 0          [anon:linker_alloc_vector]
09-13 14:17:59.456  6619  6619 W art     : b5952000-b5aec000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
09-13 14:17:59.456  6619  6619 W art     : b5aec000-b5aed000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5aed000-b5afa000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
09-13 14:17:59.456  6619  6619 W art     : b5afa000-b5afb000 rw-p 001a7000 b3:17 604        /system/
09-13 14:17:59.456  6619  6619 W art     : lib/libstagefright.so
09-13 14:17:59.456  6619  6619 W art     : b5afb000-b5aff000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
09-13 14:17:59.456  6619  6619 W art     : b5aff000-b5b00000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5b00000-b5b01000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
09-13 14:17:59.456  6619  6619 W art     : b5b01000-b5b02000 rw-p 00005000 b3:17 2676       /system/lib/libp
09-13 14:17:59.456  6619  6619 W art     : ersona.so
09-13 14:17:59.456  6619  6619 W art     : b5b02000-b5b15000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
09-13 14:17:59.456  6619  6619 W art     : b5b15000-b5b16000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
09-13 14:17:59.456  6619  6619 W art     : b5b16000-b5b17000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
09-13 14:17:59.456  6619  6619 W art     : b5b18000-b5b63000 r
09-13 14:17:59.456  6619  6619 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
09-13 14:17:59.456  6619  6619 W art     : b5b63000-b5b64000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
09-13 14:17:59.456  6619  6619 W art     : b5b64000-b5b65000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
09-13 14:17:59.456  6619  6619 W art     : b5b65000-b5b67000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5b68000-b5b79000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 14:17:59.456  6619  6619 W art     : b5b79000-b5b7a000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5b7a000-b5b7b000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 14:17:59.456  6619  6619 W art     : b5b7b000-b5b7c000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 14:17:59.456  6619  6619 W art     : b5b7c000-b5b7d000 r--p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5b7d000-b5b87000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
09-13 14:17:59.456  6619  6619 W art     : b5b87000-b5b89000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
09-13 14:17:59.456  6619  6619 W art     : b5b89000-b5b8a000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
09-13 14:17:59.456  6619  6619 W art     : b5b8a000-b5ba3000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
09-13 14:17:59.456  6619  6619 W art     : b5ba3000-b5ba4000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
09-13 14:17:59.456  6619  6619 W art     : b5ba4000-b5ba7000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
09-13 14:17:59.456  6619  6619 W art     : b5ba7000-b5bab000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5bab000-b5c1f000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
09-13 14:17:59.456  6619  6619 W art     : b5c1f000-b5c20000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5c20000-b5c23000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
09-13 14:17:59.456  6619  6619 W art     : b5c23000-b5c24000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
09-13 14:17:59.456  6619  6619 W art     : b5c24000-b5c25000 r--p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5c25000-b5c28000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
09-13 14:17:59.456  6619  6619 W art     : b5c28000-b5c29000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
09-13 14:17:59.456  6619  6619 W art     : b5c29000-b5c2a000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
09-13 14:17:59.456  6619  6619 W art     : b5c2a000-b5c2b000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5c2b000-b5c30000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 14:17:59.456  6619  6619 W art     : b5c30000-b5c31000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 14:17:59.456  6619  6619 W art     : b5c31000-b5c32000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 14:17:59.456  6619  6619 W art     : b5c32000-b5c33000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5c33000-b5c36000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 14:17:59.456  6619  6619 W art     : b5c36000-b5c37000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 14:17:59.456  6619  6619 W art     : b5c37000-b5c38000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 14:17:59.456  6619  6619 W art     : b5c38000-b5c39000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:17:59.456  6619  6619 W art     : b5c39000-b5c3d000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
09-13 14:17:59.456  6619  6619 W art     : b5c3d000-b5c3e000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
09-13 14:17:59.456  6619  6619 W art     : b5c3e000-b5c3f000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
09-13 14:17:59.456  6619  6619 W art     : b5c3f000-b5c40000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5c40000-b5c44000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 14:17:59.456  6619  6619 W art     : b5c44000-b5c45000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 14:17:59.456  6619  6619 W art     : b5c45000-b5c46000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 14:17:59.456  6619  6619 W art     : b5c46000-b5c47000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5c47000-b5c55000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
09-13 14:17:59.456  6619  6619 W art     : b5c55000-b5c56000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b5c56000-b5c57000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
09-13 14:17:59.456  6619  6619 W art     : b5c57000-b5c58000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
09-13 14:17:59.456  6619  6619 W art     : b5c58000-b5c62000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 14:17:59.456  6619  6619 W art     : b5c62000-b5c65000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 14:17:59.456  6619  6619 W art     : b5c65000-b5c66000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 14:17:59.456  6619  6619 W art     : b5c66000-b5c67000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5c67000-b5c71000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
09-13 14:17:59.456  6619  6619 W art     : b5c71000-b5c74000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
09-13 14:17:59.456  6619  6619 W art     : b5c74000-b5c75000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
09-13 14:17:59.456  6619  6619 W art     : b5c75000-b5c79000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
09-13 14:17:59.456  6619  6619 W art     : b5c79000-b5c7a000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
09-13 14:17:59.456  6619  6619 W art     : b5c7a000-b5c7b000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
09-13 14:17:59.456  6619  6619 W art     : b5c7b000-b5c7c000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b5c7c000-b5c89000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
09-13 14:17:59.456  6619  6619 W art     : b5c89000-b5c8b000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
09-13 14:17:59.456  6619  6619 W art     : b5c8b000-b5c8c000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
09-13 14:17:59.456  6619  6619 W art     : b5c8c000-b609e000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
09-13 14:17:59.456  6619  6619 W art     : b609e000-b609f000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b609f000-b60a8000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
09-13 14:17:59.456  6619  6619 W art     : b60a8000-b60ac000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
09-13 14:17:59.456  6619  6619 W art     : b60ac000-b60ad000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b60ad000-b60b4000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
09-13 14:17:59.456  6619  6619 W art     : b60b4000-b60b5000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
09-13 14:17:59.456  6619  6619 W art     : b60b5000-b60b6000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
09-13 14:17:59.456  6619  6619 W art     : b60b6000-b60b7000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b60b7000-b60d2000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
09-13 14:17:59.456  6619  6619 W art     : b60d2000-b60d3000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
09-13 14:17:59.456  6619  6619 W art     : b60d3000-b60d4000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
09-13 14:17:59.456  6619  6619 W art     : b60d4000-b60d5000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b60d5000-b6121000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 14:17:59.456  6619  6619 W art     : b6121000-b6122000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6122000-b6123000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 14:17:59.456  6619  6619 W art     : b6123000-b6124000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 14:17:59.456  6619  6619 W art     : b6124000-b6125000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6125000-b6129000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
09-13 14:17:59.456  6619  6619 W art     : b6129000-b612a000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b612a000-b612b000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
09-13 14:17:59.456  6619  6619 W art     : b612b000-b612c000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
09-13 14:17:59.456  6619  6619 W art     : b612c000-b6164000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
09-13 14:17:59.456  6619  6619 W art     : b6164000-b6165000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
09-13 14:17:59.456  6619  6619 W art     : b6165000-b6166000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
09-13 14:17:59.456  6619  6619 W art     : b6166000-b6167000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6167000-b6206000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
09-13 14:17:59.456  6619  6619 W art     : b6206000-b6224000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
09-13 14:17:59.456  6619  6619 W art     : b6224000-b6225000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
09-13 14:17:59.456  6619  6619 W art     : b6225000-b6398000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
09-13 14:17:59.456  6619  6619 W art     : b6398000-b63a3000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
09-13 14:17:59.456  6619  6619 W art     : b63a3000-b63a4000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
09-13 14:17:59.456  6619  6619 W art     : b63a4000-b64bb000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
09-13 14:17:59.456  6619  6619 W art     : b64bb000-b64c6000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
09-13 14:17:59.456  6619  6619 W art     : b64c6000-b64c7000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
09-13 14:17:59.456  6619  6619 W art     : b64c7000-b64cb000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b64cb000-b64ef000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
09-13 14:17:59.456  6619  6619 W art     : b64ef000-b64f1000 r--p 00023000 b3:17 400        /system/lib/libssl.so
09-13 14:17:59.456  6619  6619 W art     : b64f1000-b64f2000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
09-13 14:17:59.456  6619  6619 W art     : b64f2000-b6598000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
09-13 14:17:59.456  6619  6619 W art     : b6598000-b65a5000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
09-13 14:17:59.456  6619  6619 W art     : b65a5000-b65a6000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
09-13 14:17:59.456  6619  6619 W art     : b65a6000-b65a7000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b65a7000-b65fa000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
09-13 14:17:59.456  6619  6619 W art     : b65fa000-b65fb000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b65fb000-b65fc000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
09-13 14:17:59.456  6619  6619 W art     : b65fc000-b65fd000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
09-13 14:17:59.456  6619  6619 W art     : b65fd000-b6602000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6602000-b6614000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
09-13 14:17:59.456  6619  6619 W art     : b6614000-b6615000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6615000-b6616000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
09-13 14:17:59.456  6619  6619 W art     : b6616000-b6617000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
09-13 14:17:59.456  6619  6619 W art     : b6617000-b661e000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 14:17:59.456  6619  6619 W art     : b661e000-b661f000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 14:17:59.456  6619  6619 W art     : b661f000-b6620000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 14:17:59.456  6619  6619 W art     : b6620000-b6621000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6621000-b6624000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
09-13 14:17:59.456  6619  6619 W art     : b6624000-b6625000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
09-13 14:17:59.456  6619  6619 W art     : b6625000-b6626000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
09-13 14:17:59.456  6619  6619 W art     : b6626000-b662a000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
09-13 14:17:59.456  6619  6619 W art     : b662a000-b662b000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
09-13 14:17:59.456  6619  6619 W art     : b662b000-b662c000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
09-13 14:17:59.456  6619  6619 W art     : b662c000-b663a000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
09-13 14:17:59.456  6619  6619 W art     : b663a000-b663b000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b663b000-b663c000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
09-13 14:17:59.456  6619  6619 W art     : b663c000-b663d000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
09-13 14:17:59.456  6619  6619 W art     : b663d000-b6646000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 14:17:59.456  6619  6619 W art     : b6646000-b6647000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 14:17:59.456  6619  6619 W art     : b6647000-b6648000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 14:17:59.456  6619  6619 W art     : b6648000-b66ae000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
09-13 14:17:59.456  6619  6619 W art     : b66ae000-b66af000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b66af000-b66b1000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
09-13 14:17:59.456  6619  6619 W art     : b66b1000-b66ba000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
09-13 14:17:59.456  6619  6619 W art     : b66ba000-b66bd000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b66bd000-b6754000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
09-13 14:17:59.456  6619  6619 W art     : b6754000-b6756000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
09-13 14:17:59.456  6619  6619 W art     : b6756000-b6757000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
09-13 14:17:59.456  6619  6619 W art     : b6757000-b6758000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6758000-b6a76000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
09-13 14:17:59.456  6619  6619 W art     : b6a76000-b6a77000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6a77000-b6a92000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
09-13 14:17:59.456  6619  6619 W art     : b6a92000-b6a96000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
09-13 14:17:59.456  6619  6619 W art     : b6a96000-b6a9b000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6a9b000-b6aa3000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 14:17:59.456  6619  6619 W art     : b6aa3000-b6aa4000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 14:17:59.456  6619  6619 W art     : b6aa4000-b6aa5000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 14:17:59.456  6619  6619 W art     : b6aa5000-b6ad3000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
09-13 14:17:59.456  6619  6619 W art     : b6ad3000-b6ad4000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6ad4000-b6adb000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
09-13 14:17:59.456  6619  6619 W art     : b6adb000-b6adc000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
09-13 14:17:59.456  6619  6619 W art     : b6adc000-b6b22000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
09-13 14:17:59.456  6619  6619 W art     : b6b22000-b6b23000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6b23000-b6b26000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
09-13 14:17:59.456  6619  6619 W art     : b6b26000-b6b27000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
09-13 14:17:59.456  6619  6619 W art     : b6b27000-b6b42000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
09-13 14:17:59.456  6619  6619 W art     : b6b42000-b6b46000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
09-13 14:17:59.456  6619  6619 W art     : b6b46000-b6b47000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
09-13 14:17:59.456  6619  6619 W art     : b6b47000-b6b94000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
09-13 14:17:59.456  6619  6619 W art     : b6b94000-b6b95000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6b95000-b6ba1000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
09-13 14:17:59.456  6619  6619 W art     : b6ba1000-b6ba2000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
09-13 14:17:59.456  6619  6619 W art     : b6ba2000-b6baf000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
09-13 14:17:59.456  6619  6619 W art     : b6baf000-b6bb0000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6bb0000-b6bb1000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
09-13 14:17:59.456  6619  6619 W art     : b6bb1000-b6bb2000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
09-13 14:17:59.456  6619  6619 W art     : b6bb2000-b6bba000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
09-13 14:17:59.456  6619  6619 W art     : b6bba000-b6bbb000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6bbb000-b6bbc000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
09-13 14:17:59.456  6619  6619 W art     : b6bbc000-b6bbd000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
09-13 14:17:59.456  6619  6619 W art     : b6bbd000-b6bc4000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
09-13 14:17:59.456  6619  6619 W art     : b6bc4000-b6bc5000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
09-13 14:17:59.456  6619  6619 W art     : b6bc5000-b6bc6000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
09-13 14:17:59.456  6619  6619 W art     : b6bc6000-b6bda000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
09-13 14:17:59.456  6619  6619 W art     : b6bda000-b6bdc000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
09-13 14:17:59.456  6619  6619 W art     : b6bdc000-b6bdd000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
09-13 14:17:59.456  6619  6619 W art     : b6bdd000-b6c05000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
09-13 14:17:59.456  6619  6619 W art     : b6c05000-b6c07000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
09-13 14:17:59.456  6619  6619 W art     : b6c07000-b6c08000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
09-13 14:17:59.456  6619  6619 W art     : b6c08000-b6c0b000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
09-13 14:17:59.456  6619  6619 W art     : b6c0b000-b6c0c000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
09-13 14:17:59.456  6619  6619 W art     : b6c0c000-b6c0d000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
09-13 14:17:59.456  6619  6619 W art     : b6c0d000-b6c16000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
09-13 14:17:59.456  6619  6619 W art     : b6c16000-b6c17000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
09-13 14:17:59.456  6619  6619 W art     : b6c17000-b6c18000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
09-13 14:17:59.456  6619  6619 W art     : b6c18000-b6c38000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
09-13 14:17:59.456  6619  6619 W art     : b6c38000-b6c39000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
09-13 14:17:59.456  6619  6619 W art     : b6c39000-b6c3a000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
09-13 14:17:59.456  6619  6619 W art     : b6c3a000-b6cad000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
09-13 14:17:59.456  6619  6619 W art     : b6cad000-b6cb1000 r--p 00072000 b3:17 1016       /system/lib/libc.so
09-13 14:17:59.456  6619  6619 W art     : b6cb1000-b6cb4000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
09-13 14:17:59.456  6619  6619 W art     : b6cb4000-b6cbe000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6cbe000-b6d46000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
09-13 14:17:59.456  6619  6619 W art     : b6d46000-b6d47000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6d47000-b6d4b000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
09-13 14:17:59.456  6619  6619 W art     : b6d4b000-b6d4c000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
09-13 14:17:59.456  6619  6619 W art     : b6d4c000-b6d4d000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6d4d000-b6d76000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
09-13 14:17:59.456  6619  6619 W art     : b6d76000-b6d77000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6d77000-b6d7a000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
09-13 14:17:59.456  6619  6619 W art     : b6d7a000-b6d7b000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
09-13 14:17:59.456  6619  6619 W art     : b6d7b000-b6e55000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 14:17:59.456  6619  6619 W art     : b6e55000-b6e5c000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 14:17:59.456  6619  6619 W art     : b6e5c000-b6e64000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 14:17:59.456  6619  6619 W art     : b6e64000-b6e65000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6e65000-b6e66000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:17:59.456  6619  6619 W art     : b6e66000-b6e67000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
09-13 14:17:59.456  6619  6619 W art     : b6e67000-b6e68000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6e68000-b6e6b000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6e6b000-b6e90000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
09-13 14:17:59.456  6619  6619 W art     : b6e90000-b6e91000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6e91000-b6e98000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
09-13 14:17:59.456  6619  6619 W art     : b6e98000-b6e99000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
09-13 14:17:59.456  6619  6619 W art     : b6e99000-b6ea0000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
09-13 14:17:59.456  6619  6619 W art     : b6ea0000-b6ea1000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
09-13 14:17:59.456  6619  6619 W art     : b6ea1000-b6ea2000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
09-13 14:17:59.456  6619  6619 W art     : b6ea2000-b6ea3000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6ea3000-b6ebb000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
09-13 14:17:59.456  6619  6619 W art     : b6ebb000-b6ebc000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6ebc000-b6ebd000 r--p 00018000 b3:17 918        /system/lib/libutils.so
09-13 14:17:59.456  6619  6619 W art     : b6ebd000-b6ebe000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
09-13 14:17:59.456  6619  6619 W art     : b6ebe000-b6ecc000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
09-13 14:17:59.456  6619  6619 W art     : b6ecc000-b6ecd000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6ecd000-b6ece000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
09-13 14:17:59.456  6619  6619 W art     : b6ece000-b6ecf000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
09-13 14:17:59.456  6619  6619 W art     : b6ecf000-b6ed0000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:17:59.456  6619  6619 W art     : b6ed0000-b6ed2000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6ed2000-b6ed3000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6ed3000-b6ed4000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:17:59.456  6619  6619 W art     : b6ed4000-b6ed5000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
09-13 14:17:59.456  6619  6619 W art     : b6ed5000-b6ed6000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:17:59.456  6619  6619 W art     : b6ed6000-b6ef6000 r--s 00000000 00:0b 6572       /dev/__properties__
09-13 14:17:59.456  6619  6619 W art     : b6ef6000-b6ef7000 r--p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6ef7000-b6ef8000 ---p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6ef8000-b6efa000 rw-p 00000000 00:00 0          [anon:thread signal stack]
09-13 14:17:59.456  6619  6619 W art     : b6efa000-b6efb000 r-xp 00000000 00:00 0          [sigpage]
09-13 14:17:59.456  6619  6619 W art     : b6efb000-b6f16000 r-xp 00000000 b3:17 341        /system/bin/linker
09-13 14:17:59.456  6619  6619 W art     : b6f16000-b6f17000 r--p 0001a000 b3:17 341        /system/bin/linker
09-13 14:17:59.456  6619  6619 W art     : b6f17000-b6f19000 rw-p 0001b000 b3:17 341        /system/bin/linker
09-13 14:17:59.456  6619  6619 W art     : b6f19000-b6f1b000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : b6f1b000-b6f20000 r-xp 00000000 b3:17 978        /system/bin/app_process32
09-13 14:17:59.456  6619  6619 W art     : b6f20000-b6f21000 r--p 00004000 b3:17 978        /system/bin/app_process32
09-13 14:17:59.456  6619  6619 W art     : b6f21000-b6f22000 rw-p 00000000 00:00 0 
09-13 14:17:59.456  6619  6619 W art     : beb4a000-beb6b000 rw-p 00000000 00:00 0          [stack]
09-13 14:17:59.456  6619  6619 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
09-13 14:17:59.556  6619  6619 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 14:17:59.636  6619  6619 I Radio-JNI: register_android_hardware_Radio DONE
09-13 14:17:59.646  6619  6619 E AffinityControl: AffinityControl: registerfunction enter
09-13 14:17:59.676  6619  6619 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 14:17:59.696   765  1253 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
09-13 14:17:59.716   765  1253 D ActivityManager: mDVFSHelper.acquire()
09-13 14:17:59.726   765  1253 V WindowManager: addAppToken: AppWindowToken{dc1e2c token=Token{8cdf1df ActivityRecord{ee6c87e u0 com.test.thalitest/.MainActivity t169}}} to stack=1 task=169 at 0
09-13 14:17:59.736   765   891 D SecWifiDisplayUtil: Metadata value : none
09-13 14:17:59.736   765   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7c206c4 V.E...... R.....ID 0,0-0,0}
09-13 14:17:59.736   765   891 D ISSUE_DEBUG: InputChannelName : a8ac4e2 Starting com.test.thalitest
09-13 14:17:59.746   765  1253 I ActivityManager: Start proc 6650:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
09-13 14:17:59.746  6650  6650 E Zygote  : v2
09-13 14:17:59.746  6650  6650 I libpersona: KNOX_SDCARD checking this for 10004
09-13 14:17:59.746  6650  6650 I libpersona: KNOX_SDCARD not a persona
09-13 14:17:59.756   765  1253 D InputDispatcher: Focused application set to: xxxx
09-13 14:17:59.756  6650  6650 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 14:17:59.756  6650  6650 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 14:17:59.756   765  1253 D InputDispatcher: Focus left window: 3591
09-13 14:17:59.756   765   841 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a3ad79c u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
09-13 14:17:59.756   765  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
09-13 14:17:59.756  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008000 newVal=40008500 diff=500
09-13 14:17:59.756  6650  6650 E Zygote  : accessInfo : 0
09-13 14:17:59.756  6650  6650 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
09-13 14:17:59.756  6619  6619 D AndroidRuntime: Shutting down VM
09-13 14:17:59.766   292   292 I SurfaceFlinger: id=23 createSurf (1x1),1 flag=404, uhalitest
09-13 14:17:59.786   765   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
09-13 14:17:59.786   765   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 14:17:59.786   765   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
09-13 14:17:59.786   765   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 14:17:59.786   765   891 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
09-13 14:17:59.796  6650  6650 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 14:17:59.796  6650  6650 D ActivityThread: Added TimaKeyStore provider
09-13 14:17:59.806   765  1321 V WindowOrientationListener: setCurrentAppOrientation :-1
09-13 14:17:59.806   765  1321 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
09-13 14:17:59.816   765   841 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a8ac4e2 u0 d0 Starting com.test.thalitest}
09-13 14:17:59.816  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
09-13 14:17:59.826   765   891 V WindowStateAnimator: Finishing drawing window Window{a8ac4e2 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
09-13 14:17:59.826   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeb63364
09-13 14:17:59.836   765  1321 D ActivityManager:  Launching com.test.thalitest, updated priority
09-13 14:17:59.856   765   839 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
09-13 14:17:59.866   292   350 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
09-13 14:17:59.876   292   356 I SurfaceFlinger: id=21 Removed VSBConnecti (8/12)
09-13 14:17:59.876   292  2003 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/12)
09-13 14:17:59.876  1761  1900 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
09-13 14:17:59.876   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
09-13 14:17:59.876  1761  1761 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
09-13 14:17:59.876   292  2003 I SurfaceFlinger: id=19 Removed YUIInstallC (5/11)
09-13 14:17:59.886  3591  3591 V ActivityThread: updateVisibility : ActivityRecord{1231e88 token=android.os.BinderProxy@3151122 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : false
09-13 14:17:59.886   292   350 I SurfaceFlinger: id=19 Removed YUIInstallC (-2/11)
09-13 14:17:59.896  4521  4521 V ActivityThread: updateVisibility : ActivityRecord{f6ed139 token=android.os.BinderProxy@26a3964 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
09-13 14:17:59.896   292   356 D libEGL  : eglTerminate EGLDisplay = 0xb663f64c
09-13 14:17:59.906   292   356 D libEGL  : eglTerminate EGLDisplay = 0xb663f64c
09-13 14:17:59.906   292  2003 I SurfaceFlinger: id=8 Removed Mauncher (4/10)
09-13 14:17:59.906   292   350 I SurfaceFlinger: id=8 Removed Mauncher (-2/10)
09-13 14:17:59.916   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
09-13 14:17:59.916  1761  1761 V ActivityThread: updateVisibility : ActivityRecord{38b61d token=android.os.BinderProxy@bf412b7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 14:17:59.916  2261  6126 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
09-13 14:17:59.916  1761  1761 D Launcher: onTrimMemory. Level: 20
09-13 14:17:59.936   292  2003 I SurfaceFlinger: id=22 Removed VSBConnecti (4/9)
09-13 14:17:59.936   292   356 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/9)
09-13 14:17:59.946   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
09-13 14:17:59.986   765  1237 V AlarmManager: Expired Alarm result :8
,09-13 14:17:59.996   765  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
,09-13 14:17:59.996  6650  6650 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
09-13 14:17:59.996   765  3518 D M       : limitCPUFreq:: freq = -1
09-13 14:17:59.996   765  3518 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1497600  uid : 1000  pid : 765  tag : SIOP_ARM_MAX@25
,09-13 14:17:59.996   765  3518 D M       : limitGPUFreq:: freq = -1
,09-13 14:18:00.016   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:18:00.036  6650  6650 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,09-13 14:18:00.036  6650  6650 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,09-13 14:18:00.056  6650  6650 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,09-13 14:18:00.086  6650  6650 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,09-13 14:18:00.096  6650  6650 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 14:18:00.106  6650  6650 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 1732-1736)
,09-13 14:18:00.106  6650  6650 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,09-13 14:18:00.136  6650  6650 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {53fd9b4}
,09-13 14:18:00.136  6650  6650 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
09-13 14:18:00.136  6650  6650 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 14:18:00.136  6650  6669 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,09-13 14:18:00.146  6650  6650 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 14:18:00.146   765   778 I art     : Background partial concurrent mark sweep GC freed 38054(2MB) AllocSpace objects, 21(420KB) LOS objects, 27% free, 42MB/58MB, paused 2.024ms total 172.074ms
,09-13 14:18:00.176  6650  6650 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 14:18:00.176  6650  6650 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 14:18:00.176  6650  6650 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 14:18:00.176  6650  6650 I Adreno-EGL: Local Branch: ss
09-13 14:18:00.176  6650  6650 I Adreno-EGL: Remote Branch: 
09-13 14:18:00.176  6650  6650 I Adreno-EGL: Local Patches: 
09-13 14:18:00.176  6650  6650 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:00.186  6650  6650 D libEGL  : eglInitialize EGLDisplay = 0xbef52dac
,09-13 14:18:00.226   765  2490 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,09-13 14:18:00.226   765  2490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29689 com.android.server.am.ActivityManagerService.registerReceiver:22554 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3992 
,09-13 14:18:00.286  6650  6650 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,09-13 14:18:00.306  6650  6650 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 14:18:00.306  6650  6650 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,09-13 14:18:00.306  6650  6650 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,09-13 14:18:00.306  6650  6650 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,09-13 14:18:00.326  6650  6650 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,09-13 14:18:00.336  6650  6650 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 14:18:00.456  6650  6650 D SecWifiDisplayUtil: Metadata value : none
,09-13 14:18:00.466  6650  6650 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{b806abd I.E...... R.....ID 0,0-0,0}
,09-13 14:18:00.466  6650  6695 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 14:18:00.476   765   786 D ISSUE_DEBUG: InputChannelName : d9f73b7 com.test.thalitest/com.test.thalitest.MainActivity
,09-13 14:18:00.476   765  1253 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
09-13 14:18:00.476   765  1253 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 14:18:00.476   765   765 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 14:18:00.476   765   765 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-13 14:18:00.496  6650  6650 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6650
,09-13 14:18:00.506   765  2530 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6650 for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:00.506   765  1333 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,09-13 14:18:00.506   765  1333 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-13 14:18:00.506   765  1333 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
09-13 14:18:00.506   765  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,09-13 14:18:00.506   765  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 14:18:00.506   765  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 14:18:00.506   765  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
09-13 14:18:00.506   765  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
09-13 14:18:00.506   765  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
09-13 14:18:00.506   765  1333 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 14:18:00.516  6650  6669 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
09-13 14:18:00.516  6650  6650 D SecWifiDisplayUtil: Metadata value : none
09-13 14:18:00.526   292   292 I SurfaceFlinger: id=24 createSurf (1x1),1 flag=404, NainActivit
,09-13 14:18:00.546   765   783 D InputDispatcher: Focus entered window: 6650
09-13 14:18:00.546   765   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
09-13 14:18:00.546   765   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 14:18:00.546   765   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
09-13 14:18:00.546   765   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
09-13 14:18:00.546  6650  6695 D libEGL  : eglInitialize EGLDisplay = 0x9c9787c4
09-13 14:18:00.546  6650  6695 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 14:18:00.606  6650  6650 V ActivityThread: updateVisibility : ActivityRecord{2ebbfac token=android.os.BinderProxy@b24214 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 14:18:00.606  6650  6650 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,09-13 14:18:00.616  6650  6650 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,09-13 14:18:00.636   765   786 V WindowStateAnimator: Finishing drawing window Window{d9f73b7 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,09-13 14:18:00.646  6650  6650 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,09-13 14:18:00.646   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeb63364
09-13 14:18:00.646   765  1777 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 14:18:00.646   765   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 14:18:00.646   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 14:18:00.656   765   765 I KnoxTimeoutHandler: SD activityfalse
,09-13 14:18:00.656   765   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +667ms (total +930ms)
,09-13 14:18:00.656  6650  6650 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,09-13 14:18:00.666   765   891 D ActivityManager: mDVFSHelper.release()
,09-13 14:18:00.666   765   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ee6c87e u0 com.test.thalitest/.MainActivity t169} time:122295
,09-13 14:18:00.676  6650  6650 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b24214 time:122300
,09-13 14:18:00.676   765   891 D ViewRootImpl: #3 mView = null
,09-13 14:18:00.676   292   356 I SurfaceFlinger: id=23 Removed uhalitest (7/9)
,09-13 14:18:00.676   292   837 I SurfaceFlinger: id=23 Removed uhalitest (-2/9)
,09-13 14:18:00.686   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
,09-13 14:18:00.736  6650  6704 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 14:18:00.736  6650  6704 D libEGL  : eglInitialize EGLDisplay = 0x9a3913ec
,09-13 14:18:00.806  6650  6650 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6650
,09-13 14:18:00.996   765  3519 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,09-13 14:18:01.176  6650  6650 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 14:18:01.336  6650  6713 D jxcore_app_log: JniHelper::setJavaVM(0xb47bc000), pthread_self() = -1726285520
,09-13 14:18:01.336  6650  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 14:18:01.336  6650  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 14:18:01.336  6650  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 14:18:01.336  6650  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 14:18:01.336  6650  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 14:18:01.336  6650  6713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c353262 added. We now have 1 listener(s)
,09-13 14:18:01.346  6650  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,09-13 14:18:01.346  6650  6713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 14:18:01.346  6650  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 14:18:01.346  6650  6713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 14:18:01.356  6650  6713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37abf29 added. We now have 1 listener(s)
09-13 14:18:01.356  6650  6713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:01.366  6650  6713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
09-13 14:18:01.376  6650  6713 D BluetoothAdapter: STATE_ON
09-13 14:18:01.376  6650  6713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:01.376  6650  6713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:01.376  6650  6713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 14:18:01.376  6650  6713 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:01.386  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:01.386  6650  6713 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 14:18:01.386  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:01.416  6650  6650 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 14:18:01.486  1450  1450 D Recents : onTaskStackChanged
,09-13 14:18:01.496  1450  1450 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,09-13 14:18:02.556  6650  6714 W jxcore-log: Initializing JXcore engine
,09-13 14:18:02.556  6650  6714 W jxcore-log: JXcore engine is ready
,09-13 14:18:02.616  2446  2446 E audit   : type=1400 msg=audit(1473769082.616:287): avc:  denied  { ioctl } for  pid=6714 comm="Thread-952" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 14:18:02.616  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,09-13 14:18:02.616  2446  2446 E audit   : type=1300 msg=audit(1473769082.616:287): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=97f7a3c8 items=0 ppid=352 ppcomm=main pid=6714 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-952" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 14:18:02.616  2446  2446 E audit   : type=1327 msg=audit(1473769082.616:287): proctitle="com.test.thalitest"
09-13 14:18:02.616  2446  2446 E audit   : type=1320 msg=audit(1473769082.616:287): 
,09-13 14:18:02.616  2446  2446 E audit   : type=1400 msg=audit(1473769082.616:288): avc:  denied  { ioctl } for  pid=6714 comm="Thread-952" path="socket:[37745]" dev="sockfs" ino=37745 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 14:18:02.616  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
09-13 14:18:02.616  2446  2446 E audit   : type=1300 msg=audit(1473769082.616:288): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=97f7a3c8 items=0 ppid=352 ppcomm=main pid=6714 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-952" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
09-13 14:18:02.616  2446  2446 E audit   : type=1327 msg=audit(1473769082.616:288): proctitle="com.test.thalitest"
09-13 14:18:02.616  2446  2446 E audit   : type=1320 msg=audit(1473769082.616:288): 
,09-13 14:18:02.626  6650  6714 W jxcore-log: Starting JXcore engine
,09-13 14:18:02.716  6650  6714 W jxcore-log: Platform android
09-13 14:18:02.716  6650  6714 W jxcore-log: 
,09-13 14:18:02.716  6650  6714 W jxcore-log: Process ARCH arm
09-13 14:18:02.716  6650  6714 W jxcore-log: 
,09-13 14:18:02.776   765  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/169_task.xml.bak
,09-13 14:18:02.906  6650  6714 I jxcore-log: JXcore Cordova bridge is ready!
09-13 14:18:02.906  6650  6714 I jxcore-log: 
,09-13 14:18:02.906  6650  6714 W jxcore-log: JXcore engine is started
,09-13 14:18:02.916  6650  6713 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 14:18:02.916  6650  6650 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 14:18:02.936   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 14:18:02.936   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 14:18:02.936   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 14:18:06.016   765  3518 D M       : limitCPUFreq:: freq = 1497600
09-13 14:18:06.016   765  3518 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1497600  uid : 1000  pid : 765  pkgName : SIOP_ARM_MAX@25
09-13 14:18:06.026   765  3518 D M       : limitGPUFreq:: freq = 320000000
,09-13 14:18:06.036   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:18:06.446   765  1237 V AlarmManager: Expired Alarm result :4
,09-13 14:18:06.466   765   839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b3eb8a7 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{474321b 2146:com.google.android.gms.persistent/u0a11}
,09-13 14:18:06.466  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-13 14:18:06.466  1383  1383 I PERF    : received broadcast android.intent.action.TIME_TICK
,09-13 14:18:06.476  1383  1383 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 14:18:06.476   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{e21b154: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:06.506  1383  1383 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 14:18:06.516  1383  1383 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 14:18:06.516  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.516  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.526  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.526  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.526  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.536  1383  1383 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.536  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.606  1383  1383 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,09-13 14:18:06.656   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{38259f2: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:06.756  4496  6746 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-13 14:18:06.756  4496  6746 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-13 14:18:06.786  2146  2146 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 14:18:06.796   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{87c9ab5: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:06.806   765   839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{12f354a u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{474321b 2146:com.google.android.gms.persistent/u0a11}
,09-13 14:18:06.856   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{4926cbb: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:06.906   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{31b75d8: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:07.166  6752  6752 E Zygote  : v2
09-13 14:18:07.166   765  1633 I ActivityManager: Start proc 6752:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
09-13 14:18:07.166  6752  6752 I libpersona: KNOX_SDCARD checking this for 10011
09-13 14:18:07.166  6752  6752 I libpersona: KNOX_SDCARD not a persona
,09-13 14:18:07.166  6752  6752 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
09-13 14:18:07.166  6752  6752 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
09-13 14:18:07.166  6752  6752 E Zygote  : accessInfo : 0
09-13 14:18:07.166  6752  6752 W SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
,09-13 14:18:07.216  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 14:18:07.216  6752  6752 D ActivityThread: Added TimaKeyStore provider
,09-13 14:18:07.236  6752  6752 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,09-13 14:18:07.276  6752  6752 I MultiDex: VM with version 2.1.0 has multidex support
09-13 14:18:07.276  6752  6752 I MultiDex: install
09-13 14:18:07.276  6752  6752 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 14:18:07.316  6752  6752 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,09-13 14:18:07.336  6752  6752 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,09-13 14:18:07.336  6752  6752 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,09-13 14:18:07.336  6752  6752 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 14:18:07.376  6752  6752 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 14:18:07.406  6752  6752 D ChimeraCfgMgr: Reading stored module config
,09-13 14:18:07.546  2146  2146 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=4cc18dbe-1507-46f6-8203-69290671c920
,09-13 14:18:07.546  6752  6768 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 14:18:07.556  2146  2146 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 14:18:07.556  2146  2146 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 14:18:07.596   321   963 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:6752)
,09-13 14:18:07.656   321   972 D WVCdm   : Instantiating CDM.
,09-13 14:18:07.656   321   321 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6752)
,09-13 14:18:07.656   321   321 I WVCdm   : CdmEngine::OpenSession
09-13 14:18:07.656   321   321 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-13 14:18:07.666   321   321 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 14:18:07.676   321   321 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x21
,09-13 14:18:07.676   321   321 D DrmWidevineDash: Service_Initialize: starts!
09-13 14:18:07.676   321   321 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-13 14:18:07.686   321   321 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 14:18:07.686   321   321 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-13 14:18:07.686   321   321 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-13 14:18:07.686   321   321 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-13 14:18:07.686   321   321 D QSEECOMAPI: : App is not loaded in QSEE
09-13 14:18:07.686   321   321 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-13 14:18:07.686   321   321 E QSEECOMAPI: : Error::Loading image failed with ret = -1
,09-13 14:18:07.686   321   321 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-13 14:18:07.686   321   321 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 14:18:07.706   321   321 D QSEECOMAPI: : Loaded image: APP id = 2
,09-13 14:18:07.706   321   321 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-13 14:18:07.706   321   321 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaee94000
09-13 14:18:07.706   321   321 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xaee94000
,09-13 14:18:07.726   321   321 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-13 14:18:07.726   321   321 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-13 14:18:07.726   321   321 D DrmWidevineDash: hlos api version =  10
09-13 14:18:07.726   321   321 D DrmWidevineDash: tz api version =  10
09-13 14:18:07.726   321   321 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,09-13 14:18:07.726   321   321 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-13 14:18:07.736  6752  6762 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:07.736  6752  6762 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:07.746   321   321 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-13 14:18:07.746   321   321 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-13 14:18:07.746   321   321 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbee9e6b4
,09-13 14:18:07.746   321   321 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-13 14:18:07.746   321   321 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,09-13 14:18:07.746   321   321 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb1e1de28, dataLength=8
09-13 14:18:07.746   321   321 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-13 14:18:07.746   305  1186 D EnterpriseController: netId is 0
09-13 14:18:07.746   305  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 14:18:07.746   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 14:18:07.746   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 14:18:07.746   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 14:18:07.756   321   321 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xad46cc00, wrapped_rsa_key_length=1280
,09-13 14:18:07.766   321   321 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-13 14:18:07.766   321   321 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 14:18:07.766   321   971 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-13 14:18:07.766   321   971 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-13 14:18:07.766   321   971 I WVCdm   : CdmEngine::GenerateKeyRequest
09-13 14:18:07.766   321   971 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xaf4dc360, idLength=0xaf0bef2c
,09-13 14:18:07.766   321   971 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-13 14:18:07.766   321   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 0
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-13 14:18:07.776   321   971 D DrmWidevineDash: hlos api version =  10
09-13 14:18:07.776   321   971 D DrmWidevineDash: tz api version =  10
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-13 14:18:07.776   321   971 D WVCdm   : PrepareKeyRequest: nonce=669699554
,09-13 14:18:07.776   321   971 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xad462c00
09-13 14:18:07.776   321   971 D DrmWidevineDash: message_length=1631, signature=0xaf523a00, signature_length=2936795140
,09-13 14:18:07.786  2146  2341 W GCoreFlp: No location to return for getLastLocation()
,09-13 14:18:07.806  6752  6762 I qtaguid : Tagging socket 21 with tag 1000180300000000{268441603,0} uid -1, pid: 6752, getuid(): 10011
,09-13 14:18:07.866  4496  6747 D UdcContextInitService: registered all accounts: true
,09-13 14:18:07.876  2146  2403 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 14:18:07.916   321   971 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-13 14:18:07.926   321   972 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:6752)
,09-13 14:18:07.926   321   972 I WVCdm   : CdmEngine::CloseSession
09-13 14:18:07.926   321   972 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-13 14:18:07.926   321   972 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-13 14:18:07.926   321   972 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,09-13 14:18:07.926   321   972 D DrmWidevineDash: Service_Uninitialize: starts!
09-13 14:18:07.926   321   972 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-13 14:18:07.926   321   972 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,09-13 14:18:07.926   321   972 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-13 14:18:07.926   321   972 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-13 14:18:07.936  2146  2637 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-13 14:18:07.966  6752  6762 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} uid -1, pid: 6752, getuid(): 10011
,09-13 14:18:08.126   765  3518 D SSRM:n  : SIOP:: AP = 420, PST = 472, CUR = 300, LCD = 0
,09-13 14:18:08.136   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:18:08.136  6752  6762 I qtaguid : Untagging socket 21
,09-13 14:18:08.186  6752  6762 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
09-13 14:18:08.186  6752  6762 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,09-13 14:18:08.536   765  2529 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 14:18:08.536   765  2529 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4321, temperature: 331, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 14:18:08.536   765  2529 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 14:18:08.536   765  2529 D BatteryService: stay LED for charging
09-13 14:18:08.536   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 14:18:08.536   765   765 I MotionRecognitionService: Plugged
,09-13 14:18:08.546   765   765 D MotionRecognitionService:   cableConnection= 1
,09-13 14:18:08.546   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 14:18:08.546   765   765 D MotionRecognitionService: skip setTransmitPower. 
,09-13 14:18:08.556  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:18:08.556  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:18:08.556  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 14:18:08.566  2438  2438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 14:18:08.566  2438  2893 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:08.576  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:08.576  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:08.576  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:08.596  6781  6781 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-13 14:18:08.766  6781  6781 I dex2oat : ----------------------------------------------------
,09-13 14:18:08.766  6781  6781 I dex2oat : <SS>: S T A R T I N G . . .
,09-13 14:18:08.776  6781  6781 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
,09-13 14:18:08.776  6781  6781 I dex2oat : dex2oat took 182.940ms (threads: 4) arena alloc=285KB java alloc=43KB native alloc=1668KB free=1659KB
,09-13 14:18:08.786  6752  6762 W System  : ClassLoader referenced unknown path: 
,09-13 14:18:08.796  6752  6762 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.gms/app_fb
,09-13 14:18:08.796  6752  6762 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 14:18:08.796  6752  6762 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 14:18:08.796  6752  6762 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 14:18:08.796  6752  6762 I Adreno-EGL: Local Branch: ss
09-13 14:18:08.796  6752  6762 I Adreno-EGL: Remote Branch: 
09-13 14:18:08.796  6752  6762 I Adreno-EGL: Local Patches: 
09-13 14:18:08.796  6752  6762 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:08.806  6752  6762 D libEGL  : eglInitialize EGLDisplay = 0xb300d174
,09-13 14:18:08.876  6752  6762 D libEGL  : eglTerminate EGLDisplay = 0xb300d1cc
,09-13 14:18:08.886  6752  6762 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 14:18:08.886  6752  6762 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 14:18:08.886  6752  6762 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 14:18:08.886  6752  6762 I Adreno-EGL: Local Branch: ss
09-13 14:18:08.886  6752  6762 I Adreno-EGL: Remote Branch: 
09-13 14:18:08.886  6752  6762 I Adreno-EGL: Local Patches: 
09-13 14:18:08.886  6752  6762 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:08.886  6752  6762 D libEGL  : eglInitialize EGLDisplay = 0xb300d174
,09-13 14:18:08.946  6752  6762 D libEGL  : eglTerminate EGLDisplay = 0xb300d1cc
,09-13 14:18:09.506  6752  6762 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
09-13 14:18:09.506  6752  6762 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
09-13 14:18:09.506  6752  6762 I Adreno-EGL: Build Date: 01/28/16 Thu
09-13 14:18:09.506  6752  6762 I Adreno-EGL: Local Branch: ss
09-13 14:18:09.506  6752  6762 I Adreno-EGL: Remote Branch: 
09-13 14:18:09.506  6752  6762 I Adreno-EGL: Local Patches: 
09-13 14:18:09.506  6752  6762 I Adreno-EGL: Reconstruct Branch: 
,09-13 14:18:09.506  6752  6762 D libEGL  : eglInitialize EGLDisplay = 0xb300d174
,09-13 14:18:09.576  6752  6762 D libEGL  : eglTerminate EGLDisplay = 0xb300d1cc
,09-13 14:18:09.686  2146  6749 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:09.686  2146  6749 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:09.696   305  1186 D EnterpriseController: netId is 0
09-13 14:18:09.696   305  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 14:18:09.696  2146  6749 I qtaguid : Tagging socket 46 with tag 1000040100000000{268436481,0} uid 10011, pid: 2146, getuid(): 10011
,09-13 14:18:09.726   765  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 14:18:09.736  2146  6749 I qtaguid : Tagging socket 50 with tag 1000040100000000{268436481,0} uid 10011, pid: 2146, getuid(): 10011
,09-13 14:18:09.776   765   917 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 14:18:09.796   765   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 14:18:09.916   765  2490 V AlarmManager:  remove PendingIntent] PendingIntent{3403c0a: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:09.986  2146  2637 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 14:18:09.986  2146  2637 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-13 14:18:09.996  2146  2637 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-13 14:18:08.032+0200, stopTime=2016-09-13 14:18:10.006+0200, duration=1974ms
,09-13 14:18:09.996  2146  6813 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:09.996  2146  6813 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:09.996   305  1186 D EnterpriseController: netId is 0
09-13 14:18:09.996   305  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 14:18:10.006  2146  6813 I qtaguid : Tagging socket 52 with tag 1000310500000000{268448005,0} uid 10011, pid: 2146, getuid(): 10011
,09-13 14:18:10.036  2146  6813 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} uid 10011, pid: 2146, getuid(): 10011
,09-13 14:18:10.436   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{fa6ba98: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:10.446  2146  6813 I qtaguid : Untagging socket 52
,09-13 14:18:10.546  2146  2637 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-13 14:18:10.706  2146  6843 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 14:18:10.706  2146  6834 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 14:18:10.716  2146  6843 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 14:18:10.716  2146  6834 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 14:18:10.736  2146  6843 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 14:18:10.736  2146  6834 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 14:18:10.736  2146  6834 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-13 14:18:10.746  2146  6834 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 14:18:10.826   765  2530 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:10.846  2146  6834 W Uploader: UNKNOWN no longer exists, so no auth token.
,09-13 14:18:10.886  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:10.886  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:10.886   305  1186 D EnterpriseController: netId is 0
09-13 14:18:10.886   305  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 14:18:10.886  2146  6834 I qtaguid : Tagging socket 63 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:10.936  2146  6834 I qtaguid : Tagging socket 66 with tag fffff65b00000000{4294964827,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:11.176   765  2530 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:11.186  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:11.186  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:11.186  2146  6834 I qtaguid : Tagging socket 63 with tag 11065c0800000000{285629448,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:11.286   765  1613 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:11.296  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:11.296  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:11.296  2146  6834 I qtaguid : Tagging socket 63 with tag fffffb1f00000000{4294966047,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:11.396   765  1776 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:11.406  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:11.406  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:11.406  2146  6834 I qtaguid : Tagging socket 63 with tag 11065fff00000000{285630463,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:11.506   765  1633 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:11.526  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:11.526  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:11.526  2146  6834 I qtaguid : Tagging socket 63 with tag fffff1ef00000000{4294963695,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:11.666   765  2529 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:11.666  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:11.666  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:11.666  2146  6834 I qtaguid : Tagging socket 63 with tag 11065c9100000000{285629585,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:11.856   765   786 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 14:18:11.856  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:11.856  2146  6834 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:11.856  2146  6834 I qtaguid : Tagging socket 63 with tag 11065b5800000000{285629272,0} uid -1, pid: 2146, getuid(): 10011
,09-13 14:18:12.066   765  1653 V AlarmManager:  remove PendingIntent] PendingIntent{7544262: PendingIntentRecord{8ef880c com.google.android.gms broadcastIntent}}
,09-13 14:18:12.176  2146  6815 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 14:18:12.176  2146  6815 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 14:18:12.176  2146  6815 I qtaguid : Tagging socket 52 with tag 1000310200000000{268448002,0} uid 10011, pid: 2146, getuid(): 10011
,09-13 14:18:12.596  2146  6815 I qtaguid : Untagging socket 52
,09-13 14:18:12.616  2146  2637 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-13 14:18:14.646   765  1776 I ActivityManager: Killing 5769:com.google.android.apps.magazines/u0a127 (adj 15): DHA:empty #37
,09-13 14:18:14.726   765  1635 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,09-13 14:18:15.806  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 14:18:15.806  6650  6714 I jxcore-log: 
,09-13 14:18:15.806  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 14:18:15.806  6650  6714 I jxcore-log: 
,09-13 14:18:15.816  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:15.816  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:15.826  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:15.826  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:15.836  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 14:18:15.836  6650  6714 I jxcore-log: 
,09-13 14:18:15.836  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 14:18:15.836  6650  6714 I jxcore-log: 
,09-13 14:18:16.546  6650  6714 I jxcore-log: Unit Test app is loaded
09-13 14:18:16.546  6650  6714 I jxcore-log: 
,09-13 14:18:16.556  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:16.556  6650  6714 I jxcore-log: 
,09-13 14:18:16.566  6650  6650 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 14:18:16.566  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 14:18:16.566  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfa6c49 added. We now have 2 listener(s)
,09-13 14:18:16.566  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 14:18:16.566  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:16.566  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:18:16.566  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:16.566  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a14894e added. We now have 2 listener(s)
09-13 14:18:16.566  6650  6714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:16.576  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:16.576  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:16.576  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:16.586  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:16.586  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:16.586  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:16.586  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:16.586  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:16.586  6650  6714 D ExecuteNativeTests: Running unit tests
,09-13 14:18:16.586  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 14:18:16.586  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d537c added. We now have 3 listener(s)
,09-13 14:18:16.586  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:16.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 14:18:16.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:16.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 14:18:16.596  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 14:18:16.596  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7748405 added. We now have 3 listener(s)
09-13 14:18:16.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:16.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:16.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:16.596  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:16.596  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:16.606  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:16.606  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:16.606  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:16.606  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:16.606  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:18.186   765  3518 D SSRM:n  : SIOP:: AP = 420, PST = 460, CUR = 300, LCD = 0
,09-13 14:18:18.196   765  3518 D M       : limitCPUFreq:: freq = 1728000
,09-13 14:18:18.206   765  3518 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1497600  uid : 1000  pid : 765  tag : SIOP_ARM_MAX@25
,09-13 14:18:18.216   765  3518 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 765  pkgName : SIOP_ARM_MAX@25
,09-13 14:18:18.216   765  3518 D M       : limitGPUFreq:: freq = 389000000
,09-13 14:18:18.227   765  3518 D M       : limitSmartBonding:: limit = false
,09-13 14:18:18.237   765  3518 D M       : broadcastSiopChangedIntent:: FLASH = false, CAMERA = false, RECORDING = false, RECORDING_FPS = false, SMARTBONDING = false, LIVETHUMBNAIL = false
,09-13 14:18:18.256   765  3518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1096 com.android.server.ssrm.M.do:-1 i.t.z:-1 i.t.c:-1 i.e.hr:-1 
,09-13 14:18:18.256   765  3518 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 2
,09-13 14:18:18.266  2879  2879 D ContentApp:  LEVEL : 2
,09-13 14:18:18.296  2879  2879 D ContentApp: stopScan() is called.
,09-13 14:18:18.296  6880  6880 E Zygote  : v2
,09-13 14:18:18.296  6880  6880 I libpersona: KNOX_SDCARD checking this for 10053
09-13 14:18:18.306   765   839 I ActivityManager: Start proc 6880:com.sec.android.app.videoplayer/u0a53 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,09-13 14:18:18.306   765  1324 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,09-13 14:18:18.306   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:18:18.306  6880  6880 I libpersona: KNOX_SDCARD not a persona
,09-13 14:18:18.316  6880  6880 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,09-13 14:18:18.316  6880  6880 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,09-13 14:18:18.316  6880  6880 E Zygote  : accessInfo : 0
,09-13 14:18:18.326  6880  6880 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,09-13 14:18:18.396  6880  6880 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 14:18:18.396  6880  6880 D ActivityThread: Added TimaKeyStore provider
,09-13 14:18:18.406   765  1613 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{167bbba u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39ca6b 6880:com.sec.android.app.videoplayer/u0a53}
,09-13 14:18:18.406   765  1324 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,09-13 14:18:18.416  6880  6880 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,09-13 14:18:18.446  6880  6880 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,09-13 14:18:18.476  6880  6880 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,09-13 14:18:18.506  6880  6880 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 14:18:18.516  6880  6880 D videowall-Global: core_num = 4
,09-13 14:18:18.526  6880  6880 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
09-13 14:18:18.526  6880  6880 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,09-13 14:18:18.536  6880  6880 D TranscodeReceiver:  SIOP_LEVEL: 2
,09-13 14:18:18.546   765  1635 I ActivityManager: Killing 5833:com.android.email/u0a162 (adj 15): DHA:empty #37
,09-13 14:18:18.596   765   783 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,09-13 14:18:18.606   765  2530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 14:18:18.606   765  2530 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4355, temperature: 331, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 14:18:18.606   765  2530 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 14:18:18.606   765  2530 D BatteryService: stay LED for charging
,09-13 14:18:18.606   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 14:18:18.606   765   765 I MotionRecognitionService: Plugged
,09-13 14:18:18.606   765   765 D MotionRecognitionService:   cableConnection= 1
09-13 14:18:18.606   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 14:18:18.606   765   765 D MotionRecognitionService: skip setTransmitPower. 
,09-13 14:18:18.606  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:18:18.606  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:18:18.616  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 14:18:18.616  2438  2438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 14:18:18.616  2438  2893 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:18.636  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:18.636  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:18.636  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:26.787  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 14:18:26.787  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a added. We now have 4 listener(s)
,09-13 14:18:26.787  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 14:18:26.787  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:26.787  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:18:26.787  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 14:18:26.787  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b added. We now have 4 listener(s)
,09-13 14:18:26.787  6650  6714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:26.787  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:26.797  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:26.797  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:26.797  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:26.797  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.797  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:26.807  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:26.807  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:26.807  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:26.807  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.817  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 14:18:26.817  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:26.817  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:26.817  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:26.827  6650  6714 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 14:18:26.827  6650  6714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 14:18:26.827  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 14:18:26.827  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:26.827  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:26.827  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:26.827  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a removed from the list
09-13 14:18:26.827  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:26.827  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b removed from the list
09-13 14:18:26.827  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:26.836  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:26.836  6650  6714 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 14:18:26.836  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:26.836  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:26.836  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:26.836  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
,09-13 14:18:26.836  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:26.836  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:26.836  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:26.836  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:26.836  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:26.846  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-13 14:18:26.846  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:26.846  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:26.846  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:26.846  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
,09-13 14:18:26.846  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:26.846  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:26.856  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:26.856  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:26.856  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,09-13 14:18:26.856  6650  6714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 14:18:26.856  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:26.856  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:26.866  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:26.866  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.866  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:26.866  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:26.866  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:26.866  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:26.866  6650  6714 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-13 14:18:26.866  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 14:18:26.877  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:26.877  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 14:18:26.877  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:26.877  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:26.877  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:26.877  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:26.877  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:26.877  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:18:26.887  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:26.887  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:26.887  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:26.887  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:26.887  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:26.887  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:26.897  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.897  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.897  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.897  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:26.907  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.907  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.907  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 14:18:26.907  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:26.907  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.907  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:18:26.907  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 14:18:26.907  6650  6912 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 14:18:26.916  6650  6912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:26.916  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 7C F9 0E 34 8A A0
,09-13 14:18:26.916  6650  6912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:26.916  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 14:18:26.916  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:26.916  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:26.916  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.916  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.926  6650  6714 D BluetoothLeAdvertiser: start advertising
,09-13 14:18:26.926  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:26.936  2438  2921 D BtGatt.GattService: registerClient() - UUID=b20a3882-12b7-4d16-89a0-037c48619554
,09-13 14:18:26.996  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=b20a3882-12b7-4d16-89a0-037c48619554, clientIf=6
,09-13 14:18:26.996  6650  6661 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:26.996  2438  2892 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:18:26.996  2438  2892 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:26.996  2438  2892 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:26.996  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,09-13 14:18:26.996  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:27.006  2438  2651 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:27.006  2438  2651 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 14:18:27.006  2438  2651 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:18:27.006  2438  2651 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:18:27.006  2438  2651 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:18:27.006  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.016  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:27.016  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:27.016  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:27.026  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.026  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.026  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.026   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{cf1499: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.026   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{7c8935e: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.036  2438  2617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:18:27.036   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{601933f: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.036   765  2525 V AlarmManager:  remove PendingIntent] PendingIntent{b43140c: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.036  2438  2651 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:27.036  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.036  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.036  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.046   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{8f36155: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.046  2438  2617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 14:18:27.046  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 14:18:27.046  2438  2651 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 14:18:27.046  2438  2651 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 14:18:27.046  2438  2651 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 14:18:27.046  6650  6660 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 14:18:27.046  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 14:18:27.056  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:27.056  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:27.056  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:27.056  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 14:18:27.056  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:27.056  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 14:18:27.056  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:27.056  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:27.056  6650  6650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:27.056  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:27.066  6650  6714 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:27.066  6650  6714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 14:18:27.066  6650  6714 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 14:18:27.066  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 14:18:27.066  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:18:27.066  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:18:27.066  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:27.066  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:27.066  6650  6912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:27.066  6650  6912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:27.066  6650  6912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:27.076  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:27.076  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:27.076  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:27.076  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:27.076  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:27.076  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 14:18:27.076  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 14:18:27.076  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:18:27.076  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:18:27.076  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.076  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.076  6650  6714 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:27.076  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 14:18:27.076  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:27.076  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.076  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.076  6650  6714 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:27.086  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:27.086  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:27.086  2438  2651 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:27.086  2438  2651 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 14:18:27.086  2438  2651 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:18:27.086  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.086  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.086  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.086  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.086  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.086  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.086  2438  2617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 14:18:27.086  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.086  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.086  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.086  2438  2617 D BtGatt.GattService: Client app is not null!
,09-13 14:18:27.096  6650  6702 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:27.096   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{406876a: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.096   765  1546 V AlarmManager:  remove PendingIntent] PendingIntent{a06245b: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.096   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{d1364f8: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.106   765  2530 V AlarmManager:  remove PendingIntent] PendingIntent{9d5bdd1: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.106  2438  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:18:27.106  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 14:18:27.106  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:27.106  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:27.106  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 14:18:27.106  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 14:18:27.106  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:27.106  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:27.106  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:27.106  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:27.116  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:27.116  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:27.116  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:27.116  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:27.116  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:27.116  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:27.116  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 18
,09-13 14:18:27.116   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{7db036: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.126  6650  6714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:18:27.126  6650  6714 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-13 14:18:27.126  6650  6714 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 14:18:27.126  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-13 14:18:27.126  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:27.126  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:27.126  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:27.126  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:27.126  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:27.126   765  1653 V AlarmManager:  remove PendingIntent] PendingIntent{f8ab37: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.126  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562818
09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
,09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:27.136  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:27.136  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:27.136  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:27.136  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:27.136  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:27.136  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.136  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:27.136  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:18:27.136  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 14:18:27.136  6650  6932 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:18:27.136  6650  6932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:27.136  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:27.136  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:27.136  6650  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:27.136  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.146  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.146  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:27.146  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.146  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:18:27.146  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 14:18:27.146  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 7C F9 0E 34 8A A0
09-13 14:18:27.146  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:27.146  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:27.146  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.146  6650  6714 D BluetoothLeAdvertiser: start advertising
,09-13 14:18:27.146  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.156  2438  2460 D BtGatt.GattService: registerClient() - UUID=a52c0ea4-7db6-47e5-ad10-5b0118ff2237
,09-13 14:18:27.206  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=a52c0ea4-7db6-47e5-ad10-5b0118ff2237, clientIf=6
09-13 14:18:27.206  6650  6702 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:27.206  2438  2921 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:18:27.206  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:27.206  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:27.206  2438  2651 D BtGatt.AdvertiseManager: message : 0
09-13 14:18:27.206  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:18:27.206  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:27.206  2438  2651 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:18:27.206  2438  2651 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:18:27.206  2438  2651 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:18:27.206  2438  2651 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:18:27.206  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.206  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.206  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.206   765  2530 V AlarmManager:  remove PendingIntent] PendingIntent{922c3d3: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.206  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.206  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.206  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.206  2438  2617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:18:27.206  2438  2651 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:27.216  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.216   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{3a9db10: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.216  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.216  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.216  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 19
09-13 14:18:27.216  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562818
09-13 14:18:27.216  2438  2617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 14:18:27.216  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:18:27.216  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:18:27.216  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:27.216  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:18:27.216  2438  2651 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 14:18:27.216  2438  2651 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:18:27.216  2438  2651 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 14:18:27.216  6650  6661 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:18:27.216  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:27.216  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:27.216  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 14:18:27.216   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{e715609: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.216  6650  6714 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:27.216  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:27.216  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:18:27.216  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:27.216  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:27.216  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:27.216  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:27.226  6650  6650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:18:27.226  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:27.226   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{26e900e: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.226   765  1546 V AlarmManager:  remove PendingIntent] PendingIntent{1cbca2f: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.226   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{ab9983c: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.616   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 14:18:27.616   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 14:18:27.616   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 14:18:27.726  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:27.726  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:27.726  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:18:27.726  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 14:18:27.726  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:27.726  6650  6932 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:27.726  6650  6932 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:27.726  6650  6932 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:27.726  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:27.726  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:27.726  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:27.726  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:27.726  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
,09-13 14:18:27.726  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.726  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:27.726  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 14:18:27.726  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:27.726  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:18:27.726  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.736  6650  6714 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:27.736  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:27.736  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:27.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.736  6650  6714 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:27.736  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:27.736  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:27.736  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 14:18:27.736  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:27.746  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 14:18:27.746  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:18:27.746  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 14:18:27.746  2438  2651 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:27.746  2438  2651 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:18:27.746  2438  2651 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:18:27.746  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.746  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.746  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.746  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.746  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.746  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.746  2438  2617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 14:18:27.746  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.746  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:27.746  2438  2680 D bt_upio : BT_WAKE is asserted already
09-13 14:18:27.746  2438  2617 D BtGatt.GattService: Client app is not null!
,09-13 14:18:27.746  6650  6660 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:27.746  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 14:18:27.756   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{7d049c5: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.756  2438  2458 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:18:27.756  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:27.756  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:27.756  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 14:18:27.756  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 14:18:27.756  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:27.756  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:27.756  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:27.756  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:27.756  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:27.766  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:27.766  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:27.766  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:27.766  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.766  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:27.766  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.766  6650  6714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 14:18:27.766   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{d879f1a: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.776  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:27.776  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:27.776  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:27.786  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.786  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:27.786  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:27.786  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:27.786  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:27.796  6650  6714 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 14:18:27.796  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-13 14:18:27.796  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:27.796  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:27.796  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:27.796  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:27.796  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:27.796   765  1633 V AlarmManager:  remove PendingIntent] PendingIntent{af092e6: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.796   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{914d027: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.806   765  1546 V AlarmManager:  remove PendingIntent] PendingIntent{a72b2d4: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.806   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{94aec7d: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.806  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:27.806  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:27.806  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:27.806  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:27.806  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 14:18:27.816  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.816  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:27.816  2438  2878 D bt_upio : ..proc_btwrite_timeout..
,09-13 14:18:27.816  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
09-13 14:18:27.816  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:27.816  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:27.826  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.826  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.826  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.826  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:18:27.826  6650  6946 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:18:27.826  6650  6946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:27.826  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.836  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.836  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:27.836  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:27.836  6650  6946 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:27.836  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.836  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:18:27.836  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 14:18:27.836  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 7C F9 0E 34 8A A0
09-13 14:18:27.836  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:27.836  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:27.836  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:27.836  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.836  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.836  6650  6714 D BluetoothLeAdvertiser: start advertising
,09-13 14:18:27.836  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.836  2438  2458 D BtGatt.GattService: registerClient() - UUID=e0cf9a9d-4c49-4730-8762-9fe6423f8127
,09-13 14:18:27.886  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=e0cf9a9d-4c49-4730-8762-9fe6423f8127, clientIf=6
,09-13 14:18:27.886  6650  6661 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:27.886  2438  2921 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:18:27.886  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:27.886  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:27.886  2438  2651 D BtGatt.AdvertiseManager: message : 0
09-13 14:18:27.886  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:18:27.886  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:27.886  2438  2651 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:18:27.886  2438  2651 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:18:27.886  2438  2651 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:18:27.886  2438  2651 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:18:27.896  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.896  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.896  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
09-13 14:18:27.896   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{9ed379: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.896  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:27.896  2438  2680 D bt_vendor: op for 7
,09-13 14:18:27.896  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.896  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.896  2438  2617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-13 14:18:27.896  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 20
,09-13 14:18:27.896  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562818
09-13 14:18:27.896  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:18:27.896  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:27.896  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:27.896  2438  2651 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:27.896  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.896  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.896  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.896  2438  2617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:18:27.896   765  1633 V AlarmManager:  remove PendingIntent] PendingIntent{a518be: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.896  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:18:27.896  2438  2651 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:18:27.896  2438  2651 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 14:18:27.896  2438  2651 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:18:27.896  6650  6660 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:18:27.896  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:27.896  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:27.906  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:27.906  6650  6714 I io.jxcore.node.ConnectionHelper: start: OK
09-13 14:18:27.906  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:27.906  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:18:27.906  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:27.906  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:27.906  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:27.906  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:27.906   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{4c99d1f: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.906  6650  6650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 14:18:27.906  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:27.906  6650  6714 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 14:18:27.906  6650  6714 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 14:18:27.906  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 14:18:27.906  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 14:18:27.906  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:27.906  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:27.906  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:27.906  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:27.906  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:27.906  6650  6946 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:27.906  6650  6946 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:27.906  6650  6946 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 14:18:27.906  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:27.906  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:27.906  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:27.906  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:27.906  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 14:18:27.906  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 14:18:27.916  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.916   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{cb1886c: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.916  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.916  6650  6714 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:27.916  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:27.916  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:27.916  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:27.916  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.916  6650  6714 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:27.916   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{eb02e35: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.916   765  1653 V AlarmManager:  remove PendingIntent] PendingIntent{11602ca: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.916  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:27.916  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:27.916  2438  2651 D BtGatt.AdvertiseManager: message : 1
09-13 14:18:27.916  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
09-13 14:18:27.916  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:27.916  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:27.916  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
09-13 14:18:27.916  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
09-13 14:18:27.916  2438  2651 D BtGatt.AdvertiseManager: stop advertise for client =  6
09-13 14:18:27.916  2438  2651 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:18:27.916  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 14:18:27.916  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.916  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.926  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.926  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.926  2438  2617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 14:18:27.926  2438  2617 D BtGatt.GattService: Client app is not null!
,09-13 14:18:27.926  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.926  2438  2680 D bt_upio : BT_WAKE is asserted already
09-13 14:18:27.926  6650  6702 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:27.926  2438  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 14:18:27.926  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.926  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.926  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:27.926  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 14:18:27.926  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:27.926  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:18:27.926  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:27.926  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:27.926   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{d74ec3b: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.926  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:27.926  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:27.926  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:27.926  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:27.926  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 14:18:27.926  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 14:18:27.926  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 14:18:27.926  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:27.926  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:27.926  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:27.936  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.936  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.936   765  2530 V AlarmManager:  remove PendingIntent] PendingIntent{b64bf58: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.936  6650  6714 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.936  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
,09-13 14:18:27.936  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.936  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.936  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.936   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{24278b1: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.936  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.936  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:27.936  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.936  6650  6714 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:27.936  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.936  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.936  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.936  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:27.946  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.946  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.946  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.946  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 14:18:27.946   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{f98196: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.946  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.946  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
,09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.946  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.946  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.946  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:27.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 14:18:27.946   765  1633 V AlarmManager:  remove PendingIntent] PendingIntent{fbc1117: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:27.946  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.946  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.946  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.946  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.946  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.946  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.946  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:27.946  6650  6714 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-13 14:18:27.946  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:27.956  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:27.956   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{f127904: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.956  6650  6714 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 14:18:27.956  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 14:18:27.956  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 14:18:27.956  6650  6714 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:27.956  6650  6714 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 14:18:27.956  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:27.956  6650  6714 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:27.956  6650  6714 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 14:18:27.956  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:27.956  6650  6714 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 14:18:27.956  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 14:18:27.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 14:18:27.966  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 14:18:27.966  6650  6714 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 14:18:27.966  6650  6714 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 14:18:27.966  6650  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1052)
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.966  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 14:18:27.966  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.966  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.966  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.966  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.966  6650  6962 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1052
09-13 14:18:27.966  6650  6714 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 14:18:27.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.966  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.976  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.976  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.976  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.976  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.976  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.976  6650  6714 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 14:18:27.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.976  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.976  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.976  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.976  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.976  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.976  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.976  6650  6961 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-13 14:18:27.976  6650  6961 D BluetoothSocket: connect(): myUserId = 0
09-13 14:18:27.976  6650  6961 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 14:18:27.976  6650  6714 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:27.976  6650  6714 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:27.976  6650  6714 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 14:18:27.976  6650  6714 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 14:18:27.976  6650  6714 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 14:18:27.976  6650  6714 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 14:18:27.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:27.976  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.976  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.976  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:27.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:27.976  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:27.976  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:27.976  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:27.976  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:27.976  6650  6714 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 14:18:27.986  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.986   765  2530 D SecContentProvider: insert(), uri = 2
09-13 14:18:27.986  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.986  2438  2680 D bt_vendor: op for 7
09-13 14:18:27.986  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:27.986  2438  2680 D bt_upio : BT_WAKE is asserted already
09-13 14:18:27.986  2438  2838 W bt_btif : bta_dm_acl_change(), event : 2
09-13 14:18:27.986   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{ec02170: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:27.986  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 14:18:27.996  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:27.996   765  2490 V AlarmManager:  remove PendingIntent] PendingIntent{e9e8ce9: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:27.996  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:27.996  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 14:18:27.996  6650  6714 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 14:18:27.996  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:27.996  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 14:18:27.996  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 14:18:27.996  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:27.996  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:27.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 14:18:27.996  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:28.006  6650  6963 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:18:28.006  6650  6963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 14:18:28.006  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 14:18:28.006  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 14:18:28.006  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 14:18:28.006  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 14:18:28.006  6650  6963 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 14:18:28.006  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.006  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.006  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.006  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 14:18:28.006  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.016  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.016  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:28.016  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 14:18:28.016  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.016  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 14:18:28.016  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 14:18:28.016  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 7C F9 0E 34 8A A0
09-13 14:18:28.016  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:28.016  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:28.016  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 14:18:28.016  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.016  6650  6714 D BluetoothAdapter: STATE_ON
09-13 14:18:28.016  6650  6714 D BluetoothLeAdvertiser: start advertising
09-13 14:18:28.016  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:28.016  2438  2460 D BtGatt.GattService: registerClient() - UUID=2288546f-0705-4510-9f03-da63bb3b8588
,09-13 14:18:28.066  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=2288546f-0705-4510-9f03-da63bb3b8588, clientIf=6
,09-13 14:18:28.066  6650  6661 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:28.066  2438  2892 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:18:28.066  2438  2892 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:28.066  2438  2892 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:28.066  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:18:28.066  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:28.066  2438  2651 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:28.066  2438  2651 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:18:28.076  2438  2680 D bt_vendor: op for 7
09-13 14:18:28.076  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:28.076  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:28.076   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{24a0ea5: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:28.076  2438  2680 D bt_vendor: op for 7
09-13 14:18:28.076  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:28.076  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:28.076  2438  2617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:18:28.076  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 21
,09-13 14:18:28.076  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562818
09-13 14:18:28.076  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:18:28.076  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:28.076  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: starting multi advertising
09-13 14:18:28.076  2438  2680 D bt_vendor: op for 7
09-13 14:18:28.076  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:28.076  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:28.076  2438  2617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:18:28.076  2438  2651 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 14:18:28.076  2438  2651 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 14:18:28.086  6650  6702 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:18:28.086  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:28.086  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:28.086   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{29cb27a: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.086  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:28.086   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{f755a2b: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.086  6650  6714 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 14:18:28.086  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 14:18:28.086  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:18:28.086  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:28.086  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:28.086  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:28.086  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:28.096   765  2525 V AlarmManager:  remove PendingIntent] PendingIntent{eb2ae88: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.096  6650  6650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:28.096  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:28.096   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{871f021: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.096   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{a337c46: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.306   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
09-13 14:18:28.306   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
09-13 14:18:28.306   305  1182 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,09-13 14:18:28.366   765  3518 D SSRM:n  : SIOP:: AP = 400, PST = 447, CUR = 300, LCD = 0
,09-13 14:18:28.366   765  3518 D M       : limitCPUFreq:: freq = -1
,09-13 14:18:28.376   765  3518 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 765  tag : SIOP_ARM_MAX@25
,09-13 14:18:28.376   765  3518 D M       : limitGPUFreq:: freq = -1
,09-13 14:18:28.376   765  3518 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,09-13 14:18:28.386  2879  2879 D ContentApp:  LEVEL : 1
,09-13 14:18:28.406   765   839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bed6e07 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{39ca6b 6880:com.sec.android.app.videoplayer/u0a53}
,09-13 14:18:28.426   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:18:28.436  6880  6880 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 14:18:28.436  6880  6880 D TranscodeReceiver:  SIOP_LEVEL: 1
,09-13 14:18:28.596  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:18:28.596  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:28.596  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:28.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:28.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:28.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 14:18:28.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:28.596  6650  6963 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:28.596  6650  6963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:28.596  6650  6963 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:28.596  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:28.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 14:18:28.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:28.596  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 14:18:28.596  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:28.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:28.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:28.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 14:18:28.596  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:18:28.606  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:18:28.606  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:28.606  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:28.606  6650  6714 D BluetoothLeScanner: could not find callback wrapper
09-13 14:18:28.606  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 14:18:28.606  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:28.606  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:28.606  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:28.606  6650  6714 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:28.606  2438  2460 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:28.606  2438  2460 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:28.616  2438  2651 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:28.616  2438  2651 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 14:18:28.616  2438  2651 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:18:28.616  2438  2680 D bt_vendor: op for 7
,09-13 14:18:28.616  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:28.616  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:28.616  2438  2680 D bt_vendor: op for 7
,09-13 14:18:28.616  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:28.616  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:28.616  2438  2617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 14:18:28.616  2438  2680 D bt_vendor: op for 7
09-13 14:18:28.616  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:28.616  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:28.616  2438  2617 D BtGatt.GattService: Client app is not null!
,09-13 14:18:28.616  6650  6660 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:28.616  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 14:18:28.616  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 14:18:28.616  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:28.616  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 14:18:28.626  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:28.626  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 14:18:28.626   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{c082b34: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.626   765  2490 V AlarmManager:  remove PendingIntent] PendingIntent{adc6d5d: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.636   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{c1b16d2: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.636   765  1653 V AlarmManager:  remove PendingIntent] PendingIntent{e8e3a3: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.646   765  2529 V AlarmManager:  remove PendingIntent] PendingIntent{b96c6a0: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.646  2438  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 14:18:28.656  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 14:18:28.656  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:28.656  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:28.656  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:28.656  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:28.656  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:28.656  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:28.656  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:28.656  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:28.666   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{f778259: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:28.666  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:28.666  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.666  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:28.666  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
,09-13 14:18:28.666  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:28.666  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:28.666  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:28.666  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:28.666  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:28.676  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:28.676  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 14:18:28.676  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:28.676  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 14:18:28.676  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 14:18:28.676  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:28.676  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 14:18:28.676  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 14:18:28.676  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:28.676  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 14:18:28.686  6650  6980 D BluetoothSocket: bindListen(): myUserId = 0
09-13 14:18:28.686  6650  6980 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:28.686  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:28.686  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:28.686  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:28.686  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:28.686  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:28.686  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:28.686  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:28.686  6650  6980 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 14:18:28.686  6650  6980 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 14:18:28.686  6650  6980 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:28.686  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:28.686  6650  6714 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 14:18:28.686  6650  6714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 14:18:28.686  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 14:18:28.686  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:28.686  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:28.686  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 14:18:28.686  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 14:18:28.686  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:28.686  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:28.686  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:28.686  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:28.686  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:28.686  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.686  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:28.696  2438  2878 D bt_upio : ..proc_btwrite_timeout..
09-13 14:18:28.696  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:28.696  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:28.696  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.696  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:28.696  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
09-13 14:18:28.696  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:28.696  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:28.696  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:28.696  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.696  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:28.696  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:28.696  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:28.696  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:28.696  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c90200a not in the list
,09-13 14:18:28.696  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:28.696  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4dce07b not in the list
09-13 14:18:28.696  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:28.696  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:28.696  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:28.696  6650  6714 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-13 14:18:28.696  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 14:18:28.706  6650  6714 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 14:18:28.706  6650  6714 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 14:18:28.706  6650  6714 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:28.706  6650  6714 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 14:18:28.706  6650  6714 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 14:18:28.706  6650  6714 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 14:18:28.706   765  1776 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 14:18:28.706   765  1776 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4336, temperature: 331, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
09-13 14:18:28.706   765  1776 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
09-13 14:18:28.706   765  1776 D BatteryService: stay LED for charging
09-13 14:18:28.706   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 14:18:28.716   765   765 I MotionRecognitionService: Plugged
09-13 14:18:28.716   765   765 D MotionRecognitionService:   cableConnection= 1
09-13 14:18:28.716   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
09-13 14:18:28.716   765   765 D MotionRecognitionService: skip setTransmitPower. 
,09-13 14:18:28.716  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:18:28.716  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
09-13 14:18:28.716  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 14:18:28.716  6650  6982 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 14:18:28.716  6650  6982 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:18:28.726   305  1186 D EnterpriseController: netId is 0
09-13 14:18:28.726   305  1186 D Netd    : getNetworkForDns: using netid 502 for uid 10004
,09-13 14:18:28.726  6650  6982 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 14:18:28.726  6650  6984 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 14:18:28.726  6650  6982 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:28.726  2438  2438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 14:18:28.726  6650  6982 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:28.726  2438  2893 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:28.726  6650  6984 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 14:18:28.726  6650  6982 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:28.726  6650  6984 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 14:18:28.726  6650  6982 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 14:18:28.726  6650  6997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1105, name: OutgoingSocketThread/Sender)
,09-13 14:18:28.726  6650  6984 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:28.736  6650  6998 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1106, name: OutgoingSocketThread/Receiver)
09-13 14:18:28.736  6650  6984 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 14:18:28.736  6650  6999 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1107, name: IncomingSocketThread/Sender)
09-13 14:18:28.736  6650  6998 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1106, thread name: OutgoingSocketThread/Receiver)
,09-13 14:18:28.736  6650  6998 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 14:18:28.736  6650  6998 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1106, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 14:18:28.736  6650  7000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1108, name: IncomingSocketThread/Receiver)
,09-13 14:18:28.736  6650  7000 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1108, thread name: IncomingSocketThread/Receiver)
09-13 14:18:28.736  6650  7000 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:28.736  6650  7000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1108, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 14:18:28.736  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:28.736  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 14:18:28.736  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:29.196  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 14:18:29.206   765  1584 E Watchdog: !@Sync 4 [09-13 14:18:29.219]
,09-13 14:18:29.236  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 14:18:29.246  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 14:18:29.256  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bbf85a Bundle[{}]
,09-13 14:18:29.266  6650  6714 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 14:18:29.266  6650  6714 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 14:18:29.266  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 14:18:29.276  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 14:18:29.276  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 14:18:29.276  6650  6714 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 14:18:29.296  6650  7011 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 14:18:29.296  6650  7011 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 14:18:29.736   765  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 14:18:29.816  6650  7011 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 14:18:29.816  6650  7011 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 14:18:29.816  6650  7011 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:29.816  6650  7011 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:29.826  6650  7011 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 14:18:29.826  6650  7013 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 14:18:29.836  6650  7013 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 14:18:29.836  6650  7013 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:29.836  6650  7013 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:29.846  6650  7016 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1120, name: OutgoingSocketThread/Receiver)
,09-13 14:18:29.846  6650  7013 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 14:18:29.866  6650  7016 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1120, thread name: OutgoingSocketThread/Receiver)
,09-13 14:18:29.876  6650  7017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1121, name: IncomingSocketThread/Sender)
,09-13 14:18:29.876  6650  7015 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1119, name: OutgoingSocketThread/Sender)
,09-13 14:18:29.876  6650  7018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1122, name: IncomingSocketThread/Receiver)
,09-13 14:18:29.876  6650  7016 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 14:18:29.876  6650  7016 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1120, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 14:18:29.876  6650  7018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1122, thread name: IncomingSocketThread/Receiver)
,09-13 14:18:29.876  6650  7018 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 14:18:29.876  6650  7018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1122, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 14:18:30.116  2438  2680 D bt_vendor: op for 7
,09-13 14:18:30.126   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{96fce1e: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:30.126  2438  2680 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:30.126  2438  2680 D bt_upio : BT_WAKE is de-asserted already
,09-13 14:18:30.216  1674  1779 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,09-13 14:18:30.326  6650  6714 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1131)
,09-13 14:18:30.326  6650  6714 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 14:18:30.326  6650  6714 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1132)
,09-13 14:18:30.346  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 14:18:30.346  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f7dc8 added. We now have 4 listener(s)
,09-13 14:18:30.356  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,09-13 14:18:30.356  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 14:18:30.356  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 14:18:30.356  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 14:18:30.356  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bae61 added. We now have 4 listener(s)
09-13 14:18:30.356  6650  6714 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 14:18:30.356  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 14:18:30.366  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:30.376  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 14:18:30.376  6650  6714 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 14:18:30.376  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.376  6650  6714 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 14:18:30.376  6650  6714 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 14:18:30.386  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:30.386  6650  6650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 14:18:30.386  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.386  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:30.386  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:30.386  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:30.386  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 14:18:30.396  6650  6714 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f7dc8 removed from the list
,09-13 14:18:30.396  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:30.396  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bae61 removed from the list
,09-13 14:18:30.396  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:30.396  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:30.396  6650  6714 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-13 14:18:30.396  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 14:18:30.396  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:30.396  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 14:18:30.396  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:30.396  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:30.406  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:30.406  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:30.406  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 14:18:30.406  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:18:30.416  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:30.416  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 14:18:30.416  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:30.416  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:30.416  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:30.416  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:30.426  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.426  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.426  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.426  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:30.426  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.426  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.426  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:30.426  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:30.426  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.436  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:18:30.436  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 14:18:30.436  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 7C F9 0E 34 8A A0
,09-13 14:18:30.436  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:30.436  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 14:18:30.436  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:30.436  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.436  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.436  6650  6714 D BluetoothLeAdvertiser: start advertising
,09-13 14:18:30.436  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:30.436  2438  2921 D BtGatt.GattService: registerClient() - UUID=b31402fe-3a4e-4678-9c9e-64085e462265
,09-13 14:18:30.446  6650  7019 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 14:18:30.446  6650  7019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:30.446  6650  7019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:30.496  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=b31402fe-3a4e-4678-9c9e-64085e462265, clientIf=6
,09-13 14:18:30.496  6650  6702 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:30.496  2438  2458 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:18:30.496  2438  2458 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:30.496  2438  2458 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:30.496  2438  2651 D BtGatt.AdvertiseManager: message : 0
09-13 14:18:30.496  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
09-13 14:18:30.496  2438  2651 D BtGatt.AdvertiseManager: number of adv instance running = 0
09-13 14:18:30.496  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:30.496  2438  2651 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:18:30.496  2438  2651 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:18:30.496  2438  2651 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:18:30.496  2438  2680 D bt_vendor: op for 7
,09-13 14:18:30.496  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:30.496  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:30.496  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:30.496   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{3e62391: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:30.496  2438  2680 D bt_vendor: op for 7
09-13 14:18:30.496  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:30.496  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:30.506  2438  2617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:18:30.516   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{af982f6: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:30.516  2438  2651 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:30.526  2438  2680 D bt_vendor: op for 7
,09-13 14:18:30.526  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:30.526  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:30.526  2438  2617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 14:18:30.536  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 14:18:30.536  2438  2651 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 14:18:30.536  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 22
,09-13 14:18:30.536  2438  2651 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
,09-13 14:18:30.536   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{267e6f7: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:30.546  2438  2651 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,09-13 14:18:30.546  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562818
,09-13 14:18:30.546  6650  6660 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,09-13 14:18:30.546  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
,09-13 14:18:30.546  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 14:18:30.546  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:30.546  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 14:18:30.546  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:30.556  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:30.556   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{8a6c964: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:30.556  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:30.556  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 14:18:30.566  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 14:18:30.566  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:30.566  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 14:18:30.566  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:30.566  6650  6650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:30.566  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:30.566   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{7b867cd: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:31.066  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 14:18:31.066  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 14:18:31.066  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:31.306  2438  2878 D bt_upio : ..proc_btwrite_timeout..
,09-13 14:18:31.306  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:32.027  2438  2680 D bt_vendor: op for 7
,09-13 14:18:32.027  2438  2680 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:32.027  2438  2680 D bt_upio : BT_WAKE is de-asserted already
,09-13 14:18:32.037   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{eb2d882: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.587  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 14:18:33.587  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 14:18:33.587  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:18:33.587  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
,09-13 14:18:33.587  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
,09-13 14:18:33.597  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:33.597  6650  7019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:33.597  6650  7019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:33.597  6650  7019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:33.607  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:33.607  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:33.607  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 14:18:33.607  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 14:18:33.616  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 14:18:33.616  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 14:18:33.616  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 14:18:33.616  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:18:33.626  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.626  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.626  6650  6714 D BluetoothLeScanner: could not find callback wrapper
,09-13 14:18:33.636  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,09-13 14:18:33.636  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:33.646  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.646  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.646  6650  6714 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:33.646  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:33.646  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:33.657  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 14:18:33.657  2438  2651 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:33.657  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
09-13 14:18:33.657  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 14:18:33.657  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:33.657  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 14:18:33.657  2438  2651 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 14:18:33.657  2438  2651 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:18:33.657  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 14:18:33.657  2438  2680 D bt_vendor: op for 7
,09-13 14:18:33.667  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:33.667  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:33.667  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:33.667  2438  2680 D bt_vendor: op for 7
,09-13 14:18:33.667  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.667  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.667  2438  2680 D bt_vendor: op for 7
,09-13 14:18:33.667  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.667  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.677   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{6a9fb93: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.677  2438  2617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 14:18:33.677  2438  2617 D BtGatt.GattService: Client app is not null!
,09-13 14:18:33.677  6650  6661 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:33.677  2438  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:18:33.687   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{7b917d0: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:33.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:33.687  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 14:18:33.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 14:18:33.687  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:33.697  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:33.697  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 14:18:33.697  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:33.697  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:33.697   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{9f0b3c9: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.706  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:33.706  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:33.706  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:33.706  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 14:18:33.706  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:33.706   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{8b9face: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.706   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{aeebdef: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.716  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:33.716  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:33.716  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:33.716  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f7dc8 not in the list
09-13 14:18:33.716  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:33.716  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bae61 not in the list
,09-13 14:18:33.716  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:33.716  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:33.716  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:33.716  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 14:18:33.716  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 14:18:33.716  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 14:18:33.716  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 14:18:33.716  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:33.716  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:33.726  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:33.726  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:33.726  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.726  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.726  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.736  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:33.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.736  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:33.736  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:33.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.736  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.736  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 14:18:33.747  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.747  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.747  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 14:18:33.757  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 14:18:33.757  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 14:18:33.757  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 14:18:33.757  6650  6714 D BluetoothLeScanner: Start Scan
,09-13 14:18:33.757  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.757  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.757  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.757  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.757  2438  2892 D BtGatt.GattService: registerClient() - UUID=09d4da94-c0f5-4ee2-8053-524fdfbb7b3a
,09-13 14:18:33.796  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=09d4da94-c0f5-4ee2-8053-524fdfbb7b3a, clientIf=6
,09-13 14:18:33.796  6650  6661 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:33.806  2438  2921 D BtGatt.GattService: start scan with filters
,09-13 14:18:33.806  2438  2921 D BtGatt.GattService: getScanSettings
,09-13 14:18:33.806  2438  2921 D BtGatt.GattService: Is it foreground application = true
09-13 14:18:33.806  2438  2921 D BtGatt.GattService: not a background application
,09-13 14:18:33.816  2438  2921 D BtGatt.GattService: [GSIM LOG]: getActualScanMode (2/100 vs -2147483648/0)
,09-13 14:18:33.816  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
09-13 14:18:33.816  2438  2921 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:33.816  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_SCAN
09-13 14:18:33.816  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:33.827  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 14:18:33.827  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 14:18:33.827  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 14:18:33.827  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 14:18:33.827  2438  2652 D BtGatt.ScanManager: handling starting scan
,09-13 14:18:33.837  2438  2652 D BtGatt.ScanManager: isFilteringSupported
,09-13 14:18:33.837  2438  2652 D BluetoothAdapter: enableStandAloneBleMode=
,09-13 14:18:33.837  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 14:18:33.837  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:33.837  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 14:18:33.837  2438  2652 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.837  2438  2652 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.837  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:33.837  2438  2652 D BluetoothAdapter: STATE_ON
,09-13 14:18:33.847  2438  2652 D BluetoothAdapter: STATE_ON
09-13 14:18:33.847  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest : 46
09-13 14:18:33.847  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseScanCount : com.test.thalitest, com.test.thalitest
,09-13 14:18:33.847  2438  2652 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@feaa952
,09-13 14:18:33.847  2438  2680 D bt_vendor: op for 7
09-13 14:18:33.847  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.847  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.847  2438  2617 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 14:18:33.847  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:33.847   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{6134a0b: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.847  2438  2652 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-13 14:18:33.847  2438  2652 D BtGatt.ScanManager: High Rssi Filter value is = -128
09-13 14:18:33.847  2438  2652 D BtGatt.ScanManager: Low Rssi Filter value is = -128
09-13 14:18:33.847  2438  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0highRssiThreshold = -128lowRssiThreshold = -128matchmode is =2
,09-13 14:18:33.857  2438  2680 D bt_vendor: op for 7
09-13 14:18:33.857  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.857  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.857  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseScanCount 4 Battery : com.test.thalitest : 1598
,09-13 14:18:33.857  2438  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 14:18:33.857  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:33.857   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{64810e8: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:33.857  2438  2652 D BtGatt.ScanManager: Starting BLE batch scan
09-13 14:18:33.857  2438  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 14:18:33.857  2438  2680 D bt_vendor: op for 7
,09-13 14:18:33.857  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.857  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.857  2438  2680 D bt_vendor: op for 7
,09-13 14:18:33.857  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.866  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.866  2438  2617 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 14:18:33.866  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:33.866  2438  2680 D bt_vendor: op for 7
09-13 14:18:33.866  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:33.866  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562818
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: setRequestedScanType : com.test.thalitest : 2
,09-13 14:18:33.866  2438  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 14:18:33.866  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:33.866   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{d461301: PendingIntentRecord{5aa7be7 com.android.bluetooth broadcastIntent}}
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
,09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: setActualScanType : com.test.thalitest : 2
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,09-13 14:18:33.866  2438  2670 D BtGatt.GattService: [GSIM LOG]: setScanTime : com.test.thalitest : 24562818
,09-13 14:18:33.876   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{7015394: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.886   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{b7fde3d: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.896   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{b566632: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.896   765  1546 V AlarmManager:  remove PendingIntent] PendingIntent{398ef83: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.906   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{36a1500: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.906   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{4912139: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.916   765  1633 V AlarmManager:  remove PendingIntent] PendingIntent{500b37e: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:33.916   765  2525 V AlarmManager:  remove PendingIntent] PendingIntent{97100df: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:34.346  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 14:18:34.346  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 14:18:34.346  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:34.396  2438  2838 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-13 14:18:34.396  2438  2838 E bt_btif_sock_rfcomm: SDP - Failed to look up a channel number to connect to
,09-13 14:18:34.396  2438  2838 W bt_btif : bta_dm_acl_change(), event : 2
,09-13 14:18:34.406  2438  2838 W bt_btif : bta_dm_acl_change(), event : 5
,09-13 14:18:34.406  2438  2917 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
,09-13 14:18:34.416  6650  6961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1052)
,09-13 14:18:34.456  2438  2612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@feaa952
,09-13 14:18:34.466  2438  2617 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 1
,09-13 14:18:34.466  2438  2878 D bt_upio : ..proc_btwrite_timeout..
,09-13 14:18:34.466  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:34.466  2438  2617 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-13 14:18:34.466  2438  2617 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:55, value is empty for type: 241
,09-13 14:18:34.476  2862  2862 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,09-13 14:18:34.886   765  1237 V AlarmManager: Expired Alarm result :4
,09-13 14:18:34.886  2438  2438 D BtGatt.ScanManager: awakened up at time 156500
,09-13 14:18:34.906  2438  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 14:18:34.906  2438  2680 D bt_vendor: op for 7
,09-13 14:18:34.906  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:34.906  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:34.916  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:34.916  2438  2680 D bt_vendor: op for 7
,09-13 14:18:34.916  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:34.916  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:34.926  2438  2680 D bt_vendor: op for 7
,09-13 14:18:34.926  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:34.926  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:34.936  2438  2617 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=6
,09-13 14:18:34.936   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{8d997f5: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:34.936  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:34.936  2438  2617 D BtGatt.GattService: current time is 156549702652
,09-13 14:18:34.936  2438  2617 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 42, 109, -24, -126, 107, 89, 1, -128, -53, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -8, -49, -59, -39, -27, 97, 0, 71, -122, -77, 84, 69, -12, 1, -128, -76, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -81, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 94, -15, 90, -35, -8, -1, 1, -128, -78, 3, 0, 31, 2, 1, 6, 27, -1, 87, 1, 0, -83, 13, -95, -76, 72, -77, 105, 21, 82, 36, -118, 86, -70, 13, 118, -11, 2, -1, -8, -35, 90, -15, 94, 0]
,09-13 14:18:34.946   765  2529 V AlarmManager:  remove PendingIntent] PendingIntent{d70898a: PendingIntentRecord{5aa7be7 com.android.bluetooth broadcastIntent}}
,09-13 14:18:34.946  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 14:18:34.946  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:34.946  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.946  2438  2617 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -8, -49, -59, -39, -27, 97]
,09-13 14:18:34.946  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:34.946  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 14:18:34.946  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:34.956  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.956  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-13 14:18:34.956  2438  2617 D ScanRecord: parseFromBytes
09-13 14:18:34.956  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.956  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 14:18:34.956  2438  2617 D ScanRecord: parseFromBytes
09-13 14:18:34.956  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.956  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 27, -1, 87, 1, 0, -83, 13, -95, -76, 72, -77, 105, 21, 82, 36, -118, 86, -70, 13, 118, -11, 2, -1, -8, -35, 90, -15, 94]
,09-13 14:18:34.956  2438  2617 D ScanRecord: parseFromBytes
09-13 14:18:34.956  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.956  6650  6702 D ScanRecord: parseFromBytes
,09-13 14:18:34.956  6650  6702 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.966  6650  6702 D ScanRecord: parseFromBytes
09-13 14:18:34.966  6650  6702 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.966  6650  6702 D ScanRecord: parseFromBytes
09-13 14:18:34.966  6650  6702 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.966  2438  2612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@feaa952
,09-13 14:18:34.966  6650  6702 D ScanRecord: parseFromBytes
,09-13 14:18:34.966  6650  6702 D ScanRecord: parseFromBytes
09-13 14:18:34.966  6650  6702 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.966  6650  6702 D ScanRecord: parseFromBytes
09-13 14:18:34.966  6650  6702 D ScanRecord: first manudata for manu ID
,09-13 14:18:34.976  6650  6650 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61 5], added - the peer count is 1
,09-13 14:18:34.976  6650  6650 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61 5], Bluetooth address: F8:CF:C5:D9:E5:61, device name: '', device address: ''
,09-13 14:18:35.006   765   839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d8ecbfb u0 com.samsung.android.providers.context.log.action.USE_APP_FEATURE_SURVEY qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{5561b7f 2484:com.samsung.android.providers.context/u0a174}
,09-13 14:18:35.016   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{7158418: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:35.016   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{4f8be71: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:35.016   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{455b456: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:35.026   765  2525 V AlarmManager:  remove PendingIntent] PendingIntent{5f42cd7: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:35.026   765  2530 V AlarmManager:  remove PendingIntent] PendingIntent{3eac9c4: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:35.716  2438  2878 D bt_upio : ..proc_btwrite_timeout..
,09-13 14:18:35.716  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:35.966   765  1237 V AlarmManager: Expired Alarm result :4
,09-13 14:18:35.966  2438  2438 D BtGatt.ScanManager: awakened up at time 157578
,09-13 14:18:35.976  2438  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 14:18:35.976  2438  2680 D bt_vendor: op for 7
,09-13 14:18:35.976  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:35.976  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:35.986  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:35.986  2438  2680 D bt_vendor: op for 7
,09-13 14:18:35.986  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:35.986  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:35.996  2438  2680 D bt_vendor: op for 7
,09-13 14:18:35.996  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:35.996  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:36.006  2438  2617 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=8
,09-13 14:18:36.006  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:36.006  2438  2617 D BtGatt.GattService: current time is 157617088741
,09-13 14:18:36.006  2438  2617 D BtGatt.GattService: Batch record : [42, 109, -24, -126, 107, 89, 1, -128, -31, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -8, -49, -59, -39, -27, 97, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -97, -64, -51, 5, -41, 72, 1, -128, -58, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -8, -49, -59, -39, -27, 97, 0, -97, -64, -51, 5, -41, 72, 1, -128, -60, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -8, -49, -59, -39, -27, 97, 0, 85, -113, -37, 31, -33, 8, 0, -128, -86, 2, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 116, -43, -111, -91, -20, -29, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -77, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 14:18:36.006   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{290bfe2: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.006  2438  2617 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -8, -49, -59, -39, -27, 97]
,09-13 14:18:36.006   765  1633 V AlarmManager:  remove PendingIntent] PendingIntent{ce4bf73: PendingIntentRecord{5aa7be7 com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.006  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:36.006  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-13 14:18:36.006  2438  2617 D ScanRecord: parseFromBytes
09-13 14:18:36.006  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.006  2438  2617 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -8, -49, -59, -39, -27, 97]
,09-13 14:18:36.006  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:36.016  2438  2617 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -8, -49, -59, -39, -27, 97]
,09-13 14:18:36.016  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:36.016  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-13 14:18:36.016  2438  2617 D ScanRecord: parseFromBytes
09-13 14:18:36.016  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.016  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 14:18:36.016  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:36.016  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.016  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 14:18:36.026  2438  2617 D ScanRecord: parseFromBytes
,09-13 14:18:36.026  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.026  2438  2617 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 14:18:36.026  2438  2617 D ScanRecord: parseFromBytes
09-13 14:18:36.026  2438  2617 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
,09-13 14:18:36.026  6650  6660 D ScanRecord: first manudata for manu ID
09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
,09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
09-13 14:18:36.026  6650  6660 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
09-13 14:18:36.026  6650  6660 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
09-13 14:18:36.026  6650  6660 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
09-13 14:18:36.026  6650  6660 D ScanRecord: first manudata for manu ID
,09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
09-13 14:18:36.026  6650  6660 D ScanRecord: parseFromBytes
,09-13 14:18:36.036  6650  6650 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61 6] updated - the peer count is 1
,09-13 14:18:36.036  6650  6650 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61 5] updated - the peer count is 1
,09-13 14:18:36.036  6650  6650 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> F8:CF:C5:D9:E5:61 5] updated - the peer count is 1
,09-13 14:18:36.036  6650  6650 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> F8:CF:C5:D9:E5:61 6], device name: '', device address: ''
,09-13 14:18:36.036  6650  6650 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> F8:CF:C5:D9:E5:61 5], device name: '', device address: ''
,09-13 14:18:36.046   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{5acbe30: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.056   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{59fcaa9: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}},
,09-13 14:18:36.056   765  2490 V AlarmManager:  remove PendingIntent] PendingIntent{c7ef82e: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.066   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{341dfcf: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.066   765  1613 V AlarmManager:  remove PendingIntent] PendingIntent{e578d5c: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.786  2438  2878 D bt_upio : ..proc_btwrite_timeout..,
,09-13 14:18:36.786  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1,
,09-13 14:18:36.866  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-13 14:18:36.866  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-13 14:18:36.866  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left,
,09-13 14:18:36.866  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f7dc8 not in the list,
,09-13 14:18:36.866  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-13 14:18:36.866  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,09-13 14:18:36.876  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,09-13 14:18:36.876  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,09-13 14:18:36.876  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
,09-13 14:18:36.886  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,09-13 14:18:36.886  6650  6714 D BluetoothAdapter: STATE_ON,
,09-13 14:18:36.896  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.896  6650  6714 D BluetoothLeScanner: Stop Scan
,09-13 14:18:36.906  2438  2892 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:36.906  2438  2892 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:36.906  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_SCAN
,09-13 14:18:36.906  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:36.906  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateScanTime: 0
09-13 14:18:36.906  2438  2892 D BtGatt.GattService: stopScan() - queue size =1
,09-13 14:18:36.916  2438  2652 D BtGatt.ScanManager: filter size is 1
,09-13 14:18:36.916  2438  2652 D BtGatt.ScanManager: delete FilterIndex - 3
,09-13 14:18:36.916  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 1 => 1
,09-13 14:18:36.916  2438  2680 D bt_vendor: op for 7
,09-13 14:18:36.916  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:36.916  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:36.916  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:36.916  2438  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 14:18:36.916   765  1633 V AlarmManager:  remove PendingIntent] PendingIntent{9816865: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.916  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:36.926   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{d06693a: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.926  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, A time : 1 => 1
,09-13 14:18:36.926  2438  2652 D BtGatt.ScanManager: stopping BLe Batch
,09-13 14:18:36.926  2438  2921 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:18:36.926  2438  2680 D bt_vendor: op for 7
,09-13 14:18:36.936  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:36.936  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:36.936  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_ACTUAL_DB
,09-13 14:18:36.936  2438  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-13 14:18:36.936  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 14:18:36.936  2438  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 14:18:36.936  2438  2680 D bt_vendor: op for 7
,09-13 14:18:36.936  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:36.936  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:36.936  2438  2617 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 14:18:36.936  2438  2617 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 14:18:36.936   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{ca6a9eb: PendingIntentRecord{5aa7be7 com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.946  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest at  BLE_SCAN_REQUESTED_DB
,09-13 14:18:36.946   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{17e2348: PendingIntentRecord{5aa7be7 com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 14:18:36.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:36.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 14:18:36.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 14:18:36.946  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 14:18:36.946  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:36.956  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.956  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.956  6650  6714 D BluetoothLeAdvertiser: stop advertising
09-13 14:18:36.956  6650  6714 D BluetoothLeAdvertiser: wrapper is null
09-13 14:18:36.956  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:36.956  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 14:18:36.956  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:36.956  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:36.956  6650  6714 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-13 14:18:36.956  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bae61 not in the list
09-13 14:18:36.956  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:36.956  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:36.956  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 14:18:36.956  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:36.956  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:36.956  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:36.956  6650  6714 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 14:18:36.956  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 14:18:36.966  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:36.966  6650  6714 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 14:18:36.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 14:18:36.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 14:18:36.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 14:18:36.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 14:18:36.966   765  1776 V AlarmManager:  remove PendingIntent] PendingIntent{32525e1: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.966  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 14:18:36.966  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 14:18:36.976  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 14:18:36.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 14:18:36.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 14:18:36.976  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 14:18:36.976  6650  6714 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 14:18:36.976  6650  6714 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 14:18:36.986  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.986   765  2490 V AlarmManager:  remove PendingIntent] PendingIntent{aed3f1d: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:36.986  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.986  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 14:18:36.996  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.996  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.996  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 14:18:36.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 14:18:36.996  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:36.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 14:18:36.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
09-13 14:18:36.996  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 7C F9 0E 34 8A A0
,09-13 14:18:36.996  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 14:18:36.996  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 52, -118, -96]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 14:18:36.996  6650  6714 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 14:18:36.996  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:37.006  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:37.006  6650  6714 D BluetoothLeAdvertiser: start advertising
,09-13 14:18:37.006  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:37.006  2438  2892 D BtGatt.GattService: registerClient() - UUID=cdab8d09-d3a8-4937-9407-baf4f88f51d2
,09-13 14:18:37.006   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{dace592: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.016   765  1321 V AlarmManager:  remove PendingIntent] PendingIntent{17c6b63: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.016  6650  7051 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 14:18:37.026  6650  7051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 14:18:37.026  6650  7051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 14:18:37.056  2438  2617 D BtGatt.GattService: onClientRegistered() - UUID=cdab8d09-d3a8-4937-9407-baf4f88f51d2, clientIf=6
,09-13 14:18:37.056  6650  6660 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 14:18:37.056  2438  2460 D BtGatt.GattService: [GSIM LOG]: startMultiAdvertising: 2
,09-13 14:18:37.056  2438  2460 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:37.056  2438  2460 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:37.056  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_START_ADV
,09-13 14:18:37.056  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:37.056  2438  2651 D BtGatt.AdvertiseManager: message : 0
,09-13 14:18:37.056  2438  2651 D BtGatt.AdvertiseManager: number of adv instance running = 0
,09-13 14:18:37.056  2438  2651 D BtGatt.AdvertiseManager: size of list is =0
,09-13 14:18:37.066  2438  2651 D BtGatt.AdvertiseManager: starting advertising
,09-13 14:18:37.066  2438  2651 D BtGatt.AdvertiseManager: isStandardAdv = false
,09-13 14:18:37.066  2438  2680 D bt_vendor: op for 7
09-13 14:18:37.066  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:37.066  2438  2680 D bt_upio : BT_WAKE is asserted already
09-13 14:18:37.066  2438  2670 D BtGatt.GattService: [GSIM LOG]: increaseAdvCount : com.test.thalitest : 23
09-13 14:18:37.066  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvTime : com.test.thalitest@LowLatency : 24562818
09-13 14:18:37.066  2438  2670 D BtGatt.GattService: [GSIM LOG]: setAdvType : com.test.thalitest@LowLatency : 2
09-13 14:18:37.066  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
09-13 14:18:37.066  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:37.066   765   783 V AlarmManager:  remove PendingIntent] PendingIntent{c441360: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
09-13 14:18:37.066  2438  2680 D bt_vendor: op for 7
09-13 14:18:37.066  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:37.066  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:37.066  2438  2617 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 14:18:37.066  2438  2651 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 14:18:37.066  2438  2680 D bt_vendor: op for 7
09-13 14:18:37.066  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:37.066  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:37.066  2438  2617 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-13 14:18:37.066  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-13 14:18:37.066  2438  2651 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-13 14:18:37.066  2438  2651 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
09-13 14:18:37.066  2438  2651 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
09-13 14:18:37.066  6650  6661 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
09-13 14:18:37.066  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 14:18:37.066  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 14:18:37.076  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 14:18:37.076  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:37.076  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 14:18:37.076  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 14:18:37.076  6650  6650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 14:18:37.076  6650  6650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 14:18:37.076  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 14:18:37.076   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{323b019: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.076  6650  6650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:37.076  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 14:18:37.076   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{22fc8de: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.086   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{7405abf: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.086   765  1546 V AlarmManager:  remove PendingIntent] PendingIntent{c7058c: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.086   765  1653 V AlarmManager:  remove PendingIntent] PendingIntent{eb634d5: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:37.586  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 14:18:37.586  6650  6650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 14:18:37.586  6650  6650 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 14:18:37.727  2438  2878 D bt_upio : ..proc_btwrite_timeout..
,09-13 14:18:37.727  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:38.486   765  3518 D SSRM:n  : SIOP:: AP = 390, PST = 438, CUR = 300, LCD = 0
,09-13 14:18:38.576  2438  2680 D bt_vendor: op for 7
,09-13 14:18:38.576  2438  2680 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:38.576  2438  2680 D bt_upio : BT_WAKE is de-asserted already
,09-13 14:18:38.576   765  2525 V AlarmManager:  remove PendingIntent] PendingIntent{96b94ea: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:38.997   765  2530 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 14:18:38.997   765  2530 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4375, temperature: 332, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,09-13 14:18:39.007   765  2530 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,09-13 14:18:39.007   765  2530 D BatteryService: stay LED for charging
,09-13 14:18:39.007   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 14:18:39.017   765   765 I MotionRecognitionService: Plugged
,09-13 14:18:39.017   765   765 D MotionRecognitionService:   cableConnection= 1
,09-13 14:18:39.017   765   765 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,09-13 14:18:39.027   765   765 D MotionRecognitionService: skip setTransmitPower. 
,09-13 14:18:39.036  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:18:39.036  1383  1383 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,09-13 14:18:39.046  1383  1383 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 14:18:39.066  2438  2438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 14:18:39.066  2438  2893 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-13 14:18:39.076  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:39.076  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:39.076  1383  1383 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 14:18:40.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:40.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 14:18:40.596  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 14:18:40.597  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 14:18:40.597  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 14:18:40.597  6650  6714 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 14:18:40.597  6650  6650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 14:18:40.607  6650  7051 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 14:18:40.607  6650  7051 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 14:18:40.607  6650  7051 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 14:18:40.617  6650  6650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 14:18:40.617  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f7dc8 not in the list
,09-13 14:18:40.617  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 14:18:40.617  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 14:18:40.617  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 14:18:40.617  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,09-13 14:18:40.627  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 14:18:40.627  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:40.636  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:40.636  6650  6714 D BluetoothLeScanner: could not find callback wrapper
,09-13 14:18:40.636  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 14:18:40.636  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 14:18:40.646  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:40.646  6650  6714 D BluetoothAdapter: STATE_ON
,09-13 14:18:40.646  6650  6714 D BluetoothLeAdvertiser: stop advertising
,09-13 14:18:40.646  2438  2458 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:40.646  2438  2458 D BtGatt.GattService: [GSIM LOG]: getCallingProcessName: com.test.thalitest
,09-13 14:18:40.656  2438  2651 D BtGatt.AdvertiseManager: message : 1
,09-13 14:18:40.656  2438  2651 D BtGatt.AdvertiseManager: stop advertise for client =  6
,09-13 14:18:40.656  2438  2651 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,09-13 14:18:40.656  2438  2680 D bt_vendor: op for 7
,09-13 14:18:40.656  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
,09-13 14:18:40.656  2438  2651 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 14:18:40.656  2438  2670 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.test.thalitest, msg: MESSAGE_STOP_ADV
,09-13 14:18:40.656  2438  2680 D bt_upio : upio_start_stop_timer : timer_settime success
,09-13 14:18:40.656  2438  2680 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,09-13 14:18:40.666   765  1253 V AlarmManager:  remove PendingIntent] PendingIntent{129e3db: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:40.666  2438  2680 D bt_vendor: op for 7
,09-13 14:18:40.666  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:40.666  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:40.666  2438  2617 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 14:18:40.666  2438  2617 D BtGatt.GattService: Client app is not null!
,09-13 14:18:40.666  6650  6702 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,09-13 14:18:40.666  2438  2680 D bt_vendor: op for 7
,09-13 14:18:40.676  2438  2680 D bt_upio : upio_set : pio 0 action 2, polarity 1
09-13 14:18:40.676  2438  2680 D bt_upio : BT_WAKE is asserted already
,09-13 14:18:40.676  2438  2892 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 14:18:40.676   765  2526 V AlarmManager:  remove PendingIntent] PendingIntent{8a4ee78: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:40.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 14:18:40.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 14:18:40.687  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 14:18:40.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 14:18:40.687  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 14:18:40.687   765  1635 V AlarmManager:  remove PendingIntent] PendingIntent{7b24951: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:40.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:40.687  6650  6714 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 14:18:40.687  6650  6714 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 14:18:40.697  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:40.697  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bae61 not in the list
,09-13 14:18:40.697  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:40.697  6650  6650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 14:18:40.697  6650  6650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 14:18:40.697  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
09-13 14:18:40.697  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 14:18:40.697  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:40.697  6650  6714 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 14:18:40.697  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:40.697  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 14:18:40.697  6650  6714 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f7dc8 not in the list
,09-13 14:18:40.697  6650  6714 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 14:18:40.697  6650  6714 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6bae61 not in the list
,09-13 14:18:40.697  6650  6714 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 14:18:40.707  6650  6714 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 14:18:40.707  6650  6714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 14:18:40.707  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 14:18:40.707  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything,
09-13 14:18:40.707   765  2529 V AlarmManager:  remove PendingIntent] PendingIntent{ee615b6: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:40.707  2438  2670 D BtGatt.GattService: [GSIM LOG]: gsimLogHandler: prevDate: 13, currDate: 13
,09-13 14:18:40.707  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 14:18:40.707  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 14:18:40.707  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 14:18:40.707  6650  6714 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 14:18:40.707  2438  2670 D BtGatt.GattService: [GSIM LOG]: updateAdvTime
,09-13 14:18:40.707  2438  2670 D BtGatt.GattService: [GSIM LOG]: com.test.thalitest@LowLatency, R time : 0 => 0
,09-13 14:18:40.716  2438  2670 D BtGatt.GattService: [GSIM LOG]: remove : com.test.thalitest@LowLatency at  BLE_ADV_REQUESTED_DB
,09-13 14:18:40.716   765   786 V AlarmManager:  remove PendingIntent] PendingIntent{358e2b7: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:40.726  6650  7079 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1152, name: My test thread name)
,09-13 14:18:41.207  6650  6650 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 14:18:41.467  2438  2878 D bt_upio : ..proc_btwrite_timeout..
,09-13 14:18:41.467  2438  2878 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:42.186  2438  2680 D bt_vendor: op for 7
,09-13 14:18:42.186  2438  2680 D bt_upio : upio_set : pio 0 action 1, polarity 1
,09-13 14:18:42.186  2438  2680 D bt_upio : BT_WAKE is de-asserted already
,09-13 14:18:42.186   765  1777 V AlarmManager:  remove PendingIntent] PendingIntent{2767a24: PendingIntentRecord{77e4e8d com.android.bluetooth broadcastIntent}}
,09-13 14:18:42.736  6650  6714 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1152
,09-13 14:18:42.736  6650  6714 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1152, name: My test thread name)
,09-13 14:18:42.736  6650  7080 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1153, name: My test thread name)
,09-13 14:18:42.736  6650  7080 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1153, thread name: My test thread name)
,09-13 14:18:42.736  6650  7080 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1153, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 14:18:42.746  6650  6714 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 14:18:42.767  6650  7081 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1157, name: My test thread name)
,09-13 14:18:42.767  6650  7081 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1157, thread name: My test thread name): Test exception.
,09-13 14:18:42.767  6650  7081 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1157, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 14:18:42.777  6650  6714 I jxcore-log: Total number of executed tests:  76
09-13 14:18:42.777  6650  6714 I jxcore-log: 
,09-13 14:18:42.777  6650  6714 I jxcore-log: Number of passed tests:  76
09-13 14:18:42.777  6650  6714 I jxcore-log: 
,09-13 14:18:42.777  6650  6714 I jxcore-log: Number of failed tests:  0
09-13 14:18:42.777  6650  6714 I jxcore-log: 
,09-13 14:18:42.777  6650  6714 I jxcore-log: Number of ignored tests:  0
09-13 14:18:42.777  6650  6714 I jxcore-log: 
,09-13 14:18:42.777  6650  6714 I jxcore-log: Total duration:  15995
09-13 14:18:42.777  6650  6714 I jxcore-log: 
,09-13 14:18:42.777  6650  6714 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 14:18:42.777  6650  6714 I jxcore-log: 
,09-13 14:18:42.787  6650  6714 I jxcore-log: My device name is: samsung-SM-G900F
09-13 14:18:42.787  6650  6714 I jxcore-log: 
09-13 14:18:42.787  6650  6714 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 14:18:42.787  6650  6714 I jxcore-log: 
,09-13 14:18:42.796  6650  7079 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1152, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-13 14:18:42.796  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.796  6650  6714 I jxcore-log: 
,09-13 14:18:42.796  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.796  6650  6714 I jxcore-log: 
,09-13 14:18:42.796  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.796  6650  6714 I jxcore-log: 
,09-13 14:18:42.806  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.806  6650  6714 I jxcore-log: 
,09-13 14:18:42.806  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:42.806  6650  6714 I jxcore-log: 
,09-13 14:18:42.816  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.816  6650  6714 I jxcore-log: 
,09-13 14:18:42.816  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.816  6650  6714 I jxcore-log: 
,09-13 14:18:42.816  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:42.816  6650  6714 I jxcore-log: 
,09-13 14:18:42.816  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 14:18:42.816  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.826  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 14:18:42.826  6650  6714 I jxcore-log: 
,09-13 14:18:42.836  6650  6714 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 14:18:42.836  6650  6714 I jxcore-log: 
,09-13 14:18:43.706  2446  2446 E audit   : type=1400 msg=audit(1473769123.706:289): avc:  denied  { execmod } for  pid=7082 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 14:18:43.706  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,09-13 14:18:43.706  2446  2446 E audit   : type=1300 msg=audit(1473769123.706:289): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b4023000 a1=51000 a2=5 a3=4 items=0 ppid=3670 ppcomm=adbd pid=7082 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,09-13 14:18:43.706  2446  2446 E audit   : type=1327 msg=audit(1473769123.706:289): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
09-13 14:18:43.706  2446  2446 E audit   : type=1320 msg=audit(1473769123.706:289): 
,09-13 14:18:43.766  2446  2446 E audit   : type=1400 msg=audit(1473769123.766:290): avc:  denied  { execmod } for  pid=7082 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 14:18:43.766  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,09-13 14:18:43.766  2446  2446 E audit   : type=1300 msg=audit(1473769123.766:290): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe3000 a1=51000 a2=5 a3=4 items=0 ppid=3670 ppcomm=adbd pid=7082 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,09-13 14:18:43.766  2446  2446 E audit   : type=1327 msg=audit(1473769123.766:290): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
09-13 14:18:43.766  2446  2446 E audit   : type=1320 msg=audit(1473769123.766:290): 
,09-13 14:18:43.806  2446  2446 E audit   : type=1400 msg=audit(1473769123.806:291): avc:  denied  { execmod } for  pid=7082 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
09-13 14:18:43.806  2446  2446 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,09-13 14:18:43.806  2446  2446 E audit   : type=1300 msg=audit(1473769123.806:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fe3000 a1=51000 a2=5 a3=4 items=0 ppid=3670 ppcomm=adbd pid=7082 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
,09-13 14:18:43.806  2446  2446 E audit   : type=1327 msg=audit(1473769123.806:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
09-13 14:18:43.806  2446  2446 E audit   : type=1320 msg=audit(1473769123.806:291): 
,09-13 14:18:43.816  7082  7082 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 14:18:43.816  7082  7082 D AndroidRuntime: CheckJNI is OFF
,09-13 14:18:43.816  7082  7082 D AndroidRuntime: readGMSProperty: start
,09-13 14:18:43.816  7082  7082 D AndroidRuntime: readGMSProperty: already setted!!
09-13 14:18:43.816  7082  7082 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 14:18:43.816  7082  7082 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 14:18:43.816  7082  7082 D AndroidRuntime: readGMSProperty: end
,09-13 14:18:43.816  7082  7082 D AndroidRuntime: addProductProperty: start
,09-13 14:18:43.826  7082  7082 W art     : 6f8b2000-7062f000 rw-p 00000000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
,09-13 14:18:43.826  7082  7082 W art     : aee4a000-b1d70000 r--p 00000000 b3:17 14         /system/framework/arm/boot.oat
09-13 14:18:43.826  7082  7082 W art     : b1d70000-b3fdf000 r-xp 02f26000 b3:17 14         /system/framework/arm/boot.oat
09-13 14:18:43.826  7082  7082 W art     : b3fdf000-b3fe0000 rw-p 05195000 b3:17 14         /system/framework/arm/boot.oat
09-13 14:18:43.826  7082  7082 W art     : b3fe0000-b3fe1000 r--p 00000000 00:00 0          [anon:linker_alloc]
,09-13 14:18:43.826  7082  7082 W art     : b4324000-b4772000 r-xp 00000000 b3:17 946        /system/lib/libart.so
09-13 14:18:43.826  7082  7082 W art     : b4772000-b4773000 ---p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b4773000-b477d000 r--p 0044e000 b3:17 946        /system/lib/libart.so
09-13 14:18:43.826  7082  7082 W art     : b477d000-b477e000 rw-p 00458000 b3:17 946        /system/lib/libart.so
09-13 14:18:43.826  7082  7082 W art     : b477e000-b4780000 rw-p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
09-13 14:18:43.826  7082  7082 W art     : b4889000-b48b2000 r--p 00d7d000 b3:1a 130845     /data/dalvik-cache/arm/system@framework@boot.art
09-13 14:18:43.826  7082  7082 W art     : b48b2000-b48b5000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
09-13 14:18:43.826  7082  7082 W art     : b48b5000-b48b6000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
09-13 14:18:43.826  7082  7082 W art     : b48b6000-b48b7000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
,09-13 14:18:43.826  7082  7082 W art     : b48b7000-b48b8000 r--p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b48b8000-b48d8000 r--s 00000000 00:0b 6572       /dev/__properties__
09-13 14:18:43.826  7082  7082 W art     : b48d8000-b52e9000 r-xp 00000000 b3:17 322        /system/lib/libLLVM.so
09-13 14:18:43.826  7082  7082 W art     : b52e9000-b52ea000 ---p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b52ea000-b5333000 r--p 00a11000 b3:17 322        /system/lib/libLLVM.so
09-13 14:18:43.826  7082  7082 W art     : b5333000-b5334000 rw-p 00a5a000 b3:17 322        /system/lib/libLLVM.so
,09-13 14:18:43.826  7082  7082 W art     : b5334000-b533c000 rw-p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b533c000-b5371000 r-xp 00000000 b3:17 2785       /system/lib/libbcinfo.so
09-13 14:18:43.826  7082  7082 W art     : b5371000-b5372000 ---p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b5372000-b5373000 r--p 00035000 b3:17 2785       /system/lib/libbcinfo.so
09-13 14:18:43.826  7082  7082 W art     : b5373000-b5374000 rw-p 00036000 b3:17 2785       /system/lib/libbcinfo.so
,09-13 14:18:43.826  7082  7082 W art     : b5374000-b53cc000 r-xp 00000000 b3:17 2878       /system/lib/libbcc.so
09-13 14:18:43.826  7082  7082 W art     : b53cc000-b53cd000 ---p 00000000 00:00 0 
09-13 14:18:43.826  7082  7082 W art     : b53cd000-b53ce000 r--p 00058000 b3:17 2878       /system/lib/libbcc.so
09-13 14:18:43.826  7082  7082 W art     : b53ce000-b53cf000 rw-p 00059000 b3:17 2878       /system/lib/libbcc.so
09-13 14:18:43.826  7082  7082 W art     : b53d0000-b53d6000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungV
,09-13 14:18:43.826  7082  7082 W art     : AD_v01009.so
09-13 14:18:43.826  7082  7082 W art     : b53d6000-b53d7000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 14:18:43.826  7082  7082 W art     : b53d7000-b53d8000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
09-13 14:18:43.826  7082  7082 W art     : b53d8000-b53da000 rw-p 00000000 00:00 0 
,09-13 14:18:43.826  7082  7082 W art     : b53db000-b53e5000 r-xp 00000000 b3:17 1088 
09-13 14:18:43.836  7082  7082 W art     :       /system/lib/libcommon_time_client.so
09-13 14:18:43.836  7082  7082 W art     : b53e5000-b53e8000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
09-13 14:18:43.836  7082  7082 W art     : b53e8000-b53e9000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
,09-13 14:18:43.836  7082  7082 W art     : b53ea000-b5401000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 14:18:43.836  7082  7082 W art     : b5401000-b5402000 ---p 00000000 00:00 0 
,09-13 14:18:43.836  7082  7082 W art     : b5402000-b5403000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 14:18:43.836  7082  7082 W art     : b5403000-b5404000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
09-13 14:18:43.836  7082  7082 W art     : b5405000-b540f000 r-xp 00000000 b3:17 2671   
09-13 14:18:43.836  7082  7082 W art     :     /system/lib/libsec_km.so
,09-13 14:18:43.836  7082  7082 W art     : b540f000-b5410000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so,
09-13 14:18:43.836  7082  7082 W art     : b5410000-b5411000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
09-13 14:18:43.836  7082  7082 W art     : b5411000-b5415000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
,09-13 14:18:43.836  7082  7082 W art     : b5415000-b5416000 r--p 00003000 b
09-13 14:18:43.836  7082  7082 W art     : 3:17 2888       /system/lib/libSEF4MP4.so
09-13 14:18:43.836  7082  7082 W art     : b5416000-b5417000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
09-13 14:18:43.836  7082  7082 W art     : b5417000-b542d000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
,09-13 14:18:43.836  7082  7082 W art     : b542d000-b542e000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
09-13 14:18:43.836  7082  7082 W art     : b542e000-b542f000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
09-13 14:18:43.836  7082  7082 W art     : b542f000-b543c000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so,
09-13 14:18:43.836  7082  7082 W art     : b543c000-b543d000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,09-13 14:18:43.836  7082  7082 W art     : b543d000-b543e000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
09-13 14:18:43.836  7082  7082 W art     : b543e000-b549e000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
09-13 14:18:43.836  7082  7082 W art     : b549e000-b54a1000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
09-13 14:18:43.836  7082  7082 W art     : b54a1000-b54a5000 rw-p 00000000 00:00 0 
,09-13 14:18:43.836  7082  7082 W art     : b54a5000-b5506000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
09-13 14:18:43.836  7082  7082 W art     : b5506000-b5507000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
09-13 14:18:43.836  7082  7082 W art     : b5507000-b5556000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
09-13 14:18:43.836  7082  7082 W art     : b5556000-b5558000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
09-13 14:18:43.836  7082  7082 W art     : b5558000-b5559000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
09-13 14:18:43.836  7082  7082 W art     : b5559000-b555a000 rw-p 00000000 00:00 0 ,
09-13 14:18:43.836  7082  7082 W art     : b555a000-b5561000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 14:18:43.836  7082  7082 W art     : b5561000-b5562000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
09-13 14:18:43.836  7082  7082 W art     : b5562000-b5563000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
09-13 14:18:43.836  7082  7082 W art     : avc_common.so
09-13 14:18:43.836  7082  7082 W art     : b5564000-b5567000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,09-13 14:18:43.836  7082  7082 W art     : b5567000-b5568000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
09-13 14:18:43.836  7082  7082 W art     : b5568000-b5569000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
,09-13 14:18:43.836  7082  7082 W art     : enc_common.so
09-13 14:18:43.836  7082  7082 W art     : b556a000-b556e000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
09-13 14:18:43.836  7082  7082 W art     : b556e000-b556f000 ---p 00000000 00:00 0 
09-13 14:18:43.836  7082  7082 W art     : b556f000-b5570000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
09-13 14:18:43.836  7082  7082 W art     : b5570000-b5571000 rw-p 00005000 b3:17 2510       /syste
,09-13 14:18:43.836  7082  7082 W art     : m/lib/libpowermanager.so
09-13 14:18:43.836  7082  7082 W art     : b5572000-b558f000 r-xp 00000000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 14:18:43.836  7082  7082 W art     : b558f000-b5590000 r--p 0001c000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 14:18:43.836  7082  7082 W art     : b5590000-b5591000 rw-p 0001d000 b3:17 2795       /system/lib/libvorbisidec.so
09-13 14:18:43.836  7082  7082 W art     : b5592000-b5597000 r-xp 00000000 b3:17 2617       /system/lib/libstagefright_yuv.so
,09-13 14:18:43.836  7082  7082 W art     : b5597000-b5598000 r--p 00004000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 14:18:43.836  7082  7082 W art     : b5598000-b5599000 rw-p 00005000 b3:17 2617       /system/lib/libstagefright_yuv.so
09-13 14:18:43.836  7082  7082 W art     : b559a000-b55cb000 r-xp 00000000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 14:18:43.836  7082  7082 W art     : b55cb000-b55cc000 ---p 00000000 00:00 0 
09-13 14:18:43.836  7082  7082 W art     : b55cc000-b55cf000 r--p 00031000 b3:17 556        /system/lib/libstagefright_omx.so,
09-13 14:18:43.836  7082  7082 W art     : b55cf000-b55d0000 rw-p 00034000 b3:17 556        /system/lib/libstagefright_omx.so
09-13 14:18:43.836  7082  7082 W art     : b55d1000-b560c000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
,09-13 14:18:43.846  7082  7082 W art     : b560c000-b560d000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
09-13 14:18:43.846  7082  7082 W art     : b560d000-b560e000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
09-13 14:18:43.846  7082  7082 W art     : b560f000-b5616000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
,09-13 14:18:43.846  7082  7082 W art     : b5616000-b5617000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5617000-b5618000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
09-13 14:18:43.846  7082  7082 W art     : b5618000-b5619000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
09-13 14:18:43.846  7082  7082 W art     : b5619000-b561a000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b561a000-b5631000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
09-13 14:18:43.846  7082  7082 W art     : b5631000-b5632000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5632000-b5635000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
09-13 14:18:43.846  7082  7082 W art     : b5635000-b5636000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
,09-13 14:18:43.846  7082  7082 W art     : b5636000-b5655000 r-xp 00000000 b3:17 713        /system/lib/libRScpp.so
09-13 14:18:43.846  7082  7082 W art     : b5655000-b5656000 r--p 0001e000 b3:17 713        /system/lib/libRScpp.so
09-13 14:18:43.846  7082  7082 W art     : b5656000-b5657000 rw-p 0001f000 b3:17 713        /system/lib/libRScpp.so
09-13 14:18:43.846  7082  7082 W art     : b5657000-b5695000 r-xp 00000000 b3:17 2430       /system/lib/libRS.so
09-13 14:18:43.846  7082  7082 W art     : b5695000-b5696000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5696000-b5698000 r--p 0003e000 b3:17 2430       /system/lib/libRS.so
09-13 14:18:43.846  7082  7082 W art     : b5698000-b5699000 rw-p 00040000 b3:17 2430       /system/lib/libRS.so
09-13 14:18:43.846  7082  7082 W art     : b569a000-b56a1000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 14:18:43.846  7082  7082 W art     : b56a1000-b56a2000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 14:18:43.846  7082  7082 W art     : b56a2000-b56a3000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
09-13 14:18:43.846  7082  7082 W art     : b56a4000-b56a7000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 14:18:43.846  7082  7082 W art     : b56a7000-b56a8000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
,09-13 14:18:43.846  7082  7082 W art     : b56a8000-b56a9000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
09-13 14:18:43.846  7082  7082 W art     : b56a9000-b56af000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 14:18:43.846  7082  7082 W art     : b56af000-b56b0000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b56b0000-b56b1000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 14:18:43.846  7082  7082 W art     : b56b1000-b56b2000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
09-13 14:18:43.846  7082  7082 W art     : b56b2000-b56bb000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
09-13 14:18:43.846  7082  7082 W art     : b56bb000-b56bc000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
09-13 14:18:43.846  7082  7082 W art     : b56bc000-b56bd000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
09-13 14:18:43.846  7082  7082 W art     : b56bd000-b574e000 r-xp 00000000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 14:18:43.846  7082  7082 W art     : b574e000-b574f000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b574f000-b575a000 r--p 00091000 b3:17 2481       /system/lib/libcrypto-rename.so
,09-13 14:18:43.846  7082  7082 W art     : b575a000-b575b000 rw-p 0009c000 b3:17 2481       /system/lib/libcrypto-rename.so
09-13 14:18:43.846  7082  7082 W art     : b575c000-b576e000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
09-13 14:18:43.846  7082  7082 W art     : b576e000-b576f000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
09-13 14:18:43.846  7082  7082 W art     : b576f000-b5770000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
09-13 14:18:43.846  7082  7082 W art     : b5771000-b5776000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
09-13 14:18:43.846  7082  7082 W art     : b5776000-b5777000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
09-13 14:18:43.846  7082  7082 W art     : b5777000-b5778000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
09-13 14:18:43.846  7082  7082 W art     : b5779000-b57e6000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
09-13 14:18:43.846  7082  7082 W art     : b57e6000-b57e7000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b57e7000-b57e9000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
09-13 14:18:43.846  7082  7082 W art     : b57e9000-b57ea000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
,09-13 14:18:43.846  7082  7082 W art     : b57ea000-b57eb000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b57eb000-b57f2000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 14:18:43.846  7082  7082 W art     : b57f2000-b57f3000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 14:18:43.846  7082  7082 W art     : b57f3000-b57f4000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
09-13 14:18:43.846  7082  7082 W art     : b57f5000-b5875000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 14:18:43.846  7082  7082 W art     : b5875000-b5876000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5876000-b5877000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 14:18:43.846  7082  7082 W art     : b5877000-b5878000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
09-13 14:18:43.846  7082  7082 W art     : b5878000-b588f000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b588f000-b58c6000 r-xp 00000000 b3:17 3244       /system/vendor/lib/libqc-opt.so
,09-13 14:18:43.846  7082  7082 W art     : b58c6000-b58c7000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 14:18:43.846  7082  7082 W art     : b58c7000-b58c8000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
09-13 14:18:43.846  7082  7082 W art     : b58c8000-b58e4000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 14:18:43.846  7082  7082 W art     : b58e4000-b58e5000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 14:18:43.846  7082  7082 W art     : b58e5000-b58e6000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
09-13 14:18:43.846  7082  7082 W art     : b58e7000-b5948000 r-xp 00000000 b3:17 2050       /system/lib/libft2.so
09-13 14:18:43.846  7082  7082 W art     : b5948000-b594a000 r--p 00060000 b3:17 2050       /system/lib/libft2.so
09-13 14:18:43.846  7082  7082 W art     : b594a000-b594b000 rw-p 00062000 b3:17 2050       /system/lib/libft2.so
09-13 14:18:43.846  7082  7082 W art     : b594c000-b5971000 r-xp 00000000 b3:17 126        /system/lib/libpng.so
09-13 14:18:43.846  7082  7082 W art     : b5971000-b5972000 r--p 00024000 b3:17 126        /system/lib/libpng.so
09-13 14:18:43.846  7082  7082 W art     : b5972000-b5973000 rw-p 00025000 b3:17 126        /system/lib/libpng.so
09-13 14:18:43.846  7082  7082 W art     : b5974000-b597c000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
,09-13 14:18:43.846  7082  7082 W art     : b597c000-b597e000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 14:18:43.846  7082  7082 W art     : b597e000-b597f000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
09-13 14:18:43.846  7082  7082 W art     : b5980000-b5983000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
09-13 14:18:43.846  7082  7082 W art     : b5983000-b5984000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
09-13 14:18:43.846  7082  7082 W art     : b5984000-b5985000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
09-13 14:18:43.846  7082  7082 W art     : b5985000-b5989000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
09-13 14:18:43.846  7082  7082 W art     : b5989000-b598a000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b598a000-b598b000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
09-13 14:18:43.846  7082  7082 W art     : b598b000-b598c000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
09-13 14:18:43.846  7082  7082 W art     : b598c000-b599c000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
,09-13 14:18:43.846  7082  7082 W art     : b599c000-b599d000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
09-13 14:18:43.846  7082  7082 W art     : b599d000-b599e000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
09-13 14:18:43.846  7082  7082 W art     : b599e000-b59e4000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b59e4000-b59ed000 r-xp 00000000 b3:17 982        /system/lib/libbase.so
09-13 14:18:43.846  7082  7082 W art     : b59ed000-b59ee000 r--p 00008000 b3:17 982        /system/lib/libbase.so
09-13 14:18:43.846  7082  7082 W art     : b59ee000-b59ef000 rw-p 00009000 b3:17 982        /system/lib/libbase.so
09-13 14:18:43.846  7082  7082 W art     : b59f0000-b59f5000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
09-13 14:18:43.846  7082  7082 W art     : b59f5000-b59f6000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
09-13 14:18:43.846  7082  7082 W art     : b59f6000-b59f7000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
,09-13 14:18:43.846  7082  7082 W art     : b59f7000-b59fa000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 14:18:43.846  7082  7082 W art     : b59fa000-b59fb000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b59fb000-b59fc000 r--p 00003000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 14:18:43.846  7082  7082 W art     : b59fc000-b59fd000 rw-p 00004000 b3:17 2406       /system/lib/libstagefright_http_support.so
09-13 14:18:43.846  7082  7082 W art     : b59fe000-b5a16000 r-xp 00000000 b3:17 2789       /system/lib/libstagefri
09-13 14:18:43.846  7082  7082 W art     : ght_foundation.so
09-13 14:18:43.846  7082  7082 W art     : b5a16000-b5a17000 ---p 00000000 00:00 0 
,09-13 14:18:43.846  7082  7082 W art     : b5a17000-b5a18000 r--p 00018000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 14:18:43.846  7082  7082 W art     : b5a18000-b5a19000 rw-p 00019000 b3:17 2789       /system/lib/libstagefright_foundation.so
09-13 14:18:43.846  7082  7082 W art     : b5a19000-b5a1a000 rw-p 00000000 00:
09-13 14:18:43.846  7082  7082 W art     : 00 0          [anon:linker_alloc_vector]
09-13 14:18:43.846  7082  7082 W art     : b5a1a000-b5bb4000 r-xp 00000000 b3:17 604        /system/lib/libstagefright.so
09-13 14:18:43.846  7082  7082 W art     : b5bb4000-b5bb5000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5bb5000-b5bc2000 r--p 0019a000 b3:17 604        /system/lib/libstagefright.so
,09-13 14:18:43.846  7082  7082 W art     : b5bc2000-b5bc3000 rw-p 001a7000 b3:17 604        /system/
09-13 14:18:43.846  7082  7082 W art     : lib/libstagefright.so
09-13 14:18:43.846  7082  7082 W art     : b5bc3000-b5bc7000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
09-13 14:18:43.846  7082  7082 W art     : b5bc7000-b5bc8000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5bc8000-b5bc9000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
09-13 14:18:43.846  7082  7082 W art     : b5bc9000-b5bca000 rw-p 00005000 b3:17 2676       /system/lib/libp
09-13 14:18:43.846  7082  7082 W art     : ersona.so
09-13 14:18:43.846  7082  7082 W art     : b5bca000-b5bdd000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
09-13 14:18:43.846  7082  7082 W art     : b5bdd000-b5bde000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
09-13 14:18:43.846  7082  7082 W art     : b5bde000-b5bdf000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
09-13 14:18:43.846  7082  7082 W art     : b5be0000-b5c2b000 r
09-13 14:18:43.846  7082  7082 W art     : -xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
09-13 14:18:43.846  7082  7082 W art     : b5c2b000-b5c2c000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
,09-13 14:18:43.846  7082  7082 W art     : b5c2c000-b5c2d000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
09-13 14:18:43.846  7082  7082 W art     : b5c2d000-b5c2f000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5c30000-b5c41000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 14:18:43.846  7082  7082 W art     : b5c41000-b5c42000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5c42000-b5c43000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 14:18:43.846  7082  7082 W art     : b5c43000-b5c44000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
09-13 14:18:43.846  7082  7082 W art     : b5c44000-b5c45000 r--p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5c45000-b5c4f000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
09-13 14:18:43.846  7082  7082 W art     : b5c4f000-b5c51000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
09-13 14:18:43.846  7082  7082 W art     : b5c51000-b5c52000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
09-13 14:18:43.846  7082  7082 W art     : b5c52000-b5c6b000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
,09-13 14:18:43.846  7082  7082 W art     : b5c6b000-b5c6c000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
09-13 14:18:43.846  7082  7082 W art     : b5c6c000-b5c6f000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
09-13 14:18:43.846  7082  7082 W art     : b5c6f000-b5c73000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5c73000-b5ce7000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
09-13 14:18:43.846  7082  7082 W art     : b5ce7000-b5ce8000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5ce8000-b5ceb000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
09-13 14:18:43.846  7082  7082 W art     : b5ceb000-b5cec000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
09-13 14:18:43.846  7082  7082 W art     : b5cec000-b5ced000 r--p 00000000 00:00 0 
,09-13 14:18:43.846  7082  7082 W art     : b5ced000-b5cf0000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
09-13 14:18:43.846  7082  7082 W art     : b5cf0000-b5cf1000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
09-13 14:18:43.846  7082  7082 W art     : b5cf1000-b5cf2000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
09-13 14:18:43.846  7082  7082 W art     : b5cf2000-b5cf3000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b5cf3000-b5cf8000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 14:18:43.846  7082  7082 W art     : b5cf8000-b5cf9000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 14:18:43.846  7082  7082 W art     : b5cf9000-b5cfa000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
09-13 14:18:43.846  7082  7082 W art     : b5cfa000-b5cfb000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b5cfb000-b5cfe000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
,09-13 14:18:43.846  7082  7082 W art     : b5cfe000-b5cff000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 14:18:43.846  7082  7082 W art     : b5cff000-b5d00000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
09-13 14:18:43.846  7082  7082 W art     : b5d00000-b5d01000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:18:43.846  7082  7082 W art     : b5d01000-b5d05000 r-xp 00000000 b3:17 2691       /system/lib/libnativebridge.so
09-13 14:18:43.846  7082  7082 W art     : b5d05000-b5d06000 r--p 00003000 b3:17 2691       /system/lib/libnativebridge.so
09-13 14:18:43.846  7082  7082 W art     : b5d06000-b5d07000 rw-p 00004000 b3:17 2691       /system/lib/libnativebridge.so
09-13 14:18:43.846  7082  7082 W art     : b5d07000-b5d08000 r--p 00000000 00:00 0          [anon:linker_alloc]
,09-13 14:18:43.846  7082  7082 W art     : b5d08000-b5d0c000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 14:18:43.846  7082  7082 W art     : b5d0c000-b5d0d000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 14:18:43.846  7082  7082 W art     : b5d0d000-b5d0e000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
09-13 14:18:43.846  7082  7082 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b5d0f000-b5d1d000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
09-13 14:18:43.846  7082  7082 W art     : b5d1d000-b5d1e000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b5d1e000-b5d1f000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
09-13 14:18:43.846  7082  7082 W art     : b5d1f000-b5d20000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
09-13 14:18:43.846  7082  7082 W art     : b5d20000-b5d2a000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
,09-13 14:18:43.846  7082  7082 W art     : b5d2a000-b5d2d000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 14:18:43.846  7082  7082 W art     : b5d2d000-b5d2e000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
09-13 14:18:43.846  7082  7082 W art     : b5d2e000-b5d2f000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b5d2f000-b5d39000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
09-13 14:18:43.846  7082  7082 W art     : b5d39000-b5d3c000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
09-13 14:18:43.846  7082  7082 W art     : b5d3c000-b5d3d000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
09-13 14:18:43.846  7082  7082 W art     : b5d3d000-b5d41000 r-xp 00000000 b3:17 1217       /system/lib/libnetd_client.so
09-13 14:18:43.846  7082  7082 W art     : b5d41000-b5d42000 r--p 00003000 b3:17 1217       /system/lib/libnetd_client.so
,09-13 14:18:43.846  7082  7082 W art     : b5d42000-b5d43000 rw-p 00004000 b3:17 1217       /system/lib/libnetd_client.so
09-13 14:18:43.846  7082  7082 W art     : b5d43000-b5d44000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b5d44000-b5d51000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
09-13 14:18:43.846  7082  7082 W art     : b5d51000-b5d53000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
09-13 14:18:43.846  7082  7082 W art     : b5d53000-b5d54000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
09-13 14:18:43.846  7082  7082 W art     : b5d54000-b6166000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
09-13 14:18:43.846  7082  7082 W art     : b6166000-b6167000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6167000-b6170000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
,09-13 14:18:43.846  7082  7082 W art     : b6170000-b6174000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
09-13 14:18:43.846  7082  7082 W art     : b6174000-b6175000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6175000-b617c000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
09-13 14:18:43.846  7082  7082 W art     : b617c000-b617d000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
09-13 14:18:43.846  7082  7082 W art     : b617d000-b617e000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
09-13 14:18:43.846  7082  7082 W art     : b617e000-b617f000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b617f000-b619a000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
,09-13 14:18:43.846  7082  7082 W art     : b619a000-b619b000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
09-13 14:18:43.846  7082  7082 W art     : b619b000-b619c000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
09-13 14:18:43.846  7082  7082 W art     : b619c000-b619d000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.846  7082  7082 W art     : b619d000-b61e9000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 14:18:43.846  7082  7082 W art     : b61e9000-b61ea000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b61ea000-b61eb000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 14:18:43.846  7082  7082 W art     : b61eb000-b61ec000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
09-13 14:18:43.846  7082  7082 W art     : b61ec000-b61ed000 r--p 00000000 00:00 0          [anon:linker_alloc]
,09-13 14:18:43.846  7082  7082 W art     : b61ed000-b61f1000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
09-13 14:18:43.846  7082  7082 W art     : b61f1000-b61f2000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b61f2000-b61f3000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
09-13 14:18:43.846  7082  7082 W art     : b61f3000-b61f4000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
09-13 14:18:43.846  7082  7082 W art     : b61f4000-b622c000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
09-13 14:18:43.846  7082  7082 W art     : b622c000-b622d000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
09-13 14:18:43.846  7082  7082 W art     : b622d000-b622e000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
09-13 14:18:43.846  7082  7082 W art     : b622e000-b622f000 r--p 00000000 00:00 0          [anon:linker_alloc]
,09-13 14:18:43.846  7082  7082 W art     : b622f000-b62ce000 r-xp 00000000 b3:17 1063       /system/lib/libmedia.so
09-13 14:18:43.846  7082  7082 W art     : b62ce000-b62ec000 r--p 0009e000 b3:17 1063       /system/lib/libmedia.so
09-13 14:18:43.846  7082  7082 W art     : b62ec000-b62ed000 rw-p 000bc000 b3:17 1063       /system/lib/libmedia.so
09-13 14:18:43.846  7082  7082 W art     : b62ed000-b6460000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
09-13 14:18:43.846  7082  7082 W art     : b6460000-b646b000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
09-13 14:18:43.846  7082  7082 W art     : b646b000-b646c000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
09-13 14:18:43.846  7082  7082 W art     : b646c000-b6583000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
09-13 14:18:43.846  7082  7082 W art     : b6583000-b658e000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
,09-13 14:18:43.846  7082  7082 W art     : b658e000-b658f000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
09-13 14:18:43.846  7082  7082 W art     : b658f000-b6593000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6593000-b65b7000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
09-13 14:18:43.846  7082  7082 W art     : b65b7000-b65b9000 r--p 00023000 b3:17 400        /system/lib/libssl.so
09-13 14:18:43.846  7082  7082 W art     : b65b9000-b65ba000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
09-13 14:18:43.846  7082  7082 W art     : b65ba000-b6660000 r-xp 00000000 b3:17 128        /system/lib/libcrypto.so
09-13 14:18:43.846  7082  7082 W art     : b6660000-b666d000 r--p 000a5000 b3:17 128        /system/lib/libcrypto.so
09-13 14:18:43.846  7082  7082 W art     : b666d000-b666e000 rw-p 000b2000 b3:17 128        /system/lib/libcrypto.so
,09-13 14:18:43.846  7082  7082 W art     : b666e000-b666f000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b666f000-b66c2000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
09-13 14:18:43.846  7082  7082 W art     : b66c2000-b66c3000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b66c3000-b66c4000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
09-13 14:18:43.846  7082  7082 W art     : b66c4000-b66c5000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
09-13 14:18:43.846  7082  7082 W art     : b66c5000-b66ca000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b66ca000-b66dc000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
09-13 14:18:43.846  7082  7082 W art     : b66dc000-b66dd000 ---p 00000000 00:00 0 
,09-13 14:18:43.846  7082  7082 W art     : b66dd000-b66de000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
09-13 14:18:43.846  7082  7082 W art     : b66de000-b66df000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
09-13 14:18:43.846  7082  7082 W art     : b66df000-b66e6000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 14:18:43.846  7082  7082 W art     : b66e6000-b66e7000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
09-13 14:18:43.846  7082  7082 W art     : b66e7000-b66e8000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
,09-13 14:18:43.846  7082  7082 W art     : b66e8000-b66e9000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b66e9000-b66ec000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
09-13 14:18:43.846  7082  7082 W art     : b66ec000-b66ed000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
09-13 14:18:43.846  7082  7082 W art     : b66ed000-b66ee000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
09-13 14:18:43.846  7082  7082 W art     : b66ee000-b66f2000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
09-13 14:18:43.846  7082  7082 W art     : b66f2000-b66f3000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
09-13 14:18:43.846  7082  7082 W art     : b66f3000-b66f4000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
09-13 14:18:43.846  7082  7082 W art     : b66f4000-b6702000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
,09-13 14:18:43.846  7082  7082 W art     : b6702000-b6703000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6703000-b6704000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
09-13 14:18:43.846  7082  7082 W art     : b6704000-b6705000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
09-13 14:18:43.846  7082  7082 W art     : b6705000-b670e000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 14:18:43.846  7082  7082 W art     : b670e000-b670f000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 14:18:43.846  7082  7082 W art     : b670f000-b6710000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
09-13 14:18:43.846  7082  7082 W art     : b6710000-b6776000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
,09-13 14:18:43.846  7082  7082 W art     : b6776000-b6777000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6777000-b6779000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
09-13 14:18:43.846  7082  7082 W art     : b6779000-b6782000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
09-13 14:18:43.846  7082  7082 W art     : b6782000-b6785000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6785000-b681c000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
09-13 14:18:43.846  7082  7082 W art     : b681c000-b681e000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
09-13 14:18:43.846  7082  7082 W art     : b681e000-b681f000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
09-13 14:18:43.846  7082  7082 W art     : b681f000-b6820000 rw-p 00000000 00:00 0 
,09-13 14:18:43.846  7082  7082 W art     : b6820000-b6b3e000 r-xp 00000000 b3:17 615        /system/lib/libskia.so
09-13 14:18:43.846  7082  7082 W art     : b6b3e000-b6b3f000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6b3f000-b6b5a000 r--p 0031e000 b3:17 615        /system/lib/libskia.so
09-13 14:18:43.846  7082  7082 W art     : b6b5a000-b6b5e000 rw-p 00339000 b3:17 615        /system/lib/libskia.so
09-13 14:18:43.846  7082  7082 W art     : b6b5e000-b6b63000 rw-p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6b63000-b6b6b000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 14:18:43.846  7082  7082 W art     : b6b6b000-b6b6c000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
09-13 14:18:43.846  7082  7082 W art     : b6b6c000-b6b6d000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
,09-13 14:18:43.846  7082  7082 W art     : b6b6d000-b6b9b000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
09-13 14:18:43.846  7082  7082 W art     : b6b9b000-b6b9c000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6b9c000-b6ba3000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
09-13 14:18:43.846  7082  7082 W art     : b6ba3000-b6ba4000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
09-13 14:18:43.846  7082  7082 W art     : b6ba4000-b6bea000 r-xp 00000000 b3:17 2880       /system/lib/libinputflinger.so
09-13 14:18:43.846  7082  7082 W art     : b6bea000-b6beb000 ---p 00000000 00:00 0 
09-13 14:18:43.846  7082  7082 W art     : b6beb000-b6bee000 r--p 00046000 b3:17 2880       /system/lib/libinputflinger.so
09-13 14:18:43.846  7082  7082 W art     : b6bee000-b6bef000 rw-p 00049000 b3:17 2880       /system/lib/libinputflinger.so
,09-13 14:18:43.856  7082  7082 W art     : b6bef000-b6c0a000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
09-13 14:18:43.856  7082  7082 W art     : b6c0a000-b6c0e000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
09-13 14:18:43.856  7082  7082 W art     : b6c0e000-b6c0f000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
09-13 14:18:43.856  7082  7082 W art     : b6c0f000-b6c5c000 r-xp 00000000 b3:17 2708       /system/lib/libgui.so
09-13 14:18:43.856  7082  7082 W art     : b6c5c000-b6c5d000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6c5d000-b6c69000 r--p 0004d000 b3:17 2708       /system/lib/libgui.so
09-13 14:18:43.856  7082  7082 W art     : b6c69000-b6c6a000 rw-p 00059000 b3:17 2708       /system/lib/libgui.so
09-13 14:18:43.856  7082  7082 W art     : b6c6a000-b6c77000 r-xp 00000000 b3:17 1126       /system/lib/libui.so
,09-13 14:18:43.856  7082  7082 W art     : b6c77000-b6c78000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6c78000-b6c79000 r--p 0000d000 b3:17 1126       /system/lib/libui.so
09-13 14:18:43.856  7082  7082 W art     : b6c79000-b6c7a000 rw-p 0000e000 b3:17 1126       /system/lib/libui.so
09-13 14:18:43.856  7082  7082 W art     : b6c7a000-b6c82000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
09-13 14:18:43.856  7082  7082 W art     : b6c82000-b6c83000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6c83000-b6c84000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
09-13 14:18:43.856  7082  7082 W art     : b6c84000-b6c85000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
09-13 14:18:43.856  7082  7082 W art     : b6c85000-b6c8c000 r-xp 00000000 b3:17 272        /system/lib/libnativehelper.so
,09-13 14:18:43.856  7082  7082 W art     : b6c8c000-b6c8d000 r--p 00006000 b3:17 272        /system/lib/libnativehelper.so
09-13 14:18:43.856  7082  7082 W art     : b6c8d000-b6c8e000 rw-p 00007000 b3:17 272        /system/lib/libnativehelper.so
09-13 14:18:43.856  7082  7082 W art     : b6c8e000-b6ca2000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
09-13 14:18:43.856  7082  7082 W art     : b6ca2000-b6ca4000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
09-13 14:18:43.856  7082  7082 W art     : b6ca4000-b6ca5000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
09-13 14:18:43.856  7082  7082 W art     : b6ca5000-b6ccd000 r-xp 00000000 b3:17 2758       /system/lib/libandroidfw.so
09-13 14:18:43.856  7082  7082 W art     : b6ccd000-b6ccf000 r--p 00027000 b3:17 2758       /system/lib/libandroidfw.so
,09-13 14:18:43.856  7082  7082 W art     : b6ccf000-b6cd0000 rw-p 00029000 b3:17 2758       /system/lib/libandroidfw.so
09-13 14:18:43.856  7082  7082 W art     : b6cd0000-b6cd3000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
09-13 14:18:43.856  7082  7082 W art     : b6cd3000-b6cd4000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
09-13 14:18:43.856  7082  7082 W art     : b6cd4000-b6cd5000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
09-13 14:18:43.856  7082  7082 W art     : b6cd5000-b6cde000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
09-13 14:18:43.856  7082  7082 W art     : b6cde000-b6cdf000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
09-13 14:18:43.856  7082  7082 W art     : b6cdf000-b6ce0000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
09-13 14:18:43.856  7082  7082 W art     : b6ce0000-b6d00000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
,09-13 14:18:43.856  7082  7082 W art     : b6d00000-b6d01000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
09-13 14:18:43.856  7082  7082 W art     : b6d01000-b6d02000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
09-13 14:18:43.856  7082  7082 W art     : b6d02000-b6d75000 r-xp 00000000 b3:17 1016       /system/lib/libc.so
09-13 14:18:43.856  7082  7082 W art     : b6d75000-b6d79000 r--p 00072000 b3:17 1016       /system/lib/libc.so
09-13 14:18:43.856  7082  7082 W art     : b6d79000-b6d7c000 rw-p 00076000 b3:17 1016       /system/lib/libc.so
09-13 14:18:43.856  7082  7082 W art     : b6d7c000-b6d86000 rw-p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6d86000-b6e0e000 r-xp 00000000 b3:17 2266       /system/lib/libc++.so
,09-13 14:18:43.856  7082  7082 W art     : b6e0e000-b6e0f000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6e0f000-b6e13000 r--p 00088000 b3:17 2266       /system/lib/libc++.so
09-13 14:18:43.856  7082  7082 W art     : b6e13000-b6e14000 rw-p 0008c000 b3:17 2266       /system/lib/libc++.so
09-13 14:18:43.856  7082  7082 W art     : b6e14000-b6e15000 rw-p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6e15000-b6e3e000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
09-13 14:18:43.856  7082  7082 W art     : b6e3e000-b6e3f000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6e3f000-b6e42000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
09-13 14:18:43.856  7082  7082 W art     : b6e42000-b6e43000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
,09-13 14:18:43.856  7082  7082 W art     : b6e43000-b6f1d000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 14:18:43.856  7082  7082 W art     : b6f1d000-b6f24000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 14:18:43.856  7082  7082 W art     : b6f24000-b6f2c000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
09-13 14:18:43.856  7082  7082 W art     : b6f2c000-b6f2d000 rw-p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6f2d000-b6f2e000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:18:43.856  7082  7082 W art     : b6f2e000-b6f2f000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
,09-13 14:18:43.856  7082  7082 W art     : b6f2f000-b6f30000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.856  7082  7082 W art     : b6f30000-b6f33000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.856  7082  7082 W art     : b6f33000-b6f58000 r-xp 00000000 b3:17 726        /system/lib/libbinder.so
09-13 14:18:43.856  7082  7082 W art     : b6f58000-b6f59000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6f59000-b6f60000 r--p 00025000 b3:17 726        /system/lib/libbinder.so
09-13 14:18:43.856  7082  7082 W art     : b6f60000-b6f61000 rw-p 0002c000 b3:17 726        /system/lib/libbinder.so
09-13 14:18:43.856  7082  7082 W art     : b6f61000-b6f68000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
,09-13 14:18:43.856  7082  7082 W art     : b6f68000-b6f69000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
09-13 14:18:43.856  7082  7082 W art     : b6f69000-b6f6a000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
09-13 14:18:43.856  7082  7082 W art     : b6f6a000-b6f6b000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.856  7082  7082 W art     : b6f6b000-b6f83000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
09-13 14:18:43.856  7082  7082 W art     : b6f83000-b6f84000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6f84000-b6f85000 r--p 00018000 b3:17 918        /system/lib/libutils.so
,09-13 14:18:43.856  7082  7082 W art     : b6f85000-b6f86000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
09-13 14:18:43.856  7082  7082 W art     : b6f86000-b6f94000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
09-13 14:18:43.856  7082  7082 W art     : b6f94000-b6f95000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6f95000-b6f96000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
09-13 14:18:43.856  7082  7082 W art     : b6f96000-b6f97000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
09-13 14:18:43.856  7082  7082 W art     : b6f97000-b6f98000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,09-13 14:18:43.856  7082  7082 W art     : b6f98000-b6f9a000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.856  7082  7082 W art     : b6f9a000-b6f9b000 rw-p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.856  7082  7082 W art     : b6f9b000-b6f9c000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
09-13 14:18:43.856  7082  7082 W art     : b6f9c000-b6f9d000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
09-13 14:18:43.856  7082  7082 W art     : b6f9d000-b6f9e000 r--p 00000000 00:00 0          [anon:linker_alloc]
09-13 14:18:43.856  7082  7082 W art     : b6f9e000-b6fbe000 r--s 00000000 00:0b 6572       /dev/__properties__
,09-13 14:18:43.856  7082  7082 W art     : b6fbe000-b6fbf000 r--p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6fbf000-b6fc0000 ---p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6fc0000-b6fc2000 rw-p 00000000 00:00 0          [anon:thread signal stack]
09-13 14:18:43.856  7082  7082 W art     : b6fc2000-b6fc3000 r-xp 00000000 00:00 0          [sigpage]
09-13 14:18:43.856  7082  7082 W art     : b6fc3000-b6fde000 r-xp 00000000 b3:17 341        /system/bin/linker
09-13 14:18:43.856  7082  7082 W art     : b6fde000-b6fdf000 r--p 0001a000 b3:17 341        /system/bin/linker
,09-13 14:18:43.856  7082  7082 W art     : b6fdf000-b6fe1000 rw-p 0001b000 b3:17 341        /system/bin/linker
09-13 14:18:43.856  7082  7082 W art     : b6fe1000-b6fe3000 rw-p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : b6fe3000-b6fe8000 r-xp 00000000 b3:17 978        /system/bin/app_process32
09-13 14:18:43.856  7082  7082 W art     : b6fe8000-b6fe9000 r--p 00004000 b3:17 978        /system/bin/app_process32
09-13 14:18:43.856  7082  7082 W art     : b6fe9000-b6fea000 rw-p 00000000 00:00 0 
09-13 14:18:43.856  7082  7082 W art     : be924000-be945000 rw-p 00000000 00:00 0          [stack]
,09-13 14:18:43.856  7082  7082 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,09-13 14:18:43.916  7082  7082 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 14:18:43.966  7082  7082 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 14:18:43.976  7082  7082 E AffinityControl: AffinityControl: registerfunction enter
,09-13 14:18:43.986  7082  7082 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 14:18:44.006   765  2529 D PackageManager: START PACKAGE DELETE: observer{25241997}
09-13 14:18:44.006   765  2529 D PackageManager: pkg{<packageName>}
09-13 14:18:44.006   765  2529 D PackageManager: user{0}
09-13 14:18:44.006   765  2529 D PackageManager: caller{2000}
09-13 14:18:44.006   765  2529 D PackageManager: flags{2}
09-13 14:18:44.006   765  2529 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 14:18:44.006   765  2529 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 14:18:44.006   765  2529 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 14:18:44.006   765  2529 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 14:18:44.006   765  2529 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-13 14:18:44.006   765   917 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-13 14:18:44.006   765   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 14:18:44.006   765   917 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 14:18:44.006   765   917 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-13 14:18:44.016   765   917 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 14:18:44.016   765   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
,09-13 14:18:44.016   765   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-13 14:18:44.016   765   917 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
,09-13 14:18:44.016   765   839 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
09-13 14:18:44.016   765   839 I ActivityManager: Killing 6650:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-13 14:18:44.016   765   917 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
09-13 14:18:44.016   765   917 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,09-13 14:18:44.016   765   839 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 14:18:44.016   765   839 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 14:18:44.026   765   839 D ActivityManager: mDVFSHelper.acquire()
,09-13 14:18:44.036   765   917 D AASAinstall: there is not AASApackages.xml file
,09-13 14:18:44.066   765  1653 D GraphicsStats: Buffer count: 5
,09-13 14:18:44.066   765   786 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2e3d189)
,09-13 14:18:44.066   765  1613 I WindowState: WIN DEATH: Window{d9f73b7 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 14:18:44.066   765  1333 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:44.066   292   837 I SurfaceFlinger: id=24 Removed NainActivit (6/8)
,09-13 14:18:44.066   765  1333 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:44.076   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
09-13 14:18:44.076   292   350 I SurfaceFlinger: id=24 Removed NainActivit (-2/8)
09-13 14:18:44.076   292   350 I SurfaceFlinger: id=24 Removed NainActivit (-2/8)
,09-13 14:18:44.076   765  1333 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 14:18:44.076   765  1613 D InputDispatcher: Focus left window: 6650
,09-13 14:18:44.346   765   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,09-13 14:18:44.376   765  3518 D PowerManagerService: [api] setMasterBrightnessLimit : minBrightnss : -1  maxBrightness : 255 (uid: 1000 pid: 765)
09-13 14:18:44.376   765  3518 D PowerManagerService: mDisplayReady: false
09-13 14:18:44.376   765  3518 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,09-13 14:18:44.376   765  3518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1096 com.android.server.ssrm.R.c:-1 com.android.server.ssrm.at.dT:-1 com.android.server.ssrm.at.dS:-1 com.android.server.ssrm.at.run:-1 
09-13 14:18:44.376   765   894 D DisplayPowerController: animateScreenStateChange[0]: target=1
09-13 14:18:44.376   765   894 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
09-13 14:18:44.376   765   894 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
09-13 14:18:44.376   765   894 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ 255))
,09-13 14:18:44.376   765   894 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-13 14:18:44.376   765   894 D PowerManagerService: mDisplayReady: true
09-13 14:18:44.376   765   894 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,09-13 14:18:44.426   765   917 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,09-13 14:18:44.426   765   839 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 14:18:44.426   765   891 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-13 14:18:44.436   765   839 E ActivityManager: Failure starting process com.test.thalitest
09-13 14:18:44.436   765   839 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5275)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5192)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:5030)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:2639)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:3481)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:2595)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4999)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:4960)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:7377)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:9144)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:8767)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:8922)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:461)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:2599)
09-13 14:18:44.436   765   839 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:44.436   765   839 E ActivityManager: 	at android.os.Looper.loop(Looper.java:158)
09-13 14:18:44.436   765   839 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 14:18:44.436   765   839 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 14:18:44.436   327   327 W keystore: ENTER clear_uid from uid 1000 for 10004
,09-13 14:18:44.436   765   891 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
,09-13 14:18:44.436   765   917 I art     : Starting a blocking GC Explicit
09-13 14:18:44.436   765   891 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
09-13 14:18:44.436   765   891 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
09-13 14:18:44.436   765   891 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4351)
,09-13 14:18:44.436   765   839 I ActivityManager:   Force finishing activity ActivityRecord{ee6c87e u0 com.test.thalitest/.MainActivity t169}
,09-13 14:18:44.456   765   891 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13486)
,09-13 14:18:44.456   765   891 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:44.456   765   891 W System.err: 	at android.os.Looper.loop(Looper.java:158)
09-13 14:18:44.456   765   891 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 14:18:44.456   765   891 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 14:18:44.456   765   891 D SecWifiDisplayUtil: Metadata value : none
,09-13 14:18:44.456   765   891 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{3aefd45 V.E...... R.....ID 0,0-0,0}
09-13 14:18:44.456   765   891 D ISSUE_DEBUG: InputChannelName : aa779cb Starting com.test.thalitest
,09-13 14:18:44.476   765   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
09-13 14:18:44.476   292   292 I SurfaceFlinger: id=25 createSurf (1146x1876),1 flag=4, VSBConnecti
,09-13 14:18:44.476   765   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 14:18:44.476   765   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
09-13 14:18:44.476   765   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,09-13 14:18:44.486   292   292 I SurfaceFlinger: id=26 createSurf (1080x1920),1 flag=404, uhalitest
,09-13 14:18:44.486   765   839 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,09-13 14:18:44.486   765   891 D ViewRootImpl: #3 mView = null
,09-13 14:18:44.486   765  3518 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,09-13 14:18:44.496   292   838 I SurfaceFlinger: id=26 Removed uhalitest (7/9)
,09-13 14:18:44.496   292   350 I SurfaceFlinger: id=26 Removed uhalitest (-2/9)
,09-13 14:18:44.496   765   841 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9773c01 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,09-13 14:18:44.496   765   839 D InputDispatcher: Focus entered window: 3591
,09-13 14:18:44.506  1383  1383 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,09-13 14:18:44.506   765   839 D InputDispatcher: Focused application released
,09-13 14:18:44.506   765   891 W WindowManager: Failed looking up window
09-13 14:18:44.506   765   891 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@b0b0c9a does not exist
09-13 14:18:44.506   765   891 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14806)
09-13 14:18:44.506   765   891 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14797)
09-13 14:18:44.506   765   891 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:4614)
09-13 14:18:44.506   765   891 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:196)
09-13 14:18:44.506   765   891 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3748)
09-13 14:18:44.506   765   891 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:6887)
09-13 14:18:44.506   765   891 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:4232)
09-13 14:18:44.506   765   891 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:44.506   765   891 W WindowManager: 	at android.os.Looper.loop(Looper.java:158)
09-13 14:18:44.506   765   891 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 14:18:44.506   765   891 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 14:18:44.506   765  2530 V WindowOrientationListener: setCurrentAppOrientation :1
09-13 14:18:44.506   765  2530 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
,09-13 14:18:44.516   765   891 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:765 uid:1000
,09-13 14:18:44.516   765   891 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 14:18:44.516   765   891 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:765 uid:1000
09-13 14:18:44.516   765   891 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,09-13 14:18:44.516  1761  1761 D Launcher: onRestart, Launcher: 67623309
,09-13 14:18:44.526  1761  1761 D Launcher: onStart, Launcher: 67623309
,09-13 14:18:44.526  4521  4521 V ActivityThread: updateVisibility : ActivityRecord{f6ed139 token=android.os.BinderProxy@26a3964 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-13 14:18:44.526  1761  1761 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
,09-13 14:18:44.536  1761  1761 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-13 14:18:44.536  1761  1761 D Launcher.HomeView: onStart
,09-13 14:18:44.536   292   292 I SurfaceFlinger: id=27 createSurf (1146x1992),1 flag=4, YUIInstallC
,09-13 14:18:44.536   765   839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e6ce5a8 u0 com.sec.intent.action.MAX_BRIGHTNESS_CHANGED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{871aed3 2862:com.android.settings/1000}
,09-13 14:18:44.536   765   783 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
09-13 14:18:44.536   765   783 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
09-13 14:18:44.536   765   765 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.536  1761  1761 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
,09-13 14:18:44.536  1761  1761 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
,09-13 14:18:44.536  2261  2274 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
,09-13 14:18:44.536  1761  1761 V ActivityThread: updateVisibility : ActivityRecord{38b61d token=android.os.BinderProxy@bf412b7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-13 14:18:44.546   765   765 I KnoxTimeoutHandler: Shared devices show user statefalse
,09-13 14:18:44.546   765   765 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,09-13 14:18:44.556   292   292 I SurfaceFlinger: id=28 createSurf (1080x1920),1 flag=4, Mauncher
,09-13 14:18:44.566   765  1253 V WindowStateAnimator: Finishing drawing window Window{9773c01 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 14:18:44.566   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeb63364
,09-13 14:18:44.576   292   292 I SurfaceFlinger: id=29 createSurf (1194x288),1 flag=4, VSBConnecti
,09-13 14:18:44.576   765   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.576   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.576   765   891 D ActivityManager: mDVFSHelper.release()
09-13 14:18:44.576   765   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e3f9c93 u0 com.samsung.android.MtpApplication/.USBConnection t168} time:166209
,09-13 14:18:44.576   765   765 I KnoxTimeoutHandler: SD activityfalse
,09-13 14:18:44.586   292   292 I SurfaceFlinger: id=30 createSurf (145x145),1 flag=4, YUIInstallC
,09-13 14:18:44.606  3591  3591 V ActivityThread: updateVisibility : ActivityRecord{1231e88 token=android.os.BinderProxy@3151122 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,09-13 14:18:44.616   765  1321 V WindowStateAnimator: Finishing drawing window Window{e5693c u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,09-13 14:18:44.616   765  2490 V WindowStateAnimator: Finishing drawing window Window{4cb9f4b u0 d0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: mDrawState=DRAW_PENDING
,09-13 14:18:44.616   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeb63364
,09-13 14:18:44.626   765   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.626   765   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e5700e3 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t167} time:166251
09-13 14:18:44.626   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.626   765   765 I KnoxTimeoutHandler: SD activityfalse
,09-13 14:18:44.636   765  2530 V WindowStateAnimator: Finishing drawing window Window{a7e4ce7 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,09-13 14:18:44.636  3591  3591 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3151122 time:166263
,09-13 14:18:44.636   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeb63364
,09-13 14:18:44.646   292   356 I SurfaceFlinger: id=27 Removed YUIInstallC (6/12)
,09-13 14:18:44.646   292  2003 I SurfaceFlinger: id=27 Removed YUIInstallC (-2/12)
,09-13 14:18:44.646   765   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.646   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,09-13 14:18:44.646   765   765 I KnoxTimeoutHandler: SD activityfalse
,09-13 14:18:44.656   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
,09-13 14:18:44.726   765   917 I art     : Explicit concurrent mark sweep GC freed 132283(6MB) AllocSpace objects, 35(700KB) LOS objects, 27% free, 42MB/58MB, paused 1.620ms total 277.845ms
,09-13 14:18:44.746   765   917 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 14:18:44.746   765   917 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
,09-13 14:18:44.756   765   917 D AASAinstall: there is not AASApackages.xml file
,09-13 14:18:44.756   765   917 D PackageManager: result of delete: 1{25241997}
,09-13 14:18:44.756  7082  7082 I art     : System.exit called, status: 0
09-13 14:18:44.756  7082  7082 I AndroidRuntime: VM exiting with result code 0.
,09-13 14:18:44.766   765  1776 V WindowStateAnimator: Finishing drawing window Window{a3ad79c u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}: mDrawState=DRAW_PENDING
,09-13 14:18:44.766  1761  1761 D Launcher.HomeView: onStop
,09-13 14:18:44.766   765   917 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 14:18:44.766   765   917 D PackageManager: userId{-1}
09-13 14:18:44.766   765   917 D PackageManager: andCode{true}
,09-13 14:18:44.766   292   292 D libEGL  : eglInitialize EGLDisplay = 0xbeb63364
,09-13 14:18:44.766   765   891 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,09-13 14:18:44.766   765   765 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
09-13 14:18:44.776   765   891 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7b954a1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t165} time:166400
,09-13 14:18:44.776   765   765 I KnoxTimeoutHandler: SD activityfalse
,09-13 14:18:44.776   765   917 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,09-13 14:18:44.796  5464  7125 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,09-13 14:18:44.806  5464  7125 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,09-13 14:18:44.806  5464  7125 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,09-13 14:18:44.826   765   839 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 14:18:44.826   765   839 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-13 14:18:44.826   765   839 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,09-13 14:18:44.836   765   765 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.846   765   765 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.846   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.846  1383  1383 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
09-13 14:18:44.846  1383  1383 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,09-13 14:18:44.846   765   891 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.846   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.856   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.856  2021  2021 E SamsungIME: mOCRHelper is null
,09-13 14:18:44.856   765   891 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.856  2146  2403 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.866   765  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.866   765   765 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.866   765   839 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{602249f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b31213 4376:com.samsung.klmsagent/u0a18}
,09-13 14:18:44.876   765   765 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.876   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.876  4376  4376 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Tue Sep 13 14:18:44 GMT+02:00 2016
,09-13 14:18:44.886   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.886  3258  3276 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,09-13 14:18:44.886   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.886   765   765 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.886   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.886  3258  3276 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,09-13 14:18:44.886  3258  3276 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
09-13 14:18:44.886  1743  1743 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 14:18:44.886  3258  3276 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,09-13 14:18:44.886   765  1321 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.896   765   765 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.896  4376  4376 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,09-13 14:18:44.906   765   830 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.906   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.906  4376  4376 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
09-13 14:18:44.906  4376  4376 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 14:18:44.906  4376  4376 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 14:18:44.906  4376  7132 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
09-13 14:18:44.906  4376  7132 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,09-13 14:18:44.916  4376  7132 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
09-13 14:18:44.916  4376  7132 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
09-13 14:18:44.916  4376  7132 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
09-13 14:18:44.916  4376  7132 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 14:18:44.916   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.916   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.916   765  1324 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
09-13 14:18:44.916  4376  7132 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 14:18:44.916   765  1323 V NetworkStats: removeUidsLocked() for UIDs [10004]
09-13 14:18:44.916   765  1324 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-13 14:18:44.916  4376  7132 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 14:18:44.916   765  1323 V NetworkStats: performPollLocked(flags=0x3)
09-13 14:18:44.916   765  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 14:18:44.916   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.926  4376  7132 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
,09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.926  4376  7132 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
09-13 14:18:44.926   765  1253 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{602249f u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{1b78717 765:system/1000}
,09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.926   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.926   765  1323 V NetworkStats: performPollLocked() took 14ms
09-13 14:18:44.926   765  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936  4376  7132 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.936   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.946  4376  7132 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: #################################################################
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: #################################################################
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
09-13 14:18:44.946  4376  7132 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: #################################################################
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: #################################################################
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
09-13 14:18:44.946  4376  7132 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 14:18:44.946  1735  7133 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,09-13 14:18:44.946  1735  7133 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
09-13 14:18:44.946  1735  7133 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
09-13 14:18:44.946  1735  7133 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
,09-13 14:18:44.946  1735  7133 D RegisteredComponentCache: Collect Tech packages for Knox
,09-13 14:18:44.946  4376  7132 W SQLiteOpenHelper: Opened klms.db in read-only mode
,09-13 14:18:44.946   765   765 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.946   765   765 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.946   765  1324 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 14:18:44.946   765  1324 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 14:18:44.946   765   830 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.946   765   830 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.956   765   765 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
09-13 14:18:44.956  4376  7132 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
,09-13 14:18:44.956   765   765 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.966   765  1321 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
09-13 14:18:44.966   765  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 14:18:44.966   765  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 14:18:44.966   765  1321 D SettingsProvider: selectionArgs: false
09-13 14:18:44.966   765  1321 D SettingsProvider: selectionArgs: 10018
09-13 14:18:44.966   765  1321 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,09-13 14:18:44.966   765  1321 D SettingsProvider: ret = -1
09-13 14:18:44.966  4376  7132 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
09-13 14:18:44.966  4376  7132 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
,09-13 14:18:44.966   765  1323 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x71901eae in tid 1323 (NetworkStats)
,09-13 14:18:44.966  2446  2446 E audit_log: File locking failed. error= Bad file descriptor
09-13 14:18:44.976   765   830 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,09-13 14:18:44.976   765  1299 I EventHub: Removing device '/dev/input/event4' due to inotify event
09-13 14:18:44.976   765  1323 F libc    : Failed while talking to debuggerd: Broken pipe
09-13 14:18:44.976  2446  2446 E audit_log: File locking failed. error= Bad file descriptor
,09-13 14:18:45.056   291   291 I ServiceManager: service 'edmnativehelper' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'telecom' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'country_detector' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'sec_location' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'search' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'execute' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'dropbox' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'wallpaper' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'audio' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'DockObserver' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'midi' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'usb' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'serial' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'kiesusb' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'jobscheduler' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'backup' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'appwidget' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'voiceinteraction' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'SecExternalDisplayService' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'diskstats' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'mDNIe' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'AAS' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'MSCS' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'spengestureservice' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'quickconnect' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'samplingprofiler' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'commontime_management' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'dreams' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'graphicsstats' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'print' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'restrictions' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'media_session' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'media_router' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'trust' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'fingerprint' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'launcherapps' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'voip' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'media_projection' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'lpnet' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'imms' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'persona_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'package' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'activity' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'user' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'procstats' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'meminfo' died,
09-13 14:18:45.056   291   291 I ServiceManager: service 'gfxinfo' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'dbinfo' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'cpuinfo' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'permission' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'processinfo' died,
09-13 14:18:45.056   291   291 I ServiceManager: service 'sensorservice' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'mdm.remotedesktop' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'battery' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'usagestats' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'webviewupdate' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'scheduling_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'telephony.registry' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'persona' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'SEAMService' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'media.camera.proxy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'account' died
09-13 14:18:45.056   292  2003 D libEGL  : eglTerminate EGLDisplay = 0xae7606fc
09-13 14:18:45.056   291   291 I ServiceManager: service 'content' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'DirEncryptService' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'LSManager' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'ReactiveService' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'DeviceRootKeyService' died,
09-13 14:18:45.056   291   291 I ServiceManager: service 'EngineeringModeService' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'SatsService' died,
09-13 14:18:45.056   291   291 I ServiceManager: service 'sedenial' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'vibrator' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'tw_toolbox' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'tima' died,
09-13 14:18:45.056   291   291 I ServiceManager: service 'iccc' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'cepproxyks' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'emailksproxy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'CustomFrequencyManagerService' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'consumer_ir' died,
09-13 14:18:45.056   292  2003 D libEGL  : eglTerminate EGLDisplay = 0xae7606fc
09-13 14:18:45.056   291   291 I ServiceManager: service 'alarm' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'context_aware' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'scontext' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'barbeam' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'multiwindow_facade' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'window' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'input' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'bluetooth_manager' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'bluetooth_secure_mode_manager' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'rcp' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'input_method' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'accessibility' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'cover' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'knox_ccm_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'enterprise_license_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'application_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'wifi_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'phone_restriction_policy' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'remoteinjection' died
09-13 14:18:45.076  2446  2446 E audit_log: File locking failed. error= Bad file descriptor
09-13 14:18:45.056   291   291 I ServiceManager: service 'knox_ucsm_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'edm_proxy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'mum_container_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'enterprise_billing_policy' died
09-13 14:18:45.056   292  2003 I SurfaceFlinger: restart the boot-animation @ binderDied,
09-13 14:18:45.056   291   291 I ServiceManager: service 'otp_service' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'enterprise_shared_device_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'knox_timakeystore_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'enterprise_policy' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'statusbar' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'clipboard' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'clipboardEx' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'network_management' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'mount' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'lock_settings' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'deviceidle' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'device_policy' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'harmony_eas_service' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'sdp' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'sdp_log' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'dlp' died,
09-13 14:18:45.056   291   291 I ServiceManager: service 'log_manager_service' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'ABTPersistenceService' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'textservices' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'network_score' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'netstats' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'netpolicy' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'wifip2p' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'wifi' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'wifihs20' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'wifiscanner' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'rttmanager' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'ethernet' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'connectivity' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'sb_service' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'servicediscovery' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'updatelock' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'notification' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'devicestoragemonitor' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'location' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'sec_analytics' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'batterystats' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'appops' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'power' died
,09-13 14:18:45.056   291   291 I ServiceManager: service 'display' died
09-13 14:18:45.056   291   291 I ServiceManager: service 'uimode' died
09-13 14:18:45.056  1743  1743 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
09-13 14:18:45.056  1743  2273 E WifiManager: Channel connection lost
,09-13 14:18:45.066   292   292 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
09-13 14:18:45.066   292   292 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-13 14:18:45.066   321   971 W AudioFlinger: power manager service died !!!
09-13 14:18:45.066   321   971 W AudioFlinger: power manager service died !!!
,09-13 14:18:45.066  1383  1405 W Sensors : sensorservice died [0xaa63fd80]
09-13 14:18:45.066  2146  2592 W Sensors : sensorservice died [0xad415e80]
09-13 14:18:45.066  2146  2402 E WifiManager: Channel connection lost
09-13 14:18:45.066   292   356 I SurfaceFlinger: id=20 Removed DolorFade (11/11)
,09-13 14:18:45.066   292   356 I SurfaceFlinger: id=20 Removed DolorFade (-2/11)
09-13 14:18:45.066   292   356 I SurfaceFlinger: id=5 Removed TtatusBar (10/10)
09-13 14:18:45.066  2862  3245 E WifiManager: Channel connection lost
09-13 14:18:45.066  2438  2438 D HeadsetStateMachine: Proxy object disconnected
,09-13 14:18:45.066   321   972 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb68b41ba in tid 972 (Binder_3)
09-13 14:18:45.066   321   972 F libc    : Unable to open connection to debuggerd: Connection refused
09-13 14:18:45.076  5868  5923 E WifiManager: Channel connection lost
09-13 14:18:45.076  1383  1585 E WifiManager: Channel connection lost
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=2 Removed GocusedStac (9/9),
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/8)
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=4 Removed EimLayer(An (0/7)
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=15 Removed EimLayer(An (0/6)
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=14 Removed EimLayer(Di (4/5)
,09-13 14:18:45.076   292   838 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/5)
09-13 14:18:45.076   292   838 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/5)
09-13 14:18:45.076   325   325 E installd: eof
,09-13 14:18:45.076   325   325 E installd: failed to read size
09-13 14:18:45.076   325   325 I installd: closing connection
09-13 14:18:45.076   292   837 I SurfaceFlinger: id=25 Removed VSBConnecti (4/4)
,09-13 14:18:45.076   292   837 I SurfaceFlinger: id=29 Removed VSBConnecti (3/3)
09-13 14:18:45.076   292   837 I SurfaceFlinger: id=28 Removed Mauncher (1/2)
09-13 14:18:45.076   292   837 I SurfaceFlinger: id=29 Removed VSBConnecti (-2/2)
09-13 14:18:45.076   292   837 I SurfaceFlinger: id=30 Removed YUIInstallC (1/1)
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=5 Removed TtatusBar (-2/1),
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=7 Removed JmageWallpa (0/0)
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/0)
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=28 Removed Mauncher (-2/0)
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=25 Removed VSBConnecti (-2/0)
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=30 Removed YUIInstallC (-2/0),
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=14 Removed EimLayer(Di (-2/0)
09-13 14:18:45.086   292   350 I SurfaceFlinger: id=15 Removed EimLayer(An (-2/0)
09-13 14:18:45.086  1850  2000 E WifiManager: Channel connection lost
09-13 14:18:45.086  1761  2017 W Sensors : sensorservice died [0xad41d140]
,09-13 14:18:45.086  2499  2523 W Sensors : sensorservice died [0xaa632b00]
09-13 14:18:45.086   291   291 I ServiceManager: service 'media.audio_flinger' died
09-13 14:18:45.086  2438  2460 W AudioSystem: AudioFlinger server died!
09-13 14:18:45.086   291   291 I ServiceManager: service 'media.player' died
,09-13 14:18:45.086   291   291 I ServiceManager: service 'media.resource_manager' died
09-13 14:18:45.086   291   291 I ServiceManager: service 'media.camera' died
09-13 14:18:45.086   291   291 I ServiceManager: service 'listen.service' died
09-13 14:18:45.086  5868  5878 W AudioSystem: AudioPolicyService server died!
,09-13 14:18:45.086   291   291 I ServiceManager: service 'media.radio' died
09-13 14:18:45.086   291   291 I ServiceManager: service 'media.sound_trigger_hw' died
09-13 14:18:45.086   291   291 I ServiceManager: service 'media.audio_policy' died,
09-13 14:18:45.086  1850  1927 W AudioSystem: AudioFlinger server died!
09-13 14:18:45.086  1850  1927 W AudioSystem: AudioPolicyService server died!
09-13 14:18:45.086  2484  2498 W AudioSystem: AudioPolicyService server died!
09-13 14:18:45.086  2021  7139 W IMediaDeathNotifier: media server died
,09-13 14:18:45.096  1383  3830 W IMediaDeathNotifier: media server died,
09-13 14:18:45.096  1383  3830 W AudioSystem: AudioPolicyService server died!
09-13 14:18:45.096  1735  1735 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2c42425 in tid 1735 (com.android.nfc)
,09-13 14:18:45.096  1735  1735 F libc    : Unable to open connection to debuggerd: Connection refused
,09-13 14:18:45.096  1909  1919 W Sensors : sensorservice died [0xaad7da40]
09-13 14:18:45.096  2446  2446 E audit_log: File locking failed. error= Bad file descriptor
,09-13 14:18:45.096  4376  7132 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xb2d4347a in tid 7132 (IntentService[K),
,09-13 14:18:45.096  4376  7132 F libc    : Unable to open connection to debuggerd: Connection refused
09-13 14:18:45.096  2446  2446 E audit_log: File locking failed. error= Bad file descriptor
,09-13 14:18:45.096  2862  2872 W Sensors : sensorservice died [0xaad71a00],
,09-13 14:18:45.116   291   291 I ServiceManager: service 'secontroller' died,
09-13 14:18:45.116   291   291 I ServiceManager: service 'nfccontroller' died
09-13 14:18:45.116   291   291 I ServiceManager: service 'nfc' died
,09-13 14:18:45.136   352   352 I Zygote  : Process 4376 exited due to signal (7)
,09-13 14:18:45.146   352   352 I Zygote  : Process 1735 exited due to signal (7)
,09-13 14:18:45.316   292   561 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
09-13 14:18:45.316   292   292 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,09-13 14:18:45.316   290   290 I lowmemorykiller: ActivityManager disconnected
09-13 14:18:45.316   290   290 I lowmemorykiller: Closing Activity Manager data connection
,09-13 14:18:45.566   292   292 I SurfaceFlinger: Disp[0] Orientation 0=>0
,09-13 14:18:45.566   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
,09-13 14:18:45.576   292   561 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c
09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb633a4
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c
,09-13 14:18:45.586   292   292 D libEGL  : eglTerminate EGLDisplay = 0xbeb6338c

```
